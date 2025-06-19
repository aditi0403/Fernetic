# 🌿 Fernetic — Plant Image Analyzer Web App

**Fernetic** is a smart plant analysis web application that lets users upload an image of a plant and instantly receive a detailed, AI-generated report about its species, health, care tips, and interesting facts — all in a downloadable PDF format.

[🌐 Live Demo](https://fernetic.onrender.com)

---

## 📸 Features

- ✅ Upload plant images via drag & drop or file input  
- 🔎 AI-powered plant analysis using **Gemini 1.5 Flash**
- 📃 Auto-generated **Plant Analysis PDF Report** (with embedded image)
- 🌐 Clean and responsive UI (HTML + CSS + vanilla JS)
- 🧠 Backed by **Node.js**, **Express**, and **PDFKit**
- 🔐 Built with privacy and efficiency in mind

---

## 🧠 Tech Stack

| Frontend              | Backend              | Tools / APIs             |
|-----------------------|----------------------|---------------------------|
| HTML, CSS, JS         | Node.js, Express.js  | Google Generative AI API |
| Responsive UI         | Multer (file upload) | PDFKit (PDF generation)  |

---

## 📁 Folder Structure

```
Fernetic/
├── app.js                    # Main backend server
├── package.json
├── public/                   # Static files (HTML, CSS, JS, logo, etc.)
│   └── index.html
├── uploads/                  # Temp folder for uploaded images
└── reports/                  # (Generated PDF files temporarily stored here)
```

---

## ⚙️ Setup Instructions

### 🔧 1. Clone the Repository

```bash
git clone https://github.com/aditi0403/Fernetic.git
cd Fernetic
```

### 📦 2. Install Dependencies

```bash
npm install
```

### 🔑 3. Setup Environment Variables

Create a `.env` file in the root folder with the following:

```ini
gemini=YOUR_GOOGLE_GENAI_API_KEY
```

Get your API key from [Google AI Studio](https://aistudio.google.com/).

### ▶️ 4. Run the App

```bash
node app.js
```

Visit: http://localhost:8000

---

## 📌 Example Output

✅ **AI-detected species:** Ficus lyrata  
✅ **Health status:** Healthy leaves, no visible pest damage  
✅ **Care tips:** Bright indirect light, moderate watering  
✅ **PDF Report:** Includes full write-up and image  

---

## 🧪 Future Improvements

- 🌱 Add plant growth tracking over time
- 📸 Webcam input for plant scanning
- 🔐 User login and saved history
- 📊 Analytics dashboard

---

## 🙋‍♀️ About Me

I'm **Aditi Sharma**, a CS undergrad passionate about full-stack development, AI, and clean UI/UX design. I created Fernetic to combine my love for tech and nature 🌿.

[🔗 Connect on LinkedIn](https://linkedin.com/in/aditi-sharma)

---

## 📄 License

This project is licensed under the MIT License.

---

**Made with ❤️ and lots of ☕**
