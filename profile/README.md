# Serialblocks

## **Introduction**

serialblocks is an opens-source project that combines web development with embedded systems

you get to communicate with a real hardware like an Arduino through an interactive web based interface

whether it was connected to your machine , a machine on the same network or a remote machine some where else!

## **features**

- list serial ports
- connect/disconnect to serial port
- communicate (read/write) to/from the microcontroller through serial communication
- visualize data using line charts and in the future more data visualization methods
- through the Terminal block
    - change serial port settings [baudrate, data bits, stop bits, parity, etc]
    - toggle timestamp
    - simulate live data
    - toggle autoscroll
    - clear terminal output

across clients notifications (someone connecting to your server, opening/closing a serial port on your machine)

easy to code/work with prebuilt blocks 

that let’s you blink first led / graph data / read from a sensor / change color of an RGB led

## **how it works**

- with serialblocks you get to communicate with your microcontroller through a react web based interface
- through socket connection between the client and the server which is a nodejs server that you run locally that interacts with your microcontroller
- through **[Node SerialPort](https://serialport.io/)** package

the user will need to run serialblocks-local on his/her machine which is a nodejs server that interacts with **Serial devices** **[Node SerialPort](https://serialport.io/)** package

after [running](https://www.notion.so/Serialblocks-labs-33152387c628481bbe41b0e766a0d3d3?pvs=21) Serialblocks-local locally on your machine on which you will connect your microcontroller to through serial communication (UART)

if you don’t have a microcontroller and want to test Serialblocks you can just use VSPD

after [running](https://www.notion.so/Serialblocks-labs-33152387c628481bbe41b0e766a0d3d3?pvs=21) serialblocks-app whether locally or just by visiting the online version [serialblocks-app.vercel.app](http://serialblocks-app.vercel.app)

## **backstory**

serialblocks is an extension to my graduation project for my electrical engineering degree

As a group we wanted to create a GUI for an STM32 based UTM ([Universal Testing Machine](https://en.wikipedia.org/wiki/Universal_testing_machine)) 

I wanted to try something new and create it using modern web technologies 

as someone who have been passionate about web development 

I saw that it was going to be a great chance to put my skillset into practice and create something as unique and new as a GUI for a real life machine

unfortunately we didn’t get proper funding to get sensors for what a UTM would need like a load cell sensor

so I started off of something simple like a temperature sensor which luckily my STM32 had built in already so it was really easy to interface with and I kept on adding more features ever since

## Installation

## **Usage**

Connect to multiple microcontrollers connected directly to your machine.

(running serialblocks-app locally or from the online website)

Connect to multiple microcontrollers not connected directly to your machine, but to a machine on the same local network.
(If you're exclusively running the SerialBlocks-app locally.)

Connect to multiple microcontrollers online that’s not connected directly to your machine nor to a machine on the same local network 

through exposing that machine’s nodejs local server using [localtunnel](https://github.com/localtunnel/localtunnel) to the world

## **contribution**

also serialblocks is opensource with plenty of first good issues to contribute to
whether you are a web developer or an embedded systems developer you will be able to contribute to serialblocks
