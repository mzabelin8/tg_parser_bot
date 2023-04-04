# news_bot

## Бот предназначен для подборки топа новостей в сфере it по заданным параметрам

В боте реализованы функци:

- Возможность выбора каналов
- Аггрегация может совершать за кастомное число дней-недель
- Можно задать ограничение на число собранных новостей-статей
- Возможность inline отправлять в группу-канал

Метрика для топа новостей основана на максимуме функции по следующим параметрам:
- Количество подписчиков в канале
- Подобранны коэффициенты для каждого канала
- Реакции на посты
- Количество просмотров на посте

Реализация бота написана в [tg_news_bot.py](https://github.com/mzabelin8/tg_parser_bot/blob/main/tg_news_bot.py)
