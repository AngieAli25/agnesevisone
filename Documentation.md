# DOCUMENTATION - LANDING PAGE AGNESE VISONE PEDAGOGISTA

## 📋 INFORMAZIONI PROGETTO

**Cliente:** Agnese Visone  
**Ruolo:** Pedagogista  
**Obiettivo:** Lead Generation (richieste di contatto e consulenza)  
**Target:** Genitori con figli 0-12 anni, famiglie in difficoltà, istituzioni e servizi sociali  
**Tagline:** "Crescita serena per bimbi & genitori"  
**Zona operativa:** Napoli e provincia  
**Attiva dal:** 2014 (10+ anni di esperienza)

---

## 🎨 DESIGN SYSTEM

### Palette Colori

**Colori Principali:**
- Corallo Primary: `#E8605A`
- Corallo Hover: `#D44F49`
- Lavanda: `#9B8EC4`
- Lavanda Light: `#C5BDDF`
- Verde: `#8BBF5A`
- Verde Light: `#A8CF79`

**Colori Neutri:**
- Cream Background: `#FAF6F0`
- Sand: `#C8B8A2`
- White: `#FFFFFF`
- Dark Text: `#2C2C2C`
- Body Text: `#3D3D3D`
- Muted Text: `#7A7A7A`

**Colori Accento (da post social):**
- Coral Cards: `#E8605A`
- Lavender Cards: `#9B8EC4`
- Green Cards: `#8BBF5A`
- Cream Cards: `#FAF6F0`
- Sand Cards: `#F5EFE6`

### Tipografia

**Google Fonts:**
- **Nunito** (400, 600, 700, 800, 900) — Body, UI, form, bottoni
- **Caveat** (500, 700) — Titoli handwriting, accenti, tagline

**Gerarchia:**
- H1: Nunito Black 900, 48-56px desktop / 32-36px mobile, line-height 1.15
- H2: Nunito Black 900, 36-42px desktop / 28-32px mobile, line-height 1.2
- H3: Nunito ExtraBold 800, 20-24px desktop / 18-20px mobile
- Body: Nunito Regular 400, 16-18px, line-height 1.6
- Accenti handwriting: Caveat 700, 1.1-1.2em rispetto al contesto
- Label/Tag: Nunito Bold 700, 12px, uppercase, letter-spacing 0.08em
- Bottoni: Nunito ExtraBold 800, 16px

---

## 🛠️ STACK TECNOLOGICO

- **Struttura:** HTML5 singolo file (index.html)
- **CSS:** Custom Properties + CSS3 puro (no framework)
- **JS:** Vanilla JS (IntersectionObserver per scroll reveal, toggle WhatsApp)
- **Font:** Google Fonts (Nunito + Caveat)
- **Icone:** SVG inline / Emoji come decorazione
- **Responsive:** Mobile-first approach
- **No dipendenze esterne** oltre ai Google Fonts

---

## 📐 STRUTTURA LANDING PAGE

### NAVBAR (Sticky)

**Elementi:**
- Logo: dot corallo con icona SVG + "Agnese Visone" bold + "Pedagogista" in Caveat lavanda
- CTA Button: "Contattami →" — pill corallo, nascosto su mobile <600px

**Comportamento:**
- Sticky top con backdrop-filter blur(12px)
- Background: rgba(250,246,240,0.92)
- Border-bottom: 1px solid rgba(155,142,196,0.15)
- Smooth scroll su tutti i link ancora

---

### SEZIONE 1: HERO

**Layout:** Griglia 2 colonne desktop, 1 colonna mobile (foto sopra)

**Colonna sinistra:**

**Badge superiore:**
"⭐ Crescita serena per bimbi & genitori"
(background bianco, border lavanda, testo lavanda)

**H1:**
"Accompagno la tua famiglia con cuore e competenza"
— "cuore e competenza" in Caveat corallo

**Sottotitolo:**
"Pedagogista con oltre 10 anni di esperienza. Supporto a bambini, genitori e famiglie nel costruire relazioni più sane, equilibrate e consapevoli."

**Pill servizi (4):**
- 🏠 Educativa Domiciliare
- 👥 Gruppi Genitori
- 🤝 Spazi Neutri
- 💙 Famiglie Vulnerabili

