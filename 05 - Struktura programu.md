### Systaxe v C#  
### Jak funguje program po spuštění?
  1. Spustí se kompilátor, který si kód přeloží 
  2. Spustí se metoda **Main()**
  3. Program běží řádek po řádku a plní jednotlivé příkazy
  4. Jakmile dojde na konec **Main()**, program skončí   

### Aby program fungoval musí:
  - Každý program má vstupní bod. 
  - Veškerý zdrojový kód musí být uvnitř třídy (class).
  - Každý blok má složené závorky tzv.tělo kódu.
  - C# rozlišuje velká a malá písmena!
  - Každý příkaz končí středníkem.

Vyjímkou mohou být komentáře, podmínky, cykly, 
zkrátka příkazy, za kterými následuje blok dalších příkazů, který je oddělen tělem kódu pomocí složených závorek **{}**.   
Pamatujte, že po spuštění se nejdříve spustí metoda **Main()** a poté postupně příkaz za příkazem:exclamation:

// Příklad jednořádkového komentáře.  
   
/* Příklad víceřádkového komentáře.   
Příklad víceřádkového komentáře.   
*/ Příklad víceřádkového komentáře.   

Účel komentářů je zjednodušit autorovi pochopení kódu. V úvodu studia doporučuji zakomentovávat řádky stručným popisem jednotlivých příkazů.   
Pro hromadné zakomentování se používá zkratka **CTRL + K + C** (C > comment).   
Pro hromadné odkomentování se používá zkratka **CTRL + K + U** (U > uncomment).   
Potřebný text je potřeba mít označený.

### :top: Best practices:
  - Smusluplné názvy
  - PascalCase pro třídy a metody
  - camelCase pro proměnné
  - Přehlednost kódu
  - Stručné komentáře
