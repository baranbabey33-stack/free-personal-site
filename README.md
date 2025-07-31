# free-personal-site

# My Premium Personal Portfolio Website

![Website Screenshot - Hero Section Example](https://hizliresim.com/48j0g7h)

A modern, responsive, and highly interactive personal portfolio website designed to showcase my skills, projects, and professional brand in the best possible light. Built with a focus on elegant UI/UX, smooth animations, and cross-device compatibility.

---

## ✨ Features

* **Clean & Minimal Design:** A professional and aesthetically pleasing layout with attention to detail.
* **Fully Responsive:** Optimized for seamless viewing across desktops, tablets, and mobile devices.
* **Animated Background:** Subtle and engaging particle effects using Particles.js to create a dynamic visual experience.
* **Custom Mouse Cursor:** An interactive custom cursor with hover effects over clickable elements.
* **Dark/Light Mode Toggle:** Allows users to switch between dark and light themes, with preference saved in local storage.
* **Smooth Animations (AOS.js):** Elements gracefully animate into view as you scroll down the page.
* **Typing Effect Headline:** A dynamic and engaging introduction in the hero section (e.g., "I'm a Software Engineer | Web Developer | Problem Solver").
* **Sticky Navigation:** A transparent header that becomes solid on scroll, with active section highlighting (Scrollspy).
* **Project Portfolio:** A dedicated section and page to showcase your projects with images, descriptions, and tech stacks.
* **Contact Form:** A functional contact form with client-side validation for easy communication.
* **Social Media Integration:** Links to your professional social profiles (LinkedIn, GitHub, Instagram, Twitter) with hover effects.
* **High-Quality Favicon:** Professional favicon for browser tabs and mobile shortcuts.

---

## 🚀 Technologies Used

* **HTML5:** For semantic and structured content.
* **CSS3:** For styling, responsiveness, and animations.
* **JavaScript (ES6+):** For interactivity, dynamic content, and UI/UX enhancements.
* **AOS.js (Animate On Scroll):** A lightweight library for scroll-based animations.
* **Particles.js:** For creating interactive particle backgrounds.
* **Typed.js:** For the dynamic typing effect in the hero section.
* **Font Awesome:** For scalable vector icons.
* **Google Fonts:** For modern and professional typography.

---

## 📦 Setup & Installation

To get a local copy of this project up and running, follow these simple steps:

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/baranbabey33-stack/YOUR_REPO_NAME.git](https://github.com/baranbabey33-stack/YOUR_REPO_NAME.git)
    # Replace YOUR_REPO_NAME with the actual name of your repository (e.g., my-premium-portfolio)
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd YOUR_REPO_NAME
    ```
3.  **Open `index.html`:** Simply open the `index.html` file in your web browser. All assets (CSS, JS, images) are linked relatively.

---

## 🛠️ Customization

This website is designed for easy personalization:

1.  **Content:**
    * Open `index.html`, `about.html`, `projects.html`, and `contact.html`.
    * Replace all placeholder text like `[Your Name]`, `[YourBrand]`, `yourusername`, `your.email@example.com`, and project descriptions with your actual information.
2.  **Images:**
    * The current images are directly linked from external URLs. For better performance and control, it's highly recommended to:
        * Download high-quality images relevant to your content.
        * Place them in the `assets/images/` folder.
        * Update the `src` attributes in your HTML files (e.g., `<img src="assets/images/your-profile-pic.jpg">`) and `url()` paths in `assets/css/style.css` (for the hero background) to point to your local images.
3.  **Colors & Fonts:**
    * Modify the CSS variables in `assets/css/style.css` (`:root` section) to change the primary, secondary, accent, and background colors. This will instantly update the entire theme.
    * Change the `font-family` properties to use different Google Fonts if desired.
4.  **Typing Effect:**
    * Edit the `strings` array in `assets/js/script.js` to customize the text that appears in the typing effect (e.g., `["a Data Scientist.", "an AI Specialist."]` ).
5.  **Favicon:**
    * Generate your own favicon set (e.g., using [Favicon.io](https://favicon.io/)) and replace the files in `assets/images/`.

---

## 🚀 Deployment (GitHub Pages)

This website is perfectly suited for deployment using GitHub Pages, offering free and easy hosting.

1.  **Create a GitHub Repository:**
    * Go to your GitHub account (`https://github.com/baranbabey33-stack`).
    * Click the `+` icon -> `New repository`.
    * **Important:** If you want your website to be accessible directly at `https://baranbabey33-stack.github.io`, name your repository exactly `baranbabey33-stack.github.io`. Otherwise, choose any name (e.g., `my-personal-website`).
    * Set visibility to `Public`. **Do NOT initialize with a README or other files.**
2.  **Push Your Code:**
    * Open your terminal/command prompt.
    * Navigate to your project folder (`cd my-portfolio`).
    * Initialize Git (if not already done):
        ```bash
        git init
        ```
    * Add all files:
        ```bash
        git add .
        ```
    * Commit your changes:
        ```bash
        git commit -m "Initial commit: My premium personal website"
        ```
    * Rename your branch to `main` (if it's `master`):
        ```bash
        git branch -M main
        ```
    * Connect to your GitHub repository (replace `YOUR_REPO_NAME`):
        ```bash
        git remote add origin [https://github.com/baranbabey33-stack/YOUR_REPO_NAME.git](https://github.com/baranbabey33-stack/YOUR_REPO_NAME.git)
        ```
    * Push your code:
        ```bash
        git push -u origin main
        ```
3.  **Enable GitHub Pages:**
    * Go to your repository on GitHub.
    * Click on the **`Settings`** tab.
    * In the left sidebar, click on **`Pages`**.
    * Under "Build and deployment", ensure "Source" is set to **`Deploy from a branch`**.
    * Under "Branch", select `main` (or `master`) and the `/ (root)` folder.
    * Click **`Save`**.

Your website should be live at `https://baranbabey33-stack.github.io/` (if you named the repo `baranbabey33-stack.github.io`) or `https://baranbabey33-stack.github.io/YOUR_REPO_NAME/` within a few minutes.

---

## 📧 Contact

Feel free to reach out if you have any questions or collaboration opportunities!

* **LinkedIn:** [Your LinkedIn Profile URL]
* **GitHub:** [Your GitHub Profile URL]
* **Email:** [Your Email Address]

---

**© 2025 [Your Name]. All Rights Reserved.**
