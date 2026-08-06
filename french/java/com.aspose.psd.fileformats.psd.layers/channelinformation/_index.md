---
title: "InformationsCanal"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Les informations du canal."
type: docs
weight: 13
url: /fr/java/com.aspose.psd.fileformats.psd.layers/channelinformation/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Cloneable
```
public class ChannelInformation implements Cloneable
```

Les informations du canal.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ChannelInformation(short compressionMethod, int bitDepth, int psdVersion)](#ChannelInformation-short-int-int-) |  |
## Champs

| Champ | Description |
| --- | --- |
| [FullMaskChannelId_internalized](#FullMaskChannelId-internalized) | L'identifiant du canal de masque utilisateur (raster). |
| [ShortMaskChannelId_internalized](#ShortMaskChannelId-internalized) | L'identifiant du canal de masque court (raster ou vectoriel). |
| [TransparencyMaskChannelId_internalized](#TransparencyMaskChannelId-internalized) | L'identifiant du canal alpha |
## Méthodes

| Méthode | Description |
| --- | --- |
| [compressChannel_internalized(byte[] rawData, Rectangle layerBounds, Rectangle layerMaskBounds)](#compressChannel-internalized-byte---com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) | Il compresse les données du canal |
| [create_internalized(byte[] compressedData, short compressionMethod, int width, int height, PsdHeader header)](#create-internalized-byte---short-int-int-com.aspose.internal.fileformats.psd.sections.PsdHeader-) |  |
| [create_internalized(short compressionMethod, PsdHeader header)](#create-internalized-short-com.aspose.internal.fileformats.psd.sections.PsdHeader-) |  |
| [deepClone_internalized(ChannelInformation[] info)](#deepClone-internalized-com.aspose.psd.fileformats.psd.layers.ChannelInformation---) | Clone les informations de canal spécifiées. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBitDepth_internalized()](#getBitDepth-internalized--) | Obtient la profondeur de bits du canal. |
| [getChannelID()](#getChannelID--) | Obtient ou définit l'ID du canal. |
| [getClass()](#getClass--) |  |
| [getCompressionMethod()](#getCompressionMethod--) | Obtient ou définit la méthode de compression. |
| [getData_internalized()](#getData-internalized--) | Obtient ou définit les données du canal. |
| [getLength()](#getLength--) | Obtient la longueur du canal en octets. |
| [getPsdHeaderVersion_internalized()](#getPsdHeaderVersion-internalized--) | Obtient la version du PSD |
| [getUncompressedData_internalized()](#getUncompressedData-internalized--) | Obtient les données non compressées. |
| [hashCode()](#hashCode--) |  |
| [isShortMaskChannel_internalized()](#isShortMaskChannel-internalized--) | Détermine si le canal est ShortMask ou non |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [saveChannelData_internalized(StreamContainer streamContainer)](#saveChannelData-internalized-com.aspose.psd.StreamContainer-) |  |
| [saveChannelData_internalized(StreamContainer streamContainer, boolean is32BitColor)](#saveChannelData-internalized-com.aspose.psd.StreamContainer-boolean-) | Enregistre les données du canal. |
| [setChannelID(short value)](#setChannelID-short-) | Obtient ou définit l'ID du canal. |
| [setCompressedData_internalized(byte[] compressedData, int channelWidth, int channelHeight)](#setCompressedData-internalized-byte---int-int-) | Définit les données compressées. |
| [setCompressionMethod(short value)](#setCompressionMethod-short-) | Obtient ou définit la méthode de compression. |
| [setRawData_internalized(byte[] rawData, Size imageSize, Rectangle currentBounds)](#setRawData-internalized-byte---com.aspose.psd.Size-com.aspose.psd.Rectangle-) | Définit les données compressées. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ChannelInformation(short compressionMethod, int bitDepth, int psdVersion) {#ChannelInformation-short-int-int-}
```
public ChannelInformation(short compressionMethod, int bitDepth, int psdVersion)
```


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| compressionMethod | short |  |
| profondeurDeBit | int |  |
| psdVersion | int |  |

### FullMaskChannelId_internalized {#FullMaskChannelId-internalized}
```
public static final int FullMaskChannelId_internalized
```


L'identifiant du canal de masque utilisateur (raster). (si un calque possède à la fois un masque vectoriel et raster).

### ShortMaskChannelId_internalized {#ShortMaskChannelId-internalized}
```
public static final int ShortMaskChannelId_internalized
```


L'identifiant du canal de masque court (raster ou vectoriel). (si un calque n'a qu'un seul masque vectoriel ou raster mais pas les deux).

### TransparencyMaskChannelId_internalized {#TransparencyMaskChannelId-internalized}
```
public static final int TransparencyMaskChannelId_internalized
```


L'identifiant du canal alpha

### compressChannel_internalized(byte[] rawData, Rectangle layerBounds, Rectangle layerMaskBounds) {#compressChannel-internalized-byte---com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public final void compressChannel_internalized(byte[] rawData, Rectangle layerBounds, Rectangle layerMaskBounds)
```


Il compresse les données du canal

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rawData | byte[] | Les données brutes pour la compression |
| layerBounds | [Rectangle](../../com.aspose.psd/rectangle) | Les limites du calque |
| layerMaskBounds | [Rectangle](../../com.aspose.psd/rectangle) | Les limites du masque de calque |

### create_internalized(byte[] compressedData, short compressionMethod, int width, int height, PsdHeader header) {#create-internalized-byte---short-int-int-com.aspose.internal.fileformats.psd.sections.PsdHeader-}
```
public static ChannelInformation create_internalized(byte[] compressedData, short compressionMethod, int width, int height, PsdHeader header)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| compressedData | byte[] |  |
| compressionMethod | short |  |
| largeur | int |  |
| hauteur | int |  |
| en-tête | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |

**Returns:**
[ChannelInformation](../../com.aspose.psd.fileformats.psd.layers/channelinformation)
### create_internalized(short compressionMethod, PsdHeader header) {#create-internalized-short-com.aspose.internal.fileformats.psd.sections.PsdHeader-}
```
public static ChannelInformation create_internalized(short compressionMethod, PsdHeader header)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| compressionMethod | short |  |
| en-tête | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |

**Returns:**
[ChannelInformation](../../com.aspose.psd.fileformats.psd.layers/channelinformation)
### deepClone_internalized(ChannelInformation[] info) {#deepClone-internalized-com.aspose.psd.fileformats.psd.layers.ChannelInformation---}
```
public static ChannelInformation[] deepClone_internalized(ChannelInformation[] info)
```


Clone les informations de canal spécifiées.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| info | [ChannelInformation\[\]](../../com.aspose.psd.fileformats.psd.layers/channelinformation) | Les informations. |

**Returns:**
com.aspose.psd.fileformats.psd.layers.ChannelInformation[] - Le masque de calque cloné.
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
### getBitDepth_internalized() {#getBitDepth-internalized--}
```
public final int getBitDepth_internalized()
```


Obtient la profondeur de bits du canal.

**Returns:**
int
### getChannelID() {#getChannelID--}
```
public final short getChannelID()
```


Obtient ou définit l'ID du canal.

Valeur: l'ID du canal.

**Returns:**
short
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCompressionMethod() {#getCompressionMethod--}
```
public final short getCompressionMethod()
```


Obtient ou définit la méthode de compression.

Valeur: La méthode de compression.

**Returns:**
short
### getData_internalized() {#getData-internalized--}
```
public final byte[] getData_internalized()
```


Obtient ou définit les données du canal.

Valeur: Les données du canal.

**Returns:**
byte[]
### getLength() {#getLength--}
```
public final long getLength()
```


Obtient la longueur du canal en octets.

Valeur: La longueur.

**Returns:**
long
### getPsdHeaderVersion_internalized() {#getPsdHeaderVersion-internalized--}
```
public final int getPsdHeaderVersion_internalized()
```


Obtient la version du PSD

**Returns:**
int
### getUncompressedData_internalized() {#getUncompressedData-internalized--}
```
public final byte[] getUncompressedData_internalized()
```


Obtient les données non compressées.

**Returns:**
byte[] -
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isShortMaskChannel_internalized() {#isShortMaskChannel-internalized--}
```
public final boolean isShortMaskChannel_internalized()
```


Détermine si le canal est ShortMask ou non

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




### saveChannelData_internalized(StreamContainer streamContainer) {#saveChannelData-internalized-com.aspose.psd.StreamContainer-}
```
public final void saveChannelData_internalized(StreamContainer streamContainer)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) |  |

### saveChannelData_internalized(StreamContainer streamContainer, boolean is32BitColor) {#saveChannelData-internalized-com.aspose.psd.StreamContainer-boolean-}
```
public final void saveChannelData_internalized(StreamContainer streamContainer, boolean is32BitColor)
```


Enregistre les données du canal.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Le conteneur de flux où enregistrer. |
| is32BitColor | booléen | vrai si la couleur est en mode 32 bits |

### setChannelID(short value) {#setChannelID-short-}
```
public final void setChannelID(short value)
```


Obtient ou définit l'ID du canal.

Valeur: l'ID du canal.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | short |  |

### setCompressedData_internalized(byte[] compressedData, int channelWidth, int channelHeight) {#setCompressedData-internalized-byte---int-int-}
```
public final void setCompressedData_internalized(byte[] compressedData, int channelWidth, int channelHeight)
```


Définit les données compressées.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| compressedData | byte[] | Les données compressées. |
| channelWidth | int | Largeur du canal. |
| channelHeight | int | Hauteur du canal. |

### setCompressionMethod(short value) {#setCompressionMethod-short-}
```
public final void setCompressionMethod(short value)
```


Obtient ou définit la méthode de compression.

Valeur: La méthode de compression.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | short |  |

### setRawData_internalized(byte[] rawData, Size imageSize, Rectangle currentBounds) {#setRawData-internalized-byte---com.aspose.psd.Size-com.aspose.psd.Rectangle-}
```
public final void setRawData_internalized(byte[] rawData, Size imageSize, Rectangle currentBounds)
```


Définit les données compressées.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rawData | byte[] | Les données brutes. |
| imageSize | [Size](../../com.aspose.psd/size) | La taille de l'image |
| currentBounds | [Rectangle](../../com.aspose.psd/rectangle) | Les limites du channelData actuel. Si l'image est grande, elle sera divisée lors du processus et currentBounds != imageBounds |

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

