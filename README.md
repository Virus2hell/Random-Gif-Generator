# 🎲 Random GIF Generator

A fun web app built with **React** that fetches and displays random GIFs using the **Giphy API**.  
You can either generate completely random GIFs or search for GIFs based on a custom tag.  

---

## 📸 Preview

### 🔹 Random GIF
![Random GIF Preview](https://github.com/Virus2hell/Random-Gif-Generator/blob/bcc162eb4ab93c099da3c10165f8b19378bfc690/img1.png)

### 🔹 Tagged GIF
![Tagged GIF Preview](https://github.com/Virus2hell/Random-Gif-Generator/blob/bcc162eb4ab93c099da3c10165f8b19378bfc690/img3.png)

### 🔹 Download GIF
![Download GIF Preview](https://github.com/Virus2hell/Random-Gif-Generator/blob/1fb0a1d860b7fc6cbbb365a1abeace9b5055005f/img4.png)

---

## 🚀 Features
- 🎞 Fetches **random GIFs** from the Giphy API
- 🔍 Search GIFs by a **custom tag**
- 📂 GIF **download** option
- ⚡ Smooth loading state with a spinner
- 📱 Responsive design using **Tailwind CSS**
- ✨ Simple & clean UI

---

## 🛠 Tech Stack
- **React.js** – Frontend framework
- **Tailwind CSS** – Styling
- **Axios** – API requests
- **Giphy API** – GIF data

---

## 🎯 Usage
- Click **Generate** to get a new random GIF
- Type a keyword in the input box to search GIFs by tag
- Click **Download** to save the displayed GIF to your device
- Enjoy endless fun GIFs 🎉

---

## 📂 Project Structure

```
my-app/
├── public/
│ ├── index.html
│ └── robots.txt
├── src/
│ ├── components/
│ │ ├── Random.jsx # Random GIF generator
│ │ ├── Spinner.jsx # Loading spinner
│ │ └── Tag.jsx # Tagged GIF generator
│ ├── hooks/
│ │ └── useGif.js # Custom hook for fetching GIFs
│ ├── App.jsx
│ ├── index.css
│ ├── index.js
│ └── .env # API key file
├── .gitignore
├── package-lock.json
├── package.json
├── README.md
└── tailwind.config.js
```

---

## ⚙️ Setup & Installation
1. **Clone the repository**
```bash
git clone 
cd my-app
```

2. **Install dependencies**
```bash
npm install
```

3. **Get your Giphy API Key**
- Create a free account on [**Giphy Developers**](https://developers.giphy.com/)
- Create an **app** and copy your **API key**

4. **Create .env file**
```env
REACT_APP_GIPHY_API_KEY = your_api_key_here
```

5. **Run the app**
```bash
npm start
```




