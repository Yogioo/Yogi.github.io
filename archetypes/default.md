<!-- +++
title = '{{ replace .File.ContentBaseName "-" " " | title }}'
date = {{ .Date }}
draft = true
+++ -->
+++ title = "{{ replace .Name "-" " " | title }}" date = "{{ .Date }}" tags = [] slug = "" +++
