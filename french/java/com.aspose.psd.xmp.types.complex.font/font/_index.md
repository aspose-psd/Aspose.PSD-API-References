---
title: "Font"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Représente la police XMP."
type: docs
weight: 10
url: /fr/java/com.aspose.psd.xmp.types.complex.font/font/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.types.XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase), [com.aspose.psd.xmp.types.complex.ComplexTypeBase](../../com.aspose.psd.xmp.types.complex/complextypebase)
```
public final class Font extends ComplexTypeBase
```

Représente la police XMP.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Font()](#Font--) | Initialise une nouvelle instance de la classe Font. |
| [Font(String fontFamily)](#Font-java.lang.String-) | Initialise une nouvelle instance de la classe Font. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [add(String key, Object value)](#add-java.lang.String-java.lang.Object-) | Ajoute la clé spécifiée. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getChildFontFiles()](#getChildFontFiles--) | Obtient ou définit le tableau des noms de fichiers pour les polices qui composent une police composite. |
| [getClass()](#getClass--) |  |
| [getFontFace()](#getFontFace--) | Obtient ou définit le style de police. |
| [getFontFamily()](#getFontFamily--) | Obtient ou définit la famille de police. |
| [getFontFileName()](#getFontFileName--) | Obtient ou définit le nom de fichier de police sans le chemin complet. |
| [getFontName()](#getFontName--) | Obtient ou définit le nom de police PostScript. |
| [getFontType()](#getFontType--) | Obtient ou définit le type de police. |
| [getNamespaceUri()](#getNamespaceUri--) | Obtient l'URI de l'espace de noms par défaut. |
| [getPrefix()](#getPrefix--) | Obtient le préfixe. |
| [getVersion()](#getVersion--) | Obtient ou définit la version de la police. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Obtient la valeur de chaîne contenue au format XMP. |
| [hashCode()](#hashCode--) |  |
| [isComposite()](#isComposite--) | Obtient ou définit une valeur indiquant si cette police est composite. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setChildFontFiles(String[] value)](#setChildFontFiles-java.lang.String---) | Obtient ou définit le tableau des noms de fichiers pour les polices qui composent une police composite. |
| [setComposite(boolean value)](#setComposite-boolean-) | Obtient ou définit une valeur indiquant si cette police est composite. |
| [setFontFace(String value)](#setFontFace-java.lang.String-) | Obtient ou définit le style de police. |
| [setFontFamily(String value)](#setFontFamily-java.lang.String-) | Obtient ou définit la famille de police. |
| [setFontFileName(String value)](#setFontFileName-java.lang.String-) | Obtient ou définit le nom de fichier de police sans le chemin complet. |
| [setFontName(String value)](#setFontName-java.lang.String-) | Obtient ou définit le nom de police PostScript. |
| [setFontType(String value)](#setFontType-java.lang.String-) | Obtient ou définit le type de police. |
| [setVersion(String value)](#setVersion-java.lang.String-) | Obtient ou définit la version de la police. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Font() {#Font--}
```
public Font()
```


Initialise une nouvelle instance de la classe Font.

### Font(String fontFamily) {#Font-java.lang.String-}
```
public Font(String fontFamily)
```


Initialise une nouvelle instance de la classe Font.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fontFamily | java.lang.String | Famille de police. |

### add(String key, Object value) {#add-java.lang.String-java.lang.Object-}
```
public void add(String key, Object value)
```


Ajoute la clé spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| clé | java.lang.String | La représentation sous forme de chaîne de la clé qui est identifiée avec la valeur ajoutée. |
| valeur | java.lang.Object | La valeur à ajouter à. |

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
### getChildFontFiles() {#getChildFontFiles--}
```
public String[] getChildFontFiles()
```


Obtient ou définit le tableau des noms de fichiers pour les polices qui composent une police composite.

Valeur : Le tableau des noms de fichiers pour les polices qui composent une police composite.

**Returns:**
java.lang.String[]
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFontFace() {#getFontFace--}
```
public String getFontFace()
```


Obtient ou définit le style de police.

Valeur : Le style de police.

**Returns:**
java.lang.String
### getFontFamily() {#getFontFamily--}
```
public String getFontFamily()
```


Obtient ou définit la famille de police.

Valeur : La famille de police.

**Returns:**
java.lang.String
### getFontFileName() {#getFontFileName--}
```
public String getFontFileName()
```


Obtient ou définit le nom de fichier de police sans le chemin complet.

Valeur : Le nom du fichier de police sans le chemin complet.

**Returns:**
java.lang.String
### getFontName() {#getFontName--}
```
public String getFontName()
```


Obtient ou définit le nom de police PostScript.

Valeur : Le nom de la police PostScript.

**Returns:**
java.lang.String
### getFontType() {#getFontType--}
```
public String getFontType()
```


Obtient ou définit le type de police.

TrueType, Type 1, Open Type, etc. Valeur : Le type de police.

**Returns:**
java.lang.String
### getNamespaceUri() {#getNamespaceUri--}
```
public String getNamespaceUri()
```


Obtient l'URI de l'espace de noms par défaut.

**Returns:**
java.lang.String - L'URI d'espace de noms par défaut.
### getPrefix() {#getPrefix--}
```
public String getPrefix()
```


Obtient le préfixe.

**Returns:**
java.lang.String - Le préfixe.
### getVersion() {#getVersion--}
```
public String getVersion()
```


Obtient ou définit la version de la police.

/version pour les polices Type1 nameId 5 pour Apple True Type et OpenType /CIDFontVersion pour les polices CID La chaîne vide pour les polices bitmap Valeur : La version de la police.

**Returns:**
java.lang.String
### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Obtient la valeur de chaîne contenue au format XMP.

**Returns:**
java.lang.String - Retourne la valeur de chaîne contenue au format XMP.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isComposite() {#isComposite--}
```
public boolean isComposite()
```


Obtient ou définit une valeur indiquant si cette police est composite.

Valeur :  true  si cette police est composite ; sinon,  false .

**Returns:**
booléen
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setChildFontFiles(String[] value) {#setChildFontFiles-java.lang.String---}
```
public void setChildFontFiles(String[] value)
```


Obtient ou définit le tableau des noms de fichiers pour les polices qui composent une police composite.

Valeur : Le tableau des noms de fichiers pour les polices qui composent une police composite.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String[] |  |

### setComposite(boolean value) {#setComposite-boolean-}
```
public void setComposite(boolean value)
```


Obtient ou définit une valeur indiquant si cette police est composite.

Valeur :  true  si cette police est composite ; sinon,  false .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setFontFace(String value) {#setFontFace-java.lang.String-}
```
public void setFontFace(String value)
```


Obtient ou définit le style de police.

Valeur : Le style de police.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setFontFamily(String value) {#setFontFamily-java.lang.String-}
```
public void setFontFamily(String value)
```


Obtient ou définit la famille de police.

Valeur : La famille de police.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setFontFileName(String value) {#setFontFileName-java.lang.String-}
```
public void setFontFileName(String value)
```


Obtient ou définit le nom de fichier de police sans le chemin complet.

Valeur : Le nom du fichier de police sans le chemin complet.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setFontName(String value) {#setFontName-java.lang.String-}
```
public void setFontName(String value)
```


Obtient ou définit le nom de police PostScript.

Valeur : Le nom de la police PostScript.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setFontType(String value) {#setFontType-java.lang.String-}
```
public void setFontType(String value)
```


Obtient ou définit le type de police.

TrueType, Type 1, Open Type, etc. Valeur : Le type de police.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setVersion(String value) {#setVersion-java.lang.String-}
```
public void setVersion(String value)
```


Obtient ou définit la version de la police.

/version pour les polices Type1 nameId 5 pour Apple True Type et OpenType /CIDFontVersion pour les polices CID La chaîne vide pour les polices bitmap Valeur : La version de la police.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
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

