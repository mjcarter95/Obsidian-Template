---
category:
  - "[[People]]"
tags:
  - people
birthday: 
org:
  - "[[example_institution]]"
created:
  2025-01-09
url:
---
## Meetings

```dataview
table without id
	file.link as Meeting,
	date as Date
where
	contains(category,[[Meetings]]) and
	contains(people,this.file.link)
sort file.name desc
```