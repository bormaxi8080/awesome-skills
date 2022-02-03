# oh-my-skills

### Что это?

Этот репозиторий содержит систематизированную коллекцию материалов о составляющих различных экосистем (основные концепции, ОС, языки и среды разработки, фреймворки, API, различные утилиты, базы данных, безопасность, тестирование и пентест и др.), с которыми сталкиваются современные квалифицированные разработчики.

> Репозиторий изначально создавался для личных нужд как справочник, но, возможно, будет полезен широкому кругу специалистов.
> Большая часть материалов касается работы на ОС стека MacOS и Linux, поскольку автору они ближе, чем остальные.
> Репозиторий не является полным справочником по всему и вся и пополняется автором по мере личной необходимости.

В репозитории я постарался собрать максимальное количество ссылок на полезные ресурсы по интересующим меня темам, не вдаваясь в длинные описания технологий и холивары по поводу их использования.

Некоторые книги и мануалы в формате PDF для удобства выложены в отдельный репозиторий:

> https://github.com/bormaxi8080/programming-books

## Содержание:

- [Основные понятия и концепции](#основные-понятия-и-концепции)
- [Операционные системы](#операционные-системы)
- [Виртуальные машины](#виртуальные-машины)
- [Протоколы и стандарты передачи данных](#протоколы-и-стандарты)
- [Базы данных](#базы-данных)
- [Языки программирования](#языки-программирования)
- [Сервера приложений](#сервера-приложений)
- [Библиотеки и фреймворки](#бибилиотеки-и-фреймворки)
- [Frontend](#frontend)
- [Backend](#backend)
- [Мобильная разработка](#мобильная-разработка)
- [Популярные IDE](#популярные-IDE)
- [Пентестинг, безопасность и защита](#пентестинг-безопасность-и-защита)
- [Полезные утилиты](#полезные-утилиты)
- [Интересные репозитарии в Git](#интересные-репозитарии-в-git)
- [Разное](#разное)

# Основные понятия и концепции

### Основы работы в ОС семейства Linux. Shell и командная строка
- [Advanced Bash Scripting Guide](https://www.opennet.ru/docs/RUS/bash_scripting_guide/)
- [Вводная статья по Kali Linux](https://hackware.ru/?p=2767)
- [Oh My Zsh](https://ohmyz.sh/)- платформа с открытым исходным кодом для управления вашей конфигурацией Zsh. Поставляется в комплекте с тысячами полезных функций, помощников, плагинов, тем.
- [Explain Shell](https://explainshell.com/), объясняет команды терминала и ключи к ним.
- Уведомления через Shell:
> - [Linux notify-send](https://ss64.com/bash/notify-send.html) 
>
> - [Собственные уведомления в Gnome](https://habr.com/ru/post/47892/)
>
> - [MacOS terminal-notifier](https://github.com/julienXX/terminal-notifier)

### Git
- [Официальный сайт и документация](https://git-scm.com/)
- [Блог GitHub](https://github.blog)
- [4 лучших Git-клиента для Mac OS](https://medium.com/os-x-tips-tricks/3-%D0%BB%D1%83%D1%87%D1%88%D0%B8%D1%85-git-%D0%BA%D0%BB%D0%B8%D0%B5%D0%BD%D1%82%D0%B0-%D0%B4%D0%BB%D1%8F-mac-os-x-9980eaf356b6)
- [Git за полчаса - руководство для начинающих](https://proglib.io/p/git-for-half-an-hour)
- [Интерактивный курс по Git](https://githowto.com/)
- [Oh shit! Git](https://ohshitgit.com/), подскажет, что делать, если вы допустили ошибку в гите
- [Git Explorer](https://gitexplorer.com/), справочник по командам и возможностям гита
- [О файле .gitignore](https://tyapk.ru/blog/post/gitignore)
- [Token authentication requirements for Git operations](https://github.blog/2020-12-15-token-authentication-requirements-for-git-operations/)

### Markdown, редактура
- [Краткое руководство по MD](https://paulradzkov.com/2014/markdown_cheatsheet/)
- Obsidian - мощный редактор для работы с Markdown:
> - [Официальный сайт и документация](https://obsidian.md/)
>
> - [Небольшая вводная](https://habr.com/ru/company/macloud/blog/560776/)
- [Grip - утилита для автономного просмотра разметки MD](https://github.com/joeyespo/grip)
- [White Spaces](https://kirillbelyaev.com/s/), список всех существующих пробелов и рекомендации по использованию каждого;
- [Типограф](https://typograf.github.io/mobile.html), правит пунктуацию, ставит неразрывные пробелы и проч.;
- [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet), справочник по MD;
- [Markdown Editor](https://readme.so/), визуальный редактор MD;
- [Polacode](https://github.com/octref/polacode), скриншоттер для фрагментов кода;
- [Vale: a command-line tool that brings code-like linting to prose](https://github.com/errata-ai/vale)

### Regular Expressions
-   [Regex 101](https://regex101.com/), редактор и тестер регулярных выражений с объяснениями каждого символа и примерами.

# Операционные системы

### MacOS
- [Официальное руководство пользователя MacOS](https://support.apple.com/ru-ru/guide/mac-help/welcome/mac)
- [MacAppStore - Search and Install any app on MacOS](https://macappstore.org/)
- [Homebrew Formulae - online package browser for Homebrew](https://formulae.brew.sh/)
- [MacBug](http://macbug.ru/)- хороший сайт о программировании под MacOs, iOS
- [Яблык](https://yablyk.com/) - все про Apple

### Ubuntu
- [Официальный сайт и документация](https://ubuntu.com/)
- [Про Ubuntu на русском](https://ubuntu.ru/)

### Debian
- [Официальный сайт и документация](https://www.debian.org/)
- [В чём разница между Debian и Ubuntu? Что и когда лучше выбрать](https://habr.com/ru/company/ruvds/blog/576380/)

### Kali Linux
- [Официальный сайт и документация](https://kali.org)
- [Перевод официальной документации](https://hackware.ru/?p=2767)
- [Небольшая вводная статья](https://teletype.in/@hackerseverywhere/BympqZiD4)

# Виртуальные машины

### Oracle VM VirtualBox
- [Официальный сайт и документация](https://www.virtualbox.org/)
- [Образы Windows](https://g-ek.com/skachat-oficzialnyie-virtualnyie-mashinyi-windows-10)	
- [Образы Ubuntu](https://www.linuxvmimages.com/images/ubuntu-2004/)
- [Образы Kali Linux](https://www.kali.org/get-kali/)
- [Образ MacOS High Sierra](https://betacode.net/12025/install-mac-os-virtual-machine-in-virtualbox)

# Протоколы и стандарты передачи данных

### RFC и IETF:
- [Полный список стандартов RFC](https://www.rfc-editor.org/standards)
- [Наиболее популярные RFC](https://ru.wikipedia.org/wiki/%D0%A1%D0%BF%D0%B8%D1%81%D0%BE%D0%BA_RFC)
- [IETF Data Tracker](https://datatracker.ietf.org/), поиск полного описания RFC по номеру

### DNS:
- [Простое описание протокола DNS](https://ru.wikipedia.org/wiki/DNS)
- [Записи DNS](https://ru.wikipedia.org/wiki/DNS#%D0%97%D0%B0%D0%BF%D0%B8%D1%81%D0%B8_DNS)
- [Типы ресурсных записей DNS](https://ru.wikipedia.org/wiki/%D0%A2%D0%B8%D0%BF%D1%8B_%D1%80%D0%B5%D1%81%D1%83%D1%80%D1%81%D0%BD%D1%8B%D1%85_%D0%B7%D0%B0%D0%BF%D0%B8%D1%81%D0%B5%D0%B9_DNS#A)
- [MX](https://ru.wikipedia.org/wiki/%D0%97%D0%B0%D0%BF%D0%B8%D1%81%D1%8C_MX)
- [Как проверить MX-запись домена](https://timeweb.com/ru/community/articles/kak-proverit-mx-zapis-domena)
- [Команда dig (domain information groper)](https://andreyex.ru/linux/komandy-linux-i-komandy-shell/kak-ispolzovat-komandu-dig-dlya-zaprosa-dns-v-linux/), многофункциональный инструмент для опроса DNS-серверов

### HTTP/HTTPS:
-   [HTTP Statuses](https://httpstatuses.com/), список HTTP статусов ответа с их значениями;

### SMTP:
- [Простое описание протокола SMTP](https://ru.wikipedia.org/wiki/SMTP)
- (Описание протокола от ICANN](http://www2.icmm.ru/~masich/win/lexion/mail/smtp.html#relay)
- Catch-all:
> https://ru.wikipedia.org/wiki/Catch-all
> 
> https://golb.hplar.ch/2019/08/catch-all-smtp.html
> 
> [How to detect if domain has catch all policy to accept email](https://stackoverflow.com/questions/17947198/how-to-detect-if-domain-has-catch-all-policy-to-accept-email)
- [Reacher](https://reacher.email/), Open-Source Email Verification API:
> - https://github.com/orgs/reacherhq/repositories
>
> - https://github.com/reacherhq/check-if-email-exists

### MTA (Message Transfer Agent):
- [Основные принципы MTA](https://ru.bmstu.wiki/MTA_(Message_Transfer_Agent))
- [More about MTA](https://mailtrap.io/blog/mail-transfer-agent/)

# Базы данных

### Теория и основные концепции работы с БД
- [List of tz database time zones](https://en.wikipedia.org/wiki/List_of_tz_database_time_zones)
- [Checklist for Changing Data Model](https://rtpg.co/2021/06/07/changes-checklist.html), чеклист для миграции данных и схем данных.

### MySQL
- [Официальный сайт и документация](https://www.mysql.com/)
- [Документация на русском](http://www.mysql.ru/docs/)
- [Руководство по MySql на Metanit](https://metanit.com/sql/mysql/)
- [Оригинальный API для MySQL- PHP](https://www.php.net/manual/ru/book.mysql.php)

### MariaDB
- [Официальный сайт и документация](https://mariadb.com/)
- [MariaDB foundation](https://mariadb.org/)
- [История проекта](https://ru.wikipedia.org/wiki/MariaDB)
- [Установка на MacOS](https://mariadb.com/kb/en/installing-mariadb-on-macos-using-homebrew/)

### PostrgeSQL
- [Официальный сайт и документация](https://www.postgresql.org/)
- [Установка и настройка PostgreSQL](https://wiki.calculate-linux.org/ru/postgresql)
- [Руководство на Metanit](https://metanit.com/sql/postgresql/)
- [Хорошие туториалы на английском](https://www.postgresqltutorial.com/)
- [Psycopg](https://www.psycopg.org/), PostgreSQL adapter for Python

### SQLite
- [Официальный сайт и документация](https://www.sqlite.org)

### MongoDB
- [Официальный сайт и документация](https://www.mongodb.com/)
- [MongoDB Twitter account](https://twitter.com/MongoDB)
- [Руководство на Metanit](https://metanit.com/nosql/mongodb/)
- [Руководство на CoderLessons](https://coderlessons.com/tutorials/bazy-dannykh/uchitsia-mongodb/mongodb-kratkoe-rukovodstvo)
- [Примеры работы на Node.js](https://nodejsdev.ru/doc/mongodb/)

# Языки программирования

### JavaScript и SPA
- [JavaScript RU](https://javascript.ru/), исчерпывающая информация по JavaScript на русском
- [Learn JavaScript](https://learn.javascript.ru/), современный учебник по JavaScript
- Вот этот парень у себя в LinkedIn делает классные мануалы/примеры кода по JS: https://www.linkedin.com/in/sam-shpakov/

### TypeScript
- [Running and debugging TypeScript in JetBrains WebStorm](https://www.jetbrains.com/help/webstorm/running-and-debugging-typescript.html)

### C++
- [Официальный сайт стандарта C++](https://isocpp.org/)
- [Большой сайт по C++, документация](https://www.cplusplus.com/)
- [Туториалы](https://www.w3schools.com/cpp/cpp_intro.asp)

### Rust
- [Официальный сайт и документация](https://www.rust-lang.org/)
- [Rust в примерах](https://doc.rust-lang.ru/stable/rust-by-example/)
- [Русскоговорящее сообщество Rust](https://rust-lang.ru/)
- [Разбор особенностей Rust и некоторые ссылки](https://habr.com/ru/post/433302/)

### Java
- [Официальный сайт Java](https://www.java.com/)
- [Официальная документация по Java](https://dev.java/)
- [Java на русском](https://www.java.com/ru/)
- [Хаб на Habr](https://habr.com/ru/hub/java/)
- [Раздел на Metanit](https://metanit.com/java/)

### Scala
- [Официальный сайт и документация](https://www.scala-lang.org/)
- [Хаб на Habr](https://habr.com/ru/hub/scala/)

### Python
- [Официальный сайт и документация](https://www.python.org/)
- [Материалы по Python на TProger](https://tproger.ru/tag/python/)
- [Хаб на Хабре](https://habr.com/ru/hub/python/)
- [Find, install and publish Python packages with the Python Package Index](https://pypi.org), поисковик по библиотекам
- [Awesome Python](https://chel-center.ru/python-yfc/awesome-python/), курс молодого бойца
- [Абстрактные классы и интерфейсы в Python](https://habr.com/ru/post/72757/)
- [Работа с конфигурационными файлами](https://habr.com/ru/post/485236/)
- [Антипаттерн settings.py](https://habr.com/ru/post/115893/)
- [Logging facility for Python](https://docs.python.org/3/library/logging.html)
- [Логгирование в Python](https://python-scripts.com/logging-python)
- [Настройка логирования в Python](https://habr.com/ru/sandbox/150814/), повышаем информативность лога
- [Модуль Queue](https://docs.python.org/3/library/queue.html)
- [Библиотеки для работы с SQLite](https://pyneng.readthedocs.io/ru/latest/book/25_db/sqlite3.html)
- [Работа с JSON в Python](https://python-scripts.com/json)
- Celery: см. отдельный раздел ниже

### GoLang
- [Официальный сайт и документация](https://go.dev/)
- [Материалы по Go](https://gist.github.com/egorsmkv/9df2aef2eddf51986b6d2b5833a4423e), egorsmkv
- [GoLang Training](https://github.com/GoesToEleven/GolangTraining), GoesToEleven
- [Эффективный Go](https://github.com/Konstantin8105/Effective_Go_RU), Konstantin8105
- [Bulid applications with GoLang](https://github.com/astaxie/build-web-application-with-golang/blob/master/ru/preface.md)

Книги:
- [Введение в программирование на Go](http://golang-book.ru/), GitHub: https://github.com/maxpoletaev/golang-book
- [Cloud Native Go examples](https://github.com/cloud-native-go/examples)
- [Маленькая книга о Go](https://sefus.ru/little-go-book/)

Разное:
- [Шпаргалка по структурам данных в Go](https://habr.com/ru/post/456194/)
- [Парсинг файлов CSV в Go](https://golangify.com/parsing-csv)
- [Vegeta](https://github.com/tsenart/vegeta), GoLang HTTP Load Testing Tool and Library

### PHP
- [Официальный сайт и документация](https://www.php.net/)

### Ruby, RubyOnRails
- [Официальный сайт и документция](https://www.ruby-lang.org/ru/), Ruby
- [RubyOnRails](https://rubyonrails.org/)
- [Чем хорош RubyOnRails и как он ускоряет разработку](https://habr.com/ru/company/skillbox/blog/428487/)
- [Хороший сайт на русском](http://www.rubyonrails.ru/)

### Perl
- [Официальный сайт и документация](https://www.perl.org/)
- [Хаб на Хабре](https://habr.com/ru/hub/perl/)
- [Краткий экскурс в Perl-программирование](https://www.opennet.ru/docs/RUS/perl_help/)

### Lua
- [Официальный сайт и документация](https://www.lua.org/)
- [Lua за 15 минут](https://habr.com/ru/post/184538/)
- [Learn Lua](http://tylerneylon.com/a/learn-lua/)
- [Хороший мануал по Lua на русском](https://docs.geoscan.aero/ru/master/programming/lua/lua_main.html)
- [Хаб на Хабре](https://habr.com/ru/hub/lua/)

### Erlang
- [Официальный сайт и документация](https://www.erlang.org/)
- [Краткое руководство на CoderLessons](https://coderlessons.com/tutorials/kompiuternoe-programmirovanie/vyuchit-erlang/erlang-kratkoe-rukovodstvo)
- [Руководство по программированию на языке Erlang](https://pessim50.ucoz.ru/Erlang.pdf)
- [Специфика Erlang](https://eax.me/erlang-is-specific/)

# Сервера приложений
### NATS
- [Официальный сайт и документация](https://nats.io/)

### Redis
- [Официальный сайт и документация](https://redis.io/), Redis is an open source in-memory data structure store, used as a database, cache, and message broker
- [Маленькая книга о Redis](https://3s.group/upload/iblock/890/890258c1a79e7154773b210ea701b184.pdf)
- [Redis для начинающих](https://webdevblog.ru/redis-dlya-nachinajushhij/)
- [Вводная по Redis на AWS](https://aws.amazon.com/ru/redis/)
- [Шпаргалка по Redis на Хабре](https://habr.com/ru/post/204354/)
- [Redis в Python](https://python-scripts.com/redis), полная документация на примерах
- [Redis Queue в Python](https://khashtamov.com/ru/python-rq-howto/)

### Memcached
- [Официальный сайт и документация](https://memcached.org/), Memcached is a distributed memory object caching system
- [Маленькая вводная по Memcached](https://habr.com/ru/post/42607/)
- [Описание от AWS](https://aws.amazon.com/ru/memcached/), сравнение с Redis

### RabbitMQ
- [Официальный сайт и документация](https://www.rabbitmq.com/), RabbitMQ message broker
- [Введение в RabbitMQ](https://habr.com/ru/post/488654/)
- [Установка и настройка RabbitMQ в MacOS](https://russianblogs.com/article/91201405100/)
- [Коротко о работе с RabbitMQ из Python](https://habr.com/ru/post/434510/)
- [Pika](https://pika.readthedocs.io/en/stable/index.html), pure Python implementation of the AMQP 0-9-1 protocol

### Celery
- [Официальный сайт и документация](http://celeryproject.org/), Celery async message queue
- [GitHub](https://github.com/celery/celery)
- [Введение в Celery](https://docs.celeryproject.org/en/stable/getting-started/introduction.html)
- [Celery - лучшие практики](https://habr.com/ru/post/269347/)
- [Celery - начинаем правильно](https://khashtamov.com/ru/celery-best-practices/)
- [50 оттенков Celery](https://habr.com/ru/company/oleg-bunin/blog/433476/)
- [Celery Python](https://dev-gang.ru/article/celery-python-osnovy-i-primery-ba4pn1pyb9/), основы и примеры
- [3 кейса для использования Celery в Django-приложении](https://habr.com/ru/post/461775/)
- [Django и Celery](https://django.fun/tutorials/django-i-celery-1-ustanovka/), в связке
- [Пакет django-celery](https://github.com/adilkhash/django-celery)
- [Flask & Celery](https://chel-center.ru/python-yfc/2021/05/12/asinhronnye-zadachi-s-celery-v-python/), Асинхронные задачи с Celery в Python
- [Flower](https://github.com/mher/flower), web based tool for monitoring and administrating Celery clusters:

Автоматический веб-скрапинг с помощью Python и Celery:
- [Часть 1](https://www.internet-technologies.ru/articles/sozdanie-skrapera-rss-kanala-s-pomoschyu-python.html)
- [Часть 2](https://www.internet-technologies.ru/articles/avtom-veb-skraping-s-pom-python-i-celery.html#header-55486-5)
- [Часть 3](https://www.internet-technologies.ru/articles/sozd-priloz-parsinga-veb-stranic-python.html)

### Tarantool
- [Официальный сайт и документация](https://www.tarantool.io/), Tarantool, платформа in-memory вычислений

# Библиотеки и фреймворки
### Telegram

Управление ботами в Telegram:
- [Telegram на русском](https://tlgrm.ru/blog), очень много всякой информации
- [Telegram-боты](https://tlgrm.ru/docs/bots#botfather), информация для разработчиков
- [Модуль Telegram](https://vc.ru/services/278869-modul-telegram-sozdanie-chat-bota-i-kanala-minimalnye-nastroyki-komponentov), создание чат-бота и канала, минимальные настройки компонентов
- [Всё, о чём должен знать разработчик Телеграм-ботов](https://habr.com/ru/post/543676/)
- [Пишем ботов для Telegram на языке Python](https://mastergroosha.github.io/telegram-tutorial/)
- [Неплохой разбор полетов с ботами для Telegram](https://habr.com/ru/company/ods/blog/462141/)
- [Python telegram.ext package](https://python-telegram-bot.readthedocs.io/en/stable/telegram.ext.html_
- [Лимиты, существующие в Telegram](https://www.vamtlgrm.com/limity-sushhestvuyushhie-v-telegram/)

AIOgram async framework:
- [AIOgram GitHub](https://github.com/aiogram/aiogram)
- [Официальная документация по AIOgram](https://docs.aiogram.dev/en/latest/)
- [Быстрый старт]https://surik00.gitbooks.io/aiogram-lessons/content/chapter1.html)
- [Telegram-бот на Python за полчаса с aiogram](https://tproger.ru/articles/telegram-bot-create-and-deploy/)
- [Знакомство с AIOgram](https://mastergroosha.github.io/telegram-tutorial-2/quickstart/)

Платежи в Telegram:
- [Подключение оплат](https://vc.ru/dev/240195-kak-nastroit-priem-platezhey-2-0-v-telegram-za-5-chasov)
- [Как настроить прием платежей 2.0 в Telegram за 5 часов](https://vc.ru/dev/240195-kak-nastroit-priem-platezhey-2-0-v-telegram-za-5-chasov)

### Django
- [Официальный сайт и документация](https://www.djangoproject.com/)
- [Документация от Mozilla](https://developer.mozilla.org/ru/docs/Learn/Server-side/Django)
- [Исчерпывающая книга про Django](https://djbook.ru/rel3.0/), неплохая документация на русском
- [DJBook](https://djbook.ru/), и тут всего остального про Django навалом
- [Хаб по Django на Хабре](https://habr.com/ru/hub/django/)
- [Django fun](https://django.fun/)
- [Статьи про Django](https://django.fun/tutorials/)

### Flask
- [Официальный сайт и документация](https://flask.palletsprojects.com/en/2.0.x/)
- [Русский перевод документации Flask](https://flask-russian-docs.readthedocs.io/ru/latest/)
- [Учебник по Flask на Habr](https://habr.com/ru/post/193242/)

### Pyramid
- [Официальный сайт и документация](https://trypyramid.com/)
- [Руководство на Habr](https://habr.com/ru/post/135916/)
- [Еще доки](https://docs.pylonsproject.org/projects/pyramid/en/latest/index.html)

### Tornado
- [Официальный сайт и документация](https://www.tornadoweb.org/en/stable/)
- [Небольшая вводная](https://habr.com/ru/sandbox/27705/)

### Docker
- [Официальная документация](https://docs.docker.com/)
- [Быстрый старт](https://tproger.ru/translations/how-to-start-using-docker/)
- [Полное практическое руководство по Docker](https://habr.com/ru/post/310460/), на русском

# Frontend
### React.js
- [Learn React.js](https://learn-reactjs.ru/home), полное руководство по React.js

### Go Hugo:
- [Creating Hugo Themes](https://draft.dev/learn/creating-hugo-themes)
- [Create Your Own Hugo Theme](https://www.youtube.com/watch?v=wcMqrb3v2SM), большое полное видео
- [Легкое создание сайтов на Hugo](https://code.tutsplus.com/ru/tutorials/make-creating-websites-fun-again-with-hugo-the-static-website-generator-written-in-go--cms-27319)

### Подготовка графики
-   [Squoosh](https://squoosh.app/), приложение, CLI и API для оптимизации графики;
-   [SVG URL Encoder](https://yoksel.github.io/url-encoder/ru/), кодирует SVG в URL-строку, чтобы использовать его в `background` без base64
-   [SVG OMG](https://jakearchibald.github.io/svgomg/), оптимизатор SVG;
-   [Social Image Preview](https://socialsharepreview.com/), предпросмотрщик изображений для соцсетей
-   [Facebook Debug](https://developers.facebook.com/tools/debug/), дебагер соц-изображений для Facebook
- [Figmachine](https://www.figmachine.com/), Convert Figma to React Code

### HTML и доступность
- [HTML Tutorials](https://www.w3schools.com/html/)
- [Документация от Mozilla](https://developer.mozilla.org/ru/docs/Web/HTML)
- [Справочник по HTML](http://htmlbook.ru/html)
- [Emmet](https://www.emmet.io/), генератор HTML-кода из «CSS-селекторов»
- [Can I Include](https://caninclude.glitch.me/), ответит на вопрос «Можно ли класть один тег в другой?»
- [HTML head](https://html-head.ru/), поможет найти нужный элемент для `<head>` страницы
- [Logical Content Flow](https://defaced.dev/tools/logical-content-flow/), найдёт проблемы с заголовками, их порядком и отображением
- [Better Mobile Inputs](https://better-mobile-inputs.netlify.app/), поможет подобрать `<input>` и атрибуты для него так, чтобы им было удобно пользоваться на мобильных
- [Weblind](https://weblind.ru/), рекомендации по разработке сайтов для людей с нарушениями зрения
- [Inclusive Components](https://inclusive-components.design/), примеры реализации слайдеров, аккордеонов и других компонентов с упором на доступность
- [Axe](https://www.deque.com/axe/), браузерный плагин для комплексной проверки доступности страниц
- [Good Email Code](https://www.goodemailcode.com/), справочник и набор рекомендаций для пуленепробиваемой вёрстки писем
- [How to Favicon in 2021](https://evilmartians.com/chronicles/how-to-favicon-in-2021-six-files-that-fit-most-needs), статья-чеклист о том, как добавлять фавиконку на сайт без лишнего кода
- [W3C Validator](https://validator.w3.org/nu/#textarea), валидатор HTML-кода

### HTML5
- [Справочник по HTML5](https://html5book.ru/html-html5/)
- [Погружение в HTML5](http://htmlbook.ru/html5)
- [Различия меду HTML(4) и HTML5](https://www.hostinger.ru/rukovodstva/chto-takoe-html-i-ih-razlichiya)

### Стилизация и CSS
- [CSS Tutorials](https://www.w3schools.com/css/default.asp)
- [Документация от Mozilla](https://developer.mozilla.org/ru/docs/Learn/Getting_started_with_the_web/CSS_basics)
- [CSS для начинающих](https://ru.code-basics.com/languages/css)
- [Самоучитель CSS](http://htmlbook.ru/samcss)
- [Can I Use](https://caniuse.com/), поможет проверить браузерную поддержку свойства
- [Can I Use CMD](https://github.com/sgentle/caniuse-cmd), CLI для Can I Use;
- [Nth Tester](https://css-tricks.com/examples/nth-child-tester/), поможет проверить, так ли работает ваш `nth-child` селектор
- [Flexbox Playground](https://codepen.io/enxaneta/full/adLPwv/), визуализирует работу флекс-свойств
- [Grid by Example](https://gridbyexample.com/examples/), шпаргалка по CSS grid;
- [Grid Lover](https://www.gridlover.net/try), конструктор вертикального ритма и отступов для заголовков и параграфов
- [Specificity Calc](https://specificity.keegan.st/), калькулятор специфичности селекторов
- [Colord](https://colord.omgovich.ru/), конвертер цветов между разными цветовыми схемами
- [CSS Gradient](https://cssgradient.io/), конструктор CSS градиентов
- [Easings](https://easings.net/), справочник по easing-функциям с примерами
- [Cubic Bezier](https://cubic-bezier.com/#.87,0,.13,1), конструктор и редактор кривых Безье
- [CSS Paterns](https://projects.verou.me/css3patterns/), коллекция фоновых узоров на чистом CSS
- [CSS Shapes](https://css-tricks.com/the-shapes-of-css/), набор часто используемых фигур на чистом CSS
- [CSS Triggers](https://csstriggers.com/), подскажет, какие свойства запускают layout, paint и composite

### Браузерные расширения Chrome и Firefox:
- [Как посмотреть исходный код любого расширения в браузере](https://mipped.com/polezno/9742-kak-posmotret-ishodnyy-kod-lyubogo-rasshireniya-v-brauzere.html)

### Bootstrap
- [Официальный сайт и документация](https://getbootstrap.com/)
- [Создание быстрых отзывчивых сайтов с Bootstrap](https://bootstrap-4.ru/), документация на русском

### Material UI
- [Официальный сайт и документация](https://mui.com/)
- [Reactjs, Material-UI with JSS])(https://habr.com/ru/post/492378/), крайткий гайд
- [MUI React templates & tools satore](https://material-ui.com/store/)
- [Material Design](https://material.io/)
- [Material Design Components](https://material.io/components)

### UX
- [UX Club](https://www.facebook.com/groups/136827946465842), самое большое российское коммьюнити по UX

# Backend
Подробный roadmap по backend технологиям есть в этом репозитарии: https://github.com/bzick/oh-my-backend

Часть материалов из данного репозитария скопировано сюда.

### Node.js
- [Официальный сайт и документация](https://nodejs.org/)
- [Официальные руководства](https://nodeguide.ru/doc/)
- [Руководство по Node.js на Habr](https://habr.com/ru/company/ruvds/blog/422893/)
- [Полная версия руководства на Habr](https://habr.com/ru/company/ruvds/blog/428576/) + PDF
- [Сайт для разработчиков Node.js](https://nodejsdev.ru/), на русском
- [Руководство на Metalint](https://metanit.com/web/nodejs/)
- [Управление версиями Node.js и NPM](https://habr.com/ru/company/timeweb/blog/541452/), с помощью NVM
- [Using Node in JetBrains WebStorm](https://www.jetbrains.com/help/webstorm/developing-node-js-applications.html#ws_node_version)

Книги:

> https://monster-book.com/node-js
>
> https://habr.com/ru/company/ruvds/blog/428576/

Express Framework:

- [Официальный сайт и документация](https://expressjs.com/ru/)
- [Руководство по Express от Mozilla](https://developer.mozilla.org/ru/docs/Learn/Server-side/Express_Nodejs)

- [Fastify](https://www.fastify.io/), краткий обзор: https://habr.com/ru/post/555668/

- [Async Framework](https://caolan.github.io/async/v3/docs.html) 
- [Руководство по Async](https://developer.mozilla.org/ru/docs/Learn/Server-side/Express_Nodejs/Displaying_data/flow_control_using_async), от Mozilla

- [Lodash](https://lodash.com/docs/), краткий обзор: https://habr.com/ru/post/217515/

- [Node-fetch](https://www.npmjs.com/package/node-fetch), XMLHttpRequest emplementation libraru
- [Chalk](https://github.com/chalk/chalk), раскраска терминала:
- [Debug](https://developer.ibm.com/articles/intro-to-the-nodejs-debug-module/)

- Puppeteer - скрапинг web-сайтов:
- https://github.com/puppeteer/puppeteer 
- https://habr.com/ru/company/oleg-bunin/blog/421137/
- https://habr.com/ru/company/ruvds/blog/341348/
- https://habr.com/ru/post/413547/

- [Lerna](https://github.com/lerna/lerna), A tool for managing JavaScript projects with multiple packages

- Модули node для работы с SQLite:

- https://github.com/grumdrig/node-sqlite
- https://github.com/mapbox/node-sqlite3
- https://github.com/grumdrig/node-sqlite
- https://www.npmjs.com/package/better-sqlite3
- [Что выбрать](https://coderoad.ru/14355004/%D0%A7%D1%82%D0%BE-SQLite-%D0%B8%D1%81%D0%BF%D0%BE%D0%BB%D1%8C%D0%B7%D0%BE%D0%B2%D0%B0%D1%82%D1%8C-%D1%81-nodejs)
- Визуализация SQLite в Node.js: https://habr.com/ru/company/vdsina/blog/527146/

- [Примеры работы Node.js с MongoDB](https://nodejsdev.ru/doc/mongodb/)

### Backend - разное
- [Серверное программирование web-сайтов](https://developer.mozilla.org/ru/docs/Learn/Server-side), официальные рекомендации от Mozilla

- [Google Translate API](https://cloud.google.com/translate)

- [Google Language API](https://cloud.google.com/natural-language):
> API является платным.
>
> Обсуждение автоматического определения языков: https://habr.com/ru/post/52239/
>
> На данный момент самый "крутой" способ определить язык и сделать относительно точный перевод - использовать translate.google.com через Puppeteer или другую библиотеку, подставляя нужные значения. Еще интересный вариант - переводить с помощью функции GOOGLETRANSLATE в таблице Google: https://shagabutdinov.ru/translate_sheets/

### Web Scraping
- [GetData.io Web Scraper](https://chrome.google.com/webstore/detail/web-scraper-getdataio/)
- [OSINTGram](https://telegra.ph/OSINTGRAM-Sobiraem-dannye-iz-Instagram-12-04), собираем данные из Instagram
- [Web Scrapping with Go](https://www.scrapingbee.com/blog/web-scraping-go/)

# Мобильная разработка
### iOS

Objective C:
- [Официальная документация от Apple](https://developer.apple.com/library/archive/documentation/Cocoa/Conceptual/ProgrammingWithObjectiveC/Introduction/Introduction.html)
- [Objective C с нуля: https://habr.com/ru/post/107126/]

Swift:
- [Официальный сайт и документация](https://www.swift.org/)
-[Официальная документация от Apple](https://developer.apple.com/documentation/swift)
- [Хаб на Habr](https://habr.com/ru/hub/swift/)

Cocoa:
- [Официальная документация от Apple](https://developer.apple.com/library/archive/documentation/Cocoa/Conceptual/CocoaFundamentals/WhatIsCocoa/WhatIsCocoa.html)
- [Учебник на русском](http://macbug.ru/cocoa.php)
- [Хаб на Habr](https://habr.com/ru/hub/cocoa/)

### Android

Android Core:
- [Android Official Documentation](https://developer.android.com/)
- [Android Developers Community](https://developer.android.com/)
- [Android Studio](https://developer.android.com/studio)
- [Android JetPack](https://developer.android.com/jetpack)
- [Про Android на русском](https://www.android.com/intl/ru_ru/), Android.com
- [Хаб на Habr](https://habr.com/ru/hub/android_dev/)

Kotlin:
- [Develop Android apps with Kotlin (official)](https://developer.android.com/kotlin)

# Популярные IDE

### Cемейство IDE от JetBrains
- [Официальный сайт и документация](https://www.jetbrains.com/)

### Eclipse IDE
- [Официальный сайт и документация](https://www.eclipse.org/ide/)

# Пентестинг, безопасность и защита
- [Application Security](https://application.security/free/owasp-top-10), интерактивный чеклист по уязвимостям веб-приложений с объяснениями и рекомендациями к защите
- [SecurityLab - Soft](https://www.securitylab.ru/software/), огромная подборка всякого разного софта

"Mac на службе у хакера" - хорошая серия статей для начинающих пентестеров:

- [Часть 1 - Шифрование диска](https://www.securitylab.ru/analytics/491107.php)
- [Часть 2 - Создание образа шифрованного диска](https://www.securitylab.ru/analytics/491268.php)
- [Часть 3 - Управление паролями](https://www.securitylab.ru/analytics/491893.php)
- [Часть 4 - Установка iTerm2](https://www.securitylab.ru/analytics/492394.php)
- [Часть 5 - Использование Git](https://www.securitylab.ru/analytics/492395.php)
- [Часть 6 - Настройка Homebrew](https://www.securitylab.ru/analytics/492845.php)
- [Часть 7 - Установка RVM для работы с Ruby](https://www.securitylab.ru/analytics/492846.php)
- [Часть 8 - Установка Kali Linux на виртуальной машине](https://www.securitylab.ru/analytics/492847.php)
- [Часть 9 - Установка Metaspoloit Framework](https://www.securitylab.ru/analytics/492848.php)
- [Часть 10 - Упорядочивание утилит](https://www.securitylab.ru/analytics/492935.php_

### Honeypots:
- [Хорошая вводная статья про инструментарий Honeypots](https://habr.com/ru/company/alexhost/blog/528796/)

### Утилиты
- [Ciphey](https://github.com/Ciphey/Ciphey), Input encrypted text, get the decrypted text back

- Wireshark:
> - [Официальный сайт и документация](https://www.wireshark.org/)
>
> - [Небольшое руководство и шпаргалка](https://habr.com/ru/post/436226/)
>
> - [Огромное количество инструкций и примеров](https://networkguru.ru/wireshark/)

- Telnet:
> - [Простые примеры работы с Telnet](https://losst.ru/kak-polzovatsya-telnet)
>
> - [Документация по Telnet от Microsoft](https://docs.microsoft.com/ru-ru/windows-server/administration/windows-commands/telnet)

- NMap:

> - [Руководство по NMap](https://nmap.org/npcap/guide/)
>
> - [Vulscan](https://github.com/scipag/vulscan) nmap -sV --script vulners domain.com
>
> - [nmap-vulners](https://github.com/vulnersCom/nmap-vulners) nmap -sV --script=vulscan.nse domain.com
>
> - [Автоматизированный shell для NMap](https://github.com/bormaxi8080/nmap-scanner)
>
> Несколько интересных статей:
>
>> https://habr.com/ru/post/88064/
>> 
>> https://losst.ru/kak-polzovatsya-nmap-dlya-skanirovaniya-seti
>>
>> https://antiddos.biz/kak-polzovatsya-nmap-dlya-poiska-uyazvimostej-servera/
>
> [Еще некоторые примеры](https://xakinfo.ru/os/nmap-anonymous/)

Metasploit Framework:

- [Официальный сайт проекта](https://www.metasploit.com/)
- [Официальная документация](https://docs.rapid7.com/metasploit/)
- [Установка](https://github.com/rapid7/metasploit-framework/wiki/Nightly-Installers)
- [Гид по Metasploit Framework от SecurityLab](https://www.securitylab.ru/blog/personal/Informacionnaya_bezopasnost_v_detalyah/323370.php_
- Обзоры:
> 
> https://habr.com/ru/company/varonis/blog/528578/
>
> https://vc.ru/life/136613-metasploit-framework-kratkoe-prakticheskoe-rukovodstvo

### Security Tools & Utilities
- [theHarvester](https://github.com/laramies/theHarvester, a very simple to use, yet powerful tool and effective tool designed to be used in the early stages of a penetration test or red team engagement
- [hydra](https://null-byte.wonderhowto.com/how-to/hack-like-pro-crack-online-passwords-with-tamper-data-thc-hydra-0155374/),  most powerfulcrack password tool
- [Nikto (Nikto2)](https://cirt.net/Nikto2), an Open Source ([GPL](http://www.gnu.org/licenses/licenses.html#GPL)) web server scanner which performs comprehensive tests against web servers for multiple items
- [Vulners Perimeter Scanner](https://vulners.com/vulners-perimeter-scanner), Vulnerability Assessment Platform
- [Log4j Detection](https://github.com/bi-zone/Log4j_Detector), on server
- [WPScan](https://wpscan.com/wordpress-security-scanner), мощный фреймворк для пентеста WordPress, обзор: https://habr.com/ru/company/alexhost/blog/527612/

# Полезные утилиты

### Prometheus - metrics and alerting with the leading open-source monitoring solution:

Официальный сайт и документация: https://prometheus.io/

Вводная статья на Habr: https://habr.com/ru/company/southbridge/blog/455290/

### Grafana - operational dashboards

Официальный сайт и документация: https://grafana.com/

GitHub: https://github.com/grafana/grafana

Пример внедрения: https://habr.com/ru/company/southbridge/blog/431122/

### Chipmunk - утилита для работы с большими логами:

GitHub: https://github.com/esrlabs/chipmunk 

Описание на Habr: https://habr.com/ru/post/496126/

### Balena Etcher - создание образов дисков на MacOS

Официальный сайт: https://www.balena.io/etcher/

На русском: https://balena-etcher.com/

# Интересные репозитарии в Git

# Разное
-   [You Might Not Need JS](http://youmightnotneedjs.com/), набор фич, некоторые их которых действительно можно сделать без JS;
-   [HTML DOM](https://htmldom.dev/), набор нативных функций для работы с DOM-деревом;
-   [Does it Mutate](https://doesitmutate.xyz/), подскажет, какие методы изменяют массив, а какие нет;
-   [Keycode Info](http://keycode.info/), покажет код нажатой клавиши;
-   [Tmstmp](https://bespoyasov.ru/tmstmp/), переводит даты в таймштампы и обратно;
-   [Generating Random Integers](https://stackoverflow.com/a/1527820/3141337), пример генерации случайного целого с подробным объяснением работы;
-   [Jest Mocking Strategies](https://mercedesbernard.com/blog/jest-mocking-strategies), мои моки в Jest никогда не работают с первого раза;
-   [Debounce / Throttle](http://demo.nimius.net/debounce_throttle/), показывает разницу между `debounce` и `throttle`;
-   [Anything to Anything Transformer](https://transform.tools/json-schema-to-openapi-schema), конвертирует что угодно во что угодно;

### Сервисы поиска исходного кода:
- [SearchCode](https://searchcode.com/)

### Менеджмент, управление, лидерство, корпоративная культура
- [Умные и честные заметки от Виталия Шароватова](https://github.com/bormaxi8080/teamlead), вынесено в отдельный репозиторий, форк

### Найм, HR и все, что с этим связано
- [Заметки о найме и российскрм HR](https://github.com/bormaxi8080/bormaxi-about-hiring, текст в процессе создания
- [Resume.io](https://resume.io/), конструктор CV

# Об авторе
Более подробно с моей биографией можно ознакомиться здесь:

> https://www.linkedin.com/in/i-maxi/

Благодарности и обратная связь:

> Обо всех пожеланиях по поводу содержимого данного репозитория и найденных ошибках можно сообщить в комментариях или в Telegram: @bormaxi
>
> Донаты в благодарность принимаются на карту Tinkoff: 5536 9138 6607 4988
или на Etherium: 0xe29685d6f0032bccac08b0e745a1a69ef9803973
