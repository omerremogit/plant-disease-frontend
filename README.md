
# 🌿 LeafLens – Plant Disease Identification System (Frontend)

**LeafLens** is a lightweight, web-based plant disease classifier that allows users to upload an image of a leaf and get AI-based disease predictions. This is the **frontend interface**, designed for easy testing and demonstration of plant disease identification using an image classifier backend.

---

## 🚀 Features

- 🌱 Upload an image of a leaf
- 🧠 Predict plant disease using AI (via backend API)
- 📊 Displays disease name and placeholder analysis
- 🧾 Lightweight, mobile-responsive UI
- 🔒 Includes License, Disclaimer, Terms, Privacy, and Contact sections
- 📽️ Integrated with YouTube video demo

---

## 🖼️ Live Demo

> _Coming soon…_  
You can test the project  by opening in any browser.
> https://plant-disease-frontend.vercel.app/

---

## 🔧 Setup if you want to make local changes

### 1. Clone this repo

```bash
git clone <leaf-lens-git url>
cd leaflens-frontend
2. Open the project
Simply open index.html in your preferred browser.

No build tools or dependencies required.

🌐 API Integration
This frontend connects to a hosted backend API:

bash
Copy
Edit
POST https://web-production-96a69.up.railway.app/predict
Request: multipart/form-data with field file

Response: JSON with field predicted_class

Make sure the backend API is running or accessible, or replace the endpoint with your own.

📁 Project Structure
bash
Copy
Edit
├── index.html         # Main frontend file
├── README.md          # You're here!
📌 Notes
This version represents a web-based proof of concept for testing LeafLens.

The final version will include a mobile app with offline capabilities.

Presented as part of EAI6010 - Applications of AI @ Northeastern University.

📄 License
Licensed under GPL v0 for educational use only.
Commercial use, redistribution, or deployment without permission is restricted.

📫 Contact
For questions, reach out to the team at:
📧 leaf-lens@googlegroups.com

👥 Project Team at NEU
Mohammed Omer Ahmed

Arpita Kachhwah

Abhishek Jha

Tushar Nayak

Arjun Shrivatsan

🎥 Demo Video
Watch the demo here:
▶️ https://youtu.be/AKyaO9zKJv8

