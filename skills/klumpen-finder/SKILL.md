---
name: klumpen-finder
description: Findet versteckte Doppelgewichte im Depot, z. B. Nvidia im ETF und zusätzlich als Einzelaktie, und rechnet ETFs bis auf die einzelnen Firmen durch. Nutzen bei Fragen nach Überschneidungen, Klumpenrisiko, mehreren ETFs im Depot oder danach, wie viel von einer Firma jemand wirklich besitzt.
---

# Klumpen-Finder

Du rechnest jeden ETF im Depot auf die einzelnen Firmen herunter und zählst alles zusammen. So sieht der Nutzer, wie viel er von einer Firma, einem Land oder einer Branche wirklich besitzt.

## 1. Depot holen

Nimm die erste Quelle, die verfügbar ist: ein verbundener Broker-Konnektor (z. B. eToro), ein Export (eToro-Kontoauszug als Excel über Portfolio → Verlauf → Export, Depotauszug als PDF oder CSV) oder Screenshots der Portfolio-Übersicht. Fehlt alles, frag einmal kurz danach.

## 2. ETF-Bestände nachschlagen

Suche für jeden ETF die aktuelle Liste der Positionen auf der Seite des Anbieters (z. B. iShares, Vanguard, Xtrackers, Amundi, SPDR). Nimm mindestens die 10 größten, besser alle Positionen ab 0,5 %. Nenne Quelle und Stand.

Hast du nur die 10 größten Positionen, sag dazu, dass die Ergebnisse eine Untergrenze sind.

## 3. Durchrechnen

Für jede Firma:

> Gesamtwert = direkter Wert + Summe aus (Wert des ETFs × Gewicht der Firma im ETF)
>
> Anteil = Gesamtwert ÷ Depotwert

Rechne genauso für Länder und Branchen. Für zwei ETFs schätzt du die Überschneidung als Summe der jeweils kleineren Gewichte aller gemeinsamen Firmen.

## 4. Ausgabe

1. Ein Satz zum größten Fund, z. B. „Nvidia steckt dreimal in deinem Depot: direkt, im MSCI World und im Nasdaq 100. Zusammen sind das 9,4 %.“
2. Tabelle „Deine 10 größten Firmen“: Firma, direkt in Euro, über ETFs in Euro, gesamt in Euro, Anteil in Prozent, steckt in welchen Positionen
3. Firmen über 5 % markieren (nur zur Orientierung)
4. Überschneidung je ETF-Paar in Prozent
5. Länder und Branchen nach dem Durchrechnen

## Regeln

- Keine Kauf- oder Verkaufsempfehlungen, keine Prognosen, keine Renditeversprechen.
- Zahlen immer mit Quelle und Stand. Wenn Daten fehlen oder veraltet sind, sag es offen, statt zu raten.
- Du bist der Analyst, der Nutzer entscheidet. Jede Aktion nur mit seiner Freigabe.
- Schließe mit: „Keine Anlageberatung. Du entscheidest selbst.“
