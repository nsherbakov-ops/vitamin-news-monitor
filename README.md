# vitamin-news-monitor

Облачный новостной мониторинг для Vitamin.tools на GitHub Actions — работает при выключенном компьютере.

## Что делает
Каждый час с **10:00 до 19:00 МСК** (cron `0 7-16 * * *`, UTC) запускается GitHub Action, который:
1. Через Claude (official `anthropics/claude-code-action`, авторизация OAuth-токеном подписки) проверяет 12 источников рекламных новостей;
2. Оценивает релевантность миру Vitamin.tools и собирает дайджест;
3. Постит его в Telegram-канал **@monitoringnewsvitamintools** (chat_id `-1003969663541`) через Bot API.

**Гарантированные дайджесты в 10:00 и 15:00 МСК** (≥3 новости каждый, ≥6 в день) — даже если день «слабый». В остальные часы постит только реально новые релевантные новости.

Логика прогона — в [`MONITOR.md`](./MONITOR.md). Дедуп — в [`state/ledger.md`](./state/ledger.md) (коммитится обратно после каждой публикации).

## Секреты репозитория (Settings → Secrets and variables → Actions)
- `CLAUDE_CODE_OAUTH_TOKEN` — токен подписки Claude (`claude setup-token`).
- `TELEGRAM_BOT_TOKEN` — токен бота @novostivitamintoolsbot (админ канала).

## Ручной запуск
Actions → «Vitamin news monitor» → Run workflow (workflow_dispatch).

## Ограничения
- GitHub может задерживать запуск по расписанию на несколько минут.
- Статьи и картинки (ChatGPT) здесь НЕ генерируются — это делается отдельно по запросу в чате (картинки требуют браузерного ChatGPT).
