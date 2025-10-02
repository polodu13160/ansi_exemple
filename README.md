Visualiser les couleurs ANSI dans VS Code
Pour afficher correctement les couleurs et les styles contenus dans les fichiers .ansi (comme test.ansi), vous aurez besoin de deux extensions pour une expérience optimale dans Visual Studio Code.

1. vscode-icons
Cette extension permet d'assigner une icône spécifique aux fichiers .ansi dans l'explorateur de fichiers, ce qui les rend plus faciles à repérer. Elle ne s'occupe pas de l'affichage des couleurs dans l'éditeur.

Extension : vscode-icons
Configuration : Vous pouvez ajouter une association personnalisée dans votre settings.json si nécessaire.
2. ANSI Colors
C'est l'extension essentielle qui interprète les séquences d'échappement ANSI ([31m, [1m, etc.) et affiche le texte en couleur et avec les styles correspondants (gras, souligné...) directement dans l'éditeur.



RECAP
Extension : ANSI Colors / vscode-icons
Utilisation
Installez les deux extensions depuis la Marketplace de VS Code.
Ouvrez simplement le fichier .ansi dans l'éditeur. Les couleurs devraient s'afficher automatiquement.
