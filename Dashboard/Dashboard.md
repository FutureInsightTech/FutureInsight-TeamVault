---
banner: "https://images.unsplash.com/photo-1483389127117-b6a2102724ae?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1074&q=80"
banner_y: 0.444
kanban-plugin: basic
---


# Blog Posts

## Machine Learning Post:

```dataview
TABLE file.name as "Name", file.link as "Location"
WHERE type = "post" AND tags = ["blog" ,"Machine Learning"]
SORT file.name ASC
```

## Web Development Post: 

```dataview
TABLE file.name as "Name", file.link as "Location"
WHERE type = "post" AND tags = ["blog" ,"web-development"]
SORT file.name ASC

```

## Code Report: 
```dataview
TABLE file.name as "Name", file.link as "Location"
WHERE type = "post" AND tags = ["blog" ,"code-report"]
SORT file.name ASC

```



## Operating System 

### Linux

```dataview

TABLE file.name as "Name", file.link as "Location"

WHERE type = "post" AND tags = ["blog", "linux", "operating-system"] 
SORT file.name ASC

```

### Windows 
```dataview
TABLE file.name as "Name", file.link as "Location"
WHERE type = "post" AND tags = ["blog" ,"windows", "operating-system"] 
SORT file.name ASC

```



## Tech Journey

### Flutter
```dataview
TABLE file.name as "Name", file.link as "Location"
WHERE type = "post" AND tags = ["blog" ,"new-tech", "Flutter"] 
SORT file.name ASC

```


