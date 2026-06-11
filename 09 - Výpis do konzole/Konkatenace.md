### Kontatenace
Konkatenace v C# znamená spojování textů (řetězců) dohromady. Ke spojování řetězců se používá operátor **+**.
Operátor + u stringů znamená: „vezmi dva texty a spoj je dohromady“.

## :computer: Základní příklad
```
</>C#
string jmeno = "Jan";
string prijmeni = "Novák";

string celeJmeno = jmeno + " " + prijmeni;

Console.WriteLine(celeJmeno);
```
Výsledek : *Jan Novák*  

## :computer: Konkatenace s čísly
```
</>C#
int vek = 20;

Console.WriteLine("Věk je " + vek + " let.");
```
Výsledek : *Věk je 20 let.*  

## :warning: POZOR
```
</>C#
string prvniCislo = "15";
string druheCislo = "20";

Console.WriteLine(prvniCislo + druheCislo);
```
Výsledek : *1520*  
V tomto případě spojujeme dva retězce, proto nebude výsledek součtem těchto dvou čísel!