**CTA doppio:**
- Primario: "Parliamo insieme →" (corallo, pill, shadow)
- Secondario: "Scopri i servizi ↓" (link lavanda)

**Colonna destra — Foto card:**

- Placeholder foto Agnese (aspect-ratio 3/4, border-radius 32px)
- **Floating badge 1** (corallo, animazione float): "10+ anni di esperienza"
- **Floating badge 2** (bianco, animazione float ritardata): "Comune di Napoli — Servizi Sociali"

**Animazioni:**
- Hero text: fadeInUp 0.7s
- Floating badges: loop float CSS (su/giù 3-4s infinito)
- Scroll reveal: IntersectionObserver su tutte le card

---

### SEZIONE 2: TRUSTED BY

**Layout:** Barra orizzontale full-width, flex-wrap

**Contenuto:**
- Label: "Collaborazioni" (uppercase, muted)
- 🏛️ Comune di Napoli – Servizi Sociali
- 🏠 Polo Territoriale per le Famiglie
- 🌱 Incontri Protetti & Spazi Neutri

**Border:** top + bottom 1px solid rgba(44,44,44,0.06)

---

### SEZIONE 3: CHI SONO

**Background:** Cream `#FAF6F0`

**Layout:** Griglia 2 colonne desktop (immagini sinistra, testo destra)

**Colonna sinistra — Stack immagini:**
- Rettangolo posteriore: background lavanda light, ruotato 3deg
- Rettangolo anteriore: gradient corallo, placeholder foto Agnese in contesto professionale
- Stat card sovrapposta: "Dal 2014" in Caveat corallo + "in attività"

**Colonna destra — Contenuto:**

**Tag:** "Chi sono" (verde)

**H2:**
"Una pedagogista che crede nel potere delle relazioni"
— "potere delle relazioni" in Caveat verde

**Paragrafo 1:**
"Mi chiamo Agnese Visone e dal 2014 accompagno bambini, genitori e famiglie in percorsi di crescita consapevole. Il mio approccio è sistemico-relazionale: metto al centro il benessere dell'intero nucleo familiare, non solo del singolo."

**Paragrafo 2:**
"Collaboro con il Comune di Napoli per i Servizi Sociali, intervenendo in situazioni di vulnerabilità, conflittualità familiare, casi di violenza e incontri protetti. Opero anche a domicilio, direttamente nelle famiglie, per costruire con loro nuove risorse relazionali."

**Value pills (3):**
- 💛 Ascolto empatico e approccio non giudicante
- 🌱 Interventi basati sulle risorse della famiglia
- 🔗 Tutela del minore e rafforzamento dei legami

---

### SEZIONE 4: SERVIZI

**Background:** Bianco `#FFFFFF`
**ID:** `#servizi`

**Section header:**
- Tag: "I miei servizi"
- H2: "Come posso aiutarti" — "aiutarti" in Caveat corallo
- Sottotitolo: "Ogni famiglia è unica. I miei interventi sono pensati per adattarsi ai bisogni specifici di ciascun nucleo."

**Grid servizi (layout misto):**

**Card 1 — Educativa Domiciliare** (background corallo, testo bianco)
Icona: 🏠
Titolo: "Educativa Domiciliare"
Testo: "Intervengo direttamente a casa delle famiglie in contesti di disagio, fragilità emotiva e conflittualità intensa. L'obiettivo è ripristinare l'equilibrio familiare."

**Card 2 — Gruppi Genitori** (background lavanda, testo bianco)
Icona: 👥
Titolo: "Gruppi Genitori"
Testo: "Spazi di confronto e riflessione in gruppo. Un momento conviviale per condividere esperienze, trovare strumenti pratici e sentirsi meno soli nel percorso genitoriale."

**Card 3 — Spazi Neutri** (background cream, testo dark)
Icona: 🛡️
Titolo: "Spazi Neutri"
Testo: "Tutelo il diritto del minore di mantenere il contatto con il genitore non convivente, in un ambiente sicuro, protetto e supervisionato."

**Card 4 — Polo Territoriale** (background verde, testo bianco, WIDE span-2)
Icona: 🌿
Titolo: "Polo Territoriale per le Famiglie"
Testo: "Approccio sistemico-relazionale che mette al centro il benessere dell'intero nucleo. Supporto ai genitori nel decodificare i bisogni dei figli e migliorare l'organizzazione interna."
Chip tags: Routine e regole | Gestione dei pasti | Cura di base | Risorse relazionali | Legami familiari | Conflittualità | Fragilità emotive

