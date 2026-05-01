# SNAPSHOT

## Snapshot 2026-05-01

### Статус

Локальная версия GitHub-портфолио подготовлена для публикации: главный README, case studies и 8 clean/demo repos готовы. Осталось создать GitHub-репозитории, push и заменить placeholder-статусы на реальные URL.

### Сделано

- [x] Создана структура `Portfolio/`.
- [x] Подготовлен главный `README.md` без выбора конкретных проектов.
- [x] Добавлен `QUESTIONNAIRE.md` с текстами для анкеты.
- [x] Добавлен `PUBLISH_CHECKLIST.md`.
- [x] Добавлен шаблон кейса `cases/TEMPLATE.md`.
- [x] Добавлены правила проекта в `AGENTS.md`.
- [x] Добавлен `.gitignore` для защиты секретов и локальных файлов.
- [x] По глобальной wiki `projects/it` подготовлена рабочая матрица кандидатов `PROJECT_CANDIDATES.md`.
- [x] По решению пользователя в shortlist подняты `Олег (психолог)`, `Legal-verify`, `Учет доходов и расходов`, `Учитель сербского`; `Second-brain` и `Wiki_LLM` убраны из основного набора как внутренние автоматизации.
- [x] В `README.md` и `QUESTIONNAIRE.md` добавлена честная рамка: пользователь не позиционируется как ручной разработчик, а собирает AI-assisted прототипы через Codex / Claude Code, проектируя workflow, проверяя результат и документируя решение.
- [x] Проведен аудит проектов-кандидатов и создан `PORTFOLIO_AUDIT.md`: рекомендованы финальные кейсы, форматы публикации, security blockers и следующий шаг.
- [x] Принята стратегия: каждый проект публикуется отдельным clean repo, а `Portfolio` ссылается на них. Создан sibling-каталог `Portfolio-Repos/` с отдельными локальными git-заготовками для 8 проектов.
- [x] Добавлен `PUBLIC_REPOS.md` с картой будущих GitHub-репозиториев.
- [x] Созданы draft case studies: `legal-verify`, `serbian-teacher`, `income-bot`, `meeting-secretary`, `nutritionist`, `oleg-psychologist`, `poetryforge`, `voice-to-text`.
- [x] Главный `README.md` обновлен ссылками на созданные case studies.
- [x] Clean repo `Portfolio-Repos/voice-to-text` наполнен очищенным кодом: перенесены только безопасные source-файлы, `.env.example` заменен на placeholder, syntax check и secret scan пройдены.
- [x] В `Portfolio-Repos/voice-to-text` добавлены публичные sanitized `AGENTS.md` / `CLAUDE.md`.
- [x] Clean repo `Portfolio-Repos/meeting-secretary` наполнен очищенным кодом: перенесены безопасные source-файлы, Docker/docs/env templates, добавлены публичные `AGENTS.md` / `CLAUDE.md`, syntax check и secret scan пройдены.
- [x] Принято правило: публичные документы портфолио и clean repos вести на русском. `voice-to-text` и `meeting-secretary` README/AGENTS/CLEANUP/SECURITY переведены на русский.
- [x] Clean repo `Portfolio-Repos/poetryforge` наполнен очищенным кодом из стабильного `HEAD`: добавлены source-файлы, тесты, `pyproject.toml`, `uv.lock`, публичные `AGENTS.md` / `CLAUDE.md`; большие generated data не включены; `uv run pytest` пройден (`161 passed, 6 skipped`), secret scan пройден.
- [x] Clean repo `Portfolio-Repos/serbian-teacher` наполнен очищенным кодом: перенесены Telegram bot source-файлы, schema, requirements; создан безопасный `.env.example`; PDF/DOCX и исходный `.env.example` не перенесены; добавлены публичные `AGENTS.md` / `CLAUDE.md`; syntax check и secret scan пройдены.
- [x] Clean repo `Portfolio-Repos/legal-verify` наполнен очищенным кодом: перенесены package source, prompts, `pyproject.toml`, `uv.lock`; исключены `.env`, `.venv`, `history/`, PDF и приватные документы; добавлены публичные `AGENTS.md` / `CLAUDE.md`, безопасный `.env.example`, deterministic tests; `uv run pytest` пройден (`3 passed`), syntax check и secret scan пройдены.
- [x] Clean repo `Portfolio-Repos/income-bot` наполнен очищенным кодом: перенесены bot source-файлы, requirements, публичные docs; исключены `.keys`, service account JSON, `.env`, `.bak`, deploy scripts и systemd unit; реальные client aliases и персональные категории заменены на demo values; добавлены публичные `AGENTS.md` / `CLAUDE.md`, безопасный `.env.example`, tests; `pytest` пройден (`2 passed`), syntax check и secret scan пройдены.
- [x] Clean repo `Portfolio-Repos/nutritionist` наполнен очищенным кодом: перенесены `src/nutri_bot/`, `migrations/001_init.sql`, `pyproject.toml`; исключены `.env`, `keys.md`, `.venv`, N8N reference files, пользовательские профили, история питания, фотографии, health data и chat logs; добавлены публичные `AGENTS.md` / `CLAUDE.md`, безопасный `.env.example`, synthetic tests; `pytest` пройден (`2 passed`), syntax check и secret scan пройдены.
- [x] Demo repo `Portfolio-Repos/oleg-psychologist` создан как безопасный architecture case study: исходные docs с owner IDs, доменами, VPS/IP, Supabase details и production settings не перенесены; добавлена нейтральная реализация memory workflow на синтетических данных, публичные `AGENTS.md` / `CLAUDE.md`, безопасный `.env.example`, tests; `pytest` пройден (`5 passed`), syntax check, demo run, secret scan и privacy scan пройдены.
- [x] Главный README приведён к формату витрины: 5 главных кейсов и 3 дополнительных, без пустых `TODO` в контактах.
- [x] Case studies синхронизированы со статусом clean repos: устаревшие формулировки про "ещё нужно создать clean repo" убраны.
- [x] `PUBLISH_CHECKLIST.md` обновлён по фактически выполненным пунктам.
- [x] Проведён общий scan по `Portfolio` и `Portfolio-Repos`: реальные ключи, production IP/domain, owner ID и приватные env-файлы не найдены; совпадения только по безопасным `.env.example` и placeholder-документации.
- [x] В `README.md` и `QUESTIONNAIRE.md` добавлены навыки по итогам курса `Промт-Инжиниринг 2.0`: GPTs/Actions, OpenAI Playground, n8n workflows, API/HTTP-интеграции, Telegram/Gmail/Google Sheets, основы данных, Google Colab/Jupyter, LangChain ReAct и Tool/Function Calling; отдельно указаны VS Code, базовый PyCharm и Google Colab.

### В процессе

- [ ] Опубликовать `Portfolio` и clean/demo repos на GitHub.

### Следующий шаг

Создать GitHub-репозитории, запушить `Portfolio` и 8 clean/demo repos, затем заменить `GitHub URL будет добавлен после push` / `TODO` в `README.md`, `PUBLIC_REPOS.md` и case studies на реальные ссылки.
