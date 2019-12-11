# URLShortener
 Minify une URL et le rediriger vers l'URL d'origine
Le résultat de ce projet est expliqué dans le document <<Résultat du projet>>

# Installer
 Python3
 Flask
 Flask-restful

# Comment exécuter?
 1. Démarrez l'application en exécutant la commande suivante,
	$ python restAPI.py
 2. Afficher l'application dans http://127.0.0.1:5000 

# Défauts existants
 1. Fuites de mémoire à gérer (car aucun serveur d'hébergement local)
 2. La page de statistiques est conçue avec des valeurs codées en dur, car XMLHttpRequest ne permet pas de lire les fichiers enregistrés localement dans le navigateur. Mais les journaux et les fichiers de profilage sont disponibles
 3. Le fichier de sortie de profilage est désactivé pour des problèmes de mémoire (car aucun serveur d'hébergement localement)
 
