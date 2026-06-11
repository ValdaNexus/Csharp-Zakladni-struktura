# Přetypování
Přetypování (casting) v C# znamená převod hodnoty z jednoho datového typu na jiný.  

**Implicitní přetypování (automatické)**\
    - C# ho provede samo, když nehrozí ztráta dat.
 ``` csharp
int a = 10;
double b = a; // int → double (automaticky)
 ```
**Explicitní přetypování (ruční)**\
    - Musíš ho napsat ty, protože může dojít ke ztrátě dat.

 ``` csharp
double a = 10.7;
int b = (int)a; // výsledek 10
 ```

## Konverze na číslo
Při programování často pracujeme se vstupy od uživatele.  

```
</>C#
  string vstup = Console.ReadLine();
```
Problém je, že metoda **ReadLine()** vždy vrací text (string), ale my často potřebujeme čísla (int, double, …).
Proto musíme provést konverzi (převod) ze stringu na číselný datový typ.




**Přetypování pomocí Convert**\
    - Bezpečnější varianta pro převody (hlavně stringy).

 ``` csharp
string text = "123";
int number = Convert.ToInt32(text);
 ```
**Parse**
 ``` csharp
string text = "456";
int number = int.Parse(text);
 ```
**TryParse (nejbezpečnější)**\
    - Když nastane chyba, program nespadne.
 ``` csharp
string text = "abc";
bool success = int.TryParse(text, out int number);
 ```
