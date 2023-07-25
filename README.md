# План Автоматизации сценария записи на обучение профессии"Тестировщик ПО" на сайте Нетология (http://netology.ru).

## 1. Перечень автоматизируемых сценариев.
                       1
* Нажать на главной странице в хедере выподашку "Каталог курсов".
* Нажать раздел программирование.
* Нажать курс "Тестировщик ПО".
* Нажать кнопку "Записаться".

                     2
* На главной странице в разделе "Напровления обучения" нажать "Программирование".
* Нажать курс "Тестировщик ПО".
* Нажать кнопку "Записаться".

                     3
* На главной странице в разделе "Направления обучения" нажать "Программирование".
* В поле поиска "Какой курс вам нужен?" ввести Тестировщик ПО.
* выбрать в появившихся курсах "Тестеровщик ПО".
* Нажать кнопку "записаться".

                     4
* На гдавной странице в разделе "Направления обучения" нажать "Полный каталог".
* Выбрать курс "Тестировщик ПО".
* Нажать кнопку "Записаться".

## 2. Перечень используемых инструментов с обоснованием выбора.
1. Java 11 - язык программирования используется большинством, удобен в написании автотестов.
2. Selenide - это обёртка вокруг Selenium WebDriver, позволяющая быстро и просто его использовать
при написании тестов, сосредоточившись на логике, а не суете с браузером, автоматически решение
проблем с Ajax, ожиданием и таймаутами.
3. Gradle - мощная и простая система автоматической сборки проектов, которая используется
для упрощения работы с Java.
4. Faker - библиотека, которая позволяет генерировать данные. С ее помощью можно заполнить
таблицы в базе данных, построить корректные XML-документы, сформировать JSON-ответы для REST.
5. Docker - это программная платформа для разработки, доставки и запуска контейнерных приложений.
Он позволяет создавать контейнеры и автоматизировать их запуск.
6. Intellij IDEA - интегрированная среда разработки ПО для многих языков программирования.
7. Allure Report- автоматизирует сортировку тестов на баги, дефекты и сломанные тесты
и отображает результат в TMS, багтрекере или в web-отчете. 

## 3. Перечень необходимых разрешений, данных и доступов.
1. Разрешение на автотестирование сайта Нетология.
2. Данные для доступа к базе данных и API.
3. Требования ПО на функцию записи на курсы.

## 4. Перечень и описание возможных рисков при автоматизации.
1. Слишком затратно по ресурсам, возможно проще проверить вручную.
2. Возможно засорение базы данных.
3. При автотестах не отображается верстка сайта, тестируется только факт записи на курс.
4. Возможно ложное срабатывание на ошибку, если будет меняться код и селекторы.

## 5. Перечень необходимых специалистов для автоматизации.
* Нужен специалист QA automation engineer. 

## 6. Интервальная оценка с учётом рисков в часах.
* Для осуществления данной функции автотестами возможно потребуется
от 1 до 2 дней. В зависимости от опыта у тестировщика.
