# SapphireBet NGR Calculator

Статический калькулятор NGR-целей для iGaming-маркетинга. Показывает воронку регистраций, конверсии, пути достижения целей по каждому гео.

## Структура

```
├── index.html                          — основное приложение (React + Babel CDN)
├── src/original/
│   └── ngr-calculator-source.html      — исходная версия
├── docs/
│   └── project-notes.md                — заметки по проекту
├── .github/workflows/
│   └── deploy.yml                      — автодеплой на GitHub Pages
├── LICENSE
└── .gitignore
```

## Локальный запуск

Откройте `index.html` в браузере — сборка не требуется.

## GitHub Pages

Проект автоматически деплоится на GitHub Pages при пуше в `main` через GitHub Actions.

Для ручной настройки:
1. Откройте **Settings → Pages** в репозитории.
2. В **Build and deployment** выберите **GitHub Actions**.
3. Workflow `deploy.yml` запустится автоматически.

## Технологии

- **React 18** (CDN)
- **Babel Standalone** (JSX-компиляция в браузере)
- **Google Fonts** (JetBrains Mono, Inter)
- Без сборщика, без npm, без node_modules
