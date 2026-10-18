# Exclusive Grandhill Residence

A digital monograph and interactive showcase for Exclusive Grandhill Residence, an elevated residential development featuring contemporary architecture, panoramic hilltop vistas, and bespoke residential design.

---

## Overview

This project delivers a high-performance, editorial-grade web experience with zero framework overhead. It incorporates scroll-driven lighting choreography, a WebGL 3D architectural gallery, and responsive layout systems designed for luxury real estate presentations.

---

## Key Features

- **Hero Atmospheric Transition**: Scroll-synchronized dusk-to-night lighting crossfade showcasing the architectural facade under varying daylight conditions.
- **Interactive 3D Perspective Experience**: Built with Three.js, rendering a helical 3D stage of curated interior perspectives with camera path tracking and direct slide controls.
- **Curated Interior & Amenity Journeys**: Layered sticky photobands and synchronized architectural captions with high-resolution modal inspection.
- **Architectural Floor Plan Explorer**: Interactive suite layout viewer featuring detailed spatial specifications, area metrics, and noble finish schedules.
- **Motion & Accessibility**: Integrated motion toggle honoring `prefers-reduced-motion` settings, keyboard navigation, and semantic HTML5 hierarchy.

---

## Technology Stack

- **Markup & Styling**: HTML5, Vanilla CSS3 (Custom Design System, CSS Variables, Clamp Typography)
- **Logic & 3D Graphics**: Modern JavaScript (ES Modules), Three.js (r160), GSAP, ScrollTrigger
- **Asset Pipeline**: WebP image delivery, SVG vector marks, self-hosted web fonts
- **Runtime**: Native Node.js HTTP server (no build step or bundler required)

---

## Project Structure

```text
├── assets/
│   ├── acervo/          # High-resolution architectural photography
│   ├── crystal/         # Textures and backdrop assets
│   ├── images/          # Facade and hero imagery (sunset & night)
│   └── fonts/           # Typography assets
├── vendor/
│   ├── gsap.min.js
│   ├── ScrollTrigger.min.js
│   └── three.module.min.js
├── grandhill.css        # Core stylesheet and layout tokens
├── grandhill-cinema.js  # WebGL 3D helix gallery controller
├── grandhill-essence.js # Spatial feature tabs controller
├── grandhill.js         # Navigation, lightbox, and global interactions
├── index.html           # Main semantic document
├── server.js            # Zero-dependency local development server
└── vercel.json          # Deployment configuration for Vercel
```

---

## Getting Started

### Prerequisites

- Node.js 18.0.0 or higher

### Installation & Local Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/exclusive-grandhill-residence.git
   cd exclusive-grandhill-residence
   ```

2. Start the local development server:
   ```bash
   npm start
   ```

3. Open your browser and navigate to:
   ```text
   http://localhost:3000
   ```

---

## Deployment

The project is structured as a static deployment. Configuration for Vercel is included in `vercel.json` with appropriate MIME types and cache headers.

To deploy via Vercel CLI:
```bash
vercel
```

Or connect the GitHub repository directly to Vercel for automatic deployment on push.

---

## License

Private portfolio demonstration. All architectural renderings, photography, and design concepts are presented for demonstration and development purposes.
