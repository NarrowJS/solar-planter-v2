## May 17 2026

Started working on the CAD model. The goal is to make all of the electronics seperate from the planter to reduce the risk of water accidently getting into the electronics. As opposed to the LEDs in v1, I'm going to try a reflective design where the lights will bounce off the walls rather than being diffused.

![5/17](assets/1.png)

**Total time: 1.5 hrs**

## May 18 2026

Did some more work on the CAD model by adding a cutout for the wires from the solar panel and the moisture sensor. I was able to get rid of the cutout on the base and instead make the wires go through the bottom, where they will be almost invisible from most angles. I also started working on the PCB schematic, which will be based on the ESP32 C6-mini, giving me the ability to use zigbee instead of WiFi for the firmware.

![5/18](assets/2.png)
![5/18](assets/3.png)

**Total time: 1.6 hrs**

## May 19 2026

Added in the rest of the components to the schematic and finished all of the remaining routes. I'm still not fully settled on the components and I might end up exposing some more of the wires in order to allow for easier future expansion. I'm also still not sure how much IO I want to have besides the switch and usb-c for programming, since everything else has to be done through the software at the moment.

![5/19](assets/4.png)

**Total time: 1.4 hrs**

## May 29 2026

Polished up the schematic and went over each part and compared it to the datasheet to make sure I didn't make any careless mistakes. I was able to catch a couple, the i2c pins werent connected, a couple of capacitors were too small, and the voltage divider on the boost circuit was incorrect. I also made some of the connections less confusing and reorganized the layout for readability. It's now time to route all of the traces on the pcb.

![5/19](assets/5.png)

**Total time: 1.5 hrs**