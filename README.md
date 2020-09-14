# FastAPITortoise
Асинхронная работа FastAPI c Tortoise ORM

## Запуск сервера 
uvicorn main:app --reload --port 8080

У Tortoise ORM на данный момент отсутствует нативная миграция. 
Для миграции используется сторонняя библиотека Aerich
