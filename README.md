# ✨ Handwritten Digit Recogniser  
_A fun, interactive deep-learning app that reads your handwriting in real time._

This project turns your screen into a tiny canvas where you can **draw any digit (0–9)** — and a trained neural network will instantly tell you what it thinks you wrote.  
Built with **Keras**, **Tkinter**, and the classic **MNIST** dataset, this app brings machine learning to life in a simple and playful way.

---

## 🚀 Demo

🖌️ Draw a digit → 🔍 Click "Recognise" → 🤖 Get prediction + confidence  
Perfect for beginners exploring ML or anyone who wants to tinker with neural networks in a visual way.

---

## 🧠 How It Works

1. You draw on a **300×300 pixel canvas**.  
2. The app captures the drawing directly from the window using `win32gui` + `ImageGrab`.  
3. The image is:
   - resized to **28×28**
   - converted to **grayscale**
   - normalised for the model  
4. A trained MNIST model (`mnist.h5`) processes the image.  
5. The app displays:
   - **Predicted digit**
   - **Confidence percentage**

All in real time.

---

## 📦 Features

- 🎨 Interactive drawing canvas  
- 🧮 Accurate digit prediction using a CNN  
- 💯 Displays confidence percentage  
- 🔁 One-click canvas reset  
- ⚡ Fast inference  
- 🖥️ Lightweight and easy to run  

---

## 🛠️ Tech Stack

- **Python 3.x**
- **Keras / TensorFlow**
- **Tkinter** (built into Python)
- **Pillow (PIL)**
- **PyWin32**
- **NumPy**# handwritten_digit_recogniser
