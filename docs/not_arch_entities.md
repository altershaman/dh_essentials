```jsonata
$dh_lake_map($).entities.list.not_arch_entities
```

{{description}}

{{#list}}
###### :id: {{entity}}

---
**{{#title}}{{.}}{{/title}}**
{{^title}}*no title provided*{{/title}}

{{#description}}{{.}}{{/description}}{{^description}}b{{/description}}


{{/list}}

{{^list}}не обнаружено{{/list}}