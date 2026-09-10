<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20&height=180&section=header&text=Blogicum&fontSize=70&fontAlignY=35&desc=Django%20Blog%20Platform%20%7C%20Yandex%20Practicum&descAlignY=55&descSize=18" alt="Banner" width="100%">

<img src="https://img.shields.io/badge/Python-3.10%2B-blue?style=for-the-badge&logo=python&logoColor=white" alt="Python">
<img src="https://img.shields.io/badge/Django-5.1.1-092E20?style=for-the-badge&logo=django&logoColor=white" alt="Django">
<img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQLite">
<img src="https://img.shields.io/badge/Bootstrap-5.0.1-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white" alt="Bootstrap">

<br>

<img src="https://img.shields.io/badge/Pytest-8.3.3-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white" alt="Pytest">
<img src="https://img.shields.io/badge/pytest--django-4.9.0-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white" alt="pytest-django">
<img src="https://img.shields.io/badge/Flake8-7.1.1-yellow?style=for-the-badge&logo=python&logoColor=white" alt="Flake8">
<img src="https://img.shields.io/badge/Yandex-Practicum-red?style=for-the-badge&logo=yandex&logoColor=white" alt="Yandex Practicum">

<br><br>

<h2>🐍 Blogicum — блог-платформа на Django</h2>

<p><b>Учебный проект в рамках курса «Python-разработчик» от Яндекс Практикума</b></p>

</div>

<hr>

<h2>📖 О проекте</h2>

<p><b>Blogicum</b> — площадка для ведения блогов. Пользователи смогут публиковать посты, привязывать их к категориям и просматривать записи других авторов.</p>

<p>В первом спринте реализована <b>статическая вёрстка страниц</b> с использованием Bootstrap. Django-логика (модели, вью, шаблоны) будет добавлена на следующих этапах курса.</p>

<hr>

<h2>✅ Что уже сделано</h2>

<ul>
  <li>Свёрстана лента записей — <code>index.html</code>.</li>
  <li>Страница отдельного поста — <code>detail.html</code>.</li>
  <li>Страница категории — <code>category.html</code>.</li>
  <li>Статическая страница «О проекте» — <code>about.html</code>.</li>
  <li>Статическая страница «Наши правила» — <code>rules.html</code>.</li>
  <li>Общая навигация и футер для всех страниц.</li>
  <li>Подключены локальные стили Bootstrap, иконки и логотип.</li>
</ul>

<hr>

<h2>🚧 Что в разработке</h2>

<ul>
  <li>Перенос вёрстки в Django-шаблоны.</li>
  <li>Модели постов и категорий.</li>
  <li>Отображение реальных данных из БД.</li>
  <li>Регистрация, авторизация и профили пользователей.</li>
  <li>Комментарии к постам.</li>
</ul>

<hr>

<h2>🛠️ Технологии</h2>

<div align="center">

<table>
  <thead>
    <tr>
      <th align="left">Технология</th>
      <th align="left">Версия</th>
      <th align="left">Назначение</th>
    </tr>
  </thead>
  <tbody>
    <tr><td><b>Python</b></td><td>3.10+</td><td>Язык разработки</td></tr>
    <tr><td><b>Django</b></td><td>5.1.1</td><td>Веб-фреймворк</td></tr>
    <tr><td><b>SQLite</b></td><td>—</td><td>База данных</td></tr>
    <tr><td><b>Bootstrap</b></td><td>5.0.1</td><td>CSS-фреймворк</td></tr>
    <tr><td><b>Pytest</b></td><td>8.3.3</td><td>Тестирование</td></tr>
    <tr><td><b>pytest-django</b></td><td>4.9.0</td><td>Интеграция pytest с Django</td></tr>
    <tr><td><b>Flake8</b></td><td>7.1.1</td><td>Линтинг кода</td></tr>
    <tr><td><b>flake8-docstrings</b></td><td>1.7.0</td><td>Проверка docstring</td></tr>
    <tr><td><b>pep8-naming</b></td><td>0.14.1</td><td>Проверка именования</td></tr>
  </tbody>
</table>

</div>

<hr>

