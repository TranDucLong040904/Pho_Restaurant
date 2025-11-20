<div align="right">
  <a href="README.md"><img src="https://img.shields.io/badge/English-blue?style=flat-square&logo=github&logoColor=white&labelColor=000080" alt="English"></a>
  <a href="README.vi.md"><img src="https://img.shields.io/badge/Tiếng_Việt-red?style=flat-square&color=C90000" alt="Tiếng Việt"></a>
</div>

# 🍜 Pho Restaurant - Introduction and Menu Website
<div align="center">

<div align="center">

![Repo Size](https://img.shields.io/github/repo-size/TranDucLong040904/Project_PHP_Laravel?style=flat-square&label=Size&color=orange)
![Last Commit](https://img.shields.io/github/last-commit/TranDucLong040904/Project_PHP_Laravel?style=flat-square&label=Last%20Commit&color=blue)
![Commit Activity](https://img.shields.io/github/commit-activity/y/TranDucLong040904/Project_PHP_Laravel?style=flat-square&label=Commits/Year&color=red)
![Stars](https://img.shields.io/github/stars/TranDucLong040904/Project_PHP_Laravel?style=flat-square&color=yellow)
[![Ask Me Anything !](https://img.shields.io/badge/Ask%20me-anything-1abc9c.svg?style=flat-square)](https://github.com/TranDucLong040904)

</div>

</div>


## General Introduction

**Pho Restaurant** is a **mini static web project** designed to provide an overview of **Phở**—Vietnam's famous traditional dish. The website includes sections on its history, preparation, regional variations (Hanoi Pho, Nam Dinh Pho), and a simple menu page.

This project serves as a basic **Front-end practice exercise**, focusing on **One-Page Layout** design skills, effectively utilizing **HTML5** and the **Bootstrap** library.

---

## 👨‍💻 About The Author

The project is developed and maintained by:

| Avatar | Information | Contact |
| :---: | :--- | :--- |
| <img src="static/images/github_circle.png" width="80" height="80" style="border-radius:50%; object-fit:cover;"/> | **Trần Đức Long** | [![GitHub](https://img.shields.io/badge/GitHub-100000?style=flat-square&logo=github&logoColor=white)](https://github.com/TranDucLong040904)<br>[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:22010139@st.phenikaa-uni.edu.vn) |

---

## ✨ Key Features

* **📱 Responsive Design:** Uses Bootstrap to ensure the interface displays well across various screen sizes.
* **🌐 One-Page Layout:** The navigation bar allows smooth scrolling to different sections within the same page (`#section1` to `#section6`).
* **🌗 Light/Dark Mode:** The interface toggle button utilizes Bootstrap's `data-bs-theme` attribute (implemented via JavaScript).
* **🛒 Shopping Cart/Order Form:** The `user.html` page simulates a user information input and checkout form, inspired by the W3Schools style.
* **🖼️ Visual Effects:**
    * Uses attractive images of Pho and its components.
    * Includes a **spinning image effect** (CSS `animation: spin`) in the Introduction section.

---

## 🛠️ Technologies Used

| Technology | Description |
| :--- | :--- |
| **HTML5** | Provides the main content structure of the website. |
| **CSS3** | Customizes styling, colors, and creates effects (e.g., spinning effect). |
| **Bootstrap 5** | The core CSS/JS library for building layout, grid system (`row`/`col`), and ensuring Responsiveness. |
| **JavaScript (Vanilla JS)** | Handles basic interactions (switching light/dark mode, increasing/decreasing product quantity in modal). |

---

## 📂 Source Code Structure (Code Tree)

```text

│   index.html          # Homepage: Pho Introduction, History, Preparation, Menu, Location (One-Page)
│   README.md           # This file
│   user.html           # Shopping Cart/Checkout Form Page
│
└───static
    ├───css
    │   ├── bootstrap.css   # Bootstrap File (customized if any)
    │   └── style.css       # Custom CSS file (contains specific styles, spinning effect)
    │
    ├───images          # Images for dishes, logo, and Pho variations
    │   └── ... (.png, .jpg)
    │
    └───js
        ├── bootstrap.js    # Bootstrap JavaScript File
        └── main.js         # Custom JavaScript File (contains mode switch logic, quantity adjustment)
```

## 🚀 Setup & Run Instructions
Since this is a static web project, setup and running is very simple:
```bash
# 1. Clone the repository to your computer:
git clone https://github.com/TranDucLong040904/Pho_Restaurant.git

# 2. Open the cloned directory.
# 3. Open the index.html file with any modern web browser (Chrome, Firefox, Edge...).
# 4. To check the Shopping Cart page, open user.html.
```
---

## 📝 Main Website Content
The website content is divided into main sections:

#section1: Homepage / Pho (General introduction to Pho).

#section2: News / History of Formation (Origins in Hanoi/Nam Dinh).

#section3: Preparation (Focuses on the broth cooking process).

#section4: Variations (Comparison between Hanoi Pho and Nam Dinh Beef Pho).

#section5: Menu (Displays dishes: Rare Beef, Flank/Brisket, Special).

#section6: Location (Embeds Google Maps).
---

## 📜 License
This project is provided free of charge for personal study and reference purposes during academic coursework.