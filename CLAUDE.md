# PWA-Toolpoint-com — Sitzungs-Anker

**Hier liegt keine App.** Dieses Repo ist nur die Domain `pwa-toolpoint.com`, die auf
**`pwa-toolpoint.de`** weiterleitet. Gebaut wird im Repo `PWA-Toolpoint`.

## Was hier leicht kaputtgeht

- **`CNAME` nicht anfassen** — sie hält die Domain. Ohne sie zeigt die Adresse ins Leere.
- Wer hier Inhalt ergänzt, baut eine zweite Wahrheit neben `pwa-toolpoint.de` auf.
  Im Zweifel: Klaus fragen.

## Netzweit

Freibrief zum Selbst-Mergen · Gerätename · frisch von `origin/main` vor jeder Arbeit ·
Ton · kein PII · Ehrlichkeit stehen **einmal** in
**[`Sage-Protokol/docs/NETZWEIT.md`](https://github.com/lausiklauskn-png/Sage-Protokol/blob/main/docs/NETZWEIT.md)**.

```bash
git fetch origin --quiet && git checkout -B <branch> origin/main
git push -u origin refs/heads/<branch>:refs/heads/<branch>
git diff --stat origin/main origin/<branch>     # leer = der PR wäre leer
```
