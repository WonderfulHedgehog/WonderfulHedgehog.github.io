# Certification en Humanités Numériques

Ce répertoire condense l'ensemble de mes projets menés lors de ma Certification en Humanités Numériques à l'Université de Genève. Les deux cours que j'ai choisis pour mon parcours possèdent chacun leur dossier consacré, Distant Reading I et Numériser le patrimoine I. Voici détaillée l'architecture du GIT : 


## Distant Reading I 

Le dossier intitulé Distant Reading I comporte le rapport de l'ensemble des travaux au format .pdf. On y trouvera également trois dossiers, un pour chacun des projets : 


### Topic_modeling_CdMM 

- le fichier de code en R-Markdown ; 
- le texte du _Carmen de martyrio Maccabaeorum_ lemmatisé grâce à Pyrrha, au format .csv ;
- la liste des _stopwords_ ;
- un dossier intitulé "Résultats" contenant les graphiques obtenus. 

### Topic_modeling_Tertullien 

- le code sous forme de Jupyter Notebook ;
- le corpus analysé en .csv ;
- la liste des _stopwords_ ; 
- une seconde liste de _stopwords_ pour les termes spécifiques à Tertullien ; 
- un dossier réunissant les résulats.

### Clustering_Tertullien 

- le code en R-Markdown ; 
- un dossier appelé "corpus" qui contient toutes les oeuvres de Tertullien dans des fichiers .xml séparés ;
- un dossier de résultats avec les graphiques obtenus grâce à différentes mesures, ainsi que deux sous-dossiers : 
  - Test 1 : le dossier créé automatiquement par le code où sont regroupés les différents calculs effectués avec la distance de Manhattan ;
  - Consensus_trees : les graphiques des consensus trees.

  
## Numérisation du patrimoine I
### Galerie_auteurs_latins

- un fichier .css ; 
- huit pages HTML qui pointent les unes vers les autres pour constituer une ébauche de site web ; 
- un dossier "Images antiques" contenant les illustrations au format .png.

### OCR_CdMM

- le code au format Jupyter Notebook ; 
- un dossier "Photos" où se trouvent les scans de notre jeu de données (le même _Carmen de martyrio Maccabaeorum_) ; 
- un dossier "Résultats" avec deux sous-dossiers : 
  - on trouvera dans "Résultats" la page témoin après différents traitements, un échantillon de texte extrait de chacune de ces images modifiées ainsi que l'ensemble du texte océrisé ; 
  - le second dossier, "Essais_Manuscrit", comporte pareillement une page témoin de manuscrit, ainsi que les apparences qu'elle a revêtues après une succession de traitements. 
