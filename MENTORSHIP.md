# Python Middle Mentorship — Контекст

> Главный файл-якорь между сессиями с Claude.

## О человеке
- **Имя:** Sharm, GitHub: [SharmCharm](https://github.com/SharmCharm)

## Цель
Перейти на Python Middle Developer

## Среда разработки
- WSL2 + Ubuntu 24.04 LTS на ноуте MSI
- Python 3.13.13 через pyenv
- VS Code + Claude Code, ruff как форматтер

## Принципы работы
1. Учить, не делать ЗА. Задачи решаю сам.
2. Жёсткое код-ревью без сглаживания.
3. Веб-поиск перед каждой рекомендацией версий.
4. 2-5 часов в день, минимум 1 коммит/день.
5. Связка из 3 Claude: чат (ментор), Desktop+Obsidian (конспекты), Code в VS Code (код).
6. PEP 8, безопасность, идиоматичный код.
7. Линейность тем, без перепрыгиваний.

## Прогресс

### День 1 (11.05.2026) — Инфраструктура
- WSL2 + Ubuntu 24.04 LTS
- Git настроен, SSH к GitHub
- pyenv 2.6.31 установлен

### День 2 (12.05.2026) — Python и mutability
- Python 3.13.13 через pyenv
- pip 26.1.1, venv освоен
- Тема mutability + references: shallow/deep copy, is vs ==, rebinding vs mutation
- Эксперимент с id() в REPL проведён

## TODO следующая сессия
- [ ] Диагностика на 25 вопросов
- [ ] Создать Obsidian Vault + CLAUDE.md
- [ ] Тема uv (после venv)
- [ ] Следующая тема Python: функции, аргументы

## Как Claude должен начинать новый чат
1. Прочитать этот файл через web-fetch
2. Свериться с memory edits
3. Спросить: "Где остановились? Идём с {последний пункт TODO}?"
4. Не начинать обучение заново
