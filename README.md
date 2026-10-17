# Информационный сайт Local YouTube Shorts

Планируемый репозиторий: `dzekovdzek/local-shorts-info`.

Публикуются только `index.html`, `privacy.html`, `terms.html`, `style.css`, `.nojekyll` и этот README. Здесь нет загрузчика, видео, OAuth client JSON, токенов, Channel ID или журнала загрузок. Не копируйте сюда папку youtube-shorts.

Страницы статические и не требуют сборки или зависимостей. Ссылки относительные, подходят для GitHub Pages с project path. Предлагаемый адрес: `https://dzekovdzek.github.io/local-shorts-info/`; до успешного развёртывания он не считается существующим.

После публикации через Settings → Pages → Deploy from a branch → main → /(root) проверить три страницы по HTTPS без входа. Затем добавить URL-prefix property в Google Search Console под Google-аккаунтом владельца Cloud Project. Разместить выданный Google HTML-файл без изменения имени/содержимого или meta-тег в index.html. Файл/тег проверки нельзя удалять после подтверждения.

После подтверждения владения проверить, принимает ли Google Auth Platform поддомен `dzekovdzek.github.io` в Authorized domains. Добавить точные homepage, privacy и terms URL в Branding. GitHub Pages и проверка URL-prefix сами по себе не гарантируют приём домена в OAuth: результат нужно проверить в Console. Не добавлять общий домен github.io как будто он принадлежит пользователю.

Репозиторий и сайт будут публичными. Публикация, подтверждение владения и переход OAuth в Production — отдельные действия; их результаты необходимо подтвердить. Видео от этого не становятся публичными.
