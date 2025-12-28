# VG.rtl | Digital Architect Portfolio

A high-performance, immersive portfolio website designed for a Hardware Engineer. The aesthetic blends **cyberpunk minimalism, CMOS fabrication visuals, and dark-mode terminal vibes**.

Built to showcase RTL designs and Embedded Systems projects, this site leverages WebGL and modern animation libraries without the bloat of heavy frontend frameworks.

## ⚡ Visual Features

* **3D Wireframe Core:** Interactive 3D Icosahedron background powered by **Three.js**, representing complex network architectures.
* **Cinematic Atmosphere:**
    * **Noise Overlay:** Film-grain texture for a tactical, analog feel.
    * **Moving Grid:** Infinite 3D perspective grid simulating a simulation environment.
    * **Custom Cursor:** Magnetic cursor with delayed trailing mechanics.
* **Glassmorphism UI:** "Bento-style" project cards with frosted glass effects (backdrop-blur) and dynamic borders.
* **Interactive Physics:**
    * **3D Tilt:** Cards respond to mouse movement using **Vanilla Tilt**.
    * **Spotlight Effect:** Mouse-tracking radial gradients that reveal card borders in the dark.
* **Smooth Motion:** Inertia-based smooth scrolling via **Lenis** and scroll-triggered entrance animations via **GSAP**.

## 🛠️ Tech Stack

This project is built for speed and ease of deployment. It uses **CDN-hosted libraries** to avoid complex build steps (`npm install` is not required).

| Category | Technology |
| :--- | :--- |
| **Core** | Semantic HTML5, Vanilla JavaScript |
| **Styling** | [Tailwind CSS](https://tailwindcss.com/) (CDN) |
| **3D & Graphics** | [Three.js](https://threejs.org/) |
| **Animations** | [GSAP](https://greensock.com/gsap) + ScrollTrigger |
| **Interaction** | [Vanilla-Tilt.js](https://micku7zu.github.io/vanilla-tilt.js/) |
| **UX Polish** | [Lenis](https://lenis.studio/) (Smooth Scroll), [Lucide](https://lucide.dev/) (Icons) |

## 🚀 Quick Start

1.  **Clone the repository**
    ```bash
    git clone [https://github.com/VaradaGovind/VG.rtl.git](https://github.com/VaradaGovind/VG.rtl.git)
    ```
2.  **Run locally**
    Simply double-click `index.html` to open it in your browser.
    *(Note: For Three.js textures to load correctly in some browsers, you may need a local server like VS Code's "Live Server" extension).*

## 🎨 Customization

To adapt this portfolio for yourself:

1.  **Theme:** Edit the `tailwind.config` script in the `<head>` to change the `accent` color (currently Cyan/Neon `#00f2ea`).
2.  **Projects:** Update the `glass-card` links in the `#work` section.
3.  **Hero:** Modify the 3D geometry in the `initThreeJS()` function inside the `<script>` tag.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
