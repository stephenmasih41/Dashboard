# 📌 Personal Dashboard (Momentum Clone)

Welcome to the **Personal Dashboard** project! 🚀 This is a simple yet functional **Momentum-style** personal dashboard that displays:

✅ A **dynamic background image** from Unsplash 🎨  
✅ **Live time updates** 🕒  
✅ **Current weather information** based on your location 🌤️  
✅ **Cryptocurrency price updates** (Dogecoin) 📈  

This project is built using **HTML, CSS, and JavaScript** and fetches data from various APIs to provide a visually appealing and interactive experience.

---

## 📜 Features

### 🎨 Dynamic Background
- Fetches a **random landscape image** from **Unsplash** every time the page loads.
- Displays the **author's name** for credit.
- If an error occurs, a default image is used.

### 🕒 Live Time Display
- Displays the **current time**, which updates **every second**.

### 🌤️ Weather Information
- Uses the **OpenWeather API** to get real-time weather updates.
- Displays:
  - The **current temperature** in Fahrenheit.
  - The **city name**.
  - The **weather condition icon**.
- Uses **Geolocation API** to fetch the user's location.

### 📈 Cryptocurrency Prices
- Uses the **CoinGecko API** to display **Dogecoin's** latest price updates.
- Shows:
  - **Current price** 🎯
  - **24-hour high** 👆
  - **24-hour low** 👇
- Displays Dogecoin's **logo and name**.

---


## 🏆 Using it as a Chrome Extension
Want to use this dashboard as a **Chrome New Tab extension**? Here's how:

1. **Prepare the files**:
   - Ensure your project contains `index.html`, `index.css`, and `index.js`.
   - Create a `manifest.json` file with the following content:
     ```json
     {
       "manifest_version": 2,
       "name": "Personal Dashboard",
       "version": "1.0",
       "description": "A simple Momentum-style personal dashboard",
       "chrome_url_overrides": {
         "newtab": "index.html"
       }
     }
     ```

2. **Load the extension in Chrome**:
   - Open **Chrome** and go to `chrome://extensions/`.
   - Enable **Developer Mode** (toggle in the top-right corner).
   - Click **Load Unpacked**.
   - Select the project folder.
   - Open a **new tab** to see your dashboard in action! 🎉

---

## 🌟 API Sources
- **Unsplash API** for background images.
- **CoinGecko API** for cryptocurrency data.
- **OpenWeather API** for weather updates.

---



