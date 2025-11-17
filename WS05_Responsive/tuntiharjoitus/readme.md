# WS05 - Responsive Design Workshop

## Kuvaus

Tämä on kattava responsiivisen web-suunnittelun työpajaharjoitus, joka demonstroi moderneja tekniikoita ja parhaita käytäntöjä mukautuvien verkkosivujen luomiseen.

## Sisältö

### 1. Johdanto responsiiviseen suunnitteluun
- Mitä on responsiivinen web-suunnittelu?
- Mobile-first -lähestymistapa
- Media queryt ja niiden käyttö
- Joustavat layout-tekniikat

### 2. Breakpoint-esimerkit
Harjoituksessa käytetään seuraavia breakpointeja:
- **480px** - Pienet mobiililaitteet
- **768px** - Tabletit pystysuunnassa
- **1024px** - Tabletit vaakasuunnassa / pienet kannettavat
- **1200px** - Työpöytätietokoneet

### 3. Layout-tekniikat
- **Flexbox** - Yksiulotteiset asettelut (navigaatio, kortit)
- **CSS Grid** - Kaksiulotteinen järjestelmä (galleriat, sivupohjat)
- **Sidebar Layout** - Sivupalkki, joka mukautuu näyttökokoon

### 4. Responsiiviset elementit
- Kuvat, jotka skaalautuvat automaattisesti
- Typografia, joka mukautuu näyttökokoon
- Navigaatio, joka muuttuu mobiilissa pystysuuntaiseksi
- Korttiasettelu, joka mukautuu 1→2→4 palstaan

## Ominaisuudet

### Mobile-First Design
Sivusto on suunniteltu mobile-first -periaatteella, eli lähtökohtana on mobiililaite ja siitä laajennetaan suuremmille näytöille.

### Interaktiiviset esimerkit
- Dynaaminen näyttökokoilmaisin (näyttää onko mobiili/tabletti/desktop)
- Hover-efektit korteissa ja painikkeissa
- Sticky navigaatio, joka pysyy näkyvissä vieritettäessä

### Responsiiviset komponentit
1. **Navigaatio** - Muuttuu pystysuuntaisesta vaakasuuntaiseksi
2. **Feature Cards** - 1 palsta → 2 palstaa → 3 palstaa
3. **Content Cards** - 1 palsta → 2 palstaa → 4 palstaa
4. **Breakpoint Demo** - 1 palsta → 2 palstaa → 4 palstaa
5. **Sidebar Layout** - Pinottuna mobiilissa, vierekkäin desktopissa

## Tekniikat ja työkalut

### CSS-tekniikat
- `display: flex` ja `flexbox`-ominaisuudet
- `display: grid` ja `grid`-ominaisuudet
- `@media` media queryt
- Relatiiviset yksiköt (`rem`, `em`, `%`, `vw`)
- `clamp()` -funktio responsiiviseen typografiaan
- `max-width: 100%` kuville
- `position: sticky` navigaatiolle

### Layout-strategiat
- **Mobile-first approach** - Lähtökohtana mobiili
- **Progressive enhancement** - Lisätään ominaisuuksia suuremmille näytöille
- **Flexible grids** - Joustavat grid-asettelut
- **Fluid images** - Kuvat skaalautuvat automaattisesti

## Käyttöönotto

1. Avaa `index.html` selaimessa
2. Muuta selaimen ikkunan kokoa nähdäksesi responsiiviset muutokset
3. Käytä selaimen kehittäjätyökaluja (F12) ja device toolbaria mobiililaitteen simulointiin

## Testausohjeet

### Selaimen ikkunan koon muuttaminen
- **< 768px**: Mobiilinäkymä - kaikki elementit yhdessä palstassa
- **768px - 1023px**: Tablettinäkymä - useimmat elementit kahdessa palstassa
- **≥ 1024px**: Työpöytänäkymä - elementit 3-4 palstassa

### Kehittäjätyökalut
1. Avaa kehittäjätyökalut (F12 tai Ctrl+Shift+I)
2. Klikkaa "Toggle device toolbar" -ikonia (Ctrl+Shift+M)
3. Valitse eri laitteet (iPhone, iPad, jne.)
4. Testaa sekä pysty- että vaakasuunnassa

## Oppimistulokset

Tämän harjoituksen jälkeen osaat:
- ✅ Käyttää mobile-first -lähestymistapaa
- ✅ Luoda media queryja eri näyttökokoihin
- ✅ Käyttää Flexboxia ja CSS Gridia responsiivisiin layouteihin
- ✅ Tehdä kuvia ja typografiaa responsiivisiksi
- ✅ Ymmärtää breakpointien merkityksen
- ✅ Testata responsiivisuutta eri laitteilla

## Parhaat käytännöt

### TEE ✅
- Aloita mobiilisuunnittelusta
- Testaa kaikilla laitteilla
- Käytä joustavaa layoutia
- Optimoi kuvat eri kokoihin
- Käytä relatiivisia yksiköitä

### VÄLTÄ ❌
- Älä käytä kiinteitä pikseliarvoja
- Älä unohda viewport metatägiä
- Älä piilota tärkeää sisältöä mobiilissa
- Älä käytä liian pieniä painikkeita
- Älä tee liian monimutkaisia layouteja

## Tiedostot

```
WS05_Responsive/tuntiharjoitus/
├── index.html          # Pääsivu responsiivisilla esimerkeillä
├── styles/
│   └── style.css       # Mobile-first tyylitiedosto
└── readme.md           # Tämä tiedosto
```

## Lisäresurssit

- [MDN - Responsive Design](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Responsive_Design)
- [CSS-Tricks - A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
- [CSS-Tricks - A Complete Guide to Grid](https://css-tricks.com/snippets/css/complete-guide-grid/)
- [Google - Responsive Web Design Basics](https://web.dev/responsive-web-design-basics/)

## Tekijä

Laurea-ammattikorkeakoulu  
Web-sivuston kehittäminen -kurssi  
Syksy 2025

---

💡 **Muista:** Paras tapa oppia responsiivista suunnittelua on kokeilla ja testata itse! Muuta selaimen kokoa ja katso, miten elementit mukautuvat.
