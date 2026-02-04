# Cartonifier
 🎨 Cartoonify Image using Python & OpenCV
## 📌 Description
The **Cartoonify Image** project is a Python-based application that transforms ordinary images into cartoon-style visuals using computer vision techniques. The application provides a simple graphical user interface (GUI) where users can upload an image, preview the cartoonified version, and save the result.

By applying image processing methods such as **grayscale conversion, noise reduction, edge detection, and bilateral filtering**, the system enhances edges while smoothing colors to create a cartoon-like effect.

This project is ideal for beginners exploring **OpenCV**, image processing, and GUI development with Python.

## 🚀 Features
✅ Upload any image from your device
✅ Convert images into cartoon style instantly
✅ Preview each stage of image processing
✅ Simple and user-friendly GUI
✅ Save the cartoonified image
✅ Fast and lightweight application

## 🛠️ Technologies Used
* **Python**
* **OpenCV** – Image processing
* **Tkinter** – GUI interface
* **EasyGUI** – File selection dialog
* **NumPy** – Image array handling
* **Matplotlib** – Visualization
* **Pillow (PIL)** – Image support

## ⚙️ How It Works
1. The user uploads an image.
2. The image is converted to grayscale.
3. Median blur is applied to reduce noise.
4. Adaptive thresholding detects edges.
5. Bilateral filtering smooths colors while preserving edges.
6. The filtered image is combined with the edge mask to produce the cartoon effect.

## 📂 Project Structure

```
Cartoonify-Image/
│
├── cartoonify.py
├── README.md
└── sample_images/
```
## ▶️ Installation
### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/cartoonify-image.git
cd cartoonify-image
```
### 2️⃣ Install Dependencies
```bash
pip install opencv-python numpy matplotlib pillow easygui imageio
```

### 3️⃣ Run the Application
```bash
python cartoonify.py
```
A GUI window will open where you can upload and cartoonify images.

## 🎯 Learning Outcomes
* Understanding image processing fundamentals
* Working with OpenCV functions
* Building desktop GUI apps with Tkinter
* Implementing edge detection techniques
* Handling image transformations

## 🔮 Future Enhancements
* Real-time webcam cartoon filter
* AI-based artistic filters
* Drag-and-drop image upload
* Web version using Streamlit
* Batch image processing
* Adjustable filter intensity

## 📊 Use Cases
* Photo editing applications
* Social media image styling
* Computer vision practice
* Academic mini-projects
* Creative design tools


Just tell me what you want next 🙂
