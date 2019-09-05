# NLP---Cat-gorisation-de-texte
Analyse de texte et recommandation de tags suite à une question internet (prise dans la base de données de stackoverflow). Utilisation de vecteurs word2vec pondérés des TF-IDF pour générer des vecteurs « question ». 

Contient : 

- un notebook présentant le travail de nettoyage et de visualisation ainsi que l'application 
de l'algorithme tsne aux features fréquentielles

- un notebook d'entrainement d'un modèle d'embedding (word2vec) sur un large corpus représentatif

- un notebook d'apprentissage supervisé implémentant 3 modèles supervisés (vecteurs creux, 
	vecteurs d'embedding pleins, réseau convolutif). Comparaison en temps de calcul, performances 
	étude et application d'une fonction de comparaison, détermination des hyperparamètres, évaluation
	en fonction du nombre de recommandations, comparaison de la régression logistique et du réseau de neurones une couche
	dépendance en nombre de données d'entrainement
  
			- un notebook d'apprentissage tentant d'implémenter une fonction de comparaison améliorée appliquée
			  à l'apprentissage supervisé et non supervisé
        
			- un notebook d'apprentissage semi-supervisé implémentant deux méthodes se basant toutes deux sur une
			  NMF : NMF + classification et NMF > création d'une matrice topic/tag. détermination des hyperparamètres
        
			- un second notebook d'apprentissage semi-supervisé implémentant le même travail mais via une LDA
      
lire le rapport (.pdf) pour plus d'informations.

