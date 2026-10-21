# Публикация страницы tech-support

## Файлы в архиве

| Файл | Действие |
|------|----------|
| `tech-support.html` | **Добавить** в корень репозитория Portfolio |
| `favicon.ico` | **Добавить** в корень (рядом с tech-support.html) |
| `index.html` | **Заменить** корневой index.html (добавлена 6-я карточка проекта) |
| `HOW_TO_PUBLISH.md` | Можно не коммитить |

## Локально

1. Распакуйте архив.
2. Скопируйте файлы в клон репозитория `Portfolio` (корень, где уже лежит `index.html`).
3. Проверьте локально (например, откройте `tech-support.html` в браузере).

```bash
cd /path/to/Portfolio
# после копирования файлов:
git add index.html tech-support.html favicon.ico
git commit -m "Add tech support service page and project card"
git push
```

## GitHub Pages

После push на `main` (или ветку Pages):

- Главная: https://slvm972.github.io/Portfolio/
- Страница услуги: https://slvm972.github.io/Portfolio/tech-support.html

Подождите 1–2 минуты и сделайте hard refresh (Ctrl+Shift+R).

## Важно

- `tech-support.html` — рекламная страница помощи с техникой для клиентов (пожилые, Петах-Тиква).
- В портфолио она участвует как шестой проект (карточка в `index.html`).
- WhatsApp: https://wa.me/972533341679  
- Телефон: +972 53-334-1679
