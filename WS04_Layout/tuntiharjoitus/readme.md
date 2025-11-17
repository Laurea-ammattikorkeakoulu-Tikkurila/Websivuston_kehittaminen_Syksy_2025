# CSS Layout Workshop - Tuntiharjoitus

## Kuvaus

Tämä on kattava CSS-asetteluharjoitus, joka esittelee modernit layout-tekniikat: **Flexbox** ja **CSS Grid**. Esimerkki sisältää useita käytännön demonstraatioita ja sovelluksia.

## Sisältö

### 1. Flexbox-esimerkit
Flexbox on yksiulotteinen layout-malli, joka sopii täydellisesti elementtien järjestelyyn rivillä tai sarakkeessa.

**Esimerkit:**
- **Basic Row** - Perus rivijärjestely gap-tilalla
- **Space Between** - Elementit tasaisesti jaettuna
- **Centered Content** - Täydellinen keskitys (vaaka + pysty)
- **Column Layout** - Pystyjärjestely
- **Flex Wrap** - Responsiiviset kortit, jotka rivityvät automaattisesti

**Käytetyt ominaisuudet:**
- `display: flex`
- `flex-direction` (row, column)
- `justify-content` (space-between, center)
- `align-items`
- `flex-wrap`
- `gap`

### 2. CSS Grid -esimerkit
Grid on kaksiulotteinen layout-järjestelmä, joka mahdollistaa sekä rivien että sarakkeiden hallinnan samanaikaisesti.

**Esimerkit:**
- **3-Column Grid** - Perus kolmisarakkeinen grid
- **Auto-fit** - Responsiivinen grid, joka mukautuu automaattisesti
- **Different Sizes** - Eri kokoiset gridin solut (grid spanning)
- **Large Gap** - Isot välit elementtien välillä

**Käytetyt ominaisuudet:**
- `display: grid`
- `grid-template-columns` (repeat, minmax, auto-fit)
- `gap`
- `grid-column: span`
- `grid-row: span`

### 3. Sivun kokonaisasettelu (Page Layout)
Moderni sivurakenne CSS Gridillä:
- **Header** - Yläpalkki (koko leveys)
- **Sidebar** - Sivupalkki
- **Main Content** - Pääsisältö
- **Footer** - Alapalkki (koko leveys)

**Grid-rakenne:**
```css
grid-template-columns: 200px 1fr;
grid-template-rows: 80px 1fr 60px;
```

### 4. Käytännön esimerkit

**Navigaatiopalkki (Flexbox)**
- Logo vasemmalla, linkit oikealla
- `justify-content: space-between`
- Responsiivinen valikko

**Product Grid (CSS Grid)**
- Tuotekortteja automaattisella layoutilla
- `auto-fit` ja `minmax` responsiivisuutta varten
- Hover-efektit

**Card Layout (Flexbox)**
- Joustavat kortit, jotka kasvavat/kutistuvat
- `flex: 1 1 250px`
- Pinoutuu mobiilissa

## Tekniset yksityiskohdat

### Flexbox vs Grid - Milloin käyttää?

**Käytä Flexboxia kun:**
- Layoutti on yksiulotteinen (joko rivi TAI sarake)
- Haluat elementtien mukautuvan sisältöön
- Tarvitset yksinkertaisen keskityksen
- Rakennat navigaatiota, painikeriviä tms.

**Käytä Gridia kun:**
- Layoutti on kaksiulotteinen (rivit JA sarakkeet)
- Tarvitset tarkkaa kontrollia molempiin suuntiin
- Rakennat sivun päärakennetta
- Haluat elementtien olevan tarkasti määritellyissä paikoissa

### Responsiivisuus

**Breakpointit:**
- **768px:** Tablet-näkymä
  - Grid muuttuu yksisarakkeiseksi
  - Navigaatio pinoutuu
  
- **480px:** Mobiili-näkymä
  - Kaikki gridit yhdeksi sarakkeeksi
  - Flexbox-suunta muuttuu column-tilaan

### Käytetyt CSS-ominaisuudet

**Layout:**
- `display: flex / grid`
- `grid-template-columns / rows`
- `justify-content`, `align-items`
- `flex-direction`, `flex-wrap`
- `gap`

**Styling:**
- `linear-gradient()` - Liukuvärit
- `border-radius` - Pyöristetyt kulmat
- `box-shadow` - Varjostukset
- `transition` - Siirtymäanimaatiot
- `transform` - Hover-efektit

**Responsive:**
- `@media` queries
- `minmax()` funktio
- `auto-fit` / `auto-fill`
- Joustavat yksiköt (fr, %, rem)

## Oppimistavoitteet

Tämän harjoituksen jälkeen osaat:
- ✅ Käyttää Flexboxia elementtien järjestelyyn
- ✅ Rakentaa monimutkaisia asetteluja CSS Gridillä
- ✅ Valita oikean layouttitekniikan tilanteen mukaan
- ✅ Luoda responsiivisia layoutteja
- ✅ Yhdistää Flexboxia ja Gridia samalla sivulla
- ✅ Käyttää moderneja CSS-yksiköitä (fr, minmax)

## Käyttö

1. Avaa `index.html` selaimessa
2. Tutki eri layout-esimerkkejä
3. Muuta selaimen kokoa nähdäksesi responsiivisuuden
4. Hover-efektit näkyvät elementtien päällä
5. Tutki koodia ymmärtääksesi toteutuksen

## Vinkkejä

- **Flexbox** on loistava valinta yksinkertaisiin asetteluihin
- **Grid** on tehokkaampi monimutkaisiin sivurakenteisiin
- Voit käyttää **molempia samalla sivulla** - ne täydentävät toisiaan!
- Käytä **gap** -ominaisuutta marginaalien sijaan
- **minmax()** tekee grideistä joustavampia
- **auto-fit** luo responsiivisia grirejä ilman media queryjä

## Lisäresurssit

- [CSS Flexbox Guide - MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout)
- [CSS Grid Guide - MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout)
- [Flexbox Froggy](https://flexboxfroggy.com/) - Interaktiivinen peli
- [Grid Garden](https://cssgridgarden.com/) - Interaktiivinen peli

---

**Laurea-ammattikorkeakoulu | Web-sivuston kehittäminen 2025**
