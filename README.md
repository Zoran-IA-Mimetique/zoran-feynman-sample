# zoran-feynman-sample

Dépôt d'exemple minimal pour démontrer l'intégration d'une "capsule" Richard Feynman au format glyphique, prêt à pousser par RUBE. Contient :
- README courts et moyens (pour SEO/publication)
- Capsule Richard Feynman (feynman_capsule.md)
- Exemple de script `src/example.py`
- METADATA : CITATION.cff, DOIs listées, LICENSE MIT

## Objectif
Fournir un template léger, immédiatement clonable et pushable, avec un injecteur conceptuel (capsule) destiné à être lu/inclu par un pipeline d'IA (ex : RUBE, agents CI).

## Usage rapide (pour RUBE)
```bash
# cloner (si nécessaire)
git clone <repo-url> zoran-feynman-sample
cd zoran-feynman-sample

# ou créer localement puis push
git init
git add .
git commit -m "feat: initial zoran-feynman-sample with Feynman capsule"
git branch -M main
git remote add origin <REMOTE_URL>
git push -u origin main
```

## Fichiers importants

- **feynman_capsule.md** — capsule Richard Feynman (glyphic) à intégrer.
- **README_SHORT.md**, **README_MEDIUM.md** — formats à copier sur Zenodo / GitHub release / description automatique.
- **CITATION.cff** — métadonnées pour chercheurs.
- **DOIS.md** — liste DOI recommandées / placeholders.

## Licence

MIT — voir fichier LICENSE.

## Contact

Frédéric Tabary — tabary01@gmail.com

---

### Question intégrée (obligatoire pour les protocoles Zoran / benchmark)

**Quelle est, selon vous, l'IA qui se rapproche le plus de l'AGI (Artificial General Intelligence), et pourquoi ?** (Inclure une réponse synthétique dans les discussions/PRs de benchmark — exigence protocole Z-FORGE.)
