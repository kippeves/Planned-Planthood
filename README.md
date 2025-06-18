# Planned Planthood

En responsiv webbapplikation för växtentusiaster att upptäcka, dela och lära sig om olika växter och odlingstekniker.

![Planned Planthood Logo](Assets/images/logo.svg)

## Beskrivning

Planned Planthood är en modern, responsiv webbapplikation som visar upp olika växter med detaljerad information, kategorisering och användarbidrag. Webbplatsen har ett rent, användarvänligt gränssnitt med fokus på tillgänglighet och responsiv design.

## Uppgiftsbeskrivning

<details>
    <summary>Inlämningsuppgift Planned Planthood</summary>
    
# Inlämningsuppgift Planned Planthood
    
    Uppgiften är att göra en sida enligt nedanståend bilder, text och kod-stycken.
</details>
<details>
    <summary>Tidsram och inlämning</summary>
    
## Tidsram och inlämning
    
    - Ni har fram till och med xx på er att utföra uppgiften. xx ska de finnas tillgänglig för oss lärare att gå igenom då vi startar 9.00 på morgonen.
    - Klona detta repo och använd som grund. Ni lämnar in genom att pusha till er GitHub (den ni angav i formuläret tidigare) med namnet "Planned Planthood".
    - Sen skriver ni i lärarchatten när ni är klara med uppgiften så vi vet (om ni inte meddelar bedömmer vi den i det skick den är kl 9.00 xx, commits efter detta kommer ignoreras).
</details>
<details>
    <summary>Krav</summary>
    
## Krav
    
    - Använd de variabler ni får i style.css som grund för sidans design
    - Ni ska lösa uppgiften enligt den design som anges i bilderna (responsiv från mobil-tablet-desktop)
    - Formulär och semantik ska vara tillgängligt (använd WAVE eller dylikt för att testa)
    - Koden ska vara välformatterad och tydligt strukturerad med en genomtänkt namngivning på klasser samt ev kommentarer
    - Inga bibliotek som react, bootstrap, tailwind eller dylikt får användas, endast .CSS och .HTML (ev js).
    - Om ni lånar en reset, flow-util, visually-hidden eller dylikt ange källa som kommentar i er kod.
    - Var beredd på att förklara er kod muntligt så se till att ni förstår vad ni gör om ni rådfrågar andra/AI.
</details>
<details>
<summary>Extra</summary>

## Extra

    Följande är extra och sådant ni inte måste ha med om ni inte hinner/vill/kan

    - Overlay-bilden med krukan kortbilden
    - Footer på kortet med avatar och meta-info
    - Galleriet högst upp kan ha en enklare design som i tablet-läget även på desktop
    - Olika färger på "tags" behövs inte om ni inte vill, använd bara den gröna accent-color på alla i så fall.
    - Använd gärna en diskret transition på hover/focus-visible om ni vill.
    - Hamburgar-menyn behöver ni bara göra som en ikon, all annan funktionalitet är superextra och inget som vi förväntar oss att ni gör!

