---
creation-date: 2023-03-04 19:54 
modification-date: Saturday 4th March 2023 19:54:20
type: person
company-role:
location: 
aliases: 
linkedin:
tag: #people #person
---
## Info 📑
 - 🏢 [company:: [[]] ]
- 🤠 [company-role:: [[Role_QA]] ] 
 -  🖥️ [office-location:: [[]] ]
 - 📩 [e-mail::  ]
 - 📱 [phone-number::  ]


## 🚀 Projects 
```dataview 
TABLE without id
 file.link as Project, project-client as Client, project-pm as PM
FROM !"Templates"
WHERE tag = project 
WHERE contains(project-members, this.file.name) 
```

## 🌅 Meetings 
```dataview 
TABLE without id
file.link as Feedback, feedback-with as Name, Date, feedback-purpose as Purpose, project-name as Project
FROM !"Templates"
WHERE type = "meeting"
WHERE contains(participants, this.file.link) 
```


## 📚 Logs 
```dataview
TABLE
rows.Details as "Details"
FROM !"Templates"
WHERE contains(log, this.file.name) 
FLATTEN log as Details
WHERE contains(Details, this.file.name) 
GROUP BY file.link as Source
SORT row.file.day desc
```



#people #person