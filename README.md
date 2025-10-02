# Visualiser les couleurs ANSI du Test.ansi

Pour afficher correctement les couleurs et les styles contenus dans le fichier `test.ansi`, vous aurez besoin de **deux extensions** pour une expérience optimale dans Visual Studio Code.

## 1. vscode-icons

Cette extension permet d'**assigner une icône spécifique** aux fichiers `.ansi` dans l'explorateur de fichiers, ce qui les rend plus faciles à repérer. Elle **ne s'occupe pas de l'affichage des couleurs** dans l'éditeur.

* **Extension :** `vscode-icons`
* **Configuration :** Vous pouvez ajouter une association personnalisée dans votre `settings.json` si nécessaire.

## 2. ANSI Colors

C'est l'extension **essentielle** qui interprète les **séquences d'échappement ANSI** (`[31m`, `[1m`, etc.) et affiche le texte en **couleur** et avec les **styles correspondants** (gras, souligné...) directement dans l'éditeur.

---

## RÉCAPITULATIF

* **Extensions :** `ANSI Colors` / `vscode-icons`
* **Utilisation**
    1.  Installez les deux extensions depuis la Marketplace de VS Code.
    2.  Ouvrez simplement le fichier `.ansi` dans l'éditeur. Les couleurs devraient s'afficher automatiquement.



# Displaying ANSI Colors from Test.ansi

To correctly display the colors and styles contained in the file `test.ansi`, you will need **two extensions** for an optimal experience in Visual Studio Code.

---

## 1. vscode-icons

This extension allows you to **assign a specific icon** to `.ansi` files in the file explorer, making them easier to spot. It **does not handle the display of colors** within the editor.

* **Extension:** `vscode-icons`
* **Configuration:** You can add a custom association in your `settings.json` if necessary.

## 2. ANSI Colors

This is the **essential** extension that interprets the **ANSI escape sequences** (`[31m`, `[1m`, etc.) and displays the text in **color** and with the **corresponding styles** (bold, underline, etc.) directly in the editor.

---

## SUMMARY

* **Extensions:** `ANSI Colors` / `vscode-icons`
* **Usage**
    1.  Install both extensions from the VS Code Marketplace.
    2.  Simply open the `.ansi` file in the editor. The colors should display automatically.
