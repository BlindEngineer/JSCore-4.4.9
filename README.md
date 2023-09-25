# JSCore-4.4.9
Postman functionality

## 1. Регистрация
### Создаем окружение. В нем создаем переменную с корневым API:

![alt text](URLVariable.png)

### Создаем и отправляем запрос на регистрацию. Получаем ответ сервера:

![alt text](Registration.png)

## 2. Аутентификация
### При аутентификации будем сохранять токен в переменную:

![alt text](token1.png)

### Отправляем запрос (логинимся). Получаем ответ сервера:

![alt text](login.png)

### Переменная приняла значение полученного токена:

![alt text](token2.png)

## 3. Получение данных текущего пользователя
### Используем заголовки, отправляем запрос, получаем ответ:

![alt text](getCurrentUser.png)

