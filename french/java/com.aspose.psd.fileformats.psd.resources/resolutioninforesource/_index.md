---
title: "ResolutionInfoResource"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "La ressource d'information de résolution"
type: docs
weight: 33
url: /fr/java/com.aspose.psd.fileformats.psd.resources/resolutioninforesource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.ResourceBlock](../../com.aspose.psd.fileformats.psd/resourceblock)
```
public final class ResolutionInfoResource extends ResourceBlock
```

La ressource d'information de résolution
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ResolutionInfoResource()](#ResolutionInfoResource--) | Initialise une nouvelle instance de la classe [ResolutionInfoResource](../../com.aspose.psd.fileformats.psd.resources/resolutioninforesource). |
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
| [getHDpi()](#getHDpi--) | DPI horizontal. |
| [getHResDisplayUnit()](#getHResDisplayUnit--) | Unités d'affichage pour la résolution horizontale. |
| [getHeightDisplayUnit()](#getHeightDisplayUnit--) | Obtient ou définit l'unité d'affichage de la hauteur. |
| [getID()](#getID--) | Obtient ou définit l'identifiant unique de la ressource. |
| [getMinimalVersion()](#getMinimalVersion--) | Obtient la version minimale requise du PSD. |
| [getName()](#getName--) | Obtient ou définit le nom de la ressource. |
| [getSignature()](#getSignature--) | Obtient la signature de la ressource. |
| [getSize()](#getSize--) | Obtient la taille du bloc de ressource en octets, y compris ses données. |
| [getVDpi()](#getVDpi--) | DPI vertical. |
| [getVResDisplayUnit()](#getVResDisplayUnit--) | Unités d'affichage pour la résolution verticale. |
| [getWidthDisplayUnit()](#getWidthDisplayUnit--) | Obtient ou définit l'unité d'affichage de la largeur. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer stream)](#save-com.aspose.psd.StreamContainer-) | Enregistre le bloc de ressource dans le flux spécifié. |
| [setHDpi(FixedPointDecimal value)](#setHDpi-com.aspose.psd.fileformats.psd.resources.FixedPointDecimal-) | DPI horizontal. |
| [setHResDisplayUnit(int value)](#setHResDisplayUnit-int-) | Unités d'affichage pour la résolution horizontale. |
| [setHeightDisplayUnit(int value)](#setHeightDisplayUnit-int-) | Obtient ou définit l'unité d'affichage de la hauteur. |
| [setID(short value)](#setID-short-) | Obtient ou définit l'identifiant unique de la ressource. |
| [setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)](#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-) | Obtient ou définit les informations de calque et de masque. |
| [setName(String value)](#setName-java.lang.String-) | Obtient ou définit le nom de la ressource. |
| [setSignature_internalized(int signature)](#setSignature-internalized-int-) |  |
| [setState_internalized(int value)](#setState-internalized-int-) | Obtient ou définit l'état du bloc de ressource. |
| [setVDpi(FixedPointDecimal value)](#setVDpi-com.aspose.psd.fileformats.psd.resources.FixedPointDecimal-) | DPI vertical. |
| [setVResDisplayUnit(int value)](#setVResDisplayUnit-int-) | Unités d'affichage pour la résolution verticale. |
| [setWidthDisplayUnit(int value)](#setWidthDisplayUnit-int-) | Obtient ou définit l'unité d'affichage de la largeur. |
| [toString()](#toString--) |  |
| [validateValues()](#validateValues--) | Valide les valeurs de la ressource. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ResolutionInfoResource() {#ResolutionInfoResource--}
```
public ResolutionInfoResource()
```


Initialise une nouvelle instance de la classe [ResolutionInfoResource](../../com.aspose.psd.fileformats.psd.resources/resolutioninforesource).

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
### getHDpi() {#getHDpi--}
```
public final FixedPointDecimal getHDpi()
```


DPI horizontal.

Valeur : le DPI horizontal.

**Returns:**
[FixedPointDecimal](../../com.aspose.psd.fileformats.psd.resources/fixedpointdecimal)
### getHResDisplayUnit() {#getHResDisplayUnit--}
```
public final int getHResDisplayUnit()
```


Unités d'affichage pour la résolution horizontale. Cela n'affecte que l'interface utilisateur ; la résolution est toujours stockée dans le fichier PSD en pixels/pouce.

Valeur : l'unité d'affichage de la résolution horizontale.

**Returns:**
int
### getHeightDisplayUnit() {#getHeightDisplayUnit--}
```
public final int getHeightDisplayUnit()
```


Obtient ou définit l'unité d'affichage de la hauteur.

Valeur : l'unité d'affichage de la hauteur.

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
### getVDpi() {#getVDpi--}
```
public final FixedPointDecimal getVDpi()
```


DPI vertical.

Valeur : le DPI vertical.

**Returns:**
[FixedPointDecimal](../../com.aspose.psd.fileformats.psd.resources/fixedpointdecimal)
### getVResDisplayUnit() {#getVResDisplayUnit--}
```
public final int getVResDisplayUnit()
```


Unités d'affichage pour la résolution verticale.

Valeur : l'unité d'affichage de la résolution verticale.

**Returns:**
int
### getWidthDisplayUnit() {#getWidthDisplayUnit--}
```
public final int getWidthDisplayUnit()
```


Obtient ou définit l'unité d'affichage de la largeur.

Valeur : l'unité d'affichage de la largeur.

**Returns:**
int
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

### setHDpi(FixedPointDecimal value) {#setHDpi-com.aspose.psd.fileformats.psd.resources.FixedPointDecimal-}
```
public final void setHDpi(FixedPointDecimal value)
```


DPI horizontal.

Valeur : le DPI horizontal.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [FixedPointDecimal](../../com.aspose.psd.fileformats.psd.resources/fixedpointdecimal) |  |

### setHResDisplayUnit(int value) {#setHResDisplayUnit-int-}
```
public final void setHResDisplayUnit(int value)
```


Unités d'affichage pour la résolution horizontale. Cela n'affecte que l'interface utilisateur ; la résolution est toujours stockée dans le fichier PSD en pixels/pouce.

Valeur : l'unité d'affichage de la résolution horizontale.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setHeightDisplayUnit(int value) {#setHeightDisplayUnit-int-}
```
public final void setHeightDisplayUnit(int value)
```


Obtient ou définit l'unité d'affichage de la hauteur.

Valeur : l'unité d'affichage de la hauteur.

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

### setVDpi(FixedPointDecimal value) {#setVDpi-com.aspose.psd.fileformats.psd.resources.FixedPointDecimal-}
```
public final void setVDpi(FixedPointDecimal value)
```


DPI vertical.

Valeur : le DPI vertical.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [FixedPointDecimal](../../com.aspose.psd.fileformats.psd.resources/fixedpointdecimal) |  |

### setVResDisplayUnit(int value) {#setVResDisplayUnit-int-}
```
public final void setVResDisplayUnit(int value)
```


Unités d'affichage pour la résolution verticale.

Valeur : l'unité d'affichage de la résolution verticale.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setWidthDisplayUnit(int value) {#setWidthDisplayUnit-int-}
```
public final void setWidthDisplayUnit(int value)
```


Obtient ou définit l'unité d'affichage de la largeur.

Valeur : l'unité d'affichage de la largeur.

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

