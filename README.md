# DevSecOps Security Pipeline

Тестовое задание — Circle Creative Buro | Middle DevSecOps Engineer

Полный цикл DevSecOps для FastAPI REST API: статический анализ → зависимости → секреты → CI/CD gates → hardening сервера.


## Структура репозитория

```
.github/workflows/
├── security-SAST.yml        # Шаг 1 — Статический анализ кода (Semgrep)
├── Dependency Scan.yml      # Шаг 2 — Анализ зависимостей (Trivy)
├── Managing secrets.yml     # Шаг 3 — Управление секретами (Gitleaks)
├── security Gates.yml       # Шаг 4 — CI/CD Pipeline с Security Gates
└── hardening server.yml     # Шаг 5 — Hardening сервера
