---
layout: layouts/base.njk
eleventyNavigation:
  key: О блоге
  order: 4

title: О блоге
date: 2024-10-13
---

# О блоге

Блог основан на технологии [`11ty`](https://www.11ty.dev), тема [`eleventy-base-blog`](https://github.com/11ty/eleventy-base-blog)

- Шаблонизатор: [`nunjucks`](https://www.npmjs.com/package/nunjucks)
- Минификация: [`clean-css`](https://www.npmjs.com/package/clean-css)

## CI/CD

Для автоматической сборки и деплоя используются GitHub Actions, а публикуется на GitHub Pages. Флоу деплоя описано в [`gh-pages.yml`](https://github.com/asmalcev/notes/blob/main/.github/workflows/gh-pages.yml), в нем происходит установка зависимостей, сборка проекта и публикация собранных документов в ветке `gh-pages`. CI/CD флоу поставляется вместе с темой `eleventy-base-blog`
