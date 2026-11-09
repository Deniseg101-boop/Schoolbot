# Schoolbot

Foto einer Hausaufgabe hochladen → die App löst sie mit einem kostenlosen Bild-Modell von OpenRouter und zeigt das Ergebnis in zwei Tabs:

- **✅ Lösung** – nur die Ergebnisse
- **💡 Erklärung** – Schritt-für-Schritt-Vorgehensweise

## Benutzen

1. Kostenlosen API-Key auf <https://openrouter.ai/keys> erstellen.
2. `index.html` im Browser öffnen (oder `python3 -m http.server` und <http://localhost:8000>). Kein Build nötig.
3. Key unter ⚙️ Einstellungen eintragen, Foto wählen/einfügen/aufnehmen, „Lösen“ drücken.

Die App sucht automatisch kostenlose Modelle mit Bild-Eingabe (`:free`) und probiert mehrere durch, falls eins ausgelastet ist. Optional kann ein festes Modell eingetragen werden.

**Hinweis:** OpenRouter-Gratismodelle sind nicht wirklich unbegrenzt – es gibt Anfragelimits pro Minute/Tag (mehr nach einmaligem Aufladen von ein paar $). Der Key bleibt nur im Browser (localStorage). KI-Lösungen können falsch sein – bitte gegenprüfen.
