
# MJML Gulp Starter

## Введение

### MJML Starter for Email with Gulp, BrowserSync & Imagemin.
Супербыстрый препроцессор для верстки E-Mail писем. Данная сборка содержит в себе npm-плагины для сжатия картинок, Live-Reload'a и конвертации в html
### Начальный пакет :
- [MJML](https://mjml.io/) 4 процессор для Gulp (gulp-mjml),
- **BrowserSync** сервер для проверки работы в браузере с автообновлением,
- **Imagemin** для _lossless_ изображений сжимает :
  * **gifsicle** — Compress GIF images
  * **jpegtran** — Compress JPEG images
  * **optipng** — Compress PNG images
  * **svgo** — Compress SVG images
- **MJML** внутри исходный шаблон MJML.


## Порядок установки

### Обязательно
- [NodeJS](https://nodejs.org/en/) (6 или выше)
- [Gulp](https://gulpjs.com/) в командной строке npm install --global gulp-cli

### Опционально (система контроля версий)
- [Git](https://git-scm.com/)

Можно скачать репозиторий кнопкой Download ZIP.

### Порядок работы

Надо открыть папку в командной строке и установить зависимости (автоматически через package.json):

```bash
$ cd mjml-gulp-starter
$ npm install
```

## Использование

Итак, запустите `gulp watch` для старта Gulp & BrowserSync. Все, что вы сделаете, в итоге попадет в папку `dist`.

```bash
$ gulp watch
```
Локальный URL :
```bash
http://localhost:3000
```

### Готовый билд
Когда все работы по верстке завершены, просто напишите в командной строке `gulp` и тогда все изменения сохранятся :

```bash
$ gulp
```

Enjoy coding ✌️
