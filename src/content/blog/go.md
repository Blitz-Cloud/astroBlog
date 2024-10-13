---
author: Ionut
pubDatetime: 2024-10-13T22:00:00Z
modDatetime: 2024-10-13T22:00:00Z
title: Go code
slug: go-code
featured: true
draft: false
tags:
  - go
  - poli
  - scripts
description: dirClawler
---

````go
package main

import (
	"fmt"
	"log"
	"os"
	"strings"
	"time"
    "net/url"
)

type fileSysNode struct {
	name    string
	isDir   bool
	folders []fileSysNode
	files   []fileSysNode
}

func template(date, title, slug, content string) (template string) {
	template = `---
author: Ionut
pubDatetime: %s
title: %s
slug: %s
featured: false
draft: false
tags:
  - c
  - poli
description: exemple de cod
---
`
	template = fmt.Sprintf(template, date, title, slug)
	content = strings.ReplaceAll(content, "^M", "\n")
	content = strings.ReplaceAll(content, "void", "int")
	codeBlock := fmt.Sprint("```c\n" + content + "\n```")
  link := fmt.Sprintf("<a href='https://cpp.sh/?source=%s' target='_blank'> Ruleaza codul cu cpp.sh </a>",url.QueryEscape(content))
	template = fmt.Sprint(template + codeBlock + "\n" + link)
	return
}

func explorer(path string) {
	content, err := os.ReadDir(path)
	if err != nil {
		log.Fatal(err)
	}
	for _, file := range content {
		if file.IsDir() {
			path := fmt.Sprintf("%s/%s", path, file.Name())
			explorer(path)
		} else {
			folderName := strings.ReplaceAll(path[53:],"/"," ")
			path := fmt.Sprintf("%s/%s", path, file.Name())
			data, err := os.ReadFile(path)
			if err != nil {
				log.Fatal(err)
			}
			now := time.Now()
			date := fmt.Sprintf("%d-%d-%dT%d:00:00Z", now.Year(), now.Month(), now.Day(), now.Hour()-3)
      title := fmt.Sprintf("%s %s",folderName, file.Name())
			temp := []byte(template(date, title ,file.Name(), string(data)))
			fileName := fmt.Sprintf("blog/src/content/blog/%s.md", file.Name())
			err = os.WriteFile(fileName, temp, 0666)
			if err != nil {
				log.Fatal(err)
			}
		}
	}
}

func main() {
	explorer("facultate/programare/materiale/")
}

````
