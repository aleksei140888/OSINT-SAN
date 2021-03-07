#                                                                           OSINT SAN Framework.



Framework направленный на получение данных и деанонимизацию пользователей. В инструменте используется большое количество API. Сейчас инструмент дорабатывается, некоторые функции могут работать не корректно.

Инструмент адаптирован под: Kali Linux * Parrot

![alt tag](https://github.com/Bafomet666/screen/blob/main/LOGOup.png)

----

### Для работы вам понадобятся API

Название API и сайты для их получения.


     API для получения информации о номере https://numverify.com

     API для получения информации whois https://ipstack.com

     Shodan API https://www.shodan.io

     Проверка на CMS https://whatcms.org/API

     Gmap для gui https://developers.google.com/maps/documentation

     VirusTotal бесплатная служба проверки https://developers.virustotal.com/v3.0/reference
 
     Hunter.io API для получения сведений о @mail https://hunter.io/api

     ZoomEye API, вход осуществляется путем авторизации в самом инструменте https://www.zoomeye.org

     Torrent API https://iknowwhatyoudownload.com/en/api/

     CMS detect https://whatcms.org

     Обязательно прописывать API в settings.py
     
---
     
### Зависимости. ![Альтернативный текст](https://camo.githubusercontent.com/d4d0378438eebbdfdf98948d518a47cb34bd241b3c836aaae47255a64f2c3bbe/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f507974686f6e2d332e372532422d627269676874677265656e)

 
Как только вы ввели все свои API, вам нужно установить зависимости:

     sudo pip3 install -r requirements.txt
    
     В сложных модулях, вам будет предоставлен выбор дополнительной установки модулей.
---

### Использование

Запускать командой: python3 osintsan.py

Пароль и логин хранится у нас в паблике в telegram.

Инструменты запускаются в двух режимах:

    Если вам нужны функции без root [ Они зеленой строкой ], запускайте терминал:  python3 osintsan.py 
      
    Если вам нужны функции root [ Они зеленой красной ], запускайте терминал: sudo python3 osintsan.py
 
Official public https://t.me/osint_san_framework

![alt tag](https://github.com/Bafomet666/screen/blob/main/login.png)

После успешной авторизации, вам будет доступно меню с инструментами.

---

### Функционал

#### Функция [ 01 ]
Проверка IP адреса в Shodan and Censys на утечки.

#### Функция [ 02 ]
Работа с домменым именем.

    Reverse
    Subdomian
    NsLookup
    CMS Detect
    Port Scan
    Bruteforse
    ClickJaking
    Cors
    Host Header Injection
    Header
    Crawler

#### Функция [ 03 ]
Получение данных о мобильном номере.

#### Функция [ 04 ]
Карта DNS в высоком разрешении

#### Функция [ 05 ]
Вычисление места съёмки фотографии, извлечение геолокации из фотографии.

#### Функция [ 06 ]
Осуществление поиска в google and yandex картинкам.

#### Функция [ 07 ]
Проверка сервера либо IP адреса на HoneyPot

#### Функция [ 08 ]
Mac address info, с вероятностью 40% покажет еще и геолокацию.

#### Функция [ 09 ]
IP геолокация на картах GUI. Вводные данные могут быть как IP адресом так и доменом.

#### Функция [ 10 ]
Проверяем что загружает жертва через torrent в данный момент жертва.
 
#### Функция [ 11 ]
OSINT Instagram.

#### Функция [ 12 ]
DNS info, огромнейший pack информации.

#### Функция [ 13 ]
Сбор адресов @mail с сайтов. Используется API censys.

#### Функция [ 14 ]
Подключение через android debug bridge.

#### Функция [ 15 ]
Big bro 8.0 режим геолокации.

#### Функция [ 16 ]
Массовый dump данных с Shodan. Работает через API

#### Функция [ 17 ]
Графический мониторинг вашей локальной сети GUI

#### Функция [ 18 ]
Проверка всех плагинов и модулей.

#### Функция [ 19 ]
Фишинг модификация Big bro. Находится в beta версии.

#### Функция [ 20 ]
Функция открывает сайты для идентифика́ции по лицу.

#### Функция [ 21 ]
OSINT Wikipedia

### Функция [ 22 ]
ip logger

### Функция [ 23 ]
Анонимная почта

### Функция [ 24 ]
База данных паролей Bafomet +
Сейчас в базе собрано 1.9 миллиарда паролей. Все разбито по частями, что бы удобно было загружать. Пароли под различные задачи.

### Функция [ 25 ]
Поднимаем сайт Beff-XSS в сеть

Сначал вам нужно будет нажать 1. Это вариант с онлайном.
Потом вам выпадет инструкция по установке ngrok в положение ( start --all на 4 ссылки ) После вы запускаете ngrok в полном режиме и даете старт программе.

После вас попросят вписать ссылки, вписываем до http, https в таком формате:

     f19d35259оaff5.ngrok.io  всегда сначала по 80 порту
     
     f19d3c96533ff5.ngrok.io  потом по 3000 порту
     
Установка стилей для сайта. Вам нужно перейти в папку "OSINT SAN" и скопировать все там из папки "Стили Beef" в директорию /var/www/html

Если вдруг у вас нет доступа к копированию стилей в beef html, Сделайте:
         
         sudo chmod 777 /var/www/html

### Функция [ 26 ]
Наше большое сообщество OSINT СНГ

### Функция [ 27 ]
Большой pack информации по OSINT

### Функция [ 28 ]
Open Maltego, просто открывает мальтего.

### Функция [ 29 ]
Массовый dump данных с ZoomEye. Аналог shodan.

### Функция [ 30 ]
Деанонимизация хакера его же ссылкой ngrok, это обычный парсер

----

Приятного использования.

[Лицензия](https://github.com/Bafomet666/OSINT-SAN/blob/main/LICENSE)





