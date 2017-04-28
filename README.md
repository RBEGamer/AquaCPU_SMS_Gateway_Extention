# AquaCPU_SMS_Gateway
A further extention for my AquaCPU System

# FEATURES
* Adds SMS notification support for the AquaCPU System
* Simple config


# HARDWARE
* 1 RPI Zero
* 1 MCP2515 CAN breakout board
* 1 Sim800L GSM Module
* 1 Actived SimCard
* 1 USB to 3.3V UART converter.
* 1 SD Card with Debian for the pi
* 1 StepUp-Converter 3.3V -> 4.2V (for the Sim800L)

# SOFTWARE SETUP
* Make a basic setup of your pi (run setup, epand partition,..)
* Download the latest release or clone the repo and build it yourself
* set execute rights, chmode +x
* modify the config.ini file for setup
* modify the listen.csv file to setup messages
* run the AquaCPU_SMS_Gateway
* [OPTIONAL] add a startup entry in the `/etc/rc.local`


# IMAGES
## Final Hardware, with no case
![Gopher image](/documentation/images/final_hardware.jpeg)

## A simple working test with the Aqua_CPU_Refill_Extention
![Gopher image](/documentation/images/sms_test.png)
