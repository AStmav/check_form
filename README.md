# Тестовое задание "WEB - приложение для определения заполненных форм"

## Описание
Сопоставляются названия полей форм и типов данных поступающих от пользователя в рамках POST- запроса с информацией хранимой в базе данных на сервере.
 
Вывод информации о совпадающих формах, в случае если данные из  POST - запроса  прошли валиданию данных, либо об отсутствии совпадающих форм, либо о тех данных, которые не смогли пройти валидацию.


## Инструкция по установке

- Склонировать репозиторий
```
git clone https://github.com/AStmav/check_formg.git

```


- Переходим в папку проекта  
Формируем и активируем виртуальное окружение, устанавливаем зависимости
```python
python- m venv web_app_check_form
cd venv
.\Scripts\activate
pip install -r requirements.txt
 
```
- Запуск тестов
```python
python manage.py test

```
- Запуск в режиме разработки (опционально)
```python
python manage.py runserver
```
Введите в адресной строке браузера :
```
http://127.0.0.1:8000/
```
Заполняя форму можно проверить условия выполнения валидациии  и заполнения формы.