**Card 5 — Consulenza Genitoriale** (background sand, testo dark)
Icona: 💬
Titolo: "Consulenza Genitoriale"
Testo: "Non serve aspettare una difficoltà. A volte basta il desiderio di capire meglio come accompagnare tuo figlio nella crescita."

**Hover:** translateY(-6px), transizione 0.25s

---

### SEZIONE 5: COME LAVORO

**Background:** Cream `#FAF6F0`
**ID:** `#come-lavoro`

**Section header:**
- Tag: "Il mio metodo"
- H2: "Come lavoro con te" — "lavoro" in Caveat lavanda
- Sottotitolo: "Un percorso chiaro, empatico e strutturato per accompagnarti dal primo contatto al cambiamento."

**4 Step con linea connettrice gradiente (desktop):**

**Step 1** (cerchio corallo)
Numero: "1"
Titolo: "Primo contatto"
Testo: "Mi scrivi o chiami. Parliamo brevemente della tua situazione senza impegno."

**Step 2** (cerchio lavanda)
Numero: "2"
Titolo: "Valutazione"
Testo: "Ascolto la tua storia, comprendo i bisogni del nucleo e definisco l'approccio più adatto."

**Step 3** (cerchio verde)
Numero: "3"
Titolo: "Intervento"
Testo: "Avviamo insieme il percorso scelto: domiciliare, di gruppo o consulenza individuale."

**Step 4** (cerchio sand)
Numero: "4"
Titolo: "Monitoraggio"
Testo: "Verifico i progressi e adatto il percorso alle esigenze che emergono nel tempo."

**Linea connettrice:** gradient corallo→lavanda→verde, top center dei cerchi, visibile solo desktop

---

### SEZIONE 6: TEMATICHE

**Background:** Gradient lavanda `linear-gradient(135deg, #9B8EC4 0%, #7B6BB4 100%)`
**ID:** `#tematiche`

**Pattern sfondo:** SVG dot pattern bianco opacity 0.05

**Section header (testo bianco):**
- Tag: "Aree di intervento" (bianco semitrasparente)
- H2: "Di cosa mi occupo" — "occupo" in Caveat
- Sottotitolo: "Dall'educazione emotiva alla genitorialità consapevole: accompagno famiglie in tanti momenti della crescita."

**6 Card glassmorphism** (background rgba bianco 0.12, border bianco 0.2, blur):

**Tema 1:**
Icona: 😤
Titolo: "Gestione della rabbia"
Testo: "La rabbia non è il problema. È un'emozione da accogliere e decodificare insieme."

**Tema 2:**
Icona: 🤲
Titolo: "Genitorialità consapevole"
Testo: "Strumenti pratici per capire meglio i bisogni dei propri figli e rispondervi con equilibrio."

**Tema 3:**
Icona: 🌱
Titolo: "Sviluppo cognitivo"
Testo: "Comprendere le fasi evolutive per accompagnare il bambino senza forzature."

**Tema 4:**
Icona: 🤝
Titolo: "Gioco cooperativo"
Testo: "Imparare ad ascoltarsi, aiutarsi e costruire relazioni sane con gli altri."

**Tema 5:**
Icona: 💔
Titolo: "Separazione e conflitto"
Testo: "Supporto ai nuclei familiari in fase di separazione, tutela del minore nei percorsi di visita."

**Tema 6:**
Icona: ⭐
Titolo: "Autostima e identità"
Testo: "L'autostima nasce tra i bambini: interventi per costruire un sé positivo e solido."

**Hover:** background rgba bianco 0.22, translateY(-4px)

---

### SEZIONE 7: A CHI MI RIVOLGO

**Background:** Bianco `#FFFFFF`
**ID:** `#a-chi`

**Section header:**
- Tag: "A chi mi rivolgo"
- H2: "Sei nel posto giusto" — "giusto" in Caveat verde
- Sottotitolo: "Lavoro sia con famiglie che cercano supporto diretto, sia con istituzioni e servizi."

**2 Card grandi affiancate:**

