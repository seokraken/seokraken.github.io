---
draft: true
date: {{ .Date }}
publishdate: {{ now.Format "2006-01-02" }}
lastmod: {{ now.Format "2006-01-02" }}
title: "{{ replace .Name "-" " " | title }}"
subtitle: ""
description : ""
slug: ""
tags:
- seo
categories:
- tools
- training
- seo
resources:
- src: "cover.jpeg"
  name: "cover"
- src: "*.jpeg"
---

SEO Kraken

***

{{< photo src=".jpeg" alt="" >}}

{{< photo class=fullwidth src=".jpeg" alt="" >}}

{{< photoset max="2" >}}
  {{< photo src=".jpeg" alt="" >}}
  {{< photo src=".jpeg" alt="" >}}
{{</ photoset >}}

{{< photoset max="3" >}}
  {{< photo src=".jpeg" alt="" >}}
  {{< photo src=".jpeg" alt="" >}}
  {{< photo src=".jpeg" alt="" >}}
{{</ photoset >}}

***
