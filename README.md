# IMT-Statistiques

Analyse et modélisation statistiques de simples jeux de de données.

Devoir-Maison : 8

Professeur : Safouana Stabiou

## Auteurs

Vincent Escoffier, Adrien Jallais, Théo Martel, Louis Muzellec.

## Dossiers

+ "Rmd" - fichiers R markdown.
+ "R" - fichiers de script R supplémentaires.
+ "data" - données que nous téléchargeons à partir d'archives publiques.
+ "output" - données générées dans cette classe.
+ "images" - fichiers d'images.

## Let's go

### Installation

Commencez par [préparer votre ordinateur](https://www.middleprofessor.com/files/applied-biostatistics_bookdown/_book/appendix-1-getting-started-with-r.html).
Puis installez les packages suivants à partir de la console R :

```R
# Install from CRAN
## Rtools
install.Rtools()
## code style stuff
install.packages('styler')
install.packages('lintr')
## dev tools
install.packages("tidyverse")
## markdown stuff
install.packages("knitr")
install.packages("rmarkdown") 
install.packages('tinytex')
# Install TinyTeX
tinytex::install_tinytex()
```

### Lancement

Pour ouvrir le projet, double-cliquez sur *IMT-Statistiques.Rproj*.
Lorsque la session est terminée, quittez R Studio. Si une fenêtre contextuelle vous demande d'enregistrer l'espace de travail, cliquez sur "Non". 

## Références pédagogiques

- Fiche de cours : [wikistat](http://wikistat.fr/)
- Visualisations intéractives
  - générale :  [seeing-theory](https://seeing-theory.brown.edu/)
  - intervalles de confiance : [rpsychologist](https://rpsychologist.com/viz)
- Rédaction en markdown : [Analyses et modélisation des données écologiques](https://pmarchand1.github.io/ECL7102/)

## Méthodologie

La démarche générale qui sera suivie pour la réalisation des tests statistiquse pourra se décomposer en 7 étapes :
1. Poser un modèle : quelle(s) variables sont étudiées ? Quelles sont leur loi ? Comment traduire la question en terme de paramètres du modèle ?
2. Formulation des hypothèses H0/H1.
3. Choix d'une statistique de test et détermination de sa loi sous H0.
4. Choix du risque de première espèce α (appelé aussi niveau) et dé?nition de la zone de rejet
5. Calcul de la valeur observée de la statistique
6. Calcul de la p-value
7. Conclusion statistique (rejet ou non rejet de H0) et biologique (réponse à la question posée)
