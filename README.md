# VG.rtl | RTL & VLSI Engineering Portfolio

A high-performance, immersive portfolio website designed for a Hardware Engineer. The aesthetic blends **cyberpunk minimalism, CMOS fabrication visuals, and dark-mode terminal vibes**.

Built to showcase RTL designs, RISC-V microarchitecture, and edge-compatible hardware accelerators, this site leverages WebGL and modern animation libraries without the bloat of heavy frontend frameworks.

## ⚡ Visual Features

* **3D Wireframe Core:** Interactive 3D Icosahedron and Torus background powered by **Three.js**, representing complex network architectures and clock cycles.
* **Cinematic Atmosphere:**
    * **Noise Overlay:** Film-grain texture for a tactical, analog feel.
    * **Moving Grid:** Infinite 3D perspective grid simulating an EDA/simulation environment.
    * **Custom Cursor:** Magnetic cursor with delayed trailing mechanics and blend-mode difference.
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
| **Styling** | [Tailwind CSS](https://tailwindcss.com/) (via CDN script) |
| **3D & Graphics** | [Three.js](https://threejs.org/) |
| **Animations** | [GSAP](https://greensock.com/gsap) + ScrollTrigger |
| **Interaction** | [Vanilla-Tilt.js](https://micku7zu.github.io/vanilla-tilt.js/) |
| **UX Polish** | [Lenis](https://lenis.studio/) (Smooth Scroll), [Lucide](https://lucide.dev/) (Icons) |

## 🚀 Featured Projects Included

The portfolio comes pre-configured with a grid layout highlighting advanced hardware projects:
* **Prolepsis:** ISA-Agnostic Predictive Thermal Management Unit (TMU) for RISC-V.
* **Task-Aware Object Detection:** Edge AI pipeline on Genesys-2 FPGA with INT8 systolic arrays.
* **GridLock AES:** 1.6 Gbps AXI4 encryption engine.
* **RV32I Soft-Core:** Custom single-cycle RISC-V processor.
* **Hardware Protocol Stack:** Custom UART, SPI, and I2C (CDC) controllers.
* **CMOS Cell Library:** SPICE-validated standard cells.

## ⚙️ Quick Start

1.  **Clone the repository**
    ```bash
    git clone [https://github.com/VaradaGovind/VG.rtl.git](https://github.com/VaradaGovind/VG.rtl.git)
    ```
2.  **Run locally**
    Simply double-click `index.html` to open it in your browser.
    *(Note: For Three.js materials and Lenis scrolling to execute perfectly in some browsers, you may need a local server like VS Code's "Live Server" extension).*

## 🎨 Customization

To adapt this portfolio for yourself:

1.  **Theme:** Edit the `tailwind.config` script in the `<head>`. The primary accents are currently set to `signal: '#22D3EE'` (Cyan) and `lime: '#A3E635'`.
2.  **Projects:** Update the `glass-card` structures in the `#work` section. You can use the `data-category` attribute to tag projects for the filtering system.
3.  **Hero:** Modify the 3D geometry in the `initThreeJS()` function inside the bottom `<script>` tag.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
