# TAREA 1
## 1.	OBJETIVOS

	1.1	GENERAL: 
Analizar los 2 primeros capítulos del libro ¨Principios de circuitos eléctricos¨ de Floyd, con el objetivo de introducirse en los conceptos básicos de la electrónica.

	1.2	ESPECÍFICOS:

**a.**	Comprender el funcionamiento del Sistema Internacional de medidas con el fin de: representar cantidades grandes y pequeñas con notación científica; y el de reconocer prefijos y conceptos varios utilizados en el área de Ciencias Exactas.
		
**b.**	Identificar: las partes básicas de un circuito eléctrico, los tipos y valores de distintas resistencias, los riesgos eléctricos y las medidas de seguridad que se deben poner en práctica al momento de trabajar con electricidad.

**c.**	Definir conceptos como: átomo, carga eléctrica, voltaje, corriente y resistencia, fuente de voltaje, fuente de corriente, Tierra, etc. A fin de que estos conceptos sean de ayuda para el entendimiento de la materia de Fundamentos de Circuitos Eléctricos y subsiguientes.

## 2.	MARCO TEÓRICO (RESUMEN)

### CAPÍTULO 1: Cantidades y unidades
	
        	1–1 Unidades de medición
	
En 1875 se crea el ¨Système International d’Unités¨ para establecer estándares internacionales de medidas entre 18 países (a los cuales se les unirían más posteriormente.)

En SI (abreviatura de Système International d’Unités) se basa en 7 unidades base/fundamentales y 2 complementarias. La unidad eléctrica fundamental es el ampere(A) el cual se utiliza para medir corriente eléctrica(I), además este utiliza su definición en función del tiempo(t)(el segundo). Las demás medidas utilizadas en electrónica se llaman unidades derivadas ya que utilizan combinaciones de unidades fundamentales, por ejemplo, el volt(V) se define en función de m^2 * kg * s^-3 * A^-1, por tanto, es una unidad derivada (Ver tabla 1). 

