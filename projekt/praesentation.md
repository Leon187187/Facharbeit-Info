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

<!-- _class: content-slide -->

# Inhaltsangabe


---

<!-- _class: content-slide definitions-slide -->

# Definition Fachbegriffe

- [DSVGO](https://www.dataproofed.de/dsgvo-einfach-erklaert-datenschutzgrundverordnung/)
  - DSVGO bedeutet Datenschutz-Grundverordnung. Es handelt sich um ein Gesetz das die Daten der Bürger der Europäischen Unuion schützt. Darin ist geregelt welche Daten von Unternehmen gesammelt und gespeichert werden dürfen und ob diese Daten für andere Zwecke verwendet werden dürfen.
- [Metadaten](https://www.ibm.com/de-de/think/topics/metadata)
  - Metadaten sind Daten die einen Datensatz beschreiben wie z.B. Autor , Erstellungsdatum oder Dateiengröße. Sie erleichtern die Navigation von großen Datensätzen.
- [Ende-zu-Ende Verschlüsselung](https://eperi.com/de/docs/ende-zu-ende-verschlusselung/)
  - Ende-zu-Ende Verschlüsselung bedeutet das die Daten bereits auf den Gerät des Absenders verschlüsselt werden, verschlüsselt übertragen werden und erst auf dem Endgerät des Empfänger entschlüsselt werden.
- [Signal Protokoll](https://www.heise.de/select/ct/2021/9/2031014491848172917)
  - Das Signal-Protokoll ist ein Verfahren, das Nachrichten verschlüsselt, sodass nur der Absender und der Empfänger sie lesen können. Es wird beispielsweise bei Signal und WhatsApp verwendet, um private Nachrichten vor unbefugtem Zugriff zu schützen. [KI verwendet]
- [Non Profit Stiftung](https://www.deutsches-stiftungszentrum.de/stiftungswissen/stiftungsformen/gemeinnuetzige-stiftung)
  - Eine Non Profit Stiftung ist eine gemeinnützige Orgnasiation die dauerhaft mit ihrem Vermögen einen gesellschaftlichen Zweck unterstützt, z.B. Wissenschaft, Bildung oder Soziales. Drei Voraussetzungen um eine Non Profit Stiftung zu werden sind: 1. Selbstlosigkeit, 2. Ausschließlichkeit und 3. Unmittelbarkeit.
- [Open Source](https://www.iese.fraunhofer.de/blog/open-source-software/)
  - Open Source bedeutet, dass der Quellcode der Software öffentlich einsehbar ist und ihn daher jeder für seine eigenen Zwecke verwenden kann.

---

<!-- _class: content-slide overview-slide -->

# Überblick über WhatsApp, Telegram und Signal

| Dienst | Ende-zu-Ende-Verschlüsselung | Quellcode |
| --- | --- | --- |
| [WhatsApp](https://www.dr-datenschutz.de/die-ende-zu-ende-verschluesselung-bei-whatsapp/) | Seit 2016 standardmäßig für alle Nachrichten und Anrufe | Nicht Open Source |
| [Telegram](https://metricool.com/de/telegram-sicherheit-ein-check-deiner-kommunikation/#Ende-zu-Ende-Verschluesselung_bei_geheimen_Chats) | Nicht standardmäßig, nur bei geheimen Chats | Teilweise Open Source |
| [Signal](https://www.chip.de/ratgeber/software/datenschutz-und-sicherheit-bei-signal-das-muessen-sie-wissen_72abeec7-207c-4507-a1e9-5b4dff63f569.html) | Standardmäßig für Nachrichten, Anrufe und Gruppenchats mit maximal 5 Teilnehmern | Open Source |
---
