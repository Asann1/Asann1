<div align="center">
  <img src="assets/banner.svg" alt="Asan - Python backend developer" width="100%">
</div>

<br>

### about

Python backend developer. Right now I'm building a server monitoring service: agent, API, database, auth, Docker, alerts.

### stack

<img src="assets/stack.svg" alt="Using: Python, FastAPI, Pydantic, psutil, python-telegram-bot, Git. Next: PostgreSQL, SQLAlchemy, Docker, Linux, pytest, GitHub Actions." width="100%">

### projects

| project | what it does | status |
|---|---|---|
| [**server-monitor**](https://github.com/Asann1/server-monitor) | An agent collects CPU, RAM and disk metrics and sends them to a FastAPI backend | in progress |
| [**tg-pc-control-bot**](https://github.com/Asann1/tg-pc-control-bot) | Async Telegram bot for remote Windows PC monitoring and control, with confirmation for restart and sleep | work in progress |

### server-monitor roadmap

```
progress  [██░░░░░░]  2 / 8

[x] agent     CPU / RAM / disk metrics
[x] api       POST /metrics, GET /metrics/latest
[ ] storage   PostgreSQL + SQLAlchemy
[ ] auth      API key per agent
[ ] docker    one-command start with compose
[ ] alerts    Telegram
[ ] quality   pytest + CI
[ ] deploy    VPS + nginx
```
