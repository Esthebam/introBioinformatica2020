# TP 3 - El juego de la vida - Introducción a la Bioinformática

#### RETO I: Enumerá las diferencias que existen entre una célula procariota y eucariota.

- Las procariotas son más pequeñas.
- Las células procariotas no tienen un núcleo definido y su material genético se encuentra disperso en el citoplasma
- Las células eucariotas tienen membrana nuclear.
- Las eucariotas tienen reproducción sexual y asexual, en cambio las procariotas solo asexual.
- La división celular procariota es directa.
- Las células eucariotas tienen citoesqueleto.

#### RETO II: Crea un programa sencillo en algún lenguaje de programación que conozcas que imprima una cadena de ARN codificante para el siguiente péptido (cadena corta de aminoácidos).

##### Sec1: 'ATVEKGGKHKTGPNEKGKKIFVQKCSQCHTVLHGLFGRKTGQA'

```
peptido = "ATVEKGGKHKTGPNEKGKKIFVQKCSQCHTVLHGLFGRKTGQA"
tabla = {
    'V':'GUA','A':'GCU',
    'L':'CUC','P':'CCG',
    'T':'ACG','G':'GGA',
    'K':'AAA','S':'AGU',
    'w':'UGG','C':'UGC',
    'H':'CAC','N':'AAU',
    'F':'UUU','Q':'CAA',
    'I':'AUA','Y':'UAU',
    'R':'AGA','D':'GAC',
    'M':'AUG','E':'GAA'
}

print("".join(list(map(lambda x: tabla[x], peptido))))
```

#### RETO III: Crea un programa sencillo en algún lenguaje de programación que conozcas que permita identificar las regiones promotoras de un gen, en una secuencia dada de ADN, considerando que tal región comienza y termina en con la caja TATA.

```
#Denominada caja TATA consistente en una secuencia de nucleotidos 'TATAAA'
#Por lo que tomamos TAT = V y AAA = Q

peptido = "ATVEKGGKHKTGPNEKGKKIFVQKCSQCHYKTVLHGLFGRKTGQA"

tata = peptido.find("VQ")

res = ""

#Se suma dos para avanzar dos posiciones para empezar a contar desde ahi
for i in range(tata + 2, len(peptido)):
    res = res + peptido[i]

print(res)
```

#### RETO IV: Diseñá un juego de mesa o un videojuego (hecho con la herramienta que más te guste) temático sobre expresión génica, con sus reglas y resúmen. Tené en cuenta que lo vas a tener que compartir con la clase. ¡El cielo es límite, a divertirse!

[Ribosome Attack!](https://github.com/gasvel/ribosome-attack)