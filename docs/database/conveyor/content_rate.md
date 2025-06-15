# Таблица content_rate

## Описание
Таблица `content_rate` предназначена для хранения оценок контента.

## Структура таблицы

| Колонка | Тип | Описание |
|---------|-----|-----------|
| id | uuid | Первичный ключ |
| content_id | uuid | Идентификатор контента |
| rate | int | Оценка |
| prompt | varchar | Промпт |
| grounding | varchar | Обоснование |
| tag | varchar | Тег оценки |
| create_time | timestamp | Время создания |
| create_user | varchar | Пользователь, который создал запись |
| last_update_time | timestamp | Время последнего изменения |
| last_update_user | varchar | Пользователь, который последним внес изменения | 