# 🌌 Solar System Simulation

An interactive 3D solar system simulation built with A-Frame (WebVR/WebXR). Explore space with realistic planetary motion, orbits, and textures in an immersive virtual reality experience that works directly in your web browser.

![Solar System](https://img.shields.io/badge/A--Frame-1.7.0-blue)
![License](https://img.shields.io/badge/license-MIT-green)

## 🌐 Live Demo

**[Visit the Solar System Simulation →](https://spacesimulation.vercel.app)**

Experience the simulation directly in your browser - no installation required!

## 🚀 Features

- **Realistic Celestial Bodies**: Sun, Earth, and Moon with authentic textures
- **Orbital Mechanics**: 
  - Earth revolves around the Sun (55-second orbital period)
  - Moon orbits the Earth (8.5-second orbital period)
  - All bodies rotate on their axes
- **Visual Effects**:
  - Animated floating "Sun" label
  - Dashed orbital path showing Earth's trajectory
  - Space-themed background
- **Interactive Controls**: First-person navigation with keyboard and mouse
- **VR Ready**: Compatible with WebVR/WebXR headsets

## 🎮 How to Navigate

### Simple Keyboard and Mouse actions:

| Control | Action |
|---------|--------|
| **↑** | Move forward |
| **←** | Move left |
| **↓** | Move backward |
| **→** | Move right |
| **Mouse** | Look around (click and drag) |

### Camera Settings

- **Starting Position**: (0, 3, 15) - positioned to view the entire solar system
- **Field of View**: 70°
- **Movement Speed**: Enhanced acceleration (120) for faster exploration

### Navigation Tips

1. **Getting Started**: The scene loads with an optimal view of the Sun and Earth's orbit
2. **Viewing the Sun**: Move backward (S key) for a better view of the massive Sun
3. **Following Earth**: Move closer (W key) and pan your view to track Earth's revolution
4. **Moon Observation**: Navigate near Earth to see the Moon's orbital motion
5. **Orbital Path**: The white dashed torus around the Sun shows Earth's complete orbital path
6. **Full Experience**: Fly around freely to observe the scene from different angles

## 🌐 Try It Now

**Live Demo:** https://spacesimulation.vercel.app

No installation needed - just open the link in your browser and start exploring!

## 📁 Project Structure

```
spacescene/
│
├── index.html         # Main HTML file with A-Frame scene
├── README.md          # This file
├── LICENSE            # MIT License
│
└── assets/            # Texture and image assets
    ├── background.png # Space background texture
    ├── earth.png      # Earth surface texture
    ├── moon.png       # Moon surface texture
    └── sun.png        # Sun surface texture
```

## Technical Details

### Technologies Used

- **A-Frame 1.7.0**: WebVR framework built on three.js
- **HTML5**: Structure and markup
- **WebGL**: 3D rendering

### Performance Optimizations

- Antialiasing: Disabled for better performance
- Precision: Medium (balanced quality/performance)
- Power Preference: High-performance mode

### Scene Specifications

| Object | Radius | Orbital Distance | Rotation Period | Revolution Period |
|--------|--------|-----------------|-----------------|-------------------|
| **Sun** | 5 units | - | 105 seconds | - |
| **Earth** | 1 unit | 24 units | 10 seconds | 55 seconds |
| **Moon** | 0.4 units | 2.5 units from Earth | 10 seconds | 8.5 seconds |

## 🌐 Browser Compatibility

- ✅ Chrome 79+
- ✅ Firefox 70+
- ✅ Edge 79+
- ✅ Safari 13+ (limited VR support)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 🥽 VR Support

This simulation supports WebXR-compatible VR headsets:

1. Connect your VR headset
2. Open the page in a WebXR-compatible browser
3. Click the VR goggles icon in the bottom-right corner
4. Use your headset's controllers to navigate

**Supported Devices**: Meta Quest, Apple Vision Pro, HTC Vive, Valve Index, Windows Mixed Reality

## 🎯 Future Enhancements

- Add more planets (Mars, Venus, Mercury, etc.)
- Implement realistic orbital speeds and scales
- Add planet information panels
- Include asteroid belt
- Add starfield background with parallax
- Sound effects and ambient space music
- Time controls (speed up/slow down)
- Toggle orbital paths on/off

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### ⭐ Star this repository if you found it interesting!