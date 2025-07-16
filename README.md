# 1. Регистрация пользователя.
![Image alt](https://github.com/Bangreng/postman/blob/main/%D0%A0%D0%B5%D0%B3%D0%B8%D1%81%D1%82%D1%80%D0%B0%D1%86%D0%B8%D1%8F.png)
#### Отправленный запрос:
```
{
  "user": {
    "username": "bangreng",
    "email": "pavlent774@gmail.com",
    "password": "qwerty12345"
  }
}
```

### Ответ:
```
{
    "user": {
        "username": "bangreng",
        "email": "pavlent774@gmail.com",
        "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjY4NzdjM2RhNWVmZjZlMWIwMGQyN2Y1OSIsInVzZXJuYW1lIjoiYmFuZ3JlbmciLCJleHAiOjE3NTc4NjMzODYsImlhdCI6MTc1MjY3OTM4Nn0.LltYRU3ubGHV_Yjq1VZgSXfLDW2c2g5C_Qo80EQexSc"
    }
}
```


# 2. Авторизация

### Отправленныый запрос:

```
{
  "user": {
    "email": "pavlent774@gmail.com",
    "password": "qwerty12345"
  }
}
```

### Ответ:
```
{
    "user": {
        "username": "bangreng",
        "email": "pavlent774@gmail.com",
        "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjY4NzdjM2RhNWVmZjZlMWIwMGQyN2Y1OSIsInVzZXJuYW1lIjoiYmFuZ3JlbmciLCJleHAiOjE3NTc4NjM1OTYsImlhdCI6MTc1MjY3OTU5Nn0.cF27GUrv40oZ-0L3t9u_703t4jULRaJVnTknhFqHmF0"
    }
}
```


# 3. Получение данных пользователя

### Ответ:

```
{
    "user": {
        "username": "bangreng",
        "email": "pavlent774@gmail.com",
        "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjY4NzdjM2RhNWVmZjZlMWIwMGQyN2Y1OSIsInVzZXJuYW1lIjoiYmFuZ3JlbmciLCJleHAiOjE3NTc4NjM3NTAsImlhdCI6MTc1MjY3OTc1MH0.HElUVJGXz5hNM2kBsBvZyk9HoKE9cbaPvth2g_UPFEQ"
    }
}
```
