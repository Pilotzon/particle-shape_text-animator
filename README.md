# Particle Engine

A high fidelity particle driven text animation system powered by **Three.js** and **GSAP**, featuring a full UI for customizing typography, particle behavior, and visual effects.

This project renders text as dynamic particle fields and includes an interactive control panel with sliders, toggles, and font selection options. It is built as a standalone HTML file requiring no backend.
> [!IMPORTANT]
> This is all in a standalone HTML file.

---

## Features

### • Real-time Particle Text Renderer
Transforms any text into thousands of animated particles rendered with WebGL.

### • Fully Interactive UI
Includes:
- Typeface picker (built-in fonts +custom font uploader)
- Controls for font size, density, and boldness
- Sliders for particle sizes
- Color picker
- Shape and dust particle customization
- Fullscreen toggle

### • Custom Font Support
Upload a `.ttf`, `.otf`, or `.woff` font directly from the settings panel and use it immediately.

> [!NOTE]
> You can write in any language that supports your font.

### • Responsive UI
Panels, inputs, and buttons include:
- Animated transitions  
- Dock menu for quick actions  

### • GPU Accelerated Rendering
Powered by Three.js for smooth, high-performance particle simulation.

---

## Technologies Used

- **Three.js** for rendering particle fields  
- **GSAP** for smooth animations  
- **Google Fonts API** for default fonts  
- **Pure CSS** for UI (custom sliders, custom selects, responsive layout)

---

## How to Use

1. Open the HTML file in any modern WebGL supported browser.  
2. Enter text in the input capsule at the bottom of the screen.  
3. Use the dock buttons to switch views or regenerate particles.  
4. Open the settings panel using the gear icon to:
   - Adjust text density  
   - Change particle sizes  
   - Pick a color  
   - Upload a custom font  
5. Press the fullscreen icon to hide the UI and view the effect cleanly. 
No additional folders or assets are required.

---

## Requirements

Your browser must support:
- WebGL  
- JavaScript ES6  
- CSS `backdrop-filter`  

A strong GPU is recommended for heavy particle settings.

---

## Customization

You can modify:
- Color palette (CSS variables in `:root`)  
- Default slider values  
- UI layout (inside the `<style>` block)  
- Particle logic (in the JS section at the bottom)

---

## License

Free for personal & commercial use!
