<p align="center">
<img src="github-logo.jpg" width="300" height="300">
</p>

[circleci-image]: https://img.shields.io/circleci/build/github/nestjs/nest/master?token=abc123def456
[circleci-url]: https://circleci.com/gh/nestjs/nest

  <p align="center">A decentralized platform for trusted Internet-of-Things</p>
    <p align="center">
<a href="https://www.npmjs.com/~nestjscore" target="_blank"><img src="https://img.shields.io/npm/v/@nestjs/core.svg" alt="NPM Version" /></a>
<a href="https://www.npmjs.com/~nestjscore" target="_blank"><img src="https://img.shields.io/npm/l/@nestjs/core.svg" alt="Package License" /></a>
<a href="https://www.npmjs.com/~nestjscore" target="_blank"><img src="https://img.shields.io/npm/dm/@nestjs/common.svg" alt="NPM Downloads" /></a>
<a href="https://circleci.com/gh/nestjs/nest" target="_blank"><img src="https://img.shields.io/circleci/build/github/nestjs/nest/master" alt="CircleCI" /></a>
<a href="https://coveralls.io/github/nestjs/nest?branch=master" target="_blank"><img src="https://coveralls.io/repos/github/nestjs/nest/badge.svg?branch=master#9" alt="Coverage" /></a>
<a href="https://discord.com/invite/NQdM6JGwcs" target="_blank"><img src="https://img.shields.io/badge/discord-online-brightgreen.svg" alt="Discord"/></a>
<a href="https://twitter.com/FidesInnov93442" target="_blank"><img src="https://img.shields.io/twitter/follow/nestframework.svg?style=social&label=Follow"></a>
</p>


FidesInnova is a decentralized platform based on blockchain and zero-knowledge proof (ZKP) for automatic and authentication-free communication among Internet-of-Things (IoT), smart homes, and wearable devices.

The FidesInnova platform contains several network nodes distributed around the world. Each network node has:<br>
1- An IoT backend equipped with the MQTT protocol to communicate with physical IoT devices.<br>
2- A blockchain node that facilitates communication with other FidesInnova network nodes.<br>
3- A service contract management module that enables automatic communication between untrusted IoT devices and users without any authentication.<br>

Moreover, FidesInnova has a mobile application that allows network users to access their IoT devices and blockchain accounts and wallets on the network. The mobile application is available on Android and iOS.

FidesInnova introduced the concept of a Service Contract, which is a small program code to automate communication between IoT devices through the nodes. Service contracts can be managed (created/edited/browsed/enabled) through the Service Contract Management web app, which is available on each FidesInnova network node.

# FidesInnova Repositories 
#### To access the private repositories, please email info@fidesinnova.io

## A. FidesInnova IoT node 
### The IoT backend of the FidesInnova includes IoT server, web app, admin web app 
#### https://github.com/FidesInnova/iot_node_backend_web_app 

## B. FidesInnova blockchain node
### The FidesInnova blockchain network includes the validator and general nodes
#### [https://github.com/FidesInnova/iot_node_evm](https://github.com/FidesInnova/iot_node_evm)

### C. The FidesInnova mobile app
#### https://github.com/FidesInnova/mobile_app

## D. ZKP-enabled IoT hardware
### D.1. Zero-Knowledge (zk) MultiSensor
The zkMultiSensor is an IoT device that contains a thermometer, hygrometer, door sensor, motion detector, and a smart button. It can send data of the data-gathering environment with a ZKP (Zero-Knowledge Proof). It also supports an IoT mesh network protocol to let devices connect to the Internet without direct Internet access.
#### https://github.com/FidesInnova/hw_fidesinnova_multi_sensor

### D.2. Zero-Knowledge (zk) E-card
The E-card is an electronic business card to demonstrate the zkIoT functionality. The business card includes temperature and humidity sensors and a smart button.
#### https://github.com/FidesInnova/hw_fidesinnova_E-card_ZKP

