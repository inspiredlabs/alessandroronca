---
region: en

images: ["https://pablowoodward.com/img/M55128.0122.jpg"]

---

<!-- Array refrenced in `seo.html` using: -->
{{/* range $i, $e := .Params.images }}{{ if $i }}, {{ end }}{{ $e | jsonify | safeJS }}{{ end */}}