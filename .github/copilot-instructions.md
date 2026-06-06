# NovaLabs.in GitHub Copilot Coding Instructions

When generating code for any repository under the NovaLabs.in organization, please adhere to the following software engineering principles:

## 1. Code Style and Architecture
- **Keep it Simple**: Avoid over-engineering. Write clean, readable, self-documenting code.
- **Python**: Prefer standard typing hints, follow PEP 8, and use modern syntax (Python 3.10+).
- **TypeScript**: Enforce strict type safety. Avoid using `any`. Use interfaces and type definitions clearly.
- **Go**: Follow standard Go project layouts, write clean error handling (`if err != nil`), and use idiomatic patterns.

## 2. Testing
- Write automated tests for all business logic.
- Mock external network calls, database queries, and third-party APIs.
- For Python, use `pytest`. For JavaScript/TypeScript, use `jest` or `vitest`.

## 3. Comments and Documentation
- Docstrings/JSDocs are required for all public classes, functions, and modules.
- Maintain existing comment patterns. Write comments explaining the *why*, not just the *what*.
