
Petite technique pour sauvegarder et versionner votre configuration sur les préférences dans Submime Text.

# 1. Pré-requis

Avoir installé [Sublime Text 2](http://www.sublimetext.com/2) ou [Sublime Text 3](http://www.sublimetext.com/3) sur votre OS.

# 2. Installation

## 2.1 Cloner le repository

On clone le repository suivant où on le souhaite, par exemple dans `~/work/config`

	cd ~/work/config

	git clone https://github.com/alvinberthelot/my_sublime_text_settings.git

## 2.2 Identifier le répertoire Sublime Text approprié

Il faut désormais connaître le chemin du répertoire approprié à Sublime Text qui doit contenir votre configuration.

⚠ **Attention** le chemin du répertoire peut évidemment varier selon les OS et les versions de Sublime Text.

Un exemple sous Mac OS avec Sublime Text 3 : `~/Library/Application\ Support/Sublime\ Text\ 3/Packages/User`

Pour connaître votre chemin de répertoire, vous pouvez utiliser `Sublime Text > Preferences > Browse Packages...` dans le menu de Sublime Text.

## 2.3 Réaliser les liens

	ln -s ~/work/config/my_sublime_text_settings/*.sublime-settings  ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/User

⚠ **Attention** cette commande est valable si le repository a été cloné dans `~/work/config` et si votre répertoire Sublime Text est le suivant `~/Library/Application\ Support/Sublime\ Text\ 3/Packages/User`.

On démarre/redémarre Sublime Text pour bien appliquer la configuration.

On tient à jour ses configurations Sublime Text dans GitHub, c'est tout et c'est déjà pas mal :)
