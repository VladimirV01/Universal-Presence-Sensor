# Universal Presence Sensor

This repository contains all the materials related to my **Universal Presence Sensor**, based on the **HLK-LD2410 radar sensor**.

![3D View of the Sensor](Pictures/3D_View_Top.png)  

---

## **Features**
1. **ESP01 Module Powered by ESPHome**  
   The sensor runs ESPHome for seamless integration with Home Assistant.  

2. **Presence Detection with HLK-LD2410/HLK-LD2410B**  
   These affordable radar sensors ensure reliable presence detection.

3. **Power Supply**  
   - Standard **DC barrel jack** for power.  
   - Supports input voltage up to **12V**.

4. **Configurable GPIOs**  
   The two available GPIOs can be configured to suit your specific needs.

5. **LED Strip Control**  
   - Supports brightness control for up to two 5V/12V standard LED strips via **PWM**.

6. **PIR Sensor Support**  
   Enhance presence detection with an additional **PIR motion sensor**.

---

## **Project Background**
This project began in **January 2023**, during the early days of my Home Assistant journey. At that time, presence sensors based on radar technology were expensive and hard to source in my country.  

While searching for an alternative, I discovered the **HLK-LD2410 sensors** on AliExpress at a very reasonable price. Excited by the opportunity, I purchased a few units and designed this sensor to integrate with Home Assistant using ESPHome.  

---

## **Use Cases**
Currently, I have **three sensors** installed in my home, each serving unique purposes:

1. **Bathroom Automation**  
   - Installed to automate the lights.  
   - Operates with a success rate of **99.5%**, with no false positives and almost no false negatives.  

2. **Work Desk Setup**  
   - Equipped with one radar and one PWM output to control a LED strip that illuminates my keyboard based on specific conditions.  

3. **Closet Lighting**  
   - Similar to the bathroom sensor, it controls the lights.  
   - Performance is slightly affected by the closet’s layout, as items may obstruct the radar’s view in certain scenarios.  

---

## **Why This Project?**
At the time, affordable radar-based presence sensors were a rarity. By creating this sensor, I managed to fill a gap in the market while learning and experimenting with Home Assistant and ESPHome.  

