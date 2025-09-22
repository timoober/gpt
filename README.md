# GPT GitHub Pages

Dieses Repository stellt eine Jekyll-basierte Landing-Page für GitHub Pages bereit.

## Voraussetzungen

- Ruby >= 3.0
- [Bundler](https://bundler.io/) (`gem install bundler`)

## Lokale Vorschau

```bash
bundle install
bundle exec jekyll serve
```

Anschließend erreichst du die Seite unter <http://localhost:4000>.

## Anpassen

- Passe Seitentitel und Beschreibung in [`_config.yml`](./_config.yml) an.
- Bearbeite das Layout unter [`_layouts/default.html`](./_layouts/default.html).
- Aktualisiere Inhalte in [`index.html`](./index.html) und ergänze eigene Seiten im Wurzelverzeichnis.
- Style-Anpassungen nimmst du in [`assets/css/main.css`](./assets/css/main.css) vor.

## Deployment

Aktiviere GitHub Pages für den `main`-Branch (Ordner `/`) – GitHub baut die Seite automatisch mit Jekyll.
