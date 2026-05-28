Po vytvoření projektu se nám zobrazí v editoru kódu automaticky vygenerovaný zdrojový kód. To je způsobeno zaškrtnutím *"Použít příkazy nejvyšší úrovně"* v rámci vytváření projektu.
Pro uživatele je to v úvodu programování výhodné, neboť vygenerované části jsou obtížné na pochopení. Tomu se budeme věnovat později, nicméně si prvky jednoduše vysvětlíme.   

```csharp
namespace MujPrvniKod
{
    internal class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("Hello, World!");
        }
    }
}
```

:mag:    Vysvětlení kódu
  - **namespace** neboli jmenný prostor, slouží k organizaci kódu   
  - **internal class Program** definuje třídu, internal říká, že třída je dostupná uvnitř projektu   
  - **static void Main(string[] args)** **main** je vstupní bod programu, **static** znamená, že není potřeba vytvářet objekt třídy, **void** je metoda, která nic nevrací, **string[] args** je pole argumentů z příkazového řádku
  - **Console.WriteLine("Hello, World!");** vypíše text do konzole

Nyní můžeme kód spustit pomocí tlačítka :arrow_forward: nebo pomocí funk a spustí se příkazový řádek neboli konzolové okno.
<img width="1114" height="622" alt="2" src="https://github.com/user-attachments/assets/5ba754f3-1915-4903-9c4f-2489ad9547cf" />   
V konzoli se vypsalo *"Hello, World!"*.Pod textem je cesta k souboru a ladící hláška z Visual Studia.   
Právě jste si spustili Váš první kód! :computer:


