Minimal Daphne/Channels example to test in PyCharm.

1. Install requirements.
2. Start Redis, e.g. with Docker: `docker run --rm -d -p 6379:6379 redis:5`
3. Run migrations: `python manage.py migrate`
4. Start the Django server using PyCharm's run/debug configuration.
5. Open http://127.0.0.1:8000/chat/lobby/ in two separate browser tabs.
6. Write something to the chat.
