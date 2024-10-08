Описание проекта Сервис Stellar Burgers — это космический фастфуд: можно собрать и заказать бургер из необычных ингредиентов.

Структура проекта Директория tests включает в себя автотесты сервиса Stellar Burgers Константы распологаются в файле constant.py Фикстуры распологаются в файле conftest.py Локаторы распологаются в файле locators.py Генератор email распологается в файле random.py

Задание проекта Задание заключается в написании автотестов для сервиса Stellar Burgers. Необходимо проверить следующие функции:

Регистрация

- Успешная регистрация. Поле «Имя» должно быть не пустым; в поле Email введён email в формате логин@домен: например, 123@ya.ru. Минимальный пароль — шесть символов.
- Ошибку для некорректного пароля. 
Вход
- Вход по кнопке «Войти в аккаунт» на главной,
- Вход через кнопку «Личный кабинет»,
- Вход через кнопку в форме регистрации,
- Вход через кнопку в форме восстановления пароля. Переход в личный кабинет
Проверь переход по клику на «Личный кабинет».
Переход из личного кабинета в конструктор
- «Булки»,
- «Соусы»,
- «Начинки».
Запуск тестов в проекте Запустить тесты из терминала можно такой командой:

pytest -v tests.py# Sprint
