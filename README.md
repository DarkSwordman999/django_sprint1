<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20&height=180&section=header&text=Blogicum&fontSize=70&fontAlignY=35&desc=Django%20Blog%20Platform%20%7C%20Yandex%20Practicum&descAlignY=55&descSize=18" alt="Blogicum banner" width="100%">

<br>

<img src="https://img.shields.io/badge/Python-3.10%2B-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
<img src="https://img.shields.io/badge/Django-5.1.1-092E20?style=for-the-badge&logo=django&logoColor=white" alt="Django">
<img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQLite">
<img src="https://img.shields.io/badge/Bootstrap-5.0.1-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white" alt="Bootstrap">

<br>

<img src="https://img.shields.io/badge/Pytest-8.3.3-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white" alt="Pytest">
<img src="https://img.shields.io/badge/pytest--django-4.9.0-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white" alt="pytest-django">
<img src="https://img.shields.io/badge/Flake8-7.1.1-FFD43B?style=for-the-badge&logo=python&logoColor=black" alt="Flake8">
<img src="https://img.shields.io/badge/Yandex_Practicum-FF0000?style=for-the-badge&logo=yandex&logoColor=white" alt="Yandex Practicum">

<br><br>

### 📝 Blogicum — блог-платформа на Django

**Учебный проект в рамках курса «Python-разработчик» от Яндекс Практикума**

</div>

---

## 📖 О проекте

**Blogicum** — учебная блог-платформа на **Django**, предназначенная для публикации и просмотра записей пользователей.

Пользователи смогут:

* ✍️ публиковать записи;
* 🏷️ привязывать публикации к категориям;
* 👀 просматривать посты других авторов;
* 💬 взаимодействовать с публикациями через комментарии;
* 👤 создавать аккаунты и управлять профилем.

На текущем этапе проекта реализован **первый спринт курса** — статическая вёрстка основных страниц с использованием **Bootstrap**.

Django-логика, модели, представления и работа с базой данных будут добавляться на следующих этапах разработки.

---

## ✅ Что уже реализовано

| Компонент              | Статус | Описание               |
| :--------------------- | :----: | :--------------------- |
| 📰 Лента записей       |    ✅   | `index.html`           |
| 📄 Страница поста      |    ✅   | `detail.html`          |
| 🏷️ Страница категории |    ✅   | `category.html`        |
| ℹ️ О проекте           |    ✅   | `about.html`           |
| 📜 Наши правила        |    ✅   | `rules.html`           |
| 🧭 Навигация           |    ✅   | Общая для всех страниц |
| 🦶 Футер               |    ✅   | Общий для всех страниц |
| 🎨 Bootstrap           |    ✅   | Локальная версия 5.0.1 |
| 🖼️ Иконки и логотип   |    ✅   | Подключены локально    |

---

## 🚧 В разработке

Следующие этапы проекта предполагают постепенный переход от статической вёрстки к полноценному Django-приложению.

* 🔄 Перенос HTML в Django-шаблоны.
* 🗄️ Создание моделей постов и категорий.
* 💾 Подключение реальных данных из базы данных.
* 🔐 Регистрация и авторизация пользователей.
* 👤 Пользовательские профили.
* 💬 Система комментариев.
* ⚙️ Динамическое управление контентом.

---

## 🛠️ Технологический стек

<div align="center">

| Технология               |  Версия  | Назначение                 |
| :----------------------- | :------: | :------------------------- |
| 🐍 **Python**            |  `3.10+` | Основной язык разработки   |
| 🌐 **Django**            |  `5.1.1` | Веб-фреймворк              |
| 🗃️ **SQLite**           |     —    | База данных                |
| 🎨 **Bootstrap**         |  `5.0.1` | CSS-фреймворк              |
| 🧪 **Pytest**            |  `8.3.3` | Тестирование               |
| 🔌 **pytest-django**     |  `4.9.0` | Интеграция pytest с Django |
| 🧹 **Flake8**            |  `7.1.1` | Статический анализ кода    |
| 📝 **flake8-docstrings** |  `1.7.0` | Проверка docstring         |
| 📐 **pep8-naming**       | `0.14.1` | Проверка именования        |

</div>

---

## 📂 Структура проекта

```text
django_sprint1/
│
├── blogicum/
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
│
├── html/
│   ├── css/
│   │   └── bootstrap.min.css
│   │
│   ├── img/
│   │   ├── logo
│   │   ├── icons
│   │   └── favicon
│   │
│   ├── about.html
│   ├── category.html
│   ├── detail.html
│   ├── index.html
│   └── rules.html
│
├── tests/
│
├── .flake8
├── .gitignore
├── LICENSE
├── README.md
├── pytest.ini
├── requirements.txt
└── manage.py
```

