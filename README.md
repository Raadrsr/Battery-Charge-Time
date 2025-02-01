# Battery Charge Time

<p style="color: blue; text-align: center; font-size: 1.5em;">
Ein Kurzbefehl-Projekt für iOS, das die Ladezeit deines iPhones basierend auf deinem Ladeverhalten vorhersagt.
</p>

---

## 🔧 Funktionen

<ul>
  <li><strong>🔋 Ladezeitvorhersage:</strong> Analysiert deine Ladevorgänge und berechnet die Ladezeit.</li>
  <li><strong>🔐 Datenschutz:</strong> Alle Daten werden <em>ausschließlich auf deinem iPhone gespeichert</em>. Es erfolgt keine Übertragung an externe Server.</li>
  <li><strong>⚙️ Anpassung:</strong> Wähle eine gewünschte Ladeprozentzahl (z. B. 81 %).</li>
  <li><strong>📥 Datenabruf:</strong> Wenn keine Trainingsdaten auf deinem iPhone verfügbar sind, werden diese vorübergehend aus diesem GitHub-Projekt abgerufen, um den Kurzbefehl sofort nutzbar zu machen.</li>
</ul>

---

## 📋 Voraussetzungen

<p>Folgende Bedingungen müssen erfüllt sein, damit der Kurzbefehl funktioniert:</p>

<ul>
  <li>📱 iPhone mit iOS und der App <strong>Kurzbefehle</strong>.</li>
  <li>☁️ Aktivierte Synchronisation für <strong>iCloud Drive</strong>.</li>
  <li>📂 Ordnerstruktur in iCloud Drive:</li>
</ul>

<pre>
iCloud Drive/Shortcuts/Ladezeit/Differenzszeit
</pre>

---

## ⚡ Automationen

<h3>1. Beim Anschließen des iPhones an das Ladekabel</h3>
<p>Führt den Kurzbefehl <strong>„Battery Charge Time“</strong> aus und übergibt die Zahl <strong>0</strong>.</p>

<h3>2. Beim Erreichen des gewünschten Ladezustands</h3>
<p>Führt den Kurzbefehl <strong>„Battery Charge Time“</strong> aus und übergibt die Zahl <strong>1</strong>.</p>

---

## 🛠️ Wichtige Ordnerstruktur

<p>Damit der Kurzbefehl korrekt funktioniert, muss folgende Ordnerstruktur im <strong>Shortcuts-Ordner</strong> auf <strong>iCloud Drive</strong> eingerichtet werden:</p>

<ul>
  <li><strong>1. Ordner „Ladezeit“:</strong> Dieser Ordner muss sich im Verzeichnis <code>iCloud Drive/Shortcuts</code> befinden.</li>
  <li><strong>2. Ordner „Differenzszeit“:</strong> Dieser Ordner muss sich innerhalb des Ordners <code>Ladezeit</code> befinden.</li>
</ul>

<p>Zusammengefasst sollte der vollständige Pfad wie folgt aussehen:</p>

<pre>
iCloud Drive/Shortcuts/Ladezeit/Differenzszeit
</pre>

<p>Bitte stelle sicher, dass diese Ordnerstruktur auf iCloud Drive existiert. Wenn sie noch nicht vorhanden ist, erstelle sie manuell.</p>

---

## 🛠️ Installation

<ol>
  <li><strong>Kurzbefehl herunterladen:</strong> Lade den Kurzbefehl <a href="https://www.icloud.com/shortcuts/5abf199f2d4f41ec8c21fa01402609f6">hier herunter</a> und füge ihn zu deiner <strong>Kurzbefehle-App</strong> hinzu.</li>
  <li>Stelle sicher, dass die Ordnerstruktur wie oben beschrieben eingerichtet ist.</li>
  <li>Wenn keine Trainingsdaten vorhanden sind, werden diese automatisch aus diesem GitHub-Projekt abgerufen, bis der Kurzbefehl genügend eigene Daten gesammelt hat.</li>
  <li>Erstelle die Automationen gemäß den Anweisungen.</li>
</ol>

---

## ⚠️ Wichtige Hinweise

<p>Der Kurzbefehl benötigt einige Ladevorgänge, um die richtige Ladezeit für dein iPhone vorhersagen zu können. Dazu ist es notwendig, dass die Ladegewohnheiten gespeichert und analysiert werden.</p>

<ul>
  <li><strong>Lade dein iPhone immer bis zur gewünschten Prozentzahl (z. B. 81 %),</strong> wie im Kurzbefehl angegeben.</li>
  <li><strong>Abgebrochene Ladevorgänge:</strong> Wenn der Ladevorgang vorzeitig abgebrochen wird, werden keine Daten gespeichert. In diesem Fall kann der Kurzbefehl keine weiteren Verbesserungen in der Vorhersage vornehmen.</li>
  <li><strong>Datenabruf:</strong> Solange keine Trainingsdaten verfügbar sind, werden Platzhalterdaten aus diesem GitHub-Projekt verwendet, um eine funktionale Vorhersage zu ermöglichen.</li>
</ul>

<h4>Datenschutz:</h4>
<p>Alle Daten, die der Kurzbefehl speichert, verbleiben <strong>ausschließlich auf deinem iPhone</strong>. Es erfolgt keine Übertragung von persönlichen Daten an externe Server oder Dritte. Die vorübergehenden Daten aus diesem GitHub-Projekt sind anonymisiert und dienen nur zur Initialisierung.</p>

---

## 📜 Lizenz

<p>Dieses Projekt steht unter der <strong>MIT-Lizenz</strong>. Weitere Informationen findest du in der Datei <a href="./LICENSE">LICENSE</a>.</p>
