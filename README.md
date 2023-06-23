# Mobile-Phone-Detector
This useful, portable mobile transmission sniffer can identify the presence of an activated mobile phone at a distance of 1.5 metres. Therefore, it may be used to ban the usage of mobile devices in places like exam rooms and private spaces. It is helpful for identifying unauthorised video transmission and the usage of mobile phones for spying.Even when the mobile phone is in silent mode, the circuit may still pick up incoming and outgoing calls, SMS messages, and video transmission. When the Bug identifies an active mobile phone's RF transmission signal, it begins to beep an alert and the LED blinks. Up till the signal transmission stops, the alarm goes off.

# OVERVIEW
Mobile Phone Detector is a Circuit that detects the presence of Mobile Phone up to a certain range 
like 1.5 meter. It detects the phone when an incoming call or outgoing call is made or when an SMS 
is sent or received or any GPRS used.
When the circuit detects an RF signal from an activated mobile phone, it gives an indication 
by switching ON an LED. The LED will start blinking and continues to blink until
the incoming/outgoing signal stops. Mobile Phone detector can also be called as a Frequency 
Detector. Frequency Detector is simply a Current to Voltage Converter Circuit which detects the 
frequencies in between the range of about 800 MHz to 3GHz.

# CONCEPT
Mobile Phone Detector is a Circuit that detects the presence of Mobile Phone up to a certain range 
like 1.5 meter. It detects the phone when an incoming call or outgoing call is made or when an SMS 
is sent or received or any GPRS used.
When the circuit detects an RF signal from an activated mobile phone, it gives an indication 
by switching ON an LED. The LED will start blinking and continues to blink until
the incoming/outgoing signal stops. Mobile Phone detector can also be called as a Frequency 
Detector. Frequency Detector is simply a Current to Voltage Converter Circuit which detects the 
frequencies in between the range of about 800 MHz to 3GHz.
users on the same frequency is allotted 1/8 of the time and the signal is reconstituted by the 
receiver to form the speech. Peak power output of a mobile phone corresponds to 2 watts with an 
average of 250 milli watts of continuous power. Each handset with in a ‘cell’ is allotted a particular 
frequency for its use. The mobile phone transmits short signals at regular intervals to register its 
availability to the nearest base station. The network data base stores the information transmitted by 
the mobile phone. If the mobile phone moves from one cell to another, it will keep the connection 
with the base station having strongest transmission. Mobile phone always tries to make connection 
with the available base station. That is why, the back light of the phone turns on intermittently while 
traveling. This will cause severe battery drain. So in long journeys, battery will flat within a few 
hours. AM Radio uses frequencies between 180 kHz and 1.6 MHz, FM radio uses 88 to 180 MHz, TV 
uses 470 to 854 MHz Waves at higher frequencies but within the RF region is called Microwaves.
Mobile phone uses high frequency RF wave in the micro wave region carrying huge amount of 
electromagnetic energy. That is why burning sensation develops in the ear if the mobile is used for a 
long period. Just like a micro wave oven, mobile phone is ‘cooking’ the tissues in the ear. RF 
radiation from the phone causes oscillation of polar molecules like water in the tissues. This 
generates heat through friction just like the principle of microwave oven. The strongest radiation 
from the mobile phone is about 2 watts which can make connection with a base station located 2 to 
3 km away.

# Use of a Capacitor
A capacitor has two electrodes separated by a ‘dielectric’ like paper, mica etc. The non-polarized disc 
capacitor is used to pass AC and not DC. Capacitor can store energy and pass AC signals during 
discharge. 0.22µF capacitor is selected because it is a low value one and has large surface area to 
accept energy from the mobile radiation. To detect the signal, the sensor part should be like an 
aerial. So the capacitor is arranged as a mini loop aerial (similar to the dipole antenna used in TV).In 
short with this arrangement, the capacitor works like an air core coil with ability to oscillate and 
discharge current.

One lead of the capacitor gets DC from the positive rail and the other lead goes to the negative input 
of IC1. So the capacitor gets energy for storage. This energy is applied to the inputs of IC1 so that the 
inputs of IC are almost balanced with 1.4 volts. In this state output is zero. But at any time IC can 
give a high output if a small current is induced to its inputs. There a natural electromagnetic field 
around the capacitor caused by the 50Hz from electrical wiring. When the mobile phone radiates 
high energy pulsations, capacitor oscillates and release energy in the inputs of IC. This oscillation is 
indicated by the flashing of the LED and beeping of Buzzer. In short, capacitor carries energy and is in 
an electromagnetic field. So a slight change in field caused by the RF from phone will disturb the 
field and forces the capacitor to release energy