<h2>📂 Структура проекта</h2>

<pre><code>django_sprint1/
├── blogicum/                 # Django-проект (settings, urls, wsgi)
├── html/
│   ├── css/
│   │   └── bootstrap.min.css # Локальная копия Bootstrap 5.0.1
│   ├── img/                  # Логотип, иконки, favicon
│   ├── about.html            # Страница «О проекте»
│   ├── category.html         # Страница категории
│   ├── detail.html           # Страница отдельного поста
│   ├── index.html            # Лента записей
│   └── rules.html            # Страница «Наши правила»
├── tests/                    # Тесты проекта
├── .flake8                   # Конфигурация flake8
├── .gitignore                # Исключения Git
├── LICENSE                   # Лицензия проекта (файл пуст)
├── README.md                 # Документация
├── pytest.ini                # Конфигурация pytest
├── requirements.txt          # Зависимости проекта
└── manage.py                 # Управляющий скрипт Django</code></pre>

<hr>

<h2>🚀 Запуск</h2>

<h3>Требования</h3>
<ul>
  <li><b>Python</b> 3.10 или выше.</li>
  <li><b>pip</b> для установки зависимостей.</li>
</ul>

<h3>Шаги</h3>
<ol>
  <li>
    <b>Клонируйте репозиторий:</b>
    <pre><code>git clone https://github.com/DarkSwordman999/django_sprint1.git
cd django_sprint1</code></pre>
  </li>
  <li>
    <b>Создайте и активируйте виртуальное окружение:</b>
    <pre><code>python -m venv venv

# Windows:
venv\Scripts\activate

# macOS / Linux:
source venv/bin/activate</code></pre>
  </li>
  <li>
    <b>Установите зависимости:</b>
    <pre><code>pip install -r requirements.txt</code></pre>
  </li>
  <li>
    <b>Примените миграции:</b>
    <pre><code>python manage.py migrate</code></pre>
  </li>
  <li>
    <b>Запустите сервер разработки:</b>
    <pre><code>python manage.py runserver</code></pre>
  </li>
</ol>

<p>Пока Django-шаблоны не подключены, свёрстанные страницы можно открыть напрямую из папки <code>html/</code>, например <code>html/index.html</code>.</p>

<hr>

<h2>🧪 Тестирование</h2>

<p>Тесты запускаются через <b>pytest</b> с плагином <b>pytest-django</b>. Конфигурация — в <code>pytest.ini</code>.</p>

<pre><code>pytest</code></pre>

<p>Основные настройки:</p>
<ul>
  <li><code>DJANGO_SETTINGS_MODULE = blogicum.settings</code> — настройки Django для тестов.</li>
  <li><code>pythonpath = blogicum/</code> — корень проекта для импортов.</li>
  <li><code>testpaths = tests/</code> — тесты ищутся только в папке <code>tests/</code>.</li>
</ul>

<hr>

<h2>🧹 Линтинг</h2>

<p>Код проверяется линтером <b>flake8</b> с плагинами <code>flake8-docstrings</code> и <code>pep8-naming</code>. Настройки — в файле <code>.flake8</code>.</p>

<pre><code>flake8 .</code></pre>

<p>Из проверки исключены: <code>tests/</code>, <code>*/migrations/</code>, <code>venv/</code>, <code>env/</code>. Для <code>settings.py</code> отключено правило <code>E501</code> (длина строки).</p>

<hr>

<h2>📄 Лицензия</h2>

<p>Файл <a href="./LICENSE">LICENSE</a> присутствует в репозитории, но пока пуст. Лицензия будет добавлена позже.</p>

<hr>

<h2>👤 Автор</h2>

<div align="center">

<p><b>DarkSwordman999</b></p>

<a href="https://github.com/DarkSwordman999">
  <img src="https://img.shields.io/badge/GitHub-DarkSwordman999-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
</a>

</div>

<hr>

<div align="center">

<h3>🎓 Проект создан в рамках курса «Python-разработчик» от <a href="https://practicum.yandex.ru/">Яндекс Практикума</a></h3>

<p><i>Учебный проект. Создан в образовательных целях.</i></p>

</div>
