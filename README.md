# 🎨 Tintify – AI-Powered Chrome Extension for Colorblind Accessibility

**Tintify** is an AI-powered Chrome extension built to enhance web accessibility for people with color vision deficiencies. With real-time color detection, smart enhancements, and alternative color suggestions, Tintify transforms the way colorblind users interact with the web—especially on e-commerce sites and visually-driven platforms.

---

## 🚨 Problem

Millions of people with **color blindness** face daily challenges on the internet due to:

- **Difficulty distinguishing colors** used in product options, charts, and UI elements.
- **Lack of assistive tools** that adjust or explain web colors in real-time.
- **Frustration when online shopping**, often leading to incorrect purchases or poor experiences.

---

## ✅ Solution

Tintify empowers users with **real-time AI color identification**, **enhanced contrast modes**, and **smart suggestions**—making websites more accessible, informative, and usable for colorblind individuals.

---

## ✨ Key Features

### 🧠 AI-Powered Color Descriptions
- Hover over any element to receive **AI-generated color descriptions** (e.g., “warm terracotta orange”).
- Uses **OpenAI Vision** to interpret and explain colors in natural language.

### 🎨 Color Enhancement Filters
- Apply **filters based on colorblind type**:
  - Protanopia
  - Deuteranopia
  - Tritanopia
- Toggle filters dynamically to improve real-time visibility.

### 🔁 AI-Driven Color Alternatives
- When browsing products (e.g., clothes or furniture), the extension:
  - Identifies items with **low visibility colors**
  - Suggests similar objects in **easier-to-distinguish tones**
  - Powered by **CLIP (Contrastive Language-Image Pretraining)** for smart color matching

### ⚙️ Customizable Interface
- Set preferences for:
  - Filter type
  - Brightness/contrast levels
  - AI suggestions toggle
- Lightweight and responsive UI, accessible from the Chrome toolbar

### 🌐 Seamless Browser Integration
- **Works across all Chromium browsers**
- One-click activation—no login or setup required
- Fast, efficient, and doesn't interfere with regular browsing

---

## 🛠️ Tech Stack

### 🔹 Frontend (Chrome Extension)
- **Next.js** – Lightweight, React-based framework, ideal for extension UI
- **Tailwind CSS** – Modern utility-first styling
- **Chrome Extensions API** – To manipulate content scripts and UI overlays

### 🔹 Backend
- **Node.js** with **Express.js** – Handles AI calls, user preferences, and suggestions
- **Supabase (PostgreSQL)** – Manages user settings and session data
- **Firebase Auth** *(optional)* – For managing user profiles if needed

### 🔹 AI Services
- **OpenAI Vision API** – For generating natural language color descriptions
- **CLIP (by OpenAI)** – To provide visual alternatives and color-aware recommendations
- **TensorFlow.js** – Powers real-time on-device color transformations

### 🔹 Deployment
- **Frontend (Extension UI):** [Vercel](https://vercel.com)
- **Backend / AI Services:** **AWS Lambda** (serverless and scalable)

---

## 🚧 Roadmap

- [x] MVP with color detection and filters
- [ ] Product color suggestion for e-commerce
- [ ] Voice-over support for color descriptions
- [ ] User preference sync with login
- [ ] Publish to Chrome Web Store

---

## 🙌 Contributing

Interested in helping out? Contributions are welcome!
- Fork the repo
- Create a feature branch
- Submit a pull request

---

## 📄 License

MIT License

---

## 🙏 Acknowledgments

- [OpenAI](https://openai.com/)
- [CLIP](https://openai.com/research/clip)
- [Supabase](https://supabase.io/)
- [TensorFlow.js](https://www.tensorflow.org/js)
- [Vercel](https://vercel.com/)
- [Chrome Extensions Developer Docs](https://developer.chrome.com/docs/extensions/)

---

### Built to empower colorblind users. One color at a time.