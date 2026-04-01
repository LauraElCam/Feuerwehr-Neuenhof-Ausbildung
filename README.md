# Feuerwehr-Neuenhof-Ausbildung 🚒

**Interaktives Nachschlagewerk für die Feuerwehr Neuenhof**

Willkommen im Ausbildungs-Repository der Feuerwehr Neuenhof! Dieses Projekt dient als zentrale, digitale Anlaufstelle für unsere Mannschaft, um das Schweizer Feuerwehr-Basiswissen (FKS) interaktiv, modern und praxisnah zu trainieren.

---

## 📖 Themenbereiche: Basiswissen

Hier sammeln wir alle relevanten Unterlagen, Lern-Apps und Videos zu den verschiedenen Abschnitten des Basiswissens. Das Projekt ist so aufgebaut, dass es stetig um neue Themen erweitert werden kann.

### Abschnitt: Brandbekämpfung 🔥

In diesem Modul geht es um die feuerwehrtechnischen Grundlagen der Brandbekämpfung. Um Theorie und Praxis optimal zu verknüpfen, haben wir verschiedene Medien und eine interaktive Lern-App zusammengestellt.

* **📘 Offizielles Basiswissen:** [Link zum FKS Basiswissen-Dokument](#)
* **🎥 Ausbildungsvideos:** [Hier geht es zu den YouTube-Videos zum Thema Brandbekämpfung](#)
* **💻 Interaktive Shiny-App:** [Zur Lern- & Quiz-App: Brandbekämpfung](#) *(Hier Theorie lernen und Wissen im Quiz testen!)*

---

## 🚀 Geplante Erweiterungen

Dieses Nachschlagewerk wächst kontinuierlich weiter. Als Nächstes sind folgende Module geplant:
* **Atemschutz** (Shiny-App in Vorbereitung)
* *(Weitere Themen folgen...)*

---

## 🛠️ Technische Struktur (Für Entwickler)

Dieses Repository ist als Monorepo aufgebaut. Die interaktiven Module basieren auf **R und Shiny**. 

Jedes Themengebiet hat seinen eigenen Ordner:
* `/brandbekaempfung/` enthält die `app.R` sowie den `/www/`-Ordner für Bilder und Ergebnis-Exporte.
* Weitere Module (wie `/atemschutz/`) werden nach demselben Prinzip hinzugefügt.
