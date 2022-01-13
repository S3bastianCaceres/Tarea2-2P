# Tarea 2 - Capitulos 9-10
 
# OBJETIVOS # 

**Objetivo General**

Analizar los diferentes metodos para resolver los circuitos electricos y problemas de electromagnetismo e identificar cuando se usaran los diferentes metodos matemáticos para dar solucion al problema. 


**Objetivos Específicos**

- Analizar los métodos que existen para resolver ecuaciones 

- Analizar y aplicar el método de ramas para poder resolver los circuitos planteados

- Utilizar el método de nodos y lazos con la finalidad de encontrar los valores que nos pide el ejercicio 

- Comprender como resolver determinantes para poder calcular las corrientes.

- Analizar y explicar los principios tanto del electromagnetismo como los del campo magnético 

- Dibujar los circuitos simplificados de ser necesarios para su correcto entendimiento.

- Describir y analizar el principio de inducción electromagnética tanto en la parte teórica como en la parte práctica. 

- Revisar conceptos como: campo magnético, lay de Faraday, ley de Lenz, electromagnetismo que serán útiles en la resolución de los ejercicios. 

# MARCO TEORICO #

**Capitulo 9**

[![png-1.png](https://i.postimg.cc/jq6tvrg6/png-1.png)](https://postimg.cc/hhGkPNqh)

**Capitulo 10**

# EXPLICACIÓN Y RESOLUCIÓN DE EJERCICIOS O PROBLEMAS #

**Capitulo 9**

**1. Con el método de sustitución, resuelva el siguiente conjunto de ecuaciones para IR1 e IR2**

<img src="https://latex.codecogs.com/svg.image?1)100I_{1}&plus;50I_{2}=30\\2)75I_{1}&plus;90I{2}=15&space;" title="1)100I_{1}+50I_{2}=30\\2)75I_{1}+90I{2}=15 " />

**Despejar  I1 en (1) y reemplazar en 2**

(3) 

<img src="https://latex.codecogs.com/svg.image?I_{1}=\frac{30-50I_{2}}{100}&space;" title="I_{1}=\frac{30-50I_{2}}{100} " />

(3) en (2)

<img src="https://latex.codecogs.com/svg.image?75\left&space;[&space;\frac{30-50I_{2}}{100}&space;&space;\right&space;]&plus;90I_{2}=15" title="75\left [ \frac{30-50I_{2}}{100} \right ]+90I_{2}=15" />

<img src="https://latex.codecogs.com/svg.image?\frac{90}{4}-\frac{150I_{2}}{4}&plus;90I_{2}=15" title="\frac{90}{4}-\frac{150I_{2}}{4}+90I_{2}=15" />

<img src="https://latex.codecogs.com/svg.image?I_{2}=-\frac{1}{7}A" title="I_{2}=-\frac{1}{7}A" />

**Reemplazar I2 en 1**

<img src="https://latex.codecogs.com/svg.image?100I_{1}&plus;50I_{2}=30\\100I_{1}=30&plus;50\left&space;(&space;\frac{1}{7}&space;\right&space;)\\I_{1}=0.34A&space;" title="100I_{1}+50I_{2}=30\\100I_{1}=30+50\left ( \frac{1}{7} \right )\\I_{1}=0.34A " />

**3. Utilizando determinantes, resuelva el siguiente conjunto de ecuaciones para ambas corrientes:**
![imagen](https://user-images.githubusercontent.com/93798427/148665180-baea7084-bbcc-4c47-8909-9ea1b92f967d.png)

![imagen](https://user-images.githubusercontent.com/93798427/148665243-0df95fce-ceea-4eb2-9db5-d0307c6de414.png)

![imagen](https://user-images.githubusercontent.com/93798427/148665266-68b05c0c-0623-495c-b0cd-324916e3d47f.png)

**5. Evalúe cada uno de los determinantes:**

![image](https://user-images.githubusercontent.com/93739242/148868982-6d7b3868-c176-43d0-91c5-387a007547c1.png)

a)

<img src="https://latex.codecogs.com/svg.image?\\[10pt][(25)(12)(-16)&plus;(0)(5)(-8)&plus;(-20)(10)(30)]-[(-8)(12)(-20)&plus;(30)(5)(25)&plus;(-16)(10)(0)]\\[10pt][(-4800)&plus;0&plus;(-6000)]-[(1920)&plus;(3750)]=-16470" title="\\[10pt][(25)(12)(-16)+(0)(5)(-8)+(-20)(10)(30)]-[(-8)(12)(-20)+(30)(5)(25)+(-16)(10)(0)]\\[10pt][(-4800)+0+(-6000)]-[(1920)+(3750)]=-16470" />

b)

<img src="https://latex.codecogs.com/svg.image?\\[10pt][(1.08)(2.12)(-1.05)&plus;(1.75)(-0.98)(1)&plus;(0.55)(0)(3.49)]-[(1)(2.12)(0.55)&plus;(3.49)(-0.98)(1.08)&plus;(-1.05)(0)(1.75)]\\[10pt][(-2.40)&plus;(-1.715)&plus;0]-[(1.16)&plus;(-3.69)&plus;(0)]=-1.59" title="\\[10pt][(1.08)(2.12)(-1.05)+(1.75)(-0.98)(1)+(0.55)(0)(3.49)]-[(1)(2.12)(0.55)+(3.49)(-0.98)(1.08)+(-1.05)(0)(1.75)]\\[10pt][(-2.40)+(-1.715)+0]-[(1.16)+(-3.69)+(0)]=-1.59" />


**7. Resuelva para I1, I2, I3 en el siguiente conjunto de ecuaciones con determinantes:**

<img src="https://latex.codecogs.com/svg.image?1)2I_{1}-6I_{2}&plus;10I_{3}=9\\2)3I_{1}&plus;7I_{2}-8I_{3}=3\\3)10I_{1}&plus;5I_{2}-12I_{3}=0&space;" title="1)2I_{1}-6I_{2}+10I_{3}=9\\2)3I_{1}+7I_{2}-8I_{3}=3\\3)10I_{1}+5I_{2}-12I_{3}=0 " />

**Determinante de delta**

<img src="https://latex.codecogs.com/svg.image?Det(\Delta&space;)=\begin{vmatrix}&space;2&-6&space;&space;&&space;10&space;\\&space;3&&space;&space;7&&space;-8&space;\\&space;10&&space;&space;5&-12&space;&space;\\\end{vmatrix}=-374" title="Det(\Delta )=\begin{vmatrix} 2&-6 & 10 \\ 3& 7& -8 \\ 10& 5&-12 \\\end{vmatrix}=-374" />

**Determinante de I1**

<img src="https://latex.codecogs.com/svg.image?Det(I_{1})&space;=\begin{vmatrix}&space;9&&space;&space;-6&&space;&space;10\\3&space;&7&space;&space;&-8&space;&space;\\0&space;&&space;5&space;&-12&space;&space;\\\end{vmatrix}=-462" title="Det(I_{1}) =\begin{vmatrix} 9& -6& 10\\3 &7 &-8 \\0 & 5 &-12 \\\end{vmatrix}=-462" />

**Determinante de I2**

<img src="https://latex.codecogs.com/svg.image?Det(I_{2})&space;=\begin{vmatrix}&space;2&&space;&space;9&&space;&space;10\\3&space;&3&space;&space;&-8&space;&space;\\10&space;&&space;0&space;&-12&space;&space;\\\end{vmatrix}=-768" title="Det(I_{2}) =\begin{vmatrix} 2& 9& 10\\3 &3 &-8 \\10 & 0 &-12 \\\end{vmatrix}=-768" />

**Determinante de I3**

<img src="https://latex.codecogs.com/svg.image?Det(I_{3})&space;=\begin{vmatrix}&space;2&&space;&space;-6&&space;&space;10\\3&space;&7&space;&space;&-8&space;&space;\\10&space;&&space;5&space;&-12&space;&space;\\\end{vmatrix}=-705" title="Det(I_{3}) =\begin{vmatrix} 2& -6& 10\\3 &7 &-8 \\10 & 5 &-12 \\\end{vmatrix}=-705" />


**Para I1**

<img src="https://latex.codecogs.com/svg.image?I_{1}=\frac{Det(I_{1})}{\Delta&space;}=\frac{-462}{-374}=1.23A" title="I_{1}=\frac{Det(I_{1})}{\Delta }=\frac{-462}{-374}=1.23A" />

**Para I2**

<img src="https://latex.codecogs.com/svg.image?I_{2}=\frac{Det(I_{2})}{\Delta&space;}=\frac{-768}{-374}=2.05A" title="I_{2}=\frac{Det(I_{2})}{\Delta }=\frac{-768}{-374}=2.05A" />

**Para I3**

<img src="https://latex.codecogs.com/svg.image?I_{3}=\frac{Det(I_{3})}{\Delta&space;}=\frac{-705}{-374}=1.88A" title="I_{3}=\frac{Det(I_{3})}{\Delta }=\frac{-705}{-374}=1.88A" />

**9. Resuelva las dos ecuaciones simultáneas del problema 1 con su calculadora.**


![imagen](https://user-images.githubusercontent.com/93798427/148665330-a0d7daaf-c527-4b41-8947-f1e6d1b39287.png)

![imagen](https://user-images.githubusercontent.com/93798427/148665335-4d54659a-d35d-497f-b2a5-4ca2785914fe.png)


**11. Escriba la ecuación de la corriente de Kirchhoff para la asignación de corriente mostrada en el nodo A en la figura 9-26.**

![image](https://user-images.githubusercontent.com/93739242/148869116-5f27c0b0-32f5-46db-95f7-ca4d00a67548.png)

<img src="https://latex.codecogs.com/svg.image?\\[10pt]I_{1}=I_{2}&plus;I_{3}\\[10pt]I_{1}-I_{2}-I_{3}=0&space;" title="\\[10pt]I_{1}=I_{2}+I_{3}\\[10pt]I_{1}-I_{2}-I_{3}=0 " />


**13. Determine la caída de voltaje entre los extremos de cada resistor mostrado en la figura 9-26 e indique la polaridad real.**

[![figura-1.png](https://i.postimg.cc/rybfdbZc/figura-1.png)](https://postimg.cc/0rYYFtqH)


**Circuito con sus polaridades**

[![figura-1-LI-2.jpg](https://i.postimg.cc/bwDSLJTd/figura-1-LI-2.jpg)](https://postimg.cc/XrWvYnt0)

**Malla 1**

<img src="https://latex.codecogs.com/svg.image?12=8.2(I_{1})&plus;10(I_{1}-I_{2})\\12=18.2I_{1}-10I_{2}&space;" title="12=8.2(I_{1})+10(I_{1}-I_{2})\\12=18.2I_{1}-10I_{2} " />

**Malla 2**

<img src="https://latex.codecogs.com/svg.image?-6=10(I_{2}-I_{1})&plus;5.6I_{2}\\-6=15.6I_{2}-10I_{1}&space;" title="-6=10(I_{2}-I_{1})+5.6I_{2}\\-6=15.6I_{2}-10I_{1} " />

**Resolviendo el sistemna de ecuaciones**

<img src="https://latex.codecogs.com/svg.image?I_{1}=0.69&space;A\\I_{2}=0.059&space;A&space;" title="I_{1}=0.69 A\\I_{2}=0.059 A " />

**Cídas de voltaje**

<img src="https://latex.codecogs.com/svg.image?V_{1}=8.2(0.69)=5.65V\\V_{2}=10(0.69-0.058)=6.32V\\V_{3}=5.6(0.058)=0.325V=325mV&space;" title="V_{1}=8.2(0.69)=5.65V\\V_{2}=10(0.69-0.058)=6.32V\\V_{3}=5.6(0.058)=0.325V=325mV " />

**15. En la figura 9-27, determine el voltaje entre las terminales de la fuente de corriente (puntos A y B).**

![imagen](https://user-images.githubusercontent.com/93798427/148665349-71dd3642-fa16-45ba-87fd-a0f88d884587.png)

![imagen](https://user-images.githubusercontent.com/93798427/148700525-b18a55f7-d6b9-450f-b277-fdf686e56a13.png)

![imagen](https://user-images.githubusercontent.com/93798427/148700557-d91bffd1-28c1-438c-93da-52476e5eae1d.png)

![imagen](https://user-images.githubusercontent.com/93798427/148700584-21c0465c-6784-4438-a08f-76c156a67011.png)

![imagen](https://user-images.githubusercontent.com/93798427/148700623-16f49e8f-96f8-4fd6-b61f-5ce01a4586eb.png)

**17. Con el método de la corriente en lazos, determine las corrientes en los lazos que aparecen en la figura 9-28.**

![image](https://user-images.githubusercontent.com/93739242/148869152-f18a4e23-cb1d-4b3f-9fe8-d06e40313fbe.png)

![image](https://user-images.githubusercontent.com/93739242/148869161-455d7d33-1ff4-4084-98b3-cb161f96e492.png)

<img src="https://latex.codecogs.com/svg.image?\\[10pt]2&plus;1000I_{A}&plus;560(I_{A}-I_{B})&plus;4=0&space;\\[10pt]1000I_{A}&plus;560I_{A}-560I_{B}&plus;6=0&space;\\[10pt]1560I_{A}-560I_{B}=-6&space;\\[10pt]-4&plus;560(I_{B}-I_{A})&plus;820I_{B}&plus;6=0&space;\\[10pt]560I_{B}-560I_{A}&plus;820I_{B}&plus;2=0&space;\\[10pt]-560I_{A}&plus;1380I_{B}=-2&space;\\[10pt]&space;" title="\\[10pt]2+1000I_{A}+560(I_{A}-I_{B})+4=0 \\[10pt]1000I_{A}+560I_{A}-560I_{B}+6=0 \\[10pt]1560I_{A}-560I_{B}=-6 \\[10pt]-4+560(I_{B}-I_{A})+820I_{B}+6=0 \\[10pt]560I_{B}-560I_{A}+820I_{B}+2=0 \\[10pt]-560I_{A}+1380I_{B}=-2 \\[10pt] " />

<img src="https://latex.codecogs.com/svg.image?\\[10pt]I_{A}=-5.11*10^{-3}A&space;\to&space;-5.11&space;mA\\[10PT]I_{B}=-3.52*10^{-3}A&space;\to&space;-3.52mA&space;" title="\\[10pt]I_{A}=-5.11*10^{-3}A \to -5.11 mA\\[10PT]I_{B}=-3.52*10^{-3}A \to -3.52mA " />

**19. Determine los voltajes y sus polaridades apropiadas en cada uno de los resistores mostrados en la figura 9-28.**


[![figura-2.png](https://i.postimg.cc/L8FvDPMb/figura-2.png)](https://postimg.cc/CzJjLz5G)

**Circuito con sus polaridades**

[![figura-2-LI.jpg](https://i.postimg.cc/ZRZ9TLhy/figura-2-LI.jpg)](https://postimg.cc/kV1MsKGn)

**Malla 1**

<img src="https://latex.codecogs.com/svg.image?-4-2=1000I_{1}&plus;560(I_{1}-I_{2})\\-6=1560I_{1}-560I_{2}\\&space;" title="-4-2=1000I_{1}+560(I_{1}-I_{2})\\-6=1560I_{1}-560I_{2}\\ " />

**Malla 2**

<img src="https://latex.codecogs.com/svg.image?-6&plus;4=560(I_{2}-I_{1})&plus;820I_{2}\\-2=1380I_{2}-560&space;I_{1}" title="-6+4=560(I_{2}-I_{1})+820I_{2}\\-2=1380I_{2}-560 I_{1}" />

**Resolviendo el sistema de ecuaciones**

<img src="https://latex.codecogs.com/svg.image?I_{1}=-0.0051A\\I_{2}=0.0035A&space;" title="I_{1}=-0.0051A\\I_{2}=0.0035A " />

**Cídas de voltaje**

<img src="https://latex.codecogs.com/svg.image?V_{1}=5.1V\\V_{2}=2.87V\\V_{3}=560(0.0051-0.0035)=896mV&space;" title="V_{1}=5.1V\\V_{2}=2.87V\\V_{3}=560(0.0051-0.0035)=896mV " />


**21. Resuelva para las corrientes de lazo en la figura 9-29 con su calculadora.**

![imagen](https://user-images.githubusercontent.com/93798427/148665359-06b49e91-cf34-479b-bb00-015d78912bf0.png)


![imagen](https://user-images.githubusercontent.com/93798427/148665376-6411621e-324b-4245-8ad2-7b1a8cc2cc89.png)

![imagen](https://user-images.githubusercontent.com/93798427/148665381-ed1c5314-97f1-42c5-be60-f4372c4a807b.png)

![imagen](https://user-images.githubusercontent.com/93798427/148665406-93dd3026-1623-4c28-8da0-39d8ec367468.png)

![imagen](https://user-images.githubusercontent.com/93798427/148665416-3cecf1aa-15cf-4fd0-ab14-5336c46e8d6d.png)

![imagen](https://user-images.githubusercontent.com/93798427/148665435-3d294749-5794-47b7-9ebd-fd9b8f89ca1f.png)

![imagen](https://user-images.githubusercontent.com/93798427/148665444-458f697f-2f76-4186-ad14-ccea12009ffa.png)

![imagen](https://user-images.githubusercontent.com/93798427/148665530-7c3cd67e-2ea5-421d-9c2f-f75faf65520a.png)

![imagen](https://user-images.githubusercontent.com/93798427/148665535-5a1b4d12-8d10-4fda-8126-c93b604ae72b.png)

![imagen](https://user-images.githubusercontent.com/93798427/148665552-858581d3-3b0d-4f10-b5f0-3b96baf87e35.png)

**23. Determine el voltaje entre las terminales del puente abierto, A y B, en la figura 9-30.**

![image](https://user-images.githubusercontent.com/93739242/148869259-ff87a3a9-3a11-4877-816c-474621692ab1.png)

![image](https://user-images.githubusercontent.com/93739242/148869267-95b12fc1-1c0b-4916-abe1-3ae3582e6835.png)

<img src="https://latex.codecogs.com/svg.image?\\[10pt]-8&plus;10I_{1}&plus;4.7(I_{1}-I_{2})&plus;2.2(I_{1}-I_{2})=0&space;\\[10pt]&space;10I_{1}&plus;4.7I_{1}&plus;2.2I_{1}-4.7I_{2}-2.2I_{2}=8&space;\\[10pt]16.9I_{1}-6.9I_{2}=8&space;" title="\\[10pt]-8+10I_{1}+4.7(I_{1}-I_{2})+2.2(I_{1}-I_{2})=0 \\[10pt] 10I_{1}+4.7I_{1}+2.2I_{1}-4.7I_{2}-2.2I_{2}=8 \\[10pt]16.9I_{1}-6.9I_{2}=8 " />

<img src="https://latex.codecogs.com/svg.image?\\[10pt]8.2I_{2}&plus;3.9I_{2}&plus;2.2(I_{2}-I_{1})&plus;4.7(I_{2}-I_{1})=0&space;\\[10pt]8.2I_{2}&plus;3.9I_{2}&plus;2.2I_{2}-2.2I_{1}&plus;4.7I_{2}-4.7I_{1}=0\\[10pt]-6.9I_{1}&plus;19I_{2}=0&space;" title="\\[10pt]8.2I_{2}+3.9I_{2}+2.2(I_{2}-I_{1})+4.7(I_{2}-I_{1})=0 \\[10pt]8.2I_{2}+3.9I_{2}+2.2I_{2}-2.2I_{1}+4.7I_{2}-4.7I_{1}=0\\[10pt]-6.9I_{1}+19I_{2}=0 " />

<img src="https://latex.codecogs.com/svg.image?\\[10pt]I_{1}=0.55&space;A&space;\\[10pt]I_{2}=0.2&space;A&space;" title="\\[10pt]I_{1}=0.55 A \\[10pt]I_{2}=0.2 A " />

<img src="https://latex.codecogs.com/svg.image?\\[10pt]-V_{A}&plus;2.2(I_{1}-I_{2})=0&space;\\[10pt]V_{A}=2.2(0.55-0.2)&space;\\[10pt]V_{A}=0.77V&space;" title="\\[10pt]-V_{A}+2.2(I_{1}-I_{2})=0 \\[10pt]V_{A}=2.2(0.55-0.2) \\[10pt]V_{A}=0.77V " />

<img src="https://latex.codecogs.com/svg.image?\\[10pt]-V_{B}&plus;3.9I_{2}=0&space;\\[10pt]V_{B}=3.9(0.2)&space;\\[10pt]V_{B}=0.78V&space;" title="\\[10pt]-V_{B}+3.9I_{2}=0 \\[10pt]V_{B}=3.9(0.2) \\[10pt]V_{B}=0.78V " />

<img src="https://latex.codecogs.com/svg.image?\\[10pt]V_{AB}=V_{A}-V_{B}&space;\\[10pt]=0.77-0.78&space;\\[10pt]V_{AB}=-0.01V&space;\to&space;-11.2mA&space;" title="\\[10pt]V_{AB}=V_{A}-V_{B} \\[10pt]=0.77-0.78 \\[10pt]V_{AB}=-0.01V \to -11.2mA " />


**27. ¿Cuáles son los valores de corriente de rama en la figura 9-32? En cada rama, muestre la dirección real
de la corriente. **

![imagen](https://user-images.githubusercontent.com/93798427/148665559-2e15a352-8588-44e9-9fac-38a364f4ed1a.png)

![imagen](https://user-images.githubusercontent.com/93798427/148665597-e665b561-96d4-44d4-98e7-770c5940a4a1.png)

![imagen](https://user-images.githubusercontent.com/93798427/148665615-aaec49ed-ca58-48a5-85b0-eb342c461a9f.png)

![imagen](https://user-images.githubusercontent.com/93798427/148665627-93d20d59-169f-49b9-959d-37b5321705d5.png)

![imagen](https://user-images.githubusercontent.com/93798427/148665635-b54e5131-8205-45ec-bb63-fd5125dfb41d.png)


**25. Escriba las ecuaciones de lazo en la forma estándar para el circuito puente T mostrado en la figura 9-31**

[![figura-3.png](https://i.postimg.cc/j52h2QzL/figura-3.png)](https://postimg.cc/YGcFyFDH)

**MALLA DE LA CORRIENTE B**

<img src="https://latex.codecogs.com/svg.image?15=3.3(I_{B}-I_{A})&plus;820(I_{B}-I_{C})\\15=4120I_{B}-3300I_{A}-820I_{C}" title="15=3.3(I_{B}-I_{A})+820(I_{B}-I_{C})\\15=4120I_{B}-3300I_{A}-820I_{C}" />


**MALLA DE LA CORRIENTE C**

<img src="https://latex.codecogs.com/svg.image?0=1500(I_{C}-I_{A})&plus;2200(I_{C})&plus;820(I_{C}-I_{B})\\0=4520I_{C}-1500I_{A}-820I_{B}&space;" title="0=1500(I_{C}-I_{A})+2200(I_{C})+820(I_{C}-I_{B})\\0=4520I_{C}-1500I_{A}-820I_{B} " />



**MALLA DE LA CRRIENTE A**

<img src="https://latex.codecogs.com/svg.image?0=680I_{A}&plus;1500(I_{A}-I_{C})&plus;3300(I_{A}-I_{B})\\0=5480I_{A}=-1500I_{C}-3300I_{B}&space;" title="0=680I_{A}+1500(I_{A}-I_{C})+3300(I_{A}-I_{B})\\0=5480I_{A}=-1500I_{C}-3300I_{B} " />


**29. Use el análisis de nodos para determinar el voltaje en los puntos A y B con respecto a tierra en la figura 9-33.**

![image](https://user-images.githubusercontent.com/93739242/148869309-0f24c760-ac32-4196-9448-406702b9f027.png)

![image](https://user-images.githubusercontent.com/93739242/148869324-d81d8c85-6dd8-48b7-a32d-dc3be73bf2cb.png)

<img src="https://latex.codecogs.com/svg.image?\begin{aligned}&\frac{V_{A}-9}{56&space;\mathrm{k}}&plus;\frac{V_{A}}{27&space;\mathrm{k}}&plus;\frac{V_{A}-V_{B}}{91&space;\mathrm{k}}=0&space;\\[10pt]&\frac{2457\left(V_{A}-9\right)&plus;5096&space;V_{A}&plus;1512\left(V_{A}-V_{B}\right)}{137592&space;\mathrm{k}}=0&space;\\[10pt]&2457\left(V_{A}-9\right)&plus;5096&space;V_{A}&plus;1512\left(V_{A}-V_{B}\right)=0&space;\\[10pt]&2457&space;V_{A}-22113&plus;5096&space;V_{A}&plus;1512&space;V_{A}-1512&space;V_{B}=0&space;\\[10pt]&9065&space;V_{A}-1512&space;V_{B}=22113&space;\ldots&space;\ldots&space;\text&space;{&space;(1)&space;}\end{aligned}" title="\begin{aligned}&\frac{V_{A}-9}{56 \mathrm{k}}+\frac{V_{A}}{27 \mathrm{k}}+\frac{V_{A}-V_{B}}{91 \mathrm{k}}=0 \\[10pt]&\frac{2457\left(V_{A}-9\right)+5096 V_{A}+1512\left(V_{A}-V_{B}\right)}{137592 \mathrm{k}}=0 \\[10pt]&2457\left(V_{A}-9\right)+5096 V_{A}+1512\left(V_{A}-V_{B}\right)=0 \\[10pt]&2457 V_{A}-22113+5096 V_{A}+1512 V_{A}-1512 V_{B}=0 \\[10pt]&9065 V_{A}-1512 V_{B}=22113 \ldots \ldots \text { (1) }\end{aligned}" />

<img src="https://latex.codecogs.com/svg.image?\begin{aligned}&\frac{V_{B}-V_{A}}{91&space;\mathrm{k}}&plus;\frac{V_{B}&plus;4.5}{33&space;\mathrm{k}}&plus;\frac{V_{B}&plus;15}{82&space;\mathrm{k}}=0&space;\\[10pt]&\frac{2706\left(V_{B}-V_{A}\right)&plus;7462\left(V_{B}&plus;4.5\right)&plus;3003\left(V_{B}&plus;15\right)}{246246&space;\mathrm{k}}=0&space;\\[10pt]&2706\left(V_{B}-V_{A}\right)&plus;7462\left(V_{B}&plus;4.5\right)&plus;3003\left(V_{B}&plus;15\right)=0&space;\\[10pt]&2706&space;V_{B}-2706&space;V_{A}&plus;7462&space;V_{B}&plus;33579&plus;3003&space;V_{B}&plus;45045=0&space;\\[10pt]&-2706&space;V_{A}&plus;13171&space;V_{B}=-78624&space;\ldots&space;\ldots&space;\text&space;{&space;(2)&space;}\end{aligned}" title="\begin{aligned}&\frac{V_{B}-V_{A}}{91 \mathrm{k}}+\frac{V_{B}+4.5}{33 \mathrm{k}}+\frac{V_{B}+15}{82 \mathrm{k}}=0 \\[10pt]&\frac{2706\left(V_{B}-V_{A}\right)+7462\left(V_{B}+4.5\right)+3003\left(V_{B}+15\right)}{246246 \mathrm{k}}=0 \\[10pt]&2706\left(V_{B}-V_{A}\right)+7462\left(V_{B}+4.5\right)+3003\left(V_{B}+15\right)=0 \\[10pt]&2706 V_{B}-2706 V_{A}+7462 V_{B}+33579+3003 V_{B}+45045=0 \\[10pt]&-2706 V_{A}+13171 V_{B}=-78624 \ldots \ldots \text { (2) }\end{aligned}" />

<img src="https://latex.codecogs.com/svg.image?\begin{aligned}&13171V_{B}=-78624&plus;2706V_{A}\\[10pt]&V_{B}=-\frac{78624}{13171}&plus;\frac{2706}{13171}V_{A}\\[10pt]&9065V_{A}-1512[-5.942&plus;0.205V_{A}]=22113&space;\\[10pt]&9065V_{A}&plus;8984.3-309.9=22113&space;\\[10pt]&9065V_{A}=13438.6&space;\to&space;1.482&space;V\end{aligned}" title="\begin{aligned}&13171V_{B}=-78624+2706V_{A}\\[10pt]&V_{B}=-\frac{78624}{13171}+\frac{2706}{13171}V_{A}\\[10pt]&9065V_{A}-1512[-5.942+0.205V_{A}]=22113 \\[10pt]&9065V_{A}+8984.3-309.9=22113 \\[10pt]&9065V_{A}=13438.6 \to 1.482 V\end{aligned}" />
<img src="https://latex.codecogs.com/svg.image?\begin{aligned}&V_{B}=-5.942&plus;0.205(1.482)&space;\\[10pt]&=-5.942&plus;0.30381&space;\\[10pt]&=-5.63V\end{aligned}" title="\begin{aligned}&V_{B}=-5.942+0.205(1.482) \\[10pt]&=-5.942+0.30381 \\[10pt]&=-5.63V\end{aligned}" />


# Capitulo 10 

**1. El área de sección transversal de un campo magnético se incrementa, pero el flujo no cambia. ¿La densidad de flujo aumenta o disminuye?**

Disminuye

**3. ¿Cuál es el flujo en un material magnético cuando la densidad de flujo es de 2500  106 T y el área
de sección transversal mide 150 cm2?**

![imagen](https://user-images.githubusercontent.com/93798427/148665676-eea4e31d-5185-4f0f-ada5-cbbc4dfbebd7.png)

**5. Un imán permanente muy fuerte tiene un campo magnético de 100,000 mT. Exprese esta densidad de flujo en gauss.**

B(Gauss)=(Campo Magnetico) <img src="https://latex.codecogs.com/svg.image?[\frac{10^{4}G}{1T}]" title="[\frac{10^{4}G}{1T}]" />

B=(100000mT) <img src="https://latex.codecogs.com/svg.image?[\frac{10^{4}G}{1T}]" title="[\frac{10^{4}G}{1T}]" />

B=1000G


**9. ¿Cuál es la fuerza magnetomotriz en una bobina de 50 vueltas de hilo cuando hay 3 A de corriente a
través de él?**

![imagen](https://user-images.githubusercontent.com/93798427/148665690-19476f9d-cded-4455-9402-3e64e1a12547.png)


**7. ¿Cuál es la permeabilidad relativa de un material ferromagnético cuya permeabilidad absoluta es de 750 x 10^6 Wb/At·m?**

**Datos**

<img src="https://latex.codecogs.com/svg.image?\mu&space;=750\times&space;10^{-6}Wb/Atm" title="\mu =750\times 10^{-6}Wb/Atm" />

<img src="https://latex.codecogs.com/svg.image?\mu&space;_{0}=4\pi&space;\times&space;10^{-7}Wb/Atm" title="\mu _{0}=4\pi \times 10^{-7}Wb/Atm" />

**Solucion**

<img src="https://latex.codecogs.com/svg.image?\mu&space;_{0}=\frac{\mu&space;}{\mu_{0}}=\frac{750\times&space;10^{-6}}{4\pi&space;\times&space;10^{-7}}=597.13" title="\mu _{0}=\frac{\mu }{\mu_{0}}=\frac{750\times 10^{-6}}{4\pi \times 10^{-7}}=597.13" />


**11. (a) ¿Qué fuerza mueve el émbolo de imán cuando se activa un solenoide?** 

La fuerza del campo electromagnético mueve el émbolo cuando se activa un solenoide.

**(b) ¿Qué fuerza hace que el émbolo de imán regrese a su posición de reposo?**

La fuerza del resorte hace que el embolo vuelva a su posición de reposo


**15. ¿Cómo se puede cambiar la densidad de flujo en la figura 10-44 sin alterar las características físicas del
núcleo?**

![imagen](https://user-images.githubusercontent.com/93798427/148665707-a7110735-7b61-4358-9afb-fd54d05d01d3.png)

Mediante un cambio en la corriente 


**13. ¿Qué ocasiona que la aguja instalada en un movimiento de d’Arsonval se deflexione cuando circula corriente a través de la bobina**

[![figura-4.png](https://i.postimg.cc/Px7Qwp4K/figura-4.png)](https://postimg.cc/S2W90KHz)


Fuerzas producidas por la interacción del capo electromagnetico y el campo magnetico permanente


**17. Determine a partir de las curvas de histéresis mostradas en la figura 10-45 qué material tiene más retentividad**

![image](https://user-images.githubusercontent.com/93739242/148869543-ffc8dfb3-a250-4004-8232-ca2ce69c7ee8.png)


La capacidad del material para mantener un estado magnetizado sin intensidad de campo magnético se llama retención. La retentividad del material representa el flujo máximo que puede ser retenido después de que el material se ha desmagnetizado hasta la saturación.

Para el material A  BR es casi igual a Bsat y por lo tanto la retentividad es una.

Para el material B BR es menor que Bsat y por lo tanto la retentividad es menor que uno.

Para el material C BR es mucho menor que Bsat y por lo tanto, la retentividad es mucho menor que uno.

Por lo tanto, el material que tiene mayor retentividad es MATERIAL A


**19. ¿Cuáles son los tres factores que determinan el voltaje en un conductor que se mueve en dirección perpendicular al campo magnético?**


La intensidad del campo mágnetico, la longitud del conductor expuesta al campo, y la velocidad de rotaxión del conductor


**21. ¿Cómo complementa la ley de Lenz a la ley de Faraday?**

La ley de lenz nos explica o define la polaridad del voltaje que se induce 

**23. Explique el propósito del conmutador y de las escobillas en la figura 10-35.**

![image](https://user-images.githubusercontent.com/93739242/148869569-920ea638-15c1-459c-bcac-0142c376535e.png)

La figura muestra un generador de corriente directa que consta de un solo bucle de cable en un campo magnético permanente. Cada extremo del bucle de alambre está conectado a una disposición de anillo dividido. Este anillo conmutador dividido también gira. Cada mitad del anillo partido se frota contra los contactos fijos, llamados cepillos, y conecta el bucle de alambre a un circuito externo.

Según la ley de Faraday, cuando un cable se mueve a través de un campo magnético, se induce un voltaje y la cantidad de voltaje inducido es proporcional al número de vueltas en el cable y la velocidad a la que se mueve con respecto al campo magnético. Este voltaje inducido se alterna y se debe a la acción del conmutador y los cepillos se convierten en unidireccional en el circuito externo.

Por lo tanto, el propósito del conmutador y los cepillos es hacer que el voltaje inducido sea unidireccional o conecte eléctricamente la espira en el circuito externo.

*** 25. Suponga que se agrega otra espira, a 90 grados de la primera, al generador de cd del problema 24. Trace una gráfica del voltaje contra el tiempo para mostrar cómo aparece el voltaje de salida. Sea de 10 V el voltaje máximo.**


[![ej25.png](https://i.postimg.cc/cLsDY1J2/ej25.png)](https://postimg.cc/gnTqbW8H)

# VIDEO #

# CONCLUSIONES #

- Gracias a la aplicación de determinantes para la resolución del sistema de ecuaciones nos permite tener mayor conocimiento para aplicarlo en los diferentes ejercicios, aunque si resulta un poco más extenso que resolver por un método más conocido como podría ser el de sustitución, igualación o por suma y resta.

- En los ejercicios hicimos uso del método de lazos que era parecido al método de mallas y el mismo nos ayudó en la mayor parte de los mismos, hicimos uso de otros métodos como el de ramas que resulta más complicado y extenso debido a que debemos encontrar varias ecuaciones para dar solución al problema. El de nodos y el de mallas podemos decir que son los que nos permite resolver el problema optimizando tiempo, aunque cabe mencionar que va a depender del ejercicio y el método que más nos convenga. 

- Nos deja claro que existe una relación entre el magnetismo y la electricidad debido a que los electrones se mueven dentro del átomo y este se orienta en una dirección produciendo asi el magnetismo.
# BIBLIOGRAFIA #
