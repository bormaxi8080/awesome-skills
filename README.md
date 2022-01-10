# oh-my-skills
**Что это?** Этот репозиторий содержит систематизированную коллекцию материалов о составляющих различных экосистем (основные концепции, ОС, языки и среды разработки, фреймворки, API, различные утилиты, базы данных, безопасность, тестирование и пентест и др.), с которыми сталкиваются современные квалифицированные разработчики.

Репозиторий изначально создавался для личных нужд, но, возможно, будет полезен широкому кругу специалистов.

> Примечание: Большая часть материалов касается работы на ОС стека Linux и MacOS, поскольку автору они ближе, чем остальные.

В репозитории я постарался собрать максимальное количество ссылок на полезные ресурсы по интересующим меня темам, не вдаваясь в длинные описания технологии и холивары по поводу их использования.

Книги и мануалы по некоторым технологиям для удобства выложены в отдельный репозиторий:

> https://github.com/bormaxi8080/programming-books

Благодарности и обратная связь:

> Обо всех пожеланиях по поводу содержимого данного репозитория и найденных ошибках можно сообщить в комментариях или в Telegram: @bormaxi
> 
> Донаты в благодарность принимаются на карту Tinkoff: 5536 9138 6607 4988
или на Etherium: 0xe29685d6f0032bccac08b0e745a1a69ef9803973

## Содержание:

- [Основные понятия и концепции](#основные-понятия-и-концепции)
- [Операционные системы](#операционные-системы)
- [Виртуальные машины](#виртуальные-машины)
- [Базы данных](#базы-данных)
- [Языки программирования](#языки-программирования)
- [Популярные IDE](#популярные-IDE)
- [Сервера приложений](#сервера-приложений)
- [Библиотеки и фреймворки](#бибилиотеки-и-фреймворки)
- [Облачные платформы](#облачные-платформы)
- UX, HTML, CSS, Bootstrap, Material UI и пр.
- [Полезные утилиты](#полезные-утилиты)
- [Интересные репозитории в Git](#интересные-репозитории-в-git)
- [Пентестинг, безопасность и защита](#пентестинг-безопасность-и-защита)
- [Разное](#разное)

# Основные понятия и концепции

### Основы работы в ОС семейства Linux. Shell и командная строка

### Advanced Bash Scripting Guide:

> https://www.opennet.ru/docs/RUS/bash_scripting_guide/

### ExplainShell - отличный сервис для проверки работы командной строки Linux:

> https://explainshell.com/

### Краткое руководство по Markdown:

> https://paulradzkov.com/2014/markdown_cheatsheet/

### Grip - утилита для автономного просмотра разметки MD:

> https://github.com/joeyespo/grip
> 
> Запуск: grip

# Операционные системы

### MacOS
### Ubuntu
### Debian
### Kali Linux

# Виртуальные машины

### VirtualBox
### Parallels Desktop

# Базы данных

### Теория и основные концепции работы с БД
### MySQL
### PostrgeSQL
### SQLite
### MongoDB

# Языки программирования

### JavaScript
### C++
### Java
### Python
### GoLang
### Ruby, RubyOnRails

### Perl

> Perl plugin для IntelliJ Idea:
> 
> https://habr.com/ru/post/265799/
> 
> https://habr.com/ru/post/301910/

### Lua

# Популярные IDE

### Cемейство IDE от JetBrains 
### Eclipse IDE

# Сервера приложений

### Node.js
### Redis

# Библиотеки и фреймворки

### Backend

### Docker

> Официальная документация: https://docs.docker.com/
> 
> Старт: https://tproger.ru/translations/how-to-start-using-docker/
> 
> Полное практическое руководство на русском: https://habr.com/ru/post/310460/

### Серверное программирование web-сайтов - официальные рекомендации от Mozilla:

> https://developer.mozilla.org/ru/docs/Learn/Server-side

### Frontend
    ### HTML
    ### CSS
    ###ootstrap, верстка 
    ### React

### Lear React.js - Полное руководство:

> https://learn-reactjs.ru/home

# Полезные утилиты

### Chipmunk - утилита для работы с большими логами:

> GitHub:
> 
> https://github.com/esrlabs/chipmunk
> 
> Описание на Habr:
> 
> https://habr.com/ru/post/496126/

# Интересные репозитории в Git

# Пентестинг, безопасность и защита

### "Mac на службе у хакера" - хорошая подборка статей для начинающих пентестеров.

> Часть 1 - Шифрование диска: https://www.securitylab.ru/analytics/491107.php
>
> Часть 2 - Создание образа шифрованного диска: https://www.securitylab.ru/analytics/491268.php
>
> Часть 3 - Управление паролями: https://www.securitylab.ru/analytics/491893.php
>
> Часть 4 - Установка iTerm2: https://www.securitylab.ru/analytics/492394.php
>
> Часть 5 - Использование Git: https://www.securitylab.ru/analytics/492395.php
>
> Часть 6 - Настройка Homebrew: https://www.securitylab.ru/analytics/492845.php
>
> Часть 7 - Установка RVM для работы с Ruby: https://www.securitylab.ru/analytics/492846.php
>
> Часть 8 - Установка Kali Linux на виртуальной машине: https://www.securitylab.ru/analytics/492847.php
>
> Часть 9 - Установка Metaspoloit Framework: https://www.securitylab.ru/analytics/492848.php
>
> Часть 10 - Упорядочивание утилит: https://www.securitylab.ru/analytics/492935.php

### NMap

> https://nmap.org/npcap/guide/
>
> Сканирование через скрипты обнаружения уязвимостей:
> https://github.com/scipag/vulscan (nmap -sV --script vulners domain.com)
> 
> https://github.com/vulnersCom/nmap-vulners (nmap -sV --script=vulscan.nse domain.com)
> 
> Автоматизированный shell: https://github.com/bormaxi8080/nmap-scanner
> 
> Несколько интересных статей:
> https://habr.com/ru/post/88064/
> 
> https://losst.ru/kak-polzovatsya-nmap-dlya-skanirovaniya-seti
>
> https://antiddos.biz/kak-polzovatsya-nmap-dlya-poiska-uyazvimostej-servera/
> 
> Еще некоторые примеры: https://xakinfo.ru/os/nmap-anonymous/

### Metasploit Framework

> https://www.metasploit.com/
>
> Установка: https://github.com/rapid7/metasploit-framework/wiki/Nightly-Installers
>
> Обзоры:
> 
> https://habr.com/ru/company/varonis/blog/528578/
>
> https://vc.ru/life/136613-metasploit-framework-kratkoe-prakticheskoe-rukovodstvo
>
> Docs:
> 
> https://docs.rapid7.com/metasploit/
> 
> https://docs.rapid7.com/metasploit/quick-start-guide

### theHarvester:

> https://github.com/laramies/theHarvester

### hydra:

> https://null-byte.wonderhowto.com/how-to/hack-like-pro-crack-online-passwords-with-tamper-data-thc-hydra-0155374/

### Nikto (Nikto2):

> https://cirt.net/Nikto2

### WPScan - мощный фреймворк для пентеста WordPress:

> https://wpscan.com/wordpress-security-scanner
> 
> GitHub: https://github.com/wpscanteam/wpscan
>
> https://habr.com/ru/company/alexhost/blog/527612/

# Разное

### Менеджмент, управление, лидерство, корпоративная культура

Умные и честные заметки от Виталия Шароватова, вынесено в отдельный репозиторий, форк:

> https://github.com/bormaxi8080/teamlead

### Найм, HR и все, что с этим связано

Вынесено в отдельный репозиторий:

> https://github.com/bormaxi8080/bormaxi-about-hiring

