---
creation-date: 2023-03-04 19:00 
modification-date: Saturday 4th March 2023 19:00:43
type: person
company-role: [[Role_Software_Developer]]
location: 
aliases: personb
linkedin:
tag: #people #person
---
## Info 📑

- 🏢 [company:: [[Boring Company]] ] 
- 🤠 [company-role:: [[Role_Software_Developer]] ] 
-  🖥️ [office-location:: [[San Francisco]] ]
- 📩 [e-mail::  ]
- 📱 [phone-number::  ]

## 🚀 Projects 
```dataview 
TABLE without id
 file.link as Project, project-client as Client, project-pm as PM
FROM !"__Templates"
WHERE tag = project 
WHERE contains(project-members, this.file.link) 
```

## 🌅 Meetings 
```dataview 
TABLE without id file.link as Meeting, meeting-type as Type, date, topic
FROM !"__Templates"
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