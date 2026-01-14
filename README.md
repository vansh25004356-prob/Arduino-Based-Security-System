# PIR Sensor Based Security System using Arduino
PIR sensor–based security system using Arduino that detects motion and triggers LED and buzzer alerts.
---
# Project Overview : 

The goal of this project is to understand how **motion detection sensors interact with microcontrollers** and how real-world signals can be converted into hardware responses for security applications.

When motion is detected:
- The PIR sensor sends a HIGH signal to the Arduino
- Arduino processes the input using conditional logic
- LED blinks and the piezo buzzer beeps to indicate motion detection

---

# Components Used : 
- Arduino UNO  
- PIR Motion Sensor  
- LED  
- Piezo Buzzer  
- Breadboard  
- Connecting Wires  

---

# 🛠️ Tech Stack : 
- Embedded C / Arduino IDE  
- Digital Input/Output  
- Microcontroller Programming  

---

# 🔄 Working Principle : 
1. PIR sensor continuously monitors motion.
2. When motion is detected, it sends a HIGH signal to the Arduino.
3. Arduino reads the signal using `digitalRead()`.
4. Based on the condition:
   - LED blinks
   - Buzzer beeps
5. Alerts stop when motion is no longer detected.

---

# 💡 Key Learnings
- Sensor interfacing with Arduino  
- Digital I/O control  
- Conditional logic in embedded systems  
- Debugging hardware–software interaction  
- Understanding real-time system behavior  

---

# ▶️ Simulation / Demo
<img width="851" height="562" alt="Tinkercad_Simulation" src="https://github.com/user-attachments/assets/f692ebde-0712-49d3-a9c5-131697f1a7a2" />


---

# 🚀 Future Improvements
- Add GSM / WiFi module for remote alerts  
- Integrate mobile notifications  
- Log motion detection events  
- Combine with camera module  

---

# 📌 Author
Vansh Nain
B.Tech AI & ML Student  
Interested in IoT, AI/ML, and Software Development
