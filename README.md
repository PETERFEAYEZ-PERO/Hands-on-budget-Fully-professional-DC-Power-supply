Here is a fully DC power supply with implemented Safety features, real-time MCU control, Voltage & Current adjustment, a cooling system, a wireless charger, and an LCD Display for output voltage.
This Project is Part of -Making My Lab- series.


# ⚡ Adjustable Smart Bench PSU

A modular laboratory power supply designed from scratch with
real-time monitoring, protection systems, and scalable multi-output architecture.

Part of the "Building My Lab From Zero" series.


# Contents:

1- The main identity and features                                                                              
2- Why DIY, not buy a new, ready-made one?                                                                      
3- list of materials and cost                                                                        
4- The System Architecture flow                                                               
5- The main system Parameters                                                               
6- The automation and building process (METHODS)                                                               
7- Coding-related Part                                                               
8- Documented Failures                                                               
9- Outcome                                                               
10- Safety features and precautions                                                               
11- Upcoming Progress                                                               
12- References                                                               
13- Acknowledgments                                                               
14- Contact                                                               
15- License                                                               


## The Main identity and features:

I had always dreamed about owning an awesome power supply for my projects, a cable to handle various projects, ideas, and testing loads.
Unfortunately, the features, design, and flexibility I need would cost me a lot of money. So I decided to make my own. Additionally, as I had no workshop, no tools, no devices, or anything, I found it cool to make a full series on building my lab. 


### The Features I was dreaming about:                                                               
1- Adjustable DC power supply ranging from Lim➡️ZERo Till 24V.                                                               
2- Multi-port for output like 4 or 5.                                                               
3- LCD or high-quality screen, rather than 7-segment.                                                               
4- Nice Design.                                                               
5- High Safety features.                                                               
6- one or two Ac Ports.                                                               
7- one or two USB ports                                                               
7- Adjustable Wireless Charger.                                                               
8- Cooling System.                                                               
9- Data Logging, Graphing, and connection to PC or Lab capability.                                                               
10- Desktop APP                                                               
11- Short Circuit prevention.                                                               
12- Battery Charging.                                                               
13- Cable for Modefecation.                                                                
14- OverVoltage Protection (OVP), OverCurrent protection (OCP), and OverTemperature Protection (OTP)                               
15- PID controlling


So, to find these features in PSU nowadays would cost a bunch of money, about -------, and this is actually quite expensive for every beginner.
For that sake, I made Making My lab series, where I will make a full lab device open-sourced for all around the world.
Additionally, you don't have to make the full project; there are versions of this project and other alligments I will provide through the journal file, and the system architecture part in that Readme, so make whatever you need. Also, I am available all of the time answering your questions and giving you help❤️ in any kinda of projects, whatever it is. Just Feel Free to go for the Contact part.



## Why DIY, not buy a new, ready one??                                                             
Undergoing yet



## list of materials and cost                                                                        
### 🔌The Power section:
#### DC section:-
1) Power Adaptor AC to DC 24V and 5A                                                              
   cost Range from                                                              
2) Buck Converters for every DC port
                                                                
3) Rotary Encoder per Port                                                             
                                                                
4) Terminal Blocks
                                                                
5) Wiring
                                                                
6) Ports                                              

#### AC Power Section:-
External three AC power strip

#### Wireless Charger module:-
Wireless Charger Module


### 📟The Controlling section:-
1)- THE Microcontroller (MCU):                                    
<ul>
<li>Air001 MCU Cortex M0 core 32Kflash TSSOP20</li>                             
or                                                 
<li> ESP 32 (in case of making the final version)</li>
or 
<li>just any MCU (unless it fits the main parameters of the project)</li>
</ul>

2)- Current Sensor:
<ul>
<li>ACS 712</li>
</ul>

3)- Voltage Calibration circuit (Voltage Divider):-
<incline> under research until now </incline>

4)- Liquid Crystal Display (LCD):
Simply to display the voltage and current for every port, additionally warning in case a short circuit occurs.

5)- Buzzer:
For a short circuit warning.

6)- Relay module (Fuse integrated) for every port of DC and the wireless charger.

7)- Switch per every DC and the wireless charger.

8)- Circuit of continuous control for the fans and cooling.

9)- PiD controlling

### 🌡️ Cooling system & 🔐seafty control:

#### 🌡️Cooling System:
<ol>
<li>SSR Heatsink</li>
<li>Two or three Fans</li>
</ol>

#### 🔐 safety control:
<ol>
<li><strong> Main fuse after the power Adapter </strong></li>
<li>May be added fuse per every port</li>
</ol>
</br>


# The system architecture flow:
## The power Circuit:
<img width="1144" height="681" alt="the power shematic drawio" src="https://github.com/user-attachments/assets/372570cf-ef17-44f5-ab4c-59de6cc9f531" />




Upcoming progress:
