# PWA-Toolpoint-com

Dieses Repo enthält **keine App**. Es ist nur die Weiterleitung von
`pwa-toolpoint.com` auf die eine echte Adresse:

> **https://pwa-toolpoint.de**

## Warum ein eigenes Repo

GitHub Pages erlaubt **eine** eigene Adresse pro Repo. Die `.de` hängt am Repo
`PWA-Toolpoint`. Damit die `.com` dorthin zeigt, braucht sie ein eigenes kleines
Repo, das nichts tut außer weiterzuleiten.

## Was drin ist

| Datei | Zweck |
|---|---|
| `index.html` | Weiterleitung: `meta refresh` (ohne JavaScript) + `location.replace` (mit Pfad) + `canonical` |
| `404.html` | derselbe Weg für jeden anderen Pfad — GitHub Pages liefert diese Datei, wenn nichts passt |
| `.nojekyll` | schaltet Jekyll ab; die Dateien werden unverändert ausgeliefert |

Der Pfad reist mit: `pwa-toolpoint.com/impressum.html` landet auf
`pwa-toolpoint.de/impressum.html`, nicht auf der Startseite.

## Einrichtung (einmalig)

1. **Bei INWX** für `pwa-toolpoint.com` setzen:
   - vier `A`-Einträge auf `@` → `185.199.108.153`, `185.199.109.153`,
     `185.199.110.153`, `185.199.111.153`
   - ein `CNAME` auf `www` → `lausiklauskn-png.github.io.`
2. **Hier im Repo** unter *Settings → Pages → Custom domain* `pwa-toolpoint.com`
   eintragen. GitHub legt dann selbst eine `CNAME`-Datei an.
3. Sobald das Zertifikat da ist: *Enforce HTTPS* anhaken.

---

## Rechte

Rechteinhaber ist Klaus Nitzsche. Welche Lizenz gilt und welche Rolle die
KI-Werkzeuge hatten, steht in [`RECHTE.md`](RECHTE.md); der Lizenztext in
[`LICENSE`](LICENSE).
