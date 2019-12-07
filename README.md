# URLShortener
 Minify une URL et le rediriger vers l'URL d'origine

# Installer
 Python3
 Flask
 Flask-restful

# Comment exécuter?
 1. Démarrez l'application en exécutant la commande suivante,
	$ python restAPI.py
 2. Ouvrez le fichier index.html 

# Défauts existants
1. Fuites de mémoire à gérer (car aucun serveur d'hébergement local)
  2. La page de statistiques est conçue avec des valeurs codées en dur, car XMLHttpRequest ne permet pas de lire les fichiers enregistrés localement dans le navigateur. Mais les journaux et les fichiers de profilage sont disponibles.
  3. Le fichier de sortie de profilage est désactivé pour des problèmes de mémoire (car aucun serveur d'hébergement localement)
  4. Pour les URL avec des opérateurs arithmétiques et des valeurs flottantes, une exception se produit. Besoin de gérer ce problème
  5. La redirection se fait pour l'instant dans une nouvelle fenêtre (car aucun framework côté client n'est développé), sera bientôt fait et livré en version2
 
