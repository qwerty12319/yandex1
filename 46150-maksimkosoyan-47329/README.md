# Инструкция к проекту

## Установка
1. Активируйте виртуальное окружение:
   ```
   pip install venv
   python -m venv venv
   venv/Scripts/activate.bat
   для Windows или для Linux
   source venv/bin/activate
   ```
2. Установите зависимости:
   
   dev
   ```
   pip install -r requirements/dev.txt
   ```
   prod
   ```
   pip install -r requirements/prod.txt
   ```
   test
   ```
   pip install -r requirements/test.txt
   ```
3. Подставьте настоящие значения в файл .env

   SECRET_KEY

   DEBUG

   ALLOWED_HOSTS

    
4. Запусите:
   ```
   python manage.py runserver
   ```
   
# Другое

Я так и не понял что там с бейджиками, 
поэтому скопировал с лекции
![pipeline](https://gitlab.crja72.ru/django_2023/students/46150-maksimkosoyan-47229/badges/main/pipline.svg)