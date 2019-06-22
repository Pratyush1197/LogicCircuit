# LogicCircuit
A Javascript based digital logic circuit simulator
**Technologies Used**
HTML
CSS
Javascript
Jquery
node.js
Go.Js

This is a digital logic circuit simulator which is made with GoJs library and Vanilla Javascript. I t has all the logic gates (AND, OR, NOT,NOR,NAND,XOR and XNOR) fully functional with input and output ports provided for inputing the data and collecting it respectively.
 Project also has a BCD to seven segment display decoder library predefined which can be simply loaded by clicking the load button.
Uses of different gates is as follows
**INPUT** We can give any input just by dragging the input node to the drawing area and double clicking on it. It will open a small input box where youcan provide your value



![sav3_](https://user-images.githubusercontent.com/32239181/59966073-56496780-9534-11e9-896f-bf71886c1592.png)



**Output** We can get the output value when this is connected to endpoint. As at present its work is to show only the seven segment display so when the output is **one** it will display red LED of that particular segment  else it will be gray.It has seven output templates to take output for seven segments simutaneously.
**Gates** The gates works when we connect the wires with their ports we will get the output which can be calculated by taking out the wire from its output port.
**Multiplexer** Its work is to take four inputs and it has two select lines when we give it output in binary form (i.e 0 or 1) we will get the selected input as output


**BCD to seven segment display decoder**
Click on the load button. The Circuit will be loaded. Now the four input ports signify the four inputs with first input from left is MSB and last is LSB. Input is initially **zero**. Double click on any input port and set **one** as input. The color will be changed from red to green. When setting the value again to zero will make it red again. Now the four outputs from top represents segments from a to g
The logic is according to the following truth table.


![tru](https://user-images.githubusercontent.com/32239181/59966241-ed172380-9536-11e9-824b-4e70ef823d00.PNG)



Clicking on the clear button will reload the screen and clear all the circuits on the screen



![sav2_](https://user-images.githubusercontent.com/32239181/59966229-d96bbd00-9536-11e9-87cc-c9f7a7e6afe5.png)



![sa1](https://user-images.githubusercontent.com/32239181/59966203-695d3700-9536-11e9-8bf5-0affbef75568.png)

**RUN THE PROJECT ON BROWSER**
Given steps are to be followed to open the project

git clone https://github.com/Pratyush1197/LogicCircuit.git

cd LogicCircuit

Inside this folder you will find another folder logicCircuit. open it and open the logicCircuit.html on browser


