# workshop3
## 🔍 YOLOv11 Image Search Application  

A smart and interactive **Computer Vision Search Engine** built using **YOLOv11**, **Streamlit**, and **PyTorch**.  
Search, filter, and visualize object detections across thousands of images effortlessly! 🚀  

---

## ✨ 1. Key Features (Highlights)

### 🧠 YOLOv11-Powered Detection  
- Detects multiple objects across entire directories  
- Extracts bounding boxes, classes & confidence values  

### 📄 Metadata Support  
- Automatically saves processed results in JSON  
- Reload metadata anytime without re-running inference  

### 🔍 Advanced Search Engine  
- Search by specific classes  
- Choose **OR** (any class) or **AND** (all classes)  
- Apply **optional count thresholds** (e.g., person ≤ 3)  

### 🖼️ Clean & Attractive UI  
- Adjustable grid  
- Optional bounding boxes  
- Smart highlighting for matched detections  
- Beautiful card-based layout  

### 📤 Export Options  
- Download search results as JSON  
- Metadata export for other workflows  

---
## DATASET USED: From Drive

## 📦 2. Requirements (Install Before Running)


Create a file named `requirements.txt` with:


ultralytics

streamlit

opencv-python

pyyaml

torch

torchvision

pillow

pandas

numpy

📦 Project_YOLO
│
├── app.py # Main Streamlit app
├── requirements.txt
├── src
│ ├── inference.py # YOLO inference logic
│ └── utils.py # Metadata & helper functions
│
└── README.md

---

Install all dependencies:

pip install -r requirements.txt

## ▶️ 3. How to Run the Application

### ▶️ Default Port (8501)

streamlit run app.py

### 🎛️ Custom Port Example

streamlit run app.py --server.port 8080


## 🗂️ 4. Project Structure (Simple Overview)

## 🔧 5. How the App Works (Flow)

### 1️⃣ Image Processing  
- Choose a directory  
- Load YOLO model (e.g., `yolo11m.pt`)  
- Extract detections for each image  

### 2️⃣ Metadata Creation  
- Saves all results as JSON  
- Includes class counts, bounding boxes, confidence, paths  

### 3️⃣ Search Engine  
Choose:
- ✔ Selected classes  
- ✔ OR / AND search mode  
- ✔ Max count thresholds (optional)  

Example:
- class: person, car  
- threshold: person ≤ 3, car ≤ 2  

### 4️⃣ Result Display  
- Grid view (2–6 columns)  
- Optional bounding boxes  
- Highlight matching detections  
- Info overlay for selected classes  

---

## 📤 6. Export Options  
You can download:
- ✔ Search results (JSON)  
- ✔ Processed metadata  

---

## 📸 7. (Optional) Add Screenshots  
You can include UI snapshots or demo images here.  

---

## 🤝 8. Contributing  
Pull requests & suggestions are welcome!  

---

## ⭐ 9. Support the Project  
If you found this useful, please ⭐ the repository on GitHub!  

---

## 👤 10. Author  
**Clarissa K**  
Developer — YOLO Image Search Engine  

## Output images:


<img width="1912" height="1022" alt="Screenshot 2025-11-23 232228" src="https://github.com/user-attachments/assets/87c88df7-ad33-457f-9d55-c7c215842112" />



<img width="1910" height="1034" alt="Screenshot 2025-11-23 232239" src="https://github.com/user-attachments/assets/51ba6f05-0da8-4a02-b413-9354b7d5a040" />

