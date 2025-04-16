# EN - TokyoDracula - VSCode Theme

## 🌙 Description

Welcome to **TokyoDracula**, a **Visual Studio Code** theme that combines the visual elegance of **Tokyo Night Storm** with the vibrancy of **Dracula**, softened to provide optimal visual comfort, even during long development sessions.

As a big fan of both themes, I decided to mix them according to my own taste to create something truly unique. The result? A refined dark interface with punchy yet never aggressive syntax highlighting. Whether you're debugging at 2 AM or prototyping a brilliant idea, TokyoDracula remains easy on the eyes and pleasant to use.

It's a look I love, and I hope you'll enjoy it as much as I do!

---

## 🎨 Color Palette

| Element                  | Selectors                                                   | Color       | Emoji     |
|--------------------------|--------------------------------------------------------------|-------------|-----------|
| Functions                | `entity.name.function`                                       | `#66f7a1`   | 🔧        |
| Methods                  | `meta.method-call`, `entity.name.method`                     | `#66f7a1`   | 🧱        |
| Variables                | `variable`, `variable.other`                                 | `#F8F8F2`   | 📦        |
| Parameters               | `variable.parameter`                                         | `#f4a96b`   | 🎯        |
| Constants                | `constant`, `variable.other.constant`                        | `#a88ffb`   | 🧠        |
| Numbers                  | `constant.numeric`                                           | `#a88ffb`   | 📏        |
| Types / Classes          | `entity.name.type`, `entity.name.class`                      | `#7ecdf2`   | 📚        |
| Keywords                 | `keyword`, `storage.type`, `storage.modifier`                | `#e666b4`   | ⚡        |
| Strings                  | `string`, `string.quoted`                                    | `#e4d97a`   | 💬        |
| Comments                 | `comment`, `punctuation.definition.comment`                  | `#6272A4`   | 💡        |
| Operators                | `keyword.operator`, `punctuation`                            | `#e666b4`   | 🔣        |
| Support (built-ins)      | `support`, `support.function`, `support.class`               | `#7ecdf2`   | 🧩        |
| Decorators / Annotations | `meta.decorator`, `storage.type.annotation`                  | `#66f7a1`   | 🎀        |

---

## ⚙️ Installation (local use)

### 1. Download or clone the project

