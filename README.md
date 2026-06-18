# Bashta 58

Празничен статичен сайт за рожден ден, готов за Vercel.

## Какво има вътре

- `index.html` - цялото приложение: дизайн, текстове, интеракции, галерия и 58 наздравици.
- `vercel.json` - лека Vercel конфигурация за чисти URL-и и базови security headers.
- `.gitignore` - файлове, които не трябва да влизат в repo-то.

## Deploy през GitHub + Vercel

1. Създай ново repo в GitHub, например `bashta-58`.
2. Качи файловете от тази папка в root-а на repo-то.
3. Влез във Vercel и избери `New Project`.
4. Import-ни GitHub repo-то.
5. Настройки:
   - Framework Preset: `Other`
   - Root Directory: `.`
   - Build Command: остави празно
   - Output Directory: остави празно
6. Натисни `Deploy`.

## Качване през terminal

```powershell
git init
git add .
git commit -m "Add birthday tribute site"
git branch -M main
git remote add origin https://github.com/USERNAME/bashta-58.git
git push -u origin main
```

После във Vercel избираш repo-то и deploy.

## Снимки

Галерията съдържа 8 постоянни семейни снимки, без заглавия и описания върху тях. Оптимизираните файлове са в `assets/photos`.
