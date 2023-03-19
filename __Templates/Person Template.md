---
creation-date: <% tp.file.creation_date() %> 
modification-date: <% tp.file.last_modified_date("dddd Do MMMM YYYY HH:mm:ss") %>
type: person
location: 
aliases: 
linkedin:
tag: #people #person
---
## Info 📑
- 🧍‍♀️ [name:: <% tp.file.title %> ]
- 🏢 [company:: [[]] ]
- 🤠 [company-role:: ] 
-  🖥️ [office-location:: [[]] ]
- 📩 [e-mail::  ]
- 📱 [phone-number::  ]


## 🚀 Projects 
```dataview 
TABLE without id
 file.link as Project, project-client as Client, project-pm as PM
FROM !"__Templates"
WHERE tag = project 
WHERE contains(project-members, this.file.name) 
```

## 🌅 Meetings 
```dataview 
TABLE without id file.link as Meeting, meeting-type as Type, topic, date
FROM !"__Templates"
WHERE type = "meeting"
WHERE contains(participants, this.file.link) 
```


## 📚 Logs 
```dataview
TABLE
rows.Details as "Details"
FROM !"__Templates"
WHERE contains(log, this.file.name) 
FLATTEN log as Details
WHERE contains(Details, this.file.name) 
GROUP BY file.link as Source
SORT row.file.day desc
```



#people #person