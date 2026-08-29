---
title: "Classe FontSettings"
type: docs
weight: 1370
url: /fr/python-net/aspose.psd/fontsettings/
---

**Summary:** General PSD vector formats renderer font settings.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.FontSettings

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| default_font_name [static] | chaîne | r/w | Obtient ou définit le nom par défaut de la police. |
| get_system_alternative_font [static] | bool | r/w | Obtient ou définit une valeur indiquant si [get alternative font]. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| clear_font_replacements() | Efface tous les remplacements de polices |
| [get_adobe_font_name(font_family_name)](#get_adobe_font_name_font_family_name_1) | Obtient le nom de police Adobe à partir du nom de famille de police. |
| [get_default_fonts_folders()](#get_default_fonts_folders__2) | Obtient les dossiers de polices par défaut. |
| [get_font_replacements(font_name)](#get_font_replacements_font_name_3) | Obtient le tableau des remplacements de police par le nom de police |
| [get_fonts_folders()](#get_fonts_folders__4) | Obtient une copie du tableau contenant la liste des dossiers où Aspose.Words recherche les polices TrueType. |
| [get_replacement_font(font_name)](#get_replacement_font_font_name_5) | Obtient la police de remplacement la plus appropriée.<br/>            Si toutes les remplacements ne sont pas autorisées, la première police autorisée et disponible sera renvoyée.<br/>            S'il n'y a aucune police disponible, la police fournie en argument sera renvoyée. |
| [is_font_allowed(font_name)](#is_font_allowed_font_name_6) | Détermine si [is font allowed] [le nom de police spécifié]. |
| remove_font_cache_file() | Supprime le fichier de cache des polices. |
| reset() | Réinitialise le dossier des polices et le nom de police par défaut au paramètre par défaut du système. |
| [set_allowed_fonts(font_list)](#set_allowed_fonts_font_list_7) | Restreint l'utilisation des polices par une liste de polices. Veuillez vérifier les noms réels des polices avant la restriction<br/>            Définissez la liste des polices autorisées sur Null pour supprimer les restrictions |
| [set_font_replacements(font_to_replace, font_names)](#set_font_replacements_font_to_replace_font_names_8) | Définit la liste de remplacement des polices. Si une police n'est pas autorisée, un remplacement sera trouvé.<br/>            La première police de la liste sera utilisée en premier. Si elle est également restreinte, la police suivante de la liste sera sélectionnée.<br/>            Si la police n'a pas de remplacements ou que tous les remplacements ne sont pas autorisés, la première police autorisée de la liste des polices autorisées sera utilisée.<br/>            S'il n'existe aucune police autorisée et disponible, la bibliothèque essaiera d'utiliser la police par défaut du système même si elle n'est pas autorisée. |
| [set_fonts_folder(font_folder)](#set_fonts_folder_font_folder_9) | Ceci est un raccourci vers [FontSettings.set_fonts_folders(fonts_folders, recursive)](/psd/python-net/aspose.psd/fontsettings/) pour définir un seul répertoire de polices.<br/>            Aucun contrôle n'est effectué sur le dossier des polices. |
| [set_fonts_folders(fonts_folders, recursive)](#set_fonts_folders_fonts_folders_recursive_10) | Définit les dossiers d'où les polices TrueType sont chargées et supprime toutes les polices chargées.<br/>            Aucun contrôle n'est effectué sur les dossiers de polices. |
| update_fonts() | Met à jour le cache des polices pour les fichiers PSD contenant des calques de texte. Cette méthode garantit que les polices du dossier fontsFolder utilisées<br/>            via la méthode FontSettings.SetFontsFolder(fontsFolder) ou après la réinitialisation des polices avec FontSettings.Reset() seront prises en compte lors du traitement des fichiers PSD. Veuillez utiliser cette méthode chaque fois que <br/>            FontSettings.SetFontsFolder(fontsFolder) ou FontSettings.Reset() sont appelés pour des images PSD. Sans appeler cette méthode, aucune garantie n'est donnée que les polices seront mises à jour. |


### Method: get_adobe_font_name(font_family_name)  [static] {#get_adobe_font_name_font_family_name_1}


```
 get_adobe_font_name(font_family_name) 
```

Obtient le nom de police Adobe à partir du nom de famille de police.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| font_family_name | chaîne | Le nom de la famille de polices. |

**Returns**

| Type | Description |
| :- | :- |
| chaîne | Le nom de police Adobe par nom de famille de police. |


### Method: get_default_fonts_folders()  [static] {#get_default_fonts_folders__2}


```
 get_default_fonts_folders() 
```

Obtient les dossiers de polices par défaut.

**Returns**

| Type | Description |
| :- | :- |
| chaîne | Renvoie le dossier système |


### Method: get_font_replacements(font_name)  [static] {#get_font_replacements_font_name_3}


```
 get_font_replacements(font_name) 
```

Obtient le tableau des remplacements de police par le nom de police

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| font_name | chaîne | Nom de la police. |

**Returns**

| Type | Description |
| :- | :- |
| chaîne | Tableau des noms de remplacements pour les polices fournies |


### Method: get_fonts_folders()  [static] {#get_fonts_folders__4}


```
 get_fonts_folders() 
```

Obtient une copie du tableau contenant la liste des dossiers où Aspose.Words recherche les polices TrueType.

**Returns**

| Type | Description |
| :- | :- |
| chaîne | Une copie des emplacements actuels des polices. |


### Method: get_replacement_font(font_name)  [static] {#get_replacement_font_font_name_5}


```
 get_replacement_font(font_name) 
```

Obtient la police de remplacement la plus appropriée.<br/>            Si toutes les remplacements ne sont pas autorisées, la première police autorisée et disponible sera renvoyée.<br/>            S'il n'y a aucune police disponible, la police fournie en argument sera renvoyée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| font_name | chaîne | Nom de la police. |

**Returns**

| Type | Description |
| :- | :- |
| chaîne | Le nom de la police remplacée |


### Method: is_font_allowed(font_name)  [static] {#is_font_allowed_font_name_6}


```
 is_font_allowed(font_name) 
```

Détermine si [is font allowed] [le nom de police spécifié].

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| font_name | chaîne | Nom de la police. |

**Returns**

| Type | Description |
| :- | :- |
| bool | <c>true</c> si [is font allowed] [the specified font name] ; sinon, <c>false</c>. |


### Method: set_allowed_fonts(font_list)  [static] {#set_allowed_fonts_font_list_7}


```
 set_allowed_fonts(font_list) 
```

Restreint l'utilisation des polices par une liste de polices. Veuillez vérifier les noms réels des polices avant la restriction<br/>            Définissez la liste des polices autorisées sur Null pour supprimer les restrictions

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| font_list | chaîne | La liste des polices. |

### Method: set_font_replacements(font_to_replace, font_names)  [static] {#set_font_replacements_font_to_replace_font_names_8}


```
 set_font_replacements(font_to_replace, font_names) 
```

Définit la liste de remplacement des polices. Si une police n'est pas autorisée, un remplacement sera trouvé.<br/>            La première police de la liste sera utilisée en premier. Si elle est également restreinte, la police suivante de la liste sera sélectionnée.<br/>            Si la police n'a pas de remplacements ou que tous les remplacements ne sont pas autorisés, la première police autorisée de la liste des polices autorisées sera utilisée.<br/>            S'il n'existe aucune police autorisée et disponible, la bibliothèque essaiera d'utiliser la police par défaut du système même si elle n'est pas autorisée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| font_to_replace | chaîne | La police à remplacer. |
| font_names | chaîne | Les noms des polices de remplacement par ordre de similarité. |

### Method: set_fonts_folder(font_folder)  [static] {#set_fonts_folder_font_folder_9}


```
 set_fonts_folder(font_folder) 
```

Ceci est un raccourci vers [FontSettings.set_fonts_folders(fonts_folders, recursive)](/psd/python-net/aspose.psd/fontsettings/) pour définir un seul répertoire de polices.<br/>            Aucun contrôle n'est effectué sur le dossier des polices.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| font_folder | chaîne | Le dossier des polices. |

### Method: set_fonts_folders(fonts_folders, recursive)  [static] {#set_fonts_folders_fonts_folders_recursive_10}


```
 set_fonts_folders(fonts_folders, recursive) 
```

Définit les dossiers d'où les polices TrueType sont chargées et supprime toutes les polices chargées.<br/>            Aucun contrôle n'est effectué sur les dossiers de polices.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| fonts_folders | chaîne | Les dossiers de polices. |
| récursif | bool | si défini sur <c>true</c> [recursive]. |

