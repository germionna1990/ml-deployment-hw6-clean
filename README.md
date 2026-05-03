# ML Deployment HW6

## Описание
Асинхронный ML-конвейер обработки видео:
grayscale → face detection → mosaic

## Что реализовано
- AsyncAPI описание (`async.yaml`)
- Выбор брокера сообщений (RabbitMQ)
- Ленивый запуск модели (Lazy loading)
- Батчинг данных
- Асинхронная обработка через очередь

## Технологии
- Python
- OpenCV
- AsyncIO
- RabbitMQ (концептуально)
- AsyncAPI

## Автор
Ирина Дворяшина
