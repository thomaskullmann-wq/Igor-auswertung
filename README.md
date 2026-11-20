# IGOR Auswertung

Mobile Web-App (PWA) zur schnellen Auswertung von IGOR-Wettbewerben (Interessengemeinschaft Ordonnanzgewehr-Rundenwettkämpfe Nordbaden).

## App (`index.html`)

- 100 m (eine Scheibe) und 50 m (zwei Scheiben)
- 13 Schuss erfassen, die 3 schlechtesten werden gestrichen (Wertung: beste 10)
- Unterscheidung Zehner / Innenzehner
- Schützen (Name, Verein) und Wettkampf-Nr. erfassen, Ergebnisse in einer Liste sammeln
- Liste per Link senden (WhatsApp, E-Mail, Kopieren)

## Saisontabelle (`tabelle.html`)

- Führt die Ergebnisse mehrerer App-Nutzer zusammen (Link öffnen oder Code einfügen)
- Einzelwertung Saison: Durchschnitt der besten 6 Ergebnisse, bei Gleichstand Zehner, dann Innenzehner (wie die offizielle Liste)
- Tagesliste je Wettkampf, manuelle Erfassung, Sicherung/Wiederherstellung, CSV-Export, Drucken

## Datenschutz

- Läuft offline, installierbar über „Zum Home-Bildschirm“ (iOS) bzw. „App installieren“ (Android)
- Kein Server, kein Konto, keine Statistik: Der Stand liegt nur lokal im Browser
- Beim Senden stecken die Ergebnisse im Teil des Links nach dem `#`; dieser Teil wird vom Browser nicht an den Webserver übertragen

Designed by Thomas Kullmann
