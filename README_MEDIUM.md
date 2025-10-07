zoran-feynman-sample est un dépôt d'exemple conçu pour démontrer l'intégration d'une "capsule" conceptuelle — ici dédiée à Richard Feynman — dans une infrastructure de publication et d'automatisation destinée aux agents (ex : RUBE). Le dépôt contient :

1. README principal structuré pour usage humain et machine.
2. README_SHORT et README_MEDIUM — optimisés pour Zenodo, GitHub Releases et indexation.
3. feynman_capsule.md — capsule glyphique compacte, pensée pour être décodée par pipelines IA/IA (injecteurs GlyphNet).
4. CITATION.cff & DOIS.md — métadonnées prêtes à l'emploi pour la reproductibilité académique.
5. Exemple de code `src/example.py` pour validation CI simple.

**But :** faciliter la rapidité de déploiement (clone → push) et fournir un point d'entrée standardisé aux workflows Zoran. Les métadonnées incluent DOIs placeholders et contacts. Le template respecte la licence MIT et intègre des conventions Zoran (injecteur, question benchmark obligatoire). À usage immédiat : fork, remplir `<REMOTE_URL>` et pousser. Pour toute intégration avancée (C2PA signatures, SBOM CycloneDX, Sigstore/Rekor), voir annexes projet Zoran.
