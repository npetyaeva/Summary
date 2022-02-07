### Модуль «Автоматизированное тестирование»

# План автоматизации тестирования 

Необходимо составить план автоматизации тестирования сценария перехода к форме записи и заполнения этой формы на обучение профессии "Тестировщик ПО" на сайте [Нетологии](https://netology.ru/programs/qa#/order)
1. **Переход к форме записи.** Попасть на форму записи со страницы профессии можно тремя способами – пролистать всю странцу профессии до формы записи, а также нажатием одной из двух кнопок "Записаться" на странице профессии. Попасть на страницу профессии с главной страницы сайта можно как через меню "Каталог курсов", так и через некоторый контент на главной странице.
2. **Тестирование заполнения формы записи** (без отправки).

##1. Перечень автоматизируемых сценариев
###1.1. Тестирование открытия страницы профессии "Тестировщик ПО" на сайте Нетологии
####1.1.1. Через "Каталог курсов"
Сценарий №01 
1. Перейти на главную страницу [Нетологии](https://netology.ru/)
2. Найти и кликнуть на кнопку "Каталог курсов"
3. В боковом меню указать мышкой (не кликать) на пункт "Программирование" 
4. В появившемся перечне курсов выбрать и кликнуть на пункт "Тестировщик ПО", убедиться, что открывается страница программы курса "Тестировщик ПО"

Сценарий №02 
1. Перейти на главную страницу [Нетологии](https://netology.ru/)
2. Найти и кликнуть на кнопку "Каталог курсов"
3. В боковом меню кликнуть на пункт "Программирование", убедиться что открывается страница "Программирвание" с перечнем курсов
4. Найти вкладку "Тестировщик ПО" и кликнуть по ней, убедиться, что открывается страница программы курса "Тестировщик ПО"

Сценарий №03
1. Перейти на главную страницу [Нетологии](https://netology.ru/)
2. Найти и кликнуть на кнопку "Каталог курсов"
3. В боковом меню кликнуть на пункт "Полный каталог", убедиться что открывается страница с перечнем курсов
4. В поле поиска ввести "Тест"
5. Найти вкладку "Тестировщик ПО" и кликнуть по ней, убедиться, что открывается страница программы курса "Тестировщик ПО"

Сценарий №04
1. Перейти на главную страницу [Нетологии](https://netology.ru/)
2. Найти и кликнуть на кнопку "Каталог курсов"
3. В боковом меню кликнуть на пункт "Полный каталог", убедиться что открывается страница с перечнем курсов
4. В фильтре "Направление" выбрать пункт "Программирование"
5. Найти вкладку "Тестировщик ПО" и кликнуть по ней, убедиться, что открывается страница программы курса "Тестировщик ПО"

####1.1.2. Через вкладку "НЕО для начинающих"
Сценарий №05
1. Перейти на главную страницу [Нетологии](https://netology.ru/)
2. Найти и кликнуть на вкладку "НЕО для начинающих", убедиться, что открывается страница "Лучшие курсы для старта" с перечнем курсов
3. В появившемся перечне курсов найти и кликнуть по вкладке "Тестировщик ПО", убедиться, что открывается страница программы курса "Тестировщик ПО"

####1.1.3. Через блок "Изучайте актуальные темы"
Сценарий №06
1. Перейти на главную страницу [Нетологии](https://netology.ru/)
2. В блоке "Изучайте актуальные темы" найти и кликнуть по вкладке "Программирование", убедиться, что открывается страница "Программирвание" с перечнем курсов
3. В появившемся перечне курсов найти и кликнуть по вкладке "Тестировщик ПО", убедиться, что открывается страница программы курса "Тестировщик ПО"

###1.2. Тестирование перехода к форме записи на странице курса "Тестировщик ПО"
Сценарий №07
1. Перейти на [страницу профессии "Тестировщие ПО"](https://netology.ru/programs/qa)
2. Проскролить всю страницу до формы записи.

Сценарий №08
1. Перейти на [страницу профессии "Тестировщие ПО"](https://netology.ru/programs/qa)
2. Найти и нажать на кнопку "Записаться" в начале страницы, убедиться, что осуществлен переход на форму записи в конце текущей страницы

Сценарий №09
1. Перейти на [страницу профессии "Тестировщие ПО"](https://netology.ru/programs/qa)
2. Проскролить страницу до блока "Гарантия возврата денег"
3. Нажать на кнопку "Записаться" в этом блоке, убедиться, что появляется всплывающее окно с формой записи

###1.3. Тестирование заполнения формы записи (без отправки)
Сценарий №10
1. Перейти на [страницу профессии "Тестировщие ПО"](https://netology.ru/programs/qa)
2. Найти и нажать на кнопку "Записаться", убедиться, что осуществлен переход на форму записи в конце текущей страницы
3. Заполнить поле ввода "Имя" следующими данными (поля "Телефон", "Email" заполнены валидными данными (9775555555/test@netology.ru)):
   - Ввести валидное имя (Анна) 
   - Оставить поле пустым
   - Ввести пробел
   - Ввести значение состоящее из цифр и/или символов (Ник2022)
   - Ввести имя, состоящее из одной буквы ("А")
   - Ввести имя, состоящее из нескольких слов через пробел (Анна Мария)
   - Ввести имя, состоящее из нескольких слов через дефис (Анна-Мария)
   - Ввести имя с пробелами в начале и в конце ( Анна )
4. Заполнить поле ввода "Телефон" следующими данными (поля "Имя", "Email" заполнены валидными данными (Анна/test@netology.ru)):
   - Ввести валидный номер телефона без кода строны  (9775555555)
   - Ввести валидный номер телефона с кодом страны (+79775555555)
   - Ввести валидный номер телефона с разделителями "-" и/или " " (977 555-55-55)
   - Оставить поле пустым
   - Ввести пробел
   - Ввести значение состоящее из символов и/или цифр (977ооо2022)
   - Ввести номер телефона, состоящий из 7 цифр (5555555)
   - Ввести номер телефона, состоящий из 12 цифр (977555555555)
5. Заполнить поле ввода "Email" следующими данными (поля "Имя", "Телефон" заполнены валидными данными (Анна/9775555555)):
   - Ввести валидный email (test@netology.ru)
   - Оставить поле пустым
   - Ввести пробел
   - Ввести email без "@" (testnetology.ru)
   - Ввести email без "." (test@netologyru)
   - Ввести email с пробелами (test @ netology.ru)
   - Ввести email без имени почтового ящика (@netology.ru)
   - Ввести email без доменного имени (test@)

##2. Перечень используемых инструментов с обоснованием выбора
1. Java11 – универсальный язык программирования. Популярен для написания автотестов, по этой причине разнообразие фреймворков, библиотек, существует большое количество вспомогательной информации/примеров, развито комьюнити
2. IntelliJ IDEА – среда разработки для Java, присутствует интеграция с полезными инструментами (Git, GitHub), широкая поддержка расширений и плагинов для тестирования
3. Gradle – система автоматической сборки, которую используют для упрощения работы с Java. Берет на себя упраление зависимостями, компилирование/тестирование/генерирование документации, сборка исполняемых файлов
4. JUnit5 – фреймворк для тестирования, совместимый с IntelliJ IDEA, содержит аннотации для написания тестов
5. Lombok – библиотека, помогающая сократить стандартный код, заменяя повторяющиеся фрагменты кода (getter'ы, setter'ы) аннотациями
6. JavaFaker – библиотека для создания тестовых данных. При помощи Faker можем сгенерировать необходимые данные - Имя, Телефон, Email
7. Selenide – фреймворк для автоматизированного тестирования веб-приложений на основе Selenium WebDriver
8. Allure Report – фреймворк для сбора данных и построения отчетов о тестировании кода
9. Git – система контроля версий, хорошая интеграция с IntelliJ IDEA
10. GitHub – cайт-хранилище для историй версий проектов

##3. Перечень необходимых разрешений/данных/доступов
Задача тестирования отправки формы не поставлена, по этой причине не потребуется разрешение на тестирование сайта [Нетологии](https://netology.ru/).
Так же не нужно разрешение на доступ к БД пользователей, тестовые данные генерируются через JavaFaker

##4. Перечень и описание возможных рисков при автоматизации
1. Изменение структуры сайта (DOM)
2. Изменения CSS-свойств, классов и атрибутов
3. Актуальность информации на сайте
4. Поддержка автотестов

##5. Перечень необходимых специалистов для автоматизации
Один специалист по автоматизированному тестированию

##6. Интервальная оценка с учётом рисков (в часах)
1. Написание тест-кейсов: 0.5 - 1 час на каждый
2. Написание автотестов и прогон - 1-2 часа на каждый
3. Форсмажорные ситуации - 4 часа