### 📁 Основные директории и файлы

| Путь               | Назначение                                |
| :----------------- | :---------------------------------------- |
| `blogicum/`        | Конфигурация Django-проекта               |
| `html/`            | Статические HTML-страницы первого спринта |
| `html/css/`        | Локальные CSS-файлы                       |
| `html/img/`        | Изображения, иконки и логотип             |
| `tests/`           | Автоматические тесты                      |
| `manage.py`        | Управление Django-проектом                |
| `pytest.ini`       | Конфигурация pytest                       |
| `.flake8`          | Настройки линтера                         |
| `requirements.txt` | Зависимости проекта                       |

---

<details>
<summary><h2>🚀 Установка и запуск</h2></summary>

### 📋 Требования

Перед запуском убедитесь, что установлены:

* **Python 3.10+**
* **pip**
* **Git**

### 1. Клонирование репозитория

```bash
git clone https://github.com/DarkSwordman999/django_sprint1.git
cd django_sprint1
```

### 2. Создание виртуального окружения

```bash
python -m venv venv
```

### 3. Активация окружения

**Windows:**

```bash
venv\Scripts\activate
```

**macOS / Linux:**

```bash
source venv/bin/activate
```

### 4. Установка зависимостей

```bash
pip install -r requirements.txt
```

### 5. Применение миграций

```bash
python manage.py migrate
```

### 6. Запуск сервера разработки

```bash
python manage.py runserver
```

После запуска проект будет доступен по адресу:

```text
http://127.0.0.1:8000/
```

> На текущем этапе Django-шаблоны ещё не подключены. Статическую вёрстку можно открыть непосредственно из директории `html/`, например `html/index.html`.

</details>

---

<details>
<summary><h2>🧪 Тестирование</h2></summary>

Для тестирования используется **pytest** совместно с **pytest-django**.

Конфигурация находится в `pytest.ini`.

### ▶️ Запуск тестов

```bash
pytest
```

### ⚙️ Основные настройки

```ini
DJANGO_SETTINGS_MODULE = blogicum.settings
pythonpath = blogicum/
testpaths = tests/
```

| Параметр                 | Назначение                                    |
| :----------------------- | :-------------------------------------------- |
| `DJANGO_SETTINGS_MODULE` | Указывает настройки Django для тестовой среды |
| `pythonpath`             | Определяет путь для импорта модулей проекта   |
| `testpaths`              | Указывает директорию с тестами                |

</details>

---

<details>
<summary><h2>🧹 Линтинг и качество кода</h2></summary>

Для статического анализа используется **Flake8** с дополнительными плагинами:

* `flake8-docstrings`
* `pep8-naming`

Конфигурация находится в `.flake8`.

### ▶️ Запуск линтера

```bash
flake8 .
```

### 🔍 Проверки

Линтер анализирует исходный код проекта с учётом настроек `.flake8`.

Из проверки исключены:

```text
tests/
*/migrations/
venv/
env/
```

Для `settings.py` отключено правило `E501`, отвечающее за ограничение длины строки.

</details>

---

## 🗺️ План развития

```text
Статическая вёрстка
        │
        ▼
Django Templates
        │
        ▼
Модели и база данных
        │
        ▼
Динамические страницы
        │
        ▼
Авторизация и профили
        │
        ▼
Комментарии
        │
        ▼
Полноценная блог-платформа
```

Проект развивается поэтапно в соответствии с учебной программой курса.

---

## 📄 Лицензия

В репозитории присутствует файл [`LICENSE`](./LICENSE), однако на текущем этапе он пуст.

Лицензия будет добавлена на последующих этапах разработки проекта.

---

## 👤 Автор

<div align="center">

### **DarkSwordman999**

<a href="https://github.com/DarkSwordman999">
<img src="https://img.shields.io/badge/GitHub-DarkSwordman999-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
</a>

<br><br>

<a href="https://github.com/DarkSwordman999/django_sprint1">
<img src="https://img.shields.io/badge/Repository-django__sprint1-181717?style=for-the-badge&logo=github&logoColor=white" alt="Repository">
</a>

</div>

---

<div align="center">

### 🎓 Yandex Practicum

Проект создан в рамках курса
**«Python-разработчик» от Яндекс Практикума**

<br>

> 📝 **Blogicum** — учебный проект для практики Django,
> HTML/CSS, Bootstrap, тестирования и организации веб-приложений.

<br>

⭐ **Если проект был полезен — поставь звезду репозиторию!**

</div>

