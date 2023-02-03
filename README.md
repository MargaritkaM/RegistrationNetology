# RegistrationNetology
Тестирование возможности записаться на обучение профессии «Тестировщик ПО» на сайте netology.ru
Что нужно сделать: нам нужен от вас план автоматизации тестирования сценария перехода к форме записи и заполнения этой формы.

## Перечень автоматизируемых сценариев.

### Переход к форме записи "Тестировщик ПО". 

1. Через кнопку "Католог курсов" (шапка сайта). Открывается выпадающий список. Авторизованный/Неавторизованный пользователь.
    
    1.1. В поисковой строке вбиваем "Тестировщик ПО"/test enginer/QA Engineer/Тестировщик/тест.
    
    **Ожидаемый результат**: переход на страницу курса "Тестировщик ПО" https://netology.ru/programs/qa /поиск ничего не выдает/поиск ничего не выдает/поиск ничего не выдает/поиск ничего не выдает.
    
    1.2  Нажимаем кнопку "Все курсы". В открывшемся окне выбираем "Тестировщик ПО"
    
    **Ожидаемый результат**: переход на страницу курса "Тестировщик ПО" https://netology.ru/programs/qa
    
    1.3  Нажимаем кнопку "Программирование". В открывшемся окне выбираем "Тестировщик ПО"
    
    **Ожидаемый результат**: переход на страницу курса "Тестировщик ПО" https://netology.ru/programs/qa
    
    1.4. Нажимаем кнопку "Бизнес и управление". В открывшемся окне поиска выбираем "Тестировщик ПО". Появляется сообщение "По этому запросу пока нет программ". Нажимаем кнопку "Перейти в каталог курсов" 
    
    **Ожидаемый результат**: переход на страницу всех курсов https://netology.ru/navigation
    
2. Через блоки "Направления обучения" (Авторизованный/Неавторизованный пользователь).
    
    2.1. Нажимаем блок "Программирование". В открывшемся окне выбираем "Тестировщик ПО"
    
    **Ожидаемый результат**: переход на страницу курса "Тестировщик ПО" https://netology.ru/programs/qa
    
    2.2  Нажимаем блок "355 курсов всех направлний". В открывшемся окне выбираем "Тестировщик ПО"
    
    **Ожидаемый результат**: переход на страницу курса "Тестировщик ПО" https://netology.ru/programs/qa
    
    2.3. Нажимаем блок "Дизайн и UX". В открывшемся окне выбираем "Тестировщик ПО". Появляется сообщение "По этому запросу пока нет программ". Нажимаем кнопку "Перейти в каталог курсов" 
    
    **Ожидаемый результат**: переход на страницу всех курсов https://netology.ru/navigation
    
3. В середине страницы сайта, в блоке "Выберите вектор развития" выбираем кликабельный текст "Выбрать курс". В поисковой строке вбиваем "Тестировщик ПО". Авторизованный/Неавторизованный пользователь.

    **Ожидаемый результат**: переход на страницу курса "Тестировщик ПО" https://netology.ru/programs/qa

4. Через футер сайта (Авторизованный/Неавторизованный пользователь).
    
    4.1. Выбираем в блоке "Обучение" кликабельный текст "Каталог курсов". В поисковой строке вбиваем "Тестировщик ПО". 
    
    **Ожидаемый результат**: переход на страницу курса "Тестировщик ПО" https://netology.ru/programs/qa
    
    4.2  Выбираем в блоке "Обучение" кликабельный текст "Популярные курсы". Выбираем блок "Тестировщик ПО".
    
    **Ожидаемый результат**: переход на страницу курса "Тестировщик ПО" https://netology.ru/programs/qa
    
    4.3  Выбираем в блоке "Обучение" кликабельный текст "Программирование". В поисковой строке вбиваем "Тестировщик ПО"либо выбираем. 
    
    **Ожидаемый результат**: переход на страницу курса "Тестировщик ПО" https://netology.ru/programs/qa
    
    4.4  Выбираем в блоке "Обучение" кликабельный текст "Аналитика". В поисковой строке вбиваем "Тестировщик ПО". Появляется сообщение "По этому запросу пока нет программ". Нажимаем кнопку "Перейти в каталог курсов" 
    
    **Ожидаемый результат**: переход на страницу всех курсов https://netology.ru/navigation

### Заполнение формы записи на курс "Тестировщик ПО"

1. Авторизованный пользователь. Автоматическое заполнение полей формы данными пользователя. Наличие только двух полей - имя и телефон.

    **Ожидаемый результат**: поля заполнены данными авторизованного пользователя

