# M3_WIPERCONTROLSYSTEM

## INTRODUCTION

 Windscreen wiper is a device that cleans water, snow or mud from the windscreen of vehicle. Thus, it ensures proper visibility of the road ahead.  This system finds application on a large variety of locomotives from vehicles, railways to aero-planes. Generally, the term ‘windscreen wiper’ refers to the wipers installed on the front windshield of a vehicle. However, nowadays, rear wipers are also getting popular.
 Almost all the modern wiper mechanisms employ an electric motor for their operation. However, in some cases, pneumatic drives are also used to drive wiper arm. Some of the primitive designs of the wiper mechanism were hand operated. Rain sensing wipers is a recent development in wipers.

<img width="645" alt="WIPER" src="https://user-images.githubusercontent.com/101088188/168420022-01828dac-fee8-4396-a9a0-523add19c3bc.png">


 Wiper mechanism comprises of the following major components:

* Wiper motor: 
It drives the linkages of wiper mechanism which ultimately makes the wiper blade to move on the windscreen.
It takes a lot of force to accelerate the wiper blades back and forth across the windshield so quickly. In order to generate this type of force, a worm gear is used on the output of a small electric motor.
The worm gear reduction can multiply the torque of the motor by about 50 times, while slowing the output speed of the electric motor by 50 times as well. The output of the gear reduction operates a linkage that moves the wipers back and forth.
Inside the motor/gear assembly is an electronic circuit that senses when the wipers are in their down position. The circuit maintains power to the wipers until they are parked at the bottom of the windshield, then cuts the power to the motor. This circuit also parks the wipers between wipes when they are on their intermittent setting.


* Linkage: 
Linkage performs two major functions. Firstly, it holds the wiper arm and blade in position and maintains proper contact between the blade and the windscreen. Secondly, it converts the rotary motion obtained from the motor into suitable form. And to do this, it employs a worm gear. Worm gear reduces the speed of output shaft of motor and converts it into suitable torque required to operate wiper arm.A short cam is attached to the output shaft of the gear reduction. This cam spins around as the wiper motor turns. The cam is connected to a long rod; as the cam spins, it moves the rod back and forth. The long rod is connected to a short rod that actuates the wiper blade on the driver's side. Another long rod transmits the force from the driver-side to the passenger-side wiper blade.


* Wiper arm: 
Wiper arm is the connecting link between wiper linkage and wiper blade.


* Wiper blade: 
 Blade is a rubber part that comes in contact with glass. It also has a metal clamping attached to it which aids in maintaining uniform pressure on the blade.Wiper blades are like squeegees. The arms of the wiper drag a thin rubber strip across the windshield to clear away the water.
When the blade is new, the rubber is clean and has no nicks or cracks. It wipes the water away without leaving streaks. When the wiper blades age, nicks or cracks form, road grime builds up on the edge and it doesn't make as tight a seal against the window, so it leaves streaks. Sometimes you can get a little extra life out of your wiper blade by wiping the edge with a cloth soaked in window cleaner until no more dirt comes off the blade.
Another key to streak-free operation is even pressure over the length of the rubber blades. Wiper blades are designed to attach in a single point in the middle, but a series of arms branch out from the middle like a tree, so the blade is actually connected in six to eight places. If ice or snow forms on these arms, it can make the distribution of pressure uneven, causing streaks under part of the blade. Some wiper manufacturers make a special winter blade with a rubber boot covering the arm assembly to keep snow and ice out.

### SPEED MODES
Most wipers have a low and a high speed, as well as an intermittent setting. When the wipers are on low and high speed, the motor runs continuously. But in the intermittent setting, the wipers stop momentarily between each wipe. There are many different kinds of switches for wipers. Some cars have just one intermittent speed, others have 10 discrete settings and still others have a sliding scale that can be set for almost any time interval.



<img width="296" alt="WIPER SWITCH" src="https://user-images.githubusercontent.com/101088188/168420299-9f8bbd50-62c5-4167-9cc7-b5cb2558498b.png">

### WORKING

<img width="604" alt="WORKING" src="https://user-images.githubusercontent.com/101088188/168420376-8a8b5646-3913-4ebb-98b4-337baffd475e.png">
The wipers combine two mechanical technologies to perform their task:

A combination electric motor and worm gear reduction provides power to the wipers.
A neat linkage converts the rotational output of the motor into the back-and-forth motion of the wipers.

## RECENT DEVELOPMENT

### Rain sensing wiper


In the past, automakers have tried to either eliminate the wipers or to control their speed automatically. Some of the schemes involved detecting the vibrations caused by individual raindrops hitting the windshield, applying special coatings that did not allow drops to form, or even ultrasonically vibrating the windshield to break up the droplets so they don't need to be wiped at all. But these systems were plagued by problems and either never made it to production or were quickly axed because they annoyed more drivers than they pleased.

However, a new type of wiper system is starting to appear on cars that actually does a good job of detecting the amount of water on the windshield and controlling the wipers. One such system is made by TRW Inc., here is a PDF describing their rain sensor system. TRW Inc. uses optical sensors to detect the moisture. The sensor is mounted in contact with the inside of the windshield, near the rearview mirror.

The sensor projects infrared light into the windshield at a 45-degree angle. If the glass is dry, most of this light is reflected back into the sensor by the front of the windshield. If water droplets are on the glass, they reflect the light in different directions -- the wetter the glass, the less light makes it back into the sensor.

The electronics and software in the sensor turn on the wipers when the amount of light reflected onto the sensor decreases to a preset level. The software sets the speed of the wipers based on how fast the moisture builds up between wipes. It can operate the wipers at any speed. The system adjusts the speed as often as necessary to match with the rate of moisture accumulation.

The TRW system, which is found on many General Motors cars, including all Cadillac models, can also be overridden or turned off so the car can be washed.

## ADVANTAGES
  Low cost automation project. 
 
  Free from wear adjustment. 
 
  Less power consumption. 
 
  Operating principle is very easy Installation is simple. 
 
  It  is  possible to  operate  manually/automatically  by providing On/Off switch 
 
 
  Sensor cost is very low due to the use of conductive sensor
 
## DISADVANTAGES
* Broken wiper control
* Burned out fuse
* Failed wiper motor
* Damged wiper blades
* snow and mist form

causes for failure of windsheild and is dangerous for ride during rain

## APPLICATIONS

-> It is used in four wheeler  

-> It is used in aircraft 

-> It is used in train 

-> It is used in six wheeler 

## STM32F407 Discovery Board
<img width="245" alt="STM" src="https://user-images.githubusercontent.com/101088188/168424317-9b16f25d-eae6-437b-ac89-c1ce078359c6.png">


The STM32F4DISCOVERY Discovery kit leverages the capabilities of the STM32F407 high-performance microcontrollers, to allow users to develop audio applications easily. It includes an ST-LINK/V2-A embedded debug tool, one ST-MEMS digital accelerometer, one digital microphone, one audio DAC with integrated class D speaker driver, LEDs, push-buttons, and a USB OTG Micro-AB connector.  STM32F4-Discovery kit photo Specialized add-on boards can be connected by means of the extension header connectors.
There are three busses available

1. I-BUS (Instruction Bus)
2. D-BUS (Data Bus)
3. S-BUS (System Bus)

### 1. I-BUS

This bus connects the Instruction bus of the Cortex®-M4 with FPU(Floating point unit) core to the BusMatrix. This bus is used by the core to fetch instructions. The target of this bus is a memory containing code (internal Flash memory/SRAM or external memories through the FSMC/FMC).

### 2.D-BUS

This bus connects the databus of the Cortex®-M4 with FPU to the 64-Kbyte CCM data RAM to the BusMatrix. This bus is used by the core for literal load and debug access. The target of this bus is a memory containing code or data (internal Flash memory or external memories through the FSMC/FMC).

### 3.S-BUS

This bus connects the system bus of the Cortex®-M4 with FPU core to a BusMatrix. This bus is used to access data located in a peripheral or in SRAM. Instructions may also be fetched on this bus (less efficient than ICode). The targets of this bus are the internal SRAM1, SRAM2 and SRAM3, the AHB1 peripherals including the APB peripherals, the AHB2 peripherals and the external memories through the FSMC/FMC.

So instructions and data use I-bus and D-bus respectively, All the other peripheral uses System bus. The Cortex-M4 processor contains three external Advanced High-performance Bus (AHB)-Lite bus interface and one Advanced Peripheral Bus (APB) interface. The GPIOs are connected to AHB1 bus which has a maximum speed of 150Mhz and is divided into two buses as APB1 and APB2. APB1 runs at 42Mhz(max) and APB2 runs at 82Mhz(max). The different peripherals such as SPI, UART, TIMERs, ADCs, DACs, etc are connected to either APB1/APB2 buses. And the AHB2(168Mhz max) is connected to Camera and USB OTG interfaces, AHB3 is connected to External memory controller.


###  Block Diagram

The STM32F4DISCOVERY is designed around the STM32F407VGT6 microcontroller in a 100-pin LQFP package.

<img width="460" alt="block diagram" src="https://user-images.githubusercontent.com/101088188/168424668-3a05dbdc-e121-4503-b7cf-f79e024850bc.png">

