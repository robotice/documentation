
=================
Measuing Fan RPMs
=================

There are 3 kinds of fans:

* 2 wire fans are just power connections
* 3 wire fans have an extra OUTPUT from the fan to tell the (generally motherboard) what speed the fan is turning.
* 4 wire fans have that same output as 3-wire fans, but also a PWM input pin that you can drive with a regular old pwm output pin from an arduino (or motherboard).


3 Wire Fans - GPIO  Sensor
==========================

...

!http://i.stack.imgur.com/NprvN.jpg!

More information
----------------

* http://electronics.stackexchange.com/questions/79707/3-wire-fan-tach-why-using-only-one-wire-gives-a-signal

4 Wire Fans - GPIO Sensor/PWM Actuator
======================================

...

More information
----------------

* http://electronics.stackexchange.com/questions/62324/arduino-controlled-pwm-pc-fan
* http://formfactors.org/developer/specs/4_Wire_PWM_Spec.pdf