2. Авторизованный пользователь. Автоматическое заполнение полей формы данными пользователя. Возможность изменения данных в форме.

    **Ожидаемый результат**: данные в полях меняются 

3. Неавторизованный пользователь. Наличие трех полей - имя, телефон и электронная почта.

    **Ожидаемый результат**: три поля доступня для заполнения

4. Проверка поля "Имя"на валидные и невалидные значения.

   4.1. Ввод русских,латинский букв, цифр, символов
   
   **Ожидаемый результат**: поле принимает только русские и латинские буквы, в остальных случаях возникает ошибка

   4.2. Ввод одной буквы, тридцати букв, имени через дефис
   
   **Ожидаемый результат**: поле принимает значения, ошибки не возникает

5. Проверка поля "Телефон"на валидные и невалидные значения.

   5.1 Ввод русских,латинский букв, символов
   
   **Ожидаемый результат**: возникает ошибка "Номер в формате +9 (999) 999-99-99"

   5.2 Ввод одной цифры, тридцати цифр, использование дефиса
   
   **Ожидаемый результат**: возникает ошибка "Номер в формате +9 (999) 999-99-99"

   5.3. Ввод номера телеофна через 8-ку,+7 и использования кода другой страны
   
   **Ожидаемый результат**: ошибки не возникает

6. Проверка поля "Электронная почта"

   6.1 Ввод русских,латинский букв, символов, цифр
   
   **Ожидаемый результат**: значение вводятся в поле, но если вводить только русские,латинские буквы, символы, цифры возникает ошибка "Неверный email"

   6.2. Ввод почты без символов "." и "@"

   **Ожидаемый результат**: возникает ошибка "Неверный email"

7. Поступление заявки от пользователя в систему. Внесение информации в БД ,получение ответа от БД. Поступление сообщения пользователю о дальнейших шагах.

   **Ожидаемый результат**: клиент получает уведомление по почте о дальнейших шагах. Данные о клиенте поступают в БД на обработку, далее с клиентом связываются по указанному номеру телефона. 

## Перечень используемых инструментов, выбранных с учетом использования на протяжении курса:

 - IDEA (среда разработчика);
 - Язык программирования Java: OpenJDK 11; 
 - Проект будет собран на базе Gradle с подключением библиотек Selenide (работа с веб формами),Faker (генерация случайных данных для заполнения форм) и Lombok для генерации кода;
 - Фреймворк JUnit 5, как один из самых популярных проектов для автоматического тестирования;
 - Postgresql для работы в БД (в случае получения доступа к тестовым базам);
 - Отчетность будет сформирована на основе Allure.

## Перечень необходимых разрешений, данных и доступов:

- Разрешение на проведение автоматизированного тестирования
- Тестовые данные пользователя
- Тестовая версия приложения для проведения тестирования
- Симулятор для имитации работы с БД и предоставления ответа пользователю

## Перечень и описание возможных рисков при автоматизации:

- Не получение тестового приложения для тестирование
- Не возможность тестировать боевой сайт, так как тестовые запросы будут восприниматься как реальные заявки
- Потеря актуальности тестого приложения. Поддержка акктуального тестового приложения требует финансовых и ресурсных затрат. Соответственно сайт может поменяться, тесты на устарешем тестовом приложении автоматически становяться неактуальными
- Различные, сложные пути проверки для блока ""Переход к форме записи "Тестировщик ПО"", так как задействует различные функциональные части сайта (поиск, переход между страницами, работа с различными кликабельными блоками сайта и т.д. )


## Перечень необходимых специалистов для автоматизации:

- Автотестировщик (для написания кода тестов)
- Продуктовый менеджер (для получения документации по продукту, требований, логики работы)


## Интервальная оценка с учётом рисков в часах.
- Получение тестового приложения, тестовых данных и согласование тест-кейсов от 2 дней до недели 
- 5 часа настройка проекта 
- 15 часа ручное тестирование + создание issue
- 15 часов создание основы проекта
- 15 часов написание автотестов
- 10 часов формирование отчетности по итогам автоматизации
- 10 часов формирование отчетности по итогам проекта

Вывод: для тестирования данного функционала вполне подойдет ручное тестирование. Либо можно скомбинировать - ручное для блока "Переход к форме записи "Тестировщик ПО"" и автоматизированное для тестирования формы "Заполнение формы записи на курс "Тестировщик ПО""
