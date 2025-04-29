# 🇹🇷 Turkish Sign Language Detection – Flask + YOLOv8

This project deploys a real-time **Turkish Sign Language Detection System** using **YOLOv8** and **Flask**. It uses a pre-trained or custom-trained YOLOv8 model to detect and classify hand signs captured from a webcam stream, enabling interactive sign recognition through a web interface.

---

## 📂 Project Structure

```
Turkish-Sign-Language-Deployment-Flask-YOLOV8/
│
├── static/                # CSS, JS, and assets
├── templates/             # HTML templates (Flask views)
├── yolov8/                # YOLOv8 model and detection script
├── app.py                 # Flask app runner
├── requirements.txt       # Required dependencies
└── README.md              # Project overview
```

---

## 🚀 Features

- ✅ Real-time sign language detection via webcam
- 🧠 Integrated with YOLOv8 for accurate recognition
- 🌐 Lightweight Flask web app
- 🎯 Easy to deploy and extend for other sign language datasets

---

## 🛠 Installation

Clone the repository:

```bash
git clone https://github.com/Ramsha-18/Turkish-Sign-Language-Deployment-Flask-YOLOV8.git
cd Turkish-Sign-Language-Deployment-Flask-YOLOV8
```

Create a virtual environment (optional but recommended):

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the App

Make sure your YOLOv8 model is available in the project directory. Then, run:

```bash
python app.py
```

Navigate to `http://127.0.0.1:5000/` in your browser to view the app.

---

## 📸 Example

*Add a screenshot or demo GIF here to visualize the output.*

---

## 🧠 Model Details

- Framework: [Ultralytics YOLOv8](https://github.com/ultralytics/ultralytics)
- Dataset: Turkish Sign Language (custom dataset or Roboflow export)
- Model format: `.pt` file trained via YOLOv8 CLI or notebook

---

## 📌 To-Do

- [ ] Improve front-end UI
- [ ] Add multi-language support
- [ ] Extend to dynamic gesture sequences

---

## 🙌 Credits

- [Ultralytics YOLOv8](https://github.com/ultralytics/ultralytics)
- Turkish Sign Language dataset
- Flask for deployment

---

## 📄 License

MIT License. Feel free to use, modify, and distribute this project with attribution.

---

## 🌐 Connect

If you like this project, please ⭐ the repo and connect with me on [GitHub](https://github.com/Ramsha-18)!
