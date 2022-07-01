# TAREA-4
PARCIAL 2

#### UNIVERSIDAD DE LAS FUERZAS ARMADAS ESPE
##### CIRCUITOS ELÉCTRICOS
##### NOMBRE: Damaris Rivera.
##### NRC: 7318                                                                                                                  
##### FECHA: 01 – 07 – 2022

## 1. Objetivos 
  
### 1.1 Objetivo General
        
Aprender sobre los Circuitos en Serie - Paralelo y conocer los Teoremas de Circuitos y Conversiones para resolver diversos circuitos utilizando conceptos ya aprendidos con anterioridad.
	
### 1.2 Objetivos Específicos
        
- Realizar los problemas planteados en cada capítulo, indicando el proceso que ha sido utilizado.
- Hacer mapas mentales donde se utilice ideas cortas que expliquen los conceptos de cada tema y permitan un entendimiento rápido del mismo.
	
## 2. Marco Teórico

#### CAPITULO 7

![CIRCUITOS_EN_SERIE_-_PARALELO](https://user-images.githubusercontent.com/105671763/176796152-80a7a02e-0b0f-4d8f-a736-83460c08b42d.png)

#### CAPITULO 8 
![TEOREMAS_DE_CIRCUITOSY_CONVERSIONES](https://user-images.githubusercontent.com/105671763/176816913-9a771115-6f15-4a00-9ff4-34708eff9da8.png)

## 3. Explicación y resolución de ejercicios 

#### CAPITULO 7 

#### PROBLEMAS 

##### *SECCIÓN 7-1 	Identificación de relaciones en serie-paralelo*

##### 2. Visualice y trace los siguientes circuitos en serie-paralelo:
	(a) Una combinación en paralelo de tres ramas, cada rama con dos resistores en serie.
	
<img width="518" alt="image" src="https://user-images.githubusercontent.com/105671763/176853582-dba5e74e-2b3b-4fad-89e9-d97d037dc2ca.png">

	(b) Una combinación serie de tres circuitos en paralelo, cada circuito con dos resistores
	
<img width="430" alt="image" src="https://user-images.githubusercontent.com/105671763/176854405-2f44b1a6-3cc6-49b6-963d-67649dae5e42.png">

##### 4. En cada uno de los circuitos de la figura 7-63, identifique las relaciones en serie-paralelo de los resistores vistas desde la fuente.

![image](https://user-images.githubusercontent.com/105671763/176820126-80aab2f4-1e65-471f-8993-141031ea63c2.png)

	(a) R3 || R4 + R1 + R2
	(b) R1 + R4 || R3 + R2
	(c) R6 + R7 + R5 || R1 + R2 + R3 || R4 + R8

##### 6. Desarrolle un diagrama esquemático de la tarjeta de circuito impreso de doble cara mostrada en la figura 7-65, y marque los valores de resistor.

![image](https://user-images.githubusercontent.com/105671763/176820229-a67a9694-40a4-4a1f-91ab-621f9a5f4d13.png)

<img width="487" alt="image" src="https://user-images.githubusercontent.com/105671763/176860893-7da5a6ef-02d9-4f38-85cd-0a2265fdf260.png">

##### *SECCIÓN 7-2 	Análisis de circuitos resistivos en serie-paralelo*

##### 8. Un cierto circuito se compone de dos resistores en paralelo. La resistencia total es de 667 Ω. Uno de los resistores es de 1.0 kΩ. ¿Cuál es el otro resistor?

	RT = 1/(1/1000 Ω + 1/R2)
	667 Ω = 1/(1/1000 Ω + 1/R2)
	R2(99.99 Ω) = 0.15 Ω
	R2= 1.5 mΩ
	
##### 10. Repita el problema 9 para cada uno de los circuitos mostrados en la figura 7-63.

![image](https://user-images.githubusercontent.com/105671763/176820586-ac21c6e3-aea8-4ee8-88c9-a7dec1b15cfa.png)

	(a) R3 || R4 + R1 + R2   ⟹  RT = 3.32 kΩ
	(b) R1 + R4 || R3 + R2   ⟹  RT = 406 kΩ
	(c) R6 + R7 + R5 || R1 + R2 + R3 || R4 + R8  ⟹ 8.82 kΩ

##### 12. Determine la corriente a través de cada resistor en cada circuito de la figura 7-63; luego calcule cada caída de voltaje.

![image](https://user-images.githubusercontent.com/105671763/176820601-cdfff85f-6e1c-4ba9-a8ef-4e2b0e98c6b7.png)

	(a) IT = 1.43 mA
	    Is = IT(R3/R1+R2) = 1 mA
	    V1 = I1 * R1 = 1 V
	    I2 = 431 μA 
	    V2 = 431 mV
	    I3 = 259 μA
	    I4 = 173 μA
	    V3 y V4 valen 570 mV
	    
	(b) Calcular las corrientes con la Ley de Ohm:
	    IT = Vs/RT = 492 μA
	    I1 = 2 μA
	    I2 = 606 mA
	    I3 = 323 mA
	    I4 = 2 μA

	(c) Las corrientes calculadas:
	    I1 = I2 = 962 μA
	    I3 = 308 μA
	    I4 = 654 μA

##### 14. Determine la resistencia entre A y B en la figura 7-67 sin la fuente.

![image](https://user-images.githubusercontent.com/105671763/176820660-8d90b888-7720-4f14-bbcb-0710a2a2bf9e.png)

	R = (10 kΩ + 5.6 kΩ) II 4.7 kΩ = 3.61 kΩ

##### 16. Determine el voltaje en cada nodo con respecto a tierra en la figura 7-68.

![image](https://user-images.githubusercontent.com/105671763/176820689-6db415a7-46e8-49d7-be0c-175e22d6d52c.png)

	NODO A

	VA - 50/(100 + 560) + VA/56 = 0
	VA = 3.91 mV

	NODO B

	50 + VA /660 + VB/R4 = 0
	VB = 81.6 kV

	NODO C

	VA - VB + VC/1 MΩ + VC/100 kΩ = 0
	VC = 7.41 V
	
	NODO D
	
	VD = Vs(RD/RT) 
	VD = 4.55 V

##### 18. Determine la resistencia del circuito mostrado en la figura 7-67 como se ve desde la fuente de voltaje.

![image](https://user-images.githubusercontent.com/105671763/176821231-be258f9a-820b-4476-94ca-a675f0e2d885.png)
![image](https://user-images.githubusercontent.com/105671763/176888475-eb44deb9-2b6f-4c1d-9937-bffc670fa8ca.png)

##### 20. Determine el voltaje, VAB, en la figura 7-69.

![image](https://user-images.githubusercontent.com/105671763/176821292-6874fdf9-b02f-4138-b924-bf6e7f643cc1.png)
![image](https://user-images.githubusercontent.com/105671763/176888988-af65ee88-b7db-4dca-b6e0-317e292ab1df.png)

##### 22. En la figura 7-71, determine la resistencia entre el nodo A y cada uno de los demás nodos (RAB, RAC, RAD, RAE, RAF, y RAG).

![image](https://user-images.githubusercontent.com/105671763/176821475-3e17d848-50bc-4907-a70e-a1ba97c6962a.png)
![image](https://user-images.githubusercontent.com/105671763/176889454-19668c55-a5d8-4ff1-870a-a49002c83d21.png)

##### 24. Determine el valor de cada resistor mostrado en la figura 7-73.

![image](https://user-images.githubusercontent.com/105671763/176821522-2065c7f9-d019-494c-adc2-583395ec259d.png)

	V2 = V5 - V6 = 5 V - 1 V = 4V
	I2 = I5 = 2 W/4 V 
	I2 = 0.5 A
	I5= I8 - I6 = 1 A - 0.5 A 
	I5 = 0.5 A
	I1 = I2 + I5 + I4 = 0.5 A + 0.5 A + 1 A 
	I1 = 2 A
	I3= IT - I1 = 4 A – 2 A
	I3  = 2 A
	V7 = Vs - V3 = 40 V - 20V = 20 V 
	V1 = 20 W/2 A = 10 V 
	V4 = V3 - V1 = 10 V
	V8 = V4 – V5 = 5 V
	R1 = 10/2 = 5 Ω
	R2 = 4/0.5 = 8 Ω
	R3 = 20/2 = 10 Ω ; R4 = 10/1 = 10 Ω  ;  R5 = 5/0.5 = 10 Ω
	R6 = 1/0.5 = 2 Ω
	R7 = 20/4 =5 Ω  ;  R8 = 5/1 = 5 Ω

##### *SECCIÓN 7-3 	Divisores de voltaje con cargas resistivas*

##### 26. La salida de una batería de 12 V se divide para obtener dos voltajes de salida. Se utilizan tres resistores de 3.3 kΩ para proporcionar dos tomas. Determine los voltajes de salida. Si se conecta una carga de 10 kΩ a la más alta de las salidas, ¿cuál será su valor con carga?

	VA = (6.6)/(9.9)*12 = 8 V
	VB = (3.3)/9.9*12 = 4 V
	
	* Con 10 kΩ
	RAB = (6.6 * 10)/(6.6 + 10)= 3.98 KΩ
	VA = 3.98/7.28 *12 = 6.56 V

##### 28. En la figura 7-74, determine el voltaje de salida sin carga entre las terminales de salida. Con una carga de 100 kΩ conectada de A a B, ¿cuál es el voltaje de salida?

![image](https://user-images.githubusercontent.com/105671763/176821711-d8ce56ad-d74a-453e-87b2-2c7aaa2380bc.png)

	RT = 10 + 5.6 + 2.7 = 18.3 KΩ
	V salida = (R2 + R3) /(R1 + R2 + R3)*Vs = 8.3/18.3*22= 9.98 V
	
	* Con 100K Ω
	RT = R1 + (R2 + R3)RL//R2 + R3 + RL = 10K Ω + 8.3 * 100/108.3 = 17.7 KΩ
	VSALIDA = 7.7/17.7 * 22 = 9.57 V

##### 30. En la figura 7-74, determine la corriente continua extraída de la fuente sin carga entre las terminales de salida. Con una carga de 33 kΩ, ¿cuál es la corriente extraída?

![image](https://user-images.githubusercontent.com/105671763/176821711-d8ce56ad-d74a-453e-87b2-2c7aaa2380bc.png)

	RT = 10 + 5.6 + 2.7 = 18.3 Ω
	I = 22/18.3 = 1.2 mA 
	RT = 10 + (8.3 * 33)/(8.3 + 33) = 16.6 KΩ
	I = 22/16.6 = 1.33 mA 

##### 32. El divisor de voltaje de la figura 7-75 tiene una carga controlada por interruptor. Determine el voltaje en cada toma (V1, V2 y V3) para cada posición del interruptor.

![image](https://user-images.githubusercontent.com/105671763/176883563-b322b5c3-65fd-4641-999e-ba79b7aec764.png)

	Posición 1
	68 = 10 + 20.82 = 30.8 KΩ
	V1 = (20.8/30.8)*120 = 81 V
	V2 = (20/30)*81 = 54 V
	V3 = (10/30)*81 = 27 V
	
	Posición 2
	68= 20 + 15.5 = 35.5 KΩ
	V1= (10 + 15.5)/35.5*120 = 86.2 V
	V2= (15.5/35.5)*81 = 52.4 V
	V3= (10/20)*52.4 = 26.2 V
	
	Posición 3
	68= 30 + 8.72 = 38.7
	V1= (20 + 8.72)/38.7*120 = 89 V
	V2= (10 + 8.72)/38.7*81 = 58 V
	V3= (8.72/38.7) * 81 = 27 V

##### 34. Diseñe un divisor de voltaje que produzca una salida de 6 V sin carga y un mínimo de 5.5 V entre los extremos de una carga de 1.0 kΩ. El voltaje de fuente es de 24 V y la corriente extraída sin carga no debe exceder de 100 mA.

	Imax = 100 mA
	RT = 24/100
	RT = 240 Ω
	(R2/RT)24 V = 6 V
	24R2 = 6RT
	R2 = 6(240)/24 = 60 Ω
	R1 = 240 - 60 = 180 Ω
	RL = 60 Ω 
	VSALIDA = 56.6/180 + 56.6 * 24 = 5.74 V

##### *SECCIÓN 7-4 	Efecto de carga de un voltímetro*

##### 36. Determine la resistencia interna de un voltímetro de 20,000 Ω/V en cada uno de los siguientes ajustes de intervalo.

	(a) 0.5 V   ⟹ R = 20.000 Ω/V * 0.5  ⟹ R = 10 KΩ
	(b) 1 V     ⟹ R = 20.000 Ω/V * 1    ⟹ R = 20 KΩ
	(c) 5 V     ⟹ R = 20.000 Ω/V * 5    ⟹ R = 100 KΩ
	(d) 50 V    ⟹ R = 20.000 Ω/V * 50   ⟹ R = 1 MΩ
	(e) 100 V   ⟹ R = 20.000 Ω/V * 100  ⟹ R = 2 MΩ
	(f) 1000 V  ⟹ R = 20.000 Ω/V * 1000 ⟹ R = 20 MΩ

##### 38. Repita el problema 37 si se utiliza el voltímetro para medir voltaje entre los extremos de R4 en el circuito de la figura 7-62(b).

![image](https://user-images.githubusercontent.com/105671763/176822251-591a55d2-63d3-4f1d-ba2a-4babf7899dcd.png)

	VR4= (R2||R3||R4)/(R2||R3||R4+R1) 3V = (99.4 Ω/779.4 Ω)3 V = 0.383 V
	R = 20,000 Ω/V *0.5 V = 10 KΩ
	99.4 Ω|| 10 KΩ = 98.4 Ω
	VR4 = (98.4 Ω/778.4 Ω)3 V = 0.379 V
	0.383V – 0.379 V = 0.004 V

##### *SECCIÓN 7-5 	 Redes en escalera*

##### 40. Determine la resistencia total y el voltaje en los nodos A, B y C de la red en escalera mostrada en la figura 7-78.

![image](https://user-images.githubusercontent.com/105671763/176822330-ef39d40a-faac-46f4-a0b4-6b0117743df9.png)

	RT = 6.66 Ω
	VA = (1.06)/6.66 *18 = 2.86 V
	VB = (1.05)/2.05 *2.86 = 1.47 V
	VC= ½*1.47 = 735 mV

##### 42. En la figura 7-79, ¿cuál es el voltaje entre los extremos de cada resistor con 10 V entre A y B?

![image](https://user-images.githubusercontent.com/105671763/176822399-ac2792ba-2853-45df-a6d6-be285f43af7b.png)

	V1 = IT*R1 = 16.1*100 = 1.61 V
	V2 = I2*R2 = 8.27*820 = 6.8 V
	V3 = I3*R3 = 7.84*220 = 1.73 V
	V4 = I4*R4 = 4.06*820 = 3.33 V
	V5 = I5*R5 = 3.78*100 = 0.38 V
	V6 = I6*R6 = 3.78*680 = 2.6 V
	V7 = I7*R7 = 3.78*100 = 0.38 V
	V8 = I8*R8 = 7.84*220 = 1.73 V
	V9 = I9*R9 = 16.1*100 = 1.61 V

##### 44. Determine VSALIDA para la red R/2R en escalera mostrada en la figura 7-81 para las siguientes condiciones:

![image](https://user-images.githubusercontent.com/105671763/176822545-e20c32fa-a353-4334-8927-bfee22b0815c.png)

	(a) Interruptor SW2 conectado a + 12 V y los demás conectados a tierra
	   
	   VSALIDA = V/8 = 12 V/8 = 1.5 V
	   
	(b) Interruptor SW1 conectado a + 12 V y los demás conectados a tierra

	   VSALIDA = V/16 = 12 V/16 = 0.75 V

##### *SECCIÓN 7-6 	El puente Wheatstone*

##### 46. Se conecta un resistor de valor desconocido a un circuito puente Wheatstone. Los parámetros del puente en equilibrio se establecen como sigue: RV = 18 kΩ y R2/R4 = 0.02. ¿Cuál es RX?

	Rx = R2 * Rv/R4 
	Rx = 18 kΩ * 0.02 
	Rx = 0.36 kΩ 

##### 48. Determine el voltaje de salida para el puente desequilibrado mostrado en la figura 7-83 a una temperatura de 60 ºC. La característica de resistencia según la temperatura del termistor se muestra en la figura 7-60

![image](https://user-images.githubusercontent.com/105671763/176822791-b4312f8a-9c56-4902-af74-0cc0a167d613.png)

	∆ RTERMISTOR = 27 kΩ = 27.000 Ω
	∆ VSALIDA = ∆ RTERMISTOR(Vs/4R)
	∆ VSALIDA = 27.000 Ω(9 V/4(27.000 Ω))
	∆ VSALIDA = 0.25 V   

##### *SECCIÓN 7-7 	Localización de fallas*

##### 50. ¿Son correctas las lecturas del medidor mostrado en la figura 7-85?

![image](https://user-images.githubusercontent.com/105671763/176822877-ab1b870e-f8b4-4c9a-8776-491008d867b1.png)
![image](https://user-images.githubusercontent.com/105671763/176841738-0b5c4ab9-785f-4629-b12a-9ca31eb8975b.png)

	Comprobamos:
	R2 + R4 = 47 kΩ + 10 kΩ = 57 kΩ
	(R2+R4)||R5 = (57*100)/(57+100) = 36.30 kΩ
	Rab = 33 + 36.30 = 69.3 kΩ
	R1 + R2 + R2 + R4)||R5 = 27 + 33 + 36.30
	RT = 96.3 kΩ
	Rab = (Rad/RT)(Vs) = (69.3/96.3)(18) = 12.95
	Vcd = (R2/R2 + R4)(6.79) = 5.60 V
	Vad = Vcd = 12.95 - 5.60 = 7.35 V

##### 52. Vea los medidores ilustrados en la figura 7-87 y determine si hay una falla en el circuito. Si la hay, identifíquela

![image](https://user-images.githubusercontent.com/105671763/176822923-1a4fd977-691e-4485-a8ea-97d5416cd4f3.png)

	Se comprueba:
	VxT = Vs(Rs/RT) = 150 V(6 kΩ/16 kΩ) = 56.25 V
	Vx1 = 150 V(12 kΩ/22 kΩ) = 81.8 V
	Vx2 = 150 V(2.2 kΩ/7.8 kΩ) = 42.3 V

##### 54. Si en la figura 7-89 R2 se abre, ¿qué voltajes se leerán en los puntos A, B y C?

![image](https://user-images.githubusercontent.com/105671763/176822982-cb64e3b1-a361-45d7-8128-10883984cc1f.png)
![image](https://user-images.githubusercontent.com/105671763/176842761-c5f6aaeb-808a-4917-9731-8da0880855b1.png)

	El voltaje de A es de 15 V ya que el circuito se encuentra abierto y hace que por B y C no pase voltaje.

#### CAPITULO 8 

##### *SECCIÓN 8-3 	Conversiones de fuente*

##### 2. Convierta las fuentes de voltaje prácticas de la figura 8-67 en fuentes de corriente equivalentes. 

![image](https://user-images.githubusercontent.com/105671763/176823126-14c4235d-bbc5-41d0-9aeb-852be6e21b4b.png)

	(a) Is = Vs/Rs = 5 kV/100 Ω = 50 A
	
![image](https://user-images.githubusercontent.com/105671763/176845625-9f0df059-5925-44de-bb40-d27f8f6ee480.png)

	(b) Is = Vs/Rs = 12 V/2.2 Ω = 5.45 A

![image](https://user-images.githubusercontent.com/105671763/176846839-507f3a43-9030-4152-828b-02e7f6db4a6a.png)

##### 4. Trace los circuitos equivalentes de fuentes de voltaje y corriente para la batería tipo D del problema 3. 

<img width="569" alt="image" src="https://user-images.githubusercontent.com/105671763/176849733-7d9f8382-1d58-4f17-8226-518d1fe4c5c0.png">
<img width="381" alt="image" src="https://user-images.githubusercontent.com/105671763/176850088-8813d08a-629b-47e2-8f12-19490904d84b.png">

##### 6. Convierta las fuentes de corriente prácticas de la figura 8-68 en fuentes de voltaje equivalentes.

![image](https://user-images.githubusercontent.com/105671763/176823262-9000499f-22bd-47f3-be7f-7e902923c997.png)

	(a) Vs = Is*Rs = 10 mA * 4.7 kΩ = 47 V
	
<img width="584" alt="image" src="https://user-images.githubusercontent.com/105671763/176849028-ccb88349-e70a-49e4-acc5-074b3d305c0d.png">

	(b) Vs = Is*Rs = 10 mA * 2.7 kΩ = 27 V

<img width="472" alt="image" src="https://user-images.githubusercontent.com/105671763/176848786-baf90045-5c32-483d-b8ca-db0ebda34495.png">

##### *SECCIÓN 8-4 	 El teorema de superposición*

##### 8. Use el teorema de superposición para determinar la corriente a través, y el voltaje entre, los extremos de la rama R2 de la figura 8-69.

![image](https://user-images.githubusercontent.com/105671763/176823359-98772ef5-d451-49b2-9338-407991acf2d9.png)

	R1||R2 = (1)(2.2)/(1 + 2.2) = 0.69 kΩ            
	R3 + R1eq = 0.69 + 1 = 1.69 kΩ
	R5eq = (1.69)(2.2)/(1.69 + 2.2) = 0.96 kΩ              
	RT= R5eq + R4     
	RT = 0.96 + 1 = 1.96 kΩ
	IT = 3/1.96 = 1.53 mA
	I2(V1) = R1/(R1+R2)(IT) = 1/(1+2.2)(1.53)
 	I2(V1) = 0.48 mA
	IT=2/1.96=1.02 mA
	I2(V2)= R3/(R2+R3)(IT) = 1/(2.2 + 1)(1.02) = 0.32 mA
	I2 = I2(V1) + I2(V2)
	I2 = 0.48 mA + 0.3 2mA
	I2 = 0.8 mA

##### 10. Con el teorema de superposición, determine la corriente de carga en cada uno de los circuitos mostrados en la figura 8-71.

![image](https://user-images.githubusercontent.com/105671763/176823407-fd511e50-0b2b-4d60-a1b2-31c41691ebb9.png)

	Req(2.2) = (RL.R(2.2))/(RL+R(2.2)) = (3.9)(2.2)/((3.9+2.2)) = 1.41 kΩ
	RT = 10 kΩ + 1.41 kΩ
	RT = 11.41 kΩ

	Vs = IT*RT
	Vs = 1A*(11.41 kΩ)
	Vs = 11410 V

	I1(RL) = 11410 V/(3.9 kΩ)= 0.003 AI1(RL) = 2 A
	IT(RL) = 2A + 0.003 A
	IT(RL) = 2.003 A

##### 12. Repita el problema 11 si R2 es de 10 kΩ.
	
	Req1 = 2.2 kΩ + 1 kΩ = 3.1 kΩ
	RT = (3.2 kΩ * 2.2 kΩ / 3.2 kΩ + 2.2 kΩ)
	RT = 1.3 kΩ
	IT = 0.1 A
	Ix = (1.3 kΩ / 3.1 kΩ) * 0.1 A 
	Ix = 0.0419 A
	IN = 0.1 A – 0.0419 A
	IN = 58.1 mA
	RN = (3.2 kΩ * 2.2 kΩ / 3.2 kΩ + 2.2 kΩ) 
	RN = 1.3 kΩ

##### 14. Los interruptores mostrados en la figura 8-74 se cierran en secuencia, SW1 primero. Determine la corriente a través de R4 después del cierre de cada interruptor.

![image](https://user-images.githubusercontent.com/105671763/176823509-4aa5b5ac-5318-4f0d-85ca-4dc9017b6c7e.png)
![image](https://user-images.githubusercontent.com/105671763/176879161-72a3f678-f9bd-420a-940c-dee4b56f07d4.png)
![image](https://user-images.githubusercontent.com/105671763/176879251-1f18b483-c2b9-4214-bb8d-416305855f0d.png)

##### *SECCIÓN 8-5 	 Teorema de Thevenin*

##### 16. Para cada uno de los circuitos de la figura 8-76, determine el equivalente de Thevenin como se ve desde las terminales A y B.

![image](https://user-images.githubusercontent.com/105671763/176823605-2068de62-7b67-42b3-817b-5aa4ac903eff.png)

	(a) RTH = 1/(1/100 + 1/(47 + 75)) + 27 = 49.42 Ω
	    VTH = (75/222)*25 = 8.45 V
	(b) RTH = 100 II 270 = 73 Ω
	    VTH = (100/370)*3 = 811 mV
	(c) RTH = 56 II 100 = 35.9 kΩ
	    VTH = (56/156)*15 = 1.79 V
	(d) RTH = 2.2 II (1 + 2.2) = 1.3 kΩ
	    VTH = 40.7 * 2.2 = 89.5 V

##### 18. Con el teorema de Thevenin, determine el voltaje entre los extremos de R4 en la figura 8-78. 

![image](https://user-images.githubusercontent.com/105671763/176823647-f54f7a63-7056-4c15-84f5-f09e3a149c8f.png)
![image](https://user-images.githubusercontent.com/105671763/176878284-37a5b88e-a3a4-4f4f-bf6a-25233266ed2a.png)

##### 20. Determine la corriente que se dirige al punto A cuando R8 es de 1.0 kΩ, 5 kΩ, y 10 kΩ en la figura 8-80. 

![image](https://user-images.githubusercontent.com/105671763/176823721-1536f91f-373e-4323-b7be-c66ed99ece92.png)
![image](https://user-images.githubusercontent.com/105671763/176878025-aabec750-c29d-4654-b19c-645c993ecb66.png)
![image](https://user-images.githubusercontent.com/105671763/176878046-abb126df-80fb-4bf2-a222-e9a6c4b83ef1.png)
![image](https://user-images.githubusercontent.com/105671763/176878062-608054c1-6207-4e5b-90d4-0baf6300e8ca.png)
![image](https://user-images.githubusercontent.com/105671763/176878074-7f995cc6-9a66-4faf-b38f-185f0b5b725b.png)
![image](https://user-images.githubusercontent.com/105671763/176878088-ab183f3e-7603-4dfd-84a9-4fdf4e6eb7d0.png)

##### 22. Determine el equivalente de Thevenin del circuito mostrado en la figura 8-82 visto desde las terminales A y B.

![image](https://user-images.githubusercontent.com/105671763/176823783-9d7bb9d6-1330-4591-b1e2-70b898fa4ded.png)
![image](https://user-images.githubusercontent.com/105671763/176877844-f44e7e76-1523-4fd6-8459-60ee32dfa4cf.png)

##### *SECCIÓN 8-6 	Teorema de Norton*

##### 24. Con el teorema de Norton, determine la corriente que circula a través del resistor de carga RL en la figura 8-77.

![image](https://user-images.githubusercontent.com/105671763/176823880-5d712846-fa93-4bed-9334-e0e8f21a8308.png)
![image](https://user-images.githubusercontent.com/105671763/176877759-245f0d73-1dbb-45f2-b0ba-576e81e5ded1.png)
![image](https://user-images.githubusercontent.com/105671763/176877770-ef6c4fac-dc42-41ac-ad99-b94bca86fd3b.png)

##### 26. Con el teorema de Norton, determine la corriente que circula a través de R1 en la figura 8-80 cuando R8 = 8 kΩ.

![image](https://user-images.githubusercontent.com/105671763/176823965-ba9dd7f0-e031-4201-9ef3-3b0425de162e.png)
![image](https://user-images.githubusercontent.com/105671763/176877590-1ee240a7-5ada-422d-96c1-3d0ff4442fe3.png)

##### 28. En la figura 8-83, reduzca el circuito entre las terminales A y B a su equivalente Norton.

![image](https://user-images.githubusercontent.com/105671763/176824007-0b204f0c-4738-4939-a377-0036d615e791.png)
![image](https://user-images.githubusercontent.com/105671763/176877484-f46eb7a8-19f9-48c1-a8f7-066d0fb72cdd.png)
![image](https://user-images.githubusercontent.com/105671763/176877498-2ec0306a-8498-4c6a-ab48-8fd8d9cce82e.png)

##### *SECCIÓN 8-7 	Teorema de transferencia de potencia máxima*

##### 30. En cada circuito mostrado en la figura 8-85, se tiene que transferir potencia máxima a la carga RL. Determine el valor apropiado de RL en cada caso

![image](https://user-images.githubusercontent.com/105671763/176824072-966b2ced-b62b-4e8f-97fc-28ea2451e70f.png)

	(a) RL = Rs = 12 Ω
	
	(b) RL = Rs = 8.2 kΩ
	
	(c) RL = Rs = (6.37 + 1) II 2 = 6.37 Ω
	
	(d) RL = Rs = 47 + 680 = 727 Ω

##### 32. ¿Cuánta potencia se suministra a la carga cuando RL es un 10% más alta que su valor para transferencia de potencia máxima en el circuito de la figura 8-86?

![image](https://user-images.githubusercontent.com/105671763/176824125-666ffd3f-a343-4c83-bf57-386097534cbf.png)

![image](https://user-images.githubusercontent.com/105671763/176876727-20963394-07c8-46f4-bd07-2f3592d3fe0f.png)

##### *SECCIÓN 8-8 	Conversiones delta a Y (∆ a Y) y Y a ∆*

##### 34. En la figura 8-88, convierta cada red delta en una red Y.

![image](https://user-images.githubusercontent.com/105671763/176824288-17359cac-be50-4602-83f3-e895fca99221.png)

	(a)
![image](https://user-images.githubusercontent.com/105671763/176876256-3bb8919d-ae1c-49be-8d2b-6445c8654083.png)

	(b)
![image](https://user-images.githubusercontent.com/105671763/176876435-bcfafe4b-275e-49a4-a2bc-bdc5411e1ee8.png)

##### 36. Determine todas las corrientes que circulan en el circuito de la figura 8-90.

![image](https://user-images.githubusercontent.com/105671763/176824347-8d9842fe-d638-45d1-a62a-5a2f66a6ab78.png)
![image](https://user-images.githubusercontent.com/105671763/176875759-7b0eb4c0-bf9c-49fa-bc77-03295345cfb0.png)
![image](https://user-images.githubusercontent.com/105671763/176875812-e29bbf92-fdd9-43da-829a-a3375fe6a0c1.png)

## 4. Video

https://youtu.be/QE4lRA2feyw

## 5. Conclusiones

- Para la resolución de los ejercicios se utilizó los conceptos de Ley de Ohm, Leyes de Kirchhoff, Mallas, Nodos, etc. Ya que, para la resolución de ejercicios a pesar de emplear nuevos métodos se necesita recordar antiguos conceptos útiles para el futuro.
- Los teoremas utilizados necesitan de las leyes básicas ya aprendidas para ser resueltos, ya que, para llegar a la solución se debe utilizar estos conocimientos.

## 6. Bibliografía

Floyd, Thomas. 2007. Principios de circuitos eléctricos. Octava edición.

