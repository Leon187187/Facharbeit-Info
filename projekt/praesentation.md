---
marp: true
paginate: true
style: |
  section {
    padding: 40px;
    position: relative;
  }
  section.cover {
    position: relative;
    overflow: hidden;
    isolation: isolate;
    background-color: #82b0e5;
  }
  .cover-background {
    position: absolute;
    inset: 0;
    z-index: -1;
    pointer-events: none;
  }
  .cover-background img {
    position: absolute;
    width: 145px;
    height: 145px;
    object-fit: contain;
  }
  .cover-background img:nth-child(1) {
    top: 9%;
    left: 10%;
  }
  .cover-background img:nth-child(2) {
    bottom: 9%;
    left: 50%;
    transform: translateX(-50%);
  }
  .cover-background img:nth-child(3) {
    top: 9%;
    right: 10%;
  }
  .titel {
    position: absolute;
    inset: 0;
    z-index: 1;
    display: grid;
    place-items: center;
    box-sizing: border-box;
    padding: 80px;
    text-align: center;
  }
  .titel h1 {
    max-width: 920px;
    margin: 0;
    padding: 0 0 24px;
    border-bottom: 4px solid rgba(255, 255, 255, 0.8);
    color: #173657;
    font-size: 54px;
    line-height: 1.2;
    text-shadow: 0 2px 0 rgba(255, 255, 255, 0.22);
  }
  .autor {
    position: absolute;
    bottom: 24px;
    left: 40px;
    margin: 0;
    color: #173657;
    font-family: inherit;
    font-size: 20px;
    font-weight: bold;
  }
  section.content-slide {
    background-color: #82b0e5;
  }
  section.content-slide > h1 {
    position: absolute;
    top: 40px;
    left: 40px;
    margin: 0;
    z-index: 1;
    color: #173657;
    font-size: 54px;
    line-height: 1.2;
    padding-bottom: 24px;
    border-bottom: 4px solid rgba(255, 255, 255, 0.8);
    text-shadow: 0 2px 0 rgba(255, 255, 255, 0.22);
  }
  section.definitions-slide > ul {
    columns: 2;
    column-gap: 36px;
    margin: 128px 0 0;
    padding-left: 24px;
    color: #173657;
    font-size: 23px;
    line-height: 1.2;
  }
  section.definitions-slide li {
    break-inside: avoid;
    margin-bottom: 12px;
  }
  section.definitions-slide > ul > li > a {
    color: #173657;
    font-weight: bold;
    text-decoration: none;
  }
  section.definitions-slide li > ul {
    margin: 4px 0 0;
    padding-left: 0;
    list-style: none;
    font-size: 21px;
    line-height: 1.2;
  }
  section.overview-slide > table {
    position: absolute;
    top: 190px;
    left: 40px;
    width: calc(100% - 80px);
    table-layout: fixed;
    border-collapse: separate;
    border-spacing: 0 12px;
    color: #173657;
    font-size: 20px;
    line-height: 1.3;
  }
  section.overview-slide th,
  section.overview-slide td {
    padding: 14px 18px;
    text-align: left;
    vertical-align: top;
  }
  section.overview-slide th {
    background-color: #173657;
    color: #ffffff;
    font-size: 19px;
    letter-spacing: 0.02em;
  }
  section.overview-slide th:first-child {
    border-radius: 12px 0 0 12px;
  }
  section.overview-slide th:last-child {
    border-radius: 0 12px 12px 0;
  }
  section.overview-slide tbody tr {
    background-color: rgba(255, 255, 255, 0.78);
  }
  section.overview-slide tbody td:first-child {
    border-radius: 12px 0 0 12px;
    color: #173657;
    font-size: 22px;
  }
  section.overview-slide tbody td:last-child {
    border-radius: 0 12px 12px 0;
  }
  section.overview-slide tbody td:first-child a {
    color: #173657;
    font-weight: bold;
    text-decoration: underline;
    text-underline-offset: 3px;
  }
  section.overview-slide th:nth-child(1),
  section.overview-slide td:nth-child(1) {
    width: 20%;
  }
  section.overview-slide th:nth-child(2),
  section.overview-slide td:nth-child(2) {
    width: 55%;
  }
  section.overview-slide th:nth-child(3),
  section.overview-slide td:nth-child(3) {
    width: 25%;
  }
  section.e2e-slide > img {
    position: absolute;
    top: calc(50% + 25px);
    right: 50px;
    width: 610px;
    height: auto;
    transform: translateY(-50%);
  }
  section.funding-slide > img {
    position: absolute;
    top: calc(50% + 25px);
    right: 50px;
    width: 610px;
    height: auto;
    transform: translateY(-50%);
  }
  section.personal-data-slide > img {
    position: absolute;
    top: calc(50% + 25px);
    right: 50px;
    width: 610px;
    height: auto;
    transform: translateY(-50%);
  }
  section.e2e-slide > .e2e-question,
  section.personal-data-slide > .personal-data-question,
  section.funding-slide > .funding-question {
    position: absolute;
    top: calc(50% - 30px);
    left: 50px;
    width: 500px;
    margin: 0;
    color: #173657;
    font-size: 30px;
    font-weight: 600;
    line-height: 1.3;
    transform: translateY(-50%);
  }
