INTRODUCTION:

Automatic Railway Gate Control System is a simple but very useful project, which helps in automatically opening and closing the railway gate upon detecting arrival or departure of the train.

In general, Railway gates are opened or closed manually by a gate keeper. The information about arrival of train for opening or closing of door is received from nearby station. But some railway crossings are totally unmanned and many railway accidents occur at these unmanned level crossings.

To avoid the human intervention at level crossings completely, we need to automate the process of railway gate control.
The aim of this project is to save lives of people who are crossing unmanned railway crossings; by providing an automatic railway gate solution. It also deals with the reduction of time for which the gate is being kept closed. 

By employing the automatic railway gate control at the level crossing the arrival of the train is detected by the sensors placed near to the gate. Hence, the time for which it is closed is less compared to the manually operated gates.
The operation is automatic; error due to manual operation is prevented. Automatic railway gate control is highly microcontroller based arrangements, designed for use in almost all the unmanned level crossing in the train.

A major implementation in our project is the use of LCD displays, not only to provide information about the train arrival and departure, but also providing a provision of displaying advertisements of growing companies. This will help government in its regular revenue.


APPLICATIONS AND BENIFITS:

If installed in unmanned railway crossings, it prevents accidents and saves lives.
1.  Saving lives of people
2.  Eco friendly solution
3.  Low cost
4.  Can be easily installed


COMPONENTS USED:

1.	Node MCU (ESP8266)
2.	IR Sensors
3.	Servo Motors
4.	LCD Display
5.	Buzzer
6.	LED lights
7.	Bread Board, Wires and Power Supply

PRINCIPLE OF OPERATION :

The principle of operation behind the working of this project lies in the functioning of IR Sensor. A Reflective type IR Sensor is used in this project.

In Reflective Type IR Sensor, the IR transmitter and receiver are placed side by side. When there is no obstacle in front of the sensor, the IR rays transmitted by the IR Transmitter will travel undetected as there are no rays falling on the IR Receiver.

If there is an obstacle in front of the IR Transmitter and Receiver pair, the IR Rays gets reflected off from the surface of the obstacle and are incident on the IR Receiver.

This setup can be configured to detect an object like a Train and in turn can be used to switch ON or OFF the loads like motors with the help of microcontroller like a NodeMCU. 

The NodeMCU powers the servo motors to function in order to open or close the gate whenever IR detects a train coming towards the railway crossing and when it leaves.

A buzzer is incorporated to function along with the servo acting as gates to alert the people of closing of gate.
The LCD display meassages regularly about the status of the crossing. LEDs are used to inform the trian driver of any distortion present between the crossing path. 

Another IR sensor is placed in the scope of the railway gates to detect any obstacles like vehicles which are jammed in between the gate and not able to move quick enough before the train could arrive.

In such a situation, an LED placed at approx. 500 mts from the gate would glow red indicating the train driver of some problem ahead and needs to slow down or stop the train. If this IR is clear then a green LED glows indicating a Safe to move signal. 
Real time notifications about the Railway Crossing is sent to Railway Administrator Office in order to keep track of the functioning of railway crossing.
