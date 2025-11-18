# Web-sivuston kehittäminen - Syksy 2025

Tänne rakennan verkkosivuja osana Web-sivuston kehittäminen -opintojaksoa Laurea-ammattikorkeakoulussa syksyllä 2025.

## Kurssin yleiskatsaus

Kurssilla opitaan modernin web-kehityksen perusteet HTML:stä ja CSS:stä responsiiviseen suunnitteluun ja Bootstrap-frameworkiin. Kurssi sisältää seitsemän työpajaa ja lopuksi projektityön.

📌 **[Pääsivu ja navigaatio](index.html)** - Kurssin etusivu, josta pääset kaikkiin työpajoihin

---

# Työpajat (WS01–WS07)

Alla on listattu moduulien harjoitukset ja linkit kansioihin sekä tuntiharjoituksiin.

## WS01 – HTML Perusteet
**Aiheet:** Perus-HTML-rakenne, elementit, semanttinen HTML ja saavutettavuus

**Sisältö:**
- HTML-dokumentin rakenne (doctype, head, body)
- Otsikot, kappaleet, linkit ja kuvat
- Listat (järjestetyt ja järjestämättömät)
- Semanttiset elementit (header, nav, main, footer)

**Linkit:**
- 📁 [Kansion etusivu](WS01_HTML/index.html)
- 📝 [Tuntiharjoitus](WS01_HTML/tuntiharjoitus/index.html)

---

## WS02 – CSS Perusteet
**Aiheet:** Valitsimet, värit, typografia, box model ja perusasemointi

**Sisältö:**
- CSS-valitsimet (elementti, class, id)
- Värit ja typografia
- Box model (margin, padding, border)
- Ulkoinen tyylitiedosto (external CSS)

**Linkit:**
- 📁 [Kansion etusivu](WS02_CSS/index.html)
- 📝 [Tuntiharjoitus](WS02_CSS/tuntiharjoitus/index.html)

---

## WS03 – CSS Advanced
**Aiheet:** Pseudoluokat, animaatiot, transitions, muuttujat ja edistyneet tekniikat

**Sisältö:**
- Pseudoluokat (:hover, :active, :focus)
- Pseudo-elementit (::before, ::after)
- CSS-muuttujat (custom properties)
- Animaatiot ja siirtymät
- Liukuvärit (gradients)
- Kuvahaara (8 kuvaa)

**Linkit:**
- 📁 [Kansion etusivu](WS03_CSS_Advanced/index.html)
- 📝 [Tuntiharjoitus](WS03_CSS_Advanced/tuntiharjoitus/index.html)

---

## WS04 – Layout
**Aiheet:** Flexbox, CSS Grid ja modernit asettelutekniikat

**Sisältö:**
- Flexbox-perusteet ja käytännön esimerkit
- CSS Grid -järjestelmä
- Sivun kokonaisasettelu (header, sidebar, content, footer)
- Käytännön esimerkit: navigaatio, tuoteruudukko, kortit
- Flexbox vs Grid - milloin käyttää mitäkin

**Linkit:**
- 📁 [Kansion etusivu](WS04_Layout/index.html)
- 📝 [Tuntiharjoitus](WS04_Layout/tuntiharjoitus/index.html)
- 📖 [README](WS04_Layout/tuntiharjoitus/readme.md)

---

## WS05 – Responsiivisuus
**Aiheet:** Media queryt, mobiili-ensimmäinen suunnittelu ja skaalautuvuus

**Sisältö:**
- Media queryt ja breakpointit
- Mobile-first -lähestymistapa
- Responsiiviset kuvat ja typografia
- Viewport-asetukset
- Joustavat yksiköt (%, em, rem, vw, vh)

**Linkit:**
- 📁 [Kansion etusivu](WS05_Responsive/index.html)
- 📝 [Tuntiharjoitus](WS05_Responsive/tuntiharjoitus/index.html)

---

## WS06 – Bootstrap
**Aiheet:** Bootstrap-framework, komponentit ja grid-järjestelmä

**Sisältö:**
- Bootstrap 5 perusteet
- Grid-järjestelmä (12-saraketta)
- Komponentit: Navbar, Cards, Alerts, Badges, Buttons
- Lomakkeet (Forms)
- Accordion-komponentti
- Utility-luokat
- Bootstrap Icons

