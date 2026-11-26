# Иван Кирчанов · QA Lead

Руковожу командой тестирования и продолжаю писать автотесты. На GitHub показываю, как проектирую проверки на Playwright и TypeScript, запускаю их в CI и разбираю нестабильные прогоны.

## Conduit E2E Tests

[Conduit E2E Tests](https://github.com/IvanKir4anov/conduit-e2e-tests) — набор UI- и API-тестов для приложения RealWorld Conduit. Приложение поднимается в Docker Compose. В GitHub Actions быстрый smoke-прогон идёт перед регрессом, а ночной прогон отдельно проверяет стабильность тестов.

- [Запуск проекта и структура тестов](https://github.com/IvanKir4anov/conduit-e2e-tests/blob/main/README.ru.md)
- [Пример: подготовка данных через API, проверка комментариев через интерфейс](https://github.com/IvanKir4anov/conduit-e2e-tests/blob/main/tests/hybrid/article-comments.spec.ts)
- [Правила разбора нестабильных тестов и выхода из карантина](https://github.com/IvanKir4anov/conduit-e2e-tests/blob/main/docs/stability.md)

[LinkedIn](https://www.linkedin.com/in/ivan-kirchanov/)
