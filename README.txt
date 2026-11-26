XHYN V: сборка DXVK-Sarek 3.0.2 (SDL3 + экспорт для лаунчера) через GitHub Actions

1) На github.com создайте новый репозиторий (Public или Private, пустой).
2) Загрузите в него СОДЕРЖИМОЕ этой папки (Add file -> Upload files):
     .github/workflows/build.yml
     xhyn-sdl3-export.patch
     meta.json
   (папку .github перетащите целиком, чтобы сохранился путь .github/workflows/build.yml)
3) Вкладка Actions -> "Build DXVK-Sarek 3.0.2 for XHYN V" -> Run workflow.
4) Через 10-25 минут: в запуске внизу "Artifacts" -> скачайте dxvk-sarek-3.0.2-mali-xhyn.zip
   и добавьте его в лаунчере через "Add DXVK ZIP".
5) Если запуск красный: скачайте артефакт build-logs ИЛИ скопируйте текст шага
   "Show errors (if build failed)" и пришлите мне.
