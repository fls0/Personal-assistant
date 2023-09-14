# PythonWizards
Group-12 team project "Personal_assistant"

Зміст:
1.Інструкція встановлення пакету
2.Інструкція користання записною книжкою
3.Інструкція користання нотатником
4.Інструкція користання мапою
5.Інструкція користання сортуванням
6.Гра

1.Інструкція встановлення:
Відкрити командну строку та перейти в дерикторію з застосунком, вписати комманди:
pip install -r requirements (встановлює всі нетсандартні бібліоткеи що були використані в коді)
pip install -e . (встановлює як пакет)
pers запускає

pip uninstall Personal_assistant (видаляє пакет)
pip uninstall -r requirements (видаляє нетсандартні бібліоткеи що були використані в коді)

------------------------------------------------------------------------------------------------------------------------------------------------------

2.Інструкція до застосунку "Записна книжка"
До записної книжки можна додавляти контакти, їх ім'я, номер, дату народження, емейл-адрессу та жилу адрессу.
Застосунок допомогає тримати всю цю інформацію в одному місці та при необхідності легко отримати те, що потребує користувач.
Застосунок автоматично зберігає усю інформацію на диск, запобігаючи видаленню інформації при помилці чи непередбачуванному замиканню застосунку.

Основні команди застосунку це: 'hello', 'add', 'change', 'delete', 'search', 'birthday', 'show all', 'good bye', 'close', 'exit'.
Де: hello - привітатися з ассистентом,
    add - додавання нового контакту до записної книжки,
    change - редагування вже створеного контакту,
    delete - видалення контакту з записної книжки,
    search - пошук контакту в записній книжці,
    birthday - вивід на екран контактів, які мають день народження через задану кількість днів,
    show all - виводить на екран усі збережені контакти,
    good bye, close, exit - вихід.

Інструкція користання командами:
add - поетапний ввід данних(імя, номер, день народження, Еmail, адресса).
change - поетапна зміна всього запису(Обовязково імя існуючого контакту, інше можна зміняти для поточного контакту)
Видалення контакту - команда "delete Name", де Name - це імя контакта.
Пошук контакту - команда "search Contact", де Contact - це імя контакта.
Дні народження - команда "birthday 7", де 7(може бути довільним) - це діапазон днів на перед, в яких може бути день народження.

------------------------------------------------------------------------------------------------------------------------------------------------------

3.Інструкція до застосунку "Нотатки"
Застосунок призначено для ведення нотаток у вільній формі.
Кожна нотатка має:
- заголовок
- текст
- теги (може бути декілька)
- дату створення
Застосунок зберігає усі дані на диск та відтворює з диска при старті.
Збереження на диск відбувається при кожній зміні нотаток (додаванні, редагуванні, видалені).
Команди застосунку:
- Add a Note - додати нотатку
- Edit a Note - редагувати нотатку
- Delete a Note - видалити нотатку
- Search by Tag - пошук нотатки за тегом (ключовим словом)
- Search by Content - пошук нотатки за контентом
- Sort - сортування нотаток
    - Sort by tags - сортування за тегами (ключовими словми)
    - Sort by name - сортування за заголовком
    - Sort by date - сортування за датою створення
