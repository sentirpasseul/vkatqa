## 🔍 Как работает интернет: от запроса до ответа
### Когда пользователь вводит адрес сайта в браузере (например, https://example.com), происходит несколько этапов:

1️⃣ DNS-запрос
- Браузер проверяет кеш и спрашивает у DNS-сервера IP-адрес домена (example.com).
- Если IP-адрес не найден, запрос отправляется в корневые DNS-серверы, затем в доменные, пока не получит IP-адрес.

2️⃣ Установление соединения (TCP/IP + TLS)
- Браузер устанавливает соединение с сервером по IP-адресу через протокол TCP/IP.
- Если используется HTTPS, происходит TLS-шифрование для безопасной передачи данных.

3️⃣ Отправка HTTP-запроса
- Браузер формирует HTTP-запрос и отправляет его на сервер.

4️⃣ Обработка запроса сервером
- Сервер получает запрос, обрабатывает его (может взаимодействовать с базой данных, API и т. д.) и формирует ответ.

5️⃣ Возвращение HTTP-ответа
- Сервер отправляет браузеру ответ с нужными данными (например, HTML-страницей).

6️⃣ Отображение страницы браузером
- Браузер анализирует HTML, загружает CSS, JavaScript и рендерит страницу.
