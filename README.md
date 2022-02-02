## Les Infrastructure de Recharge de Véhicule Électrique en île-de-France 
## ![alt tag](https://static1.caroom.fr/guide/wp-content/uploads/2020/10/temps-recharge-voiture-electrique-1000x484.jpg)
## Sommaire :
1. [Introduction et Objectif](#Explication du choix du sujet et de l'utilité e cette visualisation)
2. [Repérage des différentes structures & Présentation de l'ensemble des données](#Pouvoir repérer les bornes et les magasins en distingant les deux avec une légende et des icones)


## Introduction et Objectif
  Dans notre vie quotidienne en France, nous trouvons de plus en plus un difficulté de vivre, c'est pourquoi certains ont préféré l'utilisation des voitures électriques au détriment des autres qui coutent cheres niveau essence, gazoil ... 
Donc c'est à partir de cette visualisation que les possesseurs des voitures électriques puissent se reperer afin de bien alimenter leurs vehicules des charges électriques nécessaires, pour faire bien j'ai décidé donc de reprer en plus des bornes de charges, les locaux commerciaux disponibles aux alentours, cela va permettre à n'importe quelle personne de recharcher son vehéicule tout en faisant les courses et les différents magasins.

## Repérage des différentes structures & Présentation de l'ensemble des données
Donc, nous constatons que si n jour, on veut faire des courcses avec une voiture électrique, les meilleurs endroits sont ceux ou les deux couleurs rouge et bleu se croisent, dans le cas ou les deux couleurs ne se croisent pas ou elles sont éloignées, l'un des deux endroits n'est pas dispopnible (Bornes ou centres commérciaux).
<iframe frameborder="0" width="800" height="600" src="https://data.opendatasoft.com/map/embed/irve0/?&static=false&scrollWheelZoom=false"></iframe>

Pour obtenir l'adressre, il suffit de zoomer sur un endroit de la carte, ou tout simplement de rpérer l'endroit dans la visualisation des tableaux qui suit, cela nous permet aussi d'avoir plus de formations sur le types des commerces à trouver, donner la géolocalisation, ainsi que les différents éléments de l'adresse postale :

Données des différents commerces selon la localisation et la disponibilité : 
<iframe src="https://data.opendatasoft.com/explore/embed/dataset/les-commerces-par-commune-ou-arrondissement-base-permanente-des-equipements@datailedefrance/table/?sort=departement&static=false&datasetcard=false" width="800" height="600" frameborder="0"></iframe>

Données des différentes bornes de recharge et localisation des bornes : 
<iframe src="https://data.opendatasoft.com/explore/embed/dataset/fichier-consolide-des-bornes-de-recharge-pour-vehicules-electriques-irve@public/table/?q=ile%20de%20france&geofilter.distance=49.48008162022706,1.7578125,148475.77503457383&location=8,48.70909,2.21649&basemap=jawg.streets&static=false&datasetcard=false" width="800" height="600" frameborder="0"></iframe>


<iframe style="width: 80vw; height: 50vh; border: none;" src="https://query.wikidata.org/embed.html#%23Restaurants%0ASELECT%20%3Fitem%20%3Fadresses%20%3Fouverture%20%3Ffermeture%20%3Ftel%20WHERE%0A%7B%0A%3Fitem%20wdt%3AP31%20wd%3AQ22687.%0A%3Fitem%20wdt%3AP17%20wd%3AQ142%0AOPTIONAL%20%7B%0A%3Fitem%20wdt%3AP6375%20%3Fadresses.%0A%3Fitem%20wdt%3AP8626%20%3Fouverture.%0A%3Fitem%20wdt%3AP8627%20%3Ffermeture.%0A%3Fitem%20wdt%3AP1329%20%3Ftel%20.%0A%7D%0A%20%20SERVICE%20wikibase%3Alabel%20%7Bbd%3AserviceParam%20wikibase%3Alanguage%20%22fr%22%7D%0A%7D%0A%0AORDER%20BY%20DESC%20%28%3Fadresses%29" referrerpolicy="origin" sandbox="allow-scripts allow-same-origin allow-popups" ></iframe>
