# Smart Water Tank Overflow Alert System

This is a simple and useful project that helps stop water from overflowing in a tank placed on the roof. It sends a wireless alert to a buzzer and light inside my home using two ESP8266 boards.

# What This Project Does

- A water sensor inside the rooftop tank checks if the water has reached the top.
- If it has, the first ESP8266 sends a wireless signal (using ESP-NOW).
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
 Breadboard                     1        
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


