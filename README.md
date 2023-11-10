# HW6-Data-Acquisition-DMA-And-Interrupt

Group : 9  
Member : B09901043 陳昱樺 B09901134 林容丞

Function
---
Here are what this project does:
1. Task1: Run ADC with modified trigger frequency and sampling time. 
2. Task2: Run DMA and print the data received in the console. 
3. Task3: Run microphone example without the limit of 2 seconds. 

Prerequisites
---
There are two things a user should prepare to run this project:
* STM32 development board
* Zeroplus Logic Cube Analyzer and corresponding software (can be found at http://www.zeroplus.com.tw/logic-analyzer_en/technical_support_search.php?model=LAP-C%2816128%29&class1=1)

Usage
---
Here are some steps to run this project properly:
1. Import the project into Mbed Studio. 

For Task 3: 

2. Connect D11 and D10 on STM32 board to the logic analyzer. 
3. Toggle signal are shown in the logic analyzer software. 

License
---
None.

Acknowledgements
---
Here are some resources we refer to to finish this project:
* Course codes: timer_trigger_adc/main.cpp and timer_trigger_adc_DMA_ver/main.cpp
* https://github.com/janjongboom/b-l475e-iot01a-audio-mbed
