# RegistrationNetology
Тестирование возможности записаться на обучение профессии «Тестировщик ПО» на сайте netology.ru
Что нужно сделать: нам нужен от вас план автоматизации тестирования сценария перехода к форме записи и заполнения этой формы.

## Перечень автоматизируемых сценариев.

### Переход к форме записи "Тестировщик ПО"
1. Через кнопку "Католог курсов" (шапка сайта). Открывается выпадающий список. Авторизованный/Неавторизованный пользователь.
    
    1.1. В поисковой строке вбиваем "Тестировщик ПО"/test enginer/QA Engineer/Тестиров.щик/тест.
    
    1.2  Нажимаем кнопку "Все курсы". В открывшемся окне выбираем "Тестировщик ПО"
    
    1.3  Нажимаем кнопку "Программирование". В открывшемся окне выбираем "Тестировщик ПО"
    
    1.4. Нажимаем кнопку "Бизнес и управление". В открывшемся окне поиска выбираем "Тестировщик ПО". Появляется сообщение "По этому запросу пока нет программ". Нажимаем кнопку "Перейти в каталог курсов" 
2. Через блоки "Направления обучения" (Авторизованный/Неавторизованный пользователь).
    
    2.1. Нажимаем блок "Программирование". В открывшемся окне выбираем "Тестировщик ПО"
    
    2.2  Нажимаем блок "355 курсов всех направлний". В открывшемся окне выбираем "Тестировщик ПО"
    
    2.3. Нажимаем блок "Дизайн и UX". В открывшемся окне выбираем "Тестировщик ПО". Появляется сообщение "По этому запросу пока нет программ". Нажимаем кнопку "Перейти в каталог курсов" 
3. В середине страницы сайта, в блоке "Выберите вектор развития" выбираем кликабельный текст "Выбрать курс". В поисковой строке вбиваем "Тестировщик ПО". Авторизованный/Неавторизованный пользователь.
4. Через футер сайта (Авторизованный/Неавторизованный пользователь).
    
    4.1. Выбираем в блоке "Обучение" кликабельный текст "Каталог курсов". В поисковой строке вбиваем "Тестировщик ПО". 
    
    4.2  Выбираем в блоке "Обучение" кликабельный текст "Популярные курсы". Выбираем блок "Тестировщик ПО".
    
    4.3  Выбираем в блоке "Обучение" кликабельный текст "Программирование". В поисковой строке вбиваем "Тестировщик ПО"либо выбираем 
    
    4.4  Выбираем в блоке "Обучение" кликабельный текст "Аналитика". В поисковой строке вбиваем "Тестировщик ПО". Появляется сообщение "По этому запросу пока нет программ". Нажимаем кнопку "Перейти в каталог курсов" 

### Заполнение формы записи на курс "Тестировщик ПО"

1. Авторизованный пользователь. Автоматическое заполнение полей формы данными пользователя. Наличие только двух полей - имя и телефон.
2. Авторизованный пользователь. Автоматическое заполнение полей формы данными пользователя. Возможность изменения данных в форме.
3. Неавторизованный пользователь. Наличие трех полей - имя, телефон и электронная почта.
4. Проверка поля "Имя"на валидные и невалидные значения.

   4.1. Ввод русских,латинский букв, цифр, символов

   4.2. Ввод одной буквы, тридцати букв, имени через дефис

5. Проверка поля "Телефон"на валидные и невалидные значения.

   5.1 Ввод русских,латинский букв, символов

   5.2 Ввод одной цифры, тридцати цифр, использование дефиса

   5.3. Ввод номера телеофна через 8-ку,+7 и использования кода другой страны

6. Проверка поля "Электронная почта"

   6.1 Ввод русских,латинский букв, символов, цифр

   6.2. Ввод почты без символов "." и "@"

7. Поступление заявки от пользователя в систему. Внесение информации в БД ,получение ответа от БД. Поступление сообщения пользователю о дальнейших шагах.


## Перечень используемых инструментов, выбранных с учетом использования на протяжении курса:

 - IDEA (среда разработчика)
 - Проект будет собран на базе Gradle с подключением библиотек Selenide (работа с веб формами) и Faker (генерация случайных данных для заполнения форм)
 - Postgresql для работы в БД (в случае получения доступа к тестовым базам)
 - Отчетность будет сформирована на основе Allure

## Перечень необходимых разрешений, данных и доступов:

- Разрешение на проведение автоматизированного тестирования
- Тестовые данные пользователя
- Тестовая версия приложения для проведения тестирования
- Симулятор для имитации работы с БД и предоставления ответа пользователю

## Перечень и описание возможных рисков при автоматизации:

- Не получения тестового приложения для тестирование
- Не возможность тестировать боевой сайт, так как тестовые запросы будут восприниматься как реальные заявки
- Потеря актуальности тестого приложения. Поддержка акктуального тестового приложения требует финансовых и ресурсных затрат. Соответственно сайт может поменяться, тесты на устарешем тестовом приложении автоматически становяться неактуальными.  

## Перечень необходимых специалистов для автоматизации:

- Продуктовый менеджер (для получения документации по продукту, требований, логики работы)
- Разработчик (для получения тестового приложения, симулятора, тестовых данных)
Интервальная оценка с учетом рисков в часах:

## Интервальная оценка с учётом рисков в часах.
- Получение тестового приложения, тестовых данных и согласование тест-кейсов от 2 дней до недели 
- 5 часа настройка проекта 
- 15 часа ручное тестирование + создание issue
- 15 часов создание основы проекта
- 15 часов написание автотестов
- 10 часов формирование отчетности по итогам автоматизации
- 10 часов формирование отчетности по итогам проекта

Вывод: для тестирования данного функционала вполне подойдет ручное тестирование. Либо можно скомбинировать - ручное для блока "Переход к форме записи "Тестировщик ПО"" и автоматизированное для тестирования формы "Заполнение формы записи на курс "Тестировщик ПО""
