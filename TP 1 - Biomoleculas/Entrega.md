# TP 1 - Biomoléculas - Introducción a la Bioinformática

#### RETO I: ¿Podrías buscar un ejemplo de macromoléculas que almacenen información sobre la ‘identidad’ de un organismo dado?

*Los ácidos nucleicos son macromoléculas que guardan identidad de los organismos. Un ejemplo es el ADN.*

#### RETO II: Proponé una forma de expresar la información contenida en la estructura primaria de las proteínas usando tipos de datos de los lenguajes de programación que conocés.

*La estructura primaria de las proteínas se basa en los aminoácidos (hay una tabla periódica de 20 aminoácidos, y cada uno se representa con 3 letras). Cada aminoácido se simplifica en una letra sola, un tipo de dato adecuado para representrar dicha estructura sería un String.*

#### RETO III: ¿ En qué tipo de datos podrías expresar la información de la estructura terciaria proteica?

*Existen dos tipos de estructura terciaria para las proteínas: fibrosa o regular. Al ser sólo dos valores podrían incluso expresarse como booleanos. Otra forma es expresarlos también con un String.*

#### RETO IV: Rosalind Franklin es una científica muy relevante, que tuvo menos reconocimiento del merecido. ¿Cuáles fueron sus contribuciones en este campo? ¿Qué nos cuenta su historia acerca del mundo de la ciencia?

*Rosalind Franklin fue una científica Inglesa que realizó grandes contribuciones a la ciencia en la época de la Segunda Guerra Mundial. Mediante el estudio bajo la técnica de difracción de Rayos X pudo describir la estructura del ADN, descubriendo así la forma de "doble hélice" de las moléculas.
Hay quienes sostienen incluso que ella habia llegado a la conclusion de la estructura helicoidal unos meses antes de la publicacion realizada por Watson y Crick. Pero que por no haber realizado ninguna publicación aún con los resultados de sus investigaciones e imágenes tomadas, que resultaron fundamentales para sostener la propuesta, no logró tener el reconocimiento merecido.*

#### RETO V: Proponé en pseudocódigo un programa que prediga la estructura secundaria que adoptará cada residuo de la secuencia proteica dada, especificandola como H (si es una hélice), B (si es una hoja beta plegada) y L (si es un bucle o loop).

```
print("Ingrese la secuencia proteica:")
secuencia = input()
prediccion = ''
for i in secuencia:
    if (i =='G') or (i =='S') or (i =='D') or (i =='N') or (i =='P'):
        prediccion += 'L'
    elif (i =='V') or (i =='I') or (i =='F') or (i =='Y') or (i =='W') or (i =='T') or (i =='R'):
            prediccion += 'B'
    else:
            prediccion += 'H'

print(prediccion)
```

#### RETO VI: ¿Qué hace distintos a dos individuos de una especie? Propone una forma de corroborar tu respuesta realizando un diagrama de un posible método computacional para dicho fin.

*Cada individuo posee una secuencia de ADN única e irrepetible, y esto es lo que nos hace diferentes a nivel molecular.*

```
def esDistinto(adn_1, adn_2):
  for idx, val in enumerate(adn_1):
    if(val != adn_2[idx]):
      return True

  return False
```