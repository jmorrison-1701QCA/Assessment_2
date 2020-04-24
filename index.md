# 1701QCA Making Interaction - Assessment 2 workbook

## Breathalyser Game ##


## Related projects ##

### MQ-3 Arduino Alcohol Sensor ###

https://www.instructables.com/id/MQ-3-Arduino-Alcohol-Sensor/

![Image](P1.jpg)

The alcohol sensor project is using the same type of alcohol sesnor that is required for my design. This project helps me to understand how the to connect the MQ-3 to the micro:Bit. This project was used to help me understand the basics of the MQ-3 sensor and helped me get a better grasp on how to code with it.

### AAn alcohol tester with LED lights made with Zerynth ###

https://create.arduino.cc/projecthub/framan/an-alcohol-tester-with-led-lights-made-with-zerynth-fc9d9e?ref=search&ref_id=Alcohol%20sensor&offset=2

![Image](P2.jpg)

This project is similar to mine as it uses an MQ-3 Alcohol Sensor and connects it to sereis of LED lights. This has a similar design as to what I want to complete just with a alternative purpose. From this project was the basis of my idea of using LED lights, and helped me understand how to code them to react with the MQ-3 Acohol sensor.

### Arduino Alcohol Detector | MQ-3 Sensor ###

https://www.viralsciencecreativity.com/post/arduino-alcohol-detector-mq-3-sensor

![Image](P3.jpg)

The Arduino Alcohol Detector | MQ-3 Sensor project uses a MQ-3 Sensor and when over the set limiot the buzzer will go off. This is related to my project as it has the basis of when a certain B.A.C limit is reached it casues a reaction from an external device. This design allows me to veiw the etireity of the process that was required to make this and allows me to veiw the code.

### RING PONG ###

https://create.arduino.cc/projecthub/aerodynamics/ring-pong-b91a4f?ref=search&ref_id=RGB%20Ring&offset=0

![Image](P4.jpg)

This project created a game using the RGB Ring LED. This project is related to mie as it uses a RGB Ring LED which is what intented to be used in my project. This design allows me to understand the programming aspect and how to connect the Ring Light onto the micro:Bit.

### Gyroscope Fun with NeoPixel Ring ###

https://create.arduino.cc/projecthub/danionescu/gyroscope-fun-with-neopixel-ring-3a0b84?ref=search&ref_id=RGB%20Ring&offset=9

![Image](P5.jpg)

The Gyroscope project is related to this project as it uses readings from an external component then uses this reading and causes it to have a reaction with the Ring Light. This allows me to understand how to correctly connect and external device correctly.

### NeoPixel Animation with Gestures ###

https://create.arduino.cc/projecthub/danionescu/neopixel-animation-with-gestures-6322bf?ref=search&ref_id=RGB%20Ring&offset=19

![Image](P6.jpg)

The Geopixel Animation design project has similar factors to the current project underway. The project uses the same RGB Ring Light, and has a similar function of using reading from an external device to cause an action with the Ring Light. This allows me to understand the more complexe coding of the Ring light.

## Other research ##

### MQ-3 Alcohol Gas Sensor ###

https://components101.com/sensors/mq-3-alcohol-gas-sensor

This webpage was used to understand how to correctly wire the MQ-3 Sensor, and what each output on the sesnor is connected too.

### Learn Python - Full Course for Beginners [Tutorial] ###

https://www.youtube.com/watch?v=rfscVS0vtbw

This video was used to help learning how to program in python.

### Using an 24 Bit RGB Neopixel LCD Ring with Arduino ###

https://www.youtube.com/watch?v=ep82zvielUE

This video was used in the process of lighting up the RGB Ring Light as to understand the fundamental basics of operating the device.

## Conceptual progress ##

### Design intent ###
To create a mature social game that allows players to interact using a sensor.

### Design Concept 1 ###

A game that uses a sonic sesnor that is connected to a series of LED Lights.

This game involves a series of players or a single player to approach the sensor and try to get the greatest amounts of points. The points are determined by what colour light is lit by the sensor. 

The sonic sensor would be set on a timer and every 20 seconds it would read where the player is and light up the equivilant light.

This would repeat with each player.

![Image](Con_1.jpg)

### Design Concept 2 ###

A game that connects a movement sensor to a motor that rotates the sensor and when movement is detected a buzzer goes off.

This game can be played individually or with others.  The players are given a series of tasks (ie. twister, hopscotch, truth or dare etc.) and when the movement sensor is in their sector they all must freeze, no matter what position they are in. If the sensor detects movement the buzzer will sound and the team will either have a disadvantage next round or be out (it is ultimatley up to the players how they wish to use the equipment and what the rules are).

![Image](Con_2.jpg)

### Final Design Concept ###

A drinking game where each player breathes on an alcohol sensor, the sesnor then relays the level to a ring light that lights a certain colour (determined by the B.A.C) this colour determines what the strength of the next drink is.

This is a group game. At each turn the player uses the the Alcohol Sensor, once the level of B.A.C in their breath has been determined the player will drink the required drink and then complete a random activity (this can be determined by the colour or a alternative way). Once their turn is up the next player goes.

