Объект тестирования: https://b2c.passport.rt.ru

Итоговый проект по автоматизации тестирования
В рамках выполнения дипломного проекта предстоит протестировать новый интерфейс авторизации в личном кабинете от заказчика Ростелеком Информационные Технологии.
Требования по проекту: https://docs.google.com/document/d/1zyZHGhbZ1THkwWEuqGexNa4H89FRKdye/edit?usp=sharing&ouid=110623258539296754002&rtpof=true&sd=true

Задание:

Протестировать требования.
Разработать тест-кейсы (не менее 15). Необходимо применить несколько техник тест-дизайна.
Провести автоматизированное тестирование продукта (не менее 15 автотестов). Заказчик ожидает по одному автотесту на каждый написанный тест-кейс. Оформите свой набор автотестов в GitHub.
Оформить описание обнаруженных дефектов. Во время обучения вы работали с разными сервисами и шаблонами, используйте их для оформления тест-кейсов и обнаруженных дефектов. (если дефекты не будут обнаружены, то составить описание трех дефектов)

Применялось тестирование по позитивному и негативному сценарию. Применялась техника тест-дизайна "Анализ граничных значений" в проверке поля ввода "Имя" формы регистрации.

В файле settings необходимо указать действующий логин, пароль зарегистрированного пользователя.

Назначение тестов приведено в комментариях.

Запуск тестов при помощи команд в консоли: python -m pytest -v --driver Chrome --driver-path chromedriver.exe tests/test.py

Для правильной работы тестов необходимо установить библиотеки в Python 3:

pytest

pytest-selenium

selenium

urllib3


Составленные тест-кейсы и баг репорты находятся тут: https://docs.google.com/spreadsheets/d/1KmWPOF_PW9UlKFBSu-Lf6NkmrF3x84Lm/edit?usp=sharing&ouid=110623258539296754002&rtpof=true&sd=true
