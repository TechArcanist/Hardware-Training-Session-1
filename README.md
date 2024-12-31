# Getting Started with IoT: Setting Up Your ESP32 : Hardware Training Session 1

If you're new to IoT, follow these steps to set up your ESP32 for development:

## 1. Download and Install the Arduino IDE
- Visit the [Arduino IDE download page](https://www.arduino.cc/en/software) and select your operating system.
- ![image](https://github.com/user-attachments/assets/e906b3c1-9ce1-4b92-a7f1-6e78c00c447f)
- Click **"Just Download"** to start the installation.
- ![image](https://github.com/user-attachments/assets/dfcd61de-2c35-40c5-90dc-063b511865e6)

## 2. Install the ESP32 Board Package
- Open the Arduino IDE after installation.
- Navigate to **Tools > Board > Boards Manager**.
- ![image](https://github.com/user-attachments/assets/9769c96f-5d8b-41cf-81d2-489b513853ad)

- Search for **ESP32** in the search bar.
- Install the package labeled **"esp32 by Espressif Systems"**.

## 3. Connect the ESP32 to Your PC
- Use a **micro USB cable** to connect the ESP32 to your computer.
- Open the **Device Manager** (on Windows) and check for a new port under **Ports (COM & LPT)**.
  - If no new port is visible:
    - Unplug and reconnect the cable.
    - Ensure you are using a **data cable** (some cables are power-only).
  - If you see a yellow triangle next to the port, proceed to the next step.

## 4. Install the CP2102 Driver (if needed)
- If the ESP32 doesn’t appear in the Device Manager or shows a yellow triangle error, install the **CP2102 driver**:
  - Download the driver from the official [CP2102 driver page](https://www.silabs.com/developers/usb-to-uart-bridge-vcp-drivers).
  - Extract the downloaded file.
  - In the Device Manager, right-click the port with the yellow triangle.
  - Select **Update Driver** > **Browse My Computer for Drivers**.
  - Navigate to the extracted driver folder and click **OK**.
- After installation, the yellow triangle should disappear, and the ESP32 will be recognized properly.

---

### You're all set to start developing IoT projects with your ESP32! 🚀
If you encounter any issues, feel free to check the official [Arduino forums](https://forum.arduino.cc/) or reach out for help.
