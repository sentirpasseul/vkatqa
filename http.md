## 📩 Из чего состоит HTTP-запрос?
HTTP - это протокол передачи данных
### HTTP-запрос включает:

1️⃣ Стартовую строку
- Метод запроса (GET, POST, PUT, DELETE и др.)
- URL-адрес (путь к ресурсу)
- Версия HTTP (HTTP/1.1, HTTP/2)

2️⃣ Заголовки (Headers)
- Передают метаданные (тип контента, авторизация, сжатие и др.).
- Пример: Content-Type: application/json

3️⃣ Тело запроса (Body) (только для методов POST, PUT и др.)
- Содержит данные, например, JSON с информацией о новом пользователе.

📌 Пример HTTP-запроса:
```console
POST /api/users HTTP/1.1  
Host: example.com  
Content-Type: application/json  
Authorization: Bearer token123  

{
  "name": "Alice",
  "email": "alice@example.com"
}
```

📌 Пример HTTP-ответа:
```console
HTTP/1.1 200 OK  
Content-Type: application/json  

{
  "id": 1,
  "name": "Alice",
  "email": "alice@example.com"
}
```

<p>💡 Вывод: интернет работает по принципу запрос-ответ.<br>Браузер запрашивает ресурс у сервера, используя HTTP, а сервер обрабатывает запрос и отправляет ответ, который браузер рендерит для пользователя. 🚀</p>
