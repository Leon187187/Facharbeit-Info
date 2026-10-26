# Recherche

## Thema und Leitfrage

- **Thema:** Messenger
- **Leitfrage:** Welcher Messengerdienst bietet den besten Schutz für meine privaten Daten?

## Überblick über WhatsApp, Telegram und Signal

| Dienst     | Ende-zu-Ende Verschlüsselung                                                         | Quellcode                                     | Worin unterscheidet er sich? | Beleg und Abrufdatum |
|------------|-----------------------------------------------------------------------|------------------------------|------------------------------|----------------------|
| WhatsApp | Seit 2016 standartmäßig für alle Nachichten und Anrufe  | nicht Open Source | Immer E2E Verschlüsselung, Quellcode nicht einsehbar      | [https://www.dr-datenschutz.de/die-ende-zu-ende-verschluesselung-bei-whatsapp/, 6.10.2026 15:07, https://reset.org/messenger-open-source-und-ende-zu-ende-verschluesselt-das-sind-die-sicheren-alternativen-zu-whatsapp/, 6.10.2026 15:27]      |
| Telegram | Nicht standartmäßig, nur bei geheimen Chats | teilweise Open Source | Keine E2E Verschlüsselung, nur Quellcode der Apps einsehbar      | [https://metricool.com/de/telegram-sicherheit-ein-check-deiner-kommunikation/#Ende-zu-Ende-Verschluesselung_bei_geheimen_Chats, 6.10.2026 15:14, https://telegram.org/apps, 6.10.2026 15:24]      |
| Signal | Standartmäßig für alle Nachichten, Anrufe und Gruppenchats| Open Source | Immer E2E Verschlüsselung, Quellcode für jeden einsehbar      | [https://www.chip.de/ratgeber/software/datenschutz-und-sicherheit-bei-signal-das-muessen-sie-wissen_72abeec7-207c-4507-a1e9-5b4dff63f569.html, 6.10.2026 15:20]      |

## Meine drei Kriterien

- **Ende-zu-Ende Verschlüsselung:** Wichtig für mich, weil dadurch meine Nachichten nicht von fremden Personen gelesen werden können.
  - **Prüffrage:** Bietet der Dienst standartmäßig Ende-zu-Ende Verschlüsselung an und welche Nachichten werden verschlüsselt?
- **Umgang mit persönlichen Daten:** Wichtig für mich, weil ich wissen will ob meine persönlichen Daten weitergegeben werden. 
  - **Prüffrage:** Welche Daten werden über mich gesammelt, wie lange werden diese Daten über mich gespeichert und werden sie eventuell weiter verkauft?
- **Finanzierung:** Wichtig für mich, weil ich wissen will wodurch sich der Dienst finanziert.
  - **Prüffrage:** Welchen Einfluss hat die Finanzierung auf meine Privatsphäre?

## Ausgewählter Dienst: Signal

- **Auswahl begründen:** Ich habe mich für den Messenger Signal entschieden da er nach erstem Überblick meine Nachichten Ende-zu-Ende verschlüsselt und sein Quellcode offen einsehbar ist. 
- **Ende-zu-Ende Verschlüsselung / Bietet der Dienst standartmäßig Ende-zu-Ende Verschlüsselung an und welche Nachichten werden verschlüsselt?:** Standartmäßig für alle Nachichten, Anrufe und Gruppenchats mit max. 5 Teilnehmern, [Quelle1](https://www.chip.de/ratgeber/software/datenschutz-und-sicherheit-bei-signal-das-muessen-sie-wissen_72abeec7-207c-4507-a1e9-5b4dff63f569.html) 6.10.2026 15:20; [Quelle2](https://www.zwp-online.info/zwpnews/dental-news/branchenmeldungen/wie-sicher-ist-der-messenger-signal-wirklich) 7.10.2026 15:17
- **Umgang mit persönlichen Daten / Welche Daten werden über mich gesammelt, wie lange werden diese Daten über mich gespeichert und werden sie eventuell weiter verkauft?:** Signal sammelt keine Metadaten, auch keine Statusinformationen werden gesammelt, [Quelle1](https://www.datenschutz.org/signal/) 7.10.2026 15:24
- **Finanzierung / Welchen Einfluss hat die Finanzierung auf meine Privatsphäre?:** Bei Signal handelt es sich um eine gemeinnützige Stiftung (Non Profit) daher werden keine Daten über mich gesammelt, [Quelle1](https://www.datenschutz.org/signal/) 7.10.2026 15:27

## Erklärung Fachbegriffe

- [DSVGO](https://www.dataproofed.de/dsgvo-einfach-erklaert-datenschutzgrundverordnung/) 11.10.2026 14:02
  - DSVGO bedeutet Datenschutz-Grundverordnung. Es handelt sich um ein Gesetz das die Daten der Bürger der Europäischen Unuion schützt. Darin ist geregelt welche Daten von Unternehmen gesammelt und gespeichert werden dürfen und ob diese Daten für andere Zwecke verwendet werden dürfen.
- [Metadaten](https://www.ibm.com/de-de/think/topics/metadata) 11.10.2026 14:08
  - Metadaten sind Daten die einen Datensatz beschreiben wie z.B. Autor , Erstellungsdatum oder Dateiengröße. Sie erleichtern die Navigation von großen Datensätzen.
- [Ende-zu-Ende Verschlüsselung](https://eperi.com/de/docs/ende-zu-ende-verschlusselung/) 11.10.2026 14:19
  - Ende-zu-Ende Verschlüsselung bedeutet das die Daten bereits auf den Gerät des Absenders verschlüsselt werden, verschlüsselt übertragen werden und erst auf dem Endgerät des Empfänger entschlüsselt werden. 
- [Signal Protokoll](https://www.heise.de/select/ct/2021/9/2031014491848172917) 12.10.2026 11:16
  - Das Signal-Protokoll ist ein Verfahren, das Nachrichten verschlüsselt, sodass nur der Absender und der Empfänger sie lesen können. Es wird beispielsweise bei Signal und WhatsApp verwendet, um private Nachrichten vor unbefugtem Zugriff zu schützen. [KI verwendet]
- [Non Profit Stiftung](https://www.deutsches-stiftungszentrum.de/stiftungswissen/stiftungsformen/gemeinnuetzige-stiftung) 12.10.2026 11:23
  - Eine Non Profit Stiftung ist eine gemeinnützige Orgnasiation die dauerhaft mit ihrem Vermögen einen gesellschaftlichen Zweck unterstützt, z.B. Wissenschaft, Bildung oder Soziales. Drei Voraussetzungen um eine Non Profit Stiftung zu werden sind: 1. Selbstlosigkeit, 2. Ausschließlichkeit und 3. Unmittelbarkeit.
- [Open Source](https://www.iese.fraunhofer.de/blog/open-source-software/) 12.10.2026 16:10
  - Open Source bedeutet, dass der Quellcode der Software öffentlich einsehbar ist und ihn daher jeder für seine eigenen Zwecke verwenden kann.