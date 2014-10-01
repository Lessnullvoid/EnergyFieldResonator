EnergyFieldResonator
====================

Programa que genera frecuencias de entre 90- 243 Hz. Relacionadas al estudio de "Electrophotonic Analysis"

De acuerdo al estudio de análisis electrofotónico del Dr. Konstantin Korotkov, el cuerpo humano es capaz de emitir energía radiante que se encuentra en un rango entre los 380 y 750nm (longitud de onda). La electrofotónica ha encontrado 7 puntos principales de emisión de esta energía ubicados en las siguientes glándulas: 
 
	⁃	Corticoadrenales
	⁃	Gónadas
	⁃	Páncreas 
	⁃	Paraganglios supracardiacos / Timo 
	⁃	Tiroides / paratiroides 
	⁃	Pituitaria 
	⁃	Pineal
 
Estas fuentes de emisión energética coinciden con los puntos conocidos como chakras dentro de las cosmovisiones del hinduismo, la teosofía y el gnosticismo. Chakra significa "rueda" en sánscrito y fueron los vedas quienes utilizaron este término para denominar los centros energéticos del cuerpo humano.

De acuerdo a estos las funciones principales de los chakras son:
 
	1.	Revitalizar el cuerpo aural o energético y con ello el cuerpo físico.
	2.	Provocar el desarrollo de distintos aspectos de la autoconciencia, pues cada chakra está relacionado con una función psicológica específica.
	3.	Transmitir energía entre los niveles aurales ya que cada capa progresiva existe en octavas de frecuencia siempre crecientes.
 
De esta forma cuando el funcionamiento de los chakras es normal, cada uno de ellos estará abierto, girando en el sentido de las manecillas del reloj para metabolizar las energías particulares que necesita del campo de energía universal (energía que también se ha llamado chi, prana u orgón). En cambio, cuando el chakra gira en sentido contrario a las agujas del reloj, la corriente fluye del centro hacia fuera interfiendo el metabolismo. Por tanto, se dice que el chakra está cerrado o bloqueado.
 
Korotkov logra estos descubrimientos a partir del uso de la Bioelectrografía, una técnica de diagnóstico y seguimiento del estado informacional de la energía humana que utiliza la visualización de descarga de gas computarizado (GDV), basadas en el método Kirlian. A partir de esta técnica ha sido posible agrupar en rangos de longitud de onda y herzios cada una de las emisiones de estas glándulas fuente de energía radiante. 
 
Utilizando esta información trabajé en el desarrollo de una aplicación programada en PureData la cual busca estimular cada uno de estos puntos utilizando el principio de resonancia. El patch está integrado por 7 osciladores, cada oscilador presenta un rango de variación en hertzios y en longitud de onda.
 

	⁃	Corticoadrenales: Nota B, NM(380-280)  Hz(179-243)
	⁃	Gónadas: Nota A, NM(430-390) Hz(158-174)
	⁃	Páncreas: Nota G, NM(480-460) Hz(142-148)
	⁃	Paraganglios: Nota F, NM(520-490)  Hz(128-139)
	⁃	Tiroides: Nota E, NM(580-550)  Hz(117-124)
	⁃	Pituitaria: Nota D, NM(640-590) Hz(106-115)
	⁃	Pineal: Nota C, NM(750-650) Hz(90-104)
 
 
El RNG (random number generator) desarrollado también en PureData, que utiliza los datos del Noosphera de Princeton conectados a los osciladores. Los generadores de números aleatorios (RNGs) de Noosphera basados en túnel cuántico, producen secuencias completamente impredecibles de ceros y unos. Pero cuando un gran evento sincroniza los sentimientos de millones de personas, las red de generadores de números aleatorios muestra estructuras sutiles. Cuando la conciencia humana se vuelve coherente, el comportamiento de los sistemas aleatorios puede cambiar. 
 
En este caso el generador RNG dentro Energy Field Resonator utiliza los datos de la red de Noosphera en tiempo real, a partir de esto los osciladores disparan en momentos distintos coordinados por los valores provenientes de esta red. 
 



 