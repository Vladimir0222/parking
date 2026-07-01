# Parking Matrix

Простий застосунок паркування (одна зона, 20 грн/год), дизайн у стилі "Матриці".

## Деплой на Vercel

### Варіант 1 — через сайт (найпростіше)
1. Розпакуй архів `parking-matrix.zip` в окрему папку.
2. Зайди на https://vercel.com/new
3. Внизу є опція "Deploy without Git" / перетягни папку — перетягни туди папку проєкту.
4. Vercel сам визначить статичний сайт (Framework Preset: Other) і задеплоїть.

### Варіант 2 — через Vercel CLI
```bash
npm i -g vercel
cd parking-matrix
vercel
```
Далі відповідай на питання за замовчуванням (Enter) — і отримаєш посилання.

### Варіант 3 — через GitHub
1. Створи новий репозиторій на GitHub і заливай туди вміст цієї папки.
2. На https://vercel.com/new вибери "Import Git Repository" і обери цей репозиторій.
3. Framework Preset залиш "Other", Build Command не потрібен — Deploy.

Файл `index.html` — це весь застосунок (HTML/CSS/JS в одному файлі), окремий білд не потрібен.