![download](https://user-images.githubusercontent.com/93396250/140690292-a82a422c-b08a-447f-bd8a-e0165756fd62.jpg)

*Tabla 1. Unidades básicas en el SI*

Se utiliza un símbolo para representar el nombre de la cantidad y otro para identificar la unidad de medición (Ver tabla 2). 

![Cantidad Símbolo](https://user-images.githubusercontent.com/93396250/140690521-6703bbd1-f84e-477e-88b0-1d44d996de2c.JPG)

*Tabla 2. Cantidades eléctricas y unidades derivadas con símbolos SI.*
        
		1–2 Notación científica
	
La notación científica es muy util al momento de representar números grandes y pequeños ademas de realizar calculos que usen dichas cantidades. Se representa como el producto de un número y una potencia de diez. Por ejemplo, el 450000000 se representaria como 4.5 * 10^8 y el 0.0000056 como 5.6 * 10^-6 . A continuación se encuentra un mapa conceptual describiendo las operaciones básicas con notación científica.

![Jsjsjs](https://user-images.githubusercontent.com/93396250/140695337-f37fb022-df6c-4bf6-8fa0-3b04c9e99136.png)


        	1–3 Notación de ingeniería y prefijos métricos
		
[![Diagrama-en-blanco.png](https://i.postimg.cc/D0pXvGMj/Diagrama-en-blanco.png)](https://postimg.cc/bSbJLZ8k)
	
La notación en ingeniera al igual que en la matemática se usa para poder expresar de mejor manera cantidades o muy grandes o muy pequeñas, pero a diferencia de las matemáticas, la notación en ingeniera solo usa potencias de 10 que son múltiplos de 3.  Teniendo asi como ejemplo el numero 65000 que en notacion matematica seria represetado como 6.5*10^4 en notacion de ingenieria es 65*10^3.

Para poder nombrar a cada una de estas potencias múltiplos de 3 se usan prefijos métricos que sirven para expresar cada una de estas potencias, cabe recalcar que estos prefijos métricos se usan solo con números que tienen una unidad de medida tales como el voltaje, amperio, ohms, etc. También es importante mencionar que no todas las potencias múltiples de 3 tienen su prefijo métrico, solo las más comunes.
        	
		1–4 Conversiones de unidades métricas
	
A menudo resulta más útil convertir una cantidad que tiene un determinado prefijo métrico a otra, esto con el fin de facilitar operaciones matemáticas. La conversión de dichas unidades tiene 3 reglas principales las cuales son:

	1. Cuando se convierte de una unidad grande a una pequeña la coma se mueve hacia la derecha
	2. Cuando se convierte de una unidad pequeña a una grande la coma se mueve hacia la izquierda
	3. El número de espacios que la coma debe recorrer está definido por la diferencia entre las potencias de 10 de las unidades que se quiere convertir.

	
### CAPÍTULO 2: Voltaje, corriente y resistencia
	
		2–1 Estructura atómica

Todo aquello que nos rodea es considerado materia la cual se compone de átomos, y ellos a su vez de electrones, protones y neutrones. El átomo es la partícula más pequeña, que forma un elemento y logra mantener sus particularidades y propiedades.

![NUCLEO](https://user-images.githubusercontent.com/93826527/140783238-23247126-462c-4ffa-b8cf-758210c64efc.jpg)


Dentro del núcleo, las particulas están cargadas negativamente **(electrones)** y positivamente **(protones)**

 
		2–2 Carga eléctrica 
![Blank diagram (1)](https://user-images.githubusercontent.com/93826527/140828905-0a4947f2-df33-4671-ad64-7cd31a2209a4.png)


![kkk](https://user-images.githubusercontent.com/93826527/140829001-398ef093-b3ec-4c9f-913c-6991f6405353.png)


		2–3 Voltaje, corriente y resistencia 
        
![Blank diagram (2)](https://user-images.githubusercontent.com/93826527/140829036-46b4e8b8-d592-408d-90dd-ff4937e62c30.png)



## 3.	EXPLICACIÓN Y RESOLUCIÓN DE EJERCICIOS O PROBLEMAS
	
### CAPÍTULO 1: Problemas (pag. 13)
	
#### <p align=center> SECCIÓN 1–2 Notación científica
	
**1. La notación científica utiliza potencias de diez.**
	
	Verdadero
	
**3. Exprese los siguientes números en notación científica:**

	(a) 4350 = la coma se recorre 3 espacios hacia la izquierda. Por tanto se multiplica 4.35 * 10^3 
	
	(b) 12,010 = la coma se recorre 4 espacios hacia la izquierda. Por tanto se multiplica 1.201 * 10^4
	
	(c) 29,000,000 = la coma se recorre 7 espacios hacia la izquierda. Por tanto se multiplica 2.9 * 10^7
	
**5. Realice las siguientes operaciones:**

	(a) (1 * 10^5) + (2 * 10^5) = Tienen potencias iguales, por lo que se suma 1+2 y el resultado es 3 * 10^5
	
	(b) (3 * 10^6) (2 * 10^4) = Se multiplican los numeros y se suman las potencias, dando como resultado 6 * 10^10
	
	(c) (8 * 10^3) / (4 * 10^2) = Se dividen los numeros y se restan las potencias, dando como resultado 2 * 10^1
	
	(d) (2.5 * 10^(-6)) - (1.3 * 10^(-7)) = Se igualan las potencias, siendo estas (25 * 10^(-7)) - (1.3 * 10^(-7)) y se procede a restar los numeros, dando como resultado               23.7 * 10^(-7)
	
**7. Exprese cada uno de los números siguientes como un número decimal regular:**

	a) 2.5 * 10^(-6) = La potencia representa el numero de espacios que recorrio la coma, en este caso hacia la derecha por ser negativo. Para lo cual haremos lo inverso,              recuperaremos los espacios y obtendremos 0.0000025
	
	b) 5.4 * 10^(-9) = La potencia representa el numero de espacios que recorrio la coma, en este caso hacia la derecha por ser negativo. Para lo cual haremos lo inverso,              recuperaremos los espacios y obtendremos 0.0000000054
	
	c) 1.0 * 10^1 = La potencia representa el numero de espacios que recorrio la coma, en este caso hacia la inzquierda por ser positivo. Para lo cual haremos lo inverso,              recuperaremos los espacios y obtendremos 10
	
**9. Sume los números siguientes:**

	a) (9.2 *10^6) + (3.4 * 10^7) = Se iguala las potencias (92 * 10^6) + (34 * 10^6) y procedemos a sumar los numero, obteniendo 126 * 10^6 y eso es 1.26 * 10^8
	
	b) (5 * 10^3) + (8.5 * 10^(-1)) = Se iguala las potencias (50000 * 10^(-1)) + (8.5 * 10^(-1)) y procedemos a sumar los numero, obteniendo 5008.5 * 10^(-1) y eso es 	            
	5.0085 * 10^2
	
	c) (5.6 * 10^(-8)) + (4.6 * 10^(-9)) = Se iguala las potencias (56 * 10^(-9)) + (4.6 * 10^(-9)) y procedemos a sumar los numero, obteniendo 60.6 * 10^(-9) y eso es 6.06            
	* 10^(-8)
	
**11. Realice las siguientes multiplicaciones:**

	a) (5 * 10^3)(4 * 10^5) = Se multiplican los numeros y se suman los coeficientes, obteniendo 20 * 10^8
	
	b) (1.2 * 10^12)(3 * 10^2) = Se multiplican los numeros y se suman los coeficientes, obteniendo 3.6 * 10^14
	
	c) (2.2 * 10^(-9))(7 * 10^(-6)) = Se multiplican los numeros y se suman los coeficientes, obteniendo 15.4 * 10^(-15) y esto es 1.54 * 10^(-14)
	

