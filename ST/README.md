# S&T College

## Routes

### List all class and groups

| HTTP Methods |  Routes  | Content-Type |
|--------------|----------|:------------:|
| GET          | /list    | JSON         |
| GET          | /details | JSON         |

### Daily schedule

| HTTP Methods |              Routes             | Content-Type |
|--------------|---------------------------------|:------------:|
| GET          | /day/:class/:name/:YYYY/:MM/:DD | JSON         |
| GET          | /day/:class/:name/              | JSON         |


### Weekly schedule

| HTTP Methods |          Routes        | Content-Type |
|--------------|------------------------|:------------:|
| GET          | /week/:class/:name/:WW | JSON         |
| GET          | /week/:class/:name/    | JSON         |
