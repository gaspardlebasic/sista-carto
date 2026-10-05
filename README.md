# sista-carto

Fichiers cartographiques statiques du visuel Power BI « Carte choroplèthe SISTA », servis par
GitHub Pages. Régénérés par `scripts/construire_tuiles.sh` et publiés par
`scripts/deploy/publier_carto.sh` dans le dépôt de l'application SISTA ; ne pas modifier à la main.

| Fichier | Contenu |
|---|---|
| `communes.pmtiles`, `epci.pmtiles`, `departements.pmtiles`, `regions.pmtiles` | contours des territoires (INSEE), propriété `code_territoire` |
| `libelles.pmtiles` | un point d'ancrage de libellé par territoire |
| `fond.pmtiles` | pays et lacs (Natural Earth, domaine public) |
| `glyphes/` | Source Sans 3 (SIL Open Font License) au format MapLibre |
| `cadrages.json` | emprise de chaque territoire, pour cadrer la carte |