#### <p align=center> SECCIÓN 1–3 Notación de ingeniería y prefijos métricos
	
**13. Exprese cada uno de los números siguientes en notación de ingeniería:**
	
	1. 89,000 = la coma se recorre 3 espacios hacia la izquierda (se quitan 3 ceros). Por tanto se multiplica por 10 elevado a la 3 = 89 * 10^3

	2. 450,000 = la coma se recorre 3 espacios hacia la izquierda = 450 * 10^3

	3. 12,040,000,000,000 = la coma se recorre 12 espacios hacia la izquierda = 12.04 * 10^12
   
	
**15. Exprese cada número en notación de ingeniería:**

	1. 0.000345 = la coma se recorre 6 espacios hacia la derecha (se aumentan 6 ceros). Por tanto se multiplica por 10 elevado a la -6 = 345 * 10^-6

	2. 0.025 = la coma se recorre 3 espacios hacia la derecha (se aumentan 3 ceeros) = 25 * 10^-3

	3. 0.00000000129 = la coma se recorre 9 espacios hacia la derecha (se aumentan 9 ceeros) = 1.29 * 10^-9
   
   

**17. Sume los números siguientes y exprese cada resultado en notación de ingeniería:**
	
	1. (2.5 * 10-3) + (4.6 * 10-3) = Las potencias estan igualadas, por lo que solo se suman los números sin sus potencias de diez ==> 2.5 + 4.6 = 7.1 
	y se pone la potencia de 10 original
	
		*Respuesta = 7.1 * 10^-3*

	2. (68 * 10^6 ) + (33 * 10^6) =  Las potencias estan igualadas, por lo que solo se suman los números sin sus potencias de diez ==> 68 + 33 = 101 
	y se pone la potencia de 10 original
	
		*Respuesta = 101 * 10^6*

	3. (1.25 * 10^6) + (250 * 10^3) = Se deben igualar las potencias. Por tanto, se transforma el  250 * 10^**3** a  0.25 * 10^**6** . 
	Con las potencias igualadas se puede realizar la suma de 1.25 + 0.25 = 1.50 . Se restablece la potencia de diez con lo que la respuesta 
	queda de la siguiente manera:
	
		*Respuesta = 1.50 * 10^6*
   
   

**19. Divida los números siguientes y exprese cada resultado en notación de ingeniería:**

	1. 50 / (2.2 * 10^3) ==> 50 * 10^0 / 2.2 * 10^3 ==> (50/2) * (10^0-3) ==> 22.72 * 10^-3  

		*Respuesta = 22.7 * 10^-3*

	2. (5 * 10^3) / (25 * 10^-6) ==> (5/25) * (10^3-(-6)) ==> 0.2 * 10^9 ==> Transformar a una potencia de diez menor, entonces:
	
		*Respuesta = 200 * 10^6*

	3. 560 * 10^3 / (660 * 10^3) = (560/660) * (10^3-3) ==> 0.84 * 10^0 ==> Transformar a una notación científica, entonces: 
	
		*Respuesta = 848 * 10^-3*
   
   

