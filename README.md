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
### Transmitter (Remote Control)
<img src="https://github.com/Johnvy-M/COMMS-2-LAB.---Design-and-Implementation-of-an-NRF24L01-Based-Remote-Control-Car-System/blob/8f396f69fba7680d1aea0f787a1d499c7f849e13/RC%20PICTURE/37e8f280-c380-4548-810d-34ac6a2697b4.jpg" alt="RC">

<img src="https://github.com/Johnvy-M/COMMS-2-LAB.---Design-and-Implementation-of-an-NRF24L01-Based-Remote-Control-Car-System/blob/8f396f69fba7680d1aea0f787a1d499c7f849e13/RC%20PICTURE/db49eb16-7425-4ec3-9a2c-ef79feab1c84.jpg" alt="RC">

### Receiver 
<img src="https://github.com/Johnvy-M/COMMS-2-LAB.---Design-and-Implementation-of-an-NRF24L01-Based-Remote-Control-Car-System/blob/8f396f69fba7680d1aea0f787a1d499c7f849e13/RC%20PICTURE/0567cf76-3dea-4aaf-aaa5-36fedb001729.jpg" alt="RC">

<img src="https://github.com/Johnvy-M/COMMS-2-LAB.---Design-and-Implementation-of-an-NRF24L01-Based-Remote-Control-Car-System/blob/8f396f69fba7680d1aea0f787a1d499c7f849e13/RC%20PICTURE/c6be3bc8-a962-434e-84d0-5ba014b2a142.jpg" alt="RC">

 <img src="https://github.com/Johnvy-M/COMMS-2-LAB.---Design-and-Implementation-of-an-NRF24L01-Based-Remote-Control-Car-System/blob/8f396f69fba7680d1aea0f787a1d499c7f849e13/RC%20PICTURE/d8b09c5f-be3e-4d94-aa67-a3b72ffd45d8.jpg" alt="RC">

 <img src="" alt="RC">

 <img src="" alt="RC">

