# S&T College

## Routes

### List all class and groups

| HTTP |  Routes  | Content-Type | Methods                     |
|------|----------|:------------:|:---------------------------:|
| GET  | /list    | JSON         | [getList()](#getlist)       |
| GET  | /details | JSON         | [getDetails()](#getdetails) | 

### Daily schedule

| HTTP | Routes                          | Content-Type | Methods                           |
|------|---------------------------------|:------------:|:---------------------------------:|
| GET  | /day/:class/:name/:YYYY/:MM/:DD | JSON         | [getDay()](#getday)               |
| GET  | /day/:class/:name/              | JSON         | [getCurrentDay()](#getcurrentday) |


### Weekly schedule

| HTTP | Routes                 | Content-Type | Methods                            |
|------|------------------------|:------------:|:----------------------------------:|
| GET  | /week/:class/:name/:WW | JSON         | [getWeek()](#getweek)              |
| GET  | /week/:class/:name/    | JSON         | [getCurrentWeek()](getcurrentweek) |


## Methods

### getList()

#### Response

```
Array[n]
 ...: {
       className: '',
       groupName: '',
       semester: 1|2
      }
       
```

### getDetails()
### getDay()
### getCurrentDay()
### getWeek()
### getCurrentWeek()
