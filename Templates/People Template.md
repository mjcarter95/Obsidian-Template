---
category:
  - "[[People]]"
tags:
  - people
birthday: 
org: 
created:
  {{date}}
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