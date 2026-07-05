# PrincessGlass ✨

Community-maintained adaptation of the **Glass** KWin effect for **KDE Plasma 6.3.6**.

PrincessGlass preserves the original visual style while restoring compatibility with modern Plasma releases and providing an easy installation experience for Linux users.

---

<p align="center">
  <img src="docs/demo.gif" alt="PrincessGlass Demo" width="100%">
</p>

---

# Features

- ✨ Glass-like window decorations
- 🌫 Improved blur effect
- ⭕ Rounded corners
- 🪟 Native Wayland support
- 🎨 Adjustable blur intensity
- 💜 Tint and glow customization
- 🔧 Plasma 6.3.6 compatibility fixes
- 🚀 Community maintenance

---

# Project Goal

PrincessGlass is **not a new window effect**.

Its purpose is to preserve and maintain the original Glass effect for modern KDE Plasma versions while making installation and future maintenance easier for the community.

---

# Tech Stack

- C++
- Qt
- KWin
- KDE Plasma
- Wayland

---

# Architecture

```
KDE Plasma
      │
      ▼
KWin
      │
      ▼
PrincessGlass
      │
      ▼
Blur Pipeline
      │
      ▼
Window Rendering
```

---

# Compatibility

| Plasma Version | Status |
|----------------|--------|
| 6.3.6 | ✅ Supported |
| 6.4.x | 🚧 Planned |
| Future releases | 🚧 Community maintained |

---

# Installation

```bash
git clone https://github.com/princessnvidia/PrincessGlass.git
cd PrincessGlass
```

Follow the standard KWin effect installation procedure for your Plasma version.

---

# Roadmap

## Maintenance

- [x] Plasma 6.3.6 support
- [ ] Plasma 6.4 compatibility
- [ ] Future Plasma releases

## Improvements

- [ ] Better blur quality
- [ ] Performance optimizations
- [ ] Additional customization
- [ ] Easier installation

---

# Credits

PrincessGlass is based on the original **Glass** KWin effect created by its original authors.

Original project:

https://github.com/4v3ngR/kwin-effects-glass

This repository focuses on maintaining compatibility with recent KDE Plasma releases while respecting the original project and its license.

---

# Status

🚧 Community Maintenance Project

---

# License

Same license as the original Glass project.
