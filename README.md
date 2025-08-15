# 🚗 Smart Parking Spot Detector (Python + OpenCV)

A real-time Parking Spot Detector using Python and computer vision.

- ✅ Detects **free** & **occupied** parking slots instantly  
- ✅ Sends **live updates** to a **Telegram bot**  
- ✅ Visualizes slots in **green (free)** & **red (occupied)**  
- ✅ Built with **OpenCV, NumPy, requests**

This system saves time, reduces traffic congestion, and improves parking management efficiency.  
**Proud to combine technology + problem-solving to make everyday life smarter.**

> #Python #OpenCV #ComputerVision #SmartParking #IoT #Automation #AI #MachineLearning #Innovation #PythonProjects #ParkingManagement #TechForGood

---

## 📸 Demo

<img width="956" height="539" alt="park1" src="https://github.com/user-attachments/assets/b56f761d-a5fd-4ff6-bfc8-310223742b8d" /><img width="959" height="539" alt="park2" src="https://github.com/user-attachments/assets/45ac1f76-e750-4122-9b90-0e255daa7792" />
![WhatsApp Image 2025-08-15 at 12 19 53_9f0200c5](https://github.com/user-attachments/assets/98e95bce-4670-4e5f-b3fa-eae011bc097b)


---

## 🧠 How It Works

1. Load a **video** or **webcam** 


2. Read pre-defined **parking slot coordinates** (rectangles/polygons).
3. For each slot, compute an **occupancy score** (pixel density / edges / grayscale).
4. Mark **FREE** (green) or **OCCUPIED** (red) based on a **threshold**.
5. Batch and send **status updates** to a **Telegram bot** at a fixed interval.

---

## 🔩 Features

- Real-time occupancy detection (video/webcam)
- Configurable slot size, threshold, update interval
- Telegram notifications with slot summary
- FPS overlay & performance toggles
- Easy calibration tool for parking slot coordinates






























  

---

## 🗂️ Project Structure

