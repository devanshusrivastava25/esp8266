# esp8266 this code tells us about how to operate on the esp8266 module and perform various AT commands on it by ESPlorer.
Steps to perform below experiment-:
1- Start with RX Arduino line is pin 2, make TX Arduino line is pin 3.
2- So, connect the TX line from the esp to the Arduino's pin 2 and the RX line from the esp to the Arduino's pin 3.
3- The number of symbol changes, waveform changes, or signaling events across the transmission medium per time might be different for your esp.(9600)
4- check if the esp is sending a message and read the next character.
5- then delay command is used if you have to send the whole data at once.
6- the available() command is used to read the character and then println for printing that code new line by line, for each of the character's.
