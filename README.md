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
    - ![image](https://github.com/user-attachments/assets/9f5939cb-1cce-4dbe-8f9c-16c05d8a855a)

  - If you see a yellow triangle next to the port, proceed to the next step.
  - ![image](https://github.com/user-attachments/assets/f948ee21-ce61-4438-b79f-392265a5f376)

## 4. Install the CP2102 Driver (if needed)
- If the ESP32 doesn’t appear in the Device Manager or shows a yellow triangle error, install the **CP2102 driver**:
  - Download the driver from the official [CP2102 driver page](https://www.silabs.com/developer-tools/usb-to-uart-bridge-vcp-drivers?tab=downloads).
  - ![image](https://github.com/user-attachments/assets/52ab9dcb-06d2-4441-b42b-2b04d7d11634)
  - Extract the downloaded file.
  - ![image](https://github.com/user-attachments/assets/7d2a57e9-5e5f-4e1d-b3dc-d98facff886d)
  - In the Device Manager, right-click the port with the yellow triangle.
  - Select **Update Driver** > **Browse My Computer for Drivers**.
  - ![image](https://github.com/user-attachments/assets/845c767c-a080-4ccf-8a0f-b690a5f998f3)
  - Navigate to the extracted driver folder and click **OK**.
  - Step 1
  - ![image](https://github.com/user-attachments/assets/69111efa-e97f-4b3c-8d05-56737fc40a5e)
  - Step 2
  - ![image](https://github.com/user-attachments/assets/831f2004-3946-4aaa-a417-409a88eeaa50)

- After installation, the yellow triangle should disappear, and the ESP32 will be recognized properly.

---

### You're all set to start developing IoT projects with your ESP32! 🚀
