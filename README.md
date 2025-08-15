<div align="center">

# 🖼️ AI Video and Photo Upscaler

Upscale your images and videos with the **Real-ESRGAN** deep learning model.  
Modern, responsive UI + cross-platform backend for professional-grade enhancement.

[![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python)](https://www.python.org/)
[![Flask](https://img.shields.io/badge/Flask-Backend-black?logo=flask)](https://flask.palletsprojects.com/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind-CSS-38B2AC?logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

</div>

---

## 🚀 Features

- **AI-Powered Upscaling** – Uses **Real-ESRGAN** for state-of-the-art enhancement.
- **Minimalist UI** – Apple-inspired, clean, and modern design.
- **Light & Dark Mode** – Switch themes for any environment.
- **Drag & Drop Uploads** – Quick and intuitive file upload.
- **Cross-Platform Backend** – Works on **Windows**, **macOS**, and **Linux**.

---

## 🛠️ Tech Stack

**Frontend**  
- HTML5 – Markup structure  
- Tailwind CSS – Utility-first responsive styling  
- JavaScript – User interaction & API integration  

**Backend**  
- Python – Core server logic  
- Flask – Lightweight API framework  
- PyTorch – ML framework  
- Real-ESRGAN – Upscaling model  
- MoviePy & OpenCV – Video frame processing and reassembly  

---

## 📦 Installation & Setup

> 💡 Recommended: Python **3.11** with a virtual environment.

### **1️⃣ Backend Setup**

#### a. Create a Virtual Environment
```bash
py -3.11 -m venv venv
b. Activate the Environment

Windows

.\venv\Scripts\activate


macOS/Linux

source venv/bin/activate

c. Install Dependencies
pip install flask torch==2.1.0 moviepy==2.2.1 basicsr==1.4.2 realesrgan==0.3.0

d. Install FFmpeg

MoviePy requires FFmpeg.

Windows → Download and add to PATH

macOS

brew install ffmpeg


Linux

sudo apt-get install ffmpeg
```

2️⃣ Run the Backend Server
```text
python app.py
```

Server runs at → http://127.0.0.1:5000

3️⃣ Frontend Setup

Open index.html in a browser

It automatically connects to the backend


📜 License

Released under the MIT License – feel free to modify and share.

🤝 Contributing

Pull requests are welcome.
For major changes, open an issue to discuss your ideas.

<div align="center">


Built with ❤️ using AI + Python

</div> 
