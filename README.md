# Agtechcourse_finproject
Presentation and documentation of Meteosystem built as a final project.
This project aims to build a working weather station that can measure and report a number of environmental variables including:
* Temperature
* Relative humidity
* Barometric pressure
* Wind speed
* Sun irradiance
* Elevation
* Calculated VPD
* Calculated Evopotranspiration

Project images folder includes pictures of the components connected to the microcontroller.

List of components:

1.	GY-b11 280 barometric pressure sensor (also measures temperature and RH but not included in code)
2.	SHT3X temperature and Relative Humidity Sensor
3.	ADS1115 module (increases resolution- 2^16 bits) 
4.	Solar Radiation Sensor- model RY EBN1, sensitivity 277.01µV to W/M^2
5.	Wind three cup anemometer (not included in above picture because unable to calibrate. Included in code but set to a constant of 1m/s windspeed)
6.	Voltage Buck converter (check specific model)
7.	Breadboard
8.	Male-male and male-female jumper wires
9.	Esp32 microcontroller
10.	Plus and minus cable (the larger black cable that carries 12V to the voltage buck converter-check specific name). 
11.	Electrical box