### PIN DIAGRAM

<img width="569" alt="Structure Diagram" src="https://user-images.githubusercontent.com/101088188/168424703-ef2a32e2-86f4-48a6-9337-27f7e7748f19.png">


<img width="698" alt="pin diagran" src="https://user-images.githubusercontent.com/101088188/168424714-89c69611-0bb3-40bf-bdd1-ee8207aaeaa7.png">




### All features

* STM32F407VGT6 microcontroller featuring 32-bit Arm® Cortex®-M4 with FPU core, 1-Mbyte Flash memory and 192-Kbyte RAM in an LQFP100 package
USB OTG FS
* ST MEMS 3-axis accelerometer
* ST-MEMS audio sensor omni-directional digital microphone
* Audio DAC with integrated class D speaker driver
* User and reset push-buttons
* Eight LEDs:
       * LD1 (red/green) for USB communication
       * LD2 (red) for 3.3 V power on
       * Four user LEDs, LD3 (orange), LD4 (green), LD5 (red) and LD6 (blue)
       * Two USB OTG LEDs, LD7 (green) VBUS and LD8 (red) over-current
* Board connectors:
       * USB with Micro-AB
       * Stereo headphone output jack
       * 2.54 mm pitch extension header for all LQFP100 I/Os for quick connection to prototyping board and easy probing
* Flexible power-supply options: ST-LINK, USB VBUS, or external sources
* External application power supply: 3 V and 5 V
* Comprehensive free software including a variety of examples, part of STM32CubeF4 MCU Package, or STSW-STM32068 for using legacy standard libraries
* On-board ST-LINK/V2-A debugger/programmer with USB re-enumeration capability: mass storage, Virtual COM port, and debug port
* Support of a wide choice of Integrated Development Environments (IDEs) including IAR Embedded Workbench®, MDK-ARM, and STM32CubeIDE

## Components
### Power supply and power selection
* The power supply is provided either by the host PC through the USB cable, or by an external 5 V power supply.
* The D1 and D2 diodes protect the 5V and 3V pins from external power supplies:
• 5V and 3V can be used as output power supplies when another application board is connected to pins P1 and P2.
In this case, the 5V and 3V pins deliver a 5 V or 3 V power supply and power consumption must be lower than 100 mA.
• 5V can also be used as input power supplies, for instance when the USB connector is not connected to the PC.
In this case, the STM32F4DISCOVERY board must be powered by a power supply unit or by auxiliary equipment complying with standard EN-60950-1: 2006+A11/2009, and must be Safety Extra Low Voltage (SELV) with limited power capability.
### LEDs
• LD1 COM: LD1 default status is red. LD1 turns to green to indicate that communications are in progress between the PC and the ST-LINK/V2-A.
• LD2 PWR: red LED indicates that the board is powered.
• User LD3: orange LED is a user LED connected to the I/O PD13 of the
STM32F407VGT6.
• User LD4: green LED is a user LED connected to the I/O PD12 of the STM32F407VGT6.
• User LD5: red LED is a user LED connected to the I/O PD14 of the STM32F407VGT6.
• User LD6: blue LED is a user LED connected to the I/O PD15 of the STM32F407VGT6.
• USB LD7: green LED indicates when VBUS is present on CN5 and is connected to PA9 of the STM32F407VGT6.
• USB LD8: red LED indicates an over-current from VBUS of CN5 and is connected to the I/O PD5 of the STM32F407VGT6.
### Push buttons
 18/32
UM1472 Rev 7
• •
B1 USER: User and Wake-Up buttons are connected to the I/O PA0 of the STM32F407VG.
B2 RESET: Push button connected to NRST is used to RESET the STM32F407VG.
 
UM1472 Hardware and layout
### On-board audio capability
The STM32F407VG microcontroller uses an audio DAC to output sounds through the audio mini-jack connector.
The STM32F407VG microcontroller controls the audio DAC through the I2C interface and processes digital signals through an I2S connection or an analog input signal.
• The sound can come independently from different inputs:
– ST-MEMS microphone: digital using PDM protocol or analog when using the low
pass filter
– USB connector: from external mass storage such as a USB key, USB HDD and others
– Internal memory of the STM32F407VG microcontroller
• The sound can be output in different ways through the audio DAC:
– Using I2S protocol
– Using DAC to analog input AIN1x of the audio DAC
– Using the microphone output directly via a low-pass filter to analog input AIN4x of the audio DAC
### USB OTG supported
The STM32F407VG microcontroller is used on this board to only drive the USB OTG full speed. The USB Micro-AB connector (CN5) allows the user to connect a host or device component, such as a USB key, mouse or others.
Two LEDs are dedicated to this module:
• LD7 (green LED) indicates when VBUS is active
• LD8 (red LED) indicates an over-current from connected device
### Motion sensor
The ST-MEMS motion sensor is an ultra-compact low-power three-axis linear accelerometer.
The motion sensor includes a sensing element and an IC interface able to provide the measured acceleration to the external world through the I2C/SPI serial interfaces.
The STM32F407VG microcontroller controls this motion sensor through the SPI interface.


