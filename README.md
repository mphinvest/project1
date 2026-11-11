# Agent Office

Ein holografischer Leitstand im HUD-Stil, in dem sechs KI-Agenten als kleine Figuren zusammenarbeiten:
Lead, Researcher, Designerin, Coder, Tester und Reviewerin. Gib eine Aufgabe ein
und schau zu, wie sie planen, sich Nachrichten schicken, Ergebnisse übergeben,
Bugs finden und am Ende gemeinsam feiern.

## Starten

`index.html` im Browser öffnen. Keine Installation, kein Build.

## Was passiert

1. **Planung** – Ada (Lead) zerlegt die Aufgabe am Whiteboard.
2. **Kickoff** – das Team trifft sich am Tisch.
3. **Recherche** – Kip sammelt Kontext, die anderen bereiten parallel vor.
4. **Design** – Mira entwirft und bringt das Ergebnis persönlich zu Nova.
5. **Code** – Nova programmiert (mit Kaffeepause).
6. **Test** – Bo testet am Server, findet einen Bug, Nova fixt ihn.
7. **Review** – Juno prüft den Pull Request und gibt frei.
8. **Fertig** – Abschlussrunde mit Konfetti.

Datenpakete zeigen Nachrichten zwischen Agenten, HUD-Callouts zeigen, woran
jemand gerade arbeitet. Unter dem Live-Feed laufen Kennzahlen und eine
Aktivitäts-Zeitleiste mit (wer arbeitet wann, wer schickt wem was). Ein
Fokus-Panel zeigt die ausgewählte Einheit als Live-Hologramm mit Statistiken. Die Inhalte passen sich der Aufgabe an (Website, Spiel,
Datenanalyse, API oder allgemein).

Aktuell ist der Ablauf simuliert. Als nächster Schritt lassen sich die Agenten
an echte LLM-Aufrufe (z. B. die Claude API) anbinden, sodass die Sprechblasen
echte Zwischenergebnisse zeigen.
