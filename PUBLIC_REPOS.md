# Публичные репозитории

Стратегия: основной `Portfolio`-репозиторий — это витрина. Каждый проект живет в отдельном публичном GitHub-репозитории, на который портфолио ссылается.

Исходные рабочие папки не трогаются. Для публикации используются чистые локальные staging-репозитории в sibling-каталоге:

`/Users/ivanzelentsov/IT-Проекты/Portfolio-Repos/`

## Карта репозиториев

| Кейс | Локальный clean repo | GitHub URL | Исходная папка | Формат публикации |
| --- | --- | --- | --- | --- |
| Legal Verify | `Portfolio-Repos/legal-verify` | TODO | `Юрий/legal-verify` | code repo + case study, local clean repo готов |
| Serbian Teacher | `Portfolio-Repos/serbian-teacher` | TODO | `Учитель сербского ` | code repo + case study, local clean repo готов |
| Income Bot | `Portfolio-Repos/income-bot` | TODO | `Учет доходов и расходов/income-bot` | code repo + case study |
| Meeting Secretary | `Portfolio-Repos/meeting-secretary` | TODO | `Секретарь собраний` | code repo + case study, local clean repo готов |
| Nutritionist Bot | `Portfolio-Repos/nutritionist` | TODO | `Нутрициолог/nutri-bot` | code repo + case study |
| Oleg Psychologist | `Portfolio-Repos/oleg-psychologist` | TODO | `Олег (психолог)` | case study / demo repo |
| PoetryForge | `Portfolio-Repos/poetryforge` | TODO | `Poetry_Killer` | code repo, local clean repo готов |
| Voice To Text | `Portfolio-Repos/voice-to-text` | TODO | `VoiceToText` | code repo, local clean repo готов |

## Правило публикации

Не публиковать исходные рабочие папки напрямую. Каждый clean repo начинается с новой git-истории и получает файлы только после ручной очистки.

Перед любым GitHub push:

- заменить все секреты на placeholder-значения;
- удалить `.env`, ключи, service account JSON, локальные базы, логи и приватные данные;
- оставить sanitized `AGENTS.md` и `CLAUDE.md` для проверяющих, которые будут смотреть репозиторий через Codex / Claude Code;
- запустить проверку на секреты;
- проверить формулировки README, чтобы они честно отражали AI-assisted development;
- добавить финальный GitHub URL обратно в это портфолио.
