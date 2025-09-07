# code_memoire
Repository comprenant les codes et données utilisées pour le mémoire de première année de master Humanités Numériques 

# Description des différents dossiers présents sur la branche : 


## M2/Code :
Notebooks utilisés pour la production des divers premiers résultats dont en voici une courte description : 
- Calculs_stats_simple_moyenne : Comme son nom l'indique, premiers calculs pour prendre le corpus en main. Taille des séances moyennes, répartition du nombre de mots, etc.
- Concordancier représentations visuelles : Concordancier comprenant plusieurs représentations visuelles qui n'ont pas toutes été retenues, possibilité d'afficher le nombre d'occurrences d'un mot par années, de voir s'il y a plus d'occurrences une année par rapport à la moyenne, etc.
- Concordancier final extraction séances : Version simplifiée du concordancier permettant l'extraction des séances correspondantes avec un mot-clef à préciser.
- Co-occurencier propre : version réduite et plus légère du co-occurencier
- Cooccurencier réel : version plus développée du co-occurencier avec affichage des extraits retenus. 
- Recherche par mot clef : simple outil de recherche par mot clef dans le document souhaité
- Test OCRonos echec : Un des divers tests réalisés pour la correction de l'OCR ici en utilisant la librairie Ocronos, malheureusement de très mauvaises performances à la suite de l'entrainement et beaucoup d'hallucinations qui ne réglaient pas le soucis de fautes de numérisation
- TF-IDF mémoire : Notebook comprenant plusieurs mesures de similarité entre les documents et notamment l'utilisation avec des listes de vocabulaire du TF-IDF pour essayer de déterminer les séances ayant un rapport thématique entre elles, approche un peu laissée de côtée car les résultats étaient trop bruités
- Topic model convainquant : Application de la modélisation de sujet la plus performante et qui retourne les sujets les plus intéressant après diverses sessions de tests.
- TOP2VEC colab : Tentative de Top2Vec puis clustering "à la main" après que l'application du modèle ne puisse pas être menée à bien faute de puissance de calcul.
- Contexte sémantique version colab : Notebook le plus pertinent pour l'étude en question, reprend les étapes du notebook concordancier pour ensuite utiliser les extraits en question et en retenir le contexte sémantique autour des mots cible. L'exemple ici utilisé de "canal" est encore une fois celui qui retourne les résultats les plus satisfaisant.

# Code : 
Notebooks utilisés pour la première version du rendu en M1, conservés ici a des fins de comparaison et de correction eventuellement

## ocr_sorted : 
L'ensemble des débats parlementaires océrisés, un document correspondant à une séance dont le titre est la date de ladite session. Il y a donc 7461 séances sous la forme de documents .txt dans le dossier.
### *Important* : 
Les images/documents numérisés des séances ne sont pas disponible sur ce github par souci de place, de temps de calcul du scrapping nécessaire à l'obtention des images et parce qu'elles sont disponible en libre accès sur gallica directement : https://gallica.bnf.fr/ark:/12148/cb328020951/date.r=Journal+officiel+de+la+Republique+francaise+Debats+parlementaires,+Chambre+des+deputes.langFR 

## Premiers résultats : 
Comprend les lemmatisations des textes contenus dans "ocr_sorted", les dictionnaires organisant les documents par année, ainsi que les premières générations de topics.

## Images rédaction :
Ensemble des images utiliées lors de la rédaction du mémoire.

## Modèle LaTeX : 
Modèle fourni par l'école utilisé pour la rédaction du mémoire.

