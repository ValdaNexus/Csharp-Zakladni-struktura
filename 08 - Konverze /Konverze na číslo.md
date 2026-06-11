### Konverze na číslo v C#  
Při programování často pracujeme se vstupy od uživatele.  

```
</>C#
  string vstup = Console.ReadLine();
```
Problém je, že metoda **ReadLine()** vždy vrací text (string), ale my často potřebujeme čísla (int, double, …).
Proto musíme provést konverzi (převod) ze stringu na číselný datový typ.
