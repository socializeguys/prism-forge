# PRISM FORGE – Crystal Cascade

Ein im Browser spielbares Match-3-Game mit sechs Spielmodi, kombinierbaren Spezialsteinen, sichtbaren Laser-, Flug- und Explosionsanimationen, Soundeffekten und lokalen Highscores.

**Spieladresse (nach Aktivierung von GitHub Pages):** https://socializeguys.github.io/prism-forge/

## GitHub Pages aktivieren

1. Im Repository **Settings → Pages** öffnen.
2. Unter **Build and deployment** als Source **Deploy from a branch** auswählen.
3. Branch **main**, Verzeichnis **/(root)** auswählen und **Save** anklicken.
4. Nach erfolgreicher Veröffentlichung die Spieladresse in Safari öffnen. Mit **Teilen → Zum Home-Bildschirm** installieren.

## Technik und Datenschutz

Die Spielmechanik befindet sich in der `index.html`, ohne externes JavaScript. Die Audiosounds werden über die Web-Audio-API erzeugt. Die Highscores werden ausschliesslich im jeweiligen Browser gespeichert; es gibt keine übergreifende Online-Rangliste. `manifest.webmanifest`, `icon.svg` und `service-worker.js` stellen Home-Bildschirm- und Offline-Funktionen bereit.
