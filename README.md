## Async FastAPI ticket system for communities with login and communications over Telegram bot

Currently in beta version. Not all files correct.

Requirements: Python >=3.11

It`s uses PostgreSQL as dtabase, Redis for cache system and temp storage for backgroud tasks (maybe Celery).
Also there will be docker and docker-compose files in future.

Dont forget to create .env file with environment variables for:
DB_HOST, DB_PORT, DB_NAME, DB_USER, DB_PASS, TG_BOT_NAME, TG_BOT_TOKEN
And fix app/auth/widget.html
