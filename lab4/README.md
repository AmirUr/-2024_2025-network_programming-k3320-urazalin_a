
# Лабораторная работа 4

Установим вагрант через впн и раскатим виртуальную машину

<img width="794" alt="image" src="https://github.com/user-attachments/assets/00573476-020b-4161-a53f-52c48771450c" />

Раскатил виртуальную машину

<img width="923" alt="image" src="https://github.com/user-attachments/assets/2d6dadda-1916-4e53-91d9-494f2e4b1f4a" />

В первой части задания реализуем базовую переадресацию для ipv4 согласно заданию Implementing Basic Forwarding. После компиляции P4-программы и настройки таблиц маршрутизации все узлы обменялись сообщениями.

![image](https://github.com/user-attachments/assets/d71803c6-6bb3-4546-b6dc-a9e4203528d4)

Схема

![image](https://github.com/user-attachments/assets/cdd9579f-ff7c-465e-b3ab-fb7458c43a7e)


Во второй части работы передаем пакеты через виртуальный туннель.
Раньше пакеты шли напрямую. Теперь добавили специальный заголовок myTunnel_t.

Итог:

<img width="678" alt="image" src="https://github.com/user-attachments/assets/b1e5a746-8272-423f-af7c-56147893d10d" />


<img width="323" alt="image" src="https://github.com/user-attachments/assets/21e1af22-056b-4d94-984e-bfd2fc14c565" />

Схема:

![image](https://github.com/user-attachments/assets/35f22f8e-15ce-4694-a2f7-b53500cc01a8)

