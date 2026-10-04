# Архитектурный паспорт платформы публикации литературных произведений

Практическая работа №3, курс «Создание клиент-серверных приложений», ИТМО, 2026.

**Команда:** Борисевич Анна, Данилов Назар, Ходакова Мария (поток СКСП 1.1)

Клиент-серверная платформа для публикации и последовательного выпуска
пользовательских произведений: авторы публикуют главы сразу или по расписанию,
читатели читают, комментируют и продолжают с сохранённой позиции.

## Артефакты

| Файл | Содержание |
|---|---|
| [ADR-001.md](docs/architecture/ADR-001.md) | Выбор архитектуры: модульный монолит |
| [c4-diagram.drawio](docs/architecture/c4-diagram.drawio) | C4: System Context, Container, модули backend |
| [openapi.yaml](docs/architecture/openapi.yaml) | Контракт REST API (OpenAPI 3.0.3) |
| [er-diagram.dbml](docs/architecture/er-diagram.dbml) | Исходник полной ER-диаграммы |
| [er-diagram.png](docs/architecture/er-diagram.png) | Полная ER-диаграмма |
| [er-diagram-simple.png](docs/architecture/er-diagram-simple.png) | Упрощённая ER-диаграмма: только основные сущности и атрибуты |
