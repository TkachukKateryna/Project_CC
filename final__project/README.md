“Персональний помічник”ʼ 
(CC-assistant v0.0.1)


Встановлення

Щоб встановити програму потрібно відкрити теку CodeCrafters_assistant (якщо ви не змінювали назву після завантаження) або теку, де знаходиться установчий пакет (файл setup.py), запустити термінал у цій теці та у командному рядку ввести “ pip install . ” (без лапок)

Після завершення встановлення можна перевірити наявність встановленого пакету (CC-assistant) у списку.
Для цього ввести команду “ pip list” (без лапок)

Package         Version
--------------- -------
build           1.0.3
CC-assistant    0.0.1
pip             23.3.2
prompt          0.4.1
prompt-toolkit  3.0.43


 
Інструкція користувача для Персонального Помічника

Запуск бота

1.	В командному рядку ввести команду  start_assistant
2.	Оберіть бажану мову введення (0 - English, 1 - Українська).
3.	Оберіть функціонал за допомогою введення в консолі:
'0' - Менеджер контактів,
'1' - Менеджер нотаток,
'2' - Сортування файлів.

4.	Для виходу з програми напишіть команду “leave”


Менеджер контактів:

Для роботи з менеджером контактів доступні наступні команди:
 
- create - додає новий запис до книги контактів: можна додати ім'я, телефони, день народження, адресу та email одразу, а можна й пізніше
- check_birthdays - виводить список іменинників на обраний користувачем період
- edit - редагує ім'я/день народження/електронну пошту/адресу контакта
- edit_phone - редагує номер телефона контакта
- add_phone - додає новий номер телефону до контакта
- find - шукає введений текст у контактах
- remove - видаляє контакт
- remove_phone - видаляє один з номерів телефону обраного контакту
- show_all - виводить всі контакти, які є в книзі
- back - повернутися у головне меню
- leave - вийти з програми
- cancel - скасовує виконання поточної програми (наприклад: create/edit/sort_files) 

почніть вводити в командній строці команду і функція автозаповння запропонує обрати доступну з команд

Після обрання команди слідкуйте за підказками Помічника для коректного заповнення, збереження та відображення  введеної інформації

Менеджер нотаток:

Для роботи з менеджером нотатків доступні наступні команди:
 
- create - додає новий запис до книги нотаток: можна додати заголовок, текст та теги одразу, а можна й пізніше
- edit - редагує заголовок або текст нотатки
- edit_tags - редагує теги нотатка
- add_tag - додає новий тег до нотатки
- find - шукає введений текст у нотатках
- remove - видаляє нотатку
- remove_tag - видаляє один з тегів обраної нотатки
- back - повернутися у головне меню
- leave - вийти з програми
- cancel - скасовує виконання поточної програми (наприклад: create/edit/sort_files) 
 
почніть вводити в командній строці команду і функція автозаповння запропонує обрати доступну з команд

Після обрання команди слідкуйте за підказками Помічника для коректного заповнення, збереження та відображення  введеної інформації

Сортування файлів:

- sort_files - сортує усі файли за вказаним шляхом (включаючи усі папки та файли у них) та переміщує їх за введеною адресою
- back - повернутися у головне меню
- leave - вийти з програми
- cancel - скасовує виконання поточної програми (наприклад: create/edit/sort_files) 
 
почніть вводити в командній строці команду і функція автозаповння запропонує обрати доступну з команд

Після обрання команди слідкуйте за підказками Помічника для обрання відповідних тек для сортування та збереження відсортованих файлів

Сортування файлів відбуваеться за наступними типами даних: 
1. images - JPEG, JPG, PNG, SVG,
2. video - AVI, MP4, MOV, MKV, 
3. documents - DOC, DOCX, TXT, PDF, XLSX, PPTX,
4. audio - MP3, OGG, WAV, AMR,
5. archives - ZIP, GZ, TAR, RAR, 7Z
