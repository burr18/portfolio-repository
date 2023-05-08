# Отчёт о тестировании

Проверка новой функции видео-уроков была проведена в период с 29.09.22 по 04.10.22.

### Тест-раны:

* [Таблица google][url]

[url]: https://docs.google.com/spreadsheets/d/1FPphkDZu20gk8ShPn5ObE7wbtKk-AoRrX1zrL5EHBVI/edit?usp=sharing

* Тест-ран тестов API:
 
![run api](https://user-images.githubusercontent.com/112339589/236830007-d258aef6-6851-4ae7-a015-cd70a9dfac67.jpg)

### Найденные баги:

**1. Тестирование портала для учителей**

![ DIP — Agile- - Jira - Google Chrome_3](https://user-images.githubusercontent.com/112339589/236831758-0bb7a352-e0b3-46be-ab52-56639624b269.jpg)
![ DIP — Agile- - Jira - Google Chrome_4](https://user-images.githubusercontent.com/112339589/236831764-29365402-0639-4f77-999a-2c96d6ac23e1.jpg)
![ DIP — Agile- - Jira - Google Chrome_5](https://user-images.githubusercontent.com/112339589/236831770-44d272ab-5b7a-4f6b-b551-6b63edf88f5d.jpg)
![ DIP — Agile- - Jira - Google Chrome_6](https://user-images.githubusercontent.com/112339589/236831778-5de1f370-176b-4543-a396-f3368a5cdd33.jpg)
![ DIP — Agile- - Jira - Google Chrome](https://user-images.githubusercontent.com/112339589/236831783-8c0bcf0d-5f7d-470e-9363-2682c946ee51.jpg)
![ DIP — Agile- - Jira - Google Chrome_2](https://user-images.githubusercontent.com/112339589/236831786-4487c7c0-8759-4dbf-9b0c-031bd4d8ce89.jpg)

Было выявлено 24 бага, 5 из них - с высоким приоритетом

**2. Тестирование приложения для ученика**
 
![ DIP — Agile- - Jira - Google Chrome_7](https://user-images.githubusercontent.com/112339589/236832775-0c0cd50b-1d4a-4e0f-9de7-87d96793da95.jpg)

Был выявлен 1 баг с высоким приоритетом, но тестирование не проводилось полностью, т.к. основная функция видео-уроков оказалась заблокирована (возможно было провести только smoke-тесты)

**3. Интеграционное тестирование**

![ DIP — Agile- - Jira - Google Chrome_8](https://user-images.githubusercontent.com/112339589/236832974-9443ca80-bb0b-40b7-a433-721a845350ad.jpg)

Был выявлен 1 баг с высоким приоритетом, но тестирование не проводилось полностью, т.к. основная функция видео-уроков в приложении ученика оказалась заблокирована.

**4. Тестирование API**

Баги не найдены.

### Готовность новой функции к выпуску

По результатам тестирования можно сказать, что функция видео-уроков не готова к выпуску, потому что она не работает в мобильном приложении ученика даже на начальном этапе:

Основная функция видео-уроков на портале для учителя работает корректно, но интерфейс веб-комнаты не удобен, не понятен интуитивно для пользователя, что сильно затрудняет использование этой функции.

Предлагаю сначала исправлять работу приложения для ученика, т.к. это более критичная проблема.
