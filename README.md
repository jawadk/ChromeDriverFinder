# ChromeDriver Finder

A simple and fast web tool for QA Engineers and Automation Developers to easily find and download the correct **ChromeDriver** version based on their **installed Chrome version** and **operating system**.

🔗 **Live Website (GitHub Pages):**  
https://jawadk.github.io/ChromeDriverFinder/

---

## 🚀 Features

- ✔ Fetches official ChromeDriver versions directly from Google  
- ✔ Filter by **Chrome version**  
- ✔ Filter by **platform (Windows, macOS, Linux)**  
- ✔ **Direct download** or **copy link**  
- ✔ Clean, modern, responsive UI  
- ✔ Fully open-source  
- ✔ NO backend required (pure frontend)  
- ✔ Auto-detect Chrome version (optional enhancement)  

---

## 🧭 Why This Tool Exists

Yes, tools like **WebDriverManager** exist — but manual ChromeDriver downloads are still required when:

- 🔒 Working in **air-gapped / restricted environments**  
- 🏢 Organizations enforce **strict security controls**  
- 🏛 Legacy frameworks do not support auto-driver management  
- 🧪 QA teams need exact driver versions for debugging  
- ⚙️ CI/CD pipelines require **manual zipped drivers**  
- 🖥️ Testers must use **version-locked drivers**  

ChromeDriverFinder instantly solves these real-world automation challenges.

---

## 🛠️ Tech Stack

- **HTML + JavaScript**
- **TailwindCSS**
- Fetches data from Google:  
  https://googlechromelabs.github.io/chrome-for-testing/known-good-versions-with-downloads.json

---

## 📦 How to Use

1. Open the website:  
   👉 https://jawadk.github.io/ChromeDriverFinder/

2. Select:
   - Chrome version  
   - Platform (win32, mac-x64, linux64 etc.)

3. Click:
   - **Download** – downloads the zip  
   - **Copy Link** – copies direct link to clipboard  

That’s it. No setup required.

---

## 📥 Local Development

Clone the repo:

```bash
git clone https://github.com/jawadk/ChromeDriverFinder
