# Bootstrap Workshop - Tuntiharjoitus

## Kuvaus

Tämä on kattava Bootstrap 5 -esimerkki, joka esittelee frameworkin keskeisimmät ominaisuudet ja komponentit.

## Sisältö

### 1. Navigaatio (Navbar)
- Responsiivinen navigaatiopalkki
- Collapse-toiminto mobiililaitteille
- Bootstrap Icons -kuvakkeet
- Aktiivisten linkkien tyylit

### 2. Hero-osio
- Isot otsikot ja call-to-action -painikkeet
- Kaksipalstainen asettelu kuvalla
- Responsiivinen grid-järjestelmä

### 3. Komponentit
**Cards (Kortit):**
- 3 korttia kuvilla
- Erivärisiä painikkeita
- Shadow-efektit

**Alerts (Ilmoitukset):**
- Success, Info ja Warning -ilmoitukset
- Suljettava alert dismiss-painikkeella
- Kuvakkeet alerteissa

**Badges & Buttons:**
- Erivärisiä badgeja
- Primary, Secondary, Success, Danger -painikkeet
- Outline-tyyliset painikkeet

### 4. Grid-järjestelmä
- 4-sarakkeinen responsiivinen grid
- Mukautetut sarakeleveydet (8/4 jako)
- Automaattinen rivittyminen mobiilissa
- Breakpoint-esimerkit (col-12, col-md-6, col-lg-3)

### 5. Lomake (Form)
- Yhteystietolomake kaikilla peruskentillä
- Input-kentät, Select-dropdown, Textarea
- Checkbox-valinta
- Validointi-valmius
- Lähetä-painike kuvakkeella

### 6. Accordion (Harmonikka)
- Kolme avattavaa FAQ-osiota
- Bootstrap collapse -toiminnallisuus
- Kuvakkeet otsikoissa
- Smooth-animaatiot

### 7. Footer
- Kaksipalstainen asettelu
- Linkit ja tekijänoikeustiedot
- Ulkoinen linkki Bootstrap-dokumentaatioon

## Käytetyt Bootstrap-ominaisuudet

### CSS-luokat
- **Container & Grid:** `container`, `row`, `col-*`, `g-*` (gap)
- **Spacing:** `p-*` (padding), `m-*` (margin), `py-*`, `px-*`
- **Colors:** `bg-primary`, `bg-success`, `text-white`, `text-dark`
- **Typography:** `display-*`, `lead`, `fw-bold`, `text-center`
- **Utilities:** `shadow`, `rounded`, `w-100`, `h-100`

### Komponentit
- `navbar`, `navbar-expand-lg`, `navbar-toggler`
- `card`, `card-body`, `card-img-top`
- `alert`, `alert-dismissible`
- `btn`, `btn-primary`, `btn-outline-*`
- `badge`
- `form-control`, `form-select`, `form-check`
- `accordion`, `accordion-item`, `accordion-button`

### Responsiivisuus
- **Breakpoints:** xs (<576px), sm (≥576px), md (≥768px), lg (≥992px), xl (≥1200px)
- **Grid:** Sarakkeet mukautuvat automaattisesti näytön koon mukaan
- **Navbar:** Collapse-valikko pienillä näytöillä
- **Cards:** Pinoutuvat mobiilissa

## Tekniset tiedot

- **Bootstrap versio:** 5.3.2
- **CDN:** jsDelivr
- **Bootstrap Icons:** 1.11.1
- **JavaScript:** Bootstrap Bundle (sisältää Popper.js:n)

## Käyttö

1. Avaa `index.html` selaimessa
2. Testaa responsiivisuutta muuttamalla selaimen kokoa
3. Kokeile interaktiivisia elementtejä:
   - Avaa/sulje navigaatiovalikko
   - Klikkaa accordion-osioita
   - Täytä lomaketta
   - Sulje alert-ilmoituksia

## Oppimistavoitteet

Tämän esimerkin avulla opit:
- ✅ Bootstrap grid-järjestelmän käytön
- ✅ Valmiiden komponenttien hyödyntämisen
- ✅ Responsiivisen layoutin rakentamisen
- ✅ Utility-luokkien käytön
- ✅ Bootstrap-teeman mukaisen ulkoasun luomisen
- ✅ JavaScript-komponenttien toiminnan

## Lisäresurssit

- [Bootstrap 5 Dokumentaatio](https://getbootstrap.com/docs/5.3/)
- [Bootstrap Icons](https://icons.getbootstrap.com/)
- [Bootstrap Examples](https://getbootstrap.com/docs/5.3/examples/)

## Huomioita

- Tämä esimerkki käyttää CDN-linkkejä, ei tarvitse asentaa mitään
- Kaikki tyylit tulevat Bootstrapista, ei erillistä CSS-tiedostoa
- JavaScript-toiminnallisuudet toimivat ilman omaa koodia
- Kuvat tulevat Lorem Picsum -palvelusta (placeholder-kuvat)

---

**Laurea-ammattikorkeakoulu | Web-sivuston kehittäminen 2025**
