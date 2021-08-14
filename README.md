# automatic-light-system
In this project, we will see the Automatic Room Lights using Arduino
where the lights in the room will automatically turn ON and OFF by detecting
the presence of a human.
Such Automatic Room Lights can be implemented in your garages, staircases,
bathrooms, etc. where we do not need continuous light but only when we are
present.
Also, with the help of an automatic room light control system, you need not
worry about electricity as the lights get automatically off when there is no
person
So, in this project , we have implemented Automatic Room Lights using
Arduino and Ultrasonic sensor.
Out of the three components, the Ultrasonic Sensor is the one in focus as it is
the main device that helps in detecting humans and human motion.
In fact, the Automatic Room Lights project can be considered as one major
application of the Ultrasonic Sensor. A similar concept is being already
implemented in automatic toilet flush valves, hand dryers, etc.
<!--  WORKING OF THE SYSTEM -->
Arduino is a microcontroller which provides open source
platform to perform software and hardware operations. This
is an advantageous project as Arduino Uno and Ultrasonic
Sensor is used thereby lights in the room will turn ON
automatically by detecting a human motion and stay turned
ON as long as the person remain present in the room. At the
beginning, when no human is present in the room, the PIR
Sensor's OUT pin is in the LOW mode. Hence, light of the room
is OFF. The output of the Ultrasonic Sensor goes HIGH as the
person enters the room. Ultrasonic Sensor detects the
Infrared (IR) radiation in the room. The Digital pin 8 of Arduino
Uno is used to connect the Data OUT pin of Ultrasonic Sensor.
When this becomes HIGH, the activation of relay takes place
by Arduino Uno. So that relay pin is in the LOW mode; because
relay is an active LOW device. Now, the lights will turn ÓN. This
light maintains its state as ON as far as there is motion in the
room. If the person exits the room or takes a nap, the motion
in front of sensor stops and there will be no changes in the IR
radiations. Therefore, Data OUT pin of Ultrasonic sensor will
be in LOW mode. This leads to turn OFF the relay. So, relay
now is in the HIGH mode. Hence, room light will be turned
OFF.
