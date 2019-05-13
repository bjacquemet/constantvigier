---
title: "{{ replace .Name "-" " " | title }}"
description: "{{ replace .Name "-" " "}}"
date: {{ .Date }}
url: /{{ .Name | title }}/
---