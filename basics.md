---
title: Basics
layout: default
permalink: /basics
nav_order: 2
---
# Zusätzliche Regeln

Hauptsächlich wird nur die folgende Regel ergänzt:

> Jede Karte, die abgelegt wird, muss ausgespielt werden.

Dies führt zu den im folgenden spezifizierten Konkretisierungen bestehender Regeln:

## Status eines Spielers

Am Ende von jedem Spielzug wird für alle Spieler überprüft, ob sie sich noch im
Spiel befinden.
Dabei gibt es folgende Fälle:

- Wer noch eine Handkarte hat, ist weiterhin _im Spiel_.
- Wer keine Handkarte mehr hat und nicht vor dem Ausscheiden durch eine Zofe geschützt wird, ist _ausgeschieden_.
- Wer keine Handkarte mehr hat, jedoch vor dem Ausscheiden durch eine Zofe geschützt wird, ist _semi-ausgeschieden_.

Hat man während eines laufenden Zuges keine Handkarte auf der Hand, so ist man _semi-ausgeschieden_.
Ob man tatsächlich ausscheidet, kann sich jedoch nur zum Ende eines Zuges entscheiden.

## Quasi-Karte

Während man semi-ausgeschieden ist, hat man eine gedankliche _Quasi-Karte_ auf der Hand.
Diese Karte hat entweder Wert
- 0, falls man keine Grafen im eigenen Ablagestapel hat,
- 1, falls man einen Grafen im eigenen Ablagestapel hat, oder
- 2, falls man zwei Grafen im eigenen Abglagestapel hat.
