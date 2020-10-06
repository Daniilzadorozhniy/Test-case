# Тест кейс №1 Валидные ключи для KeyValidator

Предусловие: скачайте приложение KeyValidator по [ссылке](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/artifacts/KeyValidator.class).

### *Шаги воспроизведения*

1. Правой кнопкой мыши кликните по "Рабочему столу" и в появившемся меню выбираем "Git Bash Here"

### *Ожидаемый результат*:

откроется консоль Git Bash

2. В консоли Git Bash прописать команду *"java KeyValidator 8f05e6a7-70e9-33d7-bfe7-b19eae0d8998 80b427f8-92cd-3aae-ba04-3927fbe17c6 b295bc63-9f03-3b4b-af80-969b39f8c262 387eedc6-12e9-3b32-9881-63b6b5e85317 c19a8cf9-5c3a-37c5-b7f3-d16d38a0c180"* без ковычек 

### *Ожидаемый результат*:

Ниже введенной команды *java KeyValidator 8f05e6a7-70e9-33d7-bfe7-b19eae0d8998 80b427f8-92cd-3aae-ba04-3927fbe17c6 b295bc63-9f03-3b4b-af80-969b39f8c262 387eedc6-12e9-3b32-9881-63b6b5e85317 c19a8cf9-5c3a-37c5-b7f3-d16d38a0c180* появится сообщение:

Result for 8f05e6a7-70e9-33d7-bfe7-b19eae0d8998: OK

Result for 80b427f8-92cd-3aae-ba04-03927fbe17c6: OK

Result for b295bc63-9f03-3b4b-af80-969b39f8c262: OK

Result for 387eedc6-12e9-3b32-9881-63b6b5e85317: OK

Result for c19a8cf9-5c3a-37c5-b7f3-d16d38a0c180: OK

### *Окружение*: 

* ОС Windows 7 (Домашняя версия), 64 разрядная
* java -version
openjdk version "11.0.8" 2020-07-14
OpenJDK Runtime Environment AdoptOpenJDK (build 11.0.8+10)
OpenJDK 64-Bit Server VM AdoptOpenJDK (build 11.0.8+10, mixed mode)
* Браузер Google Chrome (ерсия 81.0.4044.138 (Официальная сборка), (64 бит))
* Git Bash


# Тест кейс №2 Невалидные ключи для KeyValidator

*Предусловие*: скачайте приложение KeyValidator по [ссылке](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/artifacts/KeyValidator.class).

### *Шаги воспроизведения*

1. Правой кнопкой мыши кликните по "Рабочему столу" и в появившемся меню выбираем "Git Bash Here"

### *Ожидаемый результат*:

откроется консоль Git Bash

2. В консоли Git Bash прописать команду *"java KeyValidator 18252235-78e0-44a5-8720-556f0c7da17a e66075b6-ddad-445e-baf6-161b3289522b b6d53250-f07e-4352-a293-6102ddf7f1ca c2bc778a-1cb9-46c6-b435-0489649d2a42 2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1"* без ковычек.

### *Ожидаемый результат*:

Ниже введенной команды *java KeyValidator 18252235-78e0-44a5-8720-556f0c7da17a e66075b6-ddad-445e-baf6-161b3289522b b6d53250-f07e-4352-a293-6102ddf7f1ca c2bc778a-1cb9-46c6-b435-0489649d2a42 2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1* появится сообщение:

Result for 18252235-78e0-44a5-8720-556f0c7da17a: FAIL

Result for e66075b6-ddad-445e-baf6-161b3289522b: FAIL

Result for b6d53250-f07e-4352-a293-6102ddf7f1ca: FAIL

Result for c2bc778a-1cb9-46c6-b435-0489649d2a42: FAIL

Result for 2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1: FAIL


### *Окружение*: 

* ОС Windows 7 (Домашняя версия), 64 разрядная
* java -version
openjdk version "11.0.8" 2020-07-14
OpenJDK Runtime Environment AdoptOpenJDK (build 11.0.8+10)
OpenJDK 64-Bit Server VM AdoptOpenJDK (build 11.0.8+10, mixed mode)
* Браузер Google Chrome (ерсия 81.0.4044.138 (Официальная сборка), (64 бит))
* Git Bash
