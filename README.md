# RPISmartHome
A simple Python on Raspberry PI project to add a layer of intelligence to home heaters

The goal of the project is to drive a heater connected to a smart plug using a machine learning model, predicting when to turn it on and off to keep the room temperature as level as possible. 

Project uses
- Raspberry PI OS 
- BME280 sensor
- Adafruit NeoPixel 
- Meross Smart Plug

- Python libraries (Pandas, NumPy, Meross, Bokeh)
- SQLite
- Apache

Model will use the 
- sensor data from BME280 sensor - temperature, hpa, humidity
- external temperature from a public weather station
- power consumption from a Meross SmartPlug 

