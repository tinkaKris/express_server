# ДЗ 59. Розробка RESTful API з використанням Express.

Проект використовує **менеджер пакетів npm** та запускається командою **npm run dev**.

### Маршрути сервера:

**/:** Головний маршрут, що повертає "Get root route".

- **/users:** Маршрут для користувачів:
- GET: "Get users route".
- POST: "Post users route".
- **/users/:userId:** Маршрут для окремого користувача:
- GET: "Get user by Id route: {userId}".
- PUT: "Put user by Id route: {userId}".
- DELETE: "Delete user by Id route: {userId}".
- **/articles:** Маршрут для статей:
- GET: "Get articles route".
- POST: "Post articles route".
- **/articles/:articleId:** Маршрут для конкретної статті:
- GET: "Get article by Id route: {articleId}".
- PUT: "Put article by Id route: {articleId}".
- DELETE: "Delete article by Id route: {articleId}".

---
