# Thrust Fit — Premium Gym Poster Mockup

This project contains the design rules, asset references, and high-fidelity HTML/CSS mockups for the **Thrust Fit** outdoor wall entrance poster located in **Vignan Nagar**.

## 1. Project Context & Dimensions

- **Usage**: Outdoor wall poster at the main entrance of Thrust Fit.
- **Goal**: Showcase premium amenities, scale, and recovery features, conveying luxury and exclusivity.
- **Physical Size**: 10 ft Width × 8 ft Height (5:4 aspect ratio).
- **Mockup Rendering Size**: 1500px × 1200px (fully scalable using CSS container query units and viewport metrics).

---

## 2. File Directory Structure

- **`v2.html`**: **[Active Version]** Includes the latest visual design, featuring a horizontal premium stats strip, an increased-size Thrust Fit logo, a 75% visible bottom watermark, and `mask-image` opacity blending for the hero athletes.
- **`v1.html`**: A copy of the initial approved visual mockup layout.
- **`poster.html`**: The original prototype template.
- **`rules.md`**: Detailed poster design specs including visual zones, color hex values, and typography choices.
- **`logo.svg`**: The SVG brand logo for Thrust Fit.
- **`bg.jpeg`**: High-quality background image showcasing the gym interior with floor-to-ceiling glass windows.
- **`hero-transparent.png`**: Transparent PNG image of elite athletes composited on the left side.

---

## 3. Key Design Features & Technology

- **Luxury Typography**: Combines **Playfair Display** (a bold, elegant serif for headlines, stats, and taglines) and **Inter** (a clean, modern sans-serif for labels and body details).
- **watermark Silhouette**: A massive, bold `THRUST` branding silhouette spanning the bottom of the poster at `22cqw` font size, styled using Playfair Display to match the luxury design system.
- **Fluid Transparency Blending**: The hero athletes on the left blend into the dark slate/charcoal background at their feet using a CSS `-webkit-mask-image` linear-gradient mask, creating a seamless edge-free fade.
- **Responsive Dashboard Preview**: The mockups include a top preview dashboard (hidden during print) with a toggle between a physical billboard scene and a raw layout view, plus a scaling slider.

---

## 4. How to Preview & Export

### Local Preview
Simply open **[`v2.html`](./v2.html)** in any modern web browser.

### Exporting to Print-Ready PDF
1. Open the file in your browser and toggle the view to **Raw Poster**.
2. Click **Print / PDF** in the control header (or press `Ctrl + P` / `Cmd + P`).
3. Ensure the destination is set to **Save as PDF** or your local high-res printer.
4. **Important**: Under browser print settings, make sure to:
   - Set **Layout** to **Landscape**.
   - Check **Background graphics** under options to ensure the background gym image and overlays render.
   - Set **Margins** to **None** for a borderless edge-to-edge print.
