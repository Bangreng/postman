# 1. Регистрация пользователя.

#### Отправленный запрос:
```
{
  "user": {
    "username": "pavlen1",
    "email": "qqwweerrttyyy@gmail.com",
    "password": "qwertyu123456"
  }
}
```

### Ответ:
```
{"user":{"username":"pavlen1","email":"qqwweerrttyyy@gmail.com","token":"eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjY4NzYzYWI0NWVmZjZlMWIwMGQyN2Y1MiIsInVzZXJuYW1lIjoicGF2bGVuMSIsImV4cCI6MTc1Nzc2Mjc0MSwiaWF0IjoxNzUyNTc4NzQxfQ.s-GK8-iICP5bm6Xt00pWbmilqy64pIdD-c1IXGATfuw"}}
```


# 2. Авторизация

### Отправленныый запрос:

```
{
  "user": {
    "email": "qqwweerrttyyy@gmail.com",
    "password": "qwertyu123456"
  }
}
```

### Ответ:
```
{"user":{"username":"pavlen1","email":"qqwweerrttyyy@gmail.com","token":"eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjY4NzYzYWI0NWVmZjZlMWIwMGQyN2Y1MiIsInVzZXJuYW1lIjoicGF2bGVuMSIsImV4cCI6MTc1Nzc2MzQ5NiwiaWF0IjoxNzUyNTc5NDk2fQ.b7kkHo3sYPaX0w2nnxF9DVIWhnJ_VUlDywMsK102Eg8"}}
```
