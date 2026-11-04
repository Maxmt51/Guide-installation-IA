Auteur : TRUCHON Maxime, MARTINET Quentin

# 1 Créer un compte Git Hub
=> Demander l'accès au groupe AI4Health@Daisy-Lig

# 2 Installer Github Desktop 
Github Dekstop : Outil de gestion de version.
Il permet : 
- Cloner un projet
- Voir les modifications effectuées, 
- Faire des commits ; enregister une version d'un travail avec un message
- Envoyer et récupérer des changements en ligne. 
- Revenir en arrière pour accéder à une version antérieure. 

=> Penser à vérifier les composants de son ordinateur, pour installer les bonnes versions. 
   => Explorateur de fichier => Ce PC => Propriétés

# 3 Installer VS Code
- Se rendre sur le site : https://code.visualstudio.com/download?_exp_download=d53503e735 
- Installer VS code

# 4 Installer Python
- Aller sur le site web : https://ai4health-daisy-lig.github.io/ 
- Cliquer sur l'onglet "Teaching"
    => Python4Beginners
    => Set up you scientific programming workspace
- Suivre les instruction via la page web: https://ai4health-daisy-lig.github.io/python4beginners/tutorial.html?lesson=setup pour bien installer Python. 

# 5 Créer un dossier "code" 
Exemple: 
- Cliquer sur "Acer" => "utilisateurs"=> "maxim"=> Création du fichier code. 
- Créer un premier sous dossier, qui constituera le premier projet. 

# 6 Installer uv 
-Suivre les instruction via la page web: https://ai4health-daisy-lig.github.io/python4beginners/tutorial.html?lesson=setup pour créer l'espace d'environnement virtuel.

# 7 Sélectionner le modèle avec lequel on souhaite travailler.
- Identifier le modèle pertinent pour nos besoins : https://ia.numerique.gouv.fr/outils-ia/albert-api/mod%C3%A8les/ 
 - Se rendre sur le site web : https://ia.numerique.gouv.fr/outils-ia/albert-api/
 - Récupérer une clé API via : https://albert.playground.etalab.gouv.fr/keys
 - Placer cette clé, dans un fichier .env du fichier du projet avec : 
    => OPENAI_API_BASE=
    => OPENAI_API_KEY=

# 8 Récupérer les fichiers de configuration 

- Se rendre sur le site : https://github.com/AI4Health-DAISY-LIG
- Cliquer sur AI-configs
- Sélectionner la branche à la place de main => aider-albert-integration
- Sélectionner le "aider" que l'on a besoin, en fonction du modèle avec lequel on souhaite travailler (ex: albert, ollama, ...)
- Dans notre cas, nous avons besoin de aider-albert     
    =>cliquer sur aider-albert
- Cliquer sur Gemma (Modèle choisi à l'aide de : https://ia.numerique.gouv.fr/outils-ia/albert-api/mod%C3%A8les/)
- Récuper les fichiers suivants : 
    =>.aider.conf.yml
    =>.aider.model.metadata.json
=> Glisser ces fichiers dans le dossier du projet dans lequel on souhaite travailler. 
- Récupérer le fichier 
    => .gitignore
=> Glisser ces fichiers dans le dossier du projet dans lequel on souhaite travailler. 

# 9 Activer "aider"
- Se rendre sur le site de Aider : https://aider.chat/
- Cliquer sur documentation 
    => Installation
Installer  aider:
    => python -m pip install aider-install
    =>aider-install
-> aider --no-auto-commits

# 10 Un architecte du code avec lequel nous pouvons discuter apparait !

# Questions 

1. Où enregistrer nos modules d'imports d'un .env, sans enregistrer tout sur notre PC ? 
2. Quels sont les besoins spécifiques lorsque l'on créer un nouveau projet ? 
3. Comment savoir si l'on doit effectuer des ajustements dans le global, et pas dans le projet déjà existant ? 
4. Ou glisser nos .md file, pour ranger ça proprement par rapport à notre projet ? 