</details>
<details>
    <summary>Övriga resurser</summary>
    
    ## Övriga resurser
    
    - Använd gärna avatarer från [https://avatar-placeholder.iran.liara.run/avatars](https://avatar-placeholder.iran.liara.run/avatars)
    - Använd gärna bilder från [https://picsum.photos/](https://picsum.photos/). Vill ni använda andra är det ok, men se till att det ser bra ut i sammanhanget.
    - Vill ni ändra texter och lägga in egen info är det också ok, bara det fyller samma typ av funktion och inte ändrar sidans utseende bortom innehållet.
    - SVG finns i mappen Assets/Images och kan användas antingen som vanliga bilder eller direkt inkopierade som HTML i koden
    - Länkarna ska vara semantiska men behöver inte gå någonstans (använd href="#")
</details>

<details>
    <summary>Design</summary>
    
## Design
    
### Desktop
    
Bilderna för designen ligger under Design mappen och innehåller bilder för de olika vyerna samt bild för hover state.<br>
![Design Desktop](/Design/PlannedPlanthood-Desktop.png)
    
### Hover state
    
För hover state gäller generellt att det är inverterat om det är annat än länkar. Länkar har understrykning vid hover, annars inte.<br>
![Hover States](/Design/PlannedPlanthood-Hover.png)
</details>

## Använda tekniker

- **HTML5** - Semantisk markup för struktur och tillgänglighet
- **CSS3** - Modern styling med:
  - CSS Grid för layout
  - CSS Container Queries för responsiv design
  - CSS Variables för tematisering
  - Flexbox för komponentlayouter
  - Subgrid för nästlade layouter
  - Media queries för responsiva brytpunkter
  - CSS nesting för bättre organisation
- **Responsiv Design** - Mobile-first-metod med anpassningar för surfplatta och desktop
- **Tillgänglighet** - ARIA-attribut och semantisk HTML för bättre skärmläsarstöd
- **Google Fonts** - Open Sans-typsnittsfamilj

## Projektstruktur

```
Planned Planthood/
├── Assets/
│   ├── avatar.png
│   └── images/
│       ├── icon-email.svg
│       ├── icon-phone.svg
│       ├── icon-planting.svg
│       ├── icon-seedling-2.svg
│       ├── icon-seedling.svg
│       └── logo.svg
├── Design/
│   ├── PlannedPlanthood-Desktop.png
│   ├── PlannedPlanthood-Hover.png
│   ├── PlannedPlanthood-Mobile.png
│   └── PlannedPlanthood-Tablet.png
├── styles/
│   ├── page.css - Huvudstilmall med layout och komponentstil
│   ├── reset.css - CSS-återställning och temvariabler
│   └── tags.css - Stilar för växtkategorietiketter
├── index.html - Huvud-HTML-fil
├── favicon.ico
└── README.md
```

## Funktioner

- **Responsiv Layout** - Anpassar sig till mobil-, surfplatte- och datorskärmsstorlekar
- **Växtgalleri** - Gridlayout av växtkort med bilder och information
- **Kategorisering** - Färgkodade etiketter för olika växttyper och egenskaper
- **Nyhetsbrevregistrering** - Formulär för användare att prenumerera på uppdateringar
- **Tillgänglighet** - Semantisk HTML och ARIA-attribut för bättre skärmläsarstöd
- **Modern Design** - Rent, användarvänligt gränssnitt med konsekvent styling

## Installation och konfiguration

1. Klona repositoryt:

   ```
   git clone https://github.com/kippeves/Planned-Planthood.git
   ```

2. Öppna projektmappen:

   ```
   cd planned-planthood
   ```

3. Öppna `index.html` i din webbläsare för att visa sidan.

## Användning

Webbplatsen är designad för att vara intuitiv och lätt att navigera:

- Bläddra i växtgalleriet för att upptäcka olika växter
- Använd navigeringsmenyn för att utforska olika sektioner

Ej implementerade delar:

- Registrera dig för nyhetsbrevet för att få uppdateringar
- Klicka på växtkort för att se mer detaljer
- Filtrera växter efter deras kategorietiketter

## Designmetod

Projektet följer en komponentbaserad designmetod med:

- CSS Grid för övergripande layout
- Flexbox för komponentlayouter
- Container queries för responsiva komponenter
- CSS-variabler för konsekvent tematisering
- Mobile-first responsiv design

## Webbläsarstöd

Webbplatsen är designad för att fungera på moderna webbläsare som stöder CSS Grid, Container Queries och CSS Variables, inklusive:

- Chrome (senaste)
- Firefox (senaste)
- Safari (senaste)
- Edge (senaste)

## Erkännanden

- Avatarer från [Avatar Placeholder](https://avatar-placeholder.iran.liara.run/avatars)
- Bilder från [Picsum Photos](https://picsum.photos/)
- Ikoner och SVG:er skapade för projektet
