# Практическое занятие №6-2. Настройка протокола GRE

# Определение IP-адреса порта S0/0/0 на маршрутищаторе RA

 ![Desktop Screenshot 2023 12 21 - 12 56 36 87](https://github.com/hipster-x/PR-6-2/assets/145153023/ed66a1a7-853a-4b67-8067-8f2afb89e0e0)

# 1. Проверка связи между маршрутизаторами

 1. Отправка эхо-запроса с RB на RA

 ![Desktop Screenshot 2023 12 21 - 12 57 40 38](https://github.com/hipster-x/PR-6-2/assets/145153023/ed2d8e40-a916-4606-9a54-f33a6f36810c)

 Определение IP-адреса ПК А

 ![Desktop Screenshot 2023 12 21 - 12 58 37 74](https://github.com/hipster-x/PR-6-2/assets/145153023/f6952e40-3400-4d92-a5fc-019bb691de00)

 2. Отправка эхо-запроса с ПК B на ПК А до настройки туннеля GRE

 ![292188033-4eaf2dec-368f-422b-8116-3025f1d2462c](https://github.com/hipster-x/PR-6-2/assets/145153023/f8ef1499-aeca-4412-9b2f-8bf4fa74606d)


# 2. Настройка туннелей GRE

 1. Настройка туннеля GRE на маршрутизаторе RA
  
 ![Desktop Screenshot 2023 12 21 - 13 04 26 76](https://github.com/hipster-x/PR-6-2/assets/145153023/9328a291-542c-42da-9b76-6b9d02e75d91)

  2. Настройка туннеля GRE на маршрутизаторе RB

  ![Desktop Screenshot 2023 12 21 - 13 06 29 55](https://github.com/hipster-x/PR-6-2/assets/145153023/2d7da268-8bc8-456e-be27-b356a2c30b9e)

   3. Настройка маршрута для частного трафика IP

  RA 

 ![Desktop Screenshot 2023 12 21 - 13 07 38 97](https://github.com/hipster-x/PR-6-2/assets/145153023/6448be9c-9807-4462-8db3-f89699f92a36)

 RB

  ![Desktop Screenshot 2023 12 21 - 13 08 35 75](https://github.com/hipster-x/PR-6-2/assets/145153023/7a4397bb-d134-4b3d-a38f-e370e93c5f62)

# 3. Проверка связи между маршрутизаторами

 1. Отправка эхо-запроса с ПК B на ПК А после настройки GRE туннеля
  
 ![Desktop Screenshot 2023 12 21 - 13 09 32 96](https://github.com/hipster-x/PR-6-2/assets/145153023/ff49cada-8cd1-4981-b4ed-7860f2cebdd2)

 2. Трассировка от ПК А до ПК В

 ![Desktop Screenshot 2023 12 21 - 13 10 24 63](https://github.com/hipster-x/PR-6-2/assets/145153023/0d99468a-0d67-4b6f-a89d-650384d432f2)

# Проверка успешности выполнения работы 

 ![Desktop Screenshot 2023 12 21 - 13 14 00 71](https://github.com/hipster-x/PR-6-2/assets/145153023/2d010145-bd29-47a4-914c-51fed22c3adf)

 


