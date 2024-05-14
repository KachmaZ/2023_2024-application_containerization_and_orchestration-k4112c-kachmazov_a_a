
University: [ITMO University](https://itmo.ru/ru/)  
Faculty: [FICT](https://fict.itmo.ru)  
Course: [Application containerization and orchestration](https://github.com/itmo-ict-faculty/application-containerization-and-orchestration)  
Year: 2023/2024  
Group: K4112c  
Author: Kachmazov Arthur Andreevich  
Practice: practice3  
Date of create: 14.05.2024  
Date of finished: 14.05.2024 

## Подключение линтера к проекту
Работа продолжается в проекте todo-service из практической работы №1.
Интеграция в проект линтера ESLint.  
![3 1](https://github.com/KachmaZ/2023_2024-application_containerization_and_orchestration-k4112c-kachmazov_a_a/assets/59313334/f8e7d84e-126e-4dd2-a610-188283ce8e25)

## Настройка CI/CD
Для внедрения CI/CD был использован встроенный инструмент GitHub Actions. Его функциональности достаточно для выполнения поставленных задач, при этом он не требует установки новых локальных больших сервисов по типу Jenkins.  
В репозитории создан конфигурационный файл CICD.yml  
![image](https://github.com/KachmaZ/2023_2024-application_containerization_and_orchestration-k4112c-kachmazov_a_a/assets/59313334/a3120136-11c7-423b-bb49-1a87dcd6f329)  

## Тестирование CI/CD
Отработка пайплайна при ошибке  
![3 3](https://github.com/KachmaZ/2023_2024-application_containerization_and_orchestration-k4112c-kachmazov_a_a/assets/59313334/136033ff-9528-4cbd-bd7f-46c44e210894)  

Отработка пайплайна при успехе  
![3 4](https://github.com/KachmaZ/2023_2024-application_containerization_and_orchestration-k4112c-kachmazov_a_a/assets/59313334/1a0c902b-1de0-4f7b-9a5b-6fcbecd2ca79)  

Сохранённый в Docker Hub образ  
![3 5](https://github.com/KachmaZ/2023_2024-application_containerization_and_orchestration-k4112c-kachmazov_a_a/assets/59313334/c9d464f3-2be9-407d-a0de-befaf79dfbe7)  
