# Les Inégalités d'Espérance de Vie dans le Monde.

# Sommaire 

1. [La mortalité infantile à travers le monde depuis 2014](##LaMortalitéInfantile)
2. [Espérance de vie de 1817 à 2017 par pays](##EpéranceDeVieDepuis1817)
3. [Et en France alors ?](##EtEnFranceAlors)
4. [Le Revenu National Brut par habitant et l'espérance de vie](##RevenuNationalBrutParHabitantEtEspéranceDeVie.)
5. [Modification des jeux de données via OpenRefine](##ModificationDesJeuxDeDonnéesViaOpenRefine)
6. [Requête Wikidata](##RequêteWikidata)


## 1. La mortalité infantile dans le monde.

### A - Définition 

La mortalité infantile est le nombre annuel de décès d’enfants rapporté au nombre de naissances pour une populationn donnée. On parle alors de taux de mortalité infantile. Cet indicateur nous renseigne essentiellement sur le contexte sanitaire des nouveaux-nés dans un territoire. 


### B - La mortalité infantile de 2014 à 2018 : un indicateur révélateur de bien des difficultés démographiques et socio-économiques.

Outil : Datawrapper


<iframe title="Jeu de données - Taux de mortalité infantile de 2014 à 2018 par pays." aria-label="chart" id="datawrapper-chart-5j2Pc" src="https://datawrapper.dwcdn.net/5j2Pc/2/" scrolling="no" frameborder="0" style="width: 0; min-width: 100% !important; border: none;" height="794"></iframe><script type="text/javascript">!function(){"use strict";window.addEventListener("message",(function(a){if(void 0!==a.data["datawrapper-height"])for(var e in a.data["datawrapper-height"]){var t=document.getElementById("datawrapper-chart-"+e)||document.querySelector("iframe[src*='"+e+"']");t&&(t.style.height=a.data["datawrapper-height"][e]+"px")}}))}();
</script>

### C - Carte choroplèthe du taux de mortalité infantile en 2018 (par 1000 naissances vivantes) par pays.

Outil : Datawrapper

<iframe title="Taux de mortalité infantile en 2018 par pays (par 1 000 naissances vivantes)" aria-label="Map" id="datawrapper-chart-9egap" src="https://datawrapper.dwcdn.net/9egap/1/" scrolling="no" frameborder="0" style="width: 0; min-width: 100% !important; border: none;" height="424"></iframe><script type="text/javascript">!function(){"use strict";window.addEventListener("message",(function(a){if(void 0!==a.data["datawrapper-height"])for(var e in a.data["datawrapper-height"]){var t=document.getElementById("datawrapper-chart-"+e)||document.querySelector("iframe[src*='"+e+"']");t&&(t.style.height=a.data["datawrapper-height"][e]+"px")}}))}();
</script>

### D - Column chart (grouped) de l'évolution du taux de mortalité infantile de 2014 et 2018 (par 1000 naissances vivantes).

Outil : Flourish

<div class="flourish-embed flourish-chart" data-src="visualisation/5144443"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

### E - Analyse 

Ainsi, on remarque que la mortalité infantile est plus marquée dans les pays dits "sous-dévellopés" ou "en développement". Le taux de mortalité infantile a considérablement diminué en Europe, en Amérique du Nord ainsi qu'en Asie du Sud-Est, tandis qu'en Afrique les inégalités se creusent, notamment en Afrique centrale où l'on dénombre tout de même encore en 93 décés pour 1000 naissances en République centraficaine en 2018, en Somalie le taux de mortalité infantile n'a marqué aucune baisse de 2014 à 2018; néamoins il n'y a pas eu de regression, globalement la mortalité en 2018 est en baisse dans toutes les régions du monde, même s'il en demeure que la progression est plus lente en Afrique. Rappelons que l’un des principaux déterminants des inégalités d’espérance de vie à travers le globe demeure le taux de mortalité infantile. 

## 2. Espérance de vie depuis 1817 dans le Monde 

### A - Définition EV

Selon l'Institut national de la statistique et des études économiques, l'espérance de vie ou espèrance de vie à la naissance "représente la durée de vie moyenne d'une génération fictive soumise aux conditions de mortalité par âge de l'année considérée." Cet indicateur est généralement usité en raison de sa représentativité de l'état de santé d'une population. Néanmoins, il faut preter garde à ne pas confondre l'espèrance de vie avec l'espérance de vie sans incapacité que nous verrons plus en détail par la suite : en effet, il s'agit de deux indicateurs à part entière, qui renvoie à des réalités diverses. 


<iframe title="Jeu de données - Moyenne d'espérance de vie en 1817, 1917 et 2017 par pays." aria-label="chart" id="datawrapper-chart-yATfN" src="https://datawrapper.dwcdn.net/yATfN/1/" scrolling="no" frameborder="0" style="width: 0; min-width: 100% !important; border: none;" height="764"></iframe><script type="text/javascript">!function(){"use strict";window.addEventListener("message",(function(a){if(void 0!==a.data["datawrapper-height"])for(var e in a.data["datawrapper-height"]){var t=document.getElementById("datawrapper-chart-"+e)||document.querySelector("iframe[src*='"+e+"']");t&&(t.style.height=a.data["datawrapper-height"][e]+"px")}}))}();
</script>

### C - Column Chart (stacked) de l'évolution de la moyenne d'espérance de vie par pays depuis 1817.

Outil : Flourish

Ce modèle se prête parfaitement à mon jeu de données dans la mesure où je souhaitais superposer les trois années (1817, 1917, 2017) afin de mettre en évidence l'augmentation de l'espérance de vie. L'espérande de vie s'est vue rallonger dans la plupart des pays du monde, néanmoins on constate de fortes disparités, l'Afrique demeure à distance des autres continents. Ainsi, la progression de l’espérance de vie moyenne dissimule des évolutions différentes selon les continents.

<div class="flourish-embed flourish-chart" data-src="visualisation/5117674"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

### D - Carte chloroplèthe de la moyenne d'espérance de vie par pays en 2017.

<iframe title="Moyenne de l'espérance de vie dans le Monde en 2017 " aria-label="Map" id="datawrapper-chart-XzgEi" src="https://datawrapper.dwcdn.net/XzgEi/1/" scrolling="no" frameborder="0" style="width: 0; min-width: 100% !important; border: none;" height="368"></iframe><script type="text/javascript">!function(){"use strict";window.addEventListener("message",(function(a){if(void 0!==a.data["datawrapper-height"])for(var e in a.data["datawrapper-height"]){var t=document.getElementById("datawrapper-chart-"+e)||document.querySelector("iframe[src*='"+e+"']");t&&(t.style.height=a.data["datawrapper-height"][e]+"px")}}))}();
</script>


## 3. Et en France Alors ? Certes, nous vivons plus longtemps. Mais vivons-nous bien ?

### A - Définition EVSI

L'EVSI (espérence de vie sans incapacité) ou "Espérance de vie en bonne santé" est un indicateur qui  évalue, à la naissance, le nombre d’années qu’une personne peut compter vivre sans souffrir d’incapacité dans les gestes de la vie quotidienne.
Selon la Direction de la recherche, des études, de l'évaluation et des statistiques (DREES) l'espérance de vie en bonne santé s'élève en France à 64,5 ans pour les femmes et 63,4 pour le sexe masculin en 2018.

Outil : Datawrapper

<iframe title="Jeu de données - Espérance de vie à la naissance et espérance de vie sans incapacité, par sexe et âge en 2018 en France" aria-label="chart" id="datawrapper-chart-sYNHm" src="https://datawrapper.dwcdn.net/sYNHm/3/" scrolling="no" frameborder="0" style="width: 0; min-width: 100% !important; border: none;" height="701"></iframe><script type="text/javascript">!function(){"use strict";window.addEventListener("message",(function(a){if(void 0!==a.data["datawrapper-height"])for(var e in a.data["datawrapper-height"]){var t=document.getElementById("datawrapper-chart-"+e)||document.querySelector("iframe[src*='"+e+"']");t&&(t.style.height=a.data["datawrapper-height"][e]+"px")}}))}();
</script>

### B - Column Chart (grouped) de l'espérance de vie à la naissance et espérance de vie sans incapacité, par sexe et âge en 2018 en France.

Ce modèle s'est avéré particulièrement représentatif dans la mesure où mon jeu de données comportait un petit nombre de catégories distinctes, avec une valeur unique pour chaque catégorie. L'objectif étant de comparer les valeurs par chaque catégorie en simplifiant la tâche au lecteur, ce diagramme en colonnes fait appel à la capacité instinctive du lecteur à déduire les hauteurs. Il est facile d'interprétation et ne necessite pas de réelle aptitude d'analyse ou de formation pour être compris.

<div class="flourish-embed flourish-chart" data-src="visualisation/5131949"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

### C - Analyse 

   Que l'on soit né en Somalie ou en Norvège, on peut espèrer vivre moins de 25 ans ou plus de 80 ans. Ces dernières années ont vue l'espérance de vie augmenter de manière significative, cependant l'écart entre pays développés et pays en voie de développement (voire sous-développés) demeure conséquent.
De même, en fonction de la région du Monde où nous naissons nous avons plus ou moins de chances de vivre longuement. En effet, l’un des principaux déterminants des inégalités d’espérance de vie à travers le globe demeure le taux de mortalité infantile. 

Pour qu’une population puisse atteindre une moyenne d'âge de 70 ans ou plus, il faut avant toute chose que les nourissons survivent à leurs premières années. Selon une étude de l'INSEE "La mortalité infantile se concentre dans les premiers jours de la vie : la moitié des enfants décédés avant leur premier anniversaire ont vécu moins d’une semaine."

### 4. Le Revenu National Brut par habitant et l'espérance de vie.

### A - Définition 

Selon l'Organisation de Coopération et de Développement Économiques, le Revenu National Brut par habitant est défini comme le " PIB plus les revenus nets reçus de l'étranger pour la rémunération des salariés, la propriété et les impôts et subventions nets sur la production". 

<iframe title="Jeu de données - Moyenne du Revenu National Brut (RNB) par Habitant dans le Monde" aria-label="chart" id="datawrapper-chart-uLHg4" src="https://datawrapper.dwcdn.net/uLHg4/1/" scrolling="no" frameborder="0" style="width: 0; min-width: 100% !important; border: none;" height="948"></iframe><script type="text/javascript">!function(){"use strict";window.addEventListener("message",(function(a){if(void 0!==a.data["datawrapper-height"])for(var e in a.data["datawrapper-height"]){var t=document.getElementById("datawrapper-chart-"+e)||document.querySelector("iframe[src*='"+e+"']");t&&(t.style.height=a.data["datawrapper-height"][e]+"px")}}))}();
</script>

### B - Carte Chloroplèthe du revenu national brut par habitant et espérance de vie 

Outil : Datawrapper 

<iframe title=" Revenu National Brut par Habitant ($ courants)" aria-label="Map" id="datawrapper-chart-UEH0h" src="https://datawrapper.dwcdn.net/UEH0h/1/" scrolling="no" frameborder="0" style="width: 0; min-width: 100% !important; border: none;" height="368"></iframe><script type="text/javascript">!function(){"use strict";window.addEventListener("message",(function(a){if(void 0!==a.data["datawrapper-height"])for(var e in a.data["datawrapper-height"]){var t=document.getElementById("datawrapper-chart-"+e)||document.querySelector("iframe[src*='"+e+"']");t&&(t.style.height=a.data["datawrapper-height"][e]+"px")}}))}();
</script>

### 5.OpenRefine 

Modification des jeux de données via OpenRefine :  

Les jeux de données employées pour les datavisualisatiosn ci-dessus étant relativement bien structurés je n'ai pas eu recours à OpenRefine de façon avancée, néanmoins le nombre de donnée étant conséquent cet outil m'a été indispensable pour supprimer rapidement les cellules qui ne contenaient aucune entrée (aucune donnée pour certains pays à certaines dates) , de même dans le cadre de certains jeu de données les nombres décimaux ( exemple : 12, 6) étaient perçues comme des entiers positifs j'ai donc remplacé l'entiereté des "," par des "." et ainsi les valeurs étaient lues comme des entiers. Par le biais d'OpenRefine je me suis également assurée de n'avoir aucun doublons. 

Modification du jeu de données sur la mortalité infantile par pays : 

````sparql
[
  {
    "op": "core/row-removal",
    "engineConfig": {
      "facets": [
        {
          "type": "list",
          "name": "Valeurs vides par colonne",
          "expression": "filter(row.columnNames,cn,isBlank(cells[cn].value))",
          "columnName": "",
          "invert": false,
          "omitBlank": false,
          "omitError": false,
          "selection": [
            {
              "v": {
                "v": "1800",
                "l": "1800"
              }
            }
          ],
          "selectBlank": false,
          "selectError": false
        }
      ],
      "mode": "row-based"
    },
    "description": "Remove rows"
  }
]
````
Modification du jeu de donnée de l'EV et de l'EVSI par sexe et par âge en France en 2018 : 

````sparql
[
  {
    "op": "core/text-transform",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "EVSI femmes",
    "expression": "value.replace(\",\",\".\")",
    "onError": "keep-original",
    "repeat": false,
    "repeatCount": 10,
    "description": "Text transform on cells in column EVSI femmes using expression value.replace(\",\",\".\")"
  },
  {
    "op": "core/text-transform",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "EV femmes",
    "expression": "value.replace(\",\",\".\")",
    "onError": "keep-original",
    "repeat": false,
    "repeatCount": 10,
    "description": "Text transform on cells in column EV femmes using expression value.replace(\",\",\".\")"
  },
  {
    "op": "core/text-transform",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "EVSI hommes",
    "expression": "value.replace(\",\",\".\")",
    "onError": "keep-original",
    "repeat": false,
    "repeatCount": 10,
    "description": "Text transform on cells in column EVSI hommes using expression value.replace(\",\",\".\")"
  },
  {
    "op": "core/text-transform",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "EV hommes",
    "expression": "value.replace(\",\",\".\")",
    "onError": "keep-original",
    "repeat": false,
    "repeatCount": 10,
    "description": "Text transform on cells in column EV hommes using expression value.replace(\",\",\".\")"
  }
]
````

### 6.Requête Wikidata

Liste des pays par espèrance de vie (de la plus faible moyenne d'espèrance de vie à la plus elevée) 

````sparql
SELECT DISTINCT ?pays ?paysLabel ?esperance_de_vie WHERE 
{
  ?pays wdt:P31 wd:Q6256.
  ?pays wdt:P2250 ?esperance_de_vie.
  SERVICE wikibase:label { bd:serviceParam wikibase:language "fr". }
}
ORDER BY asc (?esperance_de_vie)
````
Résultat de la requête disponible ici : https://w.wiki/xEM

Liste des pays par taux d'alphabétisation (du plus bas taux d'alphabétisation au plus élevé) 


````sparql
SELECT DISTINCT ?pays ?paysLabel ?taux_d_alphabetisation WHERE 
{
  ?pays wdt:P31 wd:Q6256.
  ?pays wdt:P6897 ?taux_d_alphabetisation.
  SERVICE wikibase:label { bd:serviceParam wikibase:language "fr". }
}
 ORDER BY asc (?taux_d_alphabetisation)
 ````
 
 Résultat de la requête disponible ici : https://w.wiki/xEm
 
 Liste des pays par produit international brut (PIB) ( du plus bas au  plus élevé) 
 
  ````sparql
 SELECT DISTINCT ?pays ?paysLabel ?produit_interieur_brut_nominal WHERE 
{
  ?pays wdt:P31 wd:Q6256.
  ?pays wdt:P2131 ?produit_interieur_brut_nominal.
  SERVICE wikibase:label { bd:serviceParam wikibase:language "fr". }
}
 ORDER BY asc (?produit_interieur_brut_nominal)
  ````
  
  Résultat de la requête disponible ici : https://w.wiki/xEw
