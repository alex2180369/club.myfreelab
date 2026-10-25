# Aurum Circle: сайт трейдинг-клуба

Учебный проект по реальному заказу с FL.ru. Разбор заказа и тексты: [CASE.md](CASE.md).

Сайт: https://club.myfreelab.ru

## Состав

```text
index.html                   страница
css/styles.css               стили и подключение шрифтов
js/main.js                   меню, анимация, форма заявки
fonts/                       Cormorant Garamond и Inter (кириллица и латиница)
google-apps-script/Code.gs   приём заявок в Google Таблицу
favicon.svg
```

Сборки нет. Для просмотра достаточно любого статического сервера:

```bash
python3 -m http.server 8000
```

## Подключить приём заявок

1. Разверните `google-apps-script/Code.gs` как веб-приложение (подробно в CASE.md, раздел 10).
2. Вставьте полученный URL в `js/main.js`, в `SITE_CONFIG.googleSheetsUrl`.

Все цифры, цены и отзывы на странице демонстрационные.
