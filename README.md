﻿## REST API demo

### Skill

- Java(Spring Boot)

### Api List

| Method | Path               | Note |
| ------ | ------------------ | ---- |
| GET    | /demo/users        | -    |
| GET    | /demo/users/{ id } | -    |
| POST   | /demo/user         | \*1  |
| PUT    | /demo/user/{ id }  | \*1  |
| DELETE | /demo/user/{ id }  | -    |

```json
// *1: Body

{
  "firstName": "林",
  "lastName": "かおり",
  "age": 19
}
```
