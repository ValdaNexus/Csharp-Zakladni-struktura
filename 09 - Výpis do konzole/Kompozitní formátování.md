## Kompozitní formátování
Kompozitní formátování v C# je způsob, jak vkládat hodnoty do textu pomocí zástupných symbolů.  
Používá metodu string.Format() nebo Console.WriteLine() se speciálním zápisem {0}, {1}, {2} atd.

## Kdy se používá?
  - ve starších kódech
  - nebo když se používá string.Format()   
například: 
```
</>C#
string text = string.Format("Ahoj {0}", jmeno);
```

### 💻Základní příklad
```
</>C#
string jmeno = "Jan";
int vek = 20;

Console.WriteLine("Jmenuji se {0} a je mi {1} let.", jmeno, vek);
```
Výsledek: Jmenuji se Jan a je mi 20 let.

### 💻Další příklad
```
</>C#
string mesto = "Praha";
int pocet = 1200000;

Console.WriteLine("Město {0} má {1} obyvatel.", mesto, pocet);
```
Výsledek: Město Praha má 1200000 obyvatel.

### Jak to funguje?
  - {0} = první hodnota za textem
  - {1} = druhá hodnota
  - {2} = třetí atd.

Indexy nemusí být v pořadí, ale musí existovat odpovídající hodnota.
