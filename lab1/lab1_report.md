University: [ITMO University](https://itmo.ru/ru/)\
Faculty: [FTMI](https://ftmi.itmo.ru/)\
Course: [Introduction in web tech](https://itmo-ict-faculty.github.io/introduction-in-web-tech/)\
Year: 2025\
Group: U4225\
Author: Grigoryev Alexey Pavlovich\
Lab: Lab1\
Date of create: 03.10.2025\
Date of finished: 03.10.2025

Screenshots to prove lab1 completion:
1. Установка Docker
![img0.png](img0.png)
2. Работа с готовыми образами
![img1.png](img1.png)
![img2.png](img2.png)
3. Запуск веб-сервера
![img3.png](img3.png)
![img4.png](img4.png)
4. Управление контейнерами
![img5.png](img5.png)
5. Работа с томами
![img6.png](img6.png)

Lab1*

1. Создание файлов проекта
![img8.png](img8.png)
2. Создаем Dockerfile по инструкции (Dockerfile находится в папке lab1star)
3. При запуске видим, что выходит ошибка — недостаточно Python пакетов, придётся запускать локально и понять, какие файлы нужны
`python3.9 -m venv venv`
`source venv/bin/activate`
`pip install flask`
`pip freeze > requirements.txt`
Мы локально создали среду для запуска python, скачали нужные зависимости и "заморозили" их, теперь можно запускать.
4. Билдим, запускаем и делаем запрос к контейнеру — все работает
![img7.png](img7.png)
![img9.png](img9.png)