**Card sinistra — Per genitori e famiglie** (background gradient corallo tinted)
Tag: "Per genitori e famiglie" (corallo)
H3: "Stai cercando supporto per tuo figlio?"
Checklist:
- ✓ Tuo figlio fatica a gestire le emozioni o la rabbia
- ✓ Ti senti sopraffatto/a dalle sfide della genitorialità
- ✓ Stai attraversando una separazione e vuoi tutelare i tuoi figli
- ✓ Vuoi semplicemente capire meglio come accompagnare la crescita
- ✓ La famiglia attraversa un momento di difficoltà o riorganizzazione

**Card destra — Per istituzioni** (background gradient verde tinted)
Tag: "Per istituzioni e servizi" (verde scuro)
H3: "Collaborazioni istituzionali"
Checklist:
- ✓ Servizi sociali comunali e territoriali
- ✓ Tribunali per i minorenni – incontri protetti
- ✓ Centri antiviolenza e case rifugio
- ✓ Scuole e asili nido per progetti educativi
- ✓ Comunità e famiglie affidatarie

---

### SEZIONE 8: FORM CONTATTI

**Background:** Cream `#FAF6F0`
**ID:** `#contatti`

**Layout:** Griglia 2 colonne (info sinistra, form destra)

**Colonna sinistra:**

Tag: "Contatti" (corallo)

H2: "Iniziamo a parlare insieme" — "parlare insieme" in Caveat corallo

Testo: "Non serve aspettare una crisi. Scrivimi per una prima chiacchierata informale: capiremo insieme se posso esserti utile."

**Info contatti (3 item):**
- 📱 Telefono / WhatsApp → +39 XXX XXX XXXX
- ✉️ Email → agnese@agnesevisone.it *(da aggiornare)*
- 📍 Zona di intervento → Napoli e provincia

**Colonna destra — Form:**

Background: bianco, border-radius 48px, padding generoso, shadow soft

Titolo form: "Mandami un messaggio"
Sottotitolo: "Rispondo entro 24 ore. I campi con * sono obbligatori."

---

**CAMPI FORM:**

1. **Nome** * (required) — input text, placeholder "Il tuo nome"
2. **Cognome** * (required) — input text, placeholder "Il tuo cognome"
   → Disposti in griglia 2 colonne

3. **Email** * (required) — input email, placeholder "tua@email.it"

4. **Numero di telefono** * (required) — input tel, placeholder "+39 XXX XXX XXXX"
   + **Toggle WhatsApp** cliccabile affiancato:
   - Stato default: bordo grigio, testo "È WhatsApp?"
   - Stato attivo (checkbox checked): background verde #E8F5E8, bordo #25D366, testo "#128C7E" + "WhatsApp ✓"
   → Disposti affiancati (tel flex-1 + toggle)

5. **Età del bambino/a** (NOT required, opzionale) — input number, min 0, max 18, placeholder "es. 5"
   Label: "Età del bambino/a" + "(opzionale)"

6. **Tematica** (NOT required, opzionale) — select dropdown
   Label: "Tematica" + "(opzionale)"
   Opzioni:
   - "— Seleziona la tematica —" (default)
   - Gestione della rabbia / emozioni
   - Genitorialità consapevole
   - Sviluppo cognitivo ed evolutivo
   - Separazione e conflitto familiare
   - Autostima e identità del bambino
   - Educativa domiciliare
   - Spazi neutri / incontri protetti
   - Gruppi genitori
   - Collaborazione istituzionale
   - Altro

7. **Messaggio** (NOT required, opzionale) — textarea, min-height 90px, resize vertical
   Label: "Messaggio" + "(opzionale)"
   Placeholder: "Raccontami brevemente la tua situazione o ciò di cui hai bisogno..."

---

**CONSENSO PRIVACY:**

Checkbox required
Testo: "Ho letto e accetto la Privacy Policy. I miei dati saranno trattati esclusivamente per rispondere alla mia richiesta, nel rispetto del GDPR."
Link "Privacy Policy" → href="#"

---

**BOTTONE SUBMIT:**

Testo: "Invia messaggio" + icona SVG freccia
Background: corallo `#E8605A`
Hover: translateY(-3px), box-shadow amplificato rgba(232,96,90,0.4)
Width: 100%
Min-height: 48px
Border-radius: 999px
Font: Nunito 800

---

**STATI FORM:**

