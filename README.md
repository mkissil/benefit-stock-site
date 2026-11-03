# План роста Benefit Stock

Статический сайт: план роста на год, герой бренда Stockomat, рынок, каналы, цифры и наброски платформы Second Season.

Сборки нет. Всё лежит в корне репозитория: `index.html` и картинки рядом. Рендеры героя сделаны с ИИ. Поисковики сайт не индексируют (`robots.txt` и заголовок `X-Robots-Tag`).

## Посмотреть локально

Открыть `index.html` в браузере или выполнить `npx serve .` в папке проекта.

## Выложить на Vercel

Через GitHub: vercel.com/new, Import Git Repository, выбрать этот репозиторий. Framework Preset: Other. Build Command и Output Directory оставить пустыми. Deploy. Каждый пуш в `main` дальше обновляет сайт сам.

Без GitHub: перетащить папку проекта на vercel.com/new или выполнить `npx vercel --prod`.
