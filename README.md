# Arduino-Range-Finder-and-Temperature-Reader
The setup function initializes the pins connected to the LEDs and the NewPing and DHT22 sensors. The loop function reads the distance measured by the NewPing sensor and lights up the appropriate number of LEDs based on the distance value. If the distance is less than or equal to 5 cm, the DHT22 sensor is used to read the temperature, and the temperature value is displayed on the LEDs.

The numar function is called to display the temperature value on the LEDs. The function takes a float value as input and extracts the tens and units digits of the value using the zeci and unitate functions, respectively. The zeci and unitate functions set the appropriate LEDs to display the tens and units digits, respectively.

Overall, the sketch is a simple example of how to control LEDs and read sensor data using an Arduino board.
