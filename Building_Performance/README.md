# Building Performance Improvement Problem 🏢

Many buildings in the University of Waterloo campus were built in the 1950s –1990s and now struggle with inconsistent energy efficiency performance. To meet climate change action goals, UW must significantly reduce emissions by reducing the energy required to sustain the operations of campus buildings. 
Several buildings on campus, such as MC, DWE, and RCH, exhibit aging designs in multiple areas such as heating/cooling, building envelope, lighting, etc. Since these buildings are designed at a time where energy efficiency is not a priority concern, it is now apparent that the systems in these buildings need improvement. Although buildings such as E7 and QNC are relatively newly constructed, they also face challenges adopting to a climate that has more hot days and more freezing days.  

## 📌 Project Overview
Choose one building at UW (Any teaching, residence or plant operations building) and propose a building performance retrofit strategy that reduces the energy required to maintain its operation. After the modification, the building should still be maintained at a comfortable temperature, supply all appliance usage, and support full capacity operation for student usage. 

Your modification can not only focus on reducing the energy consumed by the building, but can also focus on human accessibility in the building, as well as improving environmental interactions between the building and nature around it.Your solution does not have to cover an entire building. You can choose to focus on a specific floor or even a specific space in that building.

While there are no strict budget and timeline requirements, consider whether your solution's impact can justify your project's spending and time. Also, consider why your solution is beneficial to the campus beyond saving energy usage and carbon emissions.

 The presentation of your solution can include a pitch deck for your solution, a prototype of the new installation, or anything else that aids the demonstration.  

## Potential Solution
We highly recommend you visit sites/buildings that you are interested in improving in person, and record/measure the site to understand what you are improving better. 

## 🏗️ Sustainable Building Solutions & Resources

| Potential Solutions | 📝 Description | 🛠️ Technical Resources |
| :--- | :--- | :--- |
| **Retrofitted plans to increase thermal retention** | Improvements to building insulation or designs of entrance/exit doorways to minimize heat loss. | • FLIR camera (heat loss analysis)<br>• Environmental quality logger<br>• Energy consumption database |
| **Lighting energy optimization** | Reducing consumption via improved scheduling, automation, or retrofitting with efficient LED systems. | • Light sensors (brightness measurement)<br>• Microcontrollers + sensors for prototyping |
| **Heating efficiency improvements** | Investigating current heating methods and exploring more efficient, low-carbon alternatives. | • Microcontroller-based sensor package |
| **Shading infrastructure** | Automated shading for glass windows to mitigate summer heat gain and reduce cooling costs. | • Microcontroller + light sensors<br>• Craft papers for physical prototyping |
| **Passive building improvements** | Using natural elements (like plants) to shade buildings in summer or redirect snow in winter. | • Craft papers + wood planks for scale models |
| **Building Monitoring/Adaptation to Climate** | Use a system to adjust the building to a changing climate and a changing usage demand, or a system to monitor building usage/perforamnce | • Sensor packet<br>• AI prototyping tools for dashboards • Data analytics Models |
| **New infrastructure recommendations** | Proposals for new builds with strict protocols to minimize carbon emissions. | • Building modelling tools<br>• Crafting equipment |


## 💡 How to use this source code
An Arduino-based environmental sensor package is provided as a part of this challenge. This package has a click button, where you can switch the screen to display different sensor readings. This package can be used to collect data to support building your solution, or you can modify it to be a part of your solution! 
To switch sensor to display: hold the until screen changes, then release. 

Below are the current environmental data provided: 
- ambient temperature
- air humidity
- ambient light (output range: 0-800, brighter light = larger output)
- UV index

### Setup: 
1. Download Arduino IDE via:https://docs.arduino.cc/software/ide/
2. Navigate to the src folder, copy and paste main.cpp into a new Arduino project
3. Use the book icon at the left of the IDE page to navigate to library manager, search and download the following: Adafruit GFX Library, Adafruit SSD1351 library, Adafruit BusIO， Grove Temperature And Humidity Sensor
    - make sure each library is at the newest version. You can select versions from the dropdown menu below each library
4. Click upload (right-pointing arrow) on the IDE to run the code on the sensor package


## Additional Resources: 
Several additional sensor modules are provided if you need more sensor measurements to support your project. Some potentially useful links are provided below. Please don't hesitate to reach out to the suppor team if there's any troubles during sensor setup. 
### FLIR One camera Instructions
A thermal camera is provided as part of the challenge resource to help you obtain better thermal data around the building. 
1. Download the Flir One app from your app store
2. Launch the application, then plug the camera into your phone's charging port
3. Press the power button at the bottom of the camera and wait. The module should first display an orange light, then flashing green when functioning
4. If the module has no response while powering or connecting, use the charging wire inside the case the charge the module, then retry.
### Sensors and resources
- general resource: a comprehensive introduction to sensors offered in the kit https://wiki.seeedstudio.com/Grove_Starter_Kit_v3/
- electric current sensor: https://wiki.seeedstudio.com/Grove-Electricity_Sensor/
- barometer sensor: https://wiki.seeedstudio.com/grove_barometer_sensor_spa06_003/
       - You MUST unplug all other sensors, and toggle the black switch on the shield to 3.3V before plugging this sensor in
### General Information
- building floor plans: https://uwaterloo.ca/plant-operations/floor-plans
- Energy Usage Dataset: Check datasets in Sustainable Energy Systems folder
- Environmental Office's [Ongoing Projects](https://uwaterloo.ca/sustainability-living-lab/catalogs/categories/climate-change-and-energy?page=0) for Inspiration
- Resources on green buildings: [Net-Zero Energy Ready Buildings](https://www.efficiencycanada.org/building-codes/net-zero-energy-ready-buildings-in-canada/),[Zero Energy Buildings](https://www.wbdg.org/resources/net-zero-energy-buildings)

---


