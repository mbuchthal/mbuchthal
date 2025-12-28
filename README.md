# Hi, I'm a Lead Frontend Engineer. 👋

I specialize in **Data Visualization**, **UI Architecture**, and building high-performance tooling for the modern web. I focus on bridging the gap between design freedom and engineering constraints.

---

## 🧇 The Waffle Visualization Ecosystem

I am currently architecting a suite of tools designed to solve the "abstraction hell" of React charting.

### 📊 [WaffleCharts](https://mbuchthal.github.io/waffle-charts/)
> **The "shadcn/ui" of Data Visualization.**

Building charts in React often forces a difficult choice: use a high-level library that's easy to start but hard to customize, or build from scratch with low-level primitives. **WaffleCharts** bridges this gap.

* **Approach:** It is not a library you install; it's a collection of copy-pasteable primitives.
* **Architecture:** You get the full power of **D3** and **Visx** for the math, but the DOM structure and styling live directly in your codebase.
* **Goal:** Total ownership of your visualization layer without reinventing the math.

### ⚡ [WaffleBatch](https://mbuchthal.github.io/waffle-batch/)
> **High-Performance React Faceting Engine.**

A specialized charting engine designed to render **thousands of small multiples** ("trellis charts") efficiently.

* **Problem:** Rendering massive dashboard grids usually crashes the main thread.
* **Solution:** Leverages virtualization, shared resource scaling, and optimized data splitting to maintain 60fps performance even with heavy data loads.

### 🎛️ [WaffleBoard](https://mbuchthal.github.io/waffle-board/)
> **Modern Dashboard Architecture.**

A production-ready dashboard template built with **React**, **Vite**, and **WaffleCharts**. It serves as the reference implementation for the ecosystem—configurable, themeable, and ready to deploy.

---

## 🛠️ Technical Stack & Tools

* **Core:** React, TypeScript, Next.js, Vite
* **Data Viz:** D3.js, Visx, HTML5 Canvas, WebGL
* **Styling:** Tailwind CSS, CSS Modules
* **State:** TanStack Query, Zustand

---

## 🔭 Other Projects

* **[Bartenders Compendium](https://github.com/mbuchthal/bartenders-compendium)** - A personal web app for managing cocktail recipes and bar inventory.

---

<p align="center">
  <a href="https://mbuchthal.github.io/waffle-charts/">Visit the WaffleCharts Documentation</a>
</p>