## Clock

STM32F407VGT6 Micorcontroller has 3 main clock sources:

### Crystal Oscillator(HSE)

This is external clock source which can be connected to MCU based on requirements. HSE standas fro High speed External. If you want to use HSE as system clock an external crystal oscillator(whose frequency must be in range 4 to 26Mhz ) has to be connected. In this board, the manufacturer has connected 8Mhz crystal.

### RC Oscillator (HSI)

All modern MCU comes with internal RC Oscillator, which can be just activated to use. HSI stands for High Speed Internal .After Reset, by default HSI is used to provide a clock to MCU, which means by default MCU select HSI as the clock. This clock is internal to MCU and its value is 16Mhz in STM32F407 MCU. The HSI internal oscillator has the advantage of providing a clock at a low cost, as no external component is required to use this clock. It also has a faster start-up time than the external crystal oscillator however, frequency is less accurate when compared to the external crystal oscillator.

### PLL(Phase locked loop)

It is also Implemented internally in MCU, it uses low frequency sources to generate high frequency clock (PLLCLK).The power of PLL lies in producing high-frequency clocks of various programmable range. By using PLL you can boost the HCLK(AHB) up to 168Mhz in STM32F4xx MCU. All the modern MCU has PLL. If you want to use MCU-buses at their maximum speed then we have to use PLL only. You have to feed either HSI or HSE to the PLL as input frequency. Then by using all PLL circuitry settings, it produces a PLL output clock in the range of 100's of Mhz. So to Run STM32F407 at its maximum frequency(168Hhz) you have to use PLL.

### OSC clock supply
If PH0 and PH1 are used as GPIOs instead of being used as a clock, then SB13 and SB14 are closed and R24, R25 and R68 are removed.
• MCO from ST-LINK. From MCO of the STM32F103. This frequency cannot be changed, it is fixed at 8 MHz and connected to PH0-OSC_IN of the STM32F407VG. Configuration needed:
– SB13, SB14 OPEN
– R25(a) removed
– R68(a) soldered
• Oscillator on board. From X2 crystal. For typical frequencies and its capacitors and resistors, refer to the STM32F407VG datasheet at www.st.com. Configuration needed:
– SB13, SB14 OPEN
– R25(a) soldered
– R68(a) removed
• Oscillator from external PH0. From external oscillator through pin 7 of the P2 connector. Configuration needed:
– SB13 closed
– SB14 closed
– R25 and R68 removed
### OSC 32 KHz clock supply
20/32
If PC14 and PC15 are only used as GPIOs and not as a clock, then SB15 and SB16 are closed, and R21 and R22 are removed.
•
•
Oscillator on board. From X1 crystal (not provided). Configuration needed:
– SB15, SB16 OPEN
– C16, C27, R21 and R22 soldered.
Oscillator from external PC14. From external oscillator trough the pin 9 of P2 connector. Configuration needed:
– SB16 closed
– SB15 closed
– R21 and R22 removed
###SYSCLK

This is the Main clock of MCU, using this other clocks are derived (Ex: Peripheral, Bus clocks ect). SYSCLK is given directly to Ethernet PTP Clock.

### HCLK

HCLK is derived from SYSCLK with a Prescaler in between , which brings down the clock frequency. HCLK goes directly to AHB bus, core, memory and DMA. HCLK goes to Cortex System Timer with prescalar in between and HCLK goes directly to Cortex Processor (FCLK Cortex Clock).

### PCLK

PCLK1 and PCLK2 are derived from HCLK, PCLK1 goes to APB1 peripheral clock and APB1 Timer Clock and PCLK2 goes to APB2 peripheral clock and APB2 Timer Clock. By default MCU uses HSI (i.e internal RC Oscillator) as SYSCLK, Which means after reset HSI is used as SYSCLK Source. Before using any peripheral its clock should be enabled. Referring MUC Block Diagram, all different peripheral drives the clock from bus which it is connected. By default almost all the peripheral are deactive, which means there clocks are not enabled. RCC(Reset and clock Control) engine of MCU gives various registers to enable and disable various peripheral clocks. For more information refer RCC section of STM32F4xxx Reference Manual (RM0090).









