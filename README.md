## Les Infrastructure de Recharge de Véhicule Électrique en île-de-France à proximité des lieux commerciaux (Restaurants, magasins...)
## ![alt tag](https://static1.caroom.fr/guide/wp-content/uploads/2020/10/temps-recharge-voiture-electrique-1000x484.jpg)
## Sommaire :
1. [Introduction et Objectif](#Explication du choix du sujet et de l'utilité e cette visualisation)
2. [Repérage des différentes structures & Présentation de l'ensemble des données](#Pouvoir repérer les bornes et les magasins en distingant les deux avec une légende et des icones)
3. [Prévoir les endroits qui ont le polus de bornes augmentera votre chance de trouver une borne](#Pouvoir repérer les bornes et les magasins en distingant les deux avec une légende et des icones)
4. [Les points toujours ouverts 7/7 et 24/24 et gratuites](#Repérage des bornes toujours ouvertes et gratuites) 
5. [Etude d'une ville précise](#Cela concerne les personnes habitant à proximité de sèvres et dont le trajet n'est pas long)
6. [Requêtage](#la requête wikidata permetera de trouver la localisation, connaitre le nombre d'habitants) 


## Introduction et Objectif
Dans notre vie quotidienne en France, nous trouvons de plus en plus un difficulté de vivre, c'est pourquoi certains ont préféré l'utilisation des voitures électriques au détriment des autres qui coutent cheres niveau essence, gazoil ... 
Donc c'est à partir de cette visualisation que les possesseurs des voitures électriques puissent se reperer afin de bien alimenter leurs vehicules des charges électriques nécessaires, pour faire bien j'ai décidé donc de reprer en plus des bornes de charges, les locaux commerciaux disponibles aux alentours, cela va permettre à n'importe quelle personne de recharcher son vehéicule tout en faisant les courses et les différents magasins.



## Repérage des différentes structures & Présentation de l'ensemble des données via  une carte :

Remarque : Carte filtrée en ile de France, les villes ayant le meme nom ont été évitées.

Donc, nous constatons que si un jour, on veut faire des courcses avec une voiture électrique, les meilleurs endroits sont ceux ou les deux couleurs rouge et bleu se croisent, dans le cas ou les deux couleurs ne se croisent pas ou elles sont éloignées, l'un des deux endroits n'est pas dispopnible (Bornes indispnibles ou centres commérciaux indisponibles).
<iframe frameborder="0" width="800" height="600" src="https://data.opendatasoft.com/map/embed/irve0/?&static=false&scrollWheelZoom=false"></iframe>

Pour obtenir l'adressre, il suffit de zoomer sur un endroit de la carte, ou tout simplement de rpérer l'endroit dans la visualisation des tableaux qui suit, cela nous permet aussi d'avoir plus d'informations sur le types des commerces à trouver, donner les différents éléments de l'adresse postale, notamment les données de géocalisation pour une recherche plus pratique sur le GPS.


Données des différents commerces selon la localisation et la disponibilité : 
<iframe src="https://data.opendatasoft.com/explore/embed/dataset/les-commerces-par-commune-ou-arrondissement-base-permanente-des-equipements@datailedefrance/table/?sort=departement&static=false&datasetcard=false" width="800" height="600" frameborder="0"></iframe>


Données des différentes bornes de recharge et leurs localisations : 
<iframe src="https://data.opendatasoft.com/explore/embed/dataset/fichier-consolide-des-bornes-de-recharge-pour-vehicules-electriques-irve@public/table/?q=ile%20de%20france&geofilter.distance=49.48008162022706,1.7578125,148475.77503457383&location=8,48.70909,2.21649&basemap=jawg.streets&static=false&datasetcard=false" width="800" height="600" frameborder="0"></iframe>


## Prévoir les endroits qui ont le plus de bornes augmentera votre chance de trouver une borne
Il est plus conseillé d'aller dans les endroits ou on peut trouver le plus de bornes, on a plus de chance de trouver une place dans une station à 30 bornes que dans une station à 5 bornes, surtout en région parisienne où il y a beaucoup de monde notamment avec des véhicules électriques, donc le camembert suivant permet de donner par régions (classées par ordre alphabétique en allant de la droite vers la gauche ), le nombre de bornes dans chaque ville, nous constatons qu'en région parisienne il y a beaucoup plus de bornes qu'ailleurs en ile-de-France.

<iframe src="https://data.opendatasoft.com/explore/embed/dataset/fichier-consolide-des-bornes-de-recharge-pour-vehicules-electriques-irve@public/analyze/?q=ILE%20DE%20FRANCE&refine.nbre_pdc=6&dataChart=eyJxdWVyaWVzIjpbeyJjb25maWciOnsiZGF0YXNldCI6ImZpY2hpZXItY29uc29saWRlLWRlcy1ib3JuZXMtZGUtcmVjaGFyZ2UtcG91ci12ZWhpY3VsZXMtZWxlY3RyaXF1ZXMtaXJ2ZUBwdWJsaWMiLCJvcHRpb25zIjp7InEiOiJJTEUgREUgRlJBTkNFIiwicmVmaW5lLm5icmVfcGRjIjoiNiJ9fSwiY2hhcnRzIjpbeyJhbGlnbk1vbnRoIjp0cnVlLCJ0eXBlIjoicGllIiwiZnVuYyI6IkNPVU5UIiwieUF4aXMiOiJuYnJlX3BkYyIsInNjaWVudGlmaWNEaXNwbGF5Ijp0cnVlLCJjb2xvciI6InJhbmdlLWN1c3RvbSIsInBvc2l0aW9uIjoiY2VudGVyIn1dLCJ4QXhpcyI6ImNvbW11bmUiLCJtYXhwb2ludHMiOjIwMCwidGltZXNjYWxlIjoiIiwic29ydCI6IiIsInNlcmllc0JyZWFrZG93biI6IiIsInNlcmllc0JyZWFrZG93blRpbWVzY2FsZSI6IiJ9XSwiZGlzcGxheUxlZ2VuZCI6dHJ1ZSwiYWxpZ25Nb250aCI6dHJ1ZSwidGltZXNjYWxlIjoiIn0%3D&static=false&datasetcard=false" width="800" height="600" frameborder="0"></iframe>
Les communes sont classées en ordre alphabétique en allant de guache à droite


## Les points toujours ouvetrs 7/7 et 24/24 et gratuits

Sachant que la disponibilité de la plupart des personnes n'est pas la meme, certaines travaillent et certaines personnes s'occupent de beaucoup de choses avant d'aller faire les courses ou en soirées, il faut s'y rendre aux endroits ou on ne craint pas de fermeture de bornes ni de payer, ce qui nous evitera plus de charges au quotidien, ce sont tout simplement des bornes disponibles à tous gratuitemnt et à n'importe quel moment.

<iframe src="https://data.opendatasoft.com/explore/embed/dataset/fichier-consolide-des-bornes-de-recharge-pour-vehicules-electriques-irve@public/analyze/?q=ILE%20DE%20FRANCE&refine.accessibilite=24h%2F24&dataChart=eyJxdWVyaWVzIjpbeyJjb25maWciOnsiZGF0YXNldCI6ImZpY2hpZXItY29uc29saWRlLWRlcy1ib3JuZXMtZGUtcmVjaGFyZ2UtcG91ci12ZWhpY3VsZXMtZWxlY3RyaXF1ZXMtaXJ2ZUBwdWJsaWMiLCJvcHRpb25zIjp7InEiOiJJTEUgREUgRlJBTkNFIiwicmVmaW5lLmFjY2Vzc2liaWxpdGUiOiIyNGgvMjQifX0sImNoYXJ0cyI6W3siYWxpZ25Nb250aCI6dHJ1ZSwidHlwZSI6InNjYXR0ZXIiLCJmdW5jIjoiQVZHIiwieUF4aXMiOiJuYnJlX3BkYyIsInNjaWVudGlmaWNEaXNwbGF5Ijp0cnVlLCJjb2xvciI6IiMxNDJFN0IiLCJwb3NpdGlvbiI6ImNlbnRlciJ9XSwieEF4aXMiOiJjb21tdW5lIiwibWF4cG9pbnRzIjoyMDAsInRpbWVzY2FsZSI6IiIsInNvcnQiOiIiLCJzZXJpZXNCcmVha2Rvd24iOiIiLCJzZXJpZXNCcmVha2Rvd25UaW1lc2NhbGUiOiIifV0sImRpc3BsYXlMZWdlbmQiOnRydWUsImFsaWduTW9udGgiOnRydWUsInRpbWVzY2FsZSI6IiJ9&static=false&datasetcard=false" width="800" height="600" frameborder="0"></iframe>


## Etude d'une ville précise 

Un exemple pour la ville de sèvres en région Hauts-de-seine pour des recherches plus affinés, concernant toutes les bornes à proximité des restaurants, j'avais filtré sur la région concernée avec un cercle, cela permetra d'éviter toutes les autres villes ou endroits au nom de sèvres, qui peuvent notamment se trouver hors france.

<iframe frameborder="0" width="800" height="600" src="https://data.opendatasoft.com/map/embed/commerces/?&static=false&scrollWheelZoom=false"></iframe>


## Requêtage 
 

Qui affichera le résultat suivant :

Les résultats de la requete permettent en premier lieu, par esemple à des personnes étrangères de trouver facilmeent la localisation de la commune dont dépend la ville qu'ils sohaitent visiter, deuxièmement elle permet aux personnes souhaitant faire les magasins par exemple de savoir ou se trouve la commune la moins peuplé qui évitera de ne pas trouver des points de recharges.

<iframe style="width: 80vw; height: 50vh; border: none;" src="https://query.wikidata.org/embed.html#%23Communes_%C3%AEle_de_france%0ASELECT%20%3Fitem%20%3Fpopulation%20%3Flocalisation%20%3Fnoms%20WHERE%0A%7B%0A%3Fitem%20wdt%3AP131%20wd%3AQ13917.%0AOPTIONAL%20%7B%0A%3Fitem%20wdt%3AP18%20%3Fimage.%20%23affichier%20les%20images%0A%3Fitem%20wdt%3AP1448%20%3Fnoms.%0A%3Fitem%20wdt%3AP1082%20%3Fpopulation%20.%23Nombre%20de%20personnes%20habitant%20la%20r%C3%A9gion%0A%3Fitem%20wdt%3AP625%20%3Flocalisation.%20%23Recherche%20gps%0A%7D%0A%20%20SERVICE%20wikibase%3Alabel%20%7Bbd%3AserviceParam%20wikibase%3Alanguage%20%22fr%22%7D%0A%7D%0A%0AORDER%20BY%20DESC%20%28%3Fpopulation%29" referrerpolicy="origin" sandbox="allow-scripts allow-same-origin allow-popups" ></iframe>

requête utilisée :

```sparql
#Communes_île_de_france
SELECT ?item ?population ?localisation ?noms WHERE
{
?item wdt:P131 wd:Q13917.
OPTIONAL {
?item wdt:P18 ?image. #affichier les images
?item wdt:P1448 ?noms.
?item wdt:P1082 ?population .#Nombre de personnes habitant la région
?item wdt:P625 ?localisation. #Recherche gps
}
  SERVICE wikibase:label {bd:serviceParam wikibase:language "fr"}
}

ORDER BY DESC (?population)
```
