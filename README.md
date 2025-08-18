
_Занятие 4_

Задача 1

https://hub.docker.com/repository/docker/alejandromunis/custom-nginx/general

Задача 2
<img width="1389" height="69" alt="image" src="https://github.com/user-attachments/assets/fce51dc0-a025-4a58-8889-e61b7ca6bee2" />
<img width="1342" height="98" alt="image" src="https://github.com/user-attachments/assets/16472253-ebdc-4658-b99e-16c5483a964a" />
<img width="1666" height="134" alt="image" src="https://github.com/user-attachments/assets/ffd952dc-8380-4c21-83a4-f5107f4eca1c" />
<img width="348" height="27" alt="image" src="https://github.com/user-attachments/assets/ed38fd00-85d9-47d2-a568-1e145f6f6417" />
<img width="1110" height="885" alt="image" src="https://github.com/user-attachments/assets/f693868a-6b29-486f-9efc-282ec9622608" />

Задача 3
<img width="1162" height="90" alt="image" src="https://github.com/user-attachments/assets/e57d84cd-0a47-4486-9c08-e11b99bd7aff" />

Подключение к контейнеру произошло не в интерактивном режиме, при закрытии сессии контейнер прекратил работу.

<img width="496" height="117" alt="image" src="https://github.com/user-attachments/assets/fa5f5f4c-eea2-42a5-8528-ce88c8f52f42" />
<img width="583" height="171" alt="image" src="https://github.com/user-attachments/assets/f72ebb16-4938-496e-9e72-b13c1820a09d" />
<img width="511" height="127" alt="image" src="https://github.com/user-attachments/assets/f426dba1-2105-451c-9640-255b0af05a92" />

По порту 8080 нельзя подключиться к nginx контейнера, потому что в конфиге изменен порт HTTP на 81 и перезапущена служба nginx, необходимо перезапустить контейнер с перенаправлением порта 8080 на 81 порт контейнера

<img width="1670" height="305" alt="image" src="https://github.com/user-attachments/assets/67c1b8ce-b9b9-458d-bff5-fd1c64ccbc6d" />

<img width="1518" height="149" alt="image" src="https://github.com/user-attachments/assets/71eaec6c-6d6b-44d8-b267-62ef43d86c05" />

Задача 4

Образ CentOS признан устаревшим, буду использовать Rocky

<img width="784" height="53" alt="image" src="https://github.com/user-attachments/assets/7cbb6b13-ed5d-416b-8dca-c0713ca43a49" />

<img width="1570" height="374" alt="image" src="https://github.com/user-attachments/assets/66059719-1e0f-4634-9dde-cfcb28ae4b72" />

Задача 5

В мануале явно написано, что предпочитается compose.yaml 

Для применения docker-compose.yaml требуется прописать в compose.yaml секцию include:

<img width="1373" height="417" alt="image" src="https://github.com/user-attachments/assets/dfb0cd81-eb44-4a21-8f9c-4fe874a39c99" />
