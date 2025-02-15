# 🖼️ DALL-E Clone - AI Image Generator  

A **full-stack AI-powered image generation** web application built with the **MERN stack** and OpenAI's DALL-E API. Users can generate images based on text prompts and manage their saved images.  

## 🚀 Features  

✅ **AI Image Generation** - Users enter text prompts, and OpenAI's DALL-E API generates images.  
✅ **Predefined Prompts** - 50+ creative prompts to inspire users.  
✅ **Image Storage** - Generated images are stored securely using **Cloudinary**.  
✅ **MERN Stack** - Full-stack architecture with **React.js (frontend) and Node.js + Express.js (backend)**.  

---

## 🛠️ Tech Stack  

- **Frontend:** React.js (Vite), Tailwind CSS  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB  
- **API:** OpenAI's DALL-E API  
- **Cloud Storage:** Cloudinary  

---
## ⚡ Getting Started  

### 
**1️⃣ Clone the Repository**  

```git clone https://github.com/Shreya327/dalle-e
cd DALL-E-Clone```

**2️⃣ Set Up Backend (Server)**

```cd server
npm install```

- Create a .env file in the server folder and add:
```OPENAI_API_KEY=your_openai_api_key
MONGO_URI=your_mongodb_connection_string
CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret```

-Start the server
```npm run dev```

**3️⃣ Set Up Frontend (Client)**

```cd ../client
npm install
npm run dev```

