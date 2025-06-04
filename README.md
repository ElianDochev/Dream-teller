<div style="display: flex; flex-direction: row; justify-content: center; align-items: center;">
  <p align="center">
  <h1 align="center"> Eliyan Dochev </h1>
   <div align="center"  class="icons-social" style="margin-left: 10px;">
          <a style="margin-left: 10px;"  target="_blank" href="https://www.linkedin.com/in/elian-dochev-8a53a9250/">
  			<img  style="width: 40px; height: 40px" src="https://img.icons8.com/doodle/40/000000/linkedin--v2.png"></a>
          <a style="margin-left: 10px;" target="_blank" href="https://github.com/ElianDochev">
  		<img  style="width: 40px; height: 40px" src="https://img.icons8.com/doodle/40/000000/github--v1.png"></a>
  		<a style="margin-left: 5px;" target="_blank" href="mailto:eliyan.dochev@epitech.eu">
  					<img style="width: 40px; height: 40px" src="https://img.icons8.com/?size=256&id=1fmYJMlAzKXa&format=png" ></a>
        </div>
  </p>
  </div>

# 🌌 DreamTeller

**AI-Powered Story Generator**

DreamTeller is an interactive storytelling tool that uses artificial intelligence to generate fully illustrated, character-driven stories. Simply input a story idea, and DreamTeller will handle the rest—writing, designing, and illustrating each scene to bring your story to life.

---

## ✨ Features

- 📝 Generate complete stories from simple prompts  
- 🎭 Create rich, character-driven narratives across multiple scenes  
- 🎨 Produce AI-generated illustrations for each scene  
- 🎚️ Choose your story’s genre and tone  
- 💾 Save and load generated stories  
- ✏️ Customize character descriptions and settings  

---

## 🧠 How It Works

DreamTeller uses a 4-step AI pipeline:

1. **Story Outline** – Generates a rough structure based on your input  
2. **Character Development** – Builds detailed character profiles  
3. **Scene Creation** – Writes fully formed scenes with dialogue and narration  
4. **Image Generation** – Creates unique illustrations for each scene  

---

## ⚙️ Prerequisites

To run DreamTeller locally, ensure you have:

- ✅ **FAL AI API key** – Required for story and image generation  
- 🐳 **Docker** and **Docker Compose** – For backend services  
- 🟢 **Node.js** and **npm** or **yarn** – For the frontend  

---

## 🚀 Setup Instructions

### 🔧 Frontend Setup

1. Navigate to the frontend directory:

   ```bash
   cd frontend
````

2. Install dependencies:

   ```bash
   npm install
   # or
   yarn install
   ```

3. Run the development server:

   ```bash
   npm run dev
   # or
   yarn dev
   ```

---

### 🖥️ Backend Setup

From the project root, run:

```bash
docker-compose up --build
```

This will build and start all necessary backend services.

---

### 🔐 Environment Configuration

Before launching the backend, configure your FAL AI API key:

1. Create a `.env` file in the project root:

   ```
   FAL_API_KEY=your_api_key_here
   ```

2. Save the file and restart the backend if needed.

---

## 🕹️ Usage

1. Open the application in your web browser
2. Enter a story prompt or idea
3. Select:

   * Genre
   * Tone
   * Number of scenes
4. (Optional) Add detailed character and setting descriptions
5. Click **"Generate Story"**
6. View, save, or export your illustrated story

---

## ⚠️ Note

This application **requires a valid FAL AI API key** to function. You can obtain one by registering on the [FAL AI website](https://fal.ai) (not affiliated).

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---
