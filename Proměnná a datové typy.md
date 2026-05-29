## Proměnná
Proměnná je místo v paměti, do kterého mohu ukládat jakoukoliv hodnotu (např. jméno, věk, hodnotu Pí aj).  
V C# má proměnná vždy určený datový typ, zálěží jakou hodnotu budeme do proměnné ukládat. Hodnotu v proměnné lze měnit.
Vytvoření proměnné se v programování říká **DEKLARACE**.

K deklaraci proměnné potřebujeme název proměnné a datový typ.

### Nejpoužívanější datové typy
  - string > neboli řetězec, ukládá text, musí být v uvozovkách
  - int > celé číslo
  - double > desetinné číslo
  - decimal > desetinné číslo
  - bool > logický typ, má pouze hodnotu TRUE nebo FALSE
  - char > jeden znak, musí být v apostrofech

### Celočíselné typy
![img](https://private-user-images.githubusercontent.com/288233596/599907844-c15b153e-73e2-44ec-9435-b1530e71c529.png?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3ODAwMzc2NTksIm5iZiI6MTc4MDAzNzM1OSwicGF0aCI6Ii8yODgyMzM1OTYvNTk5OTA3ODQ0LWMxNWIxNTNlLTczZTItNDRlYy05NDM1LWIxNTMwZTcxYzUyOS5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjYwNTI5JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI2MDUyOVQwNjQ5MTlaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT03N2E3NmYwMTg4OGJlNWNiNGE5OTFlNGI0MDI4ZjBjOWNlNDkzZWM3ZWE5MDM4M2Q2YjE0N2RlNTI4ZWYyYjgxJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZyZXNwb25zZS1jb250ZW50LXR5cGU9aW1hZ2UlMkZwbmcifQ.oluCi-DrGB3DbD-CVtWKTkBd-Z5bWBBLXhMANbiV_sM)
Nejpoužívanější:**int**  

### Desetinná čísla

![img](https://private-user-images.githubusercontent.com/288233596/599908160-344ed404-6693-4bc1-aecb-6d8a306fdfe2.png?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3ODAwMzc3MzgsIm5iZiI6MTc4MDAzNzQzOCwicGF0aCI6Ii8yODgyMzM1OTYvNTk5OTA4MTYwLTM0NGVkNDA0LTY2OTMtNGJjMS1hZWNiLTZkOGEzMDZmZGZlMi5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjYwNTI5JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI2MDUyOVQwNjUwMzhaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1iYjdjOTliZDc4ZjBiMGNlNDA4MDUxODE3ODdmYTdlMjJiZmE0YTEyMGFlNGZmNGI5MDg2YTBjZDZmMDI2MTNhJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZyZXNwb25zZS1jb250ZW50LXR5cGU9aW1hZ2UlMkZwbmcifQ.QbTau9rt4v2bZfyp_nXXIKgNsNNlPK7DtFL5rhgmAtM)
```
double > běžné výpočty (matematika, fyzika)      
float > málo místa v paměti (hry, grafika)     
decimal > peníze (vysoká přesnost)     
```


