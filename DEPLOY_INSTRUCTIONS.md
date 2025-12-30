# Инструкция по деплою тестового сайта

## Минимум действий (3 шага):

### 1. Создать репозиторий на GitHub
- Перейдите: https://github.com/new
- Имя: `bioinfo-basics`
- Сделайте **Public**
- Нажмите "Create repository"

### 2. Запушить файлы (выполните в терминале):

```bash
cd C:\dev\bioinfo-basics-test
git init
git add .
git commit -m "Initial commit - SEO test site"
git branch -M main
git remote add origin https://github.com/gorelikspb/bioinfo-basics-test.git
git push -u origin main
```

### 3. Включить GitHub Pages (1 клик):
- В репозитории: Settings → Pages
- Source: "Deploy from a branch"
- Branch: `main` / folder: `/ (root)`
- Save

**Готово!** Сайт будет доступен через 1-2 минуты:
`https://gorelikspb.github.io/bioinfo-basics-test/`

## Что дальше:

1. Добавить в Google Search Console
2. Добавить в Bing Webmaster Tools
3. Отправить sitemap
4. Проверить индексацию через 3-5 дней