The type of alchol each colour represents is determined by the players, but the game is designed that as the B.A.C increases the Alcohol Content in the drink selected will decrease. 

This game will be using a MQ-3 Alcohol Sensor and 24 RGB LED Ring Module.

The game will be played off of a similar layout of a dartboard. This is so that the players can record what drinks each colour is for and for the activity points. This layout will also be a kind of box with a removable back, all the wires for this game will be run through the back of the board, this is due to the fact that this is a drinking game and if alcohol came in contact with the electronics the game would break. The removable back is so that the batteries are easily changed if they go flat.

![Image](Final.jpg)


### Interaction flowchart ###

![Image](Flowchart.jpg)

## Physical experimentation documentation ##

### Technical Development ###
'The technical developemnt for this project has only just recently begun due to wait on essential components.

![Image](Connections.jpg)
This is how the MQ-3 Alcohol sensor is going to be connected without using a breadboad, as it has been through the testing phases.

![Image](MQ-3_1.jpg)

![Image](MQ-3_2.jpg)

![Image](MQ-3_3.jpg)

This is how the Alcohol sensor has been connected through the developmnt stages, this is allowing me to fix an errors that occur, so that the entirity of the project has to be restarted.

![Image](Code.jpg)

The basic code that is required to operate the Alcohol sensor so that when exposed the amount on the microbit increases. This is completed by using the anologue read pin.

### Fabrication ###

The fabrication for this project has been in development since its conception. It hasn't been altered much from the original design, only twice. Once for the practical manner for protecting the electronics and the other for the aesthtic purposes

![Image](Diagram_1.jpg)

![Image](Prot_2.jpg)

![Image](Prot_1.jpg)

This prototype is built to a scale of 1:4.

## Design Process discussion ##

### Technical Development ###

To get to this point in development I went through the double diamond method.

The initial concept of the idea was created by looking online at multiple types of sensors, and seeing what was available to use. The next step was to experiment in what i belive would work with the MQ-3 sensor and how i wanted to implent into my project. The notion of using a breatlyser in a adult drinking game, was thouhgt of when i thought what fun it would be to use it in a drinking game. This idea was continusly developed and has only just begun evelopment phase of the double diamond.


#### Challenges Thus far ####

Challenges that have presented themselves thus far is having to learn how to understand the MQ-3 tables so that the breathalyser can be callibrated. This process has yet to be completed and is currently in the define phase of learning and understanding the code used to create the callibration using Raspberry Pi. 

Another Challenge that has been completed was the wiring required to correclty connect the Breathyliser to the micro:Bit. This process reached completion. The method used to reach the outcome was the Double Diamond method also. The Discover phase was looking online at Git Hub and Audino at projects using the MQ-3 Alcohol Sensor, and seeing how they wired their projects together. The Define phase was understanding what each output and input on the MQ-3 was, this was completed by looking at designs of the product and how each version differentiates. The development phase was connecting all the wires and testing to see if this gave the correct reading, this was done by placing a bottle of vodka over the senor and seeing of the number that was presented on the micro:Bit LED's changed. 

The final challenge that has been presented thus far is the connecting of the 24 x RGB Ring Light to the Breathalyser. This task is in the development phase. The Disocover phase was looking at the problem and finding ways that a code can be changed so that instead of the number increasing on the LED screen on the micro:Bit the lights on the Ring change as well. The Define phase was used to cross reference other works on connecting an LED to a micro:Bit as an output.

### Fabrication ###

The fabrication for this project has just entered into the development phase where materials are being bought and assembled. To get to this phase the double diamond method was also used. I had wanted to make something portable and simplistic, as this was a drinking game i hadnt wanted the design to be too complex and also wanted it to have some style features. Originally it was going to be similar to a board game. It was made apparent that this was not appropiate for a game that involved liquids, it was also suggested that the nature of the game would make certain components difficult to remember as the game progressed this changed the external design of the board so that a white board could be incuded so these components could be easily seen and . 

#### Challenges Thus Far ####

A challenge that presented itself was due to the nature of the game involving liquid it was likly that the electronics on the project would get wet and as such the game would be destroyed this was corrected when I went to find ways to keep the electronics out oif the way of the alcohol. I looked at alternative materials and containers that would protect the electronics. In the end inspiraction was taken from a Dart board and the idea of having a woodern box, with all the wiring inside and a detachable back for access to the batteries.

## Next steps ##
The next step for this project is to configure the MQ-3 sensor so that it reads a more reasonable amount becasue at this time the sensor is over sensitive. After this I will be working on getting the ring light correctly connected and collaborated into the breathalyser system. After testing to make sure all parts of the system are working correctly, the fabrication of the box design where will begin. Once complete the electronics will temporarily placed within the box to make sure the equipment still work as intended in a alternate setup, once all electronics are working correcly the wires will be permantly intergrated into the design. 

Audience Reaction and Interactions will begin once all electronics are permanently placed in the design,
