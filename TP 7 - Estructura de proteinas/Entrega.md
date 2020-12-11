# TP 7 - Estructura de proteínas - Introducción a la Bioinformática

#### Las estructuras de las proteínas pueden ser muy diversas. Se las puede clasificar por su contenido en estructuras secundarias y según su cantidad de dominios. ¿Cómo podrías describir la estructura de esta proteína? Realizá la misma descripción pero para la proteína 1THJ, 3OGB.

1THJ: *Estructura secundaria con alfa-hélices, beta-plegadas y loops. Tiene dos túneles bien definidos y un bolsillo.*

3OGB: *Estructura secundaria de alfa hélices y loops. Tiene por lo menos un túnel.*

#### Estudiá la proteína 2CPE. ¿Qué tipo de proteína es?

*Tiene un núcleo concentrado pero con diferentes ramificaciones.*

#### ¿Cómo la describirías? Utilizá el comando “set all_states, on” para ver todos los estados conformacionales estimados para esa estructura.

*Consta de 2 alfa-hélices, 4 beta-plegadas y 7 loops.*
*No se ven túneles.*

#### Compará el espacio conformacional de la 2CPE con la de la estructura de la mioglobina (1MYF).

*La mioglobina tiene un espacio HEM, La 2CPE no. Además la mioglobina no tiene estructura beta-plegada, solo 7 alfa-hélices y 8 loops.*

#### Utilizando el modo secuencia, seleccioná la HIS 64. Mostrala en formato stick o lines. ¿Qué función podría llegar a tener?

*La proteína 2CPE se relaciona con el ARN, y al ser un anión se debe unir con otro aminoácido catión.*

#### ¿Y la HIS 93?

*Une la HEM con la proteína.*

#### RETO I: Estas estructuras difieren de las estructuras sobre las que venimos trabajando en su determinación. Como habrás notado estas fueron obtenidas mediante la técnica de MNR, ¿Pero en qué consiste esta técnica?

*La técnica NMR (nuclear magnetic resonance) consiste en generar fuertes campos magnéticos alrededor de una molécula produciendo que el núcleo de algunos átomos actúen como pequeños imanes.*
*Posteriormente se aplican ondas de radiofrecuencias de amplio espectro que hacen resonar al núcleo a su frecuencia especifica.*

#### Cálculo de la distancia promedio de un puente de hidrógeno.

*La medición entre el hidrógeno y el nitrógeno es de 1.0. La medición entre el oxígeno y el hidrógeno es de 3.2. Para ILE, la medición entre el oxígeno y el hidrógeno es de 2.6 y la medición entre el hidrógeno y el nitrógeno es de 0.9 Para PHE, la medición entre el hidrógeno y el nitrógeno es de 1 y la medición entre el oxígeno y el hidrógeno es de 2.6.*

#### RETO II: Investigá en qué consisten las interacciones puentes de hidrógeno, π-π y π-catión y qué aminoácidos podrían intervenir en dichas interacciones.

Interacción π-π: *Son un tipo de interacción no covalente que involucra sistemas π . El sistema π rico en electrones puede interactuar con un metal (catiónico o neutro), un anión, otra molécula e incluso otro sistema π.*

Interacción π-catión: *Es una interacción molecular no covalente entre la cara de un sistema π rico en electrones (vg. benceno, etileno) con un catión adyacente (vg. Li+, Na+). Esta interacción inusual es un ejemplo de enlace no covalente entre un monopolo (catión) y un cuadrupolo (sistema π).*

#### Identificación de interacciones π-π y π-catión.

*Y, F y W forman los residuos aromáticos la proteína 1A7E.*

#### Utilizado la estructura de la anhidrasa carbónica 1THJ y la opción Select en el Menú Edit: ¿Cuántas subunidades (cadenas) tiene la estructura nativa?

*3 estructuras definidas.*

#### ¿Tiene heteroátomos esta molécula? ¿Cuáles?

*Oxigeno y Zinc.*

#### ¿Los residuos que unen el Zinc pertenecen a la misma subunidad?

*No. El zinc actúa como ligando entre las estructuras de la proteína.*

#### Utilizando el programa Pymol estudiá la estructura terciaria y cuaternaria de la proteína 4AUI. Determiná la superficie, localizá ligandos e identifícalos.

Estructura terciaria: *La estructura tiene 31 átomos con ligandos inorgánicos (PO4 y MG) y 93 átomos con ligandos orgánicos (ATP).*

Estructura cuaternaria: *La proteína está compuesta por 3 subestructuras; solo una de ellas tiene el ligando MG y 2 grupos fosfatos.*

#### Utilizando el programa (o servidor https://mole.upol.cz/) MOLE estudiá los túneles asociados al sitio activo de las estructuras 1THJ y 1F90.

*La 1THJ tiene 8 cavidades y 20 túneles. La 1F90 tiene 6 cavidades y 10 túneles.*

#### El EGFR es uno de los principales marcadores de cáncer de pulmón. Utilizando la sesión de Pymol estudiá los pockets. 1M14 es un confórmero activo y 3W32 uno inactivo. Compará el sitio activo de ambos confórmeros así como también los tamaños de los pockets.

*La 1M14 tiene 25 pockets. La 3W32 tiene 22 pockets.*
*Los pockets de la proteina 1M14 ocupan más espacio de la superficie. Los pockets de la proteina 3W32 tienen mayor superficie por dentro de la proteina.*

#### ¿Encontrás algún/os túnel/es en la proteína donde pueda unirse algún fármaco?

*23 túneles.*

####  ¿Qué residuos se encuentran en dicha cavidad?

*Pymol los llama STP y son 22.*

#### RETO III: Investigá en qué consiste el docking, en qué ideas basa su funcionamiento.

*El docking o acoplamiento molecular es una técnica de mecánica molecular usada para predecir energías y modos de enlace entre proteínas y ligandos. Este método tiene un rol muy importante en el diseño racional de fármacos. Para tal fin entran en juego una serie de procesos químicos gobernados por leyes físicas, entre ellas las que tienen que ver con la energía que se consume o libera en tal proceso. En la actualidad contamos con sofisticadas técnicas experimentales de cuyos resultados se extrae información tridimensional tanto de las proteínas como de los ligandos.*

#### ¿Dónde se une el inhibidor?

*Se encuentra en un túnel.*

#### ¿Coincide con el túnel que propusiste anteriormente?

*Si coincide.*

#### ¿Dada esta inspección ocular cómo creés que actúa el inhibidor? Usando el play de la botonera, observá las distintas conformaciones del ligando o inhibidor.

*El ligando "gira" dentro del túnel sin salirse.*

#### Observá las distintas regiones de estructura secundaria, ¿todas son de igual cantidad de residuos?

*3F8V tiene más residuo helicoidal que 4LMZ.*

#### ¿Se requieren más o menos residuos para formar una alfa hélice que un loop? ¿Por qué?

*Una estructura secundaria de alfa hélice necesita 3.6 residuos de AA por vuelta.*