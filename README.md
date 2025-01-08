<p align="center">
<img src="https://github.com/ikozhuhar/sysadmin_skills/blob/main/img/sysadmin_preview.png">
</p>

<p align="center">
<i>Отличному администратору не обязательно знать все, но он должен быть в состоянии придумать потрясающие решения для невозможных проектов.</i>
</p>

<p align="center" style="margin-top: 200px;">
<i>Этот проект содержит 284 тестовых вопроса и ответа, которые можно использовать в качестве проверки ваших знаний или во время собеседования/экзамена на ​​должность системного администратора Linux.</i>
</p>

<div style="padding: 100px;"></div>
<hr>

### Содержание`

| Уровни | Кол-во вопросов | Описание |
| ---------- | :---: | ----------- |
| [Junior Sysadmin](#1) | 65 вопросов | Достаточно просто и понятно, основано на базовых знаниях. |
| Middle Sysadmin | 94 вопросов | Средний уровень вопросов, если у вас есть глубокие знания. |
| Senior Sysadmin | 99 вопросов | Сложные вопросы и загадки. Проверьте это, если хотите быть хорошим. |

<hr>

### [:large_blue_diamond:](#toc) <a name='1'>Младший системный администратор</a>

###### Системные вопросы (37)

<details style="margin-bottom: 30px;">
   <p><summary><b>Приведите несколько примеров дистрибутива Linux.</b></summary></p>

   1. **Ubuntu** — один из самых популярных и дружелюбных для новичков дистрибутивов, основанный на Debian.
   2. **Debian** — стабильный и универсальный дистрибутив, который служит основой для многих других.
   3. **Fedora** — дистрибутив, ориентированный на использование новейших технологий с фокусом на разработчиков.
   4. **Arch Linux** — дистрибутив для опытных пользователей, предоставляющий полную свободу в настройке системы.
   5. **Linux Mint** — дистрибутив, ориентированный на пользователей, привыкших к Windows, с простым и понятным интерфейсом.

[Популярные дистрибутивы Linux](https://blog.skillfactory.ru/glossary/linux/)

</details>




<details>
   <p><summary><b>В чем разница между Unix, Linux, BSD и GNU?</b></summary></p>

<b>GNU</b> на самом деле не является ОС. Это скорее набор правил или философий, регулирующих свободное программное обеспечение, которые в то же время породили множество инструментов при попытке создать ОС. Таким образом, инструменты GNU — это, по сути, открытые версии инструментов, которые уже существовали, но были переопределены, чтобы соответствовать принципам открытого программного обеспечения. <i>GNU/Linux представляет собой совокупность этих инструментов и ядра Linux</i>, образующую полноценную операционную систему, но существуют и другие GNU, например. GNU/Hurd.

<b>Unix и BSD</b> — это «старые» реализации POSIX, которые имеют различные уровни «закрытого исходного кода». Unix обычно имеет полностью закрытый исходный код, но существует столько же разновидностей Unix, сколько и Linux (если не больше). BSD обычно не считается «открытой», но на момент выпуска она считалась очень открытой. Его лицензирование также позволяло коммерческое использование с гораздо меньшими ограничениями, чем допускали более «открытые» лицензии того времени.

<b>Linux</b> — новейший из четырех. Строго говоря, это «просто ядро»; однако в целом она рассматривается как полноценная операционная система в сочетании с GNU Tools и несколькими другими основными компонентами.

Главные руководящие различия между ними заключаются в их идеалах. Unix, Linux и BSD реализуют разные идеалы. Все они соответствуют POSIX и в основном взаимозаменяемы. Некоторые из одних и тех же проблем они решают по-разному. Таким образом, кроме идеалов и способа реализации стандартов POSIX, разницы мало.
</details>




<details>
   <p><summary><b>Что такое CLI? Расскажите мне о ваших любимых инструментах CLI, советах и ​​приемах.</b></summary></p>

   <b>CLI</b> — это аббревиатура от «Интерфейс командной строки» или «Интерпретатор командного языка». Командная строка — один из самых мощных способов управления вашей системой/компьютером.

   В Unix-подобных системах <b>CLI</b> — это интерфейс, с помощью которого пользователь может вводить команды для выполнения системой. Интерфейс командной строки очень мощный, но не очень устойчив к ошибкам.

   <b>CLI</b> позволяет вам гораздо более точно манипулировать внутренними компонентами вашей системы и кодом. Он предлагает большую гибкость и контроль, чем графический интерфейс, независимо от того, какая ОС используется. Многие программы, которые вы, возможно, захотите использовать в своем программном обеспечении, размещенном, например, на Github, также требуют запуска некоторых команд в <b>CLI</b>, чтобы запустить их.

   <b>Мои любимые инструменты</b>
   
   1. `screen` — бесплатный мультиплексор терминала, я могу начать сеанс, и мои терминалы будут сохранены, даже если соединение потеряно, поэтому вы можете возобновить его позже или из дома.
   2. `ssh` — самая ценная команда для изучения, я могу использовать ее для некоторых удивительных вещей.
   3. `vi/vim` — самый популярный и мощный текстовый редактор, он универсальный, работает очень быстро даже с большими файлами.
   4. `bash-completion` — содержит ряд предопределённых правил завершения для оболочки.  

   <b>Советы и хаки</b>

- `!*` - все аргументы последней команды
- `!!` - вся последняя команда
- `!ssh` - последняя команда, начинающаяся с ssh
</details>




<details>
<p><summary><b>Какая ваша любимая оболочка и почему?</b></summary></p>

Нет однозначного мнения о любимой оболочке для Linux. Несколько вариантов, которые мне известны:

- **Bash**. Самая распространённая оболочка Linux, установлена по умолчанию в большинстве систем. Поддерживает различные сокращения и переменные, операторы цикла, контроль и подстановку вывода результатов, автодополнение имён файлов и каталогов.
- **Zsh**. Более гибкая и настраиваемая оболочка, популярная среди продвинутых пользователей. Имеет большое количество встроенных функций и поддерживает широкий спектр плагинов и тем.
- **Fish**. Подходит тем, кому нужен интерактивный терминал без особых настроек. В этой оболочке легко добавлять, удалять и использовать псевдонимы команд, а также настраивать приглашение и цветовую схему. Выбор любимой оболочки зависит от личных предпочтений и потребностей пользователя.
</details>



<details>
<p><summary><b>Как получить справку в командной строке?</b></summary></p>

Чтобы получить справку в командной строке Linux, можно использовать следующие команды:

- **help**. Предоставляет информацию о встроенных командах оболочки. Синтаксис: `help [команда]`. Например, чтобы узнать о команде cd, нужно ввести: `help cd`.
- **man**. Это сокращение от «manual» (руководство). Базовый синтаксис: `man [команда]`. Например, чтобы узнать о команде ls, нужно написать: `man ls`.
- **info**. Служит для получения более детализированной информации о командах, особенно для программ GNU. Базовый синтаксис: `info [команда]`. Например, чтобы узнать о ls, нужно ввести: `info ls`.
</details>



<details>
<p><summary><b>Ваши первые 5 команд на сервере *nix после входа в систему</b></summary></p>

- `w` — много полезной информации о времени безотказной работы сервера
- `top` — можно увидеть все запущенные процессы, а затем отсортировать их по ЦП, использованию памяти и т. д.
- `netstat` — узнать, какой порт и IP-адрес прослушивает ваш сервер и какие процессы их используют
- `df` — сообщает об объеме доступного дискового пространства, используемого файловыми системами
- `history` — сообщает, что ранее было запущено пользователем, к которому вы подключены в данный момент
</details>



<details>
<p><summary><b>Что означают поля в выводе ls -la?</b></summary></p>

В порядке вывода:

```
-rwxrw-r--    1    root   root 2048    Jan 13 07:11 db.dump
```

- права доступа к файлу,
- количество ссылок,
- имя владельца,
- группа владельцев,
- размер файла,
- время последнего изменения,
- имя файла/каталога

Права доступа к файлам отображаются следующим образом:

первый символ `-` или `l` или `d`, `d` обозначает каталог, a `-` представляет файл, `l` - это символическая ссылка (или мягкая ссылка) - специальный тип файла

три набора символов, три раза, обозначающие разрешения для владельца, группы и других:

- `r` = чтение
- `w` = запись
- `x` = исполнение

В нашем примере -rwxrw-r-- это означает, что отображается следующая строка:

- обычный файл (отображается как `-`)
- доступен для чтения, записи и выполнения владельцем (`rwx`)
- доступен только для чтения и записи группой (`rw-`)
- доступен только для чтения другими (`r--`)
</details>




<details>
<p><summary><b>Как получить список вошедших в систему пользователей?</b></summary></p>

Для получения сводки о вошедших в систему пользователях, включая каждое имя пользователя, к которому подключены пользователи терминала, дату/время входа в систему и, возможно, компьютер, с которого они выполняют подключение, введите:

```
# Команда использует файлы /var/run/utmp и /var/log/wtmp для получения подробной информации.
who
```

Для получения подробной информации, включая имя пользователя, терминал, IP-номер исходного компьютера, время начала входа, время простоя, циклы ЦП процесса, циклы ЦП задания и текущую запущенную команду, введите:

```
# Команда использует /var/run/utmp и их процессы /proc.
w
```

Также важно для отображения списка последних вошедших в систему пользователей, введите:

```
# Команда использует /var/log/wtmp.
last
```

**Полезные ресурсы:** [4 способа определить, кто вошел в систему Linux](https://www.thegeekstuff.com/2009/03/4-ways-to-identify-who-is-logged-in-on-your-linux-system/)
</details>




<details>
<p><summary><b>В чем преимущество выполнения запущенных процессов в фоновом режиме? Как это можно сделать?</b></summary></p>

Самым значительным преимуществом выполнения запущенного процесса в фоновом режиме является то, что вы можете выполнять любую другую задачу одновременно, пока другие процессы работают в фоновом режиме. Таким образом, больше процессов могут быть завершены в фоновом режиме, пока вы работаете над другими процессами. Этого можно добиться, добавив специальный символ `&` в конце команды.

Обычно приложения, которые выполняются слишком долго и не требуют взаимодействия с пользователем, отправляются в фоновый режим, чтобы мы могли продолжить работу в терминале.

Например, если вы хотите загрузить что-то в фоновом режиме, вы можете:
```
wget https://url-to-download.com/download.tar.gz &
```

При запуске указанной выше команды вы получите следующий вывод:
```
[1] 2203
```

Здесь `1` — серийный номер задания, а `2203` — PID задания.

Вы можете увидеть задания, работающие в фоновом режиме, с помощью следующей команды:
```
jobs
```

При запуске задания в фоновом режиме выводится PID задания. Вы можете завершить задание, работающее в фоновом режиме, с помощью следующей команды:

```
kill PID
```

Замените PID на PID задания. Если у вас запущено только одно задание, вы можете перевести его на передний план с помощью:

```
fg
```

Если у вас запущено несколько задач в фоновом режиме, вы можете перевести любую задачу на передний план с помощью:

```
fg %#
```

Замените `#` на серийный номер задания.

**Полезные ресурсы:**
1. [Запустить процесс Unix в фоновом режиме](https://servicenow.iu.edu/kb?id=kb_article_view&sysparm_article=KB0026038)
2. [Каковы преимущества работы приложений в фоновом режиме?](https://unix.stackexchange.com/questions/162186/what-is-are-the-advantages-of-running-applications-in-backgound)


</details>




<details>
<p><summary><b></b></summary></p>
</details>




<details>
<p><summary><b></b></summary></p>
</details>




<details>
<p><summary><b></b></summary></p>
</details>




<details>
<p><summary><b></b></summary></p>
</details>




<details>
<p><summary><b></b></summary></p>
</details>




<details>
<p><summary><b></b></summary></p>
</details>




<details>
<p><summary><b></b></summary></p>
</details>




<details>
<p><summary><b></b></summary></p>
</details>




<details>
<p><summary><b></b></summary></p>
</details>




<details>
<p><summary><b></b></summary></p>
</details>




<details>
<p><summary><b></b></summary></p>
</details>




<details>
<p><summary><b></b></summary></p>
</details>




<details>
<p><summary><b></b></summary></p>
</details>




<details>
<p><summary><b></b></summary></p>
</details>




<details>
<p><summary><b></b></summary></p>
</details>




<details>
<p><summary><b></b></summary></p>
</details>




<details>
<p><summary><b></b></summary></p>
</details>




<details>
<p><summary><b></b></summary></p>
</details>

###### Вопросы по сетям (23)

https://github.com/trimstray/test-your-sysadmin-skills/tree/master
