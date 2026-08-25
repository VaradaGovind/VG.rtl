# ⚡ VG.rtl // Varada Govind Aakula

A high-performance, responsive portfolio website for **Varada Govind Aakula**—Hardware Researcher and RTL/VLSI Engineer at IIIT Allahabad. The website showcases synthesizable digital logic designs, RISC-V microarchitectures, edge AI compute accelerators, and automated multi-agent EDA debugging frameworks.

Built with a **Clean Neobrutalist aesthetic** inspired by modern retro-tech interfaces, featuring tactile physical textures, high-contrast borders, dynamic silicon die telemetry monitors, and custom cursor physics without the bloat of heavy runtime frameworks.

---

## ✨ Visual & Interaction Design

* **Clean Neobrutalist Architecture:** 3px high-contrast solid borders, crisp offset drop shadows, and a curated pastel palette (Canary Yellow, Ice Cyan, Sakura Pink, Mint Green, and Deep Onyx).
* **Subtle Retro Dot Canvas:** Fixed 24px dot-matrix background with fine 120px gridlines active across both Light and Dark themes.
* **Precision Dual Magic Cursor:**
  * **Precision Dot (`#magic-cursor-dot`):** Instantaneous 1:1 mouse tracking for pinpoint click accuracy.
  * **Spring Follower Ring (`#magic-cursor-ring`):** Smooth spring-interpolated trailing ring (`cubic-bezier(0.34, 1.56, 0.64, 1)`) with dynamic hover scaling, elastic click squash, and rotating inspection lens mode.
  * **Top-Layer Modal Retention:** Dynamically re-parents the cursor into native `<dialog>` top layers so the custom cursor never disappears during modal interactions.
* **Silicon Die Artifact Monitors:** Every project features a dedicated silicon wafer monitor displaying live clock cycle tickers, die graphics, and verified FPGA/ASIC telemetry.
* **Interactive Flip Deck / Stack View:** Toggle between a standard high-density project stack and an interactive single-card flip deck.
* **Multi-Profile Bento Resume Sheet:** Interactive profile switcher (RTL & Architecture, FPGA & Silicon, Verification & DV, Embedded Systems) with dynamic sticker updates.
* **Tactile Field Notes:** Masking-taped lab sticky notes with hover un-tilt spring physics.
* **Native Contact Modal (`<dialog>`):** 1-click clipboard email copying with instant visual feedback.

---

## 🚀 Featured Hardware Projects

| # | Project | Focus Area | Key Benchmark / Metric | Status | Repo |
|---|---|---|---|---|---|
| **1** | **Argus: Multi-Agent AI Hardware Debugger** | EDA & AI Research | VCD/FSDB Waveform Parsing + LLM Multi-Agent Reasoning | `WIP` | — |
| **2** | **Prolepsis: Predictive Thermal Management Unit** | Computer Architecture | **96.3% <85°C** Thermal Compliance, **0.087 RMSE**, 18,015 LUTs | `VDAT 2026` | [Prolepsis-SoC](https://github.com/VaradaGovind/Prolepsis-SoC) |
| **3** | **MobileNet INT8 Systolic Array Accelerator** | Edge AI / Acceleration | **51.2 GOPS**, **207.13 MHz Fmax** (`WNS +0.172ns`), 256x Sparsity | `DVCon '26` | [MobileNet-RTL](https://github.com/VaradaGovind/MobileNet-Accelerator-RTL) |
| **4** | **GridLock AES: 1.66 Gbps Cryptographic Core** | Cryptography RTL | **1.66 Gbps @ 150 MHz** (`WNS +1.049ns`), 0 BRAM S-Box | `Completed` | [GridLock-AES](https://github.com/VaradaGovind/GridLock-AES) |
| **5** | **RV32I Soft-Core & Hardware Protocol Suite** | Microarchitecture | **~300 LUTs @ 100 MHz** (`WNS +8.161ns`), UART/SPI/I2C CDC | `Synthesized` | [rtl-riscv32](https://github.com/VaradaGovind/rtl-riscv32) |
| **6** | **CMOS Standard Cell Library & Adder** | Custom VLSI & SPICE | DC Sweep Noise Margins, $t_{pd}$, & Transient Power Analysis | `Verified` | [CMOS-Library](https://github.com/VaradaGovind/CMOS-Standard-Cell-Library) |

---

## 🛠️ Tech Stack & Philosophy

Zero npm dependencies, zero build steps, zero bloated client runtimes. Designed for instant load times, 100/100 Lighthouse performance, and straightforward GitHub Pages deployment.

```
├── Semantic HTML5          (Accessible DOM, Dialog Top-Layer, JSON-LD Schema)
├── Vanilla CSS3            (Custom Properties, Neobrutalist Tokens, Spring Keyframes)
├── Modern Typography       (Space Grotesk, Inter, IBM Plex Mono via Google Fonts)
└── Vanilla JavaScript (ES6)(Theme Persistence, Dual Cursor, Deck Switcher, Clipboard API)
```

---

## ⚙️ Quick Start & Local Preview

1. **Clone the repository:**
   ```bash
   git clone https://github.com/VaradaGovind/VG.rtl.git
   cd VG.rtl
   ```

2. **Open the site:**
   - Double-click `index.html` in your file explorer to open it directly in any modern browser.
   - Alternatively, serve locally via Python:
     ```bash
     python -m http.server 8000
     ```
     Then navigate to `http://localhost:8000`.

---

## 📬 Contact & Connect

- **Engineer:** Varada Govind Aakula
- **Email:** [varada.aakula@gmail.com](mailto:varada.aakula@gmail.com)
- **GitHub:** [@VaradaGovind](https://github.com/VaradaGovind)
- **LinkedIn:** [varada-govind-aakula-3506712b5](https://www.linkedin.com/in/varada-govind-aakula-3506712b5/)

---

## 📄 License

This portfolio and associated RTL source references are distributed under the [MIT License](LICENSE).
