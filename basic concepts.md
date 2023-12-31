[< вернуться на главную](readme.md)

**Репозиторий** - дерево изменений проекта. После создания нового репозитория дерево содержит только одну ветку — master. Ветка состоит из коммитов, расположенных в хронологическом порядке. Как правило, в ветке master находятся проверенные и протестированные изменения.

**Ветка** - указатель на коммит.  На один коммит может указывать несколько веток. Как правило это случается при создании новой ветки из текущей. Например для реализации в ней новой задачи. По мере добавления коммитов — ветки будут расходится в разные стороны.

**Индекс** - изменения, которые будут зафиксированы при следующем коммите. При этом, во время коммита, могут быть изменения, не добавленные в индекс — они не будут закоммичены. Их надо будет отдельно добавить в индекс и зафиксировать. Таким образом, можно вносить разом, все необходимые по мере работы, правки и фиксировать их логическими группами.

**Коммит** - (от слова commit - фиксировать) — логическая единица изменений.Каждый из них имеет историю уникальный ID и цепочку предшествующих коммитов. Можно «откатить» (отменить) изменения любого из коммитов. Для любого коммита из истории можно создать указатель, то есть ветку. 
