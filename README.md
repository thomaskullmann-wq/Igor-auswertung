# IGOR Auswertung

Mobile Web-Apps (PWA) zur schnellen Auswertung von IGOR-Wettbewerben (Interessengemeinschaft Ordonnanzgewehr-Rundenwettkämpfe Nordbaden). Es gibt zwei Versionen.

## Auswertung (Hauptordner, `index.html`)

Die reine Auswertung, ohne Namen und ohne Anbindung an eine Tabelle.

- 100 m (eine Scheibe) und 50 m (zwei Scheiben)
- 13 Schuss erfassen, die 3 schlechtesten werden gestrichen (Wertung: beste 10)
- Unterscheidung Zehner / Innenzehner
- Läuft offline, installierbar über „Zum Home-Bildschirm“ (iOS) bzw. „App installieren“ (Android)
- Keine Namen, keine Übertragung: der Stand liegt nur lokal im Browser

## Tabellenversion (`tabellenversion/`)

Wie die Auswertung, dazu für die Saisontabelle:

- `tabellenversion/index.html`: Schütze (Name, Verein) und Wettkampf-Nr. erfassen, Ergebnisse in einer Liste sammeln, Liste per Link senden (WhatsApp, E-Mail, Kopieren)
- `tabellenversion/tabelle.html`: führt die Ergebnisse mehrerer App-Nutzer zusammen (Link öffnen oder Code einfügen). Einzelwertung Saison: Durchschnitt der besten 6 Ergebnisse, bei Gleichstand Zehner, dann Innenzehner (wie die offizielle Liste). Dazu Tagesliste je Wettkampf, manuelle Erfassung, Sicherung/Wiederherstellung, CSV-Export und Drucken

## Datenschutz

- Kein Server, kein Konto, keine Statistik: Der Stand liegt nur lokal im Browser
- Beim Senden stecken die Ergebnisse im Teil des Links nach dem `#`; dieser Teil wird vom Browser nicht an den Webserver übertragen

Designed by Thomas Kullmann
