# Toddler Typing Game

A cheerful, open-source, single-file web typing game for toddlers (ages 2–7) to help learn the alphabet and numbers!  
**Big, colorful visuals. Friendly voice audio.**  
Designed for touchscreens and keyboards, desktop or mobile.  
No setup—just open the HTML file in any modern browser.

---

## Features

- **Type any letter (A–Z) or number (0–9):**
  - A cute OpenMoji animal/object image is shown.
  - A clear child-friendly voice says “A for apple”, “B for bear”, etc.
  - Progress is visualized with big colored dots.
  - Fun confetti and a “Play again!” button when all 36 keys are found.
- **Kid-friendly design:**
  - Large buttons and text, pastel backgrounds, clouds, and playful confetti.
  - Baloo 2/Comic Sans font for easy readability.
  - Accessible: keyboard/touch friendly, WCAG AA color contrast, ARIA labels.
- **No tracking, ads, or internet required** (images hotlinked by default, but can be downloaded for offline use).
- **Open-source:** MIT License.

---

## Usage

1. **Download or copy the HTML file**  
   (You can use the full code provided in this ChatGPT answer.)

2. **Open in any modern browser.**  
   - Works on Chrome, Firefox, Safari, Edge, mobile and desktop.

3. **Start typing!**  
   - Try pressing keys on your keyboard, or tap keys if using an on-screen keyboard.

---

## Customization

- **Replace Images:**  
  - Images use [OpenMoji](https://openmoji.org) SVGs (hotlinked).
  - You may download SVGs from OpenMoji or use your own PNGs/SVGs by updating the `alphabetMap` in the JavaScript.

- **Change Words or Speech:**  
  - Change the `word` and `audioText` fields for any letter in the `alphabetMap` object.

- **Replace Sounds:**  
  - The game uses a bundled short click sound and a ding for numbers.
  - To use your own, update the `<audio>` tag sources with your own .mp3 or .wav files (inline or linked).

---

## Accessibility

- Color contrast passes WCAG AA.
- Keyboard and screen-reader friendly (ARIA labels, live regions, tab order).
- Extra-large interactive areas for little hands.

---

## License & Credits

- **Code:** MIT License – Use, modify, and share freely.
- **Images:**  
  - OpenMoji artwork [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) – please attribute “OpenMoji” if you distribute or modify.
- **Font:**  
  - [Baloo 2](https://fonts.google.com/specimen/Baloo+2) (OFL) or Comic Sans MS.
- **Sound:**  
  - Example sound from Pixabay Audio (“click.mp3”, “ding.mp3”) – replace as needed.

---

## Attributions

- Emoji & SVG graphics: [OpenMoji – the open-source emoji and icon project](https://openmoji.org), License: CC BY-SA 4.0.
- Example sound: [Pixabay Audio](https://pixabay.com/sound-effects/).

---

_Enjoy learning and playing!_
