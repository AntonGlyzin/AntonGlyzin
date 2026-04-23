# 👋 Привет, я Антон Глызин

**Software Architect | Staff Python Engineer | Инфраструктурный разработчик**

Я проектирую и создаю сложные, отказоустойчивые системы: от низкоуровневых сетевых протоколов до объектных построителей SQL-запросов и runtime-фреймворков. Моя экспертиза лежит на стыке **архитектуры**, **инфраструктуры** и **производительности**.

Умею превращать сложные технические концепции в элегантный, переиспользуемый и хорошо документированный код.

---

### 🛠️ Технологический стек

**Языки и ядро**
![Python](https://img.shields.io/badge/Python-Expert-3776AB?style=flat&logo=python&logoColor=white)
![Asyncio](https://img.shields.io/badge/Asyncio-Expert-4B8BBE?style=flat&logo=python&logoColor=white)
![Multiprocessing](https://img.shields.io/badge/Multiprocessing-Expert-306998?style=flat&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-Advanced-F7DF1E?style=flat&logo=javascript&logoColor=black)

**Бэкенд-фреймворки**
![Django](https://img.shields.io/badge/Django-Expert-092E20?style=flat&logo=django&logoColor=white)
![DRF](https://img.shields.io/badge/DRF-Expert-A30000?style=flat&logo=django&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-Advanced-009688?style=flat&logo=fastapi&logoColor=white)
![Wagtail](https://img.shields.io/badge/Wagtail_CMS-Advanced-43B1B0?style=flat&logo=wagtail&logoColor=white)
![Django Channels](https://img.shields.io/badge/Django_Channels-Advanced-1B1B1B?style=flat&logo=django&logoColor=white)

**Фронтенд**
![Vue 3](https://img.shields.io/badge/Vue_3-Advanced-4FC08D?style=flat&logo=vuedotjs&logoColor=white)
![Vuex](https://img.shields.io/badge/Vuex-Advanced-4FC08D?style=flat&logo=vuedotjs&logoColor=white)
![PrimeVue](https://img.shields.io/badge/PrimeVue-Advanced-06C?style=flat&logo=primevue&logoColor=white)
![Dojo Toolkit](https://img.shields.io/badge/Dojo_Toolkit-Intermediate-E0672F?style=flat&logo=dojo&logoColor=white)
![jQuery](https://img.shields.io/badge/jQuery-Advanced-0769AD?style=flat&logo=jquery&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-Advanced-7952B3?style=flat&logo=bootstrap&logoColor=white)

**Базы данных и ORM**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Expert-4169E1?style=flat&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-Expert-003B57?style=flat&logo=sqlite&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-Expert-D71F00?style=flat&logo=sqlalchemy&logoColor=white)
![Alembic](https://img.shields.io/badge/Alembic-Advanced-6E4C1E?style=flat&logo=alembic&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-Advanced-DC382D?style=flat&logo=redis&logoColor=white)

**Сети, очереди и инфраструктура**
![ZeroMQ](https://img.shields.io/badge/ZeroMQ-Expert-E01825?style=flat&logo=zeromq&logoColor=white)
![WebSockets](https://img.shields.io/badge/WebSockets-Expert-010101?style=flat&logo=socketdotio&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-Advanced-2496ED?style=flat&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-Intermediate-009639?style=flat&logo=nginx&logoColor=white)
![Apache](https://img.shields.io/badge/Apache-Intermediate-D22128?style=flat&logo=apache&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-CI/CD-2088FF?style=flat&logo=githubactions&logoColor=white)

**AI/ML и научные вычисления**
![PyTorch](https://img.shields.io/badge/PyTorch-Intermediate-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![Gymnasium](https://img.shields.io/badge/Gymnasium-Advanced-0081A5?style=flat&logo=openai&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-Advanced-013243?style=flat&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Intermediate-11557C?style=flat&logo=python&logoColor=white)
![DEAP](https://img.shields.io/badge/DEAP-Intermediate-000000?style=flat&logo=python&logoColor=white)

**Telegram Bot API**
![Telegram Bot API](https://img.shields.io/badge/Telegram_Bot_API-Expert-26A5E4?style=flat&logo=telegram&logoColor=white)
![Dialogflow](https://img.shields.io/badge/Dialogflow-Intermediate-FF9800?style=flat&logo=dialogflow&logoColor=white)

**Безопасность**
![JWT](https://img.shields.io/badge/JWT-Advanced-000000?style=flat&logo=jsonwebtokens&logoColor=white)
![OAuth2](https://img.shields.io/badge/OAuth2-Advanced-3C3C3D?style=flat&logo=auth0&logoColor=white)
![Cryptography](https://img.shields.io/badge/Cryptography-Advanced-5522FA?style=flat&logo=letsencrypt&logoColor=white)

---

### 🚀 Ключевые проекты

Ниже — мои собственные open-source библиотеки и фреймворки.

<details open>
  <summary><b>📦 CORMless — Объектный построитель SQL-запросов без ORM</b></summary>
  <br>
  <blockquote>
    <p>Библиотека для безопасного построения сложных SQL-запросов в объектном стиле. 
    Главная особенность — <b>полное отсутствие моделей</b>. Создана для сценариев, 
    где классические ORM избыточны, но писать сырой SQL небезопасно.</p>
  </blockquote>

  **Архитектурные особенности:**
  *   🧩 **Собственный DSL:** Объектное представление `SELECT`, `JOIN`, `WHERE`, `GROUP BY`, `HAVING`, функций SQL.
  *   ⚡ **Синхронность и асинхронность:** Единый API для `sync` и `async` с поддержкой `PostgreSQL` и `SQLite`.
  *   💾 **Многоуровневое кеширование:** Встроенный in-memory кеш и распределенный кеш на **Redis** с логикой инвалидации по тегам таблиц.
  *   🔒 **Безопасность:** Ручная реализация параметризованных запросов для защиты от SQL-инъекций.

  **Стек:** `Python 3.9+`, `asyncio`, `asyncpg`, `psycopg2`, `aiosqlite`, `redis`, `aiocache`.

  [![Read the Docs](https://img.shields.io/badge/Read_the_Docs-8CA1AF?style=for-the-badge&logo=readthedocs&logoColor=white)](https://query-tables.readthedocs.io/ru/latest)
  [![GitHub Repo](https://img.shields.io/badge/GitHub-Repo-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AntonGlyzin/query_tables)
  [![PyPI](https://img.shields.io/badge/PyPI-package-3775A9?style=for-the-badge&logo=pypi&logoColor=white)](https://pypi.org/project/query-tables/)
</details>

<details>
  <summary><b>📨 Mail Pigeon — Отказоустойчивая шина данных на ZeroMQ</b></summary>
  <br>
  <blockquote>
    <p>Асинхронная клиент-серверная библиотека для надежного обмена сообщениями 
    между микросервисами. Реализует гарантированную доставку (At-Least-Once) 
    с персистентной файловой очередью при обрывах связи.</p>
  </blockquote>

  **Архитектурные особенности:**
  *   🏗️ **Брокер на ZeroMQ:** Реализация топологии `ROUTER`-`DEALER`.
  *   💪 **Гарантированная доставка:** Подтверждения получения и автоматический повтор отправки из очереди.
  *   🔄 **Автоматический Failover:** Клиенты могут автоматически запускать резервный сервер переадресации.
  *   🔐 **Продвинутая безопасность:** Поддержка `CurveZMQ` (аутентификация канала) и сквозное шифрование (`HMAC`).

  **Стек:** `Python 3.9+`, `PyZMQ`, `asyncio`, `cryptography`, `anyio`.

  [![Read the Docs](https://img.shields.io/badge/Read_the_Docs-8CA1AF?style=for-the-badge&logo=readthedocs&logoColor=white)](https://mail-pigeon.readthedocs.io/ru/stable)
  [![GitHub Repo](https://img.shields.io/badge/GitHub-Repo-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AntonGlyzin/mail_pigeon)
  [![PyPI](https://img.shields.io/badge/PyPI-package-3775A9?style=for-the-badge&logo=pypi&logoColor=white)](https://pypi.org/project/mail-pigeon/)
</details>

<details>
  <summary><b>🧠 Neuro Evolution — Микрофреймворк для параллельного обучения AI-агентов</b></summary>
  <br>
  <blockquote>
    <p>Расширяемый фреймворк для обучения агентов в средах Gymnasium с помощью 
    нейроэволюции (генетический алгоритм + нейронные сети). Проект демонстрирует 
    проектирование сложных многопроцессорных приложений с GUI.</p>
  </blockquote>

  **Архитектурные особенности:**
  *   ⚙️ **Собственная runtime-система:** Фреймворк для создания и управления подпроцессами-сервисами (`Frontend`, `Backend`, `CPU-bound Tasks`), реализующий асинхронную очередь задач и неблокирующий UI. Архитектура, характерная для распределённых систем, применена в рамках десктопного приложения.
  *   🧬 **Динамическая регистрация классов:** Плагинная система для добавления новых окружений `gymnasium`.
  *   🖥️ **Разделение UI и вычислений:** Вычислительная нагрузка вынесена в отдельные процессы, UI на `wxPython` не блокируется.
  *   📦 **Продакшен-сборка:** Автоматическая сборка `.exe` через `PyInstaller` и CI/CD (GitHub Actions).

  **Стек:** `Python 3.11`, `PyTorch`, `Gymnasium`, `DEAP`, `wxPython`, `Multiprocessing`.

  [![GitHub Repo](https://img.shields.io/badge/GitHub-Repo-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AntonGlyzin/neuro_evolution)
  [![Download EXE](https://img.shields.io/badge/Download-EXE-0078D6?style=for-the-badge&logo=windows&logoColor=white)](https://github.com/AntonGlyzin/neuro_evolution/releases/latest)
</details>

---

### 🧩 Прикладные проекты

Ниже представлены проекты в веб-разработке, построении real-time приложений и автоматизации бизнес-процессов.

<details>
  <summary><b>🧩 Puzzle — Социальная сеть для разработчиков (Full-Stack)</b></summary>
  <br>
  <blockquote>
    <p>Полноценная социальная платформа для создания портфолио, ведения блога и нетворкинга.</p>
  </blockquote>

  **Ключевые особенности:**
  *   **Бэкенд:** **Django REST Framework** + **Django Channels** для WebSockets (чат, real-time нотификации).
  *   **Фронтенд:** **Vue 3** (Composition API) + **Vuex** + **PrimeVue**. Кастомные директивы для ленивой загрузки.
  *   **Архитектура:** Generic Relations для лайков/просмотров, интеграция с Telegram-ботом для активации пользователей.

  **Стек:** `Python`, `Django`, `DRF`, `Django Channels`, `PostgreSQL`, `Vue 3`, `WebSockets`.

  [![Backend Repo](https://img.shields.io/badge/Backend-Repo-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/AntonGlyzin/puzzle-chats)
  [![Frontend Repo](https://img.shields.io/badge/Frontend-Repo-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/AntonGlyzin/portfolio-puzzle)
</details>

<details>
  <summary><b>🛒 FastShop — Гибридный интернет-магазин</b></summary>
  <br>
  <blockquote>
    <p>Экспериментальный проект, объединяющий <b>FastAPI</b> (API для покупателей) и <b>Django Admin</b> 
    (панель управления) в рамках одного приложения.</p>
  </blockquote>

  **Ключевые особенности:**
  *   **Гибридная архитектура:** Связка ASGI (FastAPI) и WSGI (Django Admin) в одном проекте.
  *   **Глубокая кастомизация:** Расширение Django Admin (вычисляемые поля, кастомные шаблоны `change_list.html`).
  *   **Бизнес-логика:** Управление корзиной, заказами, JWT-авторизация, email-уведомления.

  **Стек:** `FastAPI`, `Django`, `PostgreSQL`, `SQLAlchemy`, `Pydantic`, `JWT`, `Docker`.

  [![GitHub Repo](https://img.shields.io/badge/GitHub-Repo-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/AntonGlyzin/back_fastshop)
</details>

<details>
  <summary><b>🏀 Sportsite — Платформа на Wagtail CMS</b></summary>
  <br>
  <blockquote>
    <p>Продающий лендинг с блогом, построенный на фреймворке <b>Wagtail</b> (Django CMS). Проект следует лучшим практикам сообщества Wagtail.</p>
  </blockquote>

  **Ключевые особенности:**
  *   **Wagtail Best Practices:** Использование `StreamField`, `Snippets`, `RoutablePageMixin`, `SeoMixin`.
  *   **Полный функционал:** Комментарии (`django-comments-xtd`), мультиязычность (`modeltranslation`), контактная форма с ReCaptcha.
  *   **Интеграции:** Кастомное хранилище для Google Firebase Storage.

  **Стек:** `Django`, `Wagtail CMS`, `PostgreSQL`, `Docker`.

  [![GitHub Repo](https://img.shields.io/badge/GitHub-Repo-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/AntonGlyzin/wagtail-sportsite)
</details>

<details>
  <summary><b>🤖 MyShopBot — E-commerce платформа в Telegram</b></summary>
  <br>
  <blockquote>
    <p>Полноценный магазин внутри Telegram-бота. Реализована сложная логика состояний для навигации по каталогу, 
    управления корзиной и оформления заказов.</p>
  </blockquote>

  **Ключевые особенности:**
  *   **Finite State Machine:** Управление диалогами через `register_next_step_handler`.
  *   **Архитектура:** Четкое разделение на `handlers`, `models`, `filters`, `buttons`.
  *   **ORM и миграции:** Использование `SQLAlchemy` и `Alembic`.

  **Стек:** `Python`, `PyTelegramBotAPI`, `SQLAlchemy`, `Alembic`, `SQLite`.

  [![GitHub Repo](https://img.shields.io/badge/GitHub-Repo-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/AntonGlyzin/myshopbot)
</details>

---

### 📊 GitHub статистика

<div align="center">

[![GitHub Streak](https://streak-stats.demolab.com?user=AntonGlyzin&theme=radical&hide_border=true&border_radius=8&date_format=j%20M%5B%20Y%5D&mode=weekly&background=0D1117&stroke=00D1B2&ring=00D1B2&fire=FF4500&currStreakNum=FFFFFF&sideNums=FFFFFF&currStreakLabel=00D1B2&sideLabels=FFFFFF&dates=8B949E)](https://git.io/streak-stats)

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=AntonGlyzin&layout=compact&theme=radical&hide_border=true&bg_color=0D1117&title_color=00D1B2&text_color=FFFFFF&langs_count=6)](https://github.com/AntonGlyzin)

</div>

---

### 💬 Обо мне как о разработчике

> "Я не просто пользуюсь фреймворками, я создаю их. Моя страсть — решать сложные архитектурные и инфраструктурные задачи, превращая их в элегантные и переиспользуемые библиотеки. Могу быстро разобраться в чужом коде и найти нестандартное решения для выявленной проблемы."

---

### 📫 Контакты

*   **Email:** [tosha.glyzin@mail.ru](mailto:tosha.glyzin@mail.ru)
*   **Telegram:** [@tosha_glyzin](https://t.me/tosha_glyzin)
*   **VK:** [Вконтакте](https://vk.com/tosha.glyzin)
