# :house: DVF Immobilier

L'application **[DVF Immobilier](https://dvf-real-estate.tlechatelier.fr)** est un **tableau de bord** des **transactions immobilières** en **France**, qui incorpore un outil **d'intelligence artificielle** pour la prédiction de prix de biens immobiliers.

> **Attention :**
> :warning: Il est fortement recommandé d'utiliser l'application sur ordinateur. :warning:

<div align=center>
<img src="resources/DVF_Immobilier.png" width="800">
<p><i>Application DVF Immobilier</i></p>
</div>


## I. :star: Contexte

L'application DVF Immobilier rend **la visualisation des transactions immobilières (ou mutations) fluide et accessible à tous**. On y trouve les données liées aux maisons et aux appartements vendus en France (hors Moselle (57), Bas-Rhin (67), Haut-Rhin (68) et Mayotte (976)), au cours des **5 dernières années**.

Les données utilisées sont fournies par le gouvernement et sont connues sous le nom [DVF](https://www.data.gouv.fr/fr/datasets/demandes-de-valeurs-foncieres/) disponible en *Licence Ouverte*. 
**Les données présentes dans l'application ont été retraitées et agrégées** afin de fournir une meilleure qualité de lecture pour l'utilisateur.


## II. :dart: Fonctionnalités

L'application se présente sous forme de tableau de bord. Les données sont facilement exploitables à travers une **interface simple d'utilisation** qui est composée d'une unique page.

Les fonctionnalités se décomposent en **4 grandes catégories** :
1. La visualisation d'indicateurs immobiliers.
2. Filtres classiques.
3. Filtres intelligents intégrés aux graphiques.
4. Un outil d'intelligence artificielle pour prédire le prix d'un bien immobilier


### 1. 	:bar_chart: La visualisation d'indicateurs immobiliers

<div align=center>
<img src="resources/DVF_Immobilier_graphiques.png" width="800">
<p><i>Application DVF Immobilier - Graphiques</i></p>
</div>

L'application dispose de **6 visuels** mettant en valeur différents critères liés aux transactions immobilières :
1. Carte satellite (carte choroplèthe) du territoire français *(en haut à gauche)*. 
2. Prix au mètre carré sur l'ensemble des données sélectionnées *(en haut à droite)*. 
3. Nombre de mutations/transactions sélectionnées par les filtres *(au milieu à droite)*. 
4. Camembert sur la répartition du nombre de pièces principales sur l'ensemble des données sélectionnées *(au milieu à droite)*. 
5. Evolution du prix au mètre carré en fonction du temps *(en bas à gauche)*. 
6. Evolution du prix au mètre carré selon la surface *(en bas à droite)*.


<div align=center>
<img src="resources/DVF_Immobilier_popup_information.png" width="400">
<p><i>Application DVF Immobilier - Pop-up d'information</i></p>
</div>


De plus, sur chaque visuel, des **informations supplémentaires sont disponibles** en passant la souris sur les zones de couleur relatives aux données.


### 2. 	:mag_right: Filtres classiques

<div align=center>
<img src="resources/DVF_Immobilier_filtres.png" width="800">
<p><i>Application DVF Immobilier - Filtres</i></p>
</div>

Il existe **4 types de filtres classiques** qui permettent de modifier les indicateurs visuels suivants :
* Le **département**.
* Le **type de bien** (maison ou appartement).
* La **période d'affichage** des données.
* Le **type de représentation** :
  * **Plage** : agrégation par commune.
  * **Point** : transaction visible individuellement, **les points en gris** sont des points avec de multiples valeurs et l'utilisateur peut **cliquer dessus pour avoir plus d'informations**.

<div align=center>
<img src="resources/DVF_Immobilier_plage_point.png" width="800">
<p><i>Application DVF Immobilier - Vue par plage / point</i></p>
</div>

### 3. :computer_mouse: Filtres intelligents intégrés aux graphiques

<div align=center>
<img src="resources/DVF_Immobilier_graphiques_filtrés.png" width="800">
<p><i>Application DVF Immobilier - Graphiques avec filtres activés</i></p>
</div>

Sur les **visuels 1, 4 et 6**, il est possible de **cliquer sur les zones de couleur** représentant des données pour ajouter un filtre et affiner les résultats.

Pour désélectionner un filtre il suffit de re-cliquer sur la zone sélectionnée.


### 4. :chart_with_upwards_trend: Un outil d'intelligence artificielle pour prédire le prix d'un bien immobilier

Pour afficher **le menu de prédiction/estimation** il suffit de cliquer sur le bouton <img src="resources/DVF_Immobilier_prédiction_bouton.png" width="30"> en haut à droite.

<div align=center>
<img src="resources/DVF_Immobilier_prédiction.png" width="200">
<p><i>Application DVF Immobilier - Onglet de prédiction</i></p>
</div>

Pour prédire le prix d'un bien immobilier il faut renseigner certaines informations :
* Le **type de bien**.
* L'**adresse**.
* La **surface** en m².
* La **surface du terrain** en m² (exclusivement pour les maisons).
* Le **nombre de pièces principales**.

Une fois les informations remplies, il suffit de cliquer sur le bouton **Calcul** pour faire apparaître l'estimation du prix.

<div align=center>
<img src="resources/DVF_Immobilier_prédiction_2.png" width="200">
<p><i>Application DVF Immobilier - Prédiction</i></p>
</div>

Un algorithme **d'intelligence artificielle** a été entraîné sur les données existantes afin de fournir un résultat le plus proche possible de la réalité. 
L'estimation du prix d'un bien immobilier est donnée à titre indicatif et fonctionne exclusivement en **France métropolitaine**.


## III. :pencil: Licences

:warning: **L'utilisation de cette application à des fins commerciales est strictement interdite.** :warning:

## IV. :satellite: Auteur

Vous pouvez me contacter si vous avez des questions supplémentaires ou si vous avez détecté un bug à **timothe.lechatelier@gmail.com**

Et maintenant c'est à vous de prendre la main... :raised_hand_with_fingers_splayed:

**Timothé Le Chatelier**

<p>
  <a href="https://www.linkedin.com/in/timoth%C3%A9-lechatelier/" target="_blank">
    <img height=30px" src="https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white">
  </a>

</p>
