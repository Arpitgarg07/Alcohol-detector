# Alcohol-detector

Nowadays drinking and driving is the most common threat to their as well as others’ life. We cannot stop people from drinking but we can avoid these accidents by checking the person of drinking also we can put these types of small devices in vehicles to assure that no drink and drive can further take place. Today we are going to make a simple alcohol indicator that can be used in small devices or for the demonstration of simple small projects for an Alcohol detector using Arduino.

## what is an Alcohol detector using Arduino?

The stuff we are going to used today to build an alcohol indicator is Arduino, LEDs, and an MQ-3 Alcohol sensor. There are many MQ-X sensors is available in the market for different uses but we are here going to use MQ-3 because it is best for detecting alcohol. The working of most of the MQ sensors is the same. They all contain a heating element that heats up a layer of conducting material whose resistance is continuously measured. Its resistance changes when fumes or smell from alcohol comes in contact with the MQ-3 sensor. Arduino based alcohol detector having the mq3 sensor the specification given above. which can be monitor in our IoT based alcohol detector project.

The sensor gives both digital and analog output. The difference between the two is very simple in digital output only high or low means either 1 or 0 is transmitted to a microcontroller but in the analog signal, a wide range of values from 0 to 1023 is transmitted to the microcontroller which corresponds to the intensity of alcohol in the nearby environment. The sensor is built out of LM393 IC which has an inbuilt amplifier that amplifies the voltage signal to the detectable range. Also, it has voltage comparators for efficient amplification. The amount of amplification can be adjusted with the help of potentiometers given on the sensor.

![logo](https://github.com/Arpitgarg07/Alcohol-detector/blob/main/Circuit%20Diagram)

### FEATURES AND APPLICATIONS: –

Sensitivity of Alcohol, Ethanol is good <br>
Easy to use and fix <br>
Adjustable value <br>
Low price <br>
Can be used in various alcohol detection projects <br>


### COMPONENTS NEEDED: –

Arduino Uno <br>
A red led <br>
An MQ-3 Alcohol sensor <br>
A breadboard <br>
Jumper wires <br>
220ohm resistor <br>

![logo](https://github.com/Arpitgarg07/Alcohol-detector/blob/main/components.webp)

### ALCOHOL DETECTOR WORKING: –

As the code starts it initializes the pin to which the sensor sends its data. Then is setup we define the type of function we want on the initialized pins like input or output. Then in the loop, we read the data available on pin 3 and then print that value on our monitor. We also check for the condition of sensor data to be either high or low and according to the condition led glows and turns off.
