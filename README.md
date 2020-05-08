# Loterioma
The main repository of the LoterioMa casino infrastructure project. It serves for documentation and organization of 
projects included in the system.

## Goal
The aim of the project is to create a complete and functional online casino system, containing a number of applications 
enabling casino management from the administrator and end customer side. The project is educational, aims to consolidate 
good programming principles in the practical example.

## Table of concepts

### System
~

### Components

##### Loterioma
The head system repository is for documentation and project purposes only.

##### Loterioma-core
The main application kernel, it is used for integration between systems.
*Technologies:* Symfony 5  
https://github.com/RaspberryVision/loterioma-core
https://github.com/RaspberryVision/loterioma-core/projects/1

##### Loterioma-client-basic
A very basic customer enabling connections to the casino and playing games in graphical mode.  
*Technologies:* HTML, JS

##### Loterioma-game-debugger
A simple application consisting of a form enabling the preparation of request parameters for a game engine, 
it is used only for development purposes.  
*Technologies:* HTML, JS

##### Loterioma-queue
An application that supports and monitors the casino's queue system.  
*Technologies:* ?

##### Loterioma-marketing
Marketing system enabling sending messages to users, creating mailing lists for different types of notifications.  
*Technologies:* ?

##### Loterioma-engineer
An application that collects information about the application development process and quality control.
*Technologies:* Symfony 5

##### Loterioma-game-certifier
The application is used for mass testing of the game in terms of certification of the random algorithm and the game 
parameters themselves.
*Technologies:* NodeJS

##### Loterioma-bank
Application enabling deposits and withdrawals of funds in the system.
*Technologies:* ?

##### Loterioma-manager
Casino management application, it is intended for administrators and presents all the information about the casino.  
https://github.com/RaspberryVision/loterioma-manager
https://github.com/RaspberryVision/loterioma-manager/projects/1

##### Loterioma-builder

##### Loterioma-engine

##### Loterioma-datastore

##### Loterioma-dice-engine

##### Loterioma-lobby
The main casino system for the customer is the base access client.
https://github.com/RaspberryVision/loterioma-lobby
https://github.com/RaspberryVision/loterioma-lobby/projects/1


## Milestones
What phases will the implementation be divided into?

1. Version Base

Project: https://github.com/RaspberryVision/loterioma/projects/1

The user:
- can register,
- logs into the system,
- sees the list of available games,
- sees he sees his profile data,
- can update the data in his profile,
- can choose the game and play (money issues are not checked at this stage)
- game history is saved,
- the system handles won rounds,
- can to show his rounds history,

The admin:
- can to login in manager,
- show all game types,
- show all games,
- show all users with CRUD operations,
- CRUD games,
- show all games history

2. Version 0.1

- add engineer services and QA tools,
- adding debugger component

3. Version 0.2

- adding bank application, 
- adding marketing

4. Version 1.0

- adding slots games,

5. Version 1.2

- adding roulette games,

6. Version 1.3

- adding lottery games,

7. Version 1.4
8. Version 1.5
9. Version 1.5beta
10. Version 2.0alfa - first public version

What functionalities must be included in each version?
