# My Resume — Digitale CV van Hans Molenaar

Een moderne, tweetalige (NL/EN) digitale resume met live GitHub data, gebouwd als statische site.

## 🎥 Gource Visualization

De ontwikkelhistorie van dit project in een film:

<video src="https://raw.githubusercontent.com/hmol33/my-resume/main/gource.mp4" controls width="100%"></video>

*De video wordt automatisch gegenereerd door de [Gource workflow](.github/workflows/gource.yml) bij elke push.*

## 🚀 Live Site

**https://hmol33.github.io/my-resume/**

## ✨ Features

- **Tweetalig** (NL/EN) met automatische browser-taaldetectie
- **Live GitHub data** — projecten, skills, contributions (dagelijks geüpdatet)
- **Donut chart** met taalverdeling
- **Geanimeerde tijdlijn** voor werkervaring
- **Contact formulier** (mailto)
- **Download als JSON** voor ATS-systemen
- **Share knoppen** voor LinkedIn, Twitter, WhatsApp
- **Print-friendly** versie
- **Dark/Light/Auto** thema
- **Open Graph** meta-tags voor social media
- **PWA** manifest + favicons

## 🛠️ Tech Stack

- HTML5 + CSS3 + JavaScript (geen frameworks)
- GitHub Actions voor automatische data-updates
- GitHub Pages voor hosting
- Gource voor visualisatie

## 📁 Structuur

```
├── index.html              # Hoofdpagina
├── github-data.json        # Live GitHub data (automatisch gegenereerd)
├── profile-data.json       # Handmatige profiel data (THM, HTB, CyLab)
├── profile.jpg            # Profielfoto
├── favicon-*.png          # Favicons
├── site.webmanifest       # PWA manifest
├── scripts/
│   └── fetch_github_data.py  # Script om GitHub data op te halen
└── .github/workflows/
    ├── update-data.yml    # Dagelijkse data-update workflow
    └── gource.yml        # Gource visualisatie workflow
```

## 🔄 Automatische Updates

De GitHub data wordt dagelijks om 06:00 UTC automatisch bijgewerkt door de `update-data.yml` workflow. De Gource video wordt bij elke push ververst.

## 📝 License

© 2026 Hans Molenaar
