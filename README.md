# Unified IT — Scroll Services

An immersive, scroll-driven service showcase for **Unified IT**, featuring interactive particle animations, glowing service icons, and a cinematic dark-purple visual experience built with Three.js and Anime.js.

## ✨ Overview

Unified IT Scroll Services is a single-page web experience designed to present IT infrastructure and digital services through an animated, interactive interface. Instead of a traditional static service list, users navigate through individual service sections using scrolling and on-screen navigation controls.

## 🚀 Features

- **Interactive 3D particle background** — Animated particles powered by Three.js.
- **Scroll-driven animations** — Visual transitions respond to the user's scrolling.
- **Animated service icons** — SVG icons feature stroke-drawing animations and glowing effects.
- **11 IT service categories** — Dedicated sections for hosting, security, storage, and more.
- **Interactive navigation dots** — Jump directly to a specific service section.
- **Service details and call-to-action links** — Each section provides a description and an "Order Now" link.
- **Responsive layout** — CSS adjustments accommodate smaller screens.
- **Cinematic visual design** — Dark backgrounds, purple gradients, glowing elements, and smooth transitions.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Page structure and content |
| CSS3 | Layout, responsive styling, gradients, and visual effects |
| JavaScript | Scroll handling, dynamic sections, and interactive behavior |
| [Three.js](https://threejs.org/) | Real-time WebGL particle animation |
| [Anime.js](https://animejs.com/) | Animation and motion effects |
| SVG | Custom animated service icons |

## 📂 Project Structure

```text
Unified_IT_Scroll-Service/
│
├── Unified IT — Scroll Services.html
└── README.md
```

The application is implemented in a single HTML file containing the markup, styles, and JavaScript logic. Three.js and Anime.js are loaded through external CDNs.

## ⚙️ Getting Started

### Prerequisites

- A modern web browser, such as Google Chrome, Microsoft Edge, or Firefox.
- An internet connection to load the external JavaScript libraries.
- A code editor such as Visual Studio Code (optional).

### Installation

**1. Clone the repository**

```bash
git clone https://github.com/istiakahasan/Unified_IT_Scroll-Service.git
```

**2. Navigate to the project directory**

```bash
cd Unified_IT_Scroll-Service
```

**3. Run the project**

Open `Unified IT — Scroll Services.html` directly in your browser.

Alternatively, open the project folder in Visual Studio Code and use the Live Server extension to serve the HTML file locally.

No build process or package installation is required for the current standalone implementation.

## 🎨 Services Showcased

The experience presents the following IT services:

1. Cloud VPS Hosting
2. Dedicated Server
3. Managed Hosting
4. Email Hosting
5. Microsoft 365
6. SSL Certificates
7. Backup Solutions
8. Domain Registration
9. Cloud Storage
10. Cyber Security Services
11. Industry Solutions

Each service includes a title, a short description, and a link to its corresponding service page on the Unified IT website.

## 🔧 Customization

### Update service content

Open `Unified IT — Scroll Services.html` and locate the `SV` array in the JavaScript section.

You can update service names, descriptions, destination paths, and animation-related values there.

### Customize the appearance

Modify the CSS variables and styles to change the visual theme, including:

- Background and text colors
- Purple gradient effects
- Typography and spacing
- Service panel positioning
- Responsive layout behavior
- Icon glow and animation styling

### Adjust the animated background

The Three.js configuration controls the particle system, motion, colors, and rendering behavior. Modify these settings to experiment with different visual effects.

## 🌐 External Dependencies

The project loads its animation libraries from these CDNs:

- [Three.js CDN](https://cdnjs.cloudflare.com/ajax/libs/three.js/r128/three.min.js)
- [Anime.js CDN](https://cdn.jsdelivr.net/npm/animejs@4.0.2/dist/bundles/anime.umd.min.js)

An internet connection is required for these dependencies to load successfully.

## 🎯 Project Objective

The objective is to create a modern and engaging way to explore IT services through motion, visual storytelling, and interactive navigation. The project demonstrates how standard web technologies can be combined with WebGL-based rendering and animation libraries to build a more immersive service presentation.

## 👨‍💻 Author

**Istiak Ahasan**

- GitHub: [@istiakahasan](https://github.com/istiakahasan)
- Project Repository: [Unified_IT_Scroll-Service](https://github.com/istiakahasan/Unified_IT_Scroll-Service)
- Website: [unified.it.com](https://unified.it.com/)

## 📄 License

No license has been specified in this repository. If you intend to distribute or reuse the project, consider adding an appropriate license file.

---

*Built to explore interactive web design, scroll-driven motion, and animated IT service presentations.*
