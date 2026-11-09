# automatiserPME

Site statique de comparatifs d'outils d'automatisation pour PME, optimisé SEO + GEO (Generative Engine Optimization).

## Structure
- `site/` : le site statique servi par Vercel (racine de déploiement).
  - `index.html` : page d'accueil
  - `n8n-vs-make-pme.html` : comparatif pilote
  - `style.css` : styles
  - `llms.txt` : résumé machine-readable pour les moteurs génératifs (IA)
  - `sitemap.xml`, `robots.txt` : SEO + autorisation explicite des bots IA
- `vercel.json` : config de déploiement (répertoire statique)

## Déploiement
Site 100 % statique, aucun build. Vercel sert directement `site/`.

## Optimisation GEO
- Réponse directe en tête d'article (bloc extrait par les IA)
- Données structurées JSON-LD (Article + FAQPage)
- llms.txt (encore peu répandu, fort différenciateur)
- robots.txt autorisant explicitement GPTBot, PerplexityBot, ClaudeBot, Google-Extended
- Contenu neutre, factuel, daté, sources officielles = source citable
