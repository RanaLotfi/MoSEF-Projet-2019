# Projet de Linux - M2 MoSEF 
### Rana Mohamed Amr Lotfi 

## Le Script: 
Le script search_fichiers.sh a pour but de demander à l'utilisateur de choisir un répertoire, ensuite de saisir des mots clés ou expressions pour effectuer une recherche dans le répertoire choisi.
Pour lancer le script, il est appelé par `bash search_fichiers.sh paramètre1 paramètre2`. L'utilisateur peut specifier un ou deux arguments: 
- Le premier: Le nom du fichier recherché
- Le deuxième: Une expression à rechercher dans le fichier. 
Le script permet d'effectuer une recherche simple (de fichiers) ou complexe (conditioné par une expression dans le fichier).

## L'utilisateur: 
Après le lancement du programme, après que l'utilisateur specifie les arguments/paramètres dans la ligne du code de lancement, le 
programme annoncera la bienvenu à l'utilisateur, en spécifiant la date d'utilisation du code. 
Ensuite, le programme demande à l'utilisateur le nom du répertoire à ouvrir. L'utilisateur est censé donner le chemin relatif à
son propre homme (le programme intègre déjà le /home/$UTILISATEUR dans le code, donc il suffit de mettre le chemin relatif à ce 
dernier). 

## Recherche de Fichiers
Après ceci, le programme recherche automatiquement les fichiers qui correspondent au arguments spécifié par l'utilisateur lors du
lancement du programme. 

Voici un exemple de saisie et de résultat: 
```
bash search_fichiers.sh etats.* northern

Bienvenu sorbonne, nous sommes le dimanche 17 2019.
Quel repertoire vous interesse aujourd'hui? Documents
Nous cherchons le(s) fichier(s) compatible(s) avec le nom que vous aviez mis en argument
./etats.txt:Northern Mariana Islands
```
  
