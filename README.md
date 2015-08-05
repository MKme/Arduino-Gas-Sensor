# Gas-Sensor-Grenade
Repository for the Hackaday project Gas Sensor Grenade with Arduino

Gas Sensor For Emergency Workers
Gas sensor "grenade" that may save lives instead of taking them. The sensor can be thrown into dangerous areas to remotely report levels

https://hackaday.io/project/4742-gas-sensor-for-emergency-workers

In my professional life I have used many different gas analyzers for confined space entry as well as emergency response. These units are very expensive and require the user to be able to read the display or be close enough to hear the alert generated if an unsafe condition exists where human entry would need other measures. 

I made this to be a very cheap and easily reproduced product which could simply be thrown into any uncertain environment such as a confined space, building with a possible gas leak, fire etc. Any potential entry person can just toss the ball into the area and remotely receive the gas and smoke levels via voice from several hundred meters away. 

I used an MQ2 smoke, LPG (Liquified Petroleum Gas), and CO (Carbon Monoxide) sensor. I used freely available code to get the sensor working with an Arduino Nano. Then taking an Ultra Cheap 433MHZ transmitter to output real voice transmit to any basic radio within the area