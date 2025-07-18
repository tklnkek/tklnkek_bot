# ридмишечка

**Telegram Bot для услуг разработки**

Этот бот предоставляет информацию об услугах разработки Telegram-ботов, Mini Apps и других сервисов, а также позволяет оставлять заявки.

## Функциональность
- Просмотр услуг (разработка ботов, Mini Apps, сопровождение, консультации)
- Оставление заявок с сохранением данных
- Многоплатформенное сохранение данных (локальный файл, Excel, Google Sheets)

## Установка и запуск

### Локальный запуск
1. Установка зависимостей:
   ```bash
   pip install -r requirements.txt
   ```
2. Запуск бота:
   ```bash
   python3 bot.py
   ```

**Данные сохраняются в:**
  - Локальный текстовый файл `applications.txt`
  - Excel файл `applications.xlsx`
  - Google Sheets (настраивается через `SPREADSHEET_ID` и `SHEET_NAME`)

## Команды
- `/start` - начать работу с ботом
- Основное взаимодействие через кнопки меню

## Ссылки
- Бот: [@tklnkek_bot](https://t.me/tklnkek_bot)
```

