# VG.rtl | Hardware Engineer Portfolio

A minimal, high-performance portfolio website designed to reflect the aesthetic of **EDA tools, dark mode terminals, and silicon fabrication**. 

This site was built from first principles using HTML5, Tailwind CSS, and Vanilla JavaScript to ensure zero build-step complexity while maintaining high visual fidelity.

## ⚡ Features

* **Silicon Aesthetic:** Custom SVG background animation simulating PCB traces and current flow.
* **Interactive UI:** * **Spotlight Cards:** Hover effects that track mouse movement to reveal borders/glow (simulating a flashlight in a dark lab).
    * **Glitch Logo:** CSS-only glitch animation on the logo hover.
    * **Floating Elements:** Subtle vertical float animations for depth.
* **Performance:** No heavy frameworks (React/Vue). Uses utility classes via Tailwind CSS (CDN) for rapid prototyping.
* **Responsive:** Fully responsive grid layout for mobile and desktop.
* **Animations:** Staggered entry animations and scroll-based drawing effects.

## 🛠️ Tech Stack

* **Structure:** Semantic HTML5
* **Styling:** [Tailwind CSS](https://tailwindcss.com/) (CDN)
* **Icons:** [Lucide Icons](https://lucide.dev/)
* **Logic:** Vanilla JavaScript (Intersection Observers, Mouse tracking)

## 🚀 Quick Start

Since this project uses the CDN version of Tailwind, there is no `npm install` required.

1.  **Clone the repo**
    ```bash
    git clone [https://github.com/VaradaGovind/portfolio-v2.git](https://github.com/VaradaGovind/portfolio-v2.git)
    ```
2.  **Run locally**
     simply open `index.html` in your browser.

## 🎨 Customization

To adapt this template for your own use:

1.  **Colors:** Modify the `tailwind.config` script in the `<head>` to change the `brand` colors (currently Amber-400).
2.  **Links:** Update the `href` attributes in the `#projects` section.
3.  **Content:** Edit the HTML text within the `#about` and `#experience` sections.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
