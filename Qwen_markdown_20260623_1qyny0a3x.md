# 🦷 Lumière Dental — Premium Dentist Website

A clean, responsive, single-file dentist website built with **HTML + Tailwind CSS**.  
No build step. No React. No terminal. Just open and deploy.

![Preview](https://img.shields.io/badge/status-live-success)
![Tailwind](https://img.shields.io/badge/Tailwind-CSS-38bdf8)

---

## ✨ Features

- ✅ Fully responsive (mobile, tablet, desktop)
- ✅ Hero section with stats
- ✅ Services grid (6 services)
- ✅ Patient reviews / testimonials
- ✅ Google Maps embed
- ✅ Floating WhatsApp button (with pulse animation)
- ✅ Appointment form → sends data directly to WhatsApp
- ✅ Premium design with smooth animations
- ✅ Zero build step — pure HTML + Tailwind CDN

---

## 🛠️ How to Customize

**All content is in ONE place** — open `index.html` and edit the `CONTENT` object at the top of the `<script>` tag:

```js
const CONTENT = {
  brand: { name: "Your Clinic", phone: "...", ... },
  services: [ ... ],
  reviews: [ ... ],
  whatsapp: { number: "919999999999", ... },
  // ... etc
};