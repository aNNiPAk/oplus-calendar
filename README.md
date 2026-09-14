# OPlus Calendar

Канал обновлений оригинального приложения `com.oplus.calendar` для Obtainium.

APK извлекаются из OTA realme 16 Pro+ (RMX5131) проектом [OPlus Stock App Bot](https://github.com/aNNiPAk/oplus-stock-app-bot). Перед публикацией проверяются версия и сертификат подписи.

## Запуск

Откройте [Actions → Update OPlus Calendar](https://github.com/aNNiPAk/oplus-calendar/actions/workflows/update.yml) и нажмите Run workflow.

- `dry_run = true`: извлечь APK и проверить возможность обновления, без публикации.
- `dry_run = false`: опубликовать обновление, если versionCode увеличился и подпись совместима.

Обновление также запускается ежедневно в 04:23 UTC. Используется встроенный GITHUB_TOKEN этого репозитория; отдельный PAT не требуется.

## Obtainium

После появления первого APK в Releases добавьте `https://github.com/aNNiPAk/oplus-calendar` как источник Obtainium.
