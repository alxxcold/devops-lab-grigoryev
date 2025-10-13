University: [ITMO University](https://itmo.ru/ru/)\
Faculty: [FTMI](https://ftmi.itmo.ru/)\
Course: [Introduction in web tech](https://itmo-ict-faculty.github.io/introduction-in-web-tech/)\
Year: 2025\
Group: U4225\
Author: Grigoryev Alexey Pavlovich\
Lab: Lab3\
Date of create: 13.10.2025\
Date of finished: 13.10.2025

Скриншоты по лабе 3:

1. Создание конфигурации Prometheus (находится в папке Prometheus).
2. Запуск Node Exporter и проверка работы (вывод curl лежит в файле prometheus/node_output.txt):
![img0.png](img0.png)
3. Запуск Prometheus:
![img1.png](img1.png)
![img2.png](img2.png)
4. Запуск Grafana:
![img3.png](img3.png)
![img4.png](img4.png)
5. Для того, чтобы взаимодействовали контейнеры создаем сеть, перезапускаем контейнеры с флагом --network, после этого настраиваем Grafana:
![img5.png](img5.png)
6. Тестирование системы:
![img6.png](img6.png)
Запросы в Prometheus
![img7.png](img7.png)
Графики в Grafana
![img8.png](img8.png)
График памяти
![img9.png](img9.png)