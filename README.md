# Портфолио AI Automation и Prompt Engineering

Портфолио начинающего AI automation / prompt engineering специалиста.

Я собираю практические решения на стыке LLM, Telegram-ботов, автоматизации рабочих процессов и интеграций с внешними сервисами. Мой фокус не на "красивых промптах ради промптов", а на сценариях, где AI помогает быстрее получать текст, структурировать информацию, принимать решения и автоматизировать повторяющиеся действия.

Важное уточнение: я не позиционирую себя как разработчик, который пишет production-код с нуля вручную. Я работаю в формате AI-assisted development: проектирую задачу и workflow, формулирую требования, использую Codex / Claude Code для реализации, проверяю результат, тестирую сценарии, правлю промпты и документацию. Моя сильная сторона — собрать прикладной AI-прототип и довести его до понятного рабочего процесса.

## Что я умею

- Проектировать LLM-сценарии: от формулировки задачи до проверки результата.
- Собирать Telegram-ботов и простые backend-прототипы с помощью AI-coding assistants.
- Продвинуто использовать Claude Code и Codex как рабочую агентную среду: skills, MCP servers, hooks, проектные инструкции, межсессионная память и wiki по методу Карпатого.
- Интегрировать AI API, speech-to-text, task management, заметки и внешние сервисы.
- Работать с системными промптами, GPTs/Actions, OpenAI Playground и базовой логикой Tool/Function Calling.
- Собирать no-code / low-code AI-сценарии в n8n: триггеры, ноды, ветвления, HTTP-запросы, авторизация, интеграции с Telegram, Gmail и Google Sheets.
- На базовом уровне работать с данными: структура таблиц, чистка/анонимизация данных, простая аналитика и проверка гипотез с помощью LLM.
- Упаковывать решения в понятный пользовательский workflow.
- Документировать проекты так, чтобы другой человек мог понять назначение, стек, ограничения и запуск.
- Работать с Docker/VPS-деплоем на базовом прикладном уровне.

## Портфель кейсов

Кейсы готовятся как отдельные публичные репозитории, а этот репозиторий является витриной со ссылками на них. Карта репозиториев: [PUBLIC_REPOS.md](PUBLIC_REPOS.md).

Для каждого кейса здесь будет не просто ссылка на код, а короткое объяснение:

- какую задачу решал проект;
- кто пользователь и в чем его боль;
- какой workflow был собран;
- где использовались LLM / prompt engineering / automation;
- какие были ограничения;
- что получилось в результате;
- что я бы улучшил дальше.

### Главные кейсы

| Кейс | Направление | Статус |
| --- | --- | --- |
| [Legal Verify](cases/legal-verify.md) | Domain AI / legal verification | Clean repo готов, GitHub URL будет добавлен после push |
| [Serbian Teacher](cases/serbian-teacher.md) | AI tutor / education automation | Clean repo готов, GitHub URL будет добавлен после push |
| [Income Bot](cases/income-bot.md) | Finance automation / receipt parsing | Clean repo готов, GitHub URL будет добавлен после push |
| [Meeting Secretary](cases/meeting-secretary.md) | Speech-to-text / summary встреч | Clean repo готов, GitHub URL будет добавлен после push |
| [Nutritionist Bot](cases/nutritionist.md) | Product AI bot / nutrition tracking | Clean repo готов, GitHub URL будет добавлен после push |

### Дополнительные кейсы

| Кейс | Направление | Статус |
| --- | --- | --- |
| [Oleg Psychologist](cases/oleg-psychologist.md) | Long-term memory AI assistant | Demo repo готов, GitHub URL будет добавлен после push |
| [PoetryForge](cases/poetryforge.md) | Валидация LLM-результатов / CLI | Clean repo готов, GitHub URL будет добавлен после push |
| [Voice To Text](cases/voice-to-text.md) | Speech-to-text / редактирование текста | Clean repo готов, GitHub URL будет добавлен после push |

## Как я подхожу к задачам

1. Сначала уточняю реальную цель: что должно измениться для пользователя после автоматизации.
2. Разделяю workflow на входные данные, обработку, решение модели, проверку и финальный output.
3. Формулирую техническую задачу для AI-coding assistant и собираю минимально полезную версию, которую можно проверить руками.
4. Фиксирую ограничения: где модель может ошибиться, какие данные нельзя передавать, что требует ручного контроля.
5. Улучшаю UX: статусы, кнопки, понятные сообщения, документация, воспроизводимый запуск.

## Технологии

- Python-based automation (AI-assisted)
- Telegram Bot API
- OpenAI API / LLM API
- OpenAI Playground, GPTs, Actions
- n8n: workflows, triggers, nodes, HTTP/API integrations
- Speech-to-text API
- Google Sheets / Gmail integrations
- Google Colab / Jupyter Notebook на базовом уровне
- LangChain concepts: ReAct, Tool/Function Calling на ознакомительном уровне
- Docker
- Ngrok / базовое размещение AI-ассистентов на сервере
- Markdown documentation
- Git / GitHub
- VS Code, базовые навыки PyCharm
- Codex / Claude Code: skills, MCP servers, hooks, project memory, wiki-based knowledge workflow
- Basic VPS deployment

## Что важно для стажировки

Я хочу попасть в команду, где можно не просто выполнять учебные задания, а делать полезные автоматизации под реальные процессы: боты, внутренние инструменты, LLM-обработку документов, прототипы ассистентов, интеграции и улучшение рабочих сценариев.

Мне интересно развиваться в сторону AI automation / prompt engineering / junior AI product builder: соединять постановку задачи, промпты, AI-coding tools, API и понятный пользовательский опыт.

## Контакты

Контакты будут добавлены перед публикацией портфолио.
