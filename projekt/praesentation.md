---
marp: true
paginate: true
footer: "Leon Weber, Klasse 10c"
style: |
  section {
    padding: 40px;
    position: relative;
  }
  footer {
    position: absolute;
    right: 40px;
    bottom: 18px;
    color: rgba(23, 54, 87, 0.8);
    font-size: 16px;
    font-weight: 700;
    letter-spacing: 0.02em;
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
  section.content-slide > h1 + ul,
  section.content-slide > h1 + ol {
    margin-top: 120px;
  }
  section.sources-slide > ul {
    columns: 2;
    column-gap: 36px;
    margin: 132px 0 0;
    padding-left: 28px;
    font-size: 22px;
    line-height: 1.3;
  }
  section.sources-slide li {
    break-inside: avoid;
    margin-bottom: 16px;
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
    border-spacing: 0 10px;
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
    border-bottom: 3px solid #5c91ca;
  }
  section.overview-slide th:first-child {
    border-radius: 12px 0 0 12px;
  }
  section.overview-slide th:last-child {
    border-radius: 0 12px 12px 0;
  }
  section.overview-slide tbody tr {
    background-color: rgba(255, 255, 255, 0.88);
    box-shadow: 0 4px 12px rgba(23, 54, 87, 0.12);
  }
  section.overview-slide tbody tr:nth-child(even) {
    background-color: rgba(255, 255, 255, 0.72);
  }
  section.overview-slide tbody td:first-child {
    border-radius: 12px 0 0 12px;
    color: #173657;
    font-size: 22px;
    font-weight: bold;
  }
  section.overview-slide tbody td:last-child {
    border-radius: 0 12px 12px 0;
  }
  section.overview-slide tbody td a {
    color: #235f9e;
    font-weight: 600;
    text-decoration: underline;
    text-underline-offset: 3px;
  }
  section.overview-slide th:nth-child(1),
  section.overview-slide td:nth-child(1) {
    width: 18%;
  }
  section.overview-slide th:nth-child(2),
  section.overview-slide td:nth-child(2) {
    width: 28%;
  }
  section.overview-slide th:nth-child(3),
  section.overview-slide td:nth-child(3) {
    width: 18%;
  }
  section.overview-slide th:nth-child(4),
  section.overview-slide td:nth-child(4) {
    width: 36%;
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

</div>

---

<!-- _class: content-slide overview-slide -->

# Überblick über WhatsApp, Telegram und Signal

| Dienst | Ende-zu-Ende Verschlüsselung | Quellcode | Worin unterscheidet er sich? |
| --- | --- | --- | --- |
| WhatsApp | [Seit 2016 standardmäßig für alle Nachrichten und Anrufe](https://www.dr-datenschutz.de/die-ende-zu-ende-verschluesselung-bei-whatsapp/) | [Nicht Open Source](https://reset.org/messenger-open-source-und-ende-zu-ende-verschluesselt-das-sind-die-sicheren-alternativen-zu-whatsapp/) | Immer E2E-Verschlüsselung; Quellcode nicht einsehbar |
| Telegram | [Nicht standardmäßig, nur bei geheimen Chats](https://metricool.com/de/telegram-sicherheit-ein-check-deiner-kommunikation/#Ende-zu-Ende-Verschluesselung_bei_geheimen_Chats) | [Teilweise Open Source](https://telegram.org/apps) | Keine E2E-Verschlüsselung standardmäßig; nur Quellcode der Apps einsehbar |
| Signal | [Standardmäßig für Nachrichten, Anrufe und Gruppenchats](https://www.chip.de/ratgeber/software/datenschutz-und-sicherheit-bei-signal-das-muessen-sie-wissen_72abeec7-207c-4507-a1e9-5b4dff63f569.html) | [Open Source](https://www.chip.de/ratgeber/software/datenschutz-und-sicherheit-bei-signal-das-muessen-sie-wissen_72abeec7-207c-4507-a1e9-5b4dff63f569.html) | Immer E2E-Verschlüsselung; Quellcode für jeden einsehbar |
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

1. **Ende-zu-Ende Verschlüsselung:**
- [Standardmäßig für alle Nachrichten, Anrufe und Gruppenchats](https://www.zwp-online.info/zwpnews/dental-news/branchenmeldungen/wie-sicher-ist-der-messenger-signal-wirklich)
- [Basierend auf dem Signal Protokoll](https://www.zwp-online.info/zwpnews/dental-news/branchenmeldungen/wie-sicher-ist-der-messenger-signal-wirklich)
- [Double Ratchet, d.h. Signal erneuert für jede versendete Nachricht den Schlüssel und alte Schlüssel werden gelöscht](https://www.bsi.bund.de/SharedDocs/Downloads/DE/BSI/Publikationen/DVS-Berichte/messenger.pdf?__blob=publicationFile&v=8)
- [Verschlüsselung lässt sich sogar nicht durch Quantencomputer knacken](https://www.heise.de/news/Signal-sichert-seine-Chats-gegen-Quantencomputer-10717838.html)


---
<!-- _class: content-slide -->

2. **Umgang mit persönlichen Daten:**
- Signal vertritt Zero-Knowledge-Policy, daher werden nur folgende [Metadaten](https://www.tagesschau.de/signal-messenger-sicherheit-usa-regierung-trump-100.html) bis zur Löschung der App gespeichert:
  - Datum- und Uhrzeit der Kontoerstellung
  - Tag der letzten Verbindung zum Signal Server
  - Telefonnummer
  - Kontaktdaten bei Einverständnis
- Temporäre Nachrichten werden gespeichert, solange sie nicht versendet werden können
- [Signal folgt den Vorgaben der Datenschutz-Vorgaben der DSVGO](https://www.datenschutz.org/signal/)

---
<!-- _class: content-slide -->

3. **Finanzierung:**
- Signal ist eine gemeinnützige Non Profit Stiftung ["Signal Technology Foundation"](https://projects.propublica.org/nonprofits/organizations/824506840)
  - Dies verhindert einen Aufkauf durch einen Tech-Giganten wie z.B. Meta oder eine Umwandlung in ein werbebasiertes Geschäftsmodell
- [Schaltet keine Werbung, nutzt keine Tracker, verkauft keine Nutzerdaten](https://www.chip.de/news/Nach-Pannen-in-den-USA-Das-muessen-Signal-Nutzer-jetzt-wissen_185891159.html)
- Finanziert sich durch frewillige Spenden z.B. [durch einmalige Spenden oder das Spendenabo in der App](https://aboutsignal.com/de/news/neues-design-fur-die-einmaligen-spendenabzeichen-von-signal/)
- [Bietet kostenpflichtige Zusatzfunktionen an z.B. Cloudbackups](https://www.golem.de/news/messenger-app-signal-erhaelt-cloud-back-up-abo-startet-2509-199902.html)


---

<!-- _class: content-slide -->

# Fazit

Ich persönlich würde mich für die Nutzung des Messengers Signal entscheiden, da er meiner Meinung nach durch das Signal Protokoll die beste Verschlüsselung meiner Nachrichten bietet. Ausserdem gefällt mir, dass Signal nur sehr wenige Metadaten speichert so können meine Daten nicht durch Datenleckes in die falschen Hände geraten. Auch finde ich gut, dass es sich bei Signal um eine gemeinnützige Stiftung handelt, die anders als z.B. WhatsApp keinen Gewinn erzielen muss und daher nicht auf Werbung zurück greift oder meine Nutzerdaten verkauft.

Daher bietet der Signal Messenger den besten Schutz für meine privaten Daten!

---

<!-- _class: content-slide sources-slide -->

# Quellen

- WhatsApp: [Ende-zu-Ende-Verschlüsselung](https://www.dr-datenschutz.de/die-ende-zu-ende-verschluesselung-bei-whatsapp/), abgerufen am 6.10.2026 15:07; [Quellcode](https://reset.org/messenger-open-source-und-ende-zu-ende-verschluesselt-das-sind-die-sicheren-alternativen-zu-whatsapp/), abgerufen am 6.10.2026 15:27
- Telegram: [Verschlüsselung bei geheimen Chats](https://metricool.com/de/telegram-sicherheit-ein-check-deiner-kommunikation/#Ende-zu-Ende-Verschluesselung_bei_geheimen_Chats), abgerufen am 6.10.2026 15:14; [Apps/Quellcode](https://telegram.org/apps), abgerufen am 6.10.2026 15:24
- Signal: [Datenschutz & Sicherheit](https://www.chip.de/ratgeber/software/datenschutz-und-sicherheit-bei-signal-das-muessen-sie-wissen_72abeec7-207c-4507-a1e9-5b4dff63f569.html), abgerufen am 6.10.2026 15:20; [Signal-Check](https://www.zwp-online.info/zwpnews/dental-news/branchenmeldungen/wie-sicher-ist-der-messenger-signal-wirklich), abgerufen am 7.10.2026 15:17; [Datenspeicherung & Finanzierung](https://www.datenschutz.org/signal/), abgerufen am 7.10.2026 15:24
- Fachbegriffe: [DSGVO](https://www.dataproofed.de/dsgvo-einfach-erklaert-datenschutzgrundverordnung/), abgerufen am 11.10.2026 14:02; [Metadaten](https://www.ibm.com/de-de/think/topics/metadata), abgerufen am 11.10.2026 14:08; [Ende-zu-Ende-Verschlüsselung](https://eperi.com/de/docs/ende-zu-ende-verschlusselung/), abgerufen am 11.10.2026 14:19; [Signal Protokoll](https://www.heise.de/select/ct/2021/9/2031014491848172917), abgerufen am 12.10.2026 11:16; [Open Source](https://www.iese.fraunhofer.de/blog/open-source-software/), abgerufen am 12.10.2026 16:10; [Gemeinnützige Stiftung](https://www.deutsches-stiftungszentrum.de/stiftungswissen/stiftungsformen/gemeinnuetzige-stiftung), abgerufen am 12.10.2026 11:23
- Sicherheitsbelege: [Quantencomputer-Schutz](https://www.heise.de/news/Signal-sichert-seine-Chats-gegen-Quantencomputer-10717838.html), abgerufen am 19.10.2026 13:54; [BSI DVS-Bericht](https://www.bsi.bund.de/SharedDocs/Downloads/DE/BSI/Publikationen/DVS-Berichte/messenger.pdf?__blob=publicationFile&v=8), abgerufen am 19.10.2026 13:55; [Metadaten/Tagesschau](https://www.tagesschau.de/signal-messenger-sicherheit-usa-regierung-trump-100.html), abgerufen am 19.10.2026 13:58; [Cloud-Backups](https://www.golem.de/news/messenger-app-signal-erhaelt-cloud-back-up-abo-startet-2509-199902.html), abgerufen am 19.10.2026 13:59
- Finanzierung & Datenschutz: [Signal Technology Foundation](https://projects.propublica.org/nonprofits/organizations/824506840), abgerufen am 21.10.2026 13:43; [Keine Werbung, keine Tracker, keine Nutzerdatenverkauf](https://www.chip.de/news/Nach-Pannen-in-den-USA-Das-muessen-Signal-Nutzer-jetzt-wissen_185891159.html), abgerufen am 21.10.2026 13:47; [Spendenabzeichen](https://aboutsignal.com/de/news/neues-design-fur-die-einmaligen-spendenabzeichen-von-signal/), abgerufen am 21.10.2026 13:51
- Bildquellen: [E2E-Illustration](https://www.expressvpn.com/de/blog/ende-zu-ende-verschlusselung/), abgerufen am 16.10.2026 16:44; [Geldsymbol](https://www.hartvannederland.nl/advies-en-tips/kopen-besparen/artikelen/banken-gaan-minder-vragen-stellen-bij-gebruik-van-contant-geld), abgerufen am 16.10.2026 16:45; [Datenschutzsymbol](https://www.bild.de/digital/internet/internet/werbung-mit-persoenlichen-daten-signal-zeigt-was-facebook-ueber-uns-weiss-76291690.bild.html), abgerufen am 16.10.2026 16:46
