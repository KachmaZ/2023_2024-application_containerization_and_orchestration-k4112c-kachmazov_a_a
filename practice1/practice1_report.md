
University: [ITMO University](https://itmo.ru/ru/)  
Faculty: [FICT](https://fict.itmo.ru)  
Course: [Application containerization and orchestration](https://github.com/itmo-ict-faculty/application-containerization-and-orchestration)  
Year: 2023/2024  
Group: K4112c  
Author: Kachmazov Arthur Andreevich  
Practice: practice1  
Date of create: 14.05.2024  
Date of finished: 14.05.2024  

## Создание микросервиса
Было написано простейшее клиент-серверное приложение на Javascript. Это браузерный todo-лист, позволяющий записывать и удалять задачи. Бэкенд реализован с помощью express.js  
![1 1](https://github.com/KachmaZ/2023_2024-application_containerization_and_orchestration-k4112c-kachmazov_a_a/assets/59313334/11883989-b5fb-4697-8368-52441a7f6579)

Swagger сгенерирован автоматически при помощи инструмента swagger-autogen.  
![1 2](https://github.com/KachmaZ/2023_2024-application_containerization_and_orchestration-k4112c-kachmazov_a_a/assets/59313334/224473f0-97e3-4008-b23f-52dae4f98c19)

В качестве "базы данных" использован json-файл.  

## Определение зависимостей приложения и создание Docker образа с помощью Dockerfile
Единственной зависимостью для данного микросервиса является Node.js, поэтому в dockerfile в качестве исходного образа указан Node 20 версии.  
![image](https://github.com/KachmaZ/2023_2024-application_containerization_and_orchestration-k4112c-kachmazov_a_a/assets/59313334/1918c574-25d3-4f7d-acf9-f04cb75cc88c)

## Запуск  
Для создания образа и запуска контейнера выполнена следующая команда:  
![image](https://github.com/KachmaZ/2023_2024-application_containerization_and_orchestration-k4112c-kachmazov_a_a/assets/59313334/fae8543b-1717-4002-9f04-080c48adf976)  
Помимо  именования контейнера в ней также указан прослушиваемый контейнером порт.  
Статус контейнера в desktop-интерфейсе:  
![image](https://github.com/KachmaZ/2023_2024-application_containerization_and_orchestration-k4112c-kachmazov_a_a/assets/59313334/00caf710-bdf6-49af-99cb-6b828c1052f9)
Приложение в браузере:  
![1 4](https://github.com/KachmaZ/2023_2024-application_containerization_and_orchestration-k4112c-kachmazov_a_a/assets/59313334/23235da5-4e10-4f71-8221-57b918018e7d)
