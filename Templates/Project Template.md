---
category:
  - "[[Projects]]"
type: []
org: []
start: 
year: 
tags:
  - projects
url: 
status:
---

## Meetings

```dataview
table without id
	file.link as Meeting,
	date as Date
where
	contains(category,[[Meetings]]) and
	contains(project,this.file.link)
sort file.name desc
```

## Development Notes

```dataview
table without id
	file.link as Meeting,
	date as Date
where
	contains(tags,"development") and
	contains(project,this.file.link)
sort file.name desc
```