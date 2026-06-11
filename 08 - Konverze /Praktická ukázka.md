### Praktické ukázky

## Jednoduchá (méně vhodná)
```
</>C#
Console.WriteLine("Zadej číslo:");
string vstup = Console.ReadLine();

int cislo = int.Parse(vstup);

Console.WriteLine("Zadal jsi: " + cislo);
```
## Jednoduchá (lepší volba, ale stále riziková)
```
</>C#
Console.WriteLine("Zadej první číslo:");    
int prvniCislo =int.Parse(Console.ReadLine());    // Užití parsování
//Když uživatel zadá nečíslo → spadne program (výjimka)

Console.WriteLine("Zadej druhé číslo:");
int druheCislo = Convert.ToInt32(Console.ReadLine());    // Užití třídy Convert
// Když je null, vrátí 0 (Parse by spadl)
// Null znamená, že proměnná má „prázdnou“ hodnotu

Console.WriteLine("Zadal jsi: " + prvniCislo + " a " + druheCislo);
```
## Modernější (doporučený) přístup

```
</>C#

```
