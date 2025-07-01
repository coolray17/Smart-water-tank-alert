# Smart Water Tank Overflow Alert System

This is a simple and useful project that helps stop water from overflowing in a tank placed on the roof. It sends a wireless alert to a buzzer and light inside my home using two ESP8266 Node MCU DEV boards.

# What This Project Does

- A water sensor inside the rooftop tank checks if the water has reached the top.
- If it has, the first ESP8266 sends a wireless signal .
- The second ESP8266 (placed inside the house) receives the signal.
- It turns on a buzzer and LED to let me know the tank is full.

# What I Will Use (Parts List)

 Part                           Quantity
 NodeMCU ESP8266-12F Dev Board              2        
 Water level sensor (YL-69 or wire probes)  1        
 Piezo buzzer                   1        
 LED                            1        
 Resistors (220Ω)               2        
 Jumper wires                   Many     
 Breadboard                     2       
 USB cables                     2        
 power bank   2        
 Plastic box                    1        

# How It Works

- The two ESP8266 boards use *ESP-NOW*, a simple wireless communication method.
- No Wi-Fi network is needed — the ESPs talk directly to each other.

# Why I’m Making This

- Sometimes my water tank overflows because I can’t see it.
- I want to learn about wireless circuits and ESP8266.
- I already have some experience with soldering and basic electronics.
  
# 3d view
## Sender
![WhatsApp Image 2025-06-30 at 17 30 53_0f1b8370](https://github.com/user-attachments/assets/59ffe9a7-0513-4fad-ad25-f6f352b7b126)
## Reciever
![WhatsApp Image 2025-06-30 at 17 30 53_7d63d393](https://github.com/user-attachments/assets/f144cde8-928c-4004-af45-8b7c8c73dae5)

# Schematics
## Reciever 
![Screenshot (43)](https://github.com/user-attachments/assets/337bdb2a-76bd-4c30-ab18-c09ecec25ab3)
## Sender
![Screenshot (41)](https://github.com/user-attachments/assets/88c6001e-82c6-49c0-8e52-3c376ea1ed17)

# BOM
## Bill of Materials 

| Part Name                           | USD Price | INR Price | Use                                                                 | URL                                               |
|------------------------------------|-----------|-----------|----------------------------------------------------------------------|---------------------------------------------------|
| NodeMCU ESP8266-12F (x2)           | $7.00     | ₹600      | Wi-Fi microcontroller (Sender/Receiver)                              | https://amzn.in/d/1jWkNOW                         |
| Water Level Sensor (YL-69)         | $1.75     | ₹150      | Detects water at top level                                           | https://amzn.in/d/gmEhWZw                         |
| Piezo Buzzer                       | $1.70     | ₹145      | Sound alert when tank is full                                       | https://amzn.in/d/9RHO6ZJ                         |
| LED Indicator                      | $0.50     | ₹40       | Visual indicator                                                     | https://amzn.in/d/dXMBDMe                         |
| 220Ω Resistors (x2)                | $0.50     | ₹39       | For LED and sensor protection                                        | https://amzn.in/d/gM10jbX                         |
| Breadboard (x2)                    | $5.85     | ₹500      | Circuit prototyping                                                  | https://amzn.in/d/gvRq4T8                         |
| Jumper Wires                       | $2.34     | ₹200      | Connecting components                                                | https://amzn.in/d/5XqQkZq                         |
| USB Cable (Micro USB)              | $6.55     | ₹560      | Power & program ESP                                                  | https://amzn.in/d/3oeRbop                         |
| Power Bank (10000mAh) (x2)         | $14.03    | ₹1200     | Portable power supply                                                | https://amzn.in/d/dWBRAmL                         |
| Battery                            | $13.90    | ₹1195     | Circuit testing & temporary receiver-side power backup              | https://amzn.in/d/d6negGQ                         |
| Plastic Enclosure Box              | $1.87     | ₹160      | Housing for receiver module                                          | https://amzn.in/d/asbaLp8                         |

| **Total**                                           | **$55.99**| **₹4789** |                                                                                                                        