Focus input: border corallo, box-shadow rgba lavanda 0.12
Validazione: HTML5 nativa (required, type="email", type="number")

---

### FOOTER

**Background:** Dark `#2C2C2C`

**Layout:** Griglia 3 colonne desktop → 2 tablet → 1 mobile

**Colonna 1 — Brand:**
"Agnese Visone" bold bianco
"Pedagogista" in Caveat corallo
Testo: "Accompagno bambini, genitori e famiglie verso una crescita serena e consapevole. Dal 2014 con approccio sistemico-relazionale."

**Colonna 2 — Servizi:**
Titolo H4: "Servizi"
Links: Educativa Domiciliare | Gruppi Genitori | Spazi Neutri | Consulenza Genitoriale

**Colonna 3 — Info:**
Titolo H4: "Info"
Links: Chi sono | Tematiche | Contatti | Privacy Policy

**Copyright bar:**
"© 2024 Agnese Visone – Pedagogista. P.IVA XXXXXXXXXX"
"Realizzato da Meraviglialab"
(flex space-between, font 0.82rem)

---

## 🎬 ANIMAZIONI

### Globali — Scroll Reveal (IntersectionObserver vanilla JS)

```js
// Elementi target: .service-card, .tema-card, .audience-card, .process-step
initial: { opacity: 0, transform: 'translateY(20px)' }
transition: 'opacity 0.5s ease, transform 0.5s ease'
trigger: threshold 0.1
once: true
```

### Floating Badges Hero

```css
@keyframes float {
  0%, 100% { transform: translateY(0px); }
  50% { transform: translateY(-8px); }
}
.badge-1: animation: float 3s ease-in-out infinite;
.badge-2: animation: float 4s ease-in-out infinite 0.5s;
```

### Hero Text

```css
@keyframes fadeInUp {
  from { opacity: 0; transform: translateY(24px); }
  to   { opacity: 1; transform: translateY(0); }
}
.hero-left: animation: fadeInUp 0.7s ease both;
.hero-right: animation: fadeInUp 0.7s ease 0.15s both;
```

### Hover Cards

```css
.service-card:hover { transform: translateY(-6px); transition: 0.25s; }
.tema-card:hover    { background: rgba(255,255,255,0.22); transform: translateY(-4px); }
```

### CTA Buttons

```css
.btn-primary:hover {
  transform: translateY(-3px);
  box-shadow: 0 12px 32px rgba(232,96,90,0.4);
}
```

### WhatsApp Toggle

```js
// Classe .active aggiunta/rimossa su click
.wa-toggle.active {
  background: #E8F5E8;
  border-color: #25D366;
  color: #128C7E;
}
```

---

## ♿ ACCESSIBILITÀ (WCAG 2.1 AA)

- **Struttura semantica:** `<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`
- **Heading hierarchy:** H1 → H2 → H3 in ordine logico, un solo H1
- **Alt text:** Tutte le immagini con descrizione (placeholder con aria-label)
- **Focus states:** Outline visibile su tutti gli elementi interattivi
- **Keyboard navigation:** Tab order logico, tutti i CTA raggiungibili
- **Color contrast:** Minimo 4.5:1 per testo normale, 3:1 per UI
- **Form labels:** Ogni campo con `<label>` esplicita associata via `for`
- **Required fields:** `required` HTML5 + indicazione visiva asterisco
- **Aria labels:** Toggle WhatsApp con aria-label descrittivo
- **Lang attribute:** `<html lang="it">`

---

## 📱 RESPONSIVE DESIGN

### Breakpoints

| Breakpoint | Range | Layout |
|---|---|---|
| Mobile | 320px – 599px | 1 colonna, tutto stacked |
| Tablet | 600px – 899px | 2 colonne dove appropriato |
| Desktop | 900px – 1099px | Layout completo |
| Large | 1100px+ | Max-width 1100px centrato |

### Comportamenti Mobile Specifici

- **Navbar:** CTA "Contattami" nascosta sotto 600px
- **Hero:** Foto sopra, testo sotto; floating badges riposizionati vicino al bordo
- **Servizi:** 1 colonna; card wide perde span e diventa 1 colonna
- **Process steps:** 2 colonne; linea connettrice nascosta
- **Tematiche:** 1 colonna
- **Form:** Griglia nome/cognome → 1 colonna; layout contatti → stacked
- **Footer:** 1 colonna

