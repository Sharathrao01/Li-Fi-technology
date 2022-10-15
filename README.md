<div id="top"></div>

<h1 align="center"><strong> Li-Fi-technology</h1>



<!-- ABOUT THE PROJECT -->


Real time data transmission using Light-Fidelity Technology.
<br><br>
 
 <strong>Introduction
 <br>
 Li-fi or Light Fidelity is one of the emerging technologies in the field of internet. Li – Fi Technology utilizes the principles of VLC (Visual Light Communication). Through Li-fi, data such as text, images, voice can be transferred. Data is transmitted in several bit streams and the receiver side consisting a Light-Sensitive-Device such as an LDR detects and decodes the message. The transmission happens in the form of binary data where “0” means LED in ‘OFF’ state and “1” means that the LED is in the ‘ON’ state. Transmitter and receiver sections contain Arduino UNO which are programmed using Arduino IDE. Studies and practical observations have shown that Li-fi technology is 100 times faster than Wi-fi, which uses Radio waves to transfer Data. 
 <br>
 
<strong>About the Project
 <br>
Here in this project, we will be demonstrating the transmission of ‘strings’ with the help of Li-fi Technology. A 24 Character text data is transmitted with the help of an LED Bulb. This data which is transmitted from the bulb, is received by an LDR (Light dependent resistor) on the receiver’s circuit. The data Received is decoded with the help of a decoder. This project also extends on implementing Li-fi technology to transfer patient data in hospitals, where the usage of radio waves may be harmful, hence Li-fi can be a safer and secure option.
 <br>
 
<strong>Problem Statements Considered
<br>
1)	In the existing system, the transmission rate of data transfer is relatively slow. But with the designed system, the data can be transmitted 100 times faster. 
 
2)	The traditional system uses radio waves to transfer data, which may not be safe for certain patients. With the implementation of this system, data can be transmitted with the help of light which may not harm such patients.

3)	Some of the present systems may leak the user’s data, which may result in privacy issues of the patient. Through our system data security is efficiently managed.

4)	Cost to maintain the present system may be a main factor of increased expenses, with Li-Fi such costs are significantly reduced.

5)	The current system in use solely depends on the network providers connectivity. Failing of such connectivity may lead to lack of network facility. With the proposed system, we can overcome such dependencies.
<br>
<strong>Description:

•	This system consists of two Isolated circuits
1)	Transmitter circuit
2)	Receiver circuit
•	It consists of two Arduino UNO boards.
•	The transmitter circuit mainly comprises of an LED bulb and a transistor.
•	The receiver circuit consists of an LDR (Light-Dependent-Resistor), comparator module and a display screen.
•	Data transmitted through the LED bulb of the transmitter circuit, is received by the LDR circuit and decoded. This decoded data is displayed on the LCD screen.
<br>
<strong>Block Diagram of Data Flow in Li-Fi
 ![block diagram](https://user-images.githubusercontent.com/86926101/196000699-f35a007e-a923-4ce3-a921-b88823ab4e72.png)

<br>


<br>
<strong>Circuit Diagram
<br>
<strong>Receiver Circuit

![Reciever](https://user-images.githubusercontent.com/86926101/195999775-8b3e554d-1543-4817-9275-19a2dcdb6cdc.jpeg)
<br>
<strong>Transmitter Circuit

![Transmitter](https://user-images.githubusercontent.com/86926101/195999800-1bc864ba-fcad-49e3-bfac-bde3ff595378.jpeg)
<br>
<strong>IMPLEMENTATION CIRCUIT

![circuit image'](https://user-images.githubusercontent.com/86926101/195999642-f4a13ca7-6fe8-47f6-9191-3ee629285af0.jpeg)
<br><br>
 Output LCD Screen
 <br>
![Output-image](https://user-images.githubusercontent.com/86926101/195999818-dede206e-f72d-4701-b4ab-7c18d735474e.png)
<br>
<u><strong>ADVANTAGES<u> 

a. Light has 10000 times wider bandwidth than radio frequency so the capacity of data transfer will be better than that of Wi-Fi. 
b. Instead of using radio wave, Li-Fi uses visible light for communication. 
c. Data transmission through Li-Fi is very cheap as LED uses very less amount of energy.
 d. Security of a Li-Fi network is much better because the light cannot penetrate the walls so no one can misuse the network. 
e. The shortage issue of radio frequency bandwidth may be solved by using Li-Fi. 
f. Using Li-Fi each street lamp can be used as a free data access point. 
g. Underwater Wi-Fi does not work at all, here Li-Fi can be used for data transmission.
<br><br><br>
 <u><strong>DISADVANTAGES</u>

a. The main problem with Li-Fi is how the receiver will transfer the data back to the transmitter.
 b. Li-Fi works on direct line of sight. 
c. The network topology is point to point. 



