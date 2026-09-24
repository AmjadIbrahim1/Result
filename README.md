# 📊 Result Viewer

<div align="center">

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![JSON](https://img.shields.io/badge/JSON-000000?style=for-the-badge&logo=json&logoColor=white)

**A lightweight web page for viewing exam results from JSON data**

</div>

---

## 📌 Project Overview

**Result** is a simple web application that displays exam results loaded from local JSON files. Each `resultN.json` file contains the data for one result entry, and the page renders them in a clean, readable format — ideal for publishing results without a backend.

---

## ✨ Key Features

- 📄 **JSON-Driven** – Results stored as structured JSON files
- 🖥️ **Static Hosting** – Works on any static host (GitHub Pages, etc.)
- 🔢 **Multiple Entries** – Supports 19 result files (`result1.json` … `result19.json`)
- ⚡ **No Dependencies** – Pure HTML/CSS/JavaScript

---

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| **HTML5** | Page structure |
| **CSS3** | Styling |
| **JavaScript** | Loading and rendering JSON data |
| **JSON** | Result data storage |

---

## 📁 Project Structure

```
Result/
├── index.html       # Main viewer page
├── result1.json     # Result data (1)
├── result2.json     # Result data (2)
├── ...
├── result19.json    # Result data (19)
└── .gitignore
```

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/AmjadIbrahim1/Result.git
   ```
2. Open `index.html` in a modern browser.
3. Results load automatically from the JSON files.

> **Note:** If opened via `file://`, some browsers may block local JSON fetches. Use a local server (e.g., `npx serve`) or GitHub Pages for best results.

---

## 👨‍💻 Author

**Amjad Ibrahim**

- GitHub: [AmjadIbrahim1](https://github.com/AmjadIbrahim1)