**21. Exprese cada número del problema 15 en amperes por medio de un prefijo métrico.**

	1. 0.000345 ==> su notación científica es 345 * 10^-6 ==> el prefijo de la potencia 10^-6 es "micro" y su símbolo es la letra ¨u¨ ==> 
	se reemplaza la potencia con el símbolo del prefijo y se le aumenta la A(amperes), entonces: 
	
		*Respuesta = 345 uA*

	2. 0.025 ==> su notación científica es 25 * 10^-3 ==> el prefijo de la potencia 10^-3 es "mili"  y su símbolo es la letra ¨m¨ ==> 
	se reemplaza la potencia con el símbolo del prefijo y se le aumenta la A(amperes), entonces: 
		
		*Respuesta = 25 mA*

	3. 0.00000000129 = su notación científica es 129 * 10^-9 ==> el prefijo de la potencia 10^-9 es "nano"  y su símbolo es la letra ¨n¨ ==> 
	se reemplaza la potencia con el símbolo del prefijo y se le aumenta la A(amperes), entonces: 
	
		*Respuesta = 1.29 nA*
   
   

**23. Exprese cada una de las cantidades siguientes por medio de prefijos métricos:**

	1. 3 * 10^-6 F ==> la potencia 10^-6 tiene su prefijo "micro" y su simbología es la letra ¨u¨ , entonces:
	
		*Respuesta = 3 uF*

	2. 3.3 * 10^6 Ω = la potencia 10^6 tiene su prefijo "mega" y su simbología es la letra ¨M¨ , entonces:
	
		*Respuesta = 3.3 MΩ*

	3. 350 * 10^-9 A = la potencia 10^-9 tiene su prefijo "nano" y su simbología es la letra ¨n¨ , entonces:
	
		*Respuesta = 350 nA*
   


**25. Exprese cada cantidad convirtiendo el prefijo métrico en una potencia de 10:**
   
	1. 7.5 pA ==> La "p" significa "Pico" y su potencia es 10^-12, entonces: 
		
		*Respuesta = 7.5 * 10^-12 A*

	2. 3.3 GHz ==> La "G" significa "Giga" y su potencia es 10^9, entonces:
	
		*Respuesta = 3.3 * 10^9 Hz*

	3. 280 nW ==> La "n" significa "nano" y su potencia es 10^-9 ==> 280 * 10^-9 => Transformando => 
	2.8 * 10^-7 W , entonces:
	
		*Respuesta = 2.8 * 10^-7 W*

   
	
#### <p align=center> SECCIÓN 1–4 Conversiones de unidades métricas
	

**27. Realice las conversiones indicadas:**
	
	a) 5mA a microamperes
	
![27 1](https://user-images.githubusercontent.com/93834732/140670690-efe544b9-c89b-4edd-999b-79f8bb4b2b5d.PNG)

	b) 3200 microwatts a miliwatts
   
![27 2](https://user-images.githubusercontent.com/93834732/140670934-4e2a7cd8-ed62-4f0d-add6-37a94ca820d7.PNG)

	c) 5000 kV a megavolts 
 
![27 3](https://user-images.githubusercontent.com/93834732/140674068-bf137594-921f-44e4-9a46-a5af08411353.PNG)

	d)  10 MW a kilowatts 

![Captura](https://user-images.githubusercontent.com/93834732/140675238-7d813f8d-b9d9-4156-a61c-20c2acf936e3.PNG)


**29. Sume las siguientes cantidades**
   
  	a) 50mA + 680 micro Amperios
   
![29 1](https://user-images.githubusercontent.com/93834732/140675536-dc89d8e7-4620-4e1c-ac70-069fd88ae643.PNG)

	b) 120 kilo Ohmios + 2.2 Mega Ohmios
	Se trasnforma de Kilo Ohmios a Mega Ohmios y se realiza la operacion

![29 3](https://user-images.githubusercontent.com/93834732/140675755-078c4a2d-3a97-475d-a806-3fbf826a34f6.PNG)

   	c) 0.02 micro Faradios + 3300 pico Faradios
   
   	Se trasnforma de pico faradios a micro faradios y se realiza la operacion
	
