---
title: "UrlListResource"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Ressource de liste d'URL"
type: docs
weight: 40
url: /fr/java/com.aspose.psd.fileformats.psd.resources/urllistresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.ResourceBlock](../../com.aspose.psd.fileformats.psd/resourceblock)
```
public final class UrlListResource extends ResourceBlock
```

Ressource de liste d'URL
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [UrlListResource()](#UrlListResource--) | Initialise une nouvelle instance de la classe [UrlListResource](../../com.aspose.psd.fileformats.psd.resources/urllistresource). |
## Champs

| Champ | Description |
| --- | --- |
| [ResouceBlockMeSaSignature](#ResouceBlockMeSaSignature) | La signature de ressource d'ImageReady. |
| [ResouceBlockSignature](#ResouceBlockSignature) | La signature de ressource Photoshop standard. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | Obtient ou définit le nombre. |
| [getDataSize()](#getDataSize--) | Obtient la taille des données de la ressource en octets. |
| [getID()](#getID--) | Obtient ou définit l'identifiant unique de la ressource. |
| [getIds()](#getIds--) | Obtient ou définit les ids. |
| [getLongs()](#getLongs--) | Obtient ou définit les longs. |
| [getMinimalVersion()](#getMinimalVersion--) | Obtient la version minimale requise du PSD. |
| [getName()](#getName--) | Obtient ou définit le nom de la ressource. |
| [getSignature()](#getSignature--) | Obtient la signature de la ressource. |
| [getSize()](#getSize--) | Obtient la taille du bloc de ressource en octets, y compris ses données. |
| [getTexts()](#getTexts--) | Obtient ou définit les textes. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer stream)](#save-com.aspose.psd.StreamContainer-) | Enregistre le bloc de ressource dans le flux spécifié. |
| [setCount(int value)](#setCount-int-) | Obtient ou définit le nombre. |
| [setID(short value)](#setID-short-) | Obtient ou définit l'identifiant unique de la ressource. |
| [setIds(int[] value)](#setIds-int---) | Obtient ou définit les ids. |
| [setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)](#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-) | Obtient ou définit les informations de calque et de masque. |
| [setLongs(int[] value)](#setLongs-int---) | Obtient ou définit les longs. |
| [setName(String value)](#setName-java.lang.String-) | Obtient ou définit le nom de la ressource. |
| [setSignature_internalized(int signature)](#setSignature-internalized-int-) |  |
| [setState_internalized(int value)](#setState-internalized-int-) | Obtient ou définit l'état du bloc de ressource. |
| [setTexts(String[] value)](#setTexts-java.lang.String---) | Obtient ou définit les textes. |
| [toString()](#toString--) |  |
| [validateValues()](#validateValues--) | Valide les valeurs de la ressource. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### UrlListResource() {#UrlListResource--}
```
public UrlListResource()
```


Initialise une nouvelle instance de la classe [UrlListResource](../../com.aspose.psd.fileformats.psd.resources/urllistresource).

### ResouceBlockMeSaSignature {#ResouceBlockMeSaSignature}
```
public static final int ResouceBlockMeSaSignature
```


La signature de ressource d'ImageReady.

### ResouceBlockSignature {#ResouceBlockSignature}
```
public static final int ResouceBlockSignature
```


La signature de ressource Photoshop standard.

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCount() {#getCount--}
```
public final int getCount()
```


Obtient ou définit le nombre.

Valeur : Le nombre.

**Returns:**
int
### getDataSize() {#getDataSize--}
```
public int getDataSize()
```


Obtient la taille des données de la ressource en octets.

Valeur : la taille des données de la ressource.

**Returns:**
int
### getID() {#getID--}
```
public final short getID()
```


Obtient ou définit l'identifiant unique de la ressource.

Valeur : l'identifiant unique de la ressource.

**Returns:**
short
### getIds() {#getIds--}
```
public final int[] getIds()
```


Obtient ou définit les ids.

Valeur : les ids.

**Returns:**
int[]
### getLongs() {#getLongs--}
```
public final int[] getLongs()
```


Obtient ou définit les longs.

Valeur : les longs.

**Returns:**
int[]
### getMinimalVersion() {#getMinimalVersion--}
```
public int getMinimalVersion()
```


Obtient la version minimale requise du PSD.

Valeur : la version minimale du PSD.

**Returns:**
int
### getName() {#getName--}
```
public final String getName()
```


Obtient ou définit le nom de la ressource. Chaîne Pascal, remplie pour rendre la taille paire (un nom nul consiste en deux octets de 0).

Valeur : le nom de la ressource.

**Returns:**
java.lang.String
### getSignature() {#getSignature--}
```
public final int getSignature()
```


Obtient la signature de la ressource. Doit toujours être « 8BIM ».

Valeur : la signature de la ressource.

**Returns:**
int
### getSize() {#getSize--}
```
public final int getSize()
```


Obtient la taille du bloc de ressource en octets, y compris ses données.

Valeur : la taille du bloc de ressource.

**Returns:**
int
### getTexts() {#getTexts--}
```
public final String[] getTexts()
```


Obtient ou définit les textes.

Valeur : les textes.

**Returns:**
java.lang.String[]
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




### save(StreamContainer stream) {#save-com.aspose.psd.StreamContainer-}
```
public final void save(StreamContainer stream)
```


Enregistre le bloc de ressource dans le flux spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.psd/streamcontainer) | Le flux dans lequel enregistrer le bloc de ressource. |

### setCount(int value) {#setCount-int-}
```
public final void setCount(int value)
```


Obtient ou définit le nombre.

Valeur : Le nombre.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setID(short value) {#setID-short-}
```
public final void setID(short value)
```


Obtient ou définit l'identifiant unique de la ressource.

Valeur : l'identifiant unique de la ressource.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | short |  |

### setIds(int[] value) {#setIds-int---}
```
public final void setIds(int[] value)
```


Obtient ou définit les ids.

Valeur : les ids.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int[] |  |

### setLayerAndMaskInfo_internalized(LayerAndMaskInfo value) {#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-}
```
public final void setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)
```


Obtient ou définit les informations de calque et de masque.

Valeur : les informations de calque et de masque.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo |  |

### setLongs(int[] value) {#setLongs-int---}
```
public final void setLongs(int[] value)
```


Obtient ou définit les longs.

Valeur : les longs.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int[] |  |

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Obtient ou définit le nom de la ressource. Chaîne Pascal, remplie pour rendre la taille paire (un nom nul consiste en deux octets de 0).

Valeur : le nom de la ressource.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setSignature_internalized(int signature) {#setSignature-internalized-int-}
```
public void setSignature_internalized(int signature)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| signature | int |  |

### setState_internalized(int value) {#setState-internalized-int-}
```
public final void setState_internalized(int value)
```


Obtient ou définit l'état du bloc de ressource.

Valeur : l'état du bloc de ressource.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setTexts(String[] value) {#setTexts-java.lang.String---}
```
public final void setTexts(String[] value)
```


Obtient ou définit les textes.

Valeur : les textes.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String[] |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### validateValues() {#validateValues--}
```
public void validateValues()
```


Valide les valeurs de la ressource.

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

