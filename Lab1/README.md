University: [ITMO University](https://itmo.ru/ru/)

Faculty: [FICT](https://fict.itmo.ru)

Course: [Network programming](https://github.com/itmo-ict-faculty/network-programming)

Year: 2024/2025

Group: K3320

Author: Urazalin Amir

Date of create: 28.03.2025

Date of finished: 28.03.2025

## Настройка виртуальной машины в YC

Развернул виртуальную машину в YC

<img width="1041" alt="image" src="https://github.com/user-attachments/assets/717f4a7f-9096-4e09-85c4-7f5407d41bd8" />


Установил на нее Wireguard, сгенерировал сертификаты.

```
sudo apt install wireguard -y

wg genkey | sudo tee /etc/wireguard/private.key

sudo cat /etc/wireguard/private.key | wg pubkey | sudo tee /etc/wireguard/public.key

```

Задал файл конфигурации WG conf

<img width="408" alt="image" src="https://github.com/user-attachments/assets/bbb098d1-f193-4fbf-b941-001642df3d9d" />

## Настройка CHR

Настроил конфигурацию микротик

<img width="461" alt="image" src="https://github.com/user-attachments/assets/5c72f454-fdba-4979-b71d-bb30577ed913" />

## Проверка работоспособности

Из CHR в виртуалку в клауде

<img width="452" alt="image" src="https://github.com/user-attachments/assets/8896ac67-4d61-475e-a01c-a2520947d808" />

Из ВМ в CHR.

<img width="417" alt="image" src="https://github.com/user-attachments/assets/322d2667-fabc-4245-ace8-b9018c1d4fd4" />


