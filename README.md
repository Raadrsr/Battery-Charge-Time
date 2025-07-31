# Battery Charge Time

Ein Kurzbefehl-Projekt für iOS, das die Ladezeit deines iPhones basierend auf deinem Ladeverhalten vorhersagt.

---

## 🚀 Version 2.0 - Was ist neu?

- **📂 Automatische Ordnerstruktur:** Der Kurzbefehl erstellt nun automatisch die erforderliche Ordnerstruktur in iCloud Drive. Keine manuelle Einrichtung mehr notwendig.
- **⚡ Adapter-Auswahl:** Neue Funktion zur Auswahl des verwendeten Stromadapters (5V oder 20V), um die Ladezeitberechnung noch präziser zu gestalten. Standardmäßig wird 20V angenommen.
- **📝 Wichtiger Hinweis für Update-Nutzer:** Wenn du bereits die alte Version des Kurzbefehls im Pfad `iCloud Drive/Shortcuts/Ladezeit/Differenzszeit` gespeichert hast, musst du die vorhandenen Dateien manuell in die neuen Verzeichnisse verschieben:
  - Für den 20V-Stecker: `iCloud Drive/Shortcuts/BatteryChargeTime/Differenzszeit/20`
  - Für den 5V-Stecker: `iCloud Drive/Shortcuts/BatteryChargeTime/Differenzszeit/5`

---

## 📥 Download

<div align="center">

### [📱 Kurzbefehl herunterladen](https://www.icloud.com/shortcuts/fc72f5a32f9a422eb0b3bd3228511256)

[![Download Battery Charge Time](https://img.shields.io/badge/Download-Battery%20Charge%20Time-blue?style=for-the-badge&logo=apple&logoColor=white)](https://www.icloud.com/shortcuts/fc72f5a32f9a422eb0b3bd3228511256)

</div>

---

## 🔧 Funktionen

- **🔋 Ladezeitvorhersage:** Analysiert deine Ladevorgänge und berechnet die Ladezeit.
- **🔐 Datenschutz:** Alle Daten werden _ausschließlich auf deinem iPhone gespeichert_. Es erfolgt keine Übertragung an externe Server.
- **⚙️ Anpassung:** Wähle eine gewünschte Ladeprozentzahl (z. B. 81 %).
- **📥 Datenabruf:** Wenn keine Trainingsdaten auf deinem iPhone verfügbar sind, werden diese vorübergehend aus diesem GitHub-Projekt abgerufen, um den Kurzbefehl sofort nutzbar zu machen.
- **🔌 Präzise Ladezeitberechnung:** Gib den verwendeten Stromadapter (5V oder 20V) an. Standardmäßig wird 20V für Schnellladen verwendet.

---

## 📋 Voraussetzungen

Folgende Bedingungen müssen erfüllt sein, damit der Kurzbefehl funktioniert:

- 📱 iPhone mit iOS und der App **Kurzbefehle**.
- ☁️ Aktivierte Synchronisation für **iCloud Drive**.

---

## ⚡ Automationen

### 1. Beim Anschließen des iPhones an das Ladekabel
Führt den Kurzbefehl **„Battery Charge Time"** aus und übergibt die Zahl **0**.

### 2. Beim Erreichen des gewünschten Ladezustands
Führt den Kurzbefehl **„Battery Charge Time"** aus und übergibt die Zahl **1**.

---

## 🛠️ Installation

1. **Kurzbefehl herunterladen:** Klicke auf den [Download-Button](#-download) oben und füge den Kurzbefehl zu deiner **Kurzbefehle-App** hinzu.
2. Die erforderliche Ordnerstruktur wird nun automatisch erstellt. Kein manuelles Eingreifen erforderlich.
3. **⚠️ Hinweis für Update-Nutzer:** Verschiebe vorhandene Daten aus dem alten Verzeichnis `iCloud Drive/Shortcuts/Ladezeit/Differenzszeit` manuell in die neuen Verzeichnisse:
   - `iCloud Drive/Shortcuts/BatteryChargeTime/Differenzszeit/20` (für den 20V-Stecker)
   - `iCloud Drive/Shortcuts/BatteryChargeTime/Differenzszeit/5` (für den 5V-Stecker)
4. Wenn keine Trainingsdaten vorhanden sind, werden diese automatisch aus diesem GitHub-Projekt abgerufen, bis der Kurzbefehl genügend eigene Daten gesammelt hat.
5. Erstelle die Automationen gemäß den Anweisungen.

---

## ⚠️ Wichtige Hinweise

Der Kurzbefehl benötigt einige Ladevorgänge, um die richtige Ladezeit für dein iPhone vorhersagen zu können. Dazu ist es notwendig, dass die Ladegewohnheiten gespeichert und analysiert werden.

- **Lade dein iPhone immer bis zur gewünschten Prozentzahl (z. B. 81 %),** wie im Kurzbefehl angegeben.
- **Abgebrochene Ladevorgänge:** Wenn der Ladevorgang vorzeitig abgebrochen wird, werden keine Daten gespeichert. In diesem Fall kann der Kurzbefehl keine weiteren Verbesserungen in der Vorhersage vornehmen.
- **Adapter-Auswahl:** Wähle beim Start des Kurzbefehls den verwendeten Stromadapter (5V oder 20V). Standardmäßig wird 20V für Schnellladen verwendet.
- **Datenabruf:** Solange keine Trainingsdaten verfügbar sind, werden Platzhalterdaten aus diesem GitHub-Projekt verwendet, um eine funktionale Vorhersage zu ermöglichen.

#### Datenschutz:
Alle Daten, die der Kurzbefehl speichert, verbleiben **ausschließlich auf deinem iPhone**. Es erfolgt keine Übertragung von persönlichen Daten an externe Server oder Dritte. Die vorübergehenden Daten aus diesem GitHub-Projekt sind anonymisiert und dienen nur zur Initialisierung.

---

## 📜 Lizenz

Dieses Projekt steht unter der **MIT-Lizenz**. Weitere Informationen findest du in der Datei [LICENSE](./LICENSE).
