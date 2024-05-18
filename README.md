# Учебная система intellity code

## Описание проекта

Данный проект представляет собой учебную систему, разработанную для облегчения процесса обучения и администрирования курсов. Система состоит из двух основных компонентов:

- **Frontend**: Разработан с использованием React, обеспечивает интерактивный пользовательский интерфейс для студентов и преподавателей.
- https://github.com/twoballs-ai/lms_front
- **Backend**: Создан на основе FastAPI, обеспечивает быстрый и безопасный доступ к данным и функционалу системы.
- https://github.com/twoballs-ai/intellity-back-final

## Функциональные возможности

### Для студентов

- Просмотр доступных курсов
- Регистрация на курсы
- Выполнение и сдача домашних заданий
- Отслеживание прогресса и оценок

### Для преподавателей

- Создание и управление курсами
- Публикация материалов и заданий
- Оценка домашних заданий студентов
- Анализ успеваемости студентов

## Установка и запуск

### Необходимые компоненты

- Node.js
- Python 3.7+
- FastAPI
- PostgreSQL (или другая база данных)

### Установка Frontend

1. Клонируйте репозиторий:

    ```bash
    git clone [https://github.com/yourusername/education-system.git](https://github.com/twoballs-ai/lms_front.git)
    ```

2. Установите зависимости:



3. Запустите проект:



### Установка Backend

1. Клонируйте репозиторий:

    ```bash
    git clone [https://github.com/yourusername/education-system.git](https://github.com/twoballs-ai/intellity-back-final.git)
    ```

2. Создайте виртуальное окружение и активируйте его:

    ```bash
    используйте Pyenv Poetry
    ```

3. Установите зависимости:

    ```bash
    poetry install
    ```

4. Создайте файл `.env` и добавьте необходимые параметры:

    ```
    DATABASE_URL=postgresql://user:password@localhost/dbname
    SECRET_KEY=your_secret_key
    ```

5. Запустите сервер:

    ```bash
    uvicorn main:app --reload
    ```


## Контакты

Если у вас есть вопросы или предложения, пожалуйста, свяжитесь с нами по электронной почте: [bogatyrev_boris@rambler.ru](mailto:bogatyrev_boris@rambler.ru).
