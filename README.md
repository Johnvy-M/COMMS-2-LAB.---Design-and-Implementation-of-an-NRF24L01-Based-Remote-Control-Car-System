<h1 align="center"> COMMS-2-LAB.---Design-and-Implementation-of-an-NRF24L01-Based-Remote-Control-Car-System </h1>

## **Overview**
This is a laboratory report on Communication 2. In this report, viewers can see the input, process, and the output of each experiments. The theoretical explanation behind it will also be discussed and how to use each discipline pratically.    

## Table of Contents
* Brief project description
* Block Diagram
* List of components
* Pictures inside (wiring)
* Picture of the Finished Project
* Codes
* Screenshot of approval
* Sample videos

## Brief project description
This project is focused on the development of a wireless Remote Control Car using the NRF24L01 transceiver module for reliable 2.4 GHz communication. The project developer is concerned for the incosistency that the bluetooth based connection has such as the delay, and the range limitation of it. The system is consists of transmitter and receiver unit, where user input commands are wirelessly sent to control the movement and steering of the vehicle in real time.

An arduino-based microcontroller is used to process signals and control the motor driver and steering mechanism. The car utilizes a motor driver module to manage forward and reverse motion, while a servo motor enables precise left and right steering. The NRF24L01 module ensures low-power, long-range communication between the controller and the vehicle.

The project aims to demonstrate efficient wireless communication, real-time control, and embedded system integration, making it suitable for applications in robotics, automation, and educational platforms.

## Block Diagram 

 <img src="https://github.com/Johnvy-M/COMMS-2-LAB.---Design-and-Implementation-of-an-NRF24L01-Based-Remote-Control-Car-System/blob/8f396f69fba7680d1aea0f787a1d499c7f849e13/RC%20PICTURE/Your%20paragraph%20text.png" alt="RC">

## List of Components 
### Transmitter (Remote Control)
* 1 - Arduino Nano
* 1 - NRF24L01 Transceiver module
* 1 - NRF24L01 Adapter module
* 2 - 170 point Breadboard
* 4 - Tactile Switches
* Jumper Wires
* Battery Holder

### Receiver (Car)
* 1 - Arduino Nano
* 1 - NRF24L01 Transceiver module
* 1 - NRF24L01 Adapter module
* 1 - TB6612FNG Motor Driver
* 2 - N20 Geared Motor
* 1 - MP1584EN Mini Buck Converter
* 1 - SG92R Servo Motor
* 4 - 34mm Rubber Wheels

## Pictures inside (wiring)
<details>
  <summary><b><i>Transmitter (Remote Control)</i></b></summary>
<img src="https://github.com/Johnvy-M/COMMS-2-LAB.---Design-and-Implementation-of-an-NRF24L01-Based-Remote-Control-Car-System/blob/8f396f69fba7680d1aea0f787a1d499c7f849e13/RC%20PICTURE/37e8f280-c380-4548-810d-34ac6a2697b4.jpg" alt="RC">

<img src="https://github.com/Johnvy-M/COMMS-2-LAB.---Design-and-Implementation-of-an-NRF24L01-Based-Remote-Control-Car-System/blob/8f396f69fba7680d1aea0f787a1d499c7f849e13/RC%20PICTURE/db49eb16-7425-4ec3-9a2c-ef79feab1c84.jpg" alt="RC">

</details>

<details>
  <summary><b><i>Receiver (Car)</i></b></summary>

<img src="https://github.com/Johnvy-M/COMMS-2-LAB.---Design-and-Implementation-of-an-NRF24L01-Based-Remote-Control-Car-System/blob/8f396f69fba7680d1aea0f787a1d499c7f849e13/RC%20PICTURE/0567cf76-3dea-4aaf-aaa5-36fedb001729.jpg" alt="RC">

<img src="https://github.com/Johnvy-M/COMMS-2-LAB.---Design-and-Implementation-of-an-NRF24L01-Based-Remote-Control-Car-System/blob/8f396f69fba7680d1aea0f787a1d499c7f849e13/RC%20PICTURE/c6be3bc8-a962-434e-84d0-5ba014b2a142.jpg" alt="RC">

 <img src="https://github.com/Johnvy-M/COMMS-2-LAB.---Design-and-Implementation-of-an-NRF24L01-Based-Remote-Control-Car-System/blob/8f396f69fba7680d1aea0f787a1d499c7f849e13/RC%20PICTURE/d8b09c5f-be3e-4d94-aa67-a3b72ffd45d8.jpg" alt="RC">

 <img src="https://github.com/Johnvy-M/COMMS-2-LAB.---Design-and-Implementation-of-an-NRF24L01-Based-Remote-Control-Car-System/blob/51ecd47088b29f265dab10733d94b8e37a90144d/RC%20PICTURE/0c07adda-f4bc-43c2-a4eb-3f77eb0adf52.jpg" alt="RC">

</details>

## Picture of the Finished Project

