# 📸 Responsive Image Gallery with Lightbox & Category Filtering

A lightweight, modern, and fully responsive interactive Image Gallery built from scratch using clean **HTML5**, **CSS3**, and **Vanilla JavaScript**. 

This project features smooth hover states, dynamic category filtering, and a fully functional overlay Lightbox modal for a seamless user viewing experience.

---

## ✨ Key Features

* **⚡ Dynamic Filtering:** Instantly filter images by category (Nature, City, Animals, or All) without page reloads.
* **🔍 Interactive Lightbox:** Click any image to view it in full screen within an elegant dark-overlay modal.
* **↔️ Modal Navigation:** Effortlessly browse through images using built-in Next (`❯`) and Previous (`❮`) buttons inside the lightbox.
* **📱 Fully Responsive Layout:** Built using modern **CSS Grid (auto-fit/minmax)**, ensuring a perfect layout across desktops, tablets, and smartphones.
* **✨ Smooth Animations:** Includes elegant hover transitions with subtle scale zooming (`transform: scale(1.1)`) and brightness adjustments.
* **🖱️ Smart UX Interactions:** The lightbox safely closes when clicking the close button (`×`) or anywhere outside the main modal image.

---

## 🛠️ Built With

* **HTML5:** Semantic architecture layout.
* **CSS3:** Custom responsive grid styling, CSS variables, and fluid transitions.
* **JavaScript (ES6+):** Pure Vanilla JS DOM manipulation for image array indexing, lightboxes, and filtering logic.
* **Placeholder Images:** Powered by [Lorem Picsum](https://picsum.photos/).

---

## ⚙️ How to Setup and Run Locally

Since this project relies completely on frontend client-side technologies, it requires zero installation or runtime environments!

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
    ```
2.  **Navigate Into the Project Directory:**
    ```bash
    cd your-repo-name
    ```
3.  **Launch the Project:**
    Simply open the `index.html` file in any modern web browser (Chrome, Edge, Safari, Firefox).

---

## 📂 Code Architecture Highlight

* **Image Slicing & Arrays:** JavaScript queries dynamically loaded image nodes using `.querySelectorAll()` to tracking the `currentIndex`.
* **Seamless Infinite Loops:** Navigation cycles smoothly beyond limits using the modulo operator:
    ```javascript
    currentIndex = (currentIndex + 1) % images.length; // Next loop
    currentIndex = (currentIndex - 1 + images.length) % images.length; // Prev loop
    ```

---

## 📝 License

This project is open-source and available under the **MIT License**. Feel free to customize, fork, or use it for your personal portfolios!