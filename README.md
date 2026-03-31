# CSS-Only Calculator — 0% JavaScript, 100% CSS Logic

A fully functional calculator built with **pure CSS** —  
no JavaScript, no hacks, just variables, container queries, and a lot of questionable decisions.

This repo includes **multiple prototypes**, including early experimental versions that show how the logic evolved.

👉 **Live demo + all versions are available below.**  
👉 **If you're into weird CSS experiments, this is one worth starring.**

---

## 🚀 Live Demos

- **Latest version:** https://codepen.io/cascade-path/full/WbGzwdG  
- **First prototype (v1):** https://codepen.io/cascade-path/full/myrxBEo  

More versions are included in this repo.

---

## 🧠 How It Works (High-Level)

This calculator performs arithmetic operations using only CSS:

- Numbers stored in CSS variables (`--ax`, `--ay`, etc.)
- Arithmetic done via `calc()` inside layout rules
- Container queries “decode” the numeric result into text
- UI state handled with `:has()` and radio inputs
- No JavaScript. No custom properties trickery. Just CSS doing crimes.

---

## ✨ Features

- Pure CSS logic (0% JS)
- Supports **+, -, ×, ÷**
- Dynamic UI powered by `:has()`
- Result decoding via container queries
- Multiple versions included (prototype → latest)

---

## 🧪 Versions Included

### **v1 — First Prototype**
- Uses container width as the “numeric value”
- Result decoded entirely through `@container` rules
- Simple, cursed, and surprisingly stable

### **v2 — Current Version**
- Cleaner UI
- More readable output
- More expressive CSS logic
- Better separation of concerns

### **Experimental Builds**
These are included in the repo and show how the logic evolved.  
Some are broken, some are cursed, all are fun.

---

## 🖼️ Screenshots

[calculator](calc.gif)

---

## ❗ Browser Support

- Chrome ✔  
- Firefox ✔  
- Safari / iOS ❌ (container queries + `attr()` limitations)

---

## 📄 License

MIT License
