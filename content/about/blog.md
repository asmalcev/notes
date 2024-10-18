---
layout: layouts/base.njk
eleventyNavigation:
  key: О блоге
  order: 4

title: О блоге
date: 2024-10-13
description: Отчет по практической работе для ВУЗа
---

# О блоге

Блог основан на технологии [`11ty`](https://www.11ty.dev), тема [`eleventy-base-blog`](https://github.com/11ty/eleventy-base-blog)

- Шаблонизатор: [`nunjucks`](https://www.npmjs.com/package/nunjucks)
- Минификация: [`clean-css`](https://www.npmjs.com/package/clean-css)

## CI/CD

Для автоматической сборки и деплоя используются GitHub Actions, а публикуется сайт на GitHub Pages. Флоу деплоя описано в [`gh-pages.yml`](https://github.com/asmalcev/notes/blob/main/.github/workflows/gh-pages.yml), в нем происходит установка зависимостей, сборка проекта и публикация собранных документов в ветке `gh-pages`.

Флоу поставляется вместе с темой `eleventy-base-blog`, поэтому не потребовалось никаких дополнительных действий.

## Изменение темы и дефолтных шаблонов

- Добавлен footer с информацией об авторе
- Добавлены метаданные об авторе
- На главной странице добавлена небольшая SVG-анимация
