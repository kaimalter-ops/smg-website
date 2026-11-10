# Spider Murphy Gang – Website (Demo)

Statische Website der Spider Murphy Gang, gebaut von CodeNova Labs. Der Blog kommt über das Einbettungs-Skript von CodeNova Blog (`https://blog.codenovalabs.net/embed.js`, siehe `blog.html`).

- Hosting: Vercel, Team „myinsta“, Projekt `smg-website`, verbunden mit GitHub `kaimalter-ops/smg-website`. Push auf `main` = live, andere Branches = Vorschau. Kein Build-Schritt.
- Bisher lag die Demo auf Alfahosting unter `spidermurphygang.ubxplanner.com`. Stand dieses Repos = Live-Stand dort am 10.11.2026.

## Später: Domain des Kunden umstellen
1. Domain im Vercel-Projekt unter Settings → Domains hinzufügen (mit und ohne `www`).
2. Beim Provider des Kunden nur die Web-Einträge ändern: `www` als CNAME, die Hauptdomain als A-Eintrag, beides mit den Werten, die Vercel anzeigt. **Nameserver und MX-Einträge (E-Mail) nicht anfassen.**
3. In CodeNova Blog im Bereich der SMG unter „Einbindung“ die Blog-Adresse auf die neue Domain ändern (Sitemap, RSS, Canonical und Teilen-Links hängen daran).
4. Die alte Demo-Adresse auf die neue Domain weiterleiten.
