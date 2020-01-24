## Praćenje neuspjeha

Dodajmo kôd za praćenje kvarova.

+ Svaki put kad se uspostavi veza na Pin0, varijabli `ne uspije` dodati ćete 1. Da biste to učinili, povucite `na pin P0 pritisnut` s 'Ulaz'.

![screenshot](images/frustration-pressPin0.png)

+ Zatim dodajte 2 bloka za prikaz križa na 1 sekundu kada pritisnete Pin0.

![screenshot](images/frustration-pin0-x.png)

+ Tada ćete morati dodati 1 u varijablu `ne uspijeva`. Da biste to učinili, povucite stavku `promjenu 1` iz Varijable i promijenite `stavka` u `neuspjeh`. 

![screenshot](images/frustration-pin0-fails.png)

+ Konačno, možete dodati kôd za prikaz ažuriranog broja kvarova. Ovako bi tvoj kôd trebao izgledati.

![snimka zaslona](images/frustration-pin0-code.png)

+ Testirajte svoj kôd pritiskom na tipku A na emulatoru za početak igre. Svakim pritiskom Pin0 trebali vidjeti svoje `ne` varijabilni porast od 1.

![screenshot](images/frustration-pin0-test.png)

+ Kliknite "Preuzmi" i prenesite skriptu na svoj mikro: bit. Možete pritisnuti Pin0 dovršenjem kruga. Da biste to učinili, postavite desni palac na zemaljsku iglu (GND), a zatim dodirnite Pin0 lijevim palcem.

![screenshot](images/frustration-pin0-compile.png)