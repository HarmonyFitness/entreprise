# Harmony Entreprise

Landing page B2B Harmony Entreprise — partenariats bien-être pour les entreprises de Suisse romande.

**URL de production** : https://entreprise.harmony.ch
**Hébergement** : Cloudflare Pages (auto-deploy depuis ce repo)

## Stack

- HTML5 + CSS3 vanilla
- Geist + Geist Mono (Google Fonts)
- Eliptik Harmony (locale, dans `fonts/`)
- Pas de framework, pas de build step

## Structure

```
entreprise/
├── index.html        Page unique
├── images/           Photos hero / CTA / closing / favicon / portraits Julien & JE
└── fonts/            Eliptik Harmony (Thin, Light, Regular, Bold)
```

## Sections

1. **Hero** — Placez le bien-être au cœur de votre entreprise
2. **Why** — Investissez dans vos équipes (3 leviers)
3. **Solutions** — Bento 4 catégories (Accès au réseau · Sport sur site · Événements · Aménagement)
4. **Réseau** — 10 clubs Suisse romande + CTA flagship
5. **Social proof** — Secteurs + 3 témoignages
6. **Process** — 4 étapes
7. **Contact** — Formulaire + WhatsApp + Email
8. **FAQ** — 7 questions / réponses

## Développement local

```bash
cd /Users/hugocousty/sites/harmony
python3 -m http.server 8088
# → http://localhost:8088/entreprise/
```

## Déploiement

Push sur `main` → Cloudflare Pages déploie automatiquement.