- **Option 1**: [Download the ZIP](https://github.com/OscarLaude/tokyodraculatheme/archive/refs/heads/main.zip), then unzip it.
- **Option 2**: Clone this repository via Git:

```bash
git clone https://github.com/OscarLaude/tokyodraculatheme.git
```

### 2. Modifying Visual Studio Code parameters

1. Open **Visual Studio Code**.
2. Open the **Command palette** with `Ctrl+Shift+P`.
3. Type and select: `Preferences: Open User Settings (JSON)`.
4. Add the following line to the bottom of the file :

```bash
"typescript.semanticHighlighting.enabled": true
```

### 3. Install the extension in VSCode

1. Open **Visual Studio Code**
2. Open the **Command Palette** with `Ctrl+Shift+P`
3. Type and select: `Extensions: Install from VSIX...`
4. Choose the `.vsix` file you generated (for example: `tokyodracula-1.0.0.vsix`)

✅ Once installed, activate the theme via the **Theme Preferences** in VSCode.

And there you go, the theme is set up! 🌈

## 🛠 Customization (optional)

Want to go even further with customization?
Visual Studio Code allows you to manually modify theme colors via user settings.

### Example override:

```json
"editor.tokenColorCustomizations": {
  "textMateRules": [
    {
      "scope": "keyword.operator",
      "settings": {
        "foreground": "#e666b4"
      }
    }
  ]
}
```

## ✨ Happy coding!

TokyoDracula was designed for **strictly personal use**, with comfort and elegance in mind.
I want to clarify that I am not the author of the **Tokyo Night Storm** and **Dracula** themes. Out of respect for their creators, I will not publish this extension on the store. This is solely a blend I made for my own use, and I'm sharing it with you so you can enjoy it too.

Have fun with this theme, and may your code be as clean as your editor 😎


# FR - TokyoDracula - Thème VSCode

## 🌙 Description

Bienvenue sur **TokyoDracula**, un thème pour **Visual Studio Code** qui combine l'élégance visuelle de **Tokyo Night Storm** avec la vivacité de **Dracula**, adoucies pour offrir un confort visuel optimal, même lors de longues sessions de développement.

En tant que grand fan de ces deux thèmes, j'ai décidé de les mélanger selon mes propres goûts pour créer quelque chose de vraiment unique. Le résultat ? Une interface sombre et raffinée, avec une coloration syntaxique punchy mais jamais agressive. Que vous soyez en plein debug à 2h du matin ou en train de prototyper une idée brillante, TokyoDracula reste doux pour les yeux et agréable à utiliser.

C'est un rendu que j'adore, et j'espère qu'il vous plaira autant qu'à moi !

---

## 🎨 Palette de couleurs

| Élément                  | Sélecteurs                                                   | Couleur     | Emoji     |
|--------------------------|--------------------------------------------------------------|-------------|-----------|
| Fonctions                | `entity.name.function`                                       | `#66f7a1`   | 🔧        |
| Méthodes                 | `meta.method-call`, `entity.name.method`                     | `#66f7a1`   | 🧱        |
| Variables                | `variable`, `variable.other`                                 | `#F8F8F2`   | 📦        |
| Paramètres               | `variable.parameter`                                         | `#f4a96b`   | 🎯        |
| Constantes               | `constant`, `variable.other.constant`                        | `#a88ffb`   | 🧠        |
| Nombres                  | `constant.numeric`                                           | `#a88ffb`   | 📏        |
| Types / Classes          | `entity.name.type`, `entity.name.class`                      | `#7ecdf2`   | 📚        |
| Mots-clés                | `keyword`, `storage.type`, `storage.modifier`                | `#e666b4`   | ⚡        |
| Chaînes de caractères    | `string`, `string.quoted`                                    | `#e4d97a`   | 💬        |
| Commentaires             | `comment`, `punctuation.definition.comment`                  | `#6272A4`   | 💡        |
| Opérateurs               | `keyword.operator`, `punctuation`                            | `#e666b4`   | 🔣        |
| Support (built-ins)      | `support`, `support.function`, `support.class`               | `#7ecdf2`   | 🧩        |
| Décorateurs / Annotations| `meta.decorator`, `storage.type.annotation`                  | `#66f7a1`   | 🎀        |

---

## ⚙️ Installation (utilisation locale)

### 1. Télécharger ou cloner le projet

- **Option 1** : [Téléchargez le ZIP](https://github.com/OscarLaude/tokyodraculatheme/archive/refs/heads/main.zip), puis décompressez-le.
- **Option 2** : Clonez ce dépôt via Git :

```bash
git clone https://github.com/OscarLaude/tokyodraculatheme.git
```

### 2. Modifier les paramètres de Visual Studio Code

1. Ouvrez **Visual Studio Code**
2. Ouvrez la **Palette de commandes** avec `Ctrl+Shift+P`
3. Tapez et sélectionnez : `Preferences: Open User Settings (JSON)`
4. Ajouter la ligne suivante en bas du fichier :

```bash
"typescript.semanticHighlighting.enabled": true
```

### 3. Installer l'extension dans VSCode

1. Ouvrez **Visual Studio Code**
2. Ouvrez la **Palette de commandes** avec `Ctrl+Shift+P`
3. Tapez et sélectionnez : `Extensions: Install from VSIX...`
4. Choisissez le fichier `.vsix` que vous avez généré (par exemple : `tokyodracula-0.0.3.vsix`)

✅ Une fois installé, activez le thème via les **Préférences de thème** dans VSCode.

Et voilà, le thème est en place ! 🌈

## 🛠 Personnalisation (optionnel)

Vous souhaitez aller encore plus loin dans la personnalisation ?
Visual Studio Code permet de modifier manuellement les couleurs du thème via les paramètres utilisateur.

### Exemple d’override :

```json
"editor.tokenColorCustomizations": {
  "textMateRules": [
    {
      "scope": "keyword.operator",
      "settings": {
        "foreground": "#e666b4"
      }
    }
  ]
}
```

## ✨ Bon code !

TokyoDracula a été conçu pour une utilisation **strictement personnelle**, dans un souci de confort et d’élégance.
Je tiens à préciser que je ne suis pas l'auteur des thèmes **Tokyo Night Storm** et **Dracula**. Par respect pour leurs créateurs, je ne publierai pas cette extension sur le store. Il s'agit uniquement d'un mélange que j'ai fait pour mon propre usage, et je partage cela avec vous pour que vous puissiez en profiter également.

Amuse-toi bien avec ce thème, et que ton code soit aussi propre que ton éditeur 😎