![29 2](https://user-images.githubusercontent.com/93834732/140676062-af1698be-d438-4df1-b5f4-947481b56641.PNG)
	
		
### CAPÍTULO 2: Problemas (pag. 64)
	
#### <p align=center> SECCIÓN 2–2 Carga eléctrica
	
**1.¿Cuál es la carga en coulombs del núcleo de un átomo de cobre?**
 
 	Es de 4.64*10^(-18) C
 
**3. ¿Cuántos coulombs de carga poseen 50*10^31 electrones?**	

	Un coulomb equivale a 6.24*10^18 electrones

![3](https://user-images.githubusercontent.com/93834732/140679859-afc8fc2f-c12b-4439-9e10-eac4a80b890b.PNG)
	
#### <p align=center> SECCIÓN 2–3 Voltaje, corriente y resistencia
	

**5. Determine el voltaje en cada uno de los siguientes casos:**

	a) 10 J/C
   
![5 1](https://user-images.githubusercontent.com/93834732/140680262-936267e1-4866-4639-bdd4-4c968301256b.PNG)

	b) 5 J/2 C
   
![5 2](https://user-images.githubusercontent.com/93834732/140680423-2f419fe5-5ace-4ea4-8641-cce3e6f5190c.PNG)

	c) 100 J/25 C
   
![5 3](https://user-images.githubusercontent.com/93834732/140680487-cee9af33-6a40-4e00-ab18-a51b31677e54.PNG)

**7.¿Cuál es el voltaje de una batería que utiliza 800 J de energía para mover 40 C de carga a través de
un resistor?**

	Se divide la cantidad de Joules para la candidad de coulombs

![7](https://user-images.githubusercontent.com/93834732/140680677-a9b06ed7-5bee-4637-86a0-18bb7b3b392d.PNG)

**9.Si un resistor con una corriente de 2 A a través de él convierte 1000 J de energía eléctrica en energía
calorífica en 15 s, ¿cuál es el voltaje a través del resistor?**

	Usando la formula de la intensidad y sabiendo que el tiempo es de 15 segundos, se puede despejar la cantidad de 
	coulombs, usando los coulombs y teniendo la cantidad de Jouls, se puede calcular el voltaje

![9](https://user-images.githubusercontent.com/93834732/140681474-3b88e173-4d3e-47b0-a751-e692228a47d7.PNG)

**11.Seis décimos de coulomb pasan por un punto en 3 s. ¿Cuál es la corriente en amperes?**

![11](https://user-images.githubusercontent.com/93834732/140682140-f634637d-19e0-4af0-9a89-4e86af1b3c36.PNG)

**13.¿Cuántos coulombs pasan por un punto en 0.1 s cuando la corriente es de 1.5 A?**

![13](https://user-images.githubusercontent.com/93834732/140681988-baf34eb4-c82f-4109-aa9c-bf8090c7cc96.PNG)

**15.Determine la conductancia para cada uno de los siguientes valores de resistencia:**

   a) 5 Ohmios

![15 1](https://user-images.githubusercontent.com/93834732/140682261-84cfd7b8-3ff0-45fb-acff-4101ec7c4dcf.PNG)

   b) 25 Ohmios

![15 2](https://user-images.githubusercontent.com/93834732/140682331-bac6d4ba-b0c8-446c-90de-113e86d810b2.PNG)

   c) 100 Ohmios
  
![15 3](https://user-images.githubusercontent.com/93834732/140682377-49725228-29d9-4fc8-868b-2cd7bb9157b6.PNG)
	
	
	
#### <p align=center> SECCIÓN 2–4 Fuentes de voltaje y de corriente
	
**17.Enliste cuatro fuentes de voltaje comunes.**

	Baterías, Termopares, Sensores Piezoeléctricos, Generador
	
**19.¿Cómo difiere una fuente electrónica de potencia de las demás fuentes de voltaje?.**

	La principal diferencia es que esta fuente de potencia usa corriente alterna como fuente de energía, para luego transformarla en corriente directa
	
#### <p align=center> SECCIÓN 2–5 Resistores

**21. Determine los valores de resistencia y tolerancia para los siguientes resistores de 4 bandas**

	a) rojo = 2 
	
	   violeta = 7 
	   
	   naranja = *1000
	   
	   oro = +/- 5%
	   
	   27 kΩ +/- 5%
	   
	b) cafe = 1
	   
	   gris = 8
	   
	   rojo = *100
	   
	   plata = +/- 10%
	   
	   1.8 kΩ +/- 10%
	   
**23. Determine las bandas de color para cada uno de los siguientes valores de 4 bandas y 5% de tolerancia:**

	a) 330Ω 
	
	   Primer banda = Naranja 
	   
	   Segunda banda = Naranja
	   
	   # de ceros = Cafe
	   
	   Tolerancia = Dorado
	   
	b) 2.2 kΩ 
	
	   Primer banda = Rojo
	   
	   Segunda banda = Rojo
	   
	   # de ceros = Rojo
	   
	   Tolerancia = Dorado
	   
	c) 56 kΩ
	
	   Primer banda = Verde
	   
	   Segunda banda = Azul
	   
	   # de ceros = Naranja
	   
	   Tolerancia = Dorado
	   
	d) 100 kΩ
	
	   Primer banda = Cafe
	   
	   Segunda banda = Negro
	   
	   # de ceros = Amarillo
	   
	   Tolerancia = Dorado
	   
	e) 39 kΩ
	
	   Primer banda = Naranja
	   
	   Segunda banda = Blanco
	   
	   # de ceros = Naranja
	   
	   Tolerancia = Dorado
	   
