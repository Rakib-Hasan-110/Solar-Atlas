# Solar Atlas — Interactive 3D Solar System Experience

An immersive, scroll-driven journey through the Solar System.

**Solar Atlas** transforms a single 3D sphere into all eight planets as the user scrolls through the experience. Built with **Three.js**, **GSAP**, **ScrollTrigger**, and **Vanilla JavaScript**, the project combines interactive 3D rendering, smooth animations, planetary transitions, and storytelling into one continuous web experience.

## Live Demo: **solar-atlas-sb22.vercel.app**

## ✨ Features

- 🌍 Interactive 3D Solar System experience
- 🪐 Scroll-driven transformation between all eight planets
- 🌌 Animated 3D starfield background
- 🔄 Smooth planetary morphing and transitions
- 💫 Dynamic planet rotation and orbital moons
- 💍 Animated planetary rings for Saturn and Uranus
- 📜 GSAP-powered scroll animations
- 🎯 Interactive orbit navigation
- 🖱️ Custom animated cursor
- 🧲 Magnetic interactive buttons
- 📊 Planetary statistics and information
- 🌙 Horizontal scrolling moon gallery
- ⏳ Animated loading screen
- 📱 Responsive design for desktop and mobile
- ⚡ No frameworks or page reloads

## 🪐 Explore the Solar System

The experience takes users through all eight planets:

1. **Mercury** — Closest to the Sun
2. **Venus** — The hottest planet
3. **Earth** — Our home planet
4. **Mars** — The Red Planet
5. **Jupiter** — The largest planet
6. **Saturn** — The planet of rings
7. **Uranus** — The planet tilted on its side
8. **Neptune** — The distant blue world

The journey also includes a special **Field Notes** section featuring fascinating moons such as:

- Io
- Europa
- Titan
- Enceladus
- Triton
- Earth's Moon

## 🛠️ Technologies Used

### Frontend

- HTML5
- CSS3
- JavaScript (Vanilla JS)

### 3D & Animation

- **Three.js** — 3D rendering and scene creation
- **GSAP** — Animation engine
- **GSAP ScrollTrigger** — Scroll-based animations and interactions

### Design

- Responsive layout
- Custom cursor interaction
- Smooth scroll-driven storytelling
- Minimal space-inspired user interface
- Dynamic planetary color transitions

## 🎮 How It Works

The core concept of Solar Atlas is built around a **single 3D planet object**.

As the user scrolls through the page:

1. Scroll progress is detected using **GSAP ScrollTrigger**.
2. The current and next planets are calculated.
3. Planet properties are smoothly interpolated.
4. The 3D sphere changes its:
   - Color
   - Emissive lighting
   - Surface roughness
   - Metalness
   - Scale
   - Rotation speed
5. Planetary rings appear dynamically when required.
6. Moons are added or removed depending on the selected planet.
7. The user interface updates with the current planet and its information.

This creates one continuous transformation from **Mercury → Neptune** without page reloads or scene changes.

## 📂 Project Structure

```text
solar-atlas/
│
├── solar-atlas.html
└── README.md
```

The project is currently contained in a single HTML file that includes:

- HTML structure
- CSS styling
- Three.js scene setup
- GSAP animations
- ScrollTrigger interactions
- Planet data
- Interactive controls

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/solar-atlas.git
```

### 2. Open the project

Navigate to the project folder:

```bash
cd solar-atlas
```

### 3. Run the application

Open `solar-atlas.html` in your browser.

For the best experience, you can also run it using a local development server.

## 🌐 Running with Live Server

If you use VS Code:

1. Install the **Live Server** extension.
2. Open the project folder.
3. Right-click on `solar-atlas.html`.
4. Select **Open with Live Server**.

## 🎨 Key Interactions

### Scroll Journey

Scroll through the page to travel across the Solar System.

### Orbit Navigation

Use the navigation dots on the right side of the screen to quickly jump to a specific planet.

### Interactive Cursor

The project includes a custom animated cursor with hover effects.

### Magnetic Buttons

Interactive buttons respond dynamically to mouse movement.

### Restart Journey

At the end of the experience, users can restart the entire Solar System journey.

## 📸 Preview

> Add screenshots or a GIF of your project here.

```text
![Solar Atlas Preview](./assets/preview.png)
```

## 🔮 Future Improvements

Possible future enhancements include:

- High-resolution planetary textures
- Realistic surface maps
- Sound effects and ambient space audio
- More detailed moon information
- Interactive planet selection
- Mobile touch optimizations
- Performance optimization for lower-end devices
- Real-time astronomical data
- Dark/light theme variations
- VR or immersive mode

## 💡 Inspiration

Solar Atlas was created as an experimental project exploring the combination of:

- 3D web graphics
- Interactive storytelling
- Scroll-based animation
- Creative frontend development
- Scientific visualization

## 📄 License

This project is available for educational and personal use.

If you use or modify this project, please provide appropriate credit.

## 👨‍💻 Author

**Md. Rakib Hasan Rabbi**

Computer Science & Engineering Student  
Passionate about Web Development, Interactive Experiences, and Creative Technology.

---

⭐ If you like this project, consider giving the repository a star!

**Explore the universe. One scroll at a time.** 🌌

