+++
type = ""
title = "Work"
description = "Andrew Garber-Browne a ..."
meta = "false" #Do not display tags or categories
+++


{{ define "title" }}
  {{ .Title }} · {{ .Site.Title }}
{{ end }}
{{ define "content" }}
  {{ partial "home.html" . }}
{{ end }}