**25. Determine las bandas de color para cada uno de los siguientes resistores de 4 bandas. Asuma que cada resistor tiene una tolerancia del 5 por ciento.**

	a) 0.47 Ω 
	
	   Primer banda = Amarillo
	   
	   Segunda banda = Violeta
	   
	   # de ceros = Plateado
	   
	   Tolerancia = Dorado
	   
	b) 270 kΩ 
	
	   Primer banda = Rojo
	   
	   Segunda banda = Violeta
	   
	   # de ceros = Amarillo
	   
	   Tolerancia = Dorado
	   
	c) 5.1 MΩ 
	
	   Primer banda = Verde
	   
	   Segunda banda = Cafe
	   
	   # de ceros = Verde
	   
	   Tolerancia = Dorado
	   
**Determine las bandas de color para cada uno de los siguientes resistores de 5 bandas. Asuma que cada resistor tiene tolerancia del 1 por ciento.**

	a) 14.7 kΩ
	
	   Primer banda = Cafe
	   
	   Segunda banda = Amarillo
	   
	   Tercera banda = Violeta
	   
	   # de ceros = Rojo
	   
	   Tolerancia = Cafe
	   
	   b) 39.2 Ω
	
	   Primer banda = Naranja
	   
	   Segunda banda = Blanco
	   
	   Tercera banda = Rojo
	   
	   # de ceros = Dorado
	   
	   Tolerancia = Cafe
	   
	   c) 9.76 kΩ
	
	   Primer banda = Blanco
	   
	   Segunda banda = Violeta
	   
	   Tercera banda = Azul
	   
	   # de ceros = Cafe
	   
	   Tolerancia = Cafe
	   
**29. ¿Cuál es la resistencia indicada por 4K7?**

	Primer digito = 4
	
	Decimal = 7
	
	4.7 KΩ


		
#### <p align=center> SECCIÓN 2–6 El circuito eléctrico
	
**31. Trace la trayectoria de la corriente en la figura 2-69(a) con el interruptor en la posición 2.**
	
<p align=center> Respuesta: A través de la lámpara 2
		
