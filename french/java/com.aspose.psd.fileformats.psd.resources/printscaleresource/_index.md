---
title: "PrintScaleResource"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Ressource d'échelle d'impression"
type: docs
weight: 31
url: /fr/java/com.aspose.psd.fileformats.psd.resources/printscaleresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.ResourceBlock](../../com.aspose.psd.fileformats.psd/resourceblock)
```
public final class PrintScaleResource extends ResourceBlock
```

Ressource d'échelle d'impression
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PrintScaleResource()](#PrintScaleResource--) | Initialise une nouvelle instance de la classe [PrintScaleResource](../../com.aspose.psd.fileformats.psd.resources/printscaleresource). |
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
| [getDataSize()](#getDataSize--) | Obtient la taille des données de la ressource en octets. |
| [getID()](#getID--) | Obtient ou définit l'identifiant unique de la ressource. |
| [getMinimalVersion()](#getMinimalVersion--) | Obtient la version minimale requise du PSD. |
| [getName()](#getName--) | Obtient ou définit le nom de la ressource. |
| [getScale()](#getScale--) | Obtient ou définit l'échelle. |
| [getSignature()](#getSignature--) | Obtient la signature de la ressource. |
| [getSize()](#getSize--) | Obtient la taille du bloc de ressource en octets, y compris ses données. |
| [getStyle()](#getStyle--) | Obtient ou définit le style. |
| [getXLocation()](#getXLocation--) | Obtient ou définit la position x. |
| [getYLocation()](#getYLocation--) | Obtient ou définit la position y. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer stream)](#save-com.aspose.psd.StreamContainer-) | Enregistre le bloc de ressource dans le flux spécifié. |
| [setID(short value)](#setID-short-) | Obtient ou définit l'identifiant unique de la ressource. |
| [setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)](#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-) | Obtient ou définit les informations de calque et de masque. |
| [setName(String value)](#setName-java.lang.String-) | Obtient ou définit le nom de la ressource. |
| [setScale(float value)](#setScale-float-) | Obtient ou définit l'échelle. |
| [setSignature_internalized(int signature)](#setSignature-internalized-int-) |  |
| [setState_internalized(int value)](#setState-internalized-int-) | Obtient ou définit l'état du bloc de ressource. |
| [setStyle(short value)](#setStyle-short-) | Obtient ou définit le style. |
| [setXLocation(float value)](#setXLocation-float-) | Obtient ou définit la position x. |
| [setYLocation(float value)](#setYLocation-float-) | Obtient ou définit la position y. |
| [toString()](#toString--) |  |
| [validateValues()](#validateValues--) | Valide les valeurs de la ressource. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PrintScaleResource() {#PrintScaleResource--}
```
public PrintScaleResource()
```


Initialise une nouvelle instance de la classe [PrintScaleResource](../../com.aspose.psd.fileformats.psd.resources/printscaleresource).

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
### getScale() {#getScale--}
```
public final float getScale()
```


Obtient ou définit l'échelle.

Valeur : l'échelle.

**Returns:**
float
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
### getStyle() {#getStyle--}
```
public final short getStyle()
```


Obtient ou définit le style.

Valeur : le style.

**Returns:**
short
### getXLocation() {#getXLocation--}
```
public final float getXLocation()
```


Obtient ou définit la position x.

Valeur : la position x.

**Returns:**
float
### getYLocation() {#getYLocation--}
```
public final float getYLocation()
```


Obtient ou définit la position y.

Valeur : la position y.

**Returns:**
float
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

### setScale(float value) {#setScale-float-}
```
public final void setScale(float value)
```


Obtient ou définit l'échelle.

Valeur : l'échelle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float |  |

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

### setStyle(short value) {#setStyle-short-}
```
public final void setStyle(short value)
```


Obtient ou définit le style.

Valeur : le style.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | short |  |

### setXLocation(float value) {#setXLocation-float-}
```
public final void setXLocation(float value)
```


Obtient ou définit la position x.

Valeur : la position x.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float |  |

### setYLocation(float value) {#setYLocation-float-}
```
public final void setYLocation(float value)
```


Obtient ou définit la position y.

Valeur : la position y.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float |  |

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

