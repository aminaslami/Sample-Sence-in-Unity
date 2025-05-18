# Unity AR Sample Scene with C# (Vuforia Image Target Test)

This project demonstrates an augmented reality (AR) scene built with Unity and C#, utilizing the Vuforia Engine to detect image targets and trigger animations or actions on-screen.

### ✅ Project Overview
The AR application runs on a mobile device and uses the device’s camera to recognize specific images (called image targets). When a target image is detected, the application overlays virtual content (like animations or 3D objects) onto the real-world view.

### 🧪 Tested & Successfully Deployed
The app was:

*  Built in Unity
*  Scripted using C#
*  Tested using a phone screen showing the image targets
*  Recognized via a computer camera running the Unity scene
*  Successfully deployed and run without errors

### 🖼️ Image Targets Used (from Vuforia)
*  Image Target 1: Stones (imagetargets_targets-1)
*  Image Target 2: Chips (imagetargets_targets-2)
*  Image Target 3: Tarmac (imagetargets_targets-3)

These targets were sourced from Vuforia’s image target database and used to validate image recognition and AR overlay functionality.

### ⚙️ Features
*  C# scripts for event handling and image detection logic
*  Integration with Vuforia SDK for image tracking
*  Real-time AR content rendering based on detected image
*  Modular design to easily swap or add new image targets

### 🧩 Tools & Technologies
*  Unity
*  C#
*  Vuforia Engine
*  Android/iOS (for deployment)
*  Computer camera (for development-side testing)


I did this project by testing a photo on a phone screen with a computer camera.


![Animation - Screenshot](https://github.com/user-attachments/assets/f032160f-5f79-4dcb-a6d1-a24a8b0d2ef4)

The images with them I test and run it, I mentioned in below.


**Image Traget-1: Stones**
![image](https://github.com/user-attachments/assets/1fc58257-dfd7-4a1f-abc4-60195fa50ab7)

**Image Traget-2: Chips**
![image](https://github.com/user-attachments/assets/e0ee977d-f2f2-46aa-8dfd-6ef914c36a41)

**Image Traget-3: Tarmac**
![image](https://github.com/user-attachments/assets/6efbf351-5075-4adc-9cc9-d2d81a61dde3)

Images Source: Vuforia

---------------------------------------------------------

You can create a new repository on the command line, follow the below steps.
```
echo "# Sample-Sence-in-Unity" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/aminaslami/Sample-Sence-in-Unity.git
git push -u origin main
```
You can push an existing repository from the command line, follow the below steps.

```
git remote add origin https://github.com/aminaslami/Sample-Sence-in-Unity.git
git branch -M main
git push -u origin main
```
