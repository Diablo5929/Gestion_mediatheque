

    Installer Python : Téléchargez et installez Python (version 3.13 ou supérieure) depuis python.org.

    Créer un environnement virtuel : Ouvrez un terminal ou une invite de commande. Naviguez vers le dossier où vous voulez créer votre projet. Exécutez : python -m venv env Activez l'environnement virtuel : Sur Windows : env\Scripts\activate Sur macOS/Linux : source env/bin/activate

    Cloner le projet git clone https://github.com/Diablo5929/Gestion_mediatheque cd Gestion-mediatheque

    Installer les dépendances : pip install django pip install pytest

    Configurer la base de données : Exécutez les migrations : python manage.py makemigrations gestion_mediatheque python manage.py migrate

    Charger les données de test : Lancer la commande python manage.py loaddata initial_data.json

    Lancer le serveur de développement : python manage.py runserver

    Accéder à l'application : Ouvrez un navigateur et allez à http://127.0.0.1:8000 

