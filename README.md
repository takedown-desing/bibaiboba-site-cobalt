# Биба и Боба: сайт агентства, вариант «Cobalt»

Третий вариант дизайна. Структура и приёмы взяты у референса из папки `дизайн` (страница SEO-агентства): скруглённые цветные панели, двухцветные заголовки, бенто-сетки, вкладки кейсов, панель заявки с белой формой. Палитра своя: кобальт, тёмно-синий, солнечно-жёлтые кнопки и мятный акцент. Другие варианты: [Light](https://github.com/takedown-desing/bibaiboba-site-light), [Space](https://github.com/takedown-desing/bibaiboba-site-space).

- Стек: Astro 7 (статичные страницы), чистый CSS и JS, шрифты Inter и Unbounded.
- Контент: те же markdown-черновики из пайплайна агентства (`src/content/pages/`), картинки светлой серии из ChatGPT.
- Публикация: GitHub Actions, затем GitHub Pages. Превью закрыто от индексации.

```bash
npm install
npm run sync     # свежие черновики из пайплайна (локально)
npm run build
npm run qa       # проверка сборки, отчёт в qa-report.md
```
