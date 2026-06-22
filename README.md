# Global Finance Solutions – Banking Dashboard (Prototyp)

Hochwertiger FinTech-Banking-Prototyp im Stil moderner Apps (Revolut / N26 / Stripe). Reine Frontend-Demo mit simulierten Daten – es werden keine echten Bankdaten verarbeitet.

## Funktionen

- **Übersicht / Dashboard** – animierte KPI-Karten (Count-up), Wochen-Ausgaben-Chart, Bankkarte mit 3D-Tilt, Schnellaktionen, Budgets.
- **Transaktionen** – Liste mit Kategorie-Icons, Live-Suche und Filter-Chips.
- **Karten** – Kartenvisualisierungen, Sperren/Entsperren, Limits.
- **Kontowechsel** – die digitale 3-Klick-Journey (Identifikation → Bestätigung → Freigabe) mit IBAN-Prüfung, PSD2-Simulation und KI-Partner-Erkennung.
- **Vorgänge (Mitarbeiteransicht)** – interne Operations-Oberfläche: KPI-Karten, klickbare Status-Filterkarten, Falltabelle mit Suche/Sortierung/Bankfilter und ein Detailpanel mit Tabs (Übersicht/Dokumente/Prüfung/Historie). Aktionen: freigeben, manuelle Prüfung starten, zurückstellen, Status ändern, fehlende Unterlagen markieren, Kundenrückfrage und interne Notiz (über Modals), Prüfprotokoll anzeigen.
- **Sicherheit** – 2FA-Status, Login-Verlauf (mit Skeleton-Loading), Passwortstärke.
- **Dark Mode** (oben rechts umschaltbar, wird gespeichert) und responsives Layout (Desktop-Portal ↔ mobile App mit Bottom-Navigation).

## Live-Demo auf GitHub Pages hosten

1. Repository auf GitHub anlegen und die Dateien pushen (`index.html` muss im Repo-Root liegen).
2. Im Repo: **Settings → Pages**.
3. Unter **Build and deployment → Source**: `Deploy from a branch`.
4. Branch `main` und Ordner `/ (root)` wählen, **Save**.
5. Nach ~1 Minute ist die Seite unter `https://<benutzername>.github.io/<repo-name>/` erreichbar.

Lokal genügt ein Doppelklick auf `index.html` oder ein einfacher Server (`python -m http.server`).

## Dateien

- `index.html` – Einstiegsseite (von GitHub Pages bereitgestellt)
- `Global_Finance_Solutions.html` – inhaltsgleiche Kopie unter dem ursprünglichen Namen
