# Al-Burhan Quran Scholar — Landing Page

The official marketing & download landing page for the **Al-Burhan Quran Scholar** Android application.

> Deep Quranic Research, Classical Tafsirs, and Multidimensional Empirical Insights.

## About the app

Al-Burhan Quran Scholar is a scholarly Android companion that unifies:

- **Four-Layer Analysis** — linguistic roots, classical tafsirs (Al-Razi, Ibn Kathir, Al-Qurtubi), cosmic/biological empirical reflections, and practical spiritual takeaways.
- **Roman Urdu & Multilingual Support** — natural translations into Roman Urdu and English.
- **OpenRouter AI & Gemini Integration** — deep thematic exploration and smart parsing.
- **Secure Local Database** — offline-first architecture with encrypted local storage.
- **Student Mode** *(new in v1.1)* — guided lessons, progress tracking, quizzes, and a personal study journal.
- **Noorani Qaida** *(new in v1.1)* — the classic beginner primer, digitized with audio recitation and Tajweed rules.
- **Qibla Direction** *(new in v1.1)* — real-time compass to the Kaaba from anywhere in the world.

**Founder & Creator:** Hamza Ahmed
**Instagram:** [hamza_ahmed_0fficial](https://www.instagram.com/hamza_ahmed_0fficial)
**LinkedIn:** [Hamza Ahmed](https://www.linkedin.com/in/hamza-ahmed-917a17224)

## Stack

- Pure HTML, Tailwind CSS (CDN), vanilla JavaScript
- Lucide icons (CDN)
- Inter + Plus Jakarta Sans + Amiri (Arabic) from Google Fonts
- Zero build step

## File structure

```
.
├── index.html              # The entire landing page
├── vercel.json             # Vercel routing + APK content-type headers
├── .gitignore
├── Al-Burhan 1.0.apk       # Signed Android APK (downloadable from the site)
└── README.md
```

## Local development

Open `index.html` directly in a browser, or serve the directory:

```bash
python -m http.server 8000
# then visit http://localhost:8000
```

## Deploy to Vercel

The repo is pre-configured. From the Vercel dashboard:

1. Click **Add New → Project**
2. Import this GitHub repository
3. Framework preset: **Other** (no framework)
4. Click **Deploy**

That's it. Vercel auto-detects `index.html` as the entry, and `vercel.json` ensures the APK downloads with the correct `application/vnd.android.package-archive` MIME type.

## APK hosting note

The APK is currently committed to this repository for a self-contained first deploy. If the file grows or you cut frequent releases, migrate to **GitHub Releases** and update the download link in `index.html`:

```html
<a href="https://github.com/HamzaAhmedAI/al-burhan-quran-scholar/releases/latest/download/Al-Burhan-1.0.apk" download>
```

## License

© 2026 Al-Burhan Quran Scholar. All rights reserved. Built with passion by Hamza Ahmed.
