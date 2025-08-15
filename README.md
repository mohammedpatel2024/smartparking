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

*(Add a GIF or screenshot here)*  
`/assets/demo.gif`

---

## 🧠 How It Works

1. Load a **video** or **webcam** feed.<img width="959" height="539" alt="park2" src="https://github.com/user-attachments/assets/e9eec04c-13dc-4104-a4ef-4570196fd0b8" />
<img width="956" height="539" alt="park1" src="https://github.com/user-attachments/assets/2ae893d0-1657-4c8e-8f8e-64e43f188a1b" />
<img width="956" height="539" alt="park1" src="https://github.com/user-attachments/assets/f36d7a59-1664-4be5-ae64-1d00e24a2338" />
<img width="959" height="539" alt="park2" src="https://github.com/user-attachments/assets/0d09452a-3fdf-4f5b-8b95-a84b510bf9f2" />

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

