## Interpolace (nejmodernější)  
Interpolace řetězců je způsob, jak vkládat proměnné přímo do textu pomocí znaku $. Místo složitého spojování nebo indexování {0} používáš rovnou proměnné v textu.

### 💻Základní příklad
```
</>C#
string jmeno = "Jan";
int vek = 20;

Console.WriteLine($"Jmenuji se {jmeno} a je mi {vek} let.");
```
Výsledek: Jmenuji se Jan a je mi 20 let.

### 💻Součet čísel
```
</>C#
int a = 5;
int b = 3;

Console.WriteLine($"Součet je {a + b}");
```
Výsledek: Součet je 8


**Interpolace se používá nejčastěji, protože:**
  -  je nejpřehlednější
  -  dělá se nejméně chyb
  -  snadno se čte
  -  podporuje výpočty uvnitř {}
