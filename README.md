# Le Baromètre du confinement
Ce repo contient les éléments d'une analyse en continu d'un fil de tweet défini par l'usage du hashtag #confinementJour1 à #confinementJour_n. A j+15 elle comoorte 1.1 millions de tweet, rt et quote.
Un extrait (df_sample) est disponible dans le repo pour tester les proc.(le fichier entier dépasse la limite des 50mo, il en fait 1,3Mo)
L'analyse est centrée sur l'analyse du sentiment via les méthodes NCR, LSDfr et LIWC.
les premiers résultats sont [lisibles ici](https://benaventc.github.io/BarometreConfinement/confinement02_analyse.html)

Quelques questions à explorer
 * construire une frise chronologique des principaux évenements
 * la dimension spatiale via la geolocalisation
 * le traitement des emojis
 * l'analyse des auto-correlations et corrélations croisées
 * l'analyse par profils d'utisateurs (induction du genre, frequence de post, nb de followers)
 * Approche par LDA
 * Mesures spécifiques de l'ennui, de la peur, de la solitude, de la consommation.... (sur-mesure à partir de lexiques home made et de word2vec)
