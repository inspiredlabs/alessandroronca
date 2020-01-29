---
region: en

images: ["https://alessandroronca.netlify.com/images/profile.png"]

---

<!-- Array refrenced in `seo.html` using: -->
{{/* range $i, $e := .Params.images }}{{ if $i }}, {{ end }}{{ $e | jsonify | safeJS }}{{ end */}}