- Delete a Note - видалення нотатки
- Display Notes - виводить всі нотатки на екран
- Exit - завершує роботу застосунку.
Інструкція користувача.
Після старту застосунок пропонує ввести команду.
Починайте вводити потрібну команду, застосунок підкаже варіанти. Виберіть із запропонованих варіантів та натисніть Enter.
- Add a Note: для додавання нотатки необхідно послідовно ввести її заголовок (або відмовитись та повернутись в головне меню),
текст та теги (ключові слова), яких може бути декілька (через кому) або не бути взагалі.
- Display Notes: перегляд усіх нотаток, що нумеруються для виконання наступних дій
- Edit a Note: для редагування необхідно вибрати нотатку за її номером (див.Display Notes), після чого програма буде показувати 
і пропонувати ввести нове значення послідовно для заголовку, контенту та тегів нотатки. Щоб залишити старий вміст
будь якого з полів натискайте Enter.
- Delete a Note: для видалення необхідно вибрати нотатку за її номером (див.Display Notes), після чого програма покаже
повний вміст нотатки і перепитає, чи підтверджуєте ви видалення. При підтвердженні нотатка видаляється.
- Search by Tag: програма пропонує ввести тег для пошуку, результат пошуку виводиться на екран (тег треба вносити слово цілком).
- Search by Content: програма пропонує ввести ключ для пошуку, результат пошуку виводиться на екран (ключ може бути частиною слова з контенту).
- Sort: виводить на екран підменю сортування на вибір за тегами, заголовками чи датами створення. Результати сортувань виводяться на екран.
- Exit: виберіть для завершення роботи програми. 

------------------------------------------------------------------------------------------------------------------------------------------------------

4.Інструкція до застосунку "Мапа"
Застосунок створений для візуалізації та пошуку координат на картах. Основною 
функцією є виведення інтерактивної мапи з прапорцями раніше збережених 
координат.
Є три основних видів мап:
-Мапа ядерних об’єктів країни 404
-Мапа  аеропортів країни 404
-Мапа  адміністративних об’єктів країни 404
Також реалізоване збереження координат у відповідних файлах, за потреби 
користувач може отримати географічні координати за назвою міста.
Застосунок автоматично зберігає усю інформацію , запобігаючи видаленню інформації 
при помилці чи непередбачуваному замиканню застосунку.
Основні команди застосунку це: 'save_nuclear', 'add_nuclear', 'save_air', 'save_admin', 
'add_admin', 'coordinates', 'good bye', 'close', 'exit'.
Де: 
   'save_nuclear'             -Зберегти карту ядерних обєктів країни 404 
   'add_nuclear'              -Додати кординати до файлу з ядерними обєктами 
   'save_air'                 -Зберегти карту аеропортів країни 404 
   'add_air'                  -Додати кординати до файлу з аеропортами 
   'save_admin'               -Зберегти карту адміністративних обєктів країни 404 
   'add_admin'                -Додати кординати до файлу з ядерними обєктами 
   'coordinates'              -Отримати координати за назвою міста
   'good bye','close','exit ' -ихід.
 
Інструкція користання командами:
save – усі команди з таким префіксом зберігають карту з нанесеними мітками 
координат з відповідних текстових файлів у форматі html ( Наприклад: команда 
'save_nuclear'  збрігає карту з назвою 'russia_map_nuclear.html' з координатами, що 
вказані у файлі 'coordinates_nuclear.txt').
add – усі команди з префіксом «add» додають кординати у текстові відповідні текстові 
файли ( Наприклад: команда 'add_air'  додає до файлу 'coordinates_air.txt'  координати,
що вніс користувач).                     
сoordinates -  команда здійснює пошук координат по назві міста, за допомогою 
застосунку OpenCage Geocoder з використанням geocoding API key.           

------------------------------------------------------------------------------------------------------------------------------------------------------

5.Інструкція сортування:
Для сортування файлів по папкам, потрібно вказати шлях до папки, в форматі "С:/name/of/your/path" код автоматично перебере всі файли, та відсортує по папкам фото, відео, документи, музику, архіви та пайтон файли. Після сортування, в термінал будуть виведені всі відомі розширення що були знайдені в папці, та невідомі.

------------------------------------------------------------------------------------------------------------------------------------------------------

6.Інструкція до застосунку "Бандеро гусак у Моцкві"
Основною метою застосунку є -  розважальна. 
У грі є три основних об’єкти: гравець, бонуси та вороги. Гравець,  у нашому випадку 
це гусак, повинен зібрати якомога більше бонусів, при цьому ухилятись від ракет. Гра 
завершується, при потраплянні ракети у гусака.
Керування гусаком відбувається за допомогою клавіш навігації зі стрілками.