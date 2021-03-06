# KLDR-API
API udostępnia dane Kalendarza Liturgicznego Diecezji Radomskiej w postaci JSON.
Zapis formatu daty według [funkcji **date**](https://www.php.net/manual/en/function.date.php).

## Informacje o dniu
Aby pobrać informacje o dniu dzisiejszym:

    http://rub.ministranci.radom.pl/api/calendar.php
    
Aby pobrać informacje o 25 grudnia 2019:

    http://rub.ministranci.radom.pl/api/calendar.php?date=2019-12-25
    
Zmieniając datę należy pamiętać o formacie `Y-m-d`.

## Czytania na każdy dzień
Aby pobrać czytania na dzień dzisiejszy:

    http://rub.ministranci.radom.pl/api/reading.php?date=2019-12-25

Aby pobrać czytania na dzień 25 grudnia 2019:

    http://rub.ministranci.radom.pl/api/reading.php?date=2019-12-25
    
Zmieniając datę należy pamiętać o formacie `Y-m-d`.

## Intencje Apostolstwa Modlitwy
Aby pobrać Intencje Apostolstwa Modlitwy na dzień dzisiejszy:

    http://rub.ministranci.radom.pl/api/reading.php

Aby pobrać Intencje Apostolstwa Modlitwy na dzień 25 grudnia 2019:

    http://rub.ministranci.radom.pl/api/reading.php?date=2019-12-25
    
Zmieniając datę należy pamiętać o formacie `Y-m-d`.
Można również pominąć dzień używając formatu `Y-m`.

## Informacje o API
Aby pobrać informacje o tym API:

    http://rub.ministranci.radom.pl/api/info.php
