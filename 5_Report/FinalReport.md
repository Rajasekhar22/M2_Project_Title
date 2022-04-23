# Monitoring_Temperature_And_Controlling_Motor

##  ABSTRACT
This project is based on Controlling two more motors by using a switch and Monitoring the Temperature using DHT22/11 sensor. For Ac motors, we can use Relays to run another motor by energising the coil. For monitoring the sensor LCD 16x2 panel is used. This control of the motor using temperature is very much useful to control the motor in the industry. Industries, where there is a requirement for continuous operation of motors, can use this project. To prevent the motor from producing high heat and harmonics we go for controlling the motor using temperature. We can also be able to monitor the status of the motor using the LED provided to it. To improve the performance of the operation we can also use the timers to operate the motor by taking statistics of some reading provided by a sensor concerning the motor.


*   This project is based on Monitoring the temperature and controlling the motors.
*   This projects mainly used by Small scale/Large scale industries.

COMPONENTS REQUIRED

* ATMEGA328
* TEMPERATURE SENSOR -DHT22/11(POTENTIOMETER).
* DC MOTOR - 2.
* LED - 2.
* SIMULIDE(simulation).
* CODEBLOCKS.


## FLOWCHART

* CONTROLLING MOTOR

![MOTOR_CONTROL](https://github.com/Rajasekhar22/image/blob/main/2022-04-23-12-19-26.png)

* TEMPERATURE MONITORING

![MONITOR_TEMPERATURE](https://github.com/Rajasekhar22/image/blob/main/TEMP.jpeg)

* As i have used unstable version of Simulide i haven't got proper results even my code is correct.
* I have used potentiometer instead of that.

## PROCEDURE

* Temperature Monitoring
  * Temperature sensor(DHT22/11) is interfaced with the Atmega328 microcontroller chip.
  * In which it measures the temperature with some delay mentioned frequently and gives signals to MCU.
  * It is connected to PORT C for Analog to Digital conversion.
  * Using formulae the digital values are converted into deg. Celsius.
  * Now the temperature is displayed in LCD.

* Controlling motor
  * When Switch is in off condition Motor 2 is On and LED 2 will be glowing.
  * when Switch is in On Condition Motor 1 is On and LED 1 will be glowing.


## For Testing and using code

* Preferable Coding Software for Avr Coding is Microchip studio.
* You have to use C compiler with MINGGW(latest or the previous versions).
* Set path for MINGGW in Environment variables.
* To go with best compiler use VISUAL STUDIO CODE.
* In Visual Studio code you can also RUN the program in both LINUX and WINDOWS.
* Unit testing is done for Linux.

Conclusion
  
  Motor's connected are controlled using switch and temperature is sensed properly.
  
REFERENCES

* Referred temeperature sensor integration with Atmega328 MCU.
* Surefed in internet regarding AVR CODING.