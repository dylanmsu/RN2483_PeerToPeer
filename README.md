﻿# RN2483_PingPong
 
 This is an example on how to use the RN2483 LoRaWan modem to acheive peer to peer communication.
 
 It broadcasts data and afterwards it starts listening. if the module then receives a packet, it will print it to a serial monitor and broadcast another packet. If two of these devices are in reach of eachother they will constantly transmit back and forth.
 
 This was tested on a RN2483A with firmware version 1.0.4.