---

<!-- _class: cover -->

<div class="cover-background" aria-hidden="true">
  <img src="bilder/WhatsApp.svg.png" alt="">
  <img src="bilder/Telegram.svg.png" alt="">
  <img src="bilder/Signal.svg.png" alt="">
</div>

<div class="titel">

# Welcher Messengerdienst bietet den besten Schutz für meine privaten Daten?

<p class="autor">Leon Weber</p>

</div>

---

<!-- _class: content-slide overview-slide -->

# Überblick über WhatsApp, Telegram und Signal

| Dienst | Ende-zu-Ende-Verschlüsselung | Quellcode |
| --- | --- | --- |
| [WhatsApp](https://www.dr-datenschutz.de/die-ende-zu-ende-verschluesselung-bei-whatsapp/) | Seit 2016 standardmäßig für alle Nachrichten und Anrufe | Nicht Open Source |
| [Telegram](https://metricool.com/de/telegram-sicherheit-ein-check-deiner-kommunikation/#Ende-zu-Ende-Verschluesselung_bei_geheimen_Chats) | Nicht standardmäßig, nur bei geheimen Chats | Teilweise Open Source |
| [Signal](https://www.chip.de/ratgeber/software/datenschutz-und-sicherheit-bei-signal-das-muessen-sie-wissen_72abeec7-207c-4507-a1e9-5b4dff63f569.html) | Standardmäßig für Nachrichten, Anrufe und Gruppenchats mit maximal 5 Teilnehmern | Open Source |
---
<!-- _class: content-slide e2e-slide -->

# 1. Kriterium: Ende-zu-Ende Verschlüsselung 

<img src="bilder/e2e.png" alt="Darstellung der Kommunikation mit und ohne Ende-zu-Ende-Verschlüsselung">

<p class="e2e-question">Bietet der Dienst standardmäßig Ende-zu-Ende-Verschlüsselung an und welche Nachrichten werden verschlüsselt?</p>

---
<!-- _class: content-slide personal-data-slide -->

# 2. Kriterium: Umgang mit persönlichen Daten

<p class="personal-data-question">Welche Daten werden über mich gesammelt, wie lange werden sie gespeichert und werden sie eventuell weiterverkauft?</p>

<img src="bilder/datenschutz.png" alt="Symbol für den Schutz persönlicher Daten">

---

<!-- _class: content-slide funding-slide -->

# 3. Kriterium: Finanzierung

<p class="funding-question">Welchen Einfluss hat die Finanzierung auf meine Privatsphäre?</p>

<img src="bilder/moneten.png" alt="Geld als Symbol für die Finanzierung">

---
<!-- _class: content-slide -->

# Ausgewählter Dienst: Signal



---
