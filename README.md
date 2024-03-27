# GPT CLONE APP

## Description
Ce projet est une api web développée en Python avec le framework Flask. Il sert à montrer comment utiliser l'api d'openIA dans un projet python.

## Installation
1. Clonez ce dépôt sur votre machine :
   ```bash
   git clone https://github.com/franckDev21/api-chat-gpt.git
   ```
2. Accédez au répertoire du projet :
   ```bash
    cd api-chat-gpt.git
   ```
3. Installez les dépendances requises :
   ```bash
   pip install -r requirements.txt
   ```

## Configuration
1. Créez un fichier `.env` à la racine du projet et configurez les variables d'environnement selon vos besoins. Voici un exemple :
   ```
   OPENAI_API_KEY=your_secret_key_here
   ```

## Utilisation
Pour lancer l'application, exécutez la commande suivante depuis la racine du projet :
```bash
python app.py
```

L'application sera alors accessible dans votre navigateur à l'adresse [http://localhost:8000](http://localhost:8000).

## Structure du Projet
- `app.py` : Point d'entrée de l'application.
- `requirements.txt` : Liste des dépendances Python nécessaires.
- `templates/` : Répertoire contenant les templates HTML.
- `static/` : Répertoire contenant les fichiers statiques (CSS, JS, images, etc.).
- `...` : Autres fichiers et répertoires selon la structure de votre application.

## Contribution
Les contributions sont les bienvenues ! N'hésitez pas à ouvrir une issue pour signaler un bug ou proposer une amélioration.

## Licence
Ce projet est sous licence [MIT](https://opensource.org/licenses/MIT).
