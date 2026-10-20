# KartDash 🏎️ — Live Timing PWA para Karting Campillos

App web progresiva (PWA) diseñada para pilotos de karting en pista.  
Se conecta en tiempo real al live timing de **Apex Timing** del circuito Karting Campillos.

## 🚀 Demo
Abre `index.html` con un servidor local o despliega en Netlify/GitHub Pages.

## 📱 Características
- **Dashboard de piloto**: posición en grande, última vuelta, mejor vuelta, gaps delante/detrás, sectores S1/S2/S3
- **Leaderboard**: clasificación completa con tu kart resaltado en dorado
- **Historial de vueltas**: tus últimas 50 vueltas con sectores y mejor tiempo marcado
- **PWA instalable**: Wake Lock, modo fullscreen, Service Worker offline
- **Conexión en tiempo real**: polling HTTP a `live-data.apex-timing.com` cada ~1s

## 🔧 Stack
- HTML + CSS + JavaScript vanilla (sin dependencias, sin bundler)
- Tailwind-inspired CSS custom properties
- PWA: Web App Manifest + Service Worker

## ▶️ Uso Local
```bash
python -m http.server 8080
# Luego abre http://localhost:8080
```

## 🌐 Live Timing
Circuito: [Karting Campillos (Apex Timing)](https://www.apex-timing.com/live-timing/kartcenter-campillos/)
