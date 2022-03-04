# Automotive-Automation
The project includes the most often used sensor systems of modern automotive industry,showing their operating principle.  
The model that i developed uses an Arduino Nano V3 and several analogic and digital sensors to collect different types of data from projects's proximity.The entire amount of data is processed locally (the obtained data are compared with relevant threshold values, adapted to the environment) and an output is delivered.
Used sensors:
a)Light Intensity Sensor(analogic)- if the values obtained from the sensor are lower than an analog_threshold , the leds are turned on.
b)Ultrasonic Sensor(digital)- it calculates the distance between the sensor and the nearest object in front of it.A passive buzzer changes his tone and frequency depending on the distance.
c)Humidity Sensor(analogic)- if the values are greater than a specific threshold value, the module  powers up  the g9 servo motor, which moves from 0 to 90 degrees.
