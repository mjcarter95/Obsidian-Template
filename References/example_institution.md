---
category:
  - "[[Companies]]"
tags:
  - companies
type: 
people: 
url:
---

## People

```dataview
table without id
	file.link as People
where
	contains(category,[[People]]) and
	contains(org,this.file.link)
sort file.name desc
```