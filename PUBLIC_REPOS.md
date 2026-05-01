# Публичные репозитории

Стратегия: основной `Portfolio`-репозиторий — это витрина. Каждый проект живет в отдельном публичном GitHub-репозитории, на который портфолио ссылается.

Исходные рабочие папки не трогаются. Для публикации используются чистые локальные staging-репозитории в sibling-каталоге:

`/Users/ivanzelentsov/IT-Проекты/Portfolio-Repos/`

## Карта репозиториев

| Кейс | Локальный clean repo | GitHub URL | Исходная папка | Формат публикации |
| --- | --- | --- | --- | --- |
| Legal Verify | `Portfolio-Repos/legal-verify` | <https://github.com/JohnGreen1981/portfolio-legal-verify> | `Юрий/legal-verify` | code repo + case study, published |
| Serbian Teacher | `Portfolio-Repos/serbian-teacher` | <https://github.com/JohnGreen1981/portfolio-serbian-teacher> | `Учитель сербского ` | code repo + case study, published |
| Income Bot | `Portfolio-Repos/income-bot` | <https://github.com/JohnGreen1981/portfolio-income-bot> | `Учет доходов и расходов/income-bot` | code repo + case study, published |
| Meeting Secretary | `Portfolio-Repos/meeting-secretary` | <https://github.com/JohnGreen1981/portfolio-meeting-secretary> | `Секретарь собраний` | code repo + case study, published |
| Nutritionist Bot | `Portfolio-Repos/nutritionist` | <https://github.com/JohnGreen1981/portfolio-nutritionist> | `Нутрициолог/nutri-bot` | code repo + case study, published |
| Oleg Psychologist | `Portfolio-Repos/oleg-psychologist` | <https://github.com/JohnGreen1981/portfolio-oleg-psychologist> | `Олег (психолог)` | case study / demo repo, published |
| PoetryForge | `Portfolio-Repos/poetryforge` | <https://github.com/JohnGreen1981/portfolio-poetryforge> | `Poetry_Killer` | code repo, published |
| Voice To Text | `Portfolio-Repos/voice-to-text` | <https://github.com/JohnGreen1981/portfolio-voice-to-text> | `VoiceToText` | code repo, published |

## Правило публикации

Не публиковать исходные рабочие папки напрямую. Каждый clean repo начинается с новой git-истории и получает файлы только после ручной очистки.

Перед любым GitHub push:

- заменить все секреты на placeholder-значения;
- удалить `.env`, ключи, service account JSON, локальные базы, логи и приватные данные;
- оставить sanitized `AGENTS.md` и `CLAUDE.md` для проверяющих, которые будут смотреть репозиторий через Codex / Claude Code;
- запустить проверку на секреты;
- проверить формулировки README, чтобы они честно отражали AI-assisted development;
- добавить финальный GitHub URL обратно в это портфолио.
