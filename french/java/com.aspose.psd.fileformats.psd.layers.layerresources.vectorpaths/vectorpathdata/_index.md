---
title: "VectorPathData"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "La classe pour travailler avec un chemin vectoriel."
type: docs
weight: 18
url: /fr/java/com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathdata/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.IVectorPathData](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/ivectorpathdata)
```
public final class VectorPathData implements IVectorPathData
```

La classe pour travailler avec un chemin vectoriel.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [VectorPathData(byte[] data)](#VectorPathData-byte---) | Initialise une nouvelle instance de la classe [VectorPathData](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathdata). |
| [VectorPathData()](#VectorPathData--) | Initialise une nouvelle instance de la classe [VectorPathData](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathdata). |
## Champs

| Champ | Description |
| --- | --- |
| [SizeOfTheGeneralInfo_internalized](#SizeOfTheGeneralInfo-internalized) | La taille des informations générales comme la version et les indicateurs. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAsByteArray_internalized()](#getAsByteArray-internalized--) | Obtient sous forme de tableau d'octets. |
| [getClass()](#getClass--) |  |
| [getLength()](#getLength--) | Obtient la longueur des données du chemin vectoriel dans la ressource en octets. |
| [getPaths()](#getPaths--) | Obtient ou définit les enregistrements de chemin. |
| [getVersion()](#getVersion--) | Obtient ou définit la version. |
| [hashCode()](#hashCode--) |  |
| [isDisabled()](#isDisabled--) | Obtient ou définit une valeur indiquant si cette instance est désactivée. |
| [isInverted()](#isInverted--) | Obtient ou définit une valeur indiquant si cette instance est inversée. |
| [isNotLinked()](#isNotLinked--) | Obtient ou définit une valeur indiquant si cette instance n’est pas liée. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDisabled(boolean value)](#setDisabled-boolean-) | Obtient ou définit une valeur indiquant si cette instance est désactivée. |
| [setInverted(boolean value)](#setInverted-boolean-) | Obtient ou définit une valeur indiquant si cette instance est inversée. |
| [setNotLinked(boolean value)](#setNotLinked-boolean-) | Obtient ou définit une valeur indiquant si cette instance n’est pas liée. |
| [setPaths(VectorPathRecord[] value)](#setPaths-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorPathRecord---) | Obtient ou définit les enregistrements de chemin. |
| [setVersion(int value)](#setVersion-int-) | Obtient ou définit la version. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### VectorPathData(byte[] data) {#VectorPathData-byte---}
```
public VectorPathData(byte[] data)
```


Initialise une nouvelle instance de la classe [VectorPathData](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathdata).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| données | byte[] | Les données de la ressource. |

### VectorPathData() {#VectorPathData--}
```
public VectorPathData()
```


Initialise une nouvelle instance de la classe [VectorPathData](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathdata).

### SizeOfTheGeneralInfo_internalized {#SizeOfTheGeneralInfo-internalized}
```
public static final int SizeOfTheGeneralInfo_internalized
```


La taille des informations générales comme la version et les indicateurs.

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
### getAsByteArray_internalized() {#getAsByteArray-internalized--}
```
public final byte[] getAsByteArray_internalized()
```


Obtient sous forme de tableau d'octets.

**Returns:**
byte[] - La ressource sous forme de tableau d'octets.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getLength() {#getLength--}
```
public final int getLength()
```


Obtient la longueur des données du chemin vectoriel dans la ressource en octets.

**Returns:**
int
### getPaths() {#getPaths--}
```
public final VectorPathRecord[] getPaths()
```


Obtient ou définit les enregistrements de chemin.

Valeur: les chemins.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorPathRecord[]
### getVersion() {#getVersion--}
```
public final int getVersion()
```


Obtient ou définit la version.

Valeur : la version.

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isDisabled() {#isDisabled--}
```
public final boolean isDisabled()
```


Obtient ou définit une valeur indiquant si cette instance est désactivée.

Valeur:  true  si cette instance est désactivée; sinon,  false .

**Returns:**
booléen
### isInverted() {#isInverted--}
```
public final boolean isInverted()
```


Obtient ou définit une valeur indiquant si cette instance est inversée.

Valeur:  true  si cette instance est inversée; sinon,  false .

**Returns:**
booléen
### isNotLinked() {#isNotLinked--}
```
public final boolean isNotLinked()
```


Obtient ou définit une valeur indiquant si cette instance n’est pas liée.

Valeur :  true  si cette instance n'est pas liée ; sinon,  false .

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




### setDisabled(boolean value) {#setDisabled-boolean-}
```
public final void setDisabled(boolean value)
```


Obtient ou définit une valeur indiquant si cette instance est désactivée.

Valeur:  true  si cette instance est désactivée; sinon,  false .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setInverted(boolean value) {#setInverted-boolean-}
```
public final void setInverted(boolean value)
```


Obtient ou définit une valeur indiquant si cette instance est inversée.

Valeur:  true  si cette instance est inversée; sinon,  false .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setNotLinked(boolean value) {#setNotLinked-boolean-}
```
public final void setNotLinked(boolean value)
```


Obtient ou définit une valeur indiquant si cette instance n’est pas liée.

Valeur :  true  si cette instance n'est pas liée ; sinon,  false .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setPaths(VectorPathRecord[] value) {#setPaths-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorPathRecord---}
```
public final void setPaths(VectorPathRecord[] value)
```


Obtient ou définit les enregistrements de chemin.

Valeur: les chemins.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [VectorPathRecord\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathrecord) |  |

### setVersion(int value) {#setVersion-int-}
```
public final void setVersion(int value)
```


Obtient ou définit la version.

Valeur : la version.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

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

