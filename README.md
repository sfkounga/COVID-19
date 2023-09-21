<table>
  <tr>
    <td width="30%" height="30% > 
      <img src= "04_RESSOURCES/Project_Logo.png">
    <td> 
  </tr>
</table>

<h4 align="center">Analyse comparative et visualisation du taux d'infection et de mortalité liés au COVID-19</br>
  en Afrique du Sud, en Allemagne, en Côte d'ivoire et en France avec l'outil <a href="https://en.wikipedia.org/wiki/Microsoft_Power_BI" target="_blank">Power BI</a></h4>

<p align='center'>
<img src='04_RESSOURCES/The_VictoryLap.png' width=30% height=30% >
</p>

<p align="center">
  <a href="#overview">CONTEXTE</a> •
  <a href="#competences">COMPETENCES CLES</a> •
  <a href="#architecture">APPROCHE MÉTHODOLOGIQUE</a> •
  <a href="#demo">DÉMO</a> •
  <a href="#support">REMARQUES</a> •
  <a href="#license">LICENCE</a>
</p>

## CONTEXTE </br>
Ce projet met en exergue une analyse exploratoire des données relative à une revue comparative du taux d'infection et du taux de mortalité liés au COVID-19 pour la période 2018 - 2021 dans les 04 pays ci-après  :


<table>
  <tr>
    <td>1• Allemagne</td>
    <td>Le pays dans lequel j'ai étudié et demarré ma carrière professionnelle</td>
  </tr>
  <tr>
    <td>2• Côte d'Ivoire</td>
    <td>Mon second pays d'acceuil en Afrique</td>
  </tr>
  <tr>
    <td>3• France</td> 
    <td>Mon pays de résidence</td>
  </tr>
  <tr>
    <td>4• Trinité-et-Tobago</td>
    <td>Après leur passage au Mondial 2006, c'est l'un des pays dans lequel j'aimerais bien passer des vacances</td>
  </tr>
</table>


Le livrable clé de ce projet est le tableau de bord (élaboré à l'aide de l'outil Microsoft Power BI) présenté dans la section "DÉMO".
Un résumé d'informations jugées clés est tout aussi présenté dans la section "LES 05 INFORMATIONS CLÉS À RETENIR".

le dossier de ce Projet est structuré de la manière suivante :

Analyse COVID-19 <br>
 ├───01_SOURCE<br>
 ├───02_ETL<br>
 ├───03_DASHBOARD<br>
 └───04_RESSOURCES<br>


**01_SOURCE**</br>
Ce répertoire contient les données brutes téléchargées du site www.kaggle.com qui doivent être nettoyées et organisées pour faciliter le processus d'analyse et de visualisation des données.

Le dataset (jeu de données) [COVID-19.csv][website_link1] contient l'ensemble des informations liées au taux d'infection et taux de mortalité des personnes atteintes du COVID-19 pour la période 15/02/2020 - 14/05/2022.

Le dataset [Temperature.csv][website_link2] contient les données météorologiques historiques quotidiennes enregistrées pour 194 capitales de pays pour la période 01/01/2018 - 11/10/2022. 

Les périodes couvertes par ces données étant différentes, j'ai trouvé qu'il serait pertinent de mener l'analyse sur la période couverte par les deux jeux de données, c'est-à-dire : 15/02/2020 - 14/05/202 


**02_ETL**</br>
Ce répertoire contient les scripts DAX utilisés lors de la phase ETL pour les différentes transformations opérées sur l'ensemble de données brutes chargées en entrée.


**03_DASHBOARD** </br>
Ce répertoire contient le fichier de visualisation (.PBIX) du rapport Power BI.


**04_RESSOURCES** </br>
Ce répertoire contient des images et icônes, etc. utilisées au sein de ce projet.



## COMPETENCES CLES</br>
Mes principales compétences mises en application dans ce projet sont les suivantes:
- Power BI
- Processus ETL (Extraction, Transformation, Load)
- Langage DAX
- Data Analysis
- Data Visualization
- Story Telling 



## APPROCHE MÉTHODOLOGIQUE</br>
L'architecture du projet est assez simple (et alignée aux processus standards d'analyse de données) et peut être expliquée par l'image ci-dessous :

![Process Architecture][process_workflow]

Tel que présenté dans l'approche méthodologique ci-dessus, j'ai procédé au téléchargement des jeux de données sur le site kaggle.com, qui contient une bibliothèque de données historiques sur différentes thématiques.

Ces données ont tout d'abord été chargées dans l'outil Power BI Desktop. Ensuite elles ont été traitées et nettoyées à l'aide de différents scripts DAX. Deux autres tables ("Date" et "Pays") ont été créées au sein de l'environnemment pour permettre une analyse chronologique et croisée de ces données.

Enfin, une analyse exploratoire de ces données a été menée à l'aide de différents indicateurs clés et de différentes visuels disponibles dans Power BI.

Le rapport a enfin été publié sur le Service Power BI, afin de le partager avec les personnes qui seraient interessées par les résultats de cette analyse.



## LES 05 INFORMATIONS CLÉS À RETENIR</br>



## DÉMO</br>
Le tableau de bord interactif Power BI peut être consulté en cliquant sur l'image ci-après:
Une fois que vous cliquez dessus, l'utilisateur est redirigé vers le rapport dynamique publié sur le service Power BI contenant un ensemble de fonctionnalités avancées (slicers, filtres croisés, histogramme, etc.) avec lesquelles il peut interagir pour visualiser une facette spécifique des données ou pour obtenir des informations supplémentaires.

[![Power BI Dashboard][dashboard_image]][dashboard_link]



## REMARQUES</br>
Pour toute(s) question(s) ou suggestion(s), n'hésitez pas à me contacter sur :
mon profil [LinkedIn][linkedin] ou via mon eMail: sf.kounga@gmail.com



## LICENCE

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Licence Creative Commons" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />Ce(tte) œuvre est mise à disposition selon les termes de la <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Licence Creative Commons Attribution - Pas d’Utilisation Commerciale - Partage dans les Mêmes Conditions 4.0 International</a>.


<!-- Image Links -->

[project_logo]: 04_RESSOURCES/Project_Logo.png
[process_workflow]: 04_RESSOURCES/Approche_Méthodo.png
[dashboard_image]: 04_RESSOURCES/dashboard_image.png

<!-- External Links -->

[website_link1]: https://www.kaggle.com/datasets/josephassaker/covid19-global-dataset?select=worldometer_coronavirus_daily_data.csv
[website_link2]: https://www.kaggle.com/datasets/balabaskar/historical-weather-data-of-all-country-capitals?select=daily_weather_data.csv


<!-- Profile Links -->

[linkedin]: https://www.linkedin.com/in/serge-kounga-a26365161
[dashboard_link]: 

<!-- Shields Profile Links -->

