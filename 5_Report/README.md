## WIPERCONTROLSYSTEM

<h2> ABSTRACT: </h2>

The STM32F407VG-Discovery board is used to implement a car wiper control system in this project. An electric motor drives the wipers on the windshield. The wiper arms are moved by an electric motor connected to a worm gear that provides the necessary force to a long rod. A wiper is a vital component that removes rainfall or any other liquid from the windscreen of a vehicle. The previous method required manual wiper activation, and raising the wiper was a tough task. As a result, this strategy is suggested as a solution to these problems. The project's purpose is to provide automated transmission to older cars in order to improve their systems. wiping system, to improve the system by adding a sensor and an actuator, and to develop a basic software that would function seamlessly with the framework. The principle of this proposed wiper system is similar to that of other existing conventional wipers.



<h2> OBJECTIVE OF THIS PROJECT: </h2>

The project should be done using timers and the sequence of flashing of LED's RED,GREEN,BLUE and the 4th acc mode either ON or OFF mode using STM32F407,buttons,4 LED's. If we press the buttons for a long period, the car should start or stop, and the wipers' speed mode should vary.

<h2> INTRODUCTION: </h2>

A wiper is a necessary component that cleans rainfall or any other liquid from the windscreen. Wipers are designed and manufactured to remove water from a windshield. Most cars have two windshield wipers, one for the back window, and one for each headlight. The rubber blade, the wiper arm that holds the blade, a spring linkage, and portions of the wiper pivots are all visible from the outside of the car. Under the wiper, there are around six pieces called pressure points or claws, which are little arms. As part of the literature assessment for this project, two innovations were examined. Both were created with different concepts and functioning mechanisms, but the identical goal of the automobile wiper working principle. The rain sensor was a multifunctional device for automatically washing a vehicle's windscreen when it became wet from moisture, precipitation, or even dirt. It functioned by reflecting light rays in a pleasing pattern within the windscreen.

<h2> COMPONENTS AND SUPPLIES: </h2>

- STM32F407 Discovery Board.


<h2> ADVANTAGES </h2>

- It is quite simple to use.
- Less energy is consumed.
- Rain sensor-based systems are extremely simple to install.
- Individual rain sensors are fairly inexpensive.


<h2> DISADVANTAGES </h2>

- The rain sensor is activated when water falls directly on it.
- When more components, such as a rain sensor, are required, the total cost of the system rises.
- To avoid false rain detection, rain sensors must make a judgement within a few minutes.


<h2> 4W & H (WHO,WHAT,WHEN,WHERE,HOW) </h2>

<h3> WHAT: </h3>


The operational speed of a vehicle wiper is controlled by a wiper speed control mechanism based on rain conditions. To generate, the control system incorporates a rain sensor (30) that detects rain conditions. The amplitude of an analogue signal depends on the detected rain conditions.


<h3> WHY: </h3>


To keep the windscreen clean enough to give adequate view at all times. #WHEN
The windshield wipers remove rain and snow from the windshield, while the headlights improve visibility at night.


<h3> WHO: </h3>


A wiper speed control system for an automobile manages the wiper's functioning speed in response to weather conditions.


<h3> HOW: </h3>


You can adjust the speed of the car wiper system according to the rainfall


<h3> WHERE: </h3>


In general, car wipers are controlled by the stalk on the right side of the steering wheel.


<h1> SWOT ANALYSIS: </h2>


<h3> STRENGTHS: </h3>

- Low Budget.
- Big Influence on the market.
- High Bargaining Power Supliers.


<h3> WEEKNESS: </h3>

- Structural Inertia.
- High Transaction Cost.
- No Focus on Private Sector.


<h3> OPPORTUNITIES: </h3>

- Emerging New Markets.
- Technological Development.
- Demand for Saver Equipments.
- Technological Lock in of Product.


<h3> THREATS: </h3>

- Low Bargaining Power Buyers.
- Highly REgulated Industry.
- Ethical Pressure.
- Econimical Crisis.



<h2> HIGH LEVEL REQUIREMENTS: </h2>

| ID | DESCRIPTION | STATUS |
|:---| :---------- | :----- |
|HL1 | CAR ON and OFF | IMPLEMENTED |
|HL2 | LED GLOWING IN SEQUENCE | IMPLEMENTED |
|HL3 | WIPER SYSTEM USING STM32F407VG | IMPLEMENTED |


<h2> LOW LEVEL REQUIREMENTS: </h2>

| ID | DESCRIPTION | STATUS |
|:---| :---------- | :----- |
|HL1 - LL1 | PUSH BUTTON | IMPLEMENTED |
|HL2 - LL2 | RED, GREEN, BLUE LED's | IMPLEMENTED |


<h2> FLOWCHART: </h2>



![FLOWCHAT](https://github.com/19wh5a0202-Ujwala/M3_WiperControlSystem/blob/bb11a20c9b26fbdcb7944bebaaea0b6d87edebc0/2_Design/Flowchart/FLOWCHAT.png)



<h2> BLOCK DIAGRAM: </H2>



![BLOCKDIAGRAM](https://github.com/19wh5a0202-Ujwala/M3_WiperControlSystem/blob/bb11a20c9b26fbdcb7944bebaaea0b6d87edebc0/2_Design/blockdiagram/BLOCKDIAGRAM.png)


<h2> TESTCASES: </h2>

<h3> HIGH LEVEL TESTCASE: </h3>

| Test ID	| Description |	Exp.i/p	| Exp.o/p |	Actual o/p | STATUS |
| :------ | :---------- | :------ | :------ | :--------- | :----- |
| 1 | If the BUTTTON is pressed |	program execution |	Microcontroller/Engine starts |	LED ON(RED) |	PASS |
| 2	| If the BUTTTON is pressed |	program execution	| WIPER starts | LED ON(BLUE)	| PASS |
| 3	| If the BUTTTON is pressed |	program execution |	WIPER starts | LED ON(GREEN) |	PASS |
| 4	| If the BUTTTON is pressed	| program execution	| WIPER starts	| LED ON(ORANGE) |	PASS |
| 5	| If the BUTTTON is pressed	| -	| Microcontroller/Engine stops	| LED TURNED OFF |	PASS |


<h3> LOW LEVEL TESTCASE: </h3>

| Test ID	| Description |	Exp.i/p	| Exp.o/p	| Actual o/p | STATUS |
| :------ | :---------- | :------ | :------ | :--------- | :----- |
| 1	| If the BUTTTON is pressed	| program execution	| Microcontroller/Engine starts	| LED ON(RED) |	PASS |
| 2 |	If the BUTTTON is pressed | program execution |	WIPER starts and speed of wiper is slow	| LED ON(BLUE)	| PASS |
| 3 |	If the BUTTTON is pressed | program execution	| WIPER starts and speed of wiper is moderate |	LED ON(GREEN)	| PASS |
| 4 |	If the BUTTTON is pressed | program execution | WIPER starts and speed of wiper is good	| - | PASS |
| 5	| If the BUTTTON is pressed | - |	Microcontroller/Engine stops | LED TURNED OFF	| PASS |



