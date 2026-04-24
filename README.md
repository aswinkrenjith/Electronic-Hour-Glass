# ⏳ DIY Electronic Hourglass 

A sleek, digital reimagining of the classic hourglass. This project uses a microcontroller to simulate the movement of "sand" across a 57-LED matrix.

---

## 📦 What's in the Kit?
* **PCB Board:** The base for all components.
* **57 LEDs:** These act as the "sand" particles.
* **Microcontroller:** Pre-programmed to handle the LED logic and timing.
* **S1 (Slide Switch):** Main power control.
* **S2 (Push Button):** Used for resetting or adjusting the flow speed.
* **DC Power Jack:** 5V input.

---

## 🛠 Assembly Guide

### 1. Orientation is Everything (LEDs)
LEDs are **polarized**. The **longer leg** (Anode) goes into the square pad (marked `+`). 
> **Tip:** If you solder an LED backward, that "grain of sand" will never light up!

### 2. The Brain (Microcontroller)
Align the **notch** on the chip with the notch marking on the PCB (U1). If you have an IC socket, solder that first, then snap the chip in.

### 3. Power & Controls
* Solder the **DC Jack** and the **Slide Switch (S1)**.
* Solder the **Tactile Button (S2)**. 

### 4. Quality Control
Before plugging it in, check the back for **solder bridges** (blobs of solder touching two pins that shouldn't be connected). 


## 5. Troubleshooting Tips

* **Half the Hourglass is dark?** Check the orientation of the LEDs in that section. A single backward LED can sometimes break a series string.
* **Won't Power On?** Check your 5V source. These kits are specifically designed for 5V; using a 9V or 12V adapter **will** damage the microcontroller.
* **Intermittent Flickering:** Re-flow the solder joints on the IC socket pins and the power jack.

---
## Operation
1. Connect a **5V DC** power source.
2. Flip **S1** to ON.
3. Use **S2** to cycle through the different speed modes or reset the timer.
