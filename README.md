# Infection-control-robot

Introduction 
With the advancement in technology ,we can implement the face mask detection applications, temperature detection and hand sanitizing eqiupment in various places and enterprises to ensure safety.These steps are now done in manual way by which the person may get in contact with the other person while sanitizing and checking temperature might not be accurate. To mitigate the problem, aiming to increase safety,Contactless temperature sensing, Mask detection, Automatic hand san
itizing are used. Contactless temperature sensing subsystem relies on using temperature sensor,while mask detection performed by leveraging computer vision techniques on camera equipped , then the automatic hand sanitizing is achieved by the DC motor connected with the sensor and . Any person without temperature check, hand sanitizing and mask scan will not be provided entry. Only person having the conditions satisfied by the system is instantly allowed inside, else the buzzer will alert the security about the situation, if any violation of the condition is found.
The temperature sensor:It measures persons temperature using contactless IR sensor. The persons pass one by one. In case that persons temperature exceeds average human body, and then Arduino generates signal to lock the door and gives the audible alert through buzzer. Otherwise, the door is opened to let the person in. Mask detection using an camera. When the user switches on the kit then pi camera capture the images, In case that image does not contain mouth and nose, it means that person wears mask properly and corresponding door will be opened. However, if the person not wear a mask then generates signal to lock the door and also gives the audible alerts through buzzer.
Sanitization: when the person place the hands in front of the ultrasonic sensor it will detects the hands and process this data to raspberry pi then raspberry pi spray the sanitizer automatically. Here we are using DC motor as door.It provides the initial storage for the Operating System and files. The status of the work will be displays on LCD module.
 
Problem Statement
Due to the spread of covid-19 also called coronavirus, has affected almost every aspect of people’s lives globally. The government has set mandatory rules and made some procedures that followed by citizens,which includes thermal scanning, wearing of face mask and hand sanitization at the entry of crowded places, in order to control the flow of virus. The manual temperature scanning has many disadvantages,sometimes there will be a human error in reading values, and the man
ual system is not manageable in place where large number of people travels.

Objectives
Objectives for the proposed work is to identify if the person is following the rules specified:
 1. Detection of the person with and without mask.
 2. Design and develop a sensor based system to identify the body
 temperature.
 3. Design and develop a sanitization machine using DC motor.
 4. Develop an efficient communication system to notify, using the
 buzzer and LCD.

Result
The work Temperature and Mask Scan Entry System was designed an indoor measurement system to allow the people using some covid rules as body temperature ,automatic hand sanitizer and face mask detection. Arduino based contact less body temperature measurement and face mask detector which detects whether the person is wearing a
mask or not.
 
• Temperature Check: When a person is detected then the temperature of the person is checked using mlx90614 sensor. If the temperature is above threshold then 
  alert is given using buzzer. If the temperature is below threshold then the person is checked for face mask.
• Face Mask Detection: When the temperature is below threshold the facemask is detected using camera’s input.
• Alerting System: If the temperature is above the threshold buzzer supply is turned on by the Arduino and If person doesn’t wore the
  mask is alerted using LCD where some messages are displayed.
• Sanitization: If Temperature is normal and Person worn the mask,then sanitization is done by pressing push button.
