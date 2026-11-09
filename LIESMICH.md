# Lieslo-Website

Adresse: https://lieslo-app.github.io (Englisch, Deutsch unter `/de/`)
Datenschutz: https://lieslo-app.github.io/en/privacy.html (Englisch) · https://lieslo-app.github.io/datenschutz.html (Deutsch)
Impressum: https://lieslo-app.github.io/en/legal-notice.html (Englisch) · https://lieslo-app.github.io/impressum.html (Deutsch)

Die Seite liegt bei GitHub Pages (Organisation `lieslo-app`, Repository `lieslo-app.github.io`, öffentlich).
Hier darf nichts Geheimes hinein: kein Code der App, keine Schlüssel, keine Passwörter.

## So änderst du die Website

1. Datei in diesem Ordner ändern (z. B. `index.html`). Am einfachsten: Claude Code darum bitten.
2. PowerShell in diesem Ordner öffnen und eingeben:

   ```
   git add -A
   git commit -m "Kurz beschreiben, was geändert wurde"
   git push
   ```

3. Nach 1–2 Minuten ist die neue Fassung online. Im Browser neu laden (falls alt: Strg + F5).

## Gut zu wissen

- **Englisch ist Standard.** Jede Seite gibt es einzeln je Sprache, der Knopf oben rechts wechselt zum Gegenstück.
  Englisch: `index.html`, `en/help.html`, `en/privacy.html`, `en/legal-notice.html`, `404.html`.
  Deutsch: `de/index.html`, `hilfe.html`, `datenschutz.html`, `impressum.html`.
  Änderungen an Hilfe, Datenschutz oder Impressum immer in **beiden** Sprachen machen.
- Diese Adressen öffnet die App 1.5.2 fest, nicht umbenennen: `datenschutz.html`, `datenschutz.html#en`,
  `hilfe.html`, `en/help.html`. `#en` leitet ein Mini-Skript in `datenschutz.html` auf `en/privacy.html` weiter
  (genauso `impressum.html#en`). `en/index.html` leitet nur noch auf `/` weiter.
- Persönliche Angaben: im Impressum einmal am Seitenende, in der Datenschutzerklärung als letzter Abschnitt
  „Verantwortlicher“ / „Controller“ (ohne Telefon). E-Mail/Telefon als HTML-Zeichen-Codes schreiben,
  Impressum und Datenschutz (beide Sprachen) haben `noindex`. In der englischen Fußzeile heißt der Link
  „Legal notice (Impressum)“, damit deutsche Besucher es sofort finden.
- Bei Änderungen der App (Berechtigungen, Speicherdauer, Menünamen) auch Hilfe und Datenschutz anpassen
  und in der Datenschutzerklärung das Datum „Stand“ aktualisieren.
- Die Commits laufen unter dem Namen „Lieslo“ mit der anonymen GitHub-Adresse, nicht mit deiner privaten E-Mail.
