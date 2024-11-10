---
title: "UMS"
date: 2023-07-03
draft: false
tags: ["academic"]
---



{{ $productlist := site.Data.productlist }}
{{ range $productlist.products }}
  {{ if eq .title "Hugo Hula Hoop" }}
    {{ range .variants }}
      {{ .price }}
    {{ end }}
  {{ end }}
{{ end }}
