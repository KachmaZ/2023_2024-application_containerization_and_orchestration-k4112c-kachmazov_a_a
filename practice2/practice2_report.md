
University: [ITMO University](https://itmo.ru/ru/)  
Faculty: [FICT](https://fict.itmo.ru)  
Course: [Application containerization and orchestration](https://github.com/itmo-ict-faculty/application-containerization-and-orchestration)  
Year: 2023/2024  
Group: K4112c  
Author: Kachmazov Arthur Andreevich  
Practice: practice2  
Date of create: 14.05.2024  
Date of finished: 14.05.2024 

## Предварительная настройка Postgres
Создание пространства имён  
<img width="293" alt="2 1" src="https://github.com/KachmaZ/2023_2024-application_containerization_and_orchestration-k4112c-kachmazov_a_a/assets/59313334/8ecdf7ce-263e-40dd-9f96-cfa284cdde72">  

Настройка данных для авторизации в виде секретов  
<img width="665" alt="2 2" src="https://github.com/KachmaZ/2023_2024-application_containerization_and_orchestration-k4112c-kachmazov_a_a/assets/59313334/daa75d01-5d54-456c-a6aa-4b870cdc82e2">    

Созданные данные:  
<img width="417" alt="2 3" src="https://github.com/KachmaZ/2023_2024-application_containerization_and_orchestration-k4112c-kachmazov_a_a/assets/59313334/f556f6d5-c2ce-4b12-ba03-9c85432ff268">  

## Statefulset
Определение контейнера с базой данных Postgres в созданном ранее пространстве имён. Передача секретов.  
<img width="560" alt="2 4" src="https://github.com/KachmaZ/2023_2024-application_containerization_and_orchestration-k4112c-kachmazov_a_a/assets/59313334/b54c0f90-7f7f-4670-ad20-4b780e6cadf3">  

## Запуск
Создание пода Postgres  
<img width="481" alt="2 5" src="https://github.com/KachmaZ/2023_2024-application_containerization_and_orchestration-k4112c-kachmazov_a_a/assets/59313334/08fa23af-3a95-4696-ab4c-8fb58c3ab38b">  

Создание новой таблицы пользователя  
<img width="348" alt="2 6" src="https://github.com/KachmaZ/2023_2024-application_containerization_and_orchestration-k4112c-kachmazov_a_a/assets/59313334/dde67575-ae57-4e40-9f0a-deabe3834a7c">  

Удаление и пересоздание пода для проверки работы minicube  
<img width="673" alt="2 7" src="https://github.com/KachmaZ/2023_2024-application_containerization_and_orchestration-k4112c-kachmazov_a_a/assets/59313334/2df14b6a-e8ef-4585-8033-c9c3054b0034">  
