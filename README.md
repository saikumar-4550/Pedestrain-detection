## 🚶‍♂️ Pedestrian Detection System

A real-time pedestrian detection system using YOLOv8 and OpenCV. This project identifies and counts people in images or video streams with high accuracy and speed. Ideal for surveillance, smart city applications, and footfall analysis.

---

### 🔍 Features

- **Real-time Pedestrian Detection**  
  Detects humans instantly from live camera feed, video, or image input using YOLOv8.

- **Bounding Box Annotation**  
  Draws labeled boxes (`Person`) around each detected pedestrian.

- **Pedestrian Counting**  
  Counts the number of people present in each frame or within a custom-defined area.

- **Region of Interest (ROI) Support**  
  Optional ROI configuration for area-specific detection and counting.

- **Image and Video Support**  
  Works with both static images and pre-recorded/live video sources.

- **Frame-by-Frame Analysis**  
  Processes video frame-by-frame to ensure no pedestrian is missed.

- **YOLOv8 Model Compatibility**  
  Supports various YOLOv8 model sizes (`n`, `s`, `m`, `l`, `x`) for performance tuning.

- **Visual Overlays with cvzone**  
  Enhanced display of detection results using the `cvzone` library for neat bounding boxes and text.

- **Modular Code Structure**  
  Easily extendable for tracking, alerts, analytics, or integration into larger systems.

---

### 🌟 Importance

- **Smart City Surveillance**  
  Boosts urban safety by monitoring pedestrian flow in public areas.

- **Crowd Management**  
  Assists in managing people density during events or rush hours.

- **Security Monitoring**  
  Helps detect abnormal or unauthorized pedestrian activity.

- **Retail and Commercial Footfall Analytics**  
  Provides valuable insights into customer movement in stores, malls, or offices.

- **Traffic Systems**  
  Aids in intelligent transportation solutions by detecting pedestrian presence.

- **Smart Access Control**  
  Useful in automating building entry monitoring and logging.

- **Research and Prototyping**  
  Beneficial for computer vision R&D projects involving human behavior analysis.

---

### 🛠️ Technologies Used

- Python
- OpenCV
- Ultralytics YOLOv8
- cvzone (for visual overlays)
- NumPy

---

### 🧠 Model Info

- **Model**: YOLOv8-Large  
- **Dataset used for training**: COCO / custom pedestrian dataset

---

### 📌 To-Do

- [ ] Add tracking with DeepSORT  
- [ ] Web interface using Flask  
- [ ] Export results to CSV (time, count, timestamp)

---

### 👤 Author

**Sai Kumar Kuncham**  
[LinkedIn](https://www.linkedin.com/in/sai-kumar-kuncham/) | [GitHub](https://github.com/saikumar-4550)
