---
title: "PattResourceData"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "La classe pour stocker les données de motif pour la ressource."
type: docs
weight: 67
url: /fr/java/com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata/
---

**Inheritance:**
java.lang.Object
```
public final class PattResourceData
```

La classe pour stocker les données de motif pour la ressource [PattResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresource).
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PattResourceData()](#PattResourceData--) | Initialise une nouvelle instance de la classe [PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [createNewInstance_internalized()](#createNewInstance-internalized--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getChannelsCompressionMode_internalized()](#getChannelsCompressionMode-internalized--) | Renvoie le code de la méthode de compression obtenu à partir des canaux du motif. |
| [getClass()](#getClass--) |  |
| [getDefaultPattern_internalized()](#getDefaultPattern-internalized--) | Crée les données de motif par défaut. |
| [getHeight()](#getHeight--) | Obtient la hauteur. |
| [getImageMode()](#getImageMode--) | Obtient le mode d'image. |
| [getLength()](#getLength--) | Obtient la longueur du motif. |
| [getName()](#getName--) | Obtient ou définit le nom. |
| [getPatternData()](#getPatternData--) | Obtient les données du motif. |
| [getPatternDataArrayList_internalized()](#getPatternDataArrayList-internalized--) | La liste de tableaux mémoire. |
| [getPatternId()](#getPatternId--) | Obtient ou définit l’identifiant du motif. |
| [getVersion()](#getVersion--) | Obtient la version. |
| [getWidth()](#getWidth--) | Obtient la largeur. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer)](#save-com.aspose.psd.StreamContainer-) | Enregistre les données du motif. |
| [setHeight_internalized(short value)](#setHeight-internalized-short-) | Obtient la hauteur. |
| [setImageMode_internalized(short value)](#setImageMode-internalized-short-) | Obtient le mode d'image. |
| [setIndexColorTable_internalized(byte[] value)](#setIndexColorTable-internalized-byte---) | Obtient ou définit la table de couleurs d'index. |
| [setName(String value)](#setName-java.lang.String-) | Obtient ou définit le nom. |
| [setPattern(int[] pixels, Rectangle bounds)](#setPattern-int---com.aspose.psd.Rectangle-) | Définit le tampon de pixels du motif et la taille cible, met à jour la largeur ([.getWidth](../../null/\#getWidth)/[.setWidth(short)](../../null/\#setWidth-short-)) / la hauteur ([.getHeight](../../null/\#getHeight)/[.setHeight(short)](../../null/\#setHeight-short-)), et stocke les données pour l'enregistrement en utilisant le mode de compression par défaut (0). |
| [setPatternDataArrayList_internalized(VirtualMemoryArrayList value)](#setPatternDataArrayList-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.VirtualMemoryArrayList-) | La liste de tableaux mémoire. |
| [setPatternId(String value)](#setPatternId-java.lang.String-) | Obtient ou définit l’identifiant du motif. |
| [setPattern_internalized(int[] pixels, Rectangle bounds, byte compressionMode)](#setPattern-internalized-int---com.aspose.psd.Rectangle-byte-) | Définit le tampon de pixels du motif et la taille cible, met à jour la largeur ([.getWidth](../../null/\#getWidth)/[.setWidth(short)](../../null/\#setWidth-short-)) / la hauteur ([.getHeight](../../null/\#getHeight)/[.setHeight(short)](../../null/\#setHeight-short-)), et stocke les données pour l'enregistrement en utilisant le mode de compression spécifié. |
| [setVersion_internalized(int value)](#setVersion-internalized-int-) | Obtient la version. |
| [setWidth_internalized(short value)](#setWidth-internalized-short-) | Obtient la largeur. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PattResourceData() {#PattResourceData--}
```
public PattResourceData()
```


Initialise une nouvelle instance de la classe [PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata).

### createNewInstance_internalized() {#createNewInstance-internalized--}
```
public static PattResourceData createNewInstance_internalized()
```




**Returns:**
[PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata)
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
### getChannelsCompressionMode_internalized() {#getChannelsCompressionMode-internalized--}
```
public final byte getChannelsCompressionMode_internalized()
```


Renvoie le code de la méthode de compression obtenu à partir des canaux du motif.

**Returns:**
byte - Code de compression : 0 \\u2014 brut/non compressé ; >= 1 \\u2014 zip.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDefaultPattern_internalized() {#getDefaultPattern-internalized--}
```
public static PixelsData getDefaultPattern_internalized()
```


Crée les données de motif par défaut.

**Returns:**
[PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata) - The default pattern data.
### getHeight() {#getHeight--}
```
public final short getHeight()
```


Obtient la hauteur.

Valeur : la hauteur.

**Returns:**
short
### getImageMode() {#getImageMode--}
```
public final short getImageMode()
```


Obtient le mode d'image.

Valeur : le mode d'image.

**Returns:**
short
### getLength() {#getLength--}
```
public final int getLength()
```


Obtient la longueur du motif.

Valeur : la longueur du motif.

**Returns:**
int
### getName() {#getName--}
```
public final String getName()
```


Obtient ou définit le nom.

Valeur : Le nom.

**Returns:**
java.lang.String
### getPatternData() {#getPatternData--}
```
public final int[] getPatternData()
```


Obtient les données du motif.

Valeur: Les données du motif.

**Returns:**
int[]
### getPatternDataArrayList_internalized() {#getPatternDataArrayList-internalized--}
```
public final VirtualMemoryArrayList getPatternDataArrayList_internalized()
```


La liste de tableaux mémoire.

**Returns:**
com.aspose.internal.fileformats.psd.layers.layerresources.VirtualMemoryArrayList
### getPatternId() {#getPatternId--}
```
public final String getPatternId()
```


Obtient ou définit l’identifiant du motif.

Valeur: L'identifiant du motif.

**Returns:**
java.lang.String
### getVersion() {#getVersion--}
```
public final int getVersion()
```


Obtient la version.

Valeur : la version.

**Returns:**
int
### getWidth() {#getWidth--}
```
public final short getWidth()
```


Obtient la largeur.

Valeur : la largeur.

**Returns:**
short
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




### save(StreamContainer streamContainer) {#save-com.aspose.psd.StreamContainer-}
```
public final void save(StreamContainer streamContainer)
```


Enregistre les données du motif.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Le conteneur de flux où enregistrer. |

### setHeight_internalized(short value) {#setHeight-internalized-short-}
```
public final void setHeight_internalized(short value)
```


Obtient la hauteur.

Valeur : la hauteur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | short |  |

### setImageMode_internalized(short value) {#setImageMode-internalized-short-}
```
public final void setImageMode_internalized(short value)
```


Obtient le mode d'image.

Valeur : le mode d'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | short |  |

### setIndexColorTable_internalized(byte[] value) {#setIndexColorTable-internalized-byte---}
```
public final void setIndexColorTable_internalized(byte[] value)
```


Obtient ou définit la table de couleurs d'index.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte[] |  |

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Obtient ou définit le nom.

Valeur : Le nom.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setPattern(int[] pixels, Rectangle bounds) {#setPattern-int---com.aspose.psd.Rectangle-}
```
public final void setPattern(int[] pixels, Rectangle bounds)
```


Définit le tampon de pixels du motif et la taille cible, met à jour la largeur ([.getWidth](../../null/\#getWidth)/[.setWidth(short)](../../null/\#setWidth-short-)) / la hauteur ([.getHeight](../../null/\#getHeight)/[.setHeight(short)](../../null/\#setHeight-short-)), et stocke les données pour l'enregistrement en utilisant le mode de compression par défaut (0).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pixels | int[] | Pixels 32 bits au format 0xAARRGGBB. |
| bounds | [Rectangle](../../com.aspose.psd/rectangle) | Limites de pixels du motif. |

### setPatternDataArrayList_internalized(VirtualMemoryArrayList value) {#setPatternDataArrayList-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.VirtualMemoryArrayList-}
```
public final void setPatternDataArrayList_internalized(VirtualMemoryArrayList value)
```


La liste de tableaux mémoire.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | com.aspose.internal.fileformats.psd.layers.layerresources.VirtualMemoryArrayList |  |

### setPatternId(String value) {#setPatternId-java.lang.String-}
```
public final void setPatternId(String value)
```


Obtient ou définit l’identifiant du motif.

Valeur: L'identifiant du motif.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setPattern_internalized(int[] pixels, Rectangle bounds, byte compressionMode) {#setPattern-internalized-int---com.aspose.psd.Rectangle-byte-}
```
public final void setPattern_internalized(int[] pixels, Rectangle bounds, byte compressionMode)
```


Définit le tampon de pixels du motif et la taille cible, met à jour la largeur ([.getWidth](../../null/\#getWidth)/[.setWidth(short)](../../null/\#setWidth-short-)) / la hauteur ([.getHeight](../../null/\#getHeight)/[.setHeight(short)](../../null/\#setHeight-short-)), et stocke les données pour l'enregistrement en utilisant le mode de compression spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pixels | int[] | Pixels 32 bits au format 0xAARRGGBB. |
| bounds | [Rectangle](../../com.aspose.psd/rectangle) | Limites de pixels du motif. |
| compressionMode | byte | Le mode de compression utilisé pour définir la compression des données du motif lors de l'enregistrement du fichier psd. |

### setVersion_internalized(int value) {#setVersion-internalized-int-}
```
public final void setVersion_internalized(int value)
```


Obtient la version.

Valeur : la version.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setWidth_internalized(short value) {#setWidth-internalized-short-}
```
public final void setWidth_internalized(short value)
```


Obtient la largeur.

Valeur : la largeur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | short |  |

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

