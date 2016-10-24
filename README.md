# iujc_cv5
Páté předmětu IUJC (24.10.2016)

##Příklad 1 
Napište funkci, která vrací součet posloupnosti čísel od 1 do N, (1+2+3+…+N). Hlavní program načte hodnotu N, výsledek funkce zobrazí na obrazovce (např. pro N= 5 bude návratová hodnota funkce 15) 
Příklad požadované funkce: 
```c
int soucetCisel(int n);
```
##Příklad 2 
Napište funkci, která spočítá kořeny kvadratické rovnice. Funkce vrací 0 v případě, že rovnice nemá reálné řešení a 1 v případě, že reálné řešení má. Hlavní program načte hodnoty a,b,c. Pokud má reálné řešení, pak se výsledky vytisknou na obrazovku. V opačném případě je na obrazovku vytištěno, že reálné řešení nemá. 
Nápověda: funkce odmocniny sqrt() je dostupná z hlavičkového souboru math.h. Hodnoty x1,x2 lze uchovávat v dvourozměrném poli, nebo lze předat adresu proměnných x1,x2. 
Příklad požadované funkce:
```c
int kvadrRov(int a,int b,int c,float body[]);
int kvadrRov2(int a,int b,int c,float *xx1,float *xx2);
```
##Příklad 3 
Napište funkci, která vrací četnost požadovaného znaku v řetězci. Hlavní program načte řetězec a hledaný znak. Výsledek je vytištěn na obrazovku. 
Modifikace: funkce vrací void, hodnotu četnosti obsahuje proměnná volaná „odkazem“ 
Příklad požadované funkce: 
```c
int cetnostZn(char string[],char znak);
```
