# Public Repositories

Стратегия: основной `Portfolio`-репозиторий — это витрина. Каждый проект живет в отдельном публичном GitHub-репозитории, на который портфолио ссылается.

Исходные рабочие папки не трогаются. Для публикации используются чистые локальные staging-репозитории в sibling-каталоге:

`/Users/ivanzelentsov/IT-Проекты/Portfolio-Repos/`

## Repo Map

| Portfolio case | Local clean repo | GitHub URL | Source folder | Publication format |
| --- | --- | --- | --- | --- |
| Legal Verify | `Portfolio-Repos/legal-verify` | TODO | `Юрий/legal-verify` | code repo + case study |
| Serbian Teacher | `Portfolio-Repos/serbian-teacher` | TODO | `Учитель сербского ` | code repo + case study |
| Income Bot | `Portfolio-Repos/income-bot` | TODO | `Учет доходов и расходов/income-bot` | code repo + case study |
| Meeting Secretary | `Portfolio-Repos/meeting-secretary` | TODO | `Секретарь собраний` | code repo + case study, local clean version ready |
| Nutritionist Bot | `Portfolio-Repos/nutritionist` | TODO | `Нутрициолог/nutri-bot` | code repo + case study |
| Oleg Psychologist | `Portfolio-Repos/oleg-psychologist` | TODO | `Олег (психолог)` | case study / demo repo |
| PoetryForge | `Portfolio-Repos/poetryforge` | TODO | `Poetry_Killer` | code repo |
| Voice To Text | `Portfolio-Repos/voice-to-text` | TODO | `VoiceToText` | code repo, local clean version ready |

## Publication Rule

Do not publish source folders directly. Each clean repo starts with fresh git history and only receives files after manual cleanup.

Before any GitHub push:

- replace all secrets with placeholders;
- remove `.env`, keys, service account JSON, local databases, logs and private data;
- keep sanitized `AGENTS.md` and `CLAUDE.md` for reviewers who inspect the repo with Codex / Claude Code;
- run a secret scan;
- review README wording so it reflects AI-assisted development honestly;
- link the final GitHub URL back from this portfolio.
