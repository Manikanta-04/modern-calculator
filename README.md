<div align="center">

<img src="https://img.shields.io/badge/Modern%20Calculator-Soft%20Brutalist%20UI-18181b?style=for-the-badge&logo=javascript&logoColor=F7DF1E" alt="Modern Calculator Banner"/>

# 🧮 Modern Calculator

### *Minimalist Soft-Brutalist Calculator — Keyboard Support, Smooth Animations & Zero Dependencies*

<br/>

[![Live Demo](https://img.shields.io/badge/🌐%20Live%20Demo-GitHub%20Pages-18181b?style=for-the-badge)](https://manikanta-04.github.io/modern-calculator/)

<br/>

[![HTML5](https://img.shields.io/badge/HTML5-Structure-E34F26?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-Animations-1572B6?style=flat-square&logo=css3)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/Vanilla%20JS-ES6+-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Zero Dependencies](https://img.shields.io/badge/Dependencies-Zero-brightgreen?style=flat-square)]()
[![Single File](https://img.shields.io/badge/Single%20HTML%20File-All--in--One-blueviolet?style=flat-square)]()
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=flat-square)](LICENSE)
![Version](https://img.shields.io/badge/version-1.0.0-blue?style=flat-square)

</div>

---

## 🚀 Live Demo

| Service | URL |
|---|---|
| 🌐 **Modern Calculator** | [manikanta-04.github.io/modern-calculator](https://manikanta-04.github.io/modern-calculator/) |

> ⚡ No install. No login. Open and calculate instantly.

---

## 🎥 Demo Video

> 📽️ *(Add a Loom / YouTube demo walkthrough here)*
>
> [![Watch Demo](https://img.shields.io/badge/▶%20Watch%20Demo-YouTube-red?style=for-the-badge&logo=youtube)](https://youtube.com)

---

## 🧠 Problem Statement

Most calculator implementations are either:

- 😐 Ugly default HTML forms with no design thinking
- 🐌 Over-engineered with React/Vue just for basic arithmetic
- 📵 No keyboard support — mouse-only interactions
- ❌ No error handling — division by zero breaks the app
- 🎨 No visual personality — generic gray buttons everywhere

**A calculator is used dozens of times a day — it deserves to look and feel great.**

---

## 💡 Solution

**Modern Calculator** is a single-file, soft-brutalist calculator built with pure HTML, CSS & JavaScript. Inspired by Apple Calculator and Google Calculator — featuring professional typography, smooth hover animations, full keyboard support, error handling, and a warm neutral palette. Zero dependencies. Instant load.

> *"Simple math. Beautiful design."*

---

## 🖼️ Screenshots

| Calculator — Default State | Error Handling |
|---|---|
| ![Calculator](screenshots/calculator.png) | ![Error](screenshots/error.png) |

| Mobile View | Keyboard Interaction |
|---|---|
| ![Mobile](screenshots/mobile.png) | ![Keyboard](screenshots/keyboard.png) |

> 📌 *(Replace with actual screenshots from your deployed app)*

---

## 🏗️ Architecture

```
┌──────────────────────────────────────────────────────────┐
│              SINGLE FILE APP — index.html                 │
│                                                           │
│  ┌──────────────────────────────────────────────────┐     │
│  │              CSS LAYER                            │     │
│  │  CSS Variables (color tokens) | CSS Grid layout  │     │
│  │  Soft shadows | Rounded corners | Hover lift      │     │
│  │  Smooth transitions | Responsive breakpoints      │     │
│  └──────────────────────────────────────────────────┘     │
│                                                           │
│  ┌──────────────────────────────────────────────────┐     │
│  │         JAVASCRIPT CALCULATOR ENGINE              │     │
│  │  state{}           → currentInput, operator,     │     │
│  │                       previousInput, result       │     │
│  │  appendNumber()    → build number string          │     │
│  │  appendDecimal()   → prevent duplicate dots       │     │
│  │  setOperator()     → store operator + prev input  │     │
│  │  calculate()       → evaluate expression          │     │
│  │  handleDivByZero() → show "Error" gracefully      │     │
│  │  deleteLast()      → slice(-1) on display         │     │
│  │  clearAll()        → reset full state             │     │
│  │  updateDisplay()   → write to DOM                 │     │
│  │  handleKeyboard()  → keydown → map to action      │     │
│  └──────────────────────────────────────────────────┘     │
│                                                           │
│  CDN: Google Fonts (DM Sans + JetBrains Mono)             │
└──────────────────────────────────────────────────────────┘
```

---

## ⚙️ Tech Stack

| Layer | Technology | Purpose |
|---|---|---|
| **Structure** | HTML5 | Semantic calculator markup |
| **Styling** | CSS3 Grid + Flexbox | Button grid, responsive layout |
| **Animations** | CSS Transitions | Hover lift, press feedback |
| **Logic** | Vanilla JavaScript ES6+ | State machine, calculation engine |
| **Fonts** | Google Fonts CDN | DM Sans (UI) + JetBrains Mono (display) |
| **Hosting** | GitHub Pages | Free static hosting |

> ⚡ **Zero local dependencies** — Google Fonts via CDN only.

---

## ✨ Features

### 🔢 Full Calculator Operations
| Button | Action |
|---|---|
| `0–9` | Append digit |
| `.` | Decimal point (duplicate prevention) |
| `+` `−` `×` `÷` | Set operator |
| `=` | Calculate result |
| `C` | Clear all (reset state) |
| `⌫` | Delete last digit |

### ⌨️ Full Keyboard Support
| Key | Action |
|---|---|
| `0–9` | Append digit |
| `+` `-` `*` `/` | Set operator |
| `.` | Decimal point |
| `Enter` or `=` | Calculate result |
| `Backspace` | Delete last digit |
| `Escape` or `Delete` | Clear all |

### 🛡️ Error Handling
- **Division by zero** → displays `"Error"` gracefully (no crash)
- **Empty input** → prevented before calculation
- **Duplicate decimal** → second `.` ignored
- **Invalid state** → auto-reset on next input after error

### 🎨 Soft Brutalist Design
- Warm neutral palette (off-white, grays, near-black)
- Soft layered `box-shadow` for depth
- Rounded corners (8–16px)
- `JetBrains Mono` on display — monospace for clean number alignment
- `DM Sans` on buttons — modern, legible
- Inspired by **Apple Calculator** and **Google Calculator**

### 📱 Fully Responsive
- Works at 320px (smallest phones) up to 1920px (desktop)
- CSS Grid button layout adapts naturally
- Touch-friendly tap targets

### ♿ Accessibility
- Full keyboard navigation
- `focus-visible` outlines for keyboard users
- Semantic HTML button elements
- High contrast text/background ratio

---

## 📊 System Design

```
Calculator State Machine:

State = {
  currentInput:  "0",       // what's on display
  previousInput: "",        // stored before operator
  operator:      null,      // +, -, *, /
  justCalculated: false     // prevents chaining bugs
}
```

```
Calculation Flow:

[User presses number]
         │
         ▼
appendNumber() → currentInput += digit → updateDisplay()

[User presses operator]
         │
         ▼
setOperator() → previousInput = currentInput
             → operator = symbol
             → currentInput = ""

[User presses =]
         │
         ▼
calculate()
  → parse previousInput + currentInput as floats
  → switch(operator):
      "+" → a + b
      "-" → a - b
      "*" → a * b
      "/" → b === 0 ? "Error" : a / b
         │
         ▼
updateDisplay(result)
```

```
Keyboard Handler:

[keydown event fires]
         │
         ▼
switch(event.key):
  "0"-"9"     → appendNumber(key)
  "."         → appendDecimal()
  "+""-""*""/"→ setOperator(key)
  "Enter","=" → calculate()
  "Backspace" → deleteLast()
  "Escape","Delete" → clearAll()
```

---

## 🔄 Workflow

```
1. User opens calculator         →  State resets to default "0"
2. User clicks / types number    →  Display updates in real time
3. User clicks / types operator  →  Operator stored, display cleared
4. User enters second number     →  New input builds on display
5. User presses = / Enter        →  Result calculated + displayed
6. User presses C / Escape       →  Full state reset to "0"
7. User presses ⌫ / Backspace    →  Last digit removed from display
8. Division by zero attempted    →  "Error" shown, next input resets
```

---

## 📈 Performance & Metrics

| Metric | Value |
|---|---|
| Total files | 1 (single `index.html`) |
| External CDN | 1 (Google Fonts) |
| Keyboard shortcuts | 10 mapped keys |
| Error cases handled | 4 (div/zero, empty, duplicate dot, invalid) |
| Responsive breakpoints | 320px, 768px, 1024px, 1920px |
| Build step | None |
| Framework | None |
| Time to load | < 500ms |

---

## 🧪 Testing

```bash
# Open directly in browser
open index.html

# Or serve locally
npx serve .
# Visit: http://localhost:3000

# Manual test checklist:
# ✅ Click numbers 0–9 → display updates
# ✅ Click + - × ÷ → operator stored correctly
# ✅ Click = → correct result shown
# ✅ Click C → display resets to "0"
# ✅ Click ⌫ → last digit removed
# ✅ Type on keyboard → same as clicking buttons
# ✅ Enter / = → calculates result
# ✅ Backspace → deletes last digit
# ✅ Escape → clears display
# ✅ 5 ÷ 0 = → shows "Error" (no crash)
# ✅ 1.5.5 → second dot ignored
# ✅ Mobile (375px) → buttons fully clickable
# ✅ Works on Chrome, Firefox, Safari, Edge
```

### Browser Compatibility

| Browser | Version | Support |
|---|---|---|
| Chrome | 90+ | ✅ Full |
| Firefox | 88+ | ✅ Full |
| Safari | 14+ | ✅ Full |
| Edge | 90+ | ✅ Full |
| Opera | 76+ | ✅ Full |
| Mobile Chrome | Any | ✅ Full |

---

## 📁 Project Structure

```
modern-calculator/
│
├── index.html      # Entire app — HTML + CSS + JS (all-in-one)
├── README.md       # Project documentation
├── LICENSE         # MIT License
└── .gitignore      # Git ignore
```

> Everything — state machine, keyboard handler, error handling, animations — in **one self-contained `index.html`.**

---

## 🎨 Design System

| Token | Hex | Usage |
|---|---|---|
| Background | `#fafaf9` | Page background (warm off-white) |
| Surface | `#ffffff` | Calculator body |
| Primary Text | `#18181b` | Main display text |
| Secondary Text | `#52525b` | Button labels |
| Border | `#e7e5e4` | Subtle dividers |
| Error | `#dc2626` | Error state + Clear button |
| Operator Buttons | `#27272a` | Dark operator keys |
| Display Font | JetBrains Mono | Numbers (monospace alignment) |
| UI Font | DM Sans | Buttons + labels |

---

## 🔧 Customisation

### Change Color Palette
```css
:root {
    --color-bg: #fafaf9;
    --color-primary: #18181b;
    --color-error: #dc2626;
    /* modify any token here */
}
```

### Change Fonts
```html
<!-- Replace in <head> -->
<link href="https://fonts.googleapis.com/css2?family=YourFont&display=swap" rel="stylesheet">
```

---

## 🔐 Security

- **No user data stored** — stateless, no localStorage, no backend
- **No eval()** — arithmetic computed via explicit `switch` cases, not string evaluation
- **No external scripts** — zero CDN attack surface (fonts only)
- **GitHub Pages HTTPS** — all traffic over SSL

---

## ⚙️ Local Development Setup

### Prerequisites
- Any modern browser — no Node.js required

### 1️⃣ Clone

```bash
git clone https://github.com/Manikanta-04/modern-calculator.git
cd modern-calculator
```

### 2️⃣ Open

```bash
open index.html
# or
npx serve .
```

---

## 🔑 Environment Variables

No environment variables required — fully static app.

---

## 🚀 Deployment

### GitHub Pages
1. Push `index.html` to `main` branch
2. **Settings → Pages** → Source: `main` → `/ (root)`
3. Live at: `https://manikanta-04.github.io/modern-calculator/`

### Vercel / Netlify
| Setting | Value |
|---|---|
| Framework | Other / Static |
| Build Command | *(leave empty)* |
| Output Directory | `./` |

---

## 🔮 Future Improvements

- [ ] 🌙 Dark mode toggle
- [ ] 🔬 Scientific mode (sin, cos, tan, √, ^)
- [ ] 💾 Memory functions (M+, M−, MR, MC)
- [ ] 📜 Calculation history log
- [ ] ± Plus/minus toggle
- [ ] % Percentage button
- [ ] 🎨 Multiple theme presets
- [ ] 🔊 Optional key-press sound effects
- [ ] 📤 Export calculation history as CSV

---

## 🤝 Contributing

Contributions welcome!

```bash
git checkout -b feature/your-feature-name
git commit -m "feat: describe your change"
git push origin feature/your-feature-name
# Open a Pull Request
```

---

## 👨‍💻 Author

**Manikanta Naripeddi** — Full Stack & Creative Developer

[![GitHub](https://img.shields.io/badge/GitHub-Manikanta--04-181717?style=flat-square&logo=github)](https://github.com/Manikanta-04)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Manikanta%20Naripeddi-0077b5?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/manikanta-naripeddi-4326232a5/)

---

## 📜 License

Licensed under the **MIT License** — modify, distribute, use freely. See [LICENSE](LICENSE).

---

## 🙌 Acknowledgements

- Inspired by [Apple Calculator](https://apps.apple.com/app/calculator/id1069511488) and [Google Calculator](https://google.com/search?q=calculator)
- [Google Fonts](https://fonts.google.com/) — DM Sans + JetBrains Mono
- [GitHub Pages](https://pages.github.com/) — Free static hosting

---

<div align="center">

**Built with ❤️ for anyone who needs math done beautifully**

⭐ **Star this repo** if Modern Calculator impressed you!

[![GitHub Stars](https://img.shields.io/github/stars/Manikanta-04/modern-calculator?style=social)](https://github.com/Manikanta-04/modern-calculator)

---

*🧮 Simple math. Beautiful design.*

</div>
