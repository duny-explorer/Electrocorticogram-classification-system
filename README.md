
# ⚡ Система классификации электрокортикограмм

## 📄 Описание проекта

Данный проект представляет собой систему для классификации электрокортикограмм (ЭКоГ) крыс, разработанную как решение кейса на хакатоне "Цифровой Прорыв" от команды **WGHack**. Система работает в режиме реального времени и не требует подключения к интернету, что позволяет использовать её автономно. Приложение демонстрирует высокую скорость обработки данных, что делает его подходящим для использования даже на слабых ПК.

Проект построен на основе методов обработки сигналов и глубинного обучения, включая разложение в ряды Фурье и использование сверточных нейросетей для классификации. Система способна обрабатывать данные как в обычном, так и в потоковом режиме, обеспечивая высокую точность и производительность.

## 🌟 Основные возможности

1. **🛠️ Автономная работа** — приложение не требует подключения к интернету.
2. **⏱️ Потоковая передача** — поддерживает как обычную, так и потоковую обработку данных в реальном времени.
3. **⚙️ Высокая производительность** — оптимизировано для работы на слабых ПК, обеспечивая быструю обработку данных.
4. **📈 Алгоритмы обработки** — использование разложения в ряды Фурье для выделения частотных характеристик, а также дополнительных признаков для обучения модели.
5. **🤖 Сверточные нейросени** — основной алгоритм для классификации ЭКоГ сигналов, что позволяет добиться высокой точности.

## 📂 Структура проекта

- `app` — директория с Flutter-приложением, реализующим интерфейс для пользователя.
- `research` — директория с Python-скриптами для анализа и обработки данных ЭКоГ. Включает:
  - Алгоритмы разложения сигналов в ряды Фурье.
  - Скрипты для генерации дополнительных признаков.
  - Модель классификации на основе градиентного бустинга.

## 🔧 Технические требования

- **Flutter SDK** — для запуска пользовательского интерфейса.
- **Windows 7** — минимальная OC для работоспособности приложения
- **Python 3.8+** — для анализа данных и выполнения алгоритмов классификации.
- **🌐 Не требует интернет-соединения** — полностью автономное решение.

## 🚀 Установка и запуск

1. Скачайте приложение с раздела Releases
2. Запустите файл `ai25front.exe`
