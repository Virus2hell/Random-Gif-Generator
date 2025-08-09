# 🎲 Random GIF Generator

A fun web app built with **React** that fetches and displays random GIFs using the **Giphy API**.  
You can either generate completely random GIFs or search for GIFs based on a custom tag.  

---

## 📸 Preview

### 🔹 Random GIF
![Random GIF Preview](./images/random-gif.png)

### 🔹 Tagged GIF
![Tagged GIF Preview](./images/tagged-gif.png)

---

## 🚀 Features
- 🎞 Fetches **random GIFs** from the Giphy API
- 🔍 Search GIFs by a **custom tag**
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
