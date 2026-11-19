# Bahn 13 – interaktive Spendenaktion

Frontend-Prototyp einer Spendenfortschrittsanzeige für Bahn 13 des Golf-Club Bergisch Land. Ein Golfball bewegt sich entlang einer SVG-Strecke; vier Bunker markieren Zwischenziele.

## Funktionen

- Spendenstand per Schieberegler oder Beispielwert auswählen.
- Fortschritt, Restbetrag und nächsten Meilenstein anzeigen.
- Golfball entlang eines SVG-Pfads animieren.
- Eine Beispielrunde abspielen und pausieren.
- Spendenziel und aktuellen Stand in einem Dialog ändern.
- Beträge im deutschen Währungsformat anzeigen.

## Lokal starten

Repository herunterladen und `index.html` im Browser öffnen. Keine Installation, keine Abhängigkeiten und kein Build-Schritt erforderlich.

## Dateien und Techniken

- `index.html`: Seitenstruktur und SVG-Bahn.
- `styles.css`: Gestaltung, mobile Layouts, Fokuszustände und Reduced-Motion-Stile.
- `script.js`: DOM-Ereignisse, Fortschrittsberechnung und Animation mit requestAnimationFrame.
- `assets/`: Bahngrafik und Clublogo aus dem gelieferten Prototyp.

## Demo und Grenzen

Dies ist eine Simulation. Es werden keine echten Spenden erfasst, keine Zahlungen ausgelöst und keine Werte dauerhaft gespeichert. Nach dem Neuladen gelten wieder die Beispielwerte. Es gibt kein Backend und keine Anbindung an einen Zahlungsanbieter. Änderungen in diesem Repository aktualisieren keine bereits gehostete Website automatisch.
