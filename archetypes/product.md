---
title: "{{ replace .File.ContentBaseName "-" " " | title }}"
date: {{ .Date }}
draft: false
slug: "{{ .File.ContentBaseName }}"
product_type: "template"
price_eur: 12
files: ["download.zip"]
includes: ["PDF-Guide"]
requires: []
faq:
  - q: "Brauche ich Vorkenntnisse?"
    a: "Nein, kurze Anleitung ist enthalten."
  - q: "Rückgabe möglich?"
    a: "14 Tage bei Problemen."
license: "Privat, 1 Nutzer"
updated: {{ .Date }}
---

## Was du bekommst
- Übersichtliche Vorlage(n)
- Kurzanleitung (PDF)
- Beispiele

## So funktioniert’s
1. Datei öffnen
2. Felder ausfüllen
3. Fertig – Diagramme/Übersichten sind automatisch
