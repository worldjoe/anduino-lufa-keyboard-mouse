This is the Arduino program that presses random alphanumeric keys (as well as the return character).

You need to build the following Arduino circuit:
![Snapino Circuit](Snapino.jpg)

I used [Snapino](https://www.amazon.com/Snap-Circuits-Snapino-Introduction-Educational/dp/B06XC8T8GB). But you could, likely, use any [Arduino Uno R3](https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6).

The only hard requirement is 5V must be connected to Analog input A0. When they are connected the program will press random keys. When they are disconnected the program will pause.
The lights are optional to let me know what the status is from across the room.
