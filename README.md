FastAPI TODO

Endpoints
/all [GET] - Получение всех заметок
/change_content [PUT] - Изменение текста заметки
/create [POST] - Создание заметки
/delete/{id} [DELETE] - Удаление заметки по id
/get/{id} [GET] - Получение конкретной заметки по id
/is_done/{id} [PUT] - Изменение статуса заметки (Выполнено/Не выполнено)

Настройка

Склонируйте проект

Создайте виртуальное окружение:

python3 -m venv venv

Активируйте его

Установите зависимости:

pip install -r requirements.txt

Запустите приложение:

python main.py
