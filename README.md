# Abdul Malik R - Personal Portfolio

A sleek, responsive, single-page developer portfolio site designed with the **Corporate Edge** theme. Built using HTML5, Tailwind CSS, custom animations, and EmailJS integration.

---

## 💻 How to Run the Website

### Option 1: Direct Browser Open (Easiest)
1. Navigate to the project folder (`d:\Downloads\Malik's Portfolio`).
2. Double-click the **`index.html`** file.
3. It will open instantly in your default web browser (Chrome, Edge, Firefox, Safari, etc.).

---

### Option 2: VS Code Live Server
If you use VS Code:
1. Open the project folder in VS Code.
2. Install the **Live Server** extension (by Ritwick Dey).
3. Click the **"Go Live"** button in the bottom-right status bar of VS Code.
4. The site will automatically open at `http://127.0.0.1:5500/index.html`.

---

### Option 3: Terminal HTTP Server
If you have Node.js or Python installed, you can spin up a local server. Open your terminal in the project directory and run:

* **With Node.js / NPM:**
  ```bash
  npx serve .
  ```
  *(Opens the site at `http://localhost:3000`)*

* **With Python:**
  ```bash
  python -m http.server 8000
  ```
  *(Opens the site at `http://localhost:8000`)*

---

## 🛠️ Personal Customizations

1. **Resume File:** 
   - Place your PDF resume in the `assets/` folder and rename it to `Abdul_Malik_Resume.pdf` to make the "Download Resume" buttons work.
2. **Contact Form:**
   - The form is fully wired up using your **EmailJS** credentials. Submitting the form will send messages directly to your configured email inbox.
3. **Adding Projects / Experience:**
   - Open `index.html` in an editor and search for `<section id="projects">` or `<section id="experience">` to add or modify entries.
