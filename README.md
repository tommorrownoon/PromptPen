# PromptPen
Prompt is a portable smart pen engineered to combine traditional writing functionality with modern voice-assisted technology. Designed as a compact learning and productivity device, NeuraPen enables users to ask questions verbally and receive responses on an integrated OLED display within seconds. The project demonstrates the integration of embedded systems, wireless communication, power management, and human-computer interaction into a familiar everyday object.

The device is powered by an ESP32-S3 microcontroller, which serves as the central processing and communication unit. An INMP441 MEMS microphone captures spoken audio when the user presses the activation button. The recorded audio is transmitted via Bluetooth Low Energy (BLE) to a paired smartphone, where speech recognition software converts the audio into text. The smartphone then processes the request using artificial intelligence and returns a response to the pen. The ESP32-S3 receives the response and displays the information on a miniature SSD1306 OLED screen.

NeuraPen is powered by a rechargeable 3.7V lithium-polymer battery and incorporates a USB-C charging module for convenient recharging. The compact electronics are housed within a pen-shaped enclosure, emphasizing portability while maintaining functionality. By utilizing smartphone-based processing, the design reduces onboard computational requirements, allowing for a smaller form factor, lower power consumption, and longer battery life.

The device can provide quick access to definitions, calculations, factual information, scheduling assistance, and study support without requiring users to navigate between notebooks and multiple applications.

# Why I Created Prompt
I created Prompt to explore how artificial intelligence and embedded systems can be integrated into everyday objects. While smartphones provide access to information, they can be distracting and require users to stop what they are doing to search for answers. I wanted to design a device that allows people to obtain information quickly and naturally through voice interaction while maintaining focus on their work.

# Bill of Materials
Item #	Component	Qty	Unit Cost (USD)	Total Cost
1	 ESP32-S3 Development Board	1	  $15.00
2	  INMP441 MEMS Microphone	1	 $4.00	
3	  0.96" SSD1306 OLED Display	 1	$4.50	
4	3.7V 500mAh LiPo Battery	1	$8.00	
5	TP4056 USB-C Charging Module	1	$5.00	
6	Push Button Switch	1	$0.50	
7	Mini Slide Power Switch	1	$0.50	
8	Coin Vibration Motor	1	$2.00	
9	Prototype PCB / Perfboard	1	$3.00	
10	Silicone Hookup Wire	1 Set	$3.00	
11	Solder and Flux	1 Set	$5.00	
12	3D Printed Pen Housing	1	$10.0o
13	Screws, Standoffs, Hardware	Assorted	$2.00

| | Estimated Total Cost | | | $62.50 |
