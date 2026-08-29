---
title: "FontSettings"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Paramètres de police du rendu des formats vectoriels d'imagerie généraux."
type: docs
weight: 47
url: /fr/java/com.aspose.psd/fontsettings/
---

**Inheritance:**
java.lang.Object
```
public final class FontSettings
```

Paramètres de police du rendu des formats vectoriels d'imagerie généraux.
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAdobeFontName(String fontFamilyName)](#getAdobeFontName-java.lang.String-) | Obtient le nom de police Adobe à partir du nom de famille de police. |
| [getClass()](#getClass--) |  |
| [getDefaultFontName()](#getDefaultFontName--) | Obtient le nom de police par défaut. |
| [getDefaultFontsFolders()](#getDefaultFontsFolders--) | Obtient les dossiers de polices par défaut. |
| [getFontReplacements(String fontName)](#getFontReplacements-java.lang.String-) | Obtient le tableau de remplacements de polices par le nom de police. |
| [getFontsFolders()](#getFontsFolders--) | Obtient une copie du tableau qui contient la liste des dossiers où Aspose.Imaging recherche les polices TrueType. |
| [getGetSystemAlternativeFont()](#getGetSystemAlternativeFont--) | Obtient ou définit une valeur indiquant si [get alternative font]. |
| [getReplacementFont(String fontName)](#getReplacementFont-java.lang.String-) | Obtient la police de remplacement la plus appropriée. |
| [hashCode()](#hashCode--) |  |
| [isFontAllowed(String fontName)](#isFontAllowed-java.lang.String-) | Détermine si [is font allowed] [the specified font name]. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeFontCacheFile()](#removeFontCacheFile--) | Supprime le fichier de cache des polices. |
| [reset()](#reset--) | Réinitialise le dossier des polices et le nom de police par défaut aux paramètres système. |
| [setAllowedFonts(String[] fontList)](#setAllowedFonts-java.lang.String---) | Restreint l'utilisation des polices à une liste de polices. |
| [setDefaultFontName(String fontName)](#setDefaultFontName-java.lang.String-) | Définit le nom de police par défaut. |
| [setFontReplacements(String fontToReplace, String[] fontNames)](#setFontReplacements-java.lang.String-java.lang.String---) | Définit la liste de remplacement des polices. |
| [setFontsFolder(String folder)](#setFontsFolder-java.lang.String-) | Remplace la liste des dossiers de polices pour le dossier |
| [setFontsFolders(String[] folders)](#setFontsFolders-java.lang.String---) | Remplace la liste des dossiers de polices pour les dossiers |
| [setFontsFolders(String[] folders, boolean recursive)](#setFontsFolders-java.lang.String---boolean-) | Définit les dossiers d'où les polices TrueType sont chargées et supprime toutes les polices chargées. |
| [setGetSystemAlternativeFont(boolean value)](#setGetSystemAlternativeFont-boolean-) | Obtient ou définit une valeur indiquant si [get alternative font]. |
| [toString()](#toString--) |  |
| [updateFonts()](#updateFonts--) | Met à jour le cache des polices pour les fichiers PSD contenant des calques de texte. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
booléen
### getAdobeFontName(String fontFamilyName) {#getAdobeFontName-java.lang.String-}
```
public static String getAdobeFontName(String fontFamilyName)
```


Obtient le nom de police Adobe à partir du nom de famille de police.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fontFamilyName | java.lang.String | Le nom de la famille de polices. |

**Returns:**
java.lang.String - Le nom de police Adobe par nom de famille de police.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDefaultFontName() {#getDefaultFontName--}
```
public static String getDefaultFontName()
```


Obtient le nom de police par défaut.

**Returns:**
java.lang.String - nom de la police par défaut
### getDefaultFontsFolders() {#getDefaultFontsFolders--}
```
public static String[] getDefaultFontsFolders()
```


Obtient les dossiers de polices par défaut.

**Returns:**
java.lang.String[] - Retourne le dossier système
### getFontReplacements(String fontName) {#getFontReplacements-java.lang.String-}
```
public static String[] getFontReplacements(String fontName)
```


Obtient le tableau de remplacements de polices par le nom de police.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fontName | java.lang.String | Nom de la police. |

**Returns:**
java.lang.String[] - Tableau des noms de remplacements pour les polices fournies
### getFontsFolders() {#getFontsFolders--}
```
public static String[] getFontsFolders()
```


Obtient une copie du tableau qui contient la liste des dossiers où Aspose.Imaging recherche les polices TrueType.

La valeur retournée est une copie des données utilisées par Aspose.Imaging. Si vous modifiez les éléments du tableau retourné, cela n'affectera pas le rendu du document. Pour spécifier de nouveaux emplacements de polices, utilisez la méthode  setFontsFolders .

**Returns:**
java.lang.String[] - Une copie des emplacements de polices actuels.
### getGetSystemAlternativeFont() {#getGetSystemAlternativeFont--}
```
public static boolean getGetSystemAlternativeFont()
```


Obtient ou définit une valeur indiquant si [get alternative font].

Valeur :  true  si [get alternative font] ; sinon,  false .

**Returns:**
booléen
### getReplacementFont(String fontName) {#getReplacementFont-java.lang.String-}
```
public static String getReplacementFont(String fontName)
```


Obtient la police de remplacement la plus appropriée. Si toutes les remplacements ne sont pas autorisées, la première police autorisée et disponible sera retournée. S'il n'y a aucune police disponible, la police fournie en argument sera retournée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fontName | java.lang.String | Nom de la police. |

**Returns:**
java.lang.String - Le nom de la police remplacée
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isFontAllowed(String fontName) {#isFontAllowed-java.lang.String-}
```
public static boolean isFontAllowed(String fontName)
```


Détermine si [is font allowed] [the specified font name].

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fontName | java.lang.String | Nom de la police. |

**Returns:**
boolean -  true  si [is font allowed] [le nom de police spécifié] ; sinon,  false .
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeFontCacheFile() {#removeFontCacheFile--}
```
public static void removeFontCacheFile()
```


Supprime le fichier de cache des polices.

### reset() {#reset--}
```
public static void reset()
```


Réinitialise le dossier des polices et le nom de police par défaut aux paramètres système.

### setAllowedFonts(String[] fontList) {#setAllowedFonts-java.lang.String---}
```
public static void setAllowedFonts(String[] fontList)
```


Restreint l'utilisation des polices par une liste de polices. Veuillez vérifier les noms réels des polices avant la restriction. Définissez la liste des polices autorisées sur Null pour supprimer les restrictions

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fontList | java.lang.String[] | La liste des polices. |

### setDefaultFontName(String fontName) {#setDefaultFontName-java.lang.String-}
```
public static void setDefaultFontName(String fontName)
```


Définit le nom de police par défaut.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fontName | java.lang.String | Le nom par défaut de la police. |

### setFontReplacements(String fontToReplace, String[] fontNames) {#setFontReplacements-java.lang.String-java.lang.String---}
```
public static void setFontReplacements(String fontToReplace, String[] fontNames)
```


Définit la liste de remplacement des polices. Si une police n'est pas autorisée, un remplacement sera trouvé. La première police de la liste sera utilisée en premier. Si elle est également restreinte, la police suivante de la liste sera sélectionnée. Si la police n'a pas de remplacements ou que tous les remplacements ne sont pas autorisés, la première police autorisée de la liste des polices autorisées sera utilisée. S'il n'existe aucune police autorisée et disponible, la bibliothèque essaiera d'utiliser la police système par défaut même si elle n'est pas autorisée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fontToReplace | java.lang.String | La police à remplacer. |
| fontNames | java.lang.String[] | Les noms des polices de remplacement par ordre de similarité. |

### setFontsFolder(String folder) {#setFontsFolder-java.lang.String-}
```
public static void setFontsFolder(String folder)
```


Remplace la liste des dossiers de polices pour le dossier

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| folder | java.lang.String | Dossier contenant les polices TrueType. |

### setFontsFolders(String[] folders) {#setFontsFolders-java.lang.String---}
```
public static void setFontsFolders(String[] folders)
```


Remplace la liste des dossiers de polices pour les dossiers

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| folders | java.lang.String[] | Tableau de dossiers |

### setFontsFolders(String[] folders, boolean recursive) {#setFontsFolders-java.lang.String---boolean-}
```
public static void setFontsFolders(String[] folders, boolean recursive)
```


Définit les dossiers d'où les polices TrueType sont chargées et supprime toutes les polices chargées. Aucun contrôle n'est effectué sur les dossiers de polices.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| folders | java.lang.String[] | Les dossiers de polices. |
| recursive | booléen | si défini sur  true  [recursive]. |

### setGetSystemAlternativeFont(boolean value) {#setGetSystemAlternativeFont-boolean-}
```
public static void setGetSystemAlternativeFont(boolean value)
```


Obtient ou définit une valeur indiquant si [get alternative font].

Valeur :  true  si [get alternative font] ; sinon,  false .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### updateFonts() {#updateFonts--}
```
public static void updateFonts()
```


Met à jour le cache des polices pour les fichiers PSD contenant des calques de texte. Cette méthode garantit que les polices du dossier fontsFolder utilisant la méthode FontSettings.setFontsFolder(fontsFolder) ou après réinitialisation des polices avec FontSettings.reset() seront prises en compte lors du traitement des fichiers PSD. Veuillez utiliser cette méthode chaque fois que FontSettings.setFontsFolder(fontsFolder) ou FontSettings.reset() est appelé pour des images PSD. Sans appeler cette méthode, aucune garantie n'est donnée que les polices seront mises à jour.

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

