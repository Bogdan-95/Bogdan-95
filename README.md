# Богдан Реньго

### Junior Python Backend Developer

Разрабатываю Backend-приложения на Python: REST API, фоновые задачи, интеграции с внешними сервисами и работу с PostgreSQL.

Ищу первую коммерческую позицию **Junior Python Backend Developer** или **Trainee Python Developer**.

## Избранные проекты

### [Content Factory Console](https://github.com/Bogdan-95/content-factory-console)

REST API и очередь задач генерации изображений с отдельным Worker.

**Python 3.12 · FastAPI · PostgreSQL · SQLAlchemy · Alembic · Docker**

- Очередь задач на PostgreSQL без Redis/Celery.
- Конкурентный захват через `SELECT ... FOR UPDATE SKIP LOCKED`.
- Разделение API и Worker.
- Миграции Alembic, интеграционные тесты и GitHub Actions.

### [Quote Showcase](https://github.com/Bogdan-95/quote-showcase)

Асинхронная in-memory витрина цитат с потоковым импортом и кэшированием.

**Python · FastAPI · asyncio · LRU · TTL · Docker**

- Потоковый приём больших JSON-снимков.
- LRU-кэш с ограничением по размеру и TTL.
- Single Flight для объединения конкурентных запросов.
- Unit-тесты и CI.

### [Internet Speed Measurer](https://github.com/Bogdan-95/internet-speed-measurer)

CLI-утилита для измерения скорости HTTP-загрузки.

**Python · urllib · argparse · unittest · Mock**

- Потоковое чтение HTTP-ответов.
- Обработка сетевых ошибок и таймаутов.
- Unit-тесты без реальных внешних запросов.
- Реализация на стандартной библиотеке Python.

## Технологии

- **Язык:** Python 3.11–3.12, OOP, Type Hints, asyncio
- **Backend:** FastAPI, REST API, Pydantic, aiogram
- **Базы данных:** PostgreSQL, SQLite, SQLAlchemy 2.0, Alembic
- **Инфраструктура:** Docker, Docker Compose, Linux, Bash
- **Качество:** Pytest, unittest, unittest.mock, Ruff, Git, GitHub Actions

## Контакты

- [GitHub](https://github.com/Bogdan-95)
- [Портфолио и резюме](https://bogdan-95.github.io/my_business_card/)
- [Telegram](https://t.me/bodya_95)
- [Email](mailto:b95rengo@gmail.com)
