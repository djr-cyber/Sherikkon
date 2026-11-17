# Sherikkon Consulting — сайт

Одностраничный сайт на чистых HTML, CSS и JavaScript, без фреймворков и сборщиков. Три языка: русский, английский, узбекский.

## Папки

- `sherikkon-site/` — исходники для правок: `index.html` и `assets/` (шрифты Alegreya Sans, фото, превью для ссылок).
- `deploy/` — сжатая копия того же сайта. Её содержимое загружается на хостинг.

После любой правки в `sherikkon-site/` копию в `deploy/` нужно пересобрать (сжатие HTML, CSS и JS через html-minifier-terser и копирование `assets/`).

## Локальный просмотр

```bash
npx http-server sherikkon-site -p 8080
```

Затем откройте http://localhost:8080.
