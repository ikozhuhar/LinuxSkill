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
   <p><summary><b>Приведите несколько примеров дистрибутива Linux. Какой ваш любимый дистрибутив и почему?</b></summary></p>

   1. **Ubuntu** — один из самых популярных и дружелюбных для новичков дистрибутивов, основанный на Debian.
   2. **Debian** — стабильный и универсальный дистрибутив, который служит основой для многих других.
   3. **Fedora** — дистрибутив, ориентированный на использование новейших технологий с фокусом на разработчиков.
   4. **Arch Linux** — дистрибутив для опытных пользователей, предоставляющий полную свободу в настройке системы.
   5. **Linux Mint** — дистрибутив, ориентированный на пользователей, привыкших к Windows, с простым и понятным интерфейсом.

[Популярные дистрибутивы Linux](https://blog.skillfactory.ru/glossary/linux/)

</details>




<details>
   <p><summary><b>В чем разница между Unix, Linux, BSD и GNU?</b></summary></p>

<p><b>GNU</b> на самом деле не является ОС. Это скорее набор правил или философий, регулирующих свободное программное обеспечение, которые в то же время породили множество инструментов при попытке создать ОС. Таким образом, инструменты GNU — это, по сути, открытые версии инструментов, которые уже существовали, но были переопределены, чтобы соответствовать принципам открытого программного обеспечения. <i>GNU/Linux представляет собой совокупность этих инструментов и ядра Linux</i>, образующую полноценную операционную систему, но существуют и другие GNU, например. GNU/Hurd.</p>

<p><b>Unix и BSD</b> — это «старые» реализации POSIX, которые имеют различные уровни «закрытого исходного кода». Unix обычно имеет полностью закрытый исходный код, но существует столько же разновидностей Unix, сколько и Linux (если не больше). BSD обычно не считается «открытой», но на момент выпуска она считалась очень открытой. Его лицензирование также позволяло коммерческое использование с гораздо меньшими ограничениями, чем допускали более «открытые» лицензии того времени.</p>

<p><b>Linux</b> — новейший из четырех. Строго говоря, это «просто ядро»; однако в целом она рассматривается как полноценная операционная система в сочетании с GNU Tools и несколькими другими основными компонентами.</p>

<p>Главные руководящие различия между ними заключаются в их идеалах. Unix, Linux и BSD реализуют разные идеалы. Все они соответствуют POSIX и в основном взаимозаменяемы. Некоторые из одних и тех же проблем они решают по-разному. Таким образом, кроме идеалов и способа реализации стандартов POSIX, разницы мало.</p>
</details>




<details>
   <p><summary><b>Что такое CLI? Расскажите мне о ваших любимых инструментах CLI, советах и ​​приемах.</b></summary></p>

   <p><b>CLI</b> — это аббревиатура от «Интерфейс командной строки» или «Интерпретатор командного языка». Командная строка — один из самых мощных способов управления вашей системой/компьютером.</p>

   <p>В Unix-подобных системах <b>CLI</b> — это интерфейс, с помощью которого пользователь может вводить команды для выполнения системой. Интерфейс командной строки очень мощный, но не очень устойчив к ошибкам.v

   <p><b>CLI</b> позволяет вам гораздо более точно манипулировать внутренними компонентами вашей системы и кодом. Он предлагает большую гибкость и контроль, чем графический интерфейс, независимо от того, какая ОС используется. Многие программы, которые вы, возможно, захотите использовать в своем программном обеспечении, размещенном, например, на Github, также требуют запуска некоторых команд в <b>CLI</b>, чтобы запустить их.</p>

   <p><b>Мои любимые инструменты</b></p>
   1. `screen` — бесплатный мультиплексор терминала, я могу начать сеанс, и мои терминалы будут сохранены, даже если соединение потеряно, поэтому вы можете возобновить его позже или из дома. 
   
   `ssh` — самая ценная команда для изучения, я могу использовать ее для некоторых удивительных вещей.  
   
   vi/vim — самый популярный и мощный текстовый редактор, он универсальный, работает очень быстро даже с большими файлами.  
   
   bash-completion — содержит ряд предопределённых правил завершения для оболочки.  

   <p><b>Советы и хаки</b></p>
</details>





###### Вопросы по сетям (23)

https://github.com/trimstray/test-your-sysadmin-skills/tree/master
