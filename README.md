```markdown
# SleepGuardian User Guide

Welcome to **SleepGuardian**, your reliable tool for managing monitor sleep schedules effortlessly. This guide will help you get started with installing, configuring, and using SleepGuardian effectively.

---

## Table of Contents

1. [Installation]
2. [Launching SleepGuardian]
3. [Using the Global Shortcut]
4. [Configuring Settings]
5. [Minimizing to Tray]
6. [Exiting the Application]
7. [Troubleshooting]
8. [Support]

---

## Installation

1. **Download the Installer:**
   - Visit the https://github.com/Pandekte/SleepGuardianPublic the distribution platform where you have published SleepGuardian.
   - In Code section click on the download link to obtain the `SleepGuardianSetup.exe` installer.
   - Unzip installer files.

2. **Run the Installer:**
   - Locate the downloaded `SleepGuardianSetup.exe` file in your `Downloads` folder or the chosen download location.
   - Double-click the installer to begin the installation process.

3. **Follow the Installation Wizard:**
   - **Welcome Screen:** Click **"Next"** to proceed.
   - **License Agreement:** Review the End-User License Agreement (EULA). Click **"I Agree"** to accept the terms and continue.
   - **Choose Installation Directory:**
     - The default installation path is typically `C:\Program Files\SleepGuardian\`.
     - To use the default path, click **"Next"**.
     - To choose a different location, click **"Browse..."**, select your desired folder, and click **"Next"**.
   - **Select Additional Tasks:**
     - **Create Desktop Shortcut:** Check this option to add a shortcut to your desktop for easy access.
     - **Start SleepGuardian on Windows Startup:** (Optional) Check this to have SleepGuardian launch automatically when Windows starts.
   - **Install:** Click **"Install"** to begin copying files and setting up the application.
   - **Completion:** Once installation is complete, click **"Finish"** to exit the installer. If you selected to launch SleepGuardian immediately, the application will start.

---

## Launching SleepGuardian

After installation, you can launch SleepGuardian using one of the following methods:

- **Desktop Shortcut:**
  - Double-click the **SleepGuardian** icon on your desktop. It will start in your tray. Double click to open up menu from the tray.

- **Start Menu:**
  - Click the **Start** button, navigate to **All Apps**, find **SleepGuardian**, and click to launch.

- **System Tray:**
  - If SleepGuardian is running in the background, double-click its icon in the system tray to bring the main window to the foreground.

---

## Using the Global Shortcut

SleepGuardian allows you to control monitor sleep schedules using a convenient global keyboard shortcut.

### **Default Shortcut Combination:**
- "X" (sorry about that!)
In next version:
- **Ctrl + Shift + X**

### **Functionality:**
- **Activate Shortcut:**
  - Press **Ctrl + Shift + X** simultaneously.
  
- **What Happens:**
  - A **countdown timer** starts based on your configured duration (default is 5 seconds).
  - Once the countdown completes, SleepGuardian will **turn off your monitor** automatically.

### **Customizing the Shortcut:**
- **Access Settings:**
  - Open the SleepGuardian main window.
  - Click on the **"Settings"** button or icon.

- **Change Shortcut Keys:**
  - In the **Shortcut Configuration** section, you can select different modifier keys (e.g., Ctrl, Alt, Shift, Win) and a new key to redefine the global shortcut.
  
- **Save Changes:**
  - After selecting your preferred key combination, click **"Save"** or **"Apply"** to update the shortcut.

**Note:** Ensure that the chosen shortcut combination does not conflict with existing system or application shortcuts to prevent unintended behavior.

---

## Configuring Settings

Customize SleepGuardian to fit your preferences through the Settings dialog.

### **Accessing Settings:**
- Click the **"Settings"** button or icon in the SleepGuardian main window or system tray.

### **Available Settings:**

1. **Countdown Duration:**
   - **Description:** Set the number of seconds before the monitor turns off after activating the shortcut.
   - **Default Value:** `5` seconds
   - **How to Change:**
     - Enter your desired duration in the provided input field.
     - Click **"Save"** or **"Apply"** to confirm.

2. **Global Shortcut Configuration:**
   - **Modifier Keys:**
     - Choose from **Ctrl**, **Alt**, **Shift**, and **Win**.
   - **Shortcut Key:**
     - Select a key from the dropdown menu to pair with the modifier keys.
   - **Default Combination:** **Ctrl + Shift + X**
   - **How to Change:**
     - Select your preferred modifiers and key.
     - Click **"Save"** or **"Apply"** to update.

3. **Startup Behavior:**
   - **Start with Windows:**
     - **Enabled:** SleepGuardian launches automatically when you start Windows.
     - **Disabled:** SleepGuardian does not launch on startup.
   - **How to Change:**
     - Toggle the **"Start with Windows"** option on or off.
     - Click **"Save"** or **"Apply"** to confirm.

4. **Notification Settings:**
   - **Enable Notifications:**
     - **Enabled:** Receive balloon tip notifications for actions like shortcut activation and countdown completion.
     - **Disabled:** No notifications will appear.
   - **How to Change:**
     - Toggle the **"Enable Notifications"** option on or off.
     - Click **"Save"** or **"Apply"** to update.

### **Saving Settings:**
- After making changes, ensure you click **"Save"** or **"Apply"** to retain your configurations.

---

## Minimizing to Tray

SleepGuardian can run silently in the system tray, allowing you to access it without cluttering your taskbar.

### **How to Minimize to Tray:**
- **Via the Main Window:**
  - Click the **"Minimize"** button on the SleepGuardian window.
  
- **Automatic Minimization:**
  - Enable the **"Minimize to Tray"** option in the Settings to have SleepGuardian minimize to the tray automatically when closed.

### **Accessing SleepGuardian from the Tray:**
- **Restore Window:**
  - Double-click the SleepGuardian icon in the system tray to bring the main window back.
  
- **Context Menu:**
  - Right-click the SleepGuardian tray icon to access options like **"Open"** and **"Exit"**.

---

## Exiting the Application

To completely close SleepGuardian, follow these steps:

### **From the Main Window:**
1. Click the **"Exit"** button or icon within the SleepGuardian interface.
2. Confirm any prompts to terminate the application.

### **From the System Tray:**
1. Locate the SleepGuardian icon in the system tray.
2. Right-click the icon to open the context menu.
3. Click **"Exit"** to close the application.

**Note:** If **"Start with Windows"** is enabled, SleepGuardian will continue to run in the background even after closing the main window unless you explicitly exit the application.

---

## Troubleshooting

Encountering issues? Here are some common problems and their solutions.

### **1. Shortcut Not Working**
- **Possible Causes:**
  - Shortcut combination conflicts with other applications.
  - SleepGuardian is not running.
  
- **Solutions:**
  - **Check if SleepGuardian is Running:**
    - Look for the SleepGuardian icon in the system tray.
    - If not running, launch the application.
  
  - **Change Shortcut Combination:**
    - Open **Settings** and choose a different shortcut key combination that doesn't conflict with existing shortcuts.

### **2. Countdown Doesn't Start**
- **Possible Causes:**
  - Incorrect countdown duration settings.
  - Application not properly registered to handle the shortcut.
  
- **Solutions:**
  - **Verify Countdown Duration:**
    - Open **Settings** and ensure the countdown duration is set to a positive number.
  
  - **Re-register the Shortcut:**
    - Change the shortcut to a different combination and then revert to the desired one to re-register it.

### **3. Monitor Doesn't Turn Off**
- **Possible Causes:**
  - Insufficient permissions to execute monitor control commands.
  - Conflicting applications preventing SleepGuardian from functioning correctly.
  
- **Solutions:**
  - **Run as Administrator:**
    - Right-click the SleepGuardian shortcut and select **"Run as administrator"**.
  
  - **Check for Conflicting Software:**
    - Temporarily disable other applications that might control monitor settings to see if the issue persists.

### **4. Application Doesn't Start on Windows Startup**
- **Possible Causes:**
  - **"Start with Windows"** option not enabled.
  - Windows Startup folder not correctly configured.
  
- **Solutions:**
  - **Enable "Start with Windows":**
    - Open **Settings** and ensure the **"Start with Windows"** option is enabled.
  
  - **Manually Add to Startup:**
    - Press `Win + R`, type `shell:startup`, and press `Enter`.
    - Copy the SleepGuardian shortcut into the opened folder to add it to Windows Startup.

### **5. Security Warnings During Installation**
- **Cause:**
  - SleepGuardian is signed with a self-signed certificate, which is not trusted by default.
  
- **Solutions:**
  - **Install the Certificate:**
    - Follow the instructions provided in the **"Self-Signed Certificates"** section of the installation guide to install the certificate and trust it.
  
  - **Use a Trusted Certificate:**
    - For public distribution, consider obtaining a code signing certificate from a trusted Certificate Authority (CA) to eliminate security warnings.

---

## Support

If you need further assistance or encounter issues not covered in this guide, please reach out through the following channels:

- **Website:** https://github.com/Pandekte/SleepGuardianPublic 


---

**Thank you for choosing SleepGuardian! We hope it enhances your productivity and ensures your monitor's longevity.**

```
