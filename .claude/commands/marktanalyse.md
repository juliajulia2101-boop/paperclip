---
description: Startet den Marktforschungs-Agenten marktforschung-kueche mit einer Frage (KI zur richtigen Nutzung von Küchengeräten)
argument-hint: "<Marktforschungsfrage>"
---

Starte den Subagenten **marktforschung-kueche** mit dem Agent-Tool
(`subagent_type: "marktforschung-kueche"`) und übergib ihm diese Frage:

> $ARGUMENTS

Wenn keine Frage angegeben wurde, nutze die Standardfrage:
„Welche Märkte und Zielgruppen sind für KI-gestützte Küchengeräte zur richtigen
Gerätenutzung aktuell am vielversprechendsten, und in welcher Lebenszyklusphase
befindet sich der Markt?“

Gib dem Agenten zusätzlich mit, dass er:
- seinem vollständigen Arbeitsablauf folgt (Rechercheplan, Websuche, Volltext-Quellen,
  Interview-Abgleich, Selbstprüfung)
- den Bericht in `marktforschung-ki-kueche/berichte/` mit dem heutigen Datum im
  Dateinamen speichert

Warte auf das Ergebnis. Gib danach auf Deutsch den Pfad des Berichts, die
Kernaussagen, die Lebenszyklus-Einordnung und die Einschränkungen aus, die der
Agent meldet.
