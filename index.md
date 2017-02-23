### Modèle de mise en page.
Ce modèle de mise en page pour les thèses de doctorat soutenues à Aix Marseille Université propose un ensemble de fichiers LaTeX commentés, prêt à être compilés dont une classe LaTeX [.cls].

La page de titre a obtenu l'approbation du Collège Doctoral Aix-Marseille Université.

### Distribution LaTeX

La distribution LaTeX utilisée/recommandée est la [TeX Live](http://www.tug.org/texlive/acquire-netinstall.html).

### Conformation du fichier

Lors du dépôt légal de votre thèse, le fichier pdf compilé avec pdflatex peut être rejeté comme non conforme par la service [Facile](https://facile.cines.fr/) pour archivage au CINES. Vous pouvez le conformer avec une simple commande ghostscript.

```
gs -sDEVICE=pdfwrite -dCompatibilityLevel=1.5 -dNOPAUSE -dQUIET -dBATCH -sOutputFile=these-valide.pdf these.pdf
```