### Touch Targets

Tutti i bottoni e link interattivi: minimo 44x44px

---

## 🔍 SEO ON-PAGE

### Meta Tags

```html
<title>Agnese Visone – Pedagogista Napoli | Supporto Famiglie e Bambini</title>

<meta name="description" content="Pedagogista a Napoli con 10+ anni di esperienza. Educativa domiciliare, gruppi genitori, spazi neutri. Approccio sistemico-relazionale per famiglie e bambini. Contattami.">

<meta property="og:title" content="Agnese Visone – Pedagogista | Crescita serena per bimbi & genitori">
<meta property="og:description" content="Supporto a famiglie, bambini e genitori. Educativa domiciliare, gruppi genitori, spazi neutri. Napoli e provincia.">
<meta property="og:type" content="website">
```

### Keywords Target
pedagogista napoli, educativa domiciliare napoli, supporto famiglie, genitorialità consapevole, spazi neutri minori, gruppi genitori napoli, pedagogista bambini emozioni

---

## 📦 FILE NECESSARI

```
Landing - Pedagogista Agnese Visone/
├── index.html              ← Landing page (file principale)
├── Guidelines.md           ← Linee guida UX/UI
├── Documentation.md        ← Questo file
└── images/                 ← Da creare quando disponibili
    ├── agnese-hero.jpg     ← Foto professionale hero (aspect 3:4)
    ├── agnese-about.jpg    ← Foto in contesto lavorativo
    └── og-image.jpg        ← Immagine Open Graph (1200x630px)
```

**Nota sulle immagini:** Attualmente tutti i placeholder visivi sono implementati come div colorati con label testuale. Sostituire con immagini reali aggiornando:
- Hero: `.main-photo-placeholder` → `<img src="images/agnese-hero.jpg" alt="Agnese Visone Pedagogista">`
- About: `.img-front` → `<img src="images/agnese-about.jpg" alt="Agnese Visone in contesto professionale">`

---

## ✅ CHECKLIST TECNICA

- [ ] HTML5 semantico validato (W3C)
- [ ] Un solo H1 nella pagina
- [ ] Tutti i link ancora funzionanti (#servizi, #chi-sono, #contatti, ecc.)
- [ ] Form: campi required/optional corretti
- [ ] Toggle WhatsApp: classe .active aggiunta/rimossa correttamente
- [ ] IntersectionObserver: scroll reveal funzionante su card e step
- [ ] Floating badges: animazione float loop infinito
- [ ] Responsive testato a 375px, 768px, 1024px, 1440px
- [ ] Navbar sticky con backdrop blur
- [ ] Smooth scroll su tutti i link ancora
- [ ] Hover states su tutti i CTA e card
- [ ] Font Google Fonts caricati (Nunito + Caveat)
- [ ] CSS custom properties usate per tutti i colori
- [ ] Meta tags SEO implementati
- [ ] lang="it" su html tag
- [ ] P.IVA e contatti reali da inserire (placeholder: XXXXXXXXXX)
- [ ] Email reale da inserire (placeholder: agnese@agnesevisone.it)
- [ ] Telefono reale da inserire (placeholder: +39 XXX XXX XXXX)

---

## 🚀 NOTE PER LO SVILUPPO

1. **Single file:** Tutto in index.html — CSS in `<style>`, JS in `<script>` a fondo pagina
2. **No framework JS** — vanilla JS sufficiente per tutte le interazioni
3. **CSS Variables:** Tutti i colori tramite custom properties `:root`
4. **Font loading:** Preconnect a Google Fonts per performance
5. **Form backend:** Per ora solo struttura HTML. Per la gestione invio integrare con: Formspree, Netlify Forms, o webhook n8n (Meraviglialab usa n8n)
6. **Privacy policy:** Link placeholder, da creare pagina dedicata
7. **Google Analytics:** Da integrare dopo go-live con evento form_submit
8. **WhatsApp CTA:** Considerare aggiunta link diretto `wa.me/39XXXXXXXXXX` come CTA secondaria mobile

---

**FINE DOCUMENTAZIONE**

Questo documento contiene struttura completa, testi definitivi e specifiche tecniche per sviluppare e mantenere la landing page di Agnese Visone Pedagogista.
