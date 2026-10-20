# ai-service

AI service of Relay: AI-powered features and natural language processing, exposed to the other services over a REST API.

**Status:** not implemented yet. This repository only holds the project setup.

## Planned stack

Python and FastAPI. No application code, `pyproject.toml`, `requirements.txt` or dependencies exist yet; they will be added as a separate task.

## Planned responsibilities

Per the architecture overview:

- AI-powered features and natural language processing
- REST API for AI capabilities
- Integration with the core messaging system

## Related repositories

- `core-service`: application user profiles and core messaging logic
- `api-gateway`: single entry point for clients
- `realtime-gateway`: WebSocket gateway for real-time communication
- `infrastructure`: local PostgreSQL and ZITADEL (Docker Compose)

## Branches

`TASK_<kebab-case>` -> `test` -> `main`, both through pull requests, enforced by the `branch-policy` workflow. Feature branches are created from `test`.
