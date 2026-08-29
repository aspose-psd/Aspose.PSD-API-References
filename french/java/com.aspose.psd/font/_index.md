---
title: "Font"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Définit un format particulier pour le texte incluant la police, la taille et les attributs de style."
type: docs
weight: 46
url: /fr/java/com.aspose.psd/font/
---

**Inheritance:**
java.lang.Object
```
public final class Font
```

Définit un format particulier pour le texte, incluant la police, la taille et les attributs de style. Cette classe ne peut pas être héritée.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Font(Font prototype, int newStyle)](#Font-com.aspose.psd.Font-int-) | Initialise une nouvelle  com.aspose.psd.Font  qui utilise le  com.aspose.psd.Font  existant spécifié et l'énumération  com.aspose.psd.FontStyle . |
| [Font(String fontName, float emSize)](#Font-java.lang.String-float-) | Initialise un nouveau  com.aspose.psd.Font  en utilisant une taille spécifiée. |
| [Font(String fontName, float emSize, int style)](#Font-java.lang.String-float-int-) | Initialise un nouveau  com.aspose.psd.Font  en utilisant une taille et un style spécifiés. |
| [Font(String fontName, float emSize, int style, int unit, int characterSet)](#Font-java.lang.String-float-int-int-int-) | Initialise un nouveau  com.aspose.psd.Font  en utilisant une taille, un style, une unité et un jeu de caractères spécifiés. |
| [Font(String fontName, float emSize, int style, int unit)](#Font-java.lang.String-float-int-int-) | Initialise un nouveau  com.aspose.psd.Font  en utilisant une taille, un style et une unité spécifiés. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [deepClone()](#deepClone--) | Crée une copie profonde exacte de ce  Font . |
| [equals(Object obj)](#equals-java.lang.Object-) | Indique si l'objet spécifié est un  com.aspose.psd.Font  et possède les mêmes valeurs de propriétés que ce  com.aspose.psd.Font . |
| [getBold()](#getBold--) | Obtient une valeur indiquant si ce  Font  est en gras. |
| [getCharacterSet()](#getCharacterSet--) | Obtient une valeur byte qui spécifie le jeu de caractères utilisé par ce  Font . |
| [getClass()](#getClass--) |  |
| [getItalic()](#getItalic--) | Obtient une valeur indiquant si ce  Font  est en italique. |
| [getName()](#getName--) | Obtient le nom de la police de ce  Font . |
| [getSize()](#getSize--) | Obtient la taille en em de ce  Font  mesurée dans les unités spécifiées par la propriété  P:Aspose.Imaging.Font.Unit . |
| [getStrikeout()](#getStrikeout--) | Obtient une valeur indiquant si ce  Font  spécifie une ligne horizontale traversant la police. |
| [getStyle()](#getStyle--) | Obtient les informations de style pour ce  Font . |
| [getUnderline()](#getUnderline--) | Obtient une valeur indiquant si ce  Font  est souligné. |
| [getUnit()](#getUnit--) | Obtient l'unité de mesure de ce  Font . |
| [hashCode()](#hashCode--) | Obtient le code de hachage de ce  com.aspose.psd.Font . |
| [makeFontWithGraphUnit(String fontName, float emSize, int unit)](#makeFontWithGraphUnit-java.lang.String-float-int-) | Initialise un nouveau  com.aspose.psd.Font  en utilisant une taille et une unité spécifiées. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Renvoie une représentation sous forme de chaîne lisible par l'homme de ce  com.aspose.psd.Font . |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Font(Font prototype, int newStyle) {#Font-com.aspose.psd.Font-int-}
```
public Font(Font prototype, int newStyle)
```


Initialise une nouvelle  com.aspose.psd.Font  qui utilise le  com.aspose.psd.Font  existant spécifié et l'énumération  com.aspose.psd.FontStyle .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| prototype | [Font](../../com.aspose.psd/font) | Le  com.aspose.psd.Font  existant à partir duquel créer le nouveau  com.aspose.psd.Font . |
| newStyle | int | Le  com.aspose.psd.FontStyle  à appliquer au nouveau  com.aspose.psd.Font . Plusieurs valeurs de l'énumération  com.aspose.psd.FontStyle  peuvent être combinées avec l'opérateur OR. |

### Font(String fontName, float emSize) {#Font-java.lang.String-float-}
```
public Font(String fontName, float emSize)
```


Initialise un nouveau  com.aspose.psd.Font  en utilisant une taille spécifiée. Le jeu de caractères est défini sur  F:Aspose.Imaging.CharacterSet.Default , l'unité graphique sur  F:Aspose.Imaging.GraphicsUnit.Point , le style de police sur  F:Aspose.Imaging.FontStyle.Regular .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fontName | java.lang.String | Une représentation sous forme de chaîne du nom du  com.aspose.psd.Font . |
| emSize | float | La taille en em, en points, de la nouvelle police. |

### Font(String fontName, float emSize, int style) {#Font-java.lang.String-float-int-}
```
public Font(String fontName, float emSize, int style)
```


Initialise un nouveau com.aspose.psd.Font en utilisant une taille et un style spécifiés. Le jeu de caractères est défini sur F:Aspose.Imaging.CharacterSet.Default, l'unité graphique sur F:Aspose.Imaging.GraphicsUnit.Point.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fontName | java.lang.String | Une représentation sous forme de chaîne du nom du  com.aspose.psd.Font . |
| emSize | float | La taille en em, en points, de la nouvelle police. |
| style | int | Le com.aspose.psd.FontStyle de la nouvelle police. |

### Font(String fontName, float emSize, int style, int unit, int characterSet) {#Font-java.lang.String-float-int-int-int-}
```
public Font(String fontName, float emSize, int style, int unit, int characterSet)
```


Initialise un nouveau  com.aspose.psd.Font  en utilisant une taille, un style, une unité et un jeu de caractères spécifiés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fontName | java.lang.String | Une représentation sous forme de chaîne du nom du  com.aspose.psd.Font . |
| emSize | float | La taille en em de la nouvelle police dans les unités spécifiées par le paramètre unit. |
| style | int | Le com.aspose.psd.FontStyle de la nouvelle police. |
| unité | int | Le com.aspose.psd.GraphicsUnit de la nouvelle police. |
| characterSet | int | Un jeu de caractères à utiliser pour cette police. |

### Font(String fontName, float emSize, int style, int unit) {#Font-java.lang.String-float-int-int-}
```
public Font(String fontName, float emSize, int style, int unit)
```


Initialise un nouveau  com.aspose.psd.Font  en utilisant une taille, un style et une unité spécifiés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fontName | java.lang.String | Une représentation sous forme de chaîne du nom du  com.aspose.psd.Font . |
| emSize | float | La taille en em de la nouvelle police dans les unités spécifiées par le paramètre unit. |
| style | int | Le com.aspose.psd.FontStyle de la nouvelle police. |
| unité | int | Le com.aspose.psd.GraphicsUnit de la nouvelle police. |

### deepClone() {#deepClone--}
```
public Font deepClone()
```


Crée une copie profonde exacte de ce  Font .

**Returns:**
[Font](../../com.aspose.psd/font) - The  Font  this method creates.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Indique si l'objet spécifié est un  com.aspose.psd.Font  et possède les mêmes valeurs de propriétés que ce  com.aspose.psd.Font .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | L'objet à tester. |

**Returns:**
booléen - true si le paramètre obj est un com.aspose.psd.Font et possède les mêmes valeurs de propriétés que ce com.aspose.psd.Font ; sinon, false.
### getBold() {#getBold--}
```
public boolean getBold()
```


Obtient une valeur indiquant si ce  Font  est en gras.

**Returns:**
booléen - true si cette Font est en gras ; sinon, false.
### getCharacterSet() {#getCharacterSet--}
```
public int getCharacterSet()
```


Obtient une valeur byte qui spécifie le jeu de caractères utilisé par ce  Font .

**Returns:**
int - Un jeu de caractères utilisé par cette Font.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getItalic() {#getItalic--}
```
public boolean getItalic()
```


Obtient une valeur indiquant si ce  Font  est en italique.

**Returns:**
booléen - true si cette Font est en italique ; sinon, false.
### getName() {#getName--}
```
public String getName()
```


Obtient le nom de la police de ce  Font .

**Returns:**
java.lang.String - Une représentation sous forme de chaîne du nom de la police de cette Font.
### getSize() {#getSize--}
```
public float getSize()
```


Obtient la taille en em de ce  Font  mesurée dans les unités spécifiées par la propriété  P:Aspose.Imaging.Font.Unit .

**Returns:**
float - La taille en em de cette Font.
### getStrikeout() {#getStrikeout--}
```
public boolean getStrikeout()
```


Obtient une valeur indiquant si ce  Font  spécifie une ligne horizontale traversant la police.

**Returns:**
booléen - true si cette Font possède une ligne horizontale traversante ; sinon, false.
### getStyle() {#getStyle--}
```
public int getStyle()
```


Obtient les informations de style pour ce  Font .

**Returns:**
int - Une énumération FontStyle contenant les informations de style pour cette Font.
### getUnderline() {#getUnderline--}
```
public boolean getUnderline()
```


Obtient une valeur indiquant si ce  Font  est souligné.

**Returns:**
booléen - true si cette Font est soulignée ; sinon, false.
### getUnit() {#getUnit--}
```
public int getUnit()
```


Obtient l'unité de mesure de ce  Font .

**Returns:**
int - Un GraphicsUnit qui représente l'unité de mesure de cette Font.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Obtient le code de hachage de ce  com.aspose.psd.Font .

**Returns:**
int - Le code de hachage de ce com.aspose.psd.Font.
### makeFontWithGraphUnit(String fontName, float emSize, int unit) {#makeFontWithGraphUnit-java.lang.String-float-int-}
```
public static Font makeFontWithGraphUnit(String fontName, float emSize, int unit)
```


Initialise un nouveau com.aspose.psd.Font en utilisant une taille et une unité spécifiées. Le jeu de caractères est défini sur F:Aspose.Imaging.CharacterSet.Default, le style est défini sur F:Aspose.Imaging.FontStyle.Regular.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fontName | java.lang.String | Une représentation sous forme de chaîne du nom du  com.aspose.psd.Font . |
| emSize | float | La taille en em de la nouvelle police dans les unités spécifiées par le paramètre unit. |
| unité | int | Le com.aspose.psd.GraphicsUnit de la nouvelle police. |

**Returns:**
[Font](../../com.aspose.psd/font)
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### toString() {#toString--}
```
public String toString()
```


Renvoie une représentation sous forme de chaîne lisible par l'homme de ce  com.aspose.psd.Font .

**Returns:**
java.lang.String - Une chaîne qui représente ce com.aspose.psd.Font.
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

