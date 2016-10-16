# Receptek és hozzávalók
Alkalmazások fejlesztése 1/3 beadandó

## Funkcionális követelmények
#### Vendég (nem bejelentkezett látogató):
* bejelentkezés
* legnépszerűbb receptek megtekintése
* receptek böngészése
* receptek leírásának, hozzávalóinak, képeinek megtekintése 
* receptek keresése
* honlapra való regisztráció, ami új dolgokkal/funkciókkal látja el a felhasználót
* hasonló receptek megtekintése (hasonló receptek azok, amiknek legalább 5 közös hozzávalójuk van)

#### Bejelentkezett felhasználó:
* egy recept felvétele a kedvenc receptekhez
* különböző receptek értékelése (+1 pont hozzáadódik a recepthez a gomb lenyomásával) - ennek segítségével lehet majd meghatározni a legnépszerűbb recepteket
* saját recept beküldése képekkel, hozzávalókkal és leírással
* saját felhasználói adatok szerkesztése
* receptek fordítása angolra

## Nem funkcionális követelmények
* biztonság: jelszavak, e-mail címek tárolása - nem autorizált felhasználó ne férjen hozzá egy felhasználó adataihoz és autorizácóhoz kötött funkciókhoz sem
* egyszerű, érthető, felhasználóbarát felület
* gyors működés

## Szakterületi fogalomjegyzék
* recept:
    * étel elkészítéséhez szükséges hozzávalók leírása
    * étel elkészítésének lépéseit tartalmazó részletes leírása
    * különböző mértékegységek megadása más mértékegységekben, ha a felhasználó úgy dönt le szeretne fordítani angolra egy receptet

## Szerepkörök
* vendég: receptek keresését, böngészését, megtekintését végezheti
* felhasználó: receptek keresését, böngészését, megtekintését, saját receptjeinek módositását (új recept, recept törlése, recept képének megváltoztatása), receptek értékelését és más felhasználók által beküldött receptek hozzávalóinak, leírásainak angolra fordítását végezheti

## Használati eset diagram (Use Case Diagram)
![Használati eset diagram](images/receptek_UCD.PNG)

Link: [http://bit.ly/2dVzarp](http://bit.ly/2dVzarp)

## Folyamat diagramok
### Bejelentkezés folyamata
![Bejelentkezés folyamata](images/receptek_activity1.PNG)
Link: [http://bit.ly/2djnJWt](http://bit.ly/2djnJWt)

### Receptértékelés folyamata
![Receptértékelés folyamata](images/receptek_activity2.PNG)
Link: [http://bit.ly/2dTda0d](http://bit.ly/2dTda0d)

### Kedvencekhez adás folyamata
![Kedvencekhez adás folyamata](images/receptek_activity3.PNG)
Link: [http://bit.ly/2dWjVki](http://bit.ly/2dWjVki)

### Receptek fordításának folyamata
![Receptek forditásának folyamata](images/receptek_activity4.PNG)
Link: [http://bit.ly/2e9sGng](http://bit.ly/2e9sGng)

### Új recept felvételének folyamata
![Új recept felvételének folyamata](images/receptek_activity5.PNG)
Link: [http://bit.ly/2drKxXo](http://bit.ly/2drKxXo)