# Ceiling Fan Guru Overview
This is a SmartThings App that turns ceiling fans on when too warm, and off when comfortable or away. You can specify under which modes ceiling fans will operate and how long a period of inactivity will turn the fan off.  To implement separate zones, install separate named instances of the app. Learn more at LawsonAutomation.com.
# Required Devices
- SmartThings-supported temperature sensor or thermostat
- SmartThings-controlled ceiling fan(s)

# Optional Devices
- Motion sensor(s)

# Installation
To run this app you must cut and paste it into the SmartThings IDE as a new project and then publish it to your SmartThings hub from there.

# Screenshots
![screenshots](https://cloud.githubusercontent.com/assets/22286765/21753777/d265b1f0-d5a8-11e6-97d5-a8188bb3b427.png)

# Settings Explained
# Ceiling Fans
These fans will turn on when the inside temperature exceeds the specified set point and the other condition described below are met.
The speed and direction of a ceiling fan must be set on the fan itself as this app assumes a simple on/off switch
# Temperature Sensor
This is an indoor temperature sensor used to control the ceiling fans.
# Motion Sensors
If there is motion for any of these sensors, motion is considered to be present. This sensor is optional.
# Inactivity Minutes
When no motion is sensed for this amount of time, the ceiling fans are turned off. 
# Operating Modes
The mode(s) in which ceiling fans are permitted to turn on per this app. 
For example, a ceiling fan in a living room typically only operates during the 'Home' mode. 
A ceiling fan in a bedroom typically only operates during the 'Night' mode. 
Multiple modes may be selected. User defined modes are supported. 
If no Operating Mode is specified, the Home mode is assumed.
# Tips and Tricks
- If you have some ceiling fans associated with one or more motion sensors and some that are not, 
- install separate instances of Ceiling Fan Guru for each grouping of motion sensor.
- Likewise, if some ceiling fans operate under different modes, such as living room versus bedroom ceiling fans, install separate instances of Ceiling Fan Guru for each grouping of operating mode.
- If you manually switch off a fan, it will stay off until the next natural off/on cycle occurs.
