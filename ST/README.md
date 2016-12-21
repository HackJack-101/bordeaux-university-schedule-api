# S&T College

## Routes

### List all class and groups

| HTTP |  Routes  | Content-Type | Methods      |
|------|----------|:------------:|:------------:|
| GET  | /list    | JSON         | [getList()](#getList)    |
| GET  | /details | JSON         | getDetails() | 

### Daily schedule

| HTTP | Routes                          | Content-Type | Methods         |
|------|---------------------------------|:------------:|:---------------:|
| GET  | /day/:class/:name/:YYYY/:MM/:DD | JSON         | getDay()        |
| GET  | /day/:class/:name/              | JSON         | getCurrentDay() |


### Weekly schedule

| HTTP | Routes                 | Content-Type | Methods          |
|------|------------------------|:------------:|:----------------:|
| GET  | /week/:class/:name/:WW | JSON         | getWeek()        |
| GET  | /week/:class/:name/    | JSON         | getCurrentWeek() |


## Methods

### getList
