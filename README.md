# 📊 CGPA & SGPA Calculator

An elegant, high-contrast, editorial-grade academic ledger designed explicitly for Indian university students tracking progress under the **Choice Based Credit System (CBCS)**. Stepping completely away from generic SaaS aesthetics, this tool features sharp typography, intentional whitespace, a fluid dual-theme layout, and a hardcoded ink-saving print compilation engine.

Live Preview: **[Insert Your Live Domain Link Here]**

---

## ✨ Features

* **Dual Engine Architecture:** Toggle seamlessly between single-term Semester Grade Point Average (**SGPA**) worksheets and Cumulative Grade Point Average (**CGPA**) transcripts.
* **Bespoke Premium Themes:** Fluid, zero-lag dynamic animations transitioning between **Executive Midnight** (Dark Mode) and **Ivory Alabaster** (Light Mode) built on a 0.4s cubic-bezier matrix.
* **Smart Print & Export Engine:** Choose between exporting your **Result Only** (for clean dashboard screenshots) or a structured **Full Academic Transcript** displaying columns for subjects, weights, and grades. 
* **Zero-Ink Bleed Pipeline:** No matter which theme you enjoy on screen, the physical print protocol overrides layout rendering to process raw black typography on clean white layouts for formal university submissions.
* **On-Page Conversion Matrix:** Instant percentage calculations utilizing specialized algorithms configured for major universities including:
  * **Chandigarh University** ($\text{CGPA} \times 10.0$)
  * **Delhi University & Standard UGC** ($\text{CGPA} \times 9.5$)
  * **VTU Karnataka** ($(\text{CGPA} - 0.75) \times 10.0$)
  * **SPPU Pune** ($\text{CGPA} \times 8.9$)
  * **KTU Kerala** ($\text{CGPA} \times 10.0$)

---

## 📐 Custom Grading Parameters

The underlying system calculates credit-weighted mathematical models based on your exact grading metrics:

$$\text{SGPA} = \frac{\sum (\text{Course Credits} \times \text{Grade Points})}{\sum \text{Course Credits}}$$

| Letter Grade | Status | Value |
| :--- | :--- | :--- |
| **A+** | Outstanding | **10** |
| **A** | Excellent | **9** |
| **B+** | Very Good | **8** |
| **B** | Good | **7** |
| **C+** | Satisfactory | **6** |
| **C** | Fair / Pass | **5** |
| **F** | Fail | **0** |

---

## 🛠️ Tech Stack & Architecture

* **Markup & Structure:** Semantic, clean HTML5 document graph.
* **Styling Engine:** Pure CSS3 natively handling viewport scoping via advanced flexbox grids, aspect clamps, and hardware-accelerated root token animations.
* **Logic Core:** Light, zero-dependency procedural Vanilla JavaScript handling live calculations and viewport triggers safely.
* **SEO Assets:** Fully equipped with pre-compiled `sitemap.xml` indices and `robots.txt` architectures for structural search engine discovery.

---

## 🚀 Local Deployment

To run this platform locally or test code updates on your personal station:

1. Clone this repository directly:
   ```bash
   git clone [https://github.com/divyansh2453/cgpa-sgpa-calculator.git](https://github.com/divyansh2453/cgpa-sgpa-calculator.git)
