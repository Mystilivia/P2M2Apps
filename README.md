## Description
P2M2Apps est un package R créé dans le but de fournir des outils d'analyses statistiques à la plateforme d'analyse métabol(om)ique [P2M2](https://www6.rennes.inra.fr/igepp/L-IGEPP/Plateformes/P2M2). Pour le moment, elle contient une application [shiny](https://shiny.rstudio.com/) en cours de développement qui permet de réaliser les calculs associés aux analyses ciblées utilisant au moins un standard externe. Elle permet également de réaliser une normalisation par rapport à un standard interne. Les calculs sont basés sur le document suivant : [Quantitative & Qualitative HPLC](https://www.google.fr/url?sa=t&rct=j&q=&esrc=s&source=web&cd=2&cad=rja&uact=8&ved=0ahUKEwjQn7DrlInTAhXDXBoKHZofDBsQFggpMAE&url=https%3A%2F%2Fwww.researchgate.net%2Ffile.PostFileLoader.html%3Fid%3D56d4cc08217e201319573a57%26assetKey%3DAS%253A334600736919553%25401456786440271&usg=AFQjCNHNLCprEIvago_WJrgfO6LA83BlRw&sig2=oaQ-F4pMpj13_8lO23P9BA).

## Installation
l'installation du package P2M2Apps nécessite l'utilisation du package [devtools](https://cran.r-project.org/web/packages/devtools/index.html). Pour réaliser l'installation du package et de toutes ses dépendances, ouvrez R ou RStudio et lancer les commandes suivantes :

```{R}
install.packages('devtools')
devtools::install_github('Mystilivia/P2M2Apps')
```

Le logiciel va lancer l'installation de tous les packages nécessaires pour utiliser l'application, vérifier qu'il n'y a pas d'erreurs. S'il y a des erreurs, essayer de lancer R en mode administrateur et recommencer.

## Utilisation
Une fois le package installé, vous pouvez lancer l'installation en utilisant la commande suivante dans R :
```{R}
P2M2Apps::TargetedApp()
```

L'application va s'ouvrir dans votre navigateur web, et vous n'avez plus qu'à suivre les instructions.