**Linkit:**
- 📁 [Kansion etusivu](WS06_Bootstrap/index.html)
- 📝 [Tuntiharjoitus](WS06_Bootstrap/tuntiharjoitus/index.html)
- 📖 [README](WS06_Bootstrap/tuntiharjoitus/readme.md)

---

## WS07 – Projektityö
**Aiheet:** Kurssin lopputyö, jossa yhdistetään kaikki opitut taidot

**Sisältö:**
- Oma web-projekti
- Kaikkien aiempien moduulien tekniikoiden soveltaminen
- HTML, CSS, responsiivisuus, layout-tekniikat
- Valinnainen Bootstrap-käyttö

**Linkit:**
- 📁 [Projektin etusivu](WS07_Projektityo/index.html)

---

## Repositorion rakenne

```
Websivuston_kehittaminen_Syksy_2025/
├── index.html                 # Pääsivu (kurssin etusivu)
├── readme.md                  # Tämä tiedosto
├── styles/                    # Pääsivun tyylit
│   └── style.css
├── WS01_HTML/                 # Moduuli 1
│   ├── index.html
│   ├── readme.md
│   ├── images/
│   ├── styles/
│   └── tuntiharjoitus/
│       └── readme.md
├── WS02_CSS/                  # Moduuli 2
│   ├── index.html
│   ├── readme.md
│   ├── images/
│   ├── styles/
│   └── tuntiharjoitus/
│       ├── index.html
│       └── styles/style.css
├── WS03_CSS_Advanced/         # Moduuli 3
│   ├── index.html
│   ├── readme.md
│   ├── images/
│   ├── styles/
│   └── tuntiharjoitus/
│       ├── index.html
│       └── styles/styles.css
├── WS04_Layout/               # Moduuli 4
│   ├── index.html
│   ├── readme.md
│   ├── images/
│   ├── styles/
│   └── tuntiharjoitus/
│       ├── index.html
│       ├── readme.md
│       └── styles/style.css
├── WS05_Responsive/           # Moduuli 5
│   ├── index.html
│   ├── readme.md
│   ├── images/
│   ├── styles/
│   └── tuntiharjoitus/
│       └── styles/
├── WS06_Bootstrap/            # Moduuli 6
│   ├── index.html
│   ├── readme.md
│   ├── images/
│   ├── styles/
│   └── tuntiharjoitus/
│       ├── index.html
│       └── readme.md
└── WS07_Projektityo/          # Moduuli 7
    ├── index.html
    ├── images/
    └── styles/
```

## Teknologiat ja työkalut

- **HTML5** - Semanttinen merkintäkieli
- **CSS3** - Tyylit, animaatiot, layout
- **Flexbox** - Yksiulotteiset asettelut
- **CSS Grid** - Kaksiulotteiset asettelut
- **Bootstrap 5** - CSS-framework
- **Git & GitHub** - Versionhallinta
- **VS Code** - Kehitysympäristö
- **GitHub Copilot** - AI-avustin

## Oppimistavoitteet

Kurssin päätyttyä opiskelija osaa:

✅ Rakentaa semanttisia HTML-rakenteita  
✅ Tyylittää verkkosivuja CSS:llä  
✅ Käyttää Flexboxia ja CSS Gridiä asettelussa  
✅ Luoda responsiivisia verkkosivuja  
✅ Hyödyntää Bootstrap-frameworkia  
✅ Soveltaa web-kehityksen parhaita käytäntöjä  
✅ Käyttää versionhallintaa (Git/GitHub)

## Linkit ja resurssit

### Projekti
- 🌐 [GitHub Repository](https://github.com/Laurea-ammattikorkeakoulu-Tikkurila/Websivuston_kehittaminen_Syksy_2025)
- 📄 [Pääsivun README](readme.md)

### Dokumentaatio
- [MDN Web Docs](https://developer.mozilla.org/)
- [CSS-Tricks](https://css-tricks.com/)
- [Bootstrap Documentation](https://getbootstrap.com/docs/)
- [Flexbox Froggy](https://flexboxfroggy.com/) - Interaktiivinen peli
- [Grid Garden](https://cssgridgarden.com/) - Interaktiivinen peli

---

**Laurea-ammattikorkeakoulu | Web-sivuston kehittäminen | Syksy 2025**  
Opettaja: Jari Kovis
