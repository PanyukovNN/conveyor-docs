# Таблица processing_events

## Описание
Таблица `processing_events` предназначена для хранения событий на обработку контента.

## Структура таблицы

| Колонка | Тип | Описание |
|---------|-----|-----------|
| id | uuid | Первичный ключ |
| type | varchar | Тип события |
| content_id | uuid | Идентификатор контента |
| conveyor_type | varchar | Тип конвейера |
| conveyor_tag | varchar | Тег кастомизации конвейера |
| prompt_id | uuid | Идентификатор промта |
| content_batch_id | uuid | Идентификатор группы контента |
| publishing_channel_id | uuid | Идентификатор канала отправки |
| create_time | timestamp | Время создания |
| create_user | varchar | Пользователь, который создал запись |
| last_update_time | timestamp | Время последнего изменения |
| last_update_user | varchar | Пользователь, который последним внес изменения | 