# Automated_create_project
un script qui me permettra de créer un projet et qui me demandera le nom du projet, le langage, créera un depot git et l'initialisera (s'il y a un moyen d'initialiser le git, créer un repository GitHub depuis le terminal), un README et un Dockerfile, un .env, un docker-compose-yml pour le projet et un requirements.txt

Bien sûr ! Voici un exemple de README pour le script que nous avons créé :

```
# Script de création de projet

Ce script Python vous permet de créer un nouveau projet avec des fichiers de base, y compris un README, un Dockerfile, un .env, un docker-compose.yml et un requirements.txt.

## Utilisation

1. Assurez-vous d'avoir Python, Git et Docker installés sur votre système.

2. Exécutez le script `create_project.py` à l'aide de la commande suivante :

   ```shell
   python create_project.py
   ```

3. Suivez les invites pour fournir les détails du projet, tels que le nom du projet et le langage.

4. Le script créera un dossier pour le projet avec les fichiers et le contenu de base appropriés.

5. Une fois la création terminée, le script ouvrira automatiquement le dossier du projet dans Visual Studio Code (assurez-vous que l'exécutable `code` est correctement configuré).

6. Personnalisez les fichiers générés selon vos besoins pour démarrer votre projet.

## Contenu du projet

- `README.md` : Fichier de documentation principal pour le projet.
- `Dockerfile` : Fichier de configuration Docker pour la construction d'une image.
- `.env` : Fichier contenant les variables d'environnement pour le projet.
- `docker-compose.yml` : Fichier de configuration Docker Compose pour l'orchestration de conteneurs.
- `requirements.txt` : Fichier spécifiant les dépendances du projet.

## Dépendances

Ce script utilise les dépendances Python suivantes :

- GitPython : Permet d'interagir avec Git depuis Python.
- docker-compose : Permet de manipuler Docker Compose depuis Python.

Assurez-vous d'installer ces dépendances en utilisant la commande suivante :

```shell
pip install GitPython docker-compose
```

## Avertissement

Ce script est fourni tel quel, sans aucune garantie. Veuillez l'utiliser à vos propres risques. Assurez-vous de comprendre les implications de l'exécution de ce script avant de l'utiliser.

```

Vous pouvez copier ce contenu dans un fichier `README.md` à la racine de votre projet. N'hésitez pas à le personnaliser selon vos besoins spécifiques.

J'espère que cela vous convient ! Si vous avez d'autres questions, n'hésitez pas à demander.
