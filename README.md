# Raspberry-Pi-Pico-Environmental-Temperature-and-Humidity-Monitoring-Device

The aim of this project is to build a device capable of monitoring the temperature and humidity of its surroundings using a Raspberry Pi Pico, a 16x2 LCD screen, and a DHT11 sensor. The project demonstrates how to effectively utilize Raspberry Pi Pico for sensor data collection and display.

## Technical Specifications:
  - Components Used:
    - Raspberry Pi Pico: The main microcontroller unit (MCU) for handling sensor data and controlling the LCD.
    - 16x2 LCD Screen with I2C Driver: Used to display real-time data such as temperature and humidity values.
    - DHT11 Sensor: Measures environmental temperature and humidity.

  - Software and Programming Language:
    - Thonny IDE: Used for writing and uploading MicroPython code to the Raspberry Pi Pico.

  - Python Libraries Used:
    - dht.py: For reading data from the DHT11 sensor.
    - i2c_lcd.py: For controlling the LCD screen via I2C communication.
    - lcd_api.py: For interacting with the LCD display.
    - pico_i2c_lcd.py: For setting up the LCD display with Raspberry Pi Pico.
    - In the main.py file, data from the DHT11 sensor is read and then displayed on the 16x2 LCD screen in real-time.

##Wiring Diagram:
The 16x2 LCD is connected to the Raspberry Pi Pico using I2C communication via the I2C driver.
The DHT11 sensor is connected to the Raspberry Pi Pico via the analog input, allowing it to collect real-time temperature and humidity data.
###########################################################################################################################################
![DEVRE ŞEMASI](https://github.com/user-attachments/assets/3a5e6ff2-df97-46d2-a90e-5e5feabf1896)

## How to Use:
  - Connect the DHT11 sensor and LCD screen to the Raspberry Pi Pico as per the wiring diagram.
  - Flash the MicroPython firmware to the Raspberry Pi Pico.
  - Upload the required Python files (dht.py, i2c_lcd.py, lcd_api.py, pico_i2c_lcd.py) and the main program (main.py) using Thonny IDE.
  - The device will begin displaying temperature and humidity data in real-time.

## Applications:
  - Home environmental monitoring (e.g., measuring temperature and humidity in living spaces).
  - Greenhouses or agricultural environments, to monitor conditions crucial for plant growth.
  - Any space requiring accurate and live environmental data.

## Future Work:
This device can be further expanded to include additional sensors (such as pressure or gas sensors) and upgraded to display more data on larger screens. Moreover, it could be connected to a network to log data online for remote monitoring.
