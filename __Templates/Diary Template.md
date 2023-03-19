---
creation-date: <% tp.file.creation_date() %> 
modification-date: <% tp.file.last_modified_date("dddd Do MMMM YYYY HH:mm:ss") %>
type: dailytodo
tags: #todo #todolist 
---

> [!  ]+ Today
>  date::  <% tp.file.creation_date() %> 
> location::  🏭  
> start time::  
> leave time::  
> Zagreb:   <% tp.user.getWeatherShort() %>

## Tasks 📝
```button
name new todo
type command
action QuickAdd: new task
color yellow
```

## Should Be Done Today
> [! tasks]+ Lists
> ```tasks
> not done 
> ((due before <% tp.file.creation_date("YYYY-MM-DD") %>) OR (no due date)) AND (tag does not include #idea)


### Finished Today
> [! tasks]+ Lists
> ```tasks
> done on date(<% tp.file.creation_date("YYYY-MM-DD") %>)
> short mode
>```

### Created Today

> [! tasks]+ Lists
> ```dataview
>TASK
>from !"__Templates"
>WHERE created =  date(<% tp.file.creation_date("YYYY-MM-DD") %>)
>SORT tsd DESCENDING
>```



## Logs 📗
```button
name new log
type command
action QuickAdd: new log
color yellow
```


## Notes

```text
Some text
```


#todolist #dailytodo #diary #daily

