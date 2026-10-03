Публичная политика конфиденциальности «Орбитальный док: Модули»

Этот каталог предназначен для отдельного публичного репозитория
https://github.com/jonkryl/orbital-dock-aa-privacy

Приложение: ru.jonkryl.orbitaldock.
Разработчик: Evgeniy Krylov. Контакт: jonkryl@gmail.com.

Файлы репозитория:
  index.html — автономная пользовательская политика на русском.
  .github/workflows/pages.yml — публикация GitHub Pages из main.
  README.txt — эта инструкция; она не включается в опубликованный сайт.

Начальная настройка владельцем:
1. Создать указанный публичный репозиторий и разместить содержимое этого
   каталога в корне main, сохранив путь .github/workflows/pages.yml.
2. В Settings → Pages выбрать Source: GitHub Actions.
3. При необходимости запустить Actions → Publish privacy policy → Run workflow
   из main. Последующие push в main автоматически публикуют изменения.
4. Дождаться успешного deployment в окружение github-pages и проверить
   страницу без авторизации по HTTPS.

Ожидаемый адрес после успешного развёртывания:
https://jonkryl.github.io/orbital-dock-aa-privacy/

До успешного deployment и проверки этот адрес не считается опубликованным.
После проверки укажите его в поле Privacy policy приложения Google Play.

Workflow не требует дополнительных секретов: используется GITHUB_TOKEN
с чтением исходников, pages:write и id-token:write только для deployment.
Публикуется исключительно index.html; в сайте нет JavaScript, аналитики,
рекламных библиотек, внешних шрифтов или файлов приватной подписи.

Текст сайта синхронизирован с канонической пользовательской политикой игры:
docs/privacy-policy.md и app/src/main/res/raw/privacy_policy.txt.
При изменении обработки данных обновляйте обе политики и дату редакции.

Источники настройки workflow (официальные):
https://docs.github.com/en/pages/getting-started-with-github-pages/using-custom-workflows-with-github-pages
https://github.com/actions/checkout/releases/tag/v7.0.1
https://github.com/actions/configure-pages/releases/tag/v6.0.0
https://github.com/actions/upload-pages-artifact/releases/tag/v5.0.0
https://github.com/actions/deploy-pages/releases/tag/v5.0.1

Внешние аккаунты этим комплектом файлов не изменялись. Публикация выполняется
владельцем репозитория; успешное локальное создание файлов не подтверждает
доступность сайта или приложения в Google Play.
