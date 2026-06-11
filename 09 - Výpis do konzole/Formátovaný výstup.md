## Formátovaný výstup
Formátovaný výstup v C# znamená, že si upravuješ, jak se hodnoty zobrazí v textu (např. počet desetinných míst, datum, zarovnání apod.).

Několik možností použití

### :computer: Formátování čísel (Zaokrouhlení / počet desetinných míst)
```
</>C#
double cislo = 12.34567;

Console.WriteLine($"{cislo:F2}");  // F znamená "Fixed" 
```
Výsledek: 12,35

### :computer: Formátování pomocí kompozitního zápisu
```
</>C#
double cislo = 12.34567;

Console.WriteLine("{0:F2}", cislo);
```
Výsledek: 12,35

### :computer: Formátování v interpolaci (nejčastější)
```
</>C#
int cena = 1500;

Console.WriteLine($"Cena je {cena:N0} Kč");  // N je číslo s oddělovači tisíců, 0 znázorňuje žádná desetinná místa
```
Výsledek: 1 500 Kč

### :computer: Zarovnání textu doprava
```
</>C#
Console.WriteLine($"{ "Ahoj",10}");  // 10 je šířka sloupce
```

### :computer: Zarovnání textu doleva
```
</>C#
Console.WriteLine($"{ "Ahoj",-10}");  
```
