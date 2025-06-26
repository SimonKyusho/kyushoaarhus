---
title: "Welcome to My Blog"
description: "Here are my latest posts"
---

Welcome to my site! Below you'll find my most recent posts.

## Recent Posts
## Recent Posts
{{ range first 3 (where .Site.RegularPages "Section" "posts") }}
* [{{ .Title }}]({{ .RelPermalink }}) - {{ .Date.Format "January 2, 2006" }}
  {{ end }}