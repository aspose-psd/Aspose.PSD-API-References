---
title: "LengthRecord"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Classe d'enregistrement de la longueur du sous-chemin"
type: docs
weight: 13
url: /fr/java/com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/lengthrecord/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorPathRecord](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathrecord)
```
public class LengthRecord extends VectorPathRecord
```

Classe d'enregistrement de la longueur du sous-chemin
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [LengthRecord(byte[] data)](#LengthRecord-byte---) | Initialise une nouvelle instance de la classe [LengthRecord](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/lengthrecord). |
| [LengthRecord()](#LengthRecord--) | Initialise une nouvelle instance de la classe [LengthRecord](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/lengthrecord). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBezierKnotRecordsCount()](#getBezierKnotRecordsCount--) | Obtient ou définit le nombre d'enregistrements de nœuds de Bézier. |
| [getClass()](#getClass--) |  |
| [getLength_internalized()](#getLength-internalized--) | Obtient la longueur. |
| [getPathOperations()](#getPathOperations--) | Obtient ou définit les opérations de chemin. |
| [getRecordCount()](#getRecordCount--) | Obtient ou définit le nombre d'enregistrements. |
| [getShapeIndex()](#getShapeIndex--) | Obtient ou définit l'index de la forme de chemin actuelle dans le calque. |
| [getSourceData_internalized()](#getSourceData-internalized--) | Obtenir les octets de données source originaux. |
| [getType()](#getType--) | Obtient le type. |
| [hashCode()](#hashCode--) |  |
| [isClosed()](#isClosed--) | Obtient ou définit une valeur indiquant si cette instance est fermée. |
| [isOpen()](#isOpen--) | Obtient ou définit une valeur indiquant si cette instance est ouverte. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBezierKnotRecordsCount(int value)](#setBezierKnotRecordsCount-int-) | Obtient ou définit le nombre d'enregistrements de nœuds de Bézier. |
| [setClosed(boolean value)](#setClosed-boolean-) | Obtient ou définit une valeur indiquant si cette instance est fermée. |
| [setOpen(boolean value)](#setOpen-boolean-) | Obtient ou définit une valeur indiquant si cette instance est ouverte. |
| [setPathOperations(int value)](#setPathOperations-int-) | Obtient ou définit les opérations de chemin. |
| [setRecordCount(int value)](#setRecordCount-int-) | Obtient ou définit le nombre d'enregistrements. |
| [setShapeIndex(int value)](#setShapeIndex-int-) | Obtient ou définit l'index de la forme de chemin actuelle dans le calque. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LengthRecord(byte[] data) {#LengthRecord-byte---}
```
public LengthRecord(byte[] data)
```


Initialise une nouvelle instance de la classe [LengthRecord](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/lengthrecord).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| données | byte[] | Les données de l'enregistrement. |

### LengthRecord() {#LengthRecord--}
```
public LengthRecord()
```


Initialise une nouvelle instance de la classe [LengthRecord](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/lengthrecord).

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
### getBezierKnotRecordsCount() {#getBezierKnotRecordsCount--}
```
public final int getBezierKnotRecordsCount()
```


Obtient ou définit le nombre d'enregistrements de nœuds de Bézier.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getLength_internalized() {#getLength-internalized--}
```
public final int getLength_internalized()
```


Obtient la longueur.

Valeur: La longueur.

**Returns:**
int
### getPathOperations() {#getPathOperations--}
```
public final int getPathOperations()
```


Obtient ou définit les opérations de chemin.

**Returns:**
int
### getRecordCount() {#getRecordCount--}
```
public final int getRecordCount()
```


Obtient ou définit le nombre d'enregistrements.

Valeur : Le nombre d'enregistrements.

**Returns:**
int
### getShapeIndex() {#getShapeIndex--}
```
public final int getShapeIndex()
```


Obtient ou définit l'index de la forme de chemin actuelle dans le calque.

**Returns:**
int
### getSourceData_internalized() {#getSourceData-internalized--}
```
public final byte[] getSourceData_internalized()
```


Obtenir les octets de données source originaux.

**Returns:**
byte[] - tableau d'octets.
### getType() {#getType--}
```
public short getType()
```


Obtient le type.

Valeur : le type.

**Returns:**
short
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isClosed() {#isClosed--}
```
public final boolean isClosed()
```


Obtient ou définit une valeur indiquant si cette instance est fermée.

Valeur :  true  si cette instance est fermée ; sinon,  false .

**Returns:**
booléen
### isOpen() {#isOpen--}
```
public final boolean isOpen()
```


Obtient ou définit une valeur indiquant si cette instance est ouverte.

Valeur:  true  si cette instance est ouverte; sinon,  false .

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




### setBezierKnotRecordsCount(int value) {#setBezierKnotRecordsCount-int-}
```
public final void setBezierKnotRecordsCount(int value)
```


Obtient ou définit le nombre d'enregistrements de nœuds de Bézier.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setClosed(boolean value) {#setClosed-boolean-}
```
public final void setClosed(boolean value)
```


Obtient ou définit une valeur indiquant si cette instance est fermée.

Valeur :  true  si cette instance est fermée ; sinon,  false .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setOpen(boolean value) {#setOpen-boolean-}
```
public final void setOpen(boolean value)
```


Obtient ou définit une valeur indiquant si cette instance est ouverte.

Valeur:  true  si cette instance est ouverte; sinon,  false .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setPathOperations(int value) {#setPathOperations-int-}
```
public final void setPathOperations(int value)
```


Obtient ou définit les opérations de chemin.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setRecordCount(int value) {#setRecordCount-int-}
```
public final void setRecordCount(int value)
```


Obtient ou définit le nombre d'enregistrements.

Valeur : Le nombre d'enregistrements.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setShapeIndex(int value) {#setShapeIndex-int-}
```
public final void setShapeIndex(int value)
```


Obtient ou définit l'index de la forme de chemin actuelle dans le calque.

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

