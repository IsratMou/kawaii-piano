# 🎹 Kawaii Piano ✨

> A cute, interactive browser-based piano you can play with your keyboard!

![License](https://img.shields.io/badge/license-MIT-pink?style=flat-square)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white&style=flat-square)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white&style=flat-square)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black&style=flat-square)

---

## 🌸 Overview

**Kawaii Piano** is a fully client-side interactive piano built with vanilla HTML, CSS, and JavaScript. It uses the Web Audio API to synthesize sounds in real-time — no external audio files required! The design features a soft pastel aesthetic with floating animations, sparkle effects, and bouncy key interactions.

---

## 🎵 Features

- 🎹 **Real-time synthesis** — Powered by the Web Audio API (no external assets)
- ⌨️ **Keyboard controls** — Play using your computer keyboard
- 🎛️ **4 waveforms** — Piano (Triangle), Soft (Sine), 8-bit (Square), Bright (Sawtooth)
- 🎚️ **Octave shifting** — Shift up/down across 7 octaves
- 🔊 **Volume control** — Adjustable master gain
- 💖 **Kawaii UI** — Pastel gradients, floating decorations, sparkle particles
- 📱 **Responsive** — Adapts to smaller screens
- ✨ **Visual feedback** — Keys animate with hearts and sparkles on press

---

## 🚀 Getting Started

### Option 1: Open directly
Simply double-click `kawaii_piano.html` to open it in your browser.

> ⚠️ **Note:** Some browsers require user interaction before audio can play. Click anywhere on the page if sound doesn't start immediately.

### Option 2: Local server (recommended)
```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve .

# Then open http://localhost:8000/kawaii_piano.html
```

---

## 🎮 Controls

### White Keys
| Key | Note |
|:---:|:----:|
| `A` | C |
| `S` | D |
| `D` | E |
| `F` | F |
| `G` | G |
| `H` | A |
| `J` | B |
| `K` | C (next octave) |
| `L` | D (next octave) |
| `;` | E (next octave) |
| `'` | F (next octave) |

### Black Keys
| Key | Note |
|:---:|:----:|
| `W` | C# |
| `E` | D# |
| `T` | F# |
| `Y` | G# |
| `U` | A# |
| `O` | C# (next octave) |
| `P` | D# (next octave) |

### Global
| Key | Action |
|:---:|:-------|
| `Z` | Shift octave down |
| `X` | Shift octave up |
| `Mouse` | Click keys to play |

---

## 🛠️ Tech Stack

- **HTML5** — Semantic structure
- **CSS3** — Custom properties, animations, backdrop-filter, gradients
- **Vanilla JavaScript** — Web Audio API, event handling, DOM manipulation
- **Google Fonts** — Fredoka & Nunito

---

## 📁 File Structure

```
.
├── kawaii_piano.html    # Main application (single file)
└── README.md            # This file
```

> The entire app is contained in a single HTML file for maximum portability!

---

## 🎨 Customization

### Change the color theme
Edit the CSS variables in the `<style>` section:
```css
/* Main accent color */
color: #ff8fab;

/* Background gradient */
background: linear-gradient(180deg, #ffeef8 0%, ...);
```

### Add more octaves
Modify the `whiteNotes` and `blackNotes` arrays in the JavaScript to extend the key range.

### Change sound character
Switch between waveforms:
- `triangle` — Soft, piano-like (default)
- `sine` — Pure, flute-like
- `square` — Retro 8-bit / chiptune
- `sawtooth` — Bright, brassy

---

## 🌟 Browser Support

| Browser | Support |
|:-------:|:-------:|
| Chrome | ✅ |
| Firefox | ✅ |
| Safari | ✅ |
| Edge | ✅ |

> Requires a modern browser with Web Audio API support.

---

## 📜 License

MIT License — feel free to use, modify, and share! 💕

---

<p align="center">
  Made with 💖 and lots of pastel colors
</p>
