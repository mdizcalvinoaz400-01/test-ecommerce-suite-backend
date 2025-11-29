# test-ecommerce-suite - Backend

Backend repository for the test-ecommerce-suite project.

## 📊 Project Tracking

| Resource | Link |
|----------|------|
| **GitHub Project** | [test-ecommerce-suite-project](https://github.com/users/mdizcalvinoaz400-01/projects) |
| **Orchestration** | [test-ecommerce-suite-orchestration](https://github.com/mdizcalvinoaz400-01/test-ecommerce-suite-orchestration) |
| **Current Sprint** | Sprint 1 |

## 🛠️ Tech Stack

- **Framework:** Python/FastAPI
- **ORM:** SQLAlchemy
- **Testing:** pytest
- **Linting:** ruff
- **Department:** Backend

## 🤖 Copilot Agents

| Agent | Purpose |
|-------|---------|
| `@python` | Endpoint and service development |
| `@api` | API design guidance |

## 📋 Commands

```bash
pip install -e .       # Install in dev mode
pytest                 # Run tests
ruff check .           # Lint
ruff format .          # Format
uvicorn main:app       # Run dev server
```

## 📁 Project Structure

```
src/
├── api/routes/    # API endpoints
├── core/          # Config, database
├── models/        # SQLAlchemy models
├── schemas/       # Pydantic schemas
└── services/      # Business logic
```

## 🔗 Related Repositories

- [test-ecommerce-suite-orchestration](https://github.com/mdizcalvinoaz400-01/test-ecommerce-suite-orchestration) - Central coordination
- [test-ecommerce-suite-frontend](https://github.com/mdizcalvinoaz400-01/test-ecommerce-suite-frontend) - Frontend UI
- [test-ecommerce-suite-infrastructure](https://github.com/mdizcalvinoaz400-01/test-ecommerce-suite-infrastructure) - Infrastructure
