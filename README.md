Задание:
1. Создайте фуллстек-приложение с рецептами блюд, которое будет использовать Django Rest Framework, автодокументацию OpenAPI+Swagger и react-router.
2. Давать пользователю возможность создавать рецепты не нужно: достаточно распределить их по категориям и отображать в клиенте и в API.
3. Где отображать документацию API — решать вам.
4. У каждого блюда и каждой категории должна быть своя страница: с главной страницы можно перейти на любую из категорий, а из категории — на любой рецепт этой категории.

Быстрый старт:
- Клонируем репозитарий.
- Устанавливаем виртуальное окружение в корневой папке проекта Переходим в папку back и устанавливаем зависимости Запускаем команду pip install -r requirements.txt
- В консоли переходим в директорию проекта и стартуем проект: python manage.py runserver - сервер стартует на локальном хосте
API проекта будет доступно по адресам:
http://127.0.0.1:8000/swagger/ swagger
http://127.0.0.1:8000/redoc/ redoc
http://127.0.0.1:8000/json/ Пример json
http://127.0.0.1:8000/admin/ админка для правок
- Далее переходим в папку front
- Устанавливаем зависимости: npm install
- Запускаем сервер DevServer: npm start