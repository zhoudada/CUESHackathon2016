# CUESHackathon2016-CoderDodge
### Screenshots
![coderdodgescreenshot](https://cloud.githubusercontent.com/assets/13993950/19841157/d43e393e-9efd-11e6-8ca3-d70cd0c22053.PNG)

CUESHackathon2016
### Inspiration
As engineering students who love coding, we realised that sitting at a laptop all day has huge consequences on our health, in particular, on our backs and necks. We often overlook this issue, and by the time we realise it, we have already got fat and unhealthy. Following the recent success of PokemonGo as people stormed out to streets to catch Pokemons, it has inspired us to create a game to encourage programmers to work out more.

### What it does
We have created connection between the BBC:Microbit and a laptop. By attaching a Microbit to yourself, you can play the games on your laptop by moving your body, and hence exercising your body.

### How we build it
We used one microbit to transmit its accelerometer-based data wirelessly to another Microbit connected directly to PC via USB.
The server program in PC then reads data from the Microbit connected through serial port. After that, the server parsed the raw data
into a class and passed it to Unity via socket. Finally, Unity games can use the those data as the game input.
