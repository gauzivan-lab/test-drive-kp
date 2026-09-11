# AI Reels — Тест-драйв $500 (Коммерческое предложение)

Интерактивный лендинг коммерческого предложения с видеоплеером Reels, галереей каруселей, кейсами и условиями спецпредложения «Тест-драйв за $500».

## Структура проекта
- `index.html` — основная разметка, стили и скрипты лендинга
- `reels/` — видеоролики MP4 и превью WEBP (55+ референсов)
- `carousels/` — слайды экспертных постов-каруселей
- `cases/` — графические материалы кейсов
- `netlify.toml` — конфигурация заголовков и билда для деплоя на Netlify

---

## Варианты развёртывания (Deploy)

### 1. Деплой на Netlify через GitHub (Рекомендуется)
1. Откройте [Netlify Dashboard](https://app.netlify.com/).
2. Нажмите **Add new site** → **Import an existing project** → **GitHub**.
3. Выберите репозиторий `gauzivan-lab/test-drive-kp`.
4. Настройки сборки:
   - **Base directory**: оставить пустым (корень)
   - **Build command**: оставить пустым
   - **Publish directory**: `.` (или оставить пустым)
5. Нажмите **Deploy test-drive-kp**.
6. В разделе **Domain management** привяжите нужный кастомный домен.

### 2. Деплой на Netlify через CLI
```bash
npm install -g netlify-cli
netlify login
netlify deploy --prod --dir=.
```

### 3. Деплой на Vercel
```bash
npx vercel --prod
```

---

## Текущие рабочие ссылки
- **Vercel (Production)**: [https://test-drive-kp.vercel.app/](https://test-drive-kp.vercel.app/)
- **Hostinger Server (Mirror)**: [https://chat.s-m-g.online/test-drive-kp/](https://chat.s-m-g.online/test-drive-kp/)
