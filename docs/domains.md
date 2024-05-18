{{#is_not_empty}}
# Карта доменов объектов архитектуры

```jsonata
$arch_entities_id:= $dh_lake_map($).entities.list.arch_entities.entity; # получение перечня id архитектурных cущностей (метамодель)

$dh_ctx_objects($arch_entities_id, $);  # получение объектов архитектурных сущностей из глобального контекста
```

![](@document/dochub.essentials.domains.graph?data={{data}})
{{/is_not_empty}}

{{^is_not_empty}}
:warning: Архитектура не определена или не описана
{{/is_not_empty}}

