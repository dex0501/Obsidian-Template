
---
creation-date: <% tp.file.creation_date() %> 
modification-date: <% tp.file.last_modified_date("dddd Do MMMM YYYY HH:mm:ss") %>
type: role
tags: #companyrole #title
---

### Info

-  [role-name::    <% tp.file.title %>     ]
- [role-description::  ]
- [role-department:: ]



### People with this title
```dataview
TABLE
from !"Templates"
WHERE type = "person"
WHERE contains(company-role, this.file.link)
```



#companyrole #role #title