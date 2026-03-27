# Project Brainstorming

Once you are finished brainstorming your project ideas, fill in each of the sections below. You can continually update this project up to the morning of March 10th (the deadline).

**NOTE:** you should delete the initial sentences provided for each section (only include your own writing).

## Purpose

The purpose of this project is to develop a healthcare app that helps patients monitor their own health and perform simple medical tasks more safely. The system combines real-time sensing and guidance to give users feedback about their body and surroundings.

## Subsystems

### Subsystem 1

Vein Injection Guidance responsible for detecting vein locations for injections. It combines micro servo motors, light/laser guidance, and visual feedback to ensure accurate needle placement, reducing patient discomfort and error.

#### Devices

List, or put in a table, the devices your subsystem will use. 

For each device, include the Component name, Interface type, and link to any documentation you can find about that device.

Micro Servo Motors (we have it already)

Laser Pointer Module (we have it already)

### Subsystem 2

Patient Vital Monitoring monitors patient stress levels and heart rate using skin sensing and biometric sensors. The system collects and processes data in real time, providing alerts for abnormal readings. It integrates into the app to display patient vitals alongside procedural guidance.

#### Devices

GRS Skin Sensing Sensor I2C / Analog: https://www.aliexpress.com/item/1005007331806633.html?spm=a2g0o.tesla.0.0.7e20a1CNa1CNRI&afTraceInfo=1005007331806633__pc__c_ppc_item_bridge_pc_related_wf__YwwArDG__1773668420957

Heart Rate Monitor I2C / Analog: https://www.aliexpress.com/item/1005009386464038.html?spm=a2g0o.tesla.0.0.56aekbyAkbyAd0&pdp_npi=6%40dis!CAD!C%249.04!C%244.52!!!!!%402103128917746186851455956e3494!12000048943039486!btfpre!!!!1!0!&afTraceInfo=1005009386464038__pc__c_ppc_item_bridge_pc_main__XNoK581__1774618685573

### Subsystem 3

Environment Monitoring checks the patient environment for safety by monitoring temperature and oxygen levels. This subsystem complements the other two by providing context-aware data to enhance patient safety.

#### Devices

Temperature Sensor I2C / Digital (we have it already)

Oxygen Level Sensor Analog / Digital
https://www.aliexpress.com/item/1005011654864612.html?spm=a2g0o.productlist.main.1.69d715f92ICmqb&algo_pvid=d948e30f-2a85-4026-81ff-9a47389efcb2&algo_exp_id=d948e30f-2a85-4026-81ff-9a47389efcb2-0&pdp_ext_f=%7B%22order%22%3A%226%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis!CAD!11.68!11.68!!!57.00!57.00!%402103128817746189486217106efed7!12000056165138405!sea!CA!945965432!X!1!0!n_tag%3A-29911%3Bd%3Aca21dbbd%3Bm03_new_user%3A-29895&curPageLogUid=ZB6Jut89aXqo&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005011654864612%7C_p_origin_prod%3A


