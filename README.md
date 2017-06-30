# Arduino Liquid Volume Sensor
A straight walled container liquid volume sensor build with an arduino uno and an air pressure sensor. I started this project under the guidance of my Calculus Professor Dr.Samuel Gross and continued working on it after I graduated.

![Poster](https://github.com/MrPlumbum82/arduino_liquid_volume_sensor/blob/master/img/Arduino-based%20Liquid%20Volume%20Sensor%20Project%2040w%2032h.jpg)

# Future Scope
In its current state the sensor can calculate the volume of a liquid only in a straight walled container given that the sensor has actually been collaborated with the same container and the same liquid. The next natural step would be to allow for a container of any shape or size. Also it would be nice to find a way to make the collaboration easier for the user.

The end goal is to create a fully automated, user friendly liquid volume sensor that could easily be integrated in existing automation systems.

# TODO
  - Buy a new Pressure Sensor
  - Rebuild a temporary setup for further experimentation
  - Rewrite the source code without the string class, rather use pointers in an array of chars (the String class consumes too much memory)
  - Research on how to use differential equations to make calculation more accurate in cases of rapid volume increase/decrease
