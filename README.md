# Робота з датами. Бібліотека moment.js

moment.js - бібліотека, яка надає нам більше опцій для праці з часом. Такі як: більш зручний та вдосконаленний дисплей, додавання або віднімання, парсинг дат та ін. Мета цієї лекції - росказати про базові та необхідні функції для затосування цієї бібліотеки.

## Найголовні риси бібліотеки

### 1. Парсинг дат. 

Бібліотека дозволяє вам парсити дати у стрінг, обжект та у массиві. Також дозволяе клонувати момент часу, або вивести дату в UTC форматі. Також є цілий метод для затвердження дат та перевірку їх коректності.

### 2. Маніпуляція датами

Додавання, віднімання, початок та кінець відліку, отримати момент у певній часовій зоні та ін. Також існує безліч методів для отримання більш детальної інформації про дату.

### 3. Задавання дат

Присутне більше кастомізації при задаванні дат. Можна окремо редактувати годину, хвилину, секунду, мілісекунду, місяць, день тижня та інші індивідуальні аспекти.

### 4. Кастомізація

При задаванні свого локального часу - ви вільні змінювати усе, починаючи від назви місяців закінчуючи календарною структурою. Також присутня повна підтримка безлічі плагінів для кращого особистого використання. 

## Установка бібліотеки

### Для NodeJS

* Установка буде проходити через npm, завдяки команді `npm install moment`. Переконайтеся що у вас вже установленні NodeJS та NPM. Скачати їх можна за [посиланням](https://nodejs.org/uk/download/). 

![Процесс установки](/src/screen2.jpg)

* Для перевірки працездатності - створюємо файл test.js, та вводимо в нього наступний код:

`var moment = require('moment');`

`var a = moment().toString();`

`console.log(a);`

![Приклад](/src/screen1.jpg)

* Зберігаємо файл. Відкриваємо консоль та пишемо: `node C\...` та шлях до файлу test.js. При виконанні файла ми маємо отримати нинішню актуальну дату та час.

![Результат](/src/screen3.jpg)

## Лекція створена Щоткіним Максимом з ІВ-91

## Контакти:

Телеграм - @SmakLagidze

Телефон - +(380) 98 30 15 126

Поштова скринька - maksym.shchotkin@gmail.com








