# sihamTAOUZI-Extraction-et-Exploration-de-l-Espace-Latent-d-un-Autoencodeur-PCA-t-SNE-et-UMAP
Visualisation de l’Espace Latent d’un Autoencodeur sur MNIST

Ce projet présente la construction, l’entraînement et l’analyse d’un autoencodeur convolutionnel appliqué au dataset MNIST. L’objectif principal est d’étudier la capacité du modèle à apprendre une représentation latente compacte des chiffres manuscrits, et d’évaluer la qualité de cette représentation à l’aide de méthodes de réduction de dimension.

Contenu du projet

Construction du modèle : encodeur + décodeur convolutionnels..

Entraînement de l’autoencodeur sur MNIST.

Extraction de l’espace latent pour les données d’entraînement et de test.

Réduction de dimension avec :

PCA (linéaire),

t-SNE (préservation locale),

UMAP (structure locale + globale).

Comparaison Train vs Test : visualisation et analyse de la qualité des clusters.

Résultats clés

L’autoencodeur reconstruit correctement les chiffres malgré une légère perte de détails.

PCA montre une séparation limitée, t-SNE révèle des clusters distincts mais coûteux en calcul.

UMAP offre la meilleure visualisation, rapide et bien structurée.

Les données d’entraînement présentent une séparation des classes plus nette que les données de test.


Objectif

Fournir une base simple et pédagogique pour comprendre :

la structure des autoencodeurs,

l’extraction d’un espace latent,

la visualisation avancée de données en haute dimension.
