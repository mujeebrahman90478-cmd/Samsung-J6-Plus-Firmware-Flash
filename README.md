# Samsung-J6-Plus-Firmware-Flash
Step-by-step PC-less firmware flashing using Eros Engine and OTG
# Samsung Galaxy J6+ (SM-J610F) Mobile-to-Mobile Firmware Flash Guide

This project demonstrates a professional firmware restoration of a Samsung Galaxy J6+ using a Poco F3 GT as the host. This method is 100% PC-less, utilizing OTG and Eros Engine.

---

## **1. Firmware Preparation**
We sourced the official KSA binary using **Bifrost** and handled the 2.6GB extraction via **ZArchiver**.

| Firmware Download | Folder Setup | Extraction |
|---|---|---|
| ![Bifrost](1000030918.png) | ![Folders](1000030930.png) | ![ZArchiver](1000030975.png) |

---

## **2. Hardware & Connection**
Using a high-quality OTG adapter and Micro-USB data cable to establish a bridge between the Poco F3 GT (Host) and the J6+ (Target).

![Tools](1000030991.jpg)
*Hardware interface setup using OTG.*

---

## **3. Entering Odin/Download Mode**
1. Power off the target device.
2. Boot to Recovery (`Volume Up + Power`).
3. Select **"Reboot to bootloader"** to enter the flashing environment.

| Recovery Menu | Download Mode |
|---|---|
| ![Recovery](1000030994.jpg) | ![Download](1000030997.jpg) |

---

## **4. Flashing Process (Eros Engine)**
Mapping the BL, AP, CP, and **HOME_CSC** files. Note: Using `HOME_CSC` ensures that user data is preserved after the flash.

![Mapping](1000030999.jpg) | ![Progress](1000031005.jpg)
---|---

---

## **5. Final Success**
The device successfully completed the flash and booted into the official system with all data intact.

![Success Boot](1000031009.jpg)

---
**Project by MARZ INDIA**
*Lead Technical Specialist: Mujeeb Rahman*
