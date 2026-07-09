# Building Performance 🏘
The building performance improvement section has been broken down into two sub-problems. Sub-problem 1a focuses on improving a pre-existing building's performance, while sub-problem 1b focuses on the next generation of sustainable building design. Read below for more detailed descriptions and challenges related to each sub-problem.

## Overview
In this challenge you will:

- **Choose** either Sub-problem 1a or 1b
- **Research** an existing or future UW building
- **Develop** a sustainable solution
- **Support** your proposal with data or prototypes
- **Present** your solution to the judges

## Table of Contents
- [Sub-problem 1a](#-sub-problem-1a-improving-building-performance)
- [Sub-problem 1b](#-sub-problem-1b-next-generation-sustainable-building-design)
- [Potential Solutions](#potential-solutions)
- [How to use this source code](#-how-to-use-this-source-code)
- [Additional Resources](#additional-resources)

## 📌 Sub-problem 1a: Improving Building Performance 
Many buildings in the University of Waterloo campus were built in the 1950s –1990s and now struggle with inconsistent energy efficiency performance. To meet climate change action goals, UW must significantly reduce emissions by reducing the energy required to sustain the operations of campus buildings. Several buildings on campus, such as MC, DWE, and RCH, exhibit aging designs in multiple areas such as heating/cooling, building envelope, lighting, etc. Since these buildings were designed at a time when energy efficiency was not a primary concern, it is now apparent that the systems in these buildings need improvement. Although buildings such as E7 and QNC are relatively newly constructed, they also face challenges adapting to a climate that has more hot days and freezing nights. 

### Requirements
Your solution must:

- Select one University of Waterloo building (teaching, residence, or Plant Operations).
- Propose a retrofit strategy that reduces building energy consumption.
- Maintain occupant comfort and full building operation.

### Design Flexibility
- Your solution **does not need to cover the entire building**.
- Your solution may also address accessibility or environmental interactions.
- There are **no strict budget requirements**, but cost-effectiveness should be considered.

### Deliverables
Your final presentation may include:

- Pitch deck
- Physical prototype
- Demonstration materials
- Or any other format that effectively communicates your solution

## 📌 Sub-problem 1b: Next Generation Sustainable Building Design
As universities expand to accommodate growing student populations and evolving research needs, new campus buildings must be designed to meet higher standards of sustainability, resilience, and long-term performance. At the University of Waterloo, future development must align with institutional climate commitments while supporting modern teaching, research, and student life. 

Unlike older campus buildings constructed in the mid-to-late 20th century, new facilities have the opportunity to integrate high-performance systems from the ground up. However, designing a new building today presents its own challenges. It must anticipate a changing climate with more extreme heat and cold events, incorporate flexible learning environments, minimize operational carbon emissions, and remain adaptable for decades of evolving academic use. 

New construction decisions—such as building orientation, envelope performance, structural systems, material selection, HVAC design, lighting strategies, and renewable energy integration—have long-term implications for energy use, occupant comfort, embodied carbon, and lifecycle costs. Early-stage design choices are critical to ensuring that the building operates efficiently while maintaining comfort, accessibility, and full functional capacity. 

### Requirements
Your solution must:

- Design a new academic building.
- Include site selection.
- Reduce operational energy use.
- Reduce embodied carbon.
- Maintain occupant comfort and indoor air quality.
- Support full academic functionality.
- Be resilient to future climate conditions.
- Visit the selected site to collect observations or measurements.

### Recommended Activities
You may also:

- Visit other campus buildings for inspiration.

### Deliverables
Your design may include:

- Drawings
- Models
- Simulations
- Prototypes
- Other materials that communicate your ideas

## Potential Solutions
**Before you begin**, you should visit the sites/buildings that you are interested in improving and record/measure the site to better understand what you are seeking to improve. Make sure you take pictures to document the area(s). 

**These aren’t the only solutions**, but these are some of the ideas that you can take inspiration from. Feel free to mix and match any potential solutions if you feel that it is appropriate. 

| Potential Solutions | Description | Resources |
| :--- | :--- | :--- |
| **Retrofitting plans to increase thermal retention of buildings** | Improvements to the building insulation, or designs of entrance/exit doorways. | • FLIR camera to examine building heat loss<br>• Environmental quality logger to log air quality<br>• Database on energy consumption for buildings |
| **Improving energy usage due to lighting** | Energy consumed from lighting the building can be reduced through methods such as improved light scheduling/automation, or retrofitting with more efficient lighting system. | • Light sensor to measure brightness<br>• Microcontroller + sensors to prototype control systems |
| **Improving energy usage due to heating** | Investigate how each building is heated and explore more efficient solutions. | • Microcontroller-based sensor package |
| **Shading infrastructure** | Automated shading for glass windows to mitigate summer heat gain and reduce cooling costs. | • Microcontroller + light sensors<br>• Craft papers for prototyping |
| **Passive improvements to buildings** | Using natural elements (like plants) to shade buildings in summer or redirect snow in winter. | • Craft papers + cardboard for building models<br>• Heliodons for building evaluation |
| **Building monitoring + adaptation to climate** | Use a system to adjust the building to a changing climate and usage demand, or create a system to monitor building usage/performance. | • Sensor packet<br>• AI prototyping tools for dashboards<br>• Data analytics Models |
| **New infrastructure recommendation** | Proposal of a new building and a series of protocols for that building to ensure minimal increase of carbon emissions. | • Building modelling tools<br>• Crafting equipment |




## 💡 How to use this source code
An Arduino-based environmental sensor package is provided as a part of this challenge. This package has a click button, where you can switch the screen to display different sensor readings. This package can be used to **collect data** to support building your solution, or you can modify it to be a part of your solution! 
To switch sensor to display: **hold** until screen changes, then release. 

Below are the current environmental data provided: 
- ambient temperature
- air humidity
- ambient light (output range: 0-800, brighter light = larger output)
- UV index

### Setup: 
1. Download [Arduino IDE](https://docs.arduino.cc/software/ide/).
2. Navigate to the src folder, copy and paste main.cpp into a new Arduino project.
3. Use the book icon at the left of the IDE page to navigate to library manager, search and download the following: Adafruit GFX Library, Adafruit SSD1351 library, Adafruit BusIO，Grove Temperature And Humidity Sensor.
    - make sure each library is at the newest version. You can select versions from the dropdown menu below each library
4. Click upload (right-pointing arrow) on the IDE to run the code on the sensor package.


## Additional Resources: 
Several additional sensor modules are provided if you need more sensor measurements to support your project. Some potentially useful links are provided below. Please don't hesitate to reach out to the support team if there's any troubles during sensor setup. 

### FLIR One Camera Instructions
A thermal camera is provided as part of the challenge resource to help you obtain better thermal data around the building. 
1. Download the Flir One app from your app store.
2. Launch the application, then plug the camera into your phone's charging port.
3. Press the power button at the bottom of the camera and wait. The module should first display an orange light, then flashing green when functioning.
4. If the module has **no response** while powering or connecting, use the charging wire inside the case to **charge the module**, then retry.

   For more information, navigate to [FLIR Cameras.pdf](./FLIR%20Cameras.pdf)
   
### Sensors and resources
- general resource: [a comprehensive introduction to sensors](https://wiki.seeedstudio.com/Grove_Starter_Kit_v3/) 
- [electric current sensor]( https://wiki.seeedstudio.com/Grove-Electricity_Sensor/)
- [barometer sensor](https://wiki.seeedstudio.com/grove_barometer_sensor_spa06_003/)

    > [!WARNING]
    > Before connecting the barometer sensor:
    > - **Unplug** all other sensors.
    > - Set the shield switch to **3.3V**.
  
### General Information
- [UW Building Floor Plans](https://uwaterloo.ca/plant-operations/floor-plans)
- [Energy data | Sustainability |  University of Waterloo](https://uwaterloo.ca/sustainability/our-progress/energy-data)
- [Environmental Office's Ongoing Projects](https://uwaterloo.ca/sustainability-living-lab/catalogs/categories/climate-change-and-energy?page=0)
- [LEED Attributes in EV3](https://uwaterloo.ca/environment/about/ev3-leedr-platinum-certified)
- [Campus Plan](https://uwaterloo.ca/campus-plan/university-waterloo-campus-plan)
- [Campus Progression Through Imagery](https://storymaps.arcgis.com/stories/7a05e37300114e0ca33d7b3cfc860dd8)

  

---


