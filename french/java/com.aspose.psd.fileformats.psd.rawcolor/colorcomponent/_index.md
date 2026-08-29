---
title: "ColorComponent"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Le composant couleur est une abstraction de la valeur de canal et de la valeur de canal."
type: docs
weight: 10
url: /fr/java/com.aspose.psd.fileformats.psd.rawcolor/colorcomponent/
---

**Inheritance:**
java.lang.Object
```
public final class ColorComponent
```

Le composant de couleur est une abstraction de Channel Value et Channel Value. Toute couleur est composée d'un tableau de ColorComponent
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ColorComponent(byte bitDepth, String fullName)](#ColorComponent-byte-java.lang.String-) | Initialise une nouvelle instance de la classe [ColorComponent](../../com.aspose.psd.fileformats.psd.rawcolor/colorcomponent). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBitDepth()](#getBitDepth--) | Obtient la profondeur de bits du Color Component/Channel |
| [getClass()](#getClass--) |  |
| [getDescription()](#getDescription--) | Obtient la description du Color Component |
| [getFullName()](#getFullName--) | Obtient le nom complet du composant de couleur avec le nom et la description séparés par des espaces |
| [getName()](#getName--) | Obtient le nom du composant de couleur. |
| [getPermittedFullNames()](#getPermittedFullNames--) | Obtient les noms complets autorisés. |
| [getValue()](#getValue--) | Obtient ou définit la valeur. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setValue(long value)](#setValue-long-) | Obtient ou définit la valeur. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ColorComponent(byte bitDepth, String fullName) {#ColorComponent-byte-java.lang.String-}
```
public ColorComponent(byte bitDepth, String fullName)
```


Initialise une nouvelle instance de la classe [ColorComponent](../../com.aspose.psd.fileformats.psd.rawcolor/colorcomponent). Veuillez vérifier

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| profondeurDeBit | byte | La profondeur de bits. |
| fullName | java.lang.String | Le nom complet. |

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
### getBitDepth() {#getBitDepth--}
```
public final byte getBitDepth()
```


Obtient la profondeur de bits du Color Component/Channel

Valeur : La profondeur de bits.

**Returns:**
byte
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDescription() {#getDescription--}
```
public final String getDescription()
```


Obtient la description du Color Component

Valeur : La description.

**Returns:**
java.lang.String
### getFullName() {#getFullName--}
```
public final String getFullName()
```


Obtient le nom complet du composant de couleur avec le nom et la description séparés par des espaces

Valeur : Le nom complet.

**Returns:**
java.lang.String
### getName() {#getName--}
```
public final String getName()
```


Obtient le nom du composant de couleur.

Valeur : Le nom.

**Returns:**
java.lang.String
### getPermittedFullNames() {#getPermittedFullNames--}
```
public static String[] getPermittedFullNames()
```


Obtient les noms complets autorisés.

Valeur : Les noms complets autorisés.

**Returns:**
java.lang.String[]
### getValue() {#getValue--}
```
public final long getValue()
```


Obtient ou définit la valeur. Veuillez noter que si vous essayez de définir une valeur supérieure à ce qui peut être stocké dans la profondeur de bits actuelle, vous obtiendrez une exception

Valeur: la valeur.

**Returns:**
long
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setValue(long value) {#setValue-long-}
```
public final void setValue(long value)
```


Obtient ou définit la valeur. Veuillez noter que si vous essayez de définir une valeur supérieure à ce qui peut être stocké dans la profondeur de bits actuelle, vous obtiendrez une exception

Valeur: la valeur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long |  |

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

