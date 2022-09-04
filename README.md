# oh-my-skills

### Что это?

Этот репозитарий содержит систематизированную коллекцию материалов о составляющих различных экосистем (основные концепции, ОС, языки и среды разработки, фреймворки, API, различные утилиты, базы данных, безопасность, тестирование и пентест и др.), с которыми сталкиваются современные разработчики. Руководство подойдет как для начинающих, так и для продвинутых специалистов.

> Репозитарий изначально создавался для личных нужд как справочник, но, возможно, будет полезен широкому кругу специалистов.
> Большая часть материалов касается работы на ОС стека MacOS и Linux, поскольку автору они ближе, чем остальные.
> Репозитарий не является полным справочником по всему и вся и пополняется автором по мере личной необходимости.

В репозитории я постарался собрать максимальное количество ссылок на полезные ресурсы по интересующим меня темам, не вдаваясь в длинные описания технологий и холивары по поводу их использования.

Некоторые книги и мануалы в формате PDF для удобства выложены в репозитарий programming-books, ссылки на них отмечены меткой `pb`

> [programming-books](https://github.com/bormaxi8080/programming-books)

По части материалов в данной документации ссылка ведет в репозитарий oh-my-backend (fork на roadmap по современным технологиям backend). Ссылки на такие материалы отмечены меткой `[omb]`

> [oh-my-backend](https://github.com/bzick/oh-my-backend)

## Содержание:
- [Общие знания](#общие-знания)
- [Операционные системы](#операционные-системы)
- [Виртуальные машины](#виртуальные-машины)
- [Протоколы и стандарты передачи данных](#протоколы-и-стандарты)
- [Базы данных](#базы-данных)
- [Проектирование и разработка](#проектирование-и-разработка)
- [Языки программирования](#языки-программирования)
- [Сервера приложений](#сервера-приложений)
- [Библиотеки и фреймворки](#бибилиотеки-и-фреймворки)
- [Frontend](#frontend)
- [Backend](#backend)
- [Мобильная разработка](#мобильная-разработка)
- [Популярные IDE](#популярные-IDE)
- [Пентестинг, безопасность и защита](#пентестинг-безопасность-и-защита)
- [Логи и метрики](#логи-и-метрики)
- [Полезные утилиты](#полезные-утилиты)
- [Разное](#разное)
- [Об авторе](#об-авторе)

# Общие знания
### Основы работы в ОС семейства Linux. Shell и командная строка
- [Linux](https://github.com/bzick/oh-my-backend#%D1%8D%D1%82%D0%B0%D0%BF-2-linux) `[omb]`
- [Advanced Bash Scripting Guide](https://www.opennet.ru/docs/RUS/bash_scripting_guide/)
- [Шпигорь И., Программирование на Bash с нуля](https://github.com/bormaxi8080/programming-books/blob/main/Shell/Bash_programming.pdf) `[pb]`
- [Вводная статья по Kali Linux](https://hackware.ru/?p=2767)
- [Oh My Zsh](https://ohmyz.sh/)- платформа с открытым исходным кодом для управления вашей конфигурацией Zsh. Поставляется в комплекте с тысячами полезных функций, помощников, плагинов, тем
- [Explain Shell](https://explainshell.com/), объясняет команды терминала и ключи к ним
- [watch](https://andreyex.ru/operacionnaya-sistema-linux/komanda-watch-v-linux/), команда watch
- [Команда ps, управление процессами в LInux](https://losst.ru/spisok-protsessov-linux)
- [Команда kill](https://www.linuxfoundation.org/blog/classic-sysadmin-how-to-kill-a-process-from-the-command-line/)

- Уведомления через Shell:
> - [Linux notify-send](https://ss64.com/bash/notify-send.html) 
>
> - [Собственные уведомления в Gnome](https://habr.com/ru/post/47892/)
>
> - [MacOS terminal-notifier](https://github.com/julienXX/terminal-notifier)

- [Работа с файлами в терминале Linux](https://comp-security.net/%D0%BA%D0%B0%D0%BA-%D0%BE%D1%82%D0%BA%D1%80%D1%8B%D1%82%D1%8C-%D1%84%D0%B0%D0%B9%D0%BB-%D0%B2-%D1%82%D0%B5%D1%80%D0%BC%D0%B8%D0%BD%D0%B0%D0%BB%D0%B5-linux/#:~:text=%D0%A2%D0%B5%D0%BA%D1%81%D1%82%D0%BE%D0%B2%D1%8B%D0%B9%20%D1%80%D0%B5%D0%B4%D0%B0%D0%BA%D1%82%D0%BE%D1%80%20Nano-,%D0%9A%D0%BE%D0%BC%D0%B0%D0%BD%D0%B4%D1%8B%20cat%20%D0%B8%20tac,%E2%80%93%20%D1%8D%D1%82%D0%BE%20%D0%BA%D0%BE%D0%BC%D0%B0%D0%BD%D0%B4%D0%B0%20%C2%ABcat%C2%BB.&text=%D0%9F%D0%BE%D1%81%D0%BB%D0%B5%20%D0%B2%D1%8B%D0%BF%D0%BE%D0%BB%D0%BD%D0%B5%D0%BD%D0%B8%D0%B5%20%D0%B4%D0%B0%D0%BD%D0%BD%D0%BE%D0%B9%20%D0%BA%D0%BE%D0%BC%D0%B0%D0%BD%D0%B4%D1%8B%20%D0%B2%D1%81%D0%B5,%D0%B1%D1%83%D0%B4%D0%B5%D1%82%20%D0%B2%D1%8B%D0%B2%D0%B5%D0%B4%D0%B5%D0%BD%D0%BE%20%D0%B2%20%D1%82%D0%B5%D1%80%D0%BC%D0%B8%D0%BD%D0%B0%D0%BB%20Linux.)
- [Работа с файлами по SSH на Linux](https://help.reg.ru/hc/ru/articles/4408047804433-%D0%9A%D0%BE%D0%BF%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5-%D1%84%D0%B0%D0%B9%D0%BB%D0%BE%D0%B2-%D1%87%D0%B5%D1%80%D0%B5%D0%B7-SSH)
- [Права доступа к файлам в Linux](https://losst.ru/prava-dostupa-k-fajlam-v-linux)
- [Утилита PM2](https://www.digitalocean.com/community/tutorials/how-to-set-up-a-node-js-application-for-production-on-ubuntu-18-04-ru) для развертывания беперебойной работы Node.js на сервере
- [Утилиты top, htop, atop и др.](https://habr.com/ru/post/114082/)

### Git
- [Базовая работа с Git](https://github.com/bzick/oh-my-backend#%D1%8D%D1%82%D0%B0%D0%BF-7-%D0%B1%D0%B5%D0%B7%D0%BE%D0%BF%D0%B0%D1%81%D0%BD%D0%BE%D1%81%D1%82%D1%8C) `[omb]`
- [Официальный сайт и документация](https://git-scm.com/)
- [Блог GitHub](https://github.blog)
- [Setting your commit email address](https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-personal-account-on-github/managing-email-preferences/setting-your-commit-email-address#about-commit-email-addresses)
- [Token authentication requirements for Git operations](https://github.blog/2020-12-15-token-authentication-requirements-for-git-operations/)
- [Генерация открытого SSH-ключа](https://git-scm.com/book/ru/v2/Git-%D0%BD%D0%B0-%D1%81%D0%B5%D1%80%D0%B2%D0%B5%D1%80%D0%B5-%D0%93%D0%B5%D0%BD%D0%B5%D1%80%D0%B0%D1%86%D0%B8%D1%8F-%D0%BE%D1%82%D0%BA%D1%80%D1%8B%D1%82%D0%BE%D0%B3%D0%BE-SSH-%D0%BA%D0%BB%D1%8E%D1%87%D0%B0)
- [Как создать ключ SSH в macOS](https://androidp1.ru/kak-sozdat-kljuch-ssh-v-macos/)
- [Connecting to GitHub with SSH](https://docs.github.com/en/authentication/connecting-to-github-with-ssh)
- [Why are my contributions not showing up on my profile?](https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-github-profile/managing-contribution-settings-on-your-profile/why-are-my-contributions-not-showing-up-on-my-profile)
- [Git за полчаса - руководство для начинающих](https://proglib.io/p/git-for-half-an-hour)
- [Интерактивный курс по Git](https://githowto.com/)
- [Oh shit! Git](https://ohshitgit.com/), подскажет, что делать, если вы допустили ошибку в гите
- [Git Explorer](https://gitexplorer.com/), справочник по командам и возможностям гита
- [О файле .gitignore](https://tyapk.ru/blog/post/gitignore)

### Форматы хранения и передачи данных
- [Форматы хранения и передачи данных](https://github.com/bzick/oh-my-backend#%D1%8D%D1%82%D0%B0%D0%BF-7-%D0%B1%D0%B5%D0%B7%D0%BE%D0%BF%D0%B0%D1%81%D0%BD%D0%BE%D1%81%D1%82%D1%8C) `[omb]`

### Работа с сетью
- [Сеть](https://github.com/bzick/oh-my-backend#%D1%8D%D1%82%D0%B0%D0%BF-4-%D1%81%D0%B5%D1%82%D1%8C) `[omb]`
- [Traceroute](https://ru.wikipedia.org/wiki/Traceroute)

### Markdown, редактура
- [Краткое руководство по MD](https://paulradzkov.com/2014/markdown_cheatsheet/)

- Obsidian - мощный редактор для работы с Markdown:
> - [Официальный сайт и документация](https://obsidian.md/)
>
> - [Небольшая вводная](https://habr.com/ru/company/macloud/blog/560776/)

- [Grip - утилита для автономного просмотра разметки MD](https://github.com/joeyespo/grip)
- [White Spaces](https://kirillbelyaev.com/s/), список всех существующих пробелов и рекомендации по использованию каждого
- [Типограф](https://typograf.github.io/mobile.html), правит пунктуацию, ставит неразрывные пробелы и проч.
- [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet), справочник по MD
- [Markdown Editor](https://readme.so/), визуальный редактор MD
- [Polacode](https://github.com/octref/polacode), скриншоттер для фрагментов кода
- [Vale: a command-line tool that brings code-like linting to prose](https://github.com/errata-ai/vale)

### Регулярные выражения
- [Regex 101](https://regex101.com/), редактор и тестер регулярных выражений с объяснениями каждого символа и примерами
- [Regular Excpressions Cheat Sheet](https://github.com/bormaxi8080/programming-books/blob/main/Other/RegExp_cheat_sheet.pdf) `[pb]` 

### Криптография
- [Криптография](https://github.com/bzick/oh-my-backend#%D1%8D%D1%82%D0%B0%D0%BF-7-%D0%B1%D0%B5%D0%B7%D0%BE%D0%BF%D0%B0%D1%81%D0%BD%D0%BE%D1%81%D1%82%D1%8C) `[omb]`

### Полнотекстовый поиск
- [Полнотекстовый поиск](https://github.com/bzick/oh-my-backend#%D1%8D%D1%82%D0%B0%D0%BF-10-%D0%BF%D0%BE%D0%BB%D0%BD%D0%BE%D1%82%D0%B5%D0%BA%D1%81%D1%82%D0%BE%D0%B2%D1%8B%D0%B9-%D0%BF%D0%BE%D0%B8%D1%81%D0%BA) `[omb]`

# Операционные системы

### MacOS
- [Официальное руководство пользователя MacOS](https://support.apple.com/ru-ru/guide/mac-help/welcome/mac)
- [MacAppStore - Search and Install any app on MacOS](https://macappstore.org/)
- [Homebrew Formulae - online package browser for Homebrew](https://formulae.brew.sh/)
- [MacBug](http://macbug.ru/)- хороший сайт о программировании под MacOs, iOS
- [Яблык](https://yablyk.com/) - все про Apple

### Ubuntu
- [Официальный сайт и документация](https://ubuntu.com/), Ubuntu
- [Про Ubuntu на русском](https://ubuntu.ru/)

### Debian
- [Официальный сайт и документация](https://www.debian.org/), Debian
- [В чём разница между Debian и Ubuntu? Что и когда лучше выбрать](https://habr.com/ru/company/ruvds/blog/576380/)

### Kali Linux
- [Официальный сайт и документация](https://kali.org), Kali Linux
- [Перевод официальной документации](https://hackware.ru/?p=2767), Kali Linux
- [Небольшая вводная статья](https://teletype.in/@hackerseverywhere/BympqZiD4), Kali Linux

# Облачные хостинги
- [Выбираем бесплатный сервер в облаке для тестовых целей, домашних проектов и т.д](https://habr.com/ru/post/332130/)

# Виртуальные машины

### Oracle VM VirtualBox
- [Официальный сайт и документация](https://www.virtualbox.org/), Oracle VM VirtualBox
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
- [Протокол HTTP](https://github.com/bzick/oh-my-backend#%D1%8D%D1%82%D0%B0%D0%BF-6-%D0%BF%D1%80%D0%BE%D1%82%D0%BE%D0%BA%D0%BE%D0%BB-http) `[omb]`
- [HTTP Statuses](https://httpstatuses.com/), список HTTP статусов ответа с их значениями;

### SMTP:
- [Электронная почта](https://github.com/bzick/oh-my-backend#%D1%8D%D1%82%D0%B0%D0%BF-9-%D1%8D%D0%BB%D0%B5%D0%BA%D1%82%D1%80%D0%BE%D0%BD%D0%BD%D0%B0%D1%8F-%D0%BF%D0%BE%D1%87%D1%82%D0%B0) `[omb]`
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
- [Базы данных](https://github.com/bzick/oh-my-backend#%D1%8D%D1%82%D0%B0%D0%BF-5-%D0%B1%D0%B0%D0%B7%D1%8B-%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85) `[omb]`
- [List of tz database time zones](https://en.wikipedia.org/wiki/List_of_tz_database_time_zones)
- [Checklist for Changing Data Model](https://rtpg.co/2021/06/07/changes-checklist.html), чеклист для миграции данных и схем данных.

### MySQL
- [Официальный сайт и документация](https://www.mysql.com/), MySQL
- [Документация на русском](http://www.mysql.ru/docs/), MySQL
- [Руководство по MySql на Metanit](https://metanit.com/sql/mysql/)
- [Оригинальный API для MySQL- PHP](https://www.php.net/manual/ru/book.mysql.php)

### MariaDB
- [Официальный сайт и документация](https://mariadb.com/), MariaDB
- [MariaDB foundation](https://mariadb.org/)
- [История проекта MariaDB](https://ru.wikipedia.org/wiki/MariaDB), MariaDB
- [Установка MariaDB на MacOS](https://mariadb.com/kb/en/installing-mariadb-on-macos-using-homebrew/)

### PostrgeSQL
- [Официальный сайт и документация](https://www.postgresql.org/), PostgreSQL
- [Установка и настройка PostgreSQL на Linux](https://wiki.calculate-linux.org/ru/postgresql)
- [Установка и настройка PostgreSQL на MacOS](https://www.sqlshack.com/setting-up-a-postgresql-database-on-mac/)
- [Setting up a PostgreSQL Database on Mac](https://www.sqlshack.com/setting-up-a-postgresql-database-on-mac/)
- [Настройка PostgreSQL под Linux](https://habr.com/ru/post/590599/)
- [Утилита psql](https://sysadminium.ru/postgresql-psql/)
- [How to change PostgreSQL user password?](https://stackoverflow.com/questions/12720967/how-to-change-postgresql-user-password)
- [PostgreSql Software Catalogue - Administration/development tools](https://www.postgresql.org/download/products/1-administrationdevelopment-tools/)
- [11 Best PostgreSQL Monitoring Tools](https://www.comparitech.com/net-admin/best-postgresql-monitoring-tools/)
- [Руководство по PostgreSQL на Metanit](https://metanit.com/sql/postgresql/)
- [Хорошие туториалы по PostgreSQL на английском](https://www.postgresqltutorial.com/)
- [Psycopg](https://www.psycopg.org/), PostgreSQL adapter for Python
- [PostgreSQL Notes For Professionals](https://github.com/bormaxi8080/programming-books/blob/main/Databases) `[pb]`
- [Шпаргалка по основным командам PostgreSQL](https://www.oslogic.ru/knowledge/598/shpargalka-po-osnovnym-komandam-postgresql/)
- [Запускаем PostgreSQL в Docker: от простого к сложному](https://habr.com/ru/post/578744/)

Pgpool-II:
- [PgPool-II Main page](https://pgpool.net/mediawiki/index.php/Main_Page)
- [Documentation (v.4.2)](https://www.pgpool.net/docs/42/en/html/index.html)
- [Перевод на русском](https://undenied.ru/2009/03/04/uchebnoe-rukovodstvo-po-pgpool-ii/)

### SQLite
- [Официальный сайт и документация](https://www.sqlite.org), SQLite

### MongoDB
- [Официальный сайт и документация](https://www.mongodb.com/), MongoDB
- [MongoDB Twitter account](https://twitter.com/MongoDB)
- [Руководство по MongoDB на Metanit](https://metanit.com/nosql/mongodb/)
- [Руководство по mongoDB на CoderLessons](https://coderlessons.com/tutorials/bazy-dannykh/uchitsia-mongodb/mongodb-kratkoe-rukovodstvo)
- [Примеры работы с MongoDB на Node.js](https://nodejsdev.ru/doc/mongodb/)
- [Бредшоу Ш., MongoDB: Полное руководство](https://github.com/bormaxi8080/programming-books/blob/main/Databases) `[pb]`

### InfluxDB
- [Знакомство с InfluxDB и базами данных временных рядов](https://tproger.ru/translations/influxdb-guide/)
- [Installing InfluxDB OSS](https://docs.influxdata.com/influxdb/v1.7/introduction/installation/)
- [The Definitive Guide To InfluxDB In 2019](https://devconnected.com/the-definitive-guide-to-influxdb-in-2019/)
- [Influx Admin Panel](https://grafana.com/grafana/plugins/natel-influx-admin-panel/)

# Проектирование и разработка
- [Проектирование и разработка](https://github.com/bzick/oh-my-backend#%D1%8D%D1%82%D0%B0%D0%BF-12-%D0%BF%D1%80%D0%BE%D0%B5%D0%BA%D1%82%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5-%D0%B8-%D1%80%D0%B0%D0%B7%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%BA%D0%B0) `[omb]`
- [highload.today](https://highload.today/), большой сайт, посвященный highload, backend, frontend и всякому остальному

### Дональд Кнут - Искусство программирования:
- [Том I](https://github.com/bormaxi8080/programming-books/blob/main/Other/Knut-1.pdf) `[pb]`
- [Том II](https://github.com/bormaxi8080/programming-books/blob/main/Other/Knut-2.pdf) `[pb]`
- [Том III](https://github.com/bormaxi8080/programming-books/blob/main/Other/Knut-3.pdf) `[pb]`

### Принципы разработки
### Алгоритмы
- [Адилья Бхаргва, Грокаем алгоритмы](https://github.com/bormaxi8080/programming-books/blob/main/Other/Bkhargava_Grokaem_Algoritmy.pdf) `[pb]`

### Архитектурные шаблоны
### Шаблоны проектирования
- [Джеймсон М. Смит, Элементарные шаблоны проектиования](https://github.com/bormaxi8080/programming-books/blob/main/Other/Smith_Elemental_Design_Patterns.pdf) `[pb]`

### Методологии разработки
- [Титус Виттерс, Делай как в Google (Software Engineering in Google)](https://github.com/bormaxi8080/programming-books/blob/main/Other/Software_Engineering_in_Google.pdf)`[pb]`

### Типы приложений
### Тестирование
-[PencilTests](https://github.com/bormaxi8080/PencilTests) `[pb]`, копия моей нашумевшей в свое время на Хабре статьи о тестировании карандаша ))

### Проблемы приложений и проектирования
### Рефакторинг
### Антипаттерны
### Semver
### Распределенные системы
### Микросервисная архитектура

# Языки программирования
- [Языки программирования](https://github.com/bzick/oh-my-backend#%D1%8D%D1%82%D0%B0%D0%BF-8-%D1%82%D1%83%D1%82-%D0%B4%D0%BE%D0%BB%D0%B6%D0%B5%D0%BD-%D0%B1%D1%8B%D1%82%D1%8C-%D0%B2%D0%B0%D1%88-%D1%8F%D0%B7%D1%8B%D0%BA-%D0%BF%D1%80%D0%BE%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F) `[omb]`
- [Тэйт Брюс, 7 языков за 7 недель](https://github.com/bormaxi8080/programming-books/blob/main/Other/Bruce_7langs_on_7weeks.pdf) `[pb]`

### JavaScript и SPA
- [Метриалы по JS, спецификация и учебник от Mozilla](https://developer.mozilla.org/ru/docs/Web/JavaScript)
- [JavaScript.COM](https://www.javascript.com/)
- [JavaScript.RU](https://javascript.ru/), исчерпывающая информация по JavaScript на русском
- [Learn JavaScript](https://learn.javascript.ru/), современный учебник по JavaScript

Илья Кантор - JavaScript, полное руководство `[pb]`:
- [Часть 1, основная](https://github.com/bormaxi8080/programming-books/blob/main/JS/Kantor_JS_Modern_Textbook_2019/js.pdf)
- [Часть 2, дополнения](https://github.com/bormaxi8080/programming-books/blob/main/JS/Kantor_JS_Modern_Textbook_2019/more.pdf)
- [Часть 3, UI](https://github.com/bormaxi8080/programming-books/blob/main/JS/Kantor_JS_Modern_Textbook_2019/ui.pdf)

- Вот этот парень у себя в LinkedIn делает классные мануалы/примеры кода по JS: https://www.linkedin.com/in/sam-shpakov/

### TypeScript
- [Официальный сайт и документация](https://www.typescriptlang.org/), TypeScript
- [Running and debugging TypeScript in JetBrains WebStorm](https://www.jetbrains.com/help/webstorm/running-and-debugging-typescript.html)

### C++
- [Официальный сайт стандарта C++](https://isocpp.org/)
- [Большой сайт по C++, документация](https://www.cplusplus.com/)
- [Туториалы по C++](https://www.w3schools.com/cpp/cpp_intro.asp)
- [Бьерн Страуструп, Язык программирования C++, 2 издание](https://github.com/bormaxi8080/programming-books/blob/main/CPP/straustrup_cpp.pdf) `[pb]`
- [Кувшинов Д., Язык C++: Основы программирования](https://github.com/bormaxi8080/programming-books/blob/main/CPP/kuvshinov_dr_osipov_si_osnovy_programmirovaniia_iazyk_c_P.pdf) `[pb]`

### Rust
- [Официальный сайт и документация](https://www.rust-lang.org/), Rust
- [Rust в примерах](https://doc.rust-lang.ru/stable/rust-by-example/)
- [Русскоговорящее сообщество Rust](https://rust-lang.ru/)
- [Разбор особенностей Rust и некоторые ссылки](https://habr.com/ru/post/433302/)

### Java
- [Официальный сайт Java](https://www.java.com/)
- [Официальная документация по Java](https://dev.java/)
- [Java на русском](https://www.java.com/ru/)
- [Хаб на Habr](https://habr.com/ru/hub/java/), Java
- [Раздел по Java на Metanit](https://metanit.com/java/)

### Scala
- [Официальный сайт и документация](https://www.scala-lang.org/), Scala
- [Хаб на Habr](https://habr.com/ru/hub/scala/), Scala

### Python
- [Официальный сайт и документация](https://www.python.org/), Python
- [David Beazley, Python: подробный справочник](https://github.com/bormaxi8080/programming-books/blob/main/Python/Python.podrobnyj.spravochnik.4.e.izdanie.David.M.Beazley.2010.pdf) `[pb]`
- [Васильев А, Программирование на Python в задачах и примерах](https://github.com/bormaxi8080/programming-books/blob/main/Python/Vasiliev_Programming_Python.pdf) `[pb]`
- [Материалы по Python на TProger](https://tproger.ru/tag/python/)
- [Хаб на Хабре](https://habr.com/ru/hub/python/), Python
- [Find, install and publish Python packages with the Python Package Index](https://pypi.org), поисковик по библиотекам
- [Awesome Python](https://chel-center.ru/python-yfc/awesome-python/), курс молодого бойца
- [Абстрактные классы и интерфейсы в Python](https://habr.com/ru/post/72757/)
- [Работа с конфигурационными файлами в Python](https://habr.com/ru/post/485236/)
- [Антипаттерн settings.py](https://habr.com/ru/post/115893/)
- [Logging facility for Python](https://docs.python.org/3/library/logging.html)
- [Логгирование в Python](https://python-scripts.com/logging-python)
- [Настройка логирования в Python](https://habr.com/ru/sandbox/150814/), повышаем информативность лога
- [Модуль Queue](https://docs.python.org/3/library/queue.html)
- [Библиотеки для работы с SQLite](https://pyneng.readthedocs.io/ru/latest/book/25_db/sqlite3.html)
- [Работа с JSON в Python](https://python-scripts.com/json)
- Celery: см. отдельный раздел ниже

### GoLang
- [Официальный сайт и документация](https://go.dev/), GoLang
- [Материалы по Go](https://gist.github.com/egorsmkv/9df2aef2eddf51986b6d2b5833a4423e), egorsmkv
- [GoLang Training](https://github.com/GoesToEleven/GolangTraining), GoesToEleven
- [Эффективный Go](https://github.com/Konstantin8105/Effective_Go_RU), Konstantin8105
- [Bulid applications with GoLang](https://github.com/astaxie/build-web-application-with-golang/blob/master/ru/preface.md)

Книги:
- [Введение в программирование на Go](http://golang-book.ru/), GitHub: https://github.com/maxpoletaev/golang-book
- [Максим Жашкевич, Язык Go для начинающих](https://github.com/bormaxi8080/programming-books/blob/main/GoLang/Zhashkevich_Go_for_Beginners_2021.pdf) `[pb]`
- [Мэтью А. Титмус, Облачный Go](https://github.com/bormaxi8080/programming-books/blob/main/GoLang/Titmus_Cloud_Native_Go_2022.pdf) `[pb]`
- [Cloud Native Go examples](https://github.com/cloud-native-go/examples)
- [Маленькая книга о Go](https://sefus.ru/little-go-book/)

Разное:
- [Шпаргалка по структурам данных в Go](https://habr.com/ru/post/456194/)
- [Парсинг файлов CSV в Go](https://golangify.com/parsing-csv)
- [Vegeta](https://github.com/tsenart/vegeta), GoLang HTTP Load Testing Tool and Library

### PHP
- [Официальный сайт и документация по PHP](https://www.php.net/), PHP
- [Дэвид Скляр, PHP: Сборник рецептов](https://github.com/bormaxi8080/programming-books/blob/main/PHP/Sklyar_PHP_Reciepts.pdf) `[pb]`

### Ruby, RubyOnRails
- [Официальный сайт и документция](https://www.ruby-lang.org/ru/), Ruby
- [RubyOnRails ORG](https://rubyonrails.org/)
- [Чем хорош RubyOnRails и как он ускоряет разработку](https://habr.com/ru/company/skillbox/blog/428487/)
- [Хороший сайт про Ruby на русском](http://www.rubyonrails.ru/)

### Perl
- [Официальный сайт и документация](https://www.perl.org/), Perl
- [Хаб на Хабре](https://habr.com/ru/hub/perl/), Perl
- [Краткий экскурс в Perl-программирование](https://www.opennet.ru/docs/RUS/perl_help/)

### Lua
- [Официальный сайт и документация](https://www.lua.org/), Lua
- [Lua за 15 минут](https://habr.com/ru/post/184538/)
- [Learn Lua](http://tylerneylon.com/a/learn-lua/)
- [Хороший мануал по Lua на русском](https://docs.geoscan.aero/ru/master/programming/lua/lua_main.html)
- [Хаб на Хабре](https://habr.com/ru/hub/lua/), Lua

### Erlang
- [Официальный сайт и документация](https://www.erlang.org/), Erlang
- [Краткое руководство на CoderLessons](https://coderlessons.com/tutorials/kompiuternoe-programmirovanie/vyuchit-erlang/erlang-kratkoe-rukovodstvo)
- [Руководство по программированию на языке Erlang](https://pessim50.ucoz.ru/Erlang.pdf)
- [Специфика Erlang](https://eax.me/erlang-is-specific/)
- [Программирование на языке Erlang](https://github.com/bormaxi8080/programming-books/blob/main/Other/Erlang-programming-guide.pdf) `[pb]`

# Сервера приложений
### NATS
- [Официальный сайт и документация](https://nats.io/), NATS

### Redis
- [Официальный сайт и документация](https://redis.io/), Redis is an open source in-memory data structure store, used as a database, cache, and message broker
- [Маленькая книга о Redis](https://3s.group/upload/iblock/890/890258c1a79e7154773b210ea701b184.pdf), оно же [тут](https://github.com/bormaxi8080/programming-books/blob/main/Other/Seguin_redis-liitle-book.pdf) `[pb]`
- [Команды Redis](https://redis.io/commands/)
- [Redis для начинающих](https://webdevblog.ru/redis-dlya-nachinajushhij/)
- [Вводная по Redis на AWS](https://aws.amazon.com/ru/redis/)
- [Шпаргалка по Redis на Хабре](https://habr.com/ru/post/204354/)
- [Redis в Python](https://python-scripts.com/redis), полная документация на примерах
- [Redis Queue в Python](https://khashtamov.com/ru/python-rq-howto/)

### Memcached
- [Официальный сайт и документация](https://memcached.org/), Memcached is a distributed memory object caching system
- [Маленькая вводная по Memcached](https://habr.com/ru/post/42607/)
- [Описание Memcached от AWS](https://aws.amazon.com/ru/memcached/), сравнение с Redis

### RabbitMQ
- [Официальный сайт и документация](https://www.rabbitmq.com/), RabbitMQ message broker
- [Введение в RabbitMQ](https://habr.com/ru/post/488654/)
- [Установка и настройка RabbitMQ в MacOS](https://russianblogs.com/article/91201405100/)
- Маленькое руководство по старту на Habr: [часть 1](https://habr.com/ru/post/149694/) и [часть 2](https://habr.com/ru/post/150134/)
- [Коротко о работе с RabbitMQ из Python](https://habr.com/ru/post/434510/)
- [Cloud AMQP Blog](https://www.cloudamqp.com/blog/index.html), хороший блог про AMQP, RabbitMQ и все, связанное с протоколом
- [Pika](https://pika.readthedocs.io/en/stable/index.html), pure Python implementation of the AMQP 0-9-1 protocol
- [Pika Examples](https://github.com/pika/pika/tree/master/examples), official
- [Using the Pika client](https://www.rabbitmq.com/tutorials/tutorial-two-python.html)
- [Простые примеры на Pika](https://habr.com/ru/sandbox/126064/) Python для работы со статичными (reject) очередями RabbitMQ
- [aio-pika](https://aio-pika.readthedocs.io/en/latest/rabbitmq-tutorial/2-work-queues.html), AsyncIO Pika library
- [Мониторинг сообщений в RabbitMQ](https://habr.com/ru/post/447412/)
- [Building microservices for Telegram bot using Node.js, RabbitMQ, MongoDB and Docker from scratch](https://medium.com/@denismalykhin/building-microservices-for-telegram-bot-using-node-js-rabbitmq-mongodb-and-docker-from-scratch-12640d172b8f)

RabbitMQ for Beginners - Sample code for Python:
- [Part 1](https://www.cloudamqp.com/blog/avalanchemq-for-beginners-part-1-what-is-avalanchemq.html)
- [Part 2](https://www.cloudamqp.com/blog/avalanchemq-for-beginners-part-2-getting-started-with-python.html)

### Celery
- [Официальный сайт и документация](http://celeryproject.org/), Celery Async Message Queue
- [GitHub](https://github.com/celery/celery), Celery
- [Введение в Celery](https://docs.celeryproject.org/en/stable/getting-started/introduction.html), оно же [на русском](https://django.fun/docs/celery/ru/5.1/userguide/)
- [Celery - лучшие практики](https://habr.com/ru/post/269347/)
- [Celery - начинаем правильно](https://khashtamov.com/ru/celery-best-practices/)
- [50 оттенков Celery](https://habr.com/ru/company/oleg-bunin/blog/433476/)
- [Celery Python](https://dev-gang.ru/article/celery-python-osnovy-i-primery-ba4pn1pyb9/), основы и примеры
- [3 кейса для использования Celery в Django-приложении](https://habr.com/ru/post/461775/)
- [Django и Celery](https://django.fun/tutorials/django-i-celery-1-ustanovka/), в связке
- [Пакет django-celery](https://github.com/adilkhash/django-celery)
- [Flask & Celery](https://chel-center.ru/python-yfc/2021/05/12/asinhronnye-zadachi-s-celery-v-python/), Асинхронные задачи с Celery в Python
- [Celery Configuration and Defaults](https://docs.celeryproject.org/en/stable/userguide/configuration.html)
- [Настраиваем Celery в Django проекте](https://hashsum.ru/celery-django-redis/)
- [Celery Periodic Tasks](https://docs.celeryproject.org/en/latest/userguide/periodic-tasks.html?highlight=periodic)
- [Usign Celery with Django](https://docs.celeryproject.org/en/stable/django/first-steps-with-django.html)
- [Example Django project using Celery](https://github.com/celery/celery/tree/master/examples/django/)
- [Asynchronous Tasks with Celery, Flask & RabbitMQ](https://docs.google.com/presentation/d/14tXlzbsMwZXCum5jQDI_WLO-FJKSjAO0xIpP-hrn6r8/htmlpresent)
- [# Creating a click counter using Kombu and celery](https://docs.celeryproject.org/en/v2.3.3/tutorials/clickcounter.html), и тут [примерно оно же](https://tproger.ru/articles/ispolzovanie-django-celery-beat-dlja-sozdanija-periodicheskih-zadach-v-django-proektah/) на русском

- [Flower](https://github.com/mher/flower), web based tool for monitoring and administrating Celery clusters
- [Kombu](https://docs.celeryproject.org/projects/kombu/en/stable/index.html), messaging library for Python
- [celery-message-consumer](https://github.com/depop/celery-message-consumer), Tool for using the bin/celery worker to consume vanilla AMQP messages (i.e. not Celery tasks)

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
- [Telegram-боты](https://tlgrm.ru/docs/bots): информация для разработчиков (официальная документация)
- [Telegram API](https://core.telegram.org/api/obtaining_api_id)
- [Модуль Telegram](https://vc.ru/services/278869-modul-telegram-sozdanie-chat-bota-i-kanala-minimalnye-nastroyki-komponentov), создание чат-бота и канала, минимальные настройки компонентов
- [Всё, о чём должен знать разработчик Телеграм-ботов](https://habr.com/ru/post/543676/)
- [Пишем ботов для Telegram на языке Python](https://mastergroosha.github.io/telegram-tutorial/)
- [Неплохой разбор полетов с ботами для Telegram](https://habr.com/ru/company/ods/blog/462141/)
- [Python telegram.ext package](https://python-telegram-bot.readthedocs.io/en/stable/telegram.ext.html_
- [Лимиты, существующие в Telegram](https://www.vamtlgrm.com/limity-sushhestvuyushhie-v-telegram/)

Async.IO:

- [Async.IO в Python 3](http://onreader.mdl.ru/UsingAsyncioPython3/content/index.html#ToC)

AIOgram async framework:
- [AIOgram GitHub](https://github.com/aiogram/aiogram)
- [Официальная документация по AIOgram](https://docs.aiogram.dev/en/latest/)
- [Быстрый старт](https://surik00.gitbooks.io/aiogram-lessons/content/chapter1.html)
- [Telegram-бот на Python за полчаса с AIOgram](https://tproger.ru/articles/telegram-bot-create-and-deploy/)
- [Знакомство с AIOgram](https://mastergroosha.github.io/telegram-tutorial-2/quickstart/)
- [AIOgram Broadcaster Library](https://botfather.dev/blog/aiogram-broadcaster-library)
- [aiojobs](https://aiojobs.readthedocs.io/en/stable/), Jobs scheduler library for managing background task

Платежи в Telegram:
- [Подключение оплат](https://vc.ru/dev/240195-kak-nastroit-priem-platezhey-2-0-v-telegram-za-5-chasov)
- [Как настроить прием платежей 2.0 в Telegram за 5 часов](https://vc.ru/dev/240195-kak-nastroit-priem-platezhey-2-0-v-telegram-za-5-chasov)

### Django
- [Официальный сайт и документация](https://www.djangoproject.com/), Django
- [Документация по Django от Mozilla](https://developer.mozilla.org/ru/docs/Learn/Server-side/Django)
- [Исчерпывающая книга про Django](https://djbook.ru/rel3.0/), неплохая документация на русском
- [DJBook](https://djbook.ru/), и тут всего остального про Django навалом
- [Хаб по Django на Хабре](https://habr.com/ru/hub/django/), Django
- [Django fun](https://django.fun/)
- [Статьи про Django](https://django.fun/tutorials/)
- [Django models best practices](https://techrocks.ru/2021/04/22/django-models-best-practices/)
- [Справочник по полям модели](https://djbook.ru/rel1.9/ref/models/fields.html#django.db.models.DateField)
- [Транзакции в Django](https://django.fun/docs/django/ru/3.2/topics/db/transactions/)
- [Transaction Management with Django](https://realpython.com/transaction-management-with-django-1-6/)
- [django-filter module](https://django-filter.readthedocs.io/en/stable/guide/usage.html)

### Flask
- [Официальный сайт и документация](https://flask.palletsprojects.com/en/2.0.x/), Flask
- [Русский перевод документации Flask](https://flask-russian-docs.readthedocs.io/ru/latest/)
- [Учебник по Flask на Habr](https://habr.com/ru/post/193242/)

### Pyramid
- [Официальный сайт и документация](https://trypyramid.com/), Pyramid
- [Руководство по Pyramid на Habr](https://habr.com/ru/post/135916/)
- [Еще доки по Pyramid](https://docs.pylonsproject.org/projects/pyramid/en/latest/index.html)

### Tornado
- [Официальный сайт и документация](https://www.tornadoweb.org/en/stable/), Tornado web server
- [Небольшая вводная в Tornado](https://habr.com/ru/sandbox/27705/)

### Docker
- [Docker - Официальный сайт и документация](https://docs.docker.com/)
- [Установка и настройка Docker в Ubuntu](https://selectel.ru/blog/docker-install-ubuntu/)
- [Docker - быстрый старт](https://tproger.ru/translations/how-to-start-using-docker/)
- [Полное практическое руководство по Docker](https://habr.com/ru/post/310460/), на русском
- [Виртуализация Docker](https://github.com/bzick/oh-my-backend#%D1%8D%D1%82%D0%B0%D0%BF-1-%D0%B2%D0%B8%D1%80%D1%82%D1%83%D0%B0%D0%BB%D0%B8%D0%B7%D0%B0%D1%86%D0%B8%D1%8F-docker) `[omb]``
- [Иан Милл, Docker на практике](https://github.com/bormaxi8080/programming-books/blob/main/Docker/Mill_Seers_Docker_in_Practice.pdf) `[pb]`
- [Основные команды Docker](https://timeweb.com/ru/community/articles/osnovnye-komandy-docker)
- [10 команд для Docker, без которых вам не обойтись](https://tproger.ru/translations/top-10-docker-commands/)

### Kubernetes
- [Официальная документация по Kubernetes](https://kubernetes.io/ru/docs/home/)
- [Бернс, Kubernetes: Лучшие практики для профессионалов](https://github.com/bormaxi8080/programming-books/blob/main/DevOps/Berns_Kubernetes_Best_Practices.pdf) `[pb]`

# Frontend
### React.js
- [Learn React.js](https://learn-reactjs.ru/home), полное руководство по React
- [Пацианский М., React.js для начинающих](https://github.com/bormaxi8080/programming-books/blob/main/Frontend/react-course-ru.pdf) `[pb]`
- [Пацианский М., React Router](https://github.com/bormaxi8080/programming-books/blob/main/Frontend/react-router-course-ru.pdf) `[pb]`
- [Пацианский М., Reduх](https://github.com/bormaxi8080/programming-books/blob/main/Frontend/redux-course-ru.pdf) `[pb]`

### Vue.js
- [Хэнчетт Э,, Vue.js в действии](https://github.com/bormaxi8080/programming-books/blob/main/Frontend/Hanchett_Vue-in-acion.pdf) `[pb]`
- [Подходит ли Vue для создания большого веб-приложения](https://github.com/bormaxi8080/programming-books#:~:text=%D0%9F%D0%BE%D0%B4%D1%85%D0%BE%D0%B4%D0%B8%D1%82%20%D0%BB%D0%B8%20Vue%20%D0%B4%D0%BB%D1%8F%20%D1%81%D0%BE%D0%B7%D0%B4%D0%B0%D0%BD%D0%B8%D1%8F%20%D0%B1%D0%BE%D0%BB%D1%8C%D1%88%D0%BE%D0%B3%D0%BE%20web%2D%D0%BF%D1%80%D0%B8%D0%BB%D0%BE%D0%B6%D0%B5%D0%BD%D0%B8%D1%8F.%20%D0%94%D0%BE%D0%BA%D0%BB%D0%B0%D0%B4) `[pb]`

### Go Hugo:
- [Официальный сайт и документация](https://gohugo.io/), Go Hugo
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
- [Различия между HTML(4) и HTML5](https://www.hostinger.ru/rukovodstva/chto-takoe-html-i-ih-razlichiya)

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
- [CSS Patterns](https://projects.verou.me/css3patterns/), коллекция фоновых узоров на чистом CSS
- [CSS Shapes](https://css-tricks.com/the-shapes-of-css/), набор часто используемых фигур на чистом CSS
- [CSS Triggers](https://csstriggers.com/), подскажет, какие свойства запускают layout, paint и composite

### Браузерные расширения Chrome и Firefox:
- [Как посмотреть исходный код любого расширения в браузере](https://mipped.com/polezno/9742-kak-posmotret-ishodnyy-kod-lyubogo-rasshireniya-v-brauzere.html)

### Bootstrap
- [Официальный сайт и документация](https://getbootstrap.com/)
- [Создание быстрых отзывчивых сайтов с Bootstrap](https://bootstrap-4.ru/), документация на русском

### Material UI
- [Официальный сайт и документация](https://mui.com/), Material UI
- [Reactjs, Material-UI with JSS])(https://habr.com/ru/post/492378/), крайткий гайд
- [MUI React templates & tools satore](https://material-ui.com/store/)
- [Material Design](https://material.io/)
- [Material Design Components](https://material.io/components)

### UX
- [UX Club](https://www.facebook.com/groups/136827946465842), самое большое российское коммьюнити по UX

# Backend
### Nest.js
- [Официальный сайт и документация по Nest.js](https://nestjs.com/)
- [Гайд по Nest.js: что это такое и как написать свой первый код](https://ru.hexlet.io/blog/posts/gid-po-nest-js)

### Node.js
- [Официальный сайт и документация по Node.js](https://nodejs.org/)
- [Официальные руководства](https://nodeguide.ru/doc/)
- [Руководство по Node.js на Habr](https://habr.com/ru/company/ruvds/blog/422893/)
- [Install Node.js via Package Manager](https://nodejs.org/tr/download/package-manager/#macos)
- [Управление версиями Node.js и NPM с помощью NVM](https://habr.com/ru/company/timeweb/blog/541452/)
- [Полная версия руководства по Node.js на Habr](https://habr.com/ru/company/ruvds/blog/428576/) + PDF
- [Сайт для разработчиков Node.js](https://nodejsdev.ru/), на русском
- [Node.js. Официальное руководство](https://github.com/bormaxi8080/programming-books/blob/main/JS/Node.js_Official_Guide.pdf) `[pb]`
- [Руководство на Metalint](https://metanit.com/web/nodejs/)
- [Управление версиями Node.js и NPM](https://habr.com/ru/company/timeweb/blog/541452/), с помощью NVM
- [Using Node in JetBrains WebStorm](https://www.jetbrains.com/help/webstorm/developing-node-js-applications.html#ws_node_version)
- [Многопоточность в Node.js](https://tproger.ru/translations/guide-to-threads-in-node-js/)
- [Как работает Event Loop в Node.js](https://frontender.info/understanding-the-node-js-event-loop/)
- [Докеризация приложения Node.js](https://nodejs.org/ru/docs/guides/nodejs-docker-webapp/)

Книги:

> - https://monster-book.com/node-js
>
> - https://habr.com/ru/company/ruvds/blog/428576/

Express Framework:

- [Официальный сайт и документация по Express](https://expressjs.com/ru/), Express
- [Руководство по Express от Mozilla](https://developer.mozilla.org/ru/docs/Learn/Server-side/Express_Nodejs)

- [Fastify](https://www.fastify.io/), краткий обзор: https://habr.com/ru/post/555668/
- [cors](https://expressjs.com/en/resources/middleware/cors.html)

Async Framework:

> - [Async, официальная документация по Async](https://caolan.github.io/async/v3/docs.html) 
>
> - [Руководство по Async](https://developer.mozilla.org/ru/docs/Learn/Server-side/Express_Nodejs/Displaying_data/flow_control_using_async), от Mozilla

Passport.js:

- [Passport.js - официальный сайт и документация по Passport.js](https://www.passportjs.org/)
- [Еще раз о passport.js](https://habr.com/ru/post/435106/)

Push notifications:

- [push.js](https://ru.stackoverflow.com/questions/264422/push-notifications)
- [Pusher - Powering realtime experiences for mobile and web](https://pusher.com/)
- [Pusher - NPM](https://www.npmjs.com/package/pusher)

Lodash:

- [Lodash](https://lodash.com/docs/), краткий обзор: https://habr.com/ru/post/217515/

Nest.js:

- [Официальный сайт Nest.js](https://nestjs.com)
- [Nest.js documentation](https://docs.nestjs.com/)
- [Гайд по Nest.js: что это такое и как написать свой первый код](https://ru.hexlet.io/blog/posts/gid-po-nest-js)
- [NestJS - тот самый, настоящий бэкенд на nodejs](https://habr.com/ru/post/439434/)


Разное:
- [json2md](https://www.npmjs.com/package/json2md), JSON to Markdown converter
- [Node-fetch](https://www.npmjs.com/package/node-fetch), XMLHttpRequest emplementation library
- [Chalk](https://github.com/chalk/chalk), раскраска терминала
- [Debug](https://developer.ibm.com/articles/intro-to-the-nodejs-debug-module/), библиотека для отладки
- [Moment](https://momentjs.com/), библиотека для работы с датой и временем
- [Nodemon](https://www.digitalocean.com/community/tutorials/workflow-nodemon-ru)
- [request-ip](https://www.npmjs.com/package/request-ip)

- Puppeteer - скрапинг web-сайтов:
> - https://github.com/puppeteer/puppeteer 
>
> - https://habr.com/ru/company/oleg-bunin/blog/421137/
>
> - https://habr.com/ru/company/ruvds/blog/341348/
>
> - https://habr.com/ru/post/413547/

- [Lerna](https://github.com/lerna/lerna), A tool for managing JavaScript projects with multiple packages

Socket.IO

- [Socket.IO - сайт и документация](https://socket.io/)

Swagger:

- [Node.js: документирование и визуализация API с помощью Swagger](https://habr.com/ru/company/timeweb/blog/594081/)
- [swagger-autogen npm package](https://www.npmjs.com/package/swagger-autogen)
- [API versioning in Node.js](https://stackoverflow.com/questions/51513715/node-js-rest-api-versioning-the-right-way)
- [Setting Up Automated Semantic Versioning For Your NodeJS Project](https://soshace.com/setting-up-automated-semantic-versioning-for-your-nodejs-project/)
- [Swagger-autogen](https://www.npmjs.com/package/swagger-autogen)

- Модули node для работы с SQLite:

> - [node-sqlite](https://github.com/grumdrig/node-sqlite)
> 
> - [node-sqlite3](https://github.com/mapbox/node-sqlite3)
>
> - [better-sqlite3](https://www.npmjs.com/package/better-sqlite3)
>
> - [Что выбрать](https://coderoad.ru/14355004/%D0%A7%D1%82%D0%BE-SQLite-%D0%B8%D1%81%D0%BF%D0%BE%D0%BB%D1%8C%D0%B7%D0%BE%D0%B2%D0%B0%D1%82%D1%8C-%D1%81-nodejs)
>
> - [Визуализация SQLite в Node.js](https://habr.com/ru/company/vdsina/blog/527146/)

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
- [Райанн Митчелл, Современный скраппинг веб-сайтов с помощью Python](https://github.com/bormaxi8080/programming-books/blob/main/Other/Mitchel_Python_Web_Scraping.pdf) `[pb]`

# Мобильная разработка
### iOS

Objective C:
- [Официальная документация по ObectiveC от Apple](https://developer.apple.com/library/archive/documentation/Cocoa/Conceptual/ProgrammingWithObjectiveC/Introduction/Introduction.html)
- [Objective C с нуля](https://habr.com/ru/post/107126/)

Swift:
- [Официальный сайт и документация](https://www.swift.org/), Swift
- [Официальная документация по Swift от Apple](https://developer.apple.com/documentation/swift)
- [Хаб на Habr](https://habr.com/ru/hub/swift/), Swift

Cocoa:
- [Официальная документация по Cocoa от Apple](https://developer.apple.com/library/archive/documentation/Cocoa/Conceptual/CocoaFundamentals/WhatIsCocoa/WhatIsCocoa.html)
- [Учебник Cocoa на русском](http://macbug.ru/cocoa.php)
- [Хаб на Habr](https://habr.com/ru/hub/cocoa/), Cocoa

Flutter:
- [Фрэнк Заметти, Flutter на практике](https://github.com/bormaxi8080/programming-books/blob/main/Other/Flutter_on_practice_2020.pdf) `[pb]`

### Android

Android Core:
- [Android Official Documentation](https://developer.android.com/)
- [Android Developers Community](https://developer.android.com/)
- [Android Studio](https://developer.android.com/studio)
- [Android JetPack](https://developer.android.com/jetpack)
- [Про Android на русском](https://www.android.com/intl/ru_ru/), Android.com
- [Хаб на Habr](https://habr.com/ru/hub/android_dev/), Android

Kotlin:
- [Develop Android apps with Kotlin (official)](https://developer.android.com/kotlin)

# Популярные IDE
### Cемейство IDE от JetBrains
- [Официальный сайт и документация](https://www.jetbrains.com/), JetBrains

### Eclipse IDE
- [Официальный сайт и документация](https://www.eclipse.org/ide/), Eclipse IDE

# Пентестинг, безопасность и защита
- [Безопасность](https://github.com/bzick/oh-my-backend#%D1%8D%D1%82%D0%B0%D0%BF-7-%D0%B1%D0%B5%D0%B7%D0%BE%D0%BF%D0%B0%D1%81%D0%BD%D0%BE%D1%81%D1%82%D1%8C) `[omb]`
- [Эндрю Хоффман, Безопасность web-приложений: разведка, защита, нападение](https://github.com/bormaxi8080/programming-books/blob/main/Other/Hoffman_Web_applications_security.pdf) `[pb]`
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
- [Часть 10 - Упорядочивание утилит](https://www.securitylab.ru/analytics/492935.php)

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

- Обзоры Metasploit:
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

# Логи и метрики

- [Логи и метрики](https://github.com/bzick/oh-my-backend#%D1%8D%D1%82%D0%B0%D0%BF-11-%D0%BB%D0%BE%D0%B3%D0%B8-%D0%B8-%D0%BC%D0%B5%D1%82%D1%80%D0%B8%D0%BA%D0%B8) `[omb]`
- [Retrace](https://stackify.com/retrace/), log analyzing platform

### Prometheus
- [Официальный сайт и документация](https://prometheus.io/), Prometheus - metrics and alerting with the leading open-source monitoring solution
- [Введение в мониторинг серверов с помощью Prometheus и Grafana](https://habr.com/ru/post/652185/)
- [Полное руководство по Prometheus в 2019 году](https://habr.com/ru/company/southbridge/blog/455290/)

### Grafana
- [Официальный сайт и документация](https://grafana.com/), Grafana - operational dashboards
- [GitHub](https://github.com/grafana/grafana)
- [Пример внедрения](https://habr.com/ru/company/southbridge/blog/431122/)

### Chipmunk

- [GitHub](https://github.com/esrlabs/chipmunk), Chipmunk - утилита для работы с большими логами
- [Описание на Habr](https://habr.com/ru/post/496126/), Chipmunk

# Полезные утилиты

[Bookmarklets](https://habr.com/ru/company/theonlypage/blog/234427/) - simple Javascript code features:
- [Использование bookmarklets](https://habr.com/ru/post/52346/)
- [Содание букмарклетов - правильный путь](https://coderlessons.com/articles/veb-razrabotka-articles/sozdanie-bukmarkletov-pravilnyi-put)
- [bookmarklets.com collection](http://bookmarklets.com/tools/categor.html)
- [Favelets](https://tantek.com/favelets/)
- [squarefree.com bookmarklets collection](https://www.squarefree.com/bookmarklets/)

Balena Etcher - создание образов дисков на MacOS:
- [Официальный сайт](https://www.balena.io/etcher/)
- [На русском](https://balena-etcher.com/)

Calibre - управление электронной библиотекой:
- [Руководство пользователя Calibre](https://manual.calibre-ebook.com/ru/)
- [Настройка среды разработки Calibre](https://manual.calibre-ebook.com/ru/develop.html)

# Разное

- [You Might Not Need JS](http://youmightnotneedjs.com/), набор фич, некоторые их которых действительно можно сделать без JS
- [HTML DOM](https://htmldom.dev/), набор нативных функций для работы с DOM-деревом
- [Does it Mutate](https://doesitmutate.xyz/), подскажет, какие методы изменяют массив, а какие нет
- [Keycode Info](http://keycode.info/), покажет код нажатой клавиши
- [Tmstmp](https://bespoyasov.ru/tmstmp/), переводит даты в таймштампы и обратно
- [Generating Random Integers](https://stackoverflow.com/a/1527820/3141337), пример генерации случайного целого с подробным объяснением работы
- [Jest Mocking Strategies](https://mercedesbernard.com/blog/jest-mocking-strategies), мои моки в Jest никогда не работают с первого раза
- [Debounce / Throttle](http://demo.nimius.net/debounce_throttle/), показывает разницу между `debounce` и `throttle`
- [Anything to Anything Transformer](https://transform.tools/json-schema-to-openapi-schema), конвертирует что угодно во что угодно
- [List of Chrome URLs](chrome://chrome-urls/)

### Сервисы поиска исходного кода:
- [SearchCode](https://searchcode.com/)

### Менеджмент, управление, лидерство, корпоративная культура
- [Умные и честные заметки от Виталия Шароватова](https://github.com/bormaxi8080/teamlead), вынесено в отдельный репозиторий, форк

### Найм, HR и все, что с этим связано
- [Заметки о найме и российскрм HR](https://github.com/bormaxi8080/bormaxi-about-hiring, текст в процессе создания
- [Resume.io](https://resume.io/), конструктор CV

# Благодарности и обратная связь:

> Обо всех пожеланиях по поводу содержимого данного репозитария и найденных ошибках можно сообщить в Issues или в Telegram: @bormaxi
>
> Донаты в благодарность принимаются на Etherium: 0xe29685d6f0032bccac08b0e745a1a69ef9803973