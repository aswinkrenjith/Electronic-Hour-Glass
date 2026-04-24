# ⏳ Electronic Hourglass DIY Kit

A sleek, digital reimagining of the classic hourglass. This project uses a microcontroller to simulate the movement of "sand" across a 57-LED matrix. 

This repository documents my assembly of the **stock version** of the kit, keeping the original factory settings and components.

---

## 📖 Project Description
The Electronic Hourglass is a DIY electronics project that replaces physical sand with a matrix of LEDs. Controlled by a microcontroller, the "grains of light" respond to timing and reset triggers, providing a "tech-vintage" aesthetic for any desk.

### 🔧 Build Status: **Pure Stock**
* **Firmware:** Original Stock Firmware (Not re-programmed).
* **Power Input:** Standard 5V DC-Jack (No USB mod used).
* **Configuration:** Factory-standard assembly.

---

## 🛠 How I Made It

1.  **LED Matrix Assembly:** Soldered **57 LEDs** into the board. I had to be careful with orientation—the longer leg (Anode) goes into the square pad marked `+`.
2.  **The Brain:** Installed the microcontroller (U1) into its socket.
3.  **Switches & Power:** Soldered the slide switch (**S1**) for power and the tactile push-button (**S2**) for resetting the timer.
4.  **Connectors:** Installed the **5V DC-Jack** for power and the **ISP Header Pins**.
5.  **Quality Check:** Inspected all 57 LED joints and the IC pins for solder bridges before powering on.

---

## 📦 Bill of Materials (BOM)

| Part | Quantity | Description |
| :--- | :--- | :--- |
| **LEDs** | 57 | Clear LEDs (The "Sand" particles) |
| **Microcontroller** | 1 | Pre-programmed stock chip |
| **S1 Switch** | 1 | Slide switch (ON/OFF) |
| **S2 Switch** | 1 | Tactile push button (Reset/Speed) |
| **DC-Jack** | 1 | 5V DC Power Socket |
| **Header Pins** | 1 set | Male ISP pins (For structural completeness) |
| **PCB** | 1 | YH-106 Circuit Board |

---

## 🚀 Future Potential (Not Applied in this Build)
While I kept my build **100% stock**, this board is designed with flexibility in mind for those who want to mod it:
* **Re-programmable:** The included male ISP pins allow you to connect a programmer to flash custom code or change the "sand" physics.
* **USB Connection:** The board has traces that allow for a USB power connection instead of the standard DC-jack if you want to power it via a computer or power bank.

---

## 🎮 Operation
1.  Plug in a **5V DC** power source.
2.  Flip **S1** to ON.
3.  The "sand" (LEDs) will begin to fall.
4.  Press **S2** to reset the timer or cycle through pre-set speed modes.

---

## ⚠️ Troubleshooting Tips
* **Dark LEDs:** If a section of "sand" isn't lighting up, double-check the polarity of the LEDs in that area.
* **Power Warning:** Only use **5V**. Using a 9V or 12V adapter will damage the stock microcontroller.
