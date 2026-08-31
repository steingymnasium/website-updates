# website-updates

Update-Kanal für die eigenen WordPress-Plugins und das Theme aus
**[steingymnasium/webiste](https://github.com/steingymnasium/webiste)**.

Dieses Repo wird **automatisch** von der CI des `webiste`-Repos befüllt – nicht von Hand bearbeiten.

* `metadata/<slug>.json` – Versions-Info, die der *Plugin Update Checker* auf der
  Schul-WordPress-Seite abfragt (`raw.githubusercontent.com`).
* **Releases** `<slug>-v<version>` – enthalten das jeweilige `<slug>.zip` als Asset
  (das lädt WordPress beim „Aktualisieren").

Ablauf: Code-Änderung in `webiste` → Push auf `main` → CI baut ZIP, legt ein
Release hier an und aktualisiert die Metadaten → WordPress zeigt das Update an.

Siehe Wiki-Seite **Plugin-Updates** im Doku-Repo.
