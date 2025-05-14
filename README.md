# 🌱 Carbon Offset Calculator (SPA + PWA)

## 📘 Project Brief

Create a **Single Page Application (SPA)** that estimates a user’s carbon footprint based on travel and energy use, and calculates how many trees are needed to offset it. The app must also be a fully functional **Progressive Web App (PWA)** — installable, offline-ready, and mobile-friendly.

---

## ✅ Requirements

### Core Features
- **Form Inputs**:
  - Mode of transport: Car, Plane, Train
  - Distance traveled (in kilometers or miles)
  - Monthly electricity usage (in kWh)

- **Results Display**:
  - Total estimated carbon emissions (in kg CO₂)
  - Number of trees required to offset that amount annually

- **UI/UX**:
  - Responsive, mobile-first layout
  - Real-time or triggered result display

### Technical Requirements
- Built as a **SPA** using your preferred stack (e.g. Vanilla JS / React / Vue / Svelte)
- Implement as a **PWA**:
  - Web app manifest
  - Service worker with offline support
  - Installable on devices
- Store user input or calculation history using `localStorage` or `IndexedDB`

---

## 🌟 Bonus Features (Optional)
- Dark mode toggle
- Save and view past calculations
- Basic animation/transition for result reveal
- Deploy the app publicly (e.g. Netlify, Vercel, or GitHub Pages)

---

## 🧪 Evaluation Criteria

| Category          | What We Look For                                                    |
|-------------------|-------------------------------------------------------------------------|
| Functionality     | Core features work correctly, accurate calculations                     |
| Code Quality      | Clean, modular, readable code                                           |
| PWA Compliance    | Installable, works offline, includes manifest and service worker        |
| UX/UI             | Intuitive layout, responsiveness, clear user feedback                   |
| Git Hygiene       | Clear commit messages, organized commit history                         |
| Documentation     | README file with clear setup and instructions                           |

---


## 📊 Sample Emission Factors

| Mode of Transport | Emissions (per km) |
|-------------------|--------------------|
| Car               | 0.21 kg CO₂        |
| Plane             | 0.15 kg CO₂        |
| Train             | 0.05 kg CO₂        |

**Tree Offset Assumption:** One mature tree absorbs ~21 kg CO₂ per year.

---

## 📤 Submission Guidelines
- Fork this repository.
- Complete the task in your fork.
- Submit your solution by:
  - Opening a pull request
- Complete within 24 hours