<details>
  <summary><b><i>Transmitter (Remote Control)</i></b></summary>
 <img src="https://github.com/Johnvy-M/COMMS-2-LAB.---Design-and-Implementation-of-an-NRF24L01-Based-Remote-Control-Car-System/blob/8d0086e20c872f9321bc691af05f7b63bfc9cdfb/RC%20PICTURE/33b9bae2-98e5-4a14-aff0-f1c99eac38aa.jpg" alt="RC">
 
 <img src="https://github.com/Johnvy-M/COMMS-2-LAB.---Design-and-Implementation-of-an-NRF24L01-Based-Remote-Control-Car-System/blob/8d0086e20c872f9321bc691af05f7b63bfc9cdfb/RC%20PICTURE/5d20673e-3d38-4180-82ff-bda166248e54.jpg" alt="RC">
 
 <img src="https://github.com/Johnvy-M/COMMS-2-LAB.---Design-and-Implementation-of-an-NRF24L01-Based-Remote-Control-Car-System/blob/8d0086e20c872f9321bc691af05f7b63bfc9cdfb/RC%20PICTURE/959a8d3f-2b1e-42d5-bed2-e087bcedc6e4.jpg" alt="RC">

 </details>

 <details>
  <summary><b><i>Reciever (Car)</i></b></summary>
 <img src="https://github.com/Johnvy-M/COMMS-2-LAB.---Design-and-Implementation-of-an-NRF24L01-Based-Remote-Control-Car-System/blob/8d0086e20c872f9321bc691af05f7b63bfc9cdfb/RC%20PICTURE/0715e494-4d96-4204-8da2-a3d69a8f9ef7.jpg" alt="RC">
 
 <img src="https://github.com/Johnvy-M/COMMS-2-LAB.---Design-and-Implementation-of-an-NRF24L01-Based-Remote-Control-Car-System/blob/8d0086e20c872f9321bc691af05f7b63bfc9cdfb/RC%20PICTURE/35222f06-a607-4045-8dd3-df0bc66d603e.jpg" alt="RC">
 
 <img src="https://github.com/Johnvy-M/COMMS-2-LAB.---Design-and-Implementation-of-an-NRF24L01-Based-Remote-Control-Car-System/blob/8d0086e20c872f9321bc691af05f7b63bfc9cdfb/RC%20PICTURE/3a5f9886-0240-40fd-8962-0dddc7df8f1d.jpg" alt="RC">

 <img src="https://github.com/Johnvy-M/COMMS-2-LAB.---Design-and-Implementation-of-an-NRF24L01-Based-Remote-Control-Car-System/blob/8d0086e20c872f9321bc691af05f7b63bfc9cdfb/RC%20PICTURE/5083c995-9c43-48de-9774-8a5a550a296f.jpg" alt="RC">

 </details>
 
 <img src="https://github.com/Johnvy-M/COMMS-2-LAB.---Design-and-Implementation-of-an-NRF24L01-Based-Remote-Control-Car-System/blob/8d0086e20c872f9321bc691af05f7b63bfc9cdfb/RC%20PICTURE/f2205664-8716-416d-a861-8a86cda6d820.jpg" alt="RC">

 <img src="https://github.com/Johnvy-M/COMMS-2-LAB.---Design-and-Implementation-of-an-NRF24L01-Based-Remote-Control-Car-System/blob/8d0086e20c872f9321bc691af05f7b63bfc9cdfb/RC%20PICTURE/2a265732-3a21-438c-b659-b5d4e4718707.jpg" alt="RC">


## Codes 

### Transmitter code 

<img src="https://github.com/Johnvy-M/COMMS-2-LAB.---Design-and-Implementation-of-an-NRF24L01-Based-Remote-Control-Car-System/blob/3ae3c82b21bec325901ea8e2e028eb2673a3cadc/CODES/transmit.png" alt="RC">

<img src="https://github.com/Johnvy-M/COMMS-2-LAB.---Design-and-Implementation-of-an-NRF24L01-Based-Remote-Control-Car-System/blob/3ae3c82b21bec325901ea8e2e028eb2673a3cadc/CODES/transmit2.png" alt="RC">


### Reciever

<img src="https://github.com/Johnvy-M/COMMS-2-LAB.---Design-and-Implementation-of-an-NRF24L01-Based-Remote-Control-Car-System/blob/3ae3c82b21bec325901ea8e2e028eb2673a3cadc/CODES/receiver.png" alt="RC">

<img src="https://github.com/Johnvy-M/COMMS-2-LAB.---Design-and-Implementation-of-an-NRF24L01-Based-Remote-Control-Car-System/blob/3ae3c82b21bec325901ea8e2e028eb2673a3cadc/CODES/receiver2.png" alt="RC">

<img src="https://github.com/Johnvy-M/COMMS-2-LAB.---Design-and-Implementation-of-an-NRF24L01-Based-Remote-Control-Car-System/blob/3ae3c82b21bec325901ea8e2e028eb2673a3cadc/CODES/receiver3.png" alt="RC">

<img src="https://github.com/Johnvy-M/COMMS-2-LAB.---Design-and-Implementation-of-an-NRF24L01-Based-Remote-Control-Car-System/blob/3ae3c82b21bec325901ea8e2e028eb2673a3cadc/CODES/receiver4.png" alt="RC">

<img src="https://github.com/Johnvy-M/COMMS-2-LAB.---Design-and-Implementation-of-an-NRF24L01-Based-Remote-Control-Car-System/blob/3ae3c82b21bec325901ea8e2e028eb2673a3cadc/CODES/receiver5.png" alt="RC">


## Screenshot of Approval
<img src="https://github.com/Johnvy-M/COMMS-2-LAB.---Design-and-Implementation-of-an-NRF24L01-Based-Remote-Control-Car-System/blob/fd6d8122399a9272740503e26262a2ff95e918d0/CODES/approval.png" alt="RC">

## Sample Video 

[![Watch the Video](https://github.com/Johnvy-M/COMMS-2-LAB.---Design-and-Implementation-of-an-NRF24L01-Based-Remote-Control-Car-System/blob/afeaea6c52670c47582e6facce02263318cdde1f/VIDEO%20presentation.png)](https://drive.google.com/file/d/1zIsu1MKTEFcTpOsH8T-EKASjUTMsQm5E/view?usp=sharing)




