# Описание проекта - Разработка дашборда для Яндекс.Дзен

## Данные

Для исследования доступна информация из базы данных `zen`.

**Состав данных**:

- **record_id** — первичный ключ,
- **item_topic** — тема карточки,
- **source_topic** — тема источника,
- **age_segment** — возрастной сегмент,
- **dt** — дата и время,
- **visits** — количество событий.

## Задача

Используя данные Яндекс.Дзена, построить дашборд с метриками взаимодействия пользователей с карточками статей 

## Используемые библиотеки
*pandas*, *SQLAlchemy*, PostgreSQL, Tableau