![31](https://user-images.githubusercontent.com/93396250/140863057-a7c2b8ef-e489-48cc-83c9-9b16883598d5.JPG)

	
**33. En la figura 2-69, solamente hay un circuito en el cual es posible encender todas las lámparas al mismo tiempo. Determine cuál es este circuito.**

<p align=center> Respuesta: Circuito (b)
		
![33](https://user-images.githubusercontent.com/93396250/140857420-9150554b-7aaf-48e2-9343-7db0040e3c3a.JPG)


**35. Disponga un arreglo de interruptor mediante el cual se puedan conectar dos fuentes de voltaje (VS1 y VS2) al mismo tiempo a cualquiera de dos resistores (R1 y R2) como sigue:**
	
	Primero se realiza la conexion de ¨VS1( tensión de salida) conectada a R1(resistencia) y VS2 conectada a R2¨ implementando un interruptor 
	para que ahora el circuito sea ¨VS1 conectada a R2 y VS2 conectada a R1¨. Para construir el circuito necesitaremos 2 fuentes de corriente, 
	2 resistores y 1 interruptor del tipo doble polo doble tiro. Además todas estan conectadas a tierra, creando asi una conexión equipotencial.

![35](https://user-images.githubusercontent.com/93396250/140863190-01d83f71-ba55-467c-9a6f-03e8e72b5d46.jpg)
	
	
#### <p align=center> SECCIÓN 2–7 Mediciones de circuito básicas


**37. Muestre la colocación de un amperímetro y un voltímetro para medir la corriente y el voltaje de fuente en la figura 2-72.**

	El voltaje se mide con un Voltímetro conectado en paralelo.
	La corriente se mide con un Amperímetro conectado en serie.
	
![37](https://user-images.githubusercontent.com/93396250/140864714-d933002c-dc52-47e3-9938-2e4b6a9f894b.JPG)


**39. En la figura 2-73, ¿cuánto voltaje indica cada medidor cuando el interruptor está en la posición 1? ¿En la posición 2?**
	
	Cuando el interruptor está en la posición 1 los voltímetros(medidores) indicaran que V1 = 0 V y V2 = Vs
	Cuando el interruptor está en la posición 2 los voltímetros(medidores) indicaran que V1 = VS y V2 = 0 V
	
![2 70](https://user-images.githubusercontent.com/93396250/140864866-0f82de2d-cde6-489f-9f27-3a6fea35f433.JPG)
	

**41. En la figura 2-70, muestre la colocación apropiada de los amperímetros para medir la corriente a través del resistor y la que sale de la batería.**
	
	El voltaje se mide con un Voltímetro conectado en paralelo.
	La corriente se mide con un Amperímetro conectado en serie.
	Sabiendo esto se puede proceder a la colocación de los mismos.
	
![41](https://user-images.githubusercontent.com/93396250/140866347-7379a642-a6f3-4fba-9597-f792d88b6cfe.jpg)


**43. ¿Cuál es la lectura de voltaje del medidor mostrado en la figura 2-74?**

	El voltaje es de 125 V
	
![image](https://user-images.githubusercontent.com/93396250/140867275-96bfb01c-bade-49de-88f1-2f8e0cb28dc6.png)

	
**45. Determine la resistencia indicada por cada una de las siguientes lecturas y ajustes de intervalo de ohmmetro:**
	
	(a) manecilla en 2, ajuste de intervalo en *10
		R: La resistencia es de 20 Ω
	(b) manecilla en 15, ajuste de intervalo en *100,000
		R: La resistencia es de 1.50 MΩ
	(c) manecilla en 45, ajuste de intervalo en *100
		R: La resistencia es de 4500 Ω

**47. Indique en qué forma conectaría el multímetro de la figura 2-75 al circuito de la figura 2-76 para medir cada una de las siguientes cantidades. Incluya la función y el intervalo apropiados en todos los casos.**
	
	(a) I1 (b) V1 
	
![47 A yB](https://user-images.githubusercontent.com/93396250/140868353-5bd862e2-347b-4523-809e-46f4f8f3e372.jpg)

	
	(c) R1
	 Para medir la resistencia se conecta entre los dos extremos de la misma, estando ésta desconectada del circuito eléctrico.
	
![47 c](https://user-images.githubusercontent.com/93396250/140868894-b49e18b1-910d-418e-b40d-d86ac465bac3.jpg)


## 4.	VIDEO
	
	Link del video ¨Informe tarea 1¨, en dondé se explican 4 ejercicios vistos en la Tarea #1 :
	
https://youtu.be/2iV6VzArCmY
	
	
[![Presentación Tarea 1](https://img.youtube.com/vi/2iV6VzArCmY/0.jpg)](https://www.youtube.com/watch?v=2iV6VzArCmY)
	
## 5.	CONCLUSIONES
        
En conclusión, podemos decir que la notación científica en la ingeniera es de suma utilidad ya que nos facilita el trabajo con números o muy grandes o muy pequeños, facilitando asi los cálculos matemáticos, gracias a esto se han podido crear los prefijos que se usan normalmente en ingeniera.

Adicional a esto se ha podido identificar las partes más importantes de un circuito, tales como los conductores y las resistencias, etc. Así mismo se aprendió el código de colores de las resistencias el cual es útil a la hora de trabajar con resistencias específicas y poder identificarlas fácilmente.

Finalmente se redescubrió los conceptos de átomo, carga eléctrica, voltaje, corriente y resistencia, fuente de voltaje, fuente de corriente, Tierra, etc. Los cuáles serán parte fundamental en el entendimiento de cómo trabajan los circuitos eléctricos y electrónicos

## 6.	BIBLIOGRAFÍA

Floyd, T. L. (2007). PRINCIPIOS DE CIRCUITOS ELÉCTRICOS - Octava edición. México: PEARSON EDUCACIÓN.

