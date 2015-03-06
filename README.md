
# 1. Pré-requis

Avoir installé Sublime Text 3

# 2. Installation

On clone le repo suivant où on le souhaite, par exemple "~/work/config"

On se positionne dans le répertoire de configuration propre à un utilisateur dans Sublime Text 3
/!\ Attention ce chemin peut évidemment varier selon les OS et les versions de Sublime Text

  cd ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/User

On fait les liens symboliques pour les fichiers concernés

	ln -s ~/work/config/my_sublime_text_config/Default\ \(OSX\).sublime-keymap Default\ \(OSX\).sublime-keymap

  ln -s ~/work/config/my_sublime_text_config/Preferences.sublime-settings Preferences.sublime-settings

  ln -s ~/work/config/my_sublime_text_config/WordCount.sublime-settings WordCount.sublime-settings

On tient à jour ses configurations Sublime Text dans GitHub, c'est tout et c'est déjà pas mal :)