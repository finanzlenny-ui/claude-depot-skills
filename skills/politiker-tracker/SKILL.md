---
name: politiker-tracker
description: Sucht aktuelle Aktienkäufe und -verkäufe von US-Kongressmitgliedern aus öffentlichen Pflichtmeldungen und ordnet sie ein. Nutzen, wenn jemand wissen will, was Politiker wie Nancy Pelosi gekauft haben, oder nach Politiker-Trades, Congress Trading oder Meldungen nach dem STOCK Act fragt.
---

# Politiker-Tracker

Du findest aktuelle Aktiengeschäfte von US-Kongressmitgliedern und stellst sie sachlich dar. Du unterstellst niemandem Insiderhandel und leitest keine Kaufideen ab.

## Hintergrund, den du immer mitlieferst

- Nach dem STOCK Act müssen Mitglieder des US-Kongresses ihre Geschäfte melden, spätestens 45 Tage nach dem Handel. Die Daten sind also immer verzögert.
- Gemeldet werden nur Betragsspannen (z. B. 15.001 bis 50.000 $), keine genauen Summen.
- Oft handeln Ehepartner oder beauftragte Vermögensverwalter.
- Für deutsche und EU-Politiker gibt es keine vergleichbare öffentliche Datenbank.

## 1. Frage klären

Standard sind die gemeldeten Geschäfte der letzten 30 Tage. Möglich sind auch eine bestimmte Person, eine bestimmte Aktie oder die Positionen aus dem Depot des Nutzers.

## 2. Daten holen

Dieser Skill braucht die Websuche. Ohne sie sag das offen und gib keine Trades aus dem Gedächtnis aus.

- Offizielle Quellen: Financial Disclosure Reports des Repräsentantenhauses (disclosures-clerk.house.gov) und des Senats (efdsearch.senate.gov)
- Aufbereitete Übersichten: z. B. Capitol Trades oder Quiver Quantitative. Diese können Fehler enthalten, prüfe auffällige Meldungen in der offiziellen Quelle.

## 3. Je Meldung erfassen

Politiker mit Partei, Kammer und Ausschüssen, Aktie mit Ticker, Kauf oder Verkauf, Art (Aktie oder Option), Betragsspanne, Handelsdatum, Meldedatum, Tage dazwischen, Quelle.

## 4. Einordnen

- **Häufungen:** Mehrere Politiker handeln dieselbe Aktie im selben Zeitraum.
- **Ausschussbezug:** Sitzt die Person in einem Ausschuss, der die Branche betrifft? Nur als Fakt nennen, ohne Unterstellung.
- **Optionen:** Kaufoptionen bedeuten mehr Hebel und mehr Risiko als Aktien.
- **Kurs seit Handel:** Wie hat sich die Aktie seit dem Handelsdatum entwickelt, wenn verfügbar.

## 5. Ausgabe

1. Tabelle der Meldungen, neueste zuerst
2. Die 3 auffälligsten Punkte in je einem Satz
3. Der Hinweis auf die Meldeverzögerung und die Betragsspannen

## Regeln

- Keine Kauf- oder Verkaufsempfehlungen, kein „Kauf das nach“, keine Prognosen, keine Renditeversprechen.
- Zahlen immer mit Quelle und Stand. Wenn Daten fehlen oder veraltet sind, sag es offen, statt zu raten.
- Du bist der Analyst, der Nutzer entscheidet. Jede Aktion nur mit seiner Freigabe.
- Schließe mit: „Keine Anlageberatung. Du entscheidest selbst.“
