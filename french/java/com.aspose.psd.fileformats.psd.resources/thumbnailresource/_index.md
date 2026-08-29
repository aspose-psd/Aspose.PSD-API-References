---
title: "ThumbnailResource"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Le bloc de ressource de vignette."
type: docs
weight: 36
url: /fr/java/com.aspose.psd.fileformats.psd.resources/thumbnailresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.ResourceBlock](../../com.aspose.psd.fileformats.psd/resourceblock)
```
public class ThumbnailResource extends ResourceBlock
```

Le bloc de ressource de vignette.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ThumbnailResource()](#ThumbnailResource--) | Initialise une nouvelle instance de la classe [ThumbnailResource](../../com.aspose.psd.fileformats.psd.resources/thumbnailresource). |
## Champs

| Champ | Description |
| --- | --- |
| [ResouceBlockMeSaSignature](#ResouceBlockMeSaSignature) | La signature de ressource d'ImageReady. |
| [ResouceBlockSignature](#ResouceBlockSignature) | La signature de ressource Photoshop standard. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBitsPixel()](#getBitsPixel--) | Obtient ou définit les bits pixel. |
| [getClass()](#getClass--) |  |
| [getDataSize()](#getDataSize--) | Obtient la taille des données de la ressource en octets. |
| [getFormat()](#getFormat--) | Obtient ou définit le format des données de la vignette. |
| [getHeight()](#getHeight--) | Obtient ou définit la hauteur de la vignette en pixels. |
| [getID()](#getID--) | Obtient ou définit l'identifiant unique de la ressource. |
| [getJpegOptions()](#getJpegOptions--) | Obtient ou définit les options JPEG. |
| [getMinimalVersion()](#getMinimalVersion--) | Obtient la version minimale requise du psd. |
| [getName()](#getName--) | Obtient ou définit le nom de la ressource. |
| [getPlanesCount()](#getPlanesCount--) | Obtient ou définit le nombre de plans. |
| [getSignature()](#getSignature--) | Obtient la signature de la ressource. |
| [getSize()](#getSize--) | Obtient la taille du bloc de ressource en octets, y compris ses données. |
| [getSizeAfterCompression()](#getSizeAfterCompression--) | Obtient ou définit la taille après compression. |
| [getThumbnailArgb32Data()](#getThumbnailArgb32Data--) | Obtient ou définit les données de la vignette ARGB 32 bits. |
| [getThumbnailData()](#getThumbnailData--) | Obtient ou définit les données de la vignette. |
| [getTotalSize()](#getTotalSize--) | Obtient la taille totale des données. |
| [getWidth()](#getWidth--) | Obtient ou définit la largeur de la vignette en pixels. |
| [getWidthBytes()](#getWidthBytes--) | Obtient la largeur de ligne en octets. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer stream)](#save-com.aspose.psd.StreamContainer-) | Enregistre le bloc de ressource dans le flux spécifié. |
| [setBitsPixel(short value)](#setBitsPixel-short-) | Obtient ou définit les bits pixel. |
| [setFormat(int value)](#setFormat-int-) | Obtient ou définit le format des données de la vignette. |
| [setHeight(int value)](#setHeight-int-) | Obtient ou définit la hauteur de la vignette en pixels. |
| [setID(short value)](#setID-short-) | Obtient ou définit l'identifiant unique de la ressource. |
| [setJpegOptions(JpegOptions value)](#setJpegOptions-com.aspose.psd.imageoptions.JpegOptions-) | Obtient ou définit les options JPEG. |
| [setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)](#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-) | Obtient ou définit les informations de calque et de masque. |
| [setName(String value)](#setName-java.lang.String-) | Obtient ou définit le nom de la ressource. |
| [setPlanesCount(short value)](#setPlanesCount-short-) | Obtient ou définit le nombre de plans. |
| [setSignature_internalized(int signature)](#setSignature-internalized-int-) |  |
| [setState_internalized(int value)](#setState-internalized-int-) | Obtient ou définit l'état du bloc de ressource. |
| [setThumbnailArgb32Data(int[] value)](#setThumbnailArgb32Data-int---) | Obtient ou définit les données de la vignette ARGB 32 bits. |
| [setThumbnailData(Color[] value)](#setThumbnailData-com.aspose.psd.Color---) | Obtient ou définit les données de la vignette. |
| [setWidth(int value)](#setWidth-int-) | Obtient ou définit la largeur de la vignette en pixels. |
| [toString()](#toString--) |  |
| [validateValues()](#validateValues--) | Valide les valeurs de la ressource. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ThumbnailResource() {#ThumbnailResource--}
```
public ThumbnailResource()
```


Initialise une nouvelle instance de la classe [ThumbnailResource](../../com.aspose.psd.fileformats.psd.resources/thumbnailresource).

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
### getBitsPixel() {#getBitsPixel--}
```
public final short getBitsPixel()
```


Obtient ou définit les bits pixel.

Valeur: les bits pixel de la vignette.

**Returns:**
short
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
### getFormat() {#getFormat--}
```
public final int getFormat()
```


Obtient ou définit le format des données de la vignette.

Valeur: le format des données de la miniature.

**Returns:**
int
### getHeight() {#getHeight--}
```
public final int getHeight()
```


Obtient ou définit la hauteur de la vignette en pixels.

Valeur: la hauteur de la miniature.

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
### getJpegOptions() {#getJpegOptions--}
```
public final JpegOptions getJpegOptions()
```


Obtient ou définit les options JPEG. Convient lorsque la ressource de miniature est enregistrée uniquement au format de fichier JPEG. Cette option n’a aucun effet lorsque le format RAW est défini.

Valeur: les options JPEG.

**Returns:**
[JpegOptions](../../com.aspose.psd.imageoptions/jpegoptions)
### getMinimalVersion() {#getMinimalVersion--}
```
public int getMinimalVersion()
```


Obtient la version minimale requise du psd.

Valeur: la version minimale du psd.

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
### getPlanesCount() {#getPlanesCount--}
```
public final short getPlanesCount()
```


Obtient ou définit le nombre de plans.

Valeur: le nombre de plans de la miniature.

**Returns:**
short
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
### getSizeAfterCompression() {#getSizeAfterCompression--}
```
public final int getSizeAfterCompression()
```


Obtient ou définit la taille après compression. Utilisé pour la vérification de cohérence.

Valeur: la taille après compression.

**Returns:**
int
### getThumbnailArgb32Data() {#getThumbnailArgb32Data--}
```
public final int[] getThumbnailArgb32Data()
```


Obtient ou définit les données de la vignette ARGB 32 bits.

Valeur: les données de la miniature ARGB 32 bits.

**Returns:**
int[]
### getThumbnailData() {#getThumbnailData--}
```
public final Color[] getThumbnailData()
```


Obtient ou définit les données de la vignette.

Valeur: les données de la miniature.

**Returns:**
com.aspose.psd.Color[]
### getTotalSize() {#getTotalSize--}
```
public final int getTotalSize()
```


Obtient la taille totale des données.

Valeur: la taille totale des données.

**Returns:**
int
### getWidth() {#getWidth--}
```
public final int getWidth()
```


Obtient ou définit la largeur de la vignette en pixels.

Valeur: la largeur de la miniature.

**Returns:**
int
### getWidthBytes() {#getWidthBytes--}
```
public final int getWidthBytes()
```


Obtient la largeur de ligne en octets.

Valeur: la largeur de ligne en octets.

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

### setBitsPixel(short value) {#setBitsPixel-short-}
```
public final void setBitsPixel(short value)
```


Obtient ou définit les bits pixel.

Valeur: les bits pixel de la vignette.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | short |  |

### setFormat(int value) {#setFormat-int-}
```
public final void setFormat(int value)
```


Obtient ou définit le format des données de la vignette.

Valeur: le format des données de la miniature.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Obtient ou définit la hauteur de la vignette en pixels.

Valeur: la hauteur de la miniature.

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

### setJpegOptions(JpegOptions value) {#setJpegOptions-com.aspose.psd.imageoptions.JpegOptions-}
```
public final void setJpegOptions(JpegOptions value)
```


Obtient ou définit les options JPEG. Convient lorsque la ressource de miniature est enregistrée uniquement au format de fichier JPEG. Cette option n’a aucun effet lorsque le format RAW est défini.

Valeur: les options JPEG.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [JpegOptions](../../com.aspose.psd.imageoptions/jpegoptions) |  |

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

### setPlanesCount(short value) {#setPlanesCount-short-}
```
public final void setPlanesCount(short value)
```


Obtient ou définit le nombre de plans.

Valeur: le nombre de plans de la miniature.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | short |  |

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

### setThumbnailArgb32Data(int[] value) {#setThumbnailArgb32Data-int---}
```
public final void setThumbnailArgb32Data(int[] value)
```


Obtient ou définit les données de la vignette ARGB 32 bits.

Valeur: les données de la miniature ARGB 32 bits.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int[] |  |

### setThumbnailData(Color[] value) {#setThumbnailData-com.aspose.psd.Color---}
```
public final void setThumbnailData(Color[] value)
```


Obtient ou définit les données de la vignette.

Valeur: les données de la miniature.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Color\[\]](../../com.aspose.psd/color) |  |

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Obtient ou définit la largeur de la vignette en pixels.

Valeur: la largeur de la miniature.

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

