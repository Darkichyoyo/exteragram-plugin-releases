# exteraGram plugin releases

Опубликованные сборки плагинов для exteraGram.

## Актуальные версии

| Плагин | Версия | Файл |
|---|---|---|
| ExteraGram Diagnostics | 0.5.3 | [`exteragram_diagnostics.plugin`](plugins/exteragram_diagnostics/0.5.3/exteragram_diagnostics.plugin) |
| MultiTools | 3.2 | [`multi_tools.plugin`](plugins/multi_tools/3.2/multi_tools.plugin) |
| Virtual Premium Reactions | 4.0 | [`virtual_premium_reactions.plugin`](plugins/virtual_premium_reactions/4.0/virtual_premium_reactions.plugin) |

Отдельная сборка MultiTools без функции удалённых сообщений лежит в [`plugins/multi_tools/3.3-bez-udalennyh`](plugins/multi_tools/3.3-bez-udalennyh).

## Структура

- `plugins/<plugin_id>/<version>/` — файлы каждой опубликованной версии. Старые версии сохраняются.
- `releases.json` — манифест актуальных версий (URL, размер, SHA-256) для автообновления.

При публикации новой версии добавьте папку с версией и обновите `releases.json` и таблицу выше.
