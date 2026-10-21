# 🐕 Agility Parcours-Planer

Ein interaktiver, browserbasierter Web-Editor zum Planen, Gestalten und Verwalten von Agility-Parcours. Die Anwendung läuft komplett clientseitig im Browser, speichert Daten lokal (Local Storage) und benötigt kein Backend.

## 🚀 Features

* **Parcours-Editor:** Intuitive Drag-and-Drop-Oberfläche zur Platzierung von Hindernissen (Hürden, Tunnel, Slalom, Kontaktzonenhindernisse u.v.m.).
* **Rotation & Ausrichtung:** Drehe Hindernisse stufenlos oder in festen Schritten (15°, 90°).
* **Nummerierung & Lauflinie:** Automatische Berechnung und Visualisierung der Lauflinie inklusive Kurvenberechnung (Bezier-Kurven) und Richtungsmarkierungen.
* **Prüfungs- und Validierungs-Modus:** Warnhinweise bei Abständen, fehlendem Start/Ziel oder Geräten außerhalb der Fläche.
* **Druck- und PDF-Export:** Erstelle saubere Druckansichten für das Training oder Turniere (A4 Quer- oder Hochformat).
* **Backup & Wiederherstellung:** Exportiere und importiere deine Parcours als JSON-Datei oder Text-Backup.
* **Dark Mode Support:** Passt sich automatisch an die Systemeinstellungen an (Hell/Dunkel).

## 🛠️ Technologien

* **HTML5 / SVG** für die performante Darstellung des Parcours-Grids und der Hindernisse.
* **CSS3** mit CSS-Variablen und Responsive Design.
* **Vanilla JavaScript** (keine externen Frameworks oder Build-Tools erforderlich).

## 📦 Installation & Nutzung

Da es sich um eine reine Single-File- bzw. clientseitige Web-Anwendung handelt, gibt es keinen Kompilierungs- oder Installationsschritt:

1. Klone das Repository oder lade die `.html`-Datei herunter.
2. Öffne die Datei `index.html` (oder `Agility Parcours-Planer.html`) in einem beliebigen modernen Webbrowser (Chrome, Firefox, Safari, Edge).
3. Optional: Hoste das Projekt direkt über **GitHub Pages**, indem du den `main`-Branch in den Repository-Einstellungen als Quelle auswählst.

## 📄 Lizenz

Dieses Projekt steht unter der [MIT License](LICENSE).
