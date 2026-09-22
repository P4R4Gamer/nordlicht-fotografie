# Nordlicht Fotografie

Responsive One-Page-Website für ein fiktives Fotografie-Studio. Umgesetzt mit
reinem HTML, CSS und Vanilla JavaScript — bewusst ohne Framework oder Build-Step,
um zu zeigen, dass es sauberes, wartbares Frontend auch ohne Tooling-Overhead gibt.

## Features

- Sticky Header mit Scroll-Verhalten (transparent → solide beim Scrollen)
- Mobile Navigation mit Hamburger-Menü
- Filterbare Portfolio-Galerie inkl. Lightbox
- Scroll-Reveal-Animationen über `IntersectionObserver`
- Kontaktformular mit clientseitiger Validierung
- Vollständig responsive (Desktop bis Mobile), kein CSS-Framework

## Stack

- HTML5, CSS3 (Custom Properties, Grid & Flexbox)
- Vanilla JavaScript (ES6+, keine Dependencies)
- Google Fonts (Cormorant Garamond, Jost)

## Struktur

```
nordlicht-fotografie/
├── index.html
├── css/
│   └── style.css
├── js/
│   └── main.js
└── README.md
```

## Lokal starten

Kein Build nötig — einfach `index.html` im Browser öffnen, oder z. B. mit dem
VS-Code-Plugin "Live Server" für automatisches Neuladen.

```bash
npx serve .
```

## Hinweis

Die Bilder sind Platzhalter (picsum.photos), Studio, Name und Kundenstimmen sind
frei erfunden — das Projekt dient als Code-Beispiel, nicht als echte Website.
