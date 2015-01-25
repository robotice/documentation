.. Robotice documentation master file, created by automat

================
Robotice Project
================

Quick Overview
==============

Robotice is autonomous agent-based system aimed to solve common life problems. It makes use of modern single-board computers as well as virtual resources of cloud for scalable computing.

Architecture
------------

Robotice consists of two separate major systems. Where Robotice Agent System is a standalone entity and Robotice Control System is designed to operate multiple agent systems.

* **Robotice Agent System** - A light-weight system for interfacing physical sensors and actuators, capable of autonomous operations with a little need for CPU and memory resources.
* **Robotice Control System** - A multitenant system for controlling multiple Robotice Agent Systems, it provides UI for planning and device manipulation and provide compute-intense services for i.e. motion or face detections.

Use Cases
------------

Robotice can be used in many ways, the following illustrate some of the major areas of focus.

* **Gardening Automation** - Integrate various hardware sensors and actuators to support gardening automation. Automate light cycles with watering cycles based on actual soil moisture or predefined plan.
* **Security and Surveillance** - Interact with cameras to capture and evaluate the data for alarms or other actions. Interact with  PIR sensors for motion or humidity sensor or buttons for opening detection.
* **Intelligent Living** - Improve quality of life by controlling the living environment and adjusting the parameters like temperature, light or humidity according to outside conditions or personal preference. Or use it as a simple meteorological station.
* **ICT Service Monitoring** - React to operations problems (heavy loads, hardware malfunctions) by communicating with external monitoring and configuration management systems.

More information
-----------------

* :doc:`Architectural Overview <intro/overview>` - Read more about Robotice architecture
* :doc:`User Interface Screenshots <intro/screenshot>` - Real-work GUI screenshots

Hardware Support
====================

Robotice uses Linux operating system to access physical devices. Suitable Linux can be installed on wide range of supported devices.

Computing Devices
-----------------

* :doc:`Single-board ARM Computers <hardware/computer/arm>`
* :doc:`Intel x86/64 Computers <hardware/computer/intel>`
* :doc:`USB Extensions<hardware/computer/usb>`


Physical Sensors
----------------

* :doc:`Air Humidity<hardware/sensor/air_humidity>` - ratio of water vapor pressure to the equilibrium vapor pressure of water (DHT11, DHT22, HTU19D)
* :doc:`Air Pressure<hardware/sensor/air_pressure>` (BMP)
* :doc:`Distance<hardware/sensor/distance>`
* :doc:`Electric Button<hardware/sensor/electric_button>`
* :doc:`Electric Current<hardware/sensor/electric_current>`
* :doc:`Light/Luminosity<hardware/sensor/light_luminosity>` - a measure of the intensity of light that hits a surface (TSL2561, TSL2591, CdS)
* :doc:`Liquid Flow <hardware/sensor/liquid_flow>`
* :doc:`Liquid Level <hardware/sensor/liquid_level>`
* :doc:`Liquid pH<hardware/sensor/liquid_ph>` - acidity or basicity of an aqueous solution (AS pH Kit)
* :doc:`Soil Moisture<hardware/sensor/soil_moisture>` - the water content in soil (HygroMeter)
* :doc:`Temperature<hardware/sensor/temperature>` - a comparative objective measure of hot and cold (DHT11, DHT22, HTU19D, DS18B20, TMP36)

Physical Actuators
----------------

* :doc:`Electric Switchich <hardware/actuator/electric_switch>`
* :doc:`Electric Power Modulation <hardware/actuator/electric_modulation>`
* :doc:`OLED Display <hardware/actuator/display_oled>`

Contribution
===========

* :doc:`Source code <contrib/git>`
* :doc:`How to add support for new device/sensor/actuator <contrib/new_device>`
* :doc:`Contributors <contrib/contributors>`
