# Přetypování
Přetypování (casting) v C# znamená převod hodnoty z jednoho datového typu na jiný.

  1. **Implicitní přetypování (automatické)**\
    - C# ho provede samo, když nehrozí ztráta dat.
 ``` csharp
int a = 10;
double b = a; // int → double (automaticky)
 ```
  2. **Explicitní přetypování (ruční)**\
    - Musíš ho napsat ty, protože může dojít ke ztrátě dat.

 ``` csharp
double a = 10.7;
int b = (int)a; // výsledek 10
 ```
  3. **Přetypování pomocí Convert**\
    - Bezpečnější varianta pro převody (hlavně stringy).

 ``` csharp
string text = "123";
int number = Convert.ToInt32(text);
 ```
  4. **Parse**
 ``` csharp
string text = "456";
int number = int.Parse(text);
 ```
  5. **TryParse (nejbezpečnější)**\
    - Když nastane chyba, program nespadne.
 ``` csharp
string text = "abc";
bool success = int.TryParse(text, out int number);
 ```
