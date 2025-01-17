# Reservoir-Water-Level-Detection
The primary objective of this project is to create a robust embedded system capable of activating visual and audible alerts when water level is detected at a distance less than 10 cm from the sensor. To achieve this, the system integrates an ultrasonic sensor for distance measurement, along with LEDs and a buzzer for indicating proximity
The hardware configuration comprises the LPC1768 microcontroller interfaced with an ultrasonic
sensor and connected to digital output pins for controlling LEDs and a buzzer. Additionally, an
LCD display is integrated into the system using the I2C communication protocol, facilitating the
display of distance measurements.
In terms of software, the project leverages Embedded C programming language to orchestrate the
functionality of the microcontroller. GPIO pins are utilized for sensor interfacing and output
control, ensuring seamless integration of hardware components. The ultrasonic sensor serves as the
primary means of distance measurement, with the measured distance being processed to determine
if it falls below the predefined threshold of 10 cm. Upon detection of such proximity, the system
triggers the activation of LEDs and the buzzer, providing both visual and audible alerts to the user.
Simultaneously, the LCD display showcases the real-time distance measurement, enhancing
situational awareness.
Through meticulous design and implementation, the project underscores the effectiveness of
embedded systems in addressing real-world challenges while showcasing the versatility and
adaptability of the LPC1768 microcontroller platform.
