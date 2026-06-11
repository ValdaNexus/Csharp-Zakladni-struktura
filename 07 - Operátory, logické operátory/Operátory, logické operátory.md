# Základní operátory
Základní symboly pro jednotlivé operace.
### Aritmetické   
  -  \+ \- \* /
  -  %(modulo) zbytek po celočíselném dělení\
  -  příklad:\
    int x = 10;\
    int y = 3;\
    int z = x % y;   
    z = 1;

### Logické (boolenovské)
Výstupem logických operátorů je hodnota TRUE nebo hodnota FALSE\

| Operátor | Název |  Výraz v C# | Význam | Výsledek je *true*, když.. | Příklad
| ----------- | ----------- | ----------- | ----------- | ----------- | ----------- |
| `&&` | AND | `a && b` | "A zároveň" | obě podmínky jsou pravdivé |  x > 10 && y > 10
|`\|\|` | OR | `a \|\| b` | "Nebo" | alespoň jedna podmínka je pravdivá | x > 10 || y > 10
| `!` | NOT | `!a`| "Ne" | výraz je nepravda | !(x > 10)

  - && AND (a zároveň)   
    - znak ampersand **&&** (pravý alt + C)
    - obě podmínky musí platit
   
  - || OR (nebo)
    - svislík **||** (pravý alt + W)
    - alespoň jedna musí být TRUE, jinak je výsledek FALSE
   
  - ! NOT (negace)
    -  vykřičník **!**
    -  otočí neboli zneguje hodnotu        

### Relační
  - \>, >=, \<, <=, !=, ==
  - větší, větší rovno, menší, menší rovno, nerovná se, rovná se

### Další operátory
  - \+ sloučení řetězců
  - ++ inkrementace, -- dekrementace
  - = přiřazení

