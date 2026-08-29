---
title: "LayerMaskDataShort"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Définit la classe LayerMaskDataShort qui contient des informations sur les données de masque dans le calque du fichier PSD lorsque le calque possède uniquement un masque raster ou vectoriel, mais pas les deux."
type: docs
weight: 23
url: /fr/java/com.aspose.psd.fileformats.psd.layers/layermaskdatashort/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata)
```
public final class LayerMaskDataShort extends LayerMaskData
```

Définit la classe LayerMaskDataShort qui contient des informations sur les données de masque dans le calque du fichier PSD lorsque le calque possède uniquement un masque raster ou vectoriel, mais pas les deux. Sinon, un [LayerMaskDataFull](../../com.aspose.psd.fileformats.psd.layers/layermaskdatafull) est utilisé. Si le calque possède uniquement un masque raster, ImageData contient les octets des données du masque raster. Si le calque possède uniquement un masque vectoriel, ImageData contient les octets des données du masque vectoriel rasterisé (mis en cache). La longueur des octets de LayerMaskData.ImageData ([LayerMaskData.getImageData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata\#getImageData)/[LayerMaskData.setImageData(byte[])](../../com.aspose.psd.fileformats.psd.layers/layermaskdata\#setImageData-byte---)) doit être égale à Width \* Height de LayerMaskData.MaskRectangle ([LayerMaskData.getMaskRectangle](../../com.aspose.psd.fileformats.psd.layers/layermaskdata\#getMaskRectangle)/[LayerMaskData.setMaskRectangle(Rectangle)](../../com.aspose.psd.fileformats.psd.layers/layermaskdata\#setMaskRectangle-Rectangle-)) propriétés.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [LayerMaskDataShort()](#LayerMaskDataShort--) | Initialise une nouvelle instance de la classe [LayerMaskDataShort](../../com.aspose.psd.fileformats.psd.layers/layermaskdatashort). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [create_internalized(PixelsData pixelsData)](#create-internalized-com.aspose.psd.pixelsdatamodels.PixelsData-) |  |
| [deepClone_internalized()](#deepClone-internalized--) | Clone cette instance. |
| [deepClone_internalized(LayerMaskData mask)](#deepClone-internalized-com.aspose.psd.fileformats.psd.layers.LayerMaskData-) | Clone le masque de calque. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBottom()](#getBottom--) | Obtient ou définit la position du masque de calque inférieur. |
| [getClass()](#getClass--) |  |
| [getDataSize()](#getDataSize--) | Obtient la taille des données du masque de calque. |
| [getDefaultColor()](#getDefaultColor--) | Obtient ou définit la couleur par défaut. |
| [getFlags()](#getFlags--) | Obtient ou définit les indicateurs du masque de calque. |
| [getHeight_internalized()](#getHeight-internalized--) | Obtient la hauteur du masque. |
| [getImageData()](#getImageData--) | Obtient ou définit les données du masque de calque (ou le masque combiné / final s'il existe un masque vectoriel) dans le fichier PSD. |
| [getLeft()](#getLeft--) | Obtient ou définit la position gauche du masque de calque. |
| [getMaskRectangle()](#getMaskRectangle--) | Obtient ou définit le  Rectangle  du masque de calque dans le fichier PSD. |
| [getPadding()](#getPadding--) | Obtient ou définit le remplissage du masque de calque. |
| [getRight()](#getRight--) | Obtient ou définit la position droite du masque de calque. |
| [getTop()](#getTop--) | Obtient ou définit la position supérieure du masque de calque. |
| [getWidth_internalized()](#getWidth-internalized--) | Obtient la largeur du masque. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save_internalized(StreamContainer streamContainer)](#save-internalized-com.aspose.psd.StreamContainer-) | Enregistre [LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) dans le StreamContainer spécifié. |
| [setBottom(int value)](#setBottom-int-) | Obtient ou définit la position du masque de calque inférieur. |
| [setDefaultColor(byte value)](#setDefaultColor-byte-) | Obtient ou définit la couleur par défaut. |
| [setFlags(byte value)](#setFlags-byte-) | Obtient ou définit les indicateurs du masque de calque. |
| [setImageData(byte[] value)](#setImageData-byte---) | Obtient ou définit les données du masque de calque (ou le masque combiné / final s'il existe un masque vectoriel) dans le fichier PSD. |
| [setLeft(int value)](#setLeft-int-) | Obtient ou définit la position gauche du masque de calque. |
| [setMaskRectangle(Rectangle value)](#setMaskRectangle-com.aspose.psd.Rectangle-) | Obtient ou définit le  Rectangle  du masque de calque dans le fichier PSD. |
| [setPadding(short value)](#setPadding-short-) | Obtient ou définit le remplissage du masque de calque. |
| [setRight(int value)](#setRight-int-) | Obtient ou définit la position droite du masque de calque. |
| [setTop(int value)](#setTop-int-) | Obtient ou définit la position supérieure du masque de calque. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LayerMaskDataShort() {#LayerMaskDataShort--}
```
public LayerMaskDataShort()
```


Initialise une nouvelle instance de la classe [LayerMaskDataShort](../../com.aspose.psd.fileformats.psd.layers/layermaskdatashort).

### create_internalized(PixelsData pixelsData) {#create-internalized-com.aspose.psd.pixelsdatamodels.PixelsData-}
```
public static LayerMaskDataShort create_internalized(PixelsData pixelsData)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pixelsData | [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata) |  |

**Returns:**
[LayerMaskDataShort](../../com.aspose.psd.fileformats.psd.layers/layermaskdatashort)
### deepClone_internalized() {#deepClone-internalized--}
```
public LayerMaskData deepClone_internalized()
```


Clone cette instance.

**Returns:**
[LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) - The cloned layer mask.
### deepClone_internalized(LayerMaskData mask) {#deepClone-internalized-com.aspose.psd.fileformats.psd.layers.LayerMaskData-}
```
public static LayerMaskData deepClone_internalized(LayerMaskData mask)
```


Clone le masque de calque.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| mask | [LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) | Le masque. |

**Returns:**
[LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) - The cloned layer mask.
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
### getBottom() {#getBottom--}
```
public final int getBottom()
```


Obtient ou définit la position du masque de calque inférieur.

Valeur : la position inférieure du masque de calque.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDataSize() {#getDataSize--}
```
public final int getDataSize()
```


Obtient la taille des données du masque de calque.

Valeur : la taille des données du masque de calque.

**Returns:**
int
### getDefaultColor() {#getDefaultColor--}
```
public final byte getDefaultColor()
```


Obtient ou définit la couleur par défaut.

Valeur : la couleur par défaut.

**Returns:**
byte
### getFlags() {#getFlags--}
```
public final byte getFlags()
```


Obtient ou définit les indicateurs du masque de calque.

Valeur : les indicateurs du masque de calque.

**Returns:**
byte
### getHeight_internalized() {#getHeight-internalized--}
```
public final int getHeight_internalized()
```


Obtient la hauteur du masque.

Valeur : la hauteur.

**Returns:**
int
### getImageData() {#getImageData--}
```
public final byte[] getImageData()
```


Obtient ou définit les données du masque de calque (ou le masque combiné / final s'il existe un masque vectoriel) dans le fichier PSD.

Valeur : les données de l'image.

**Returns:**
byte[]
### getLeft() {#getLeft--}
```
public final int getLeft()
```


Obtient ou définit la position gauche du masque de calque.

Valeur : la position gauche du masque de calque.

**Returns:**
int
### getMaskRectangle() {#getMaskRectangle--}
```
public final Rectangle getMaskRectangle()
```


Obtient ou définit le  Rectangle  du masque de calque dans le fichier PSD. Il prend les propriétés gauche, droite, supérieure et inférieure et crée un  Rectangle.

Valeur : le rectangle du masque.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getPadding() {#getPadding--}
```
public final short getPadding()
```


Obtient ou définit le remplissage du masque de calque.

Valeur : le remplissage du masque de calque.

**Returns:**
short
### getRight() {#getRight--}
```
public final int getRight()
```


Obtient ou définit la position droite du masque de calque.

Valeur : la position droite du masque de calque.

**Returns:**
int
### getTop() {#getTop--}
```
public final int getTop()
```


Obtient ou définit la position supérieure du masque de calque.

Valeur : la position supérieure du masque de calque.

**Returns:**
int
### getWidth_internalized() {#getWidth-internalized--}
```
public final int getWidth_internalized()
```


Obtient la largeur du masque.

Valeur : la largeur.

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




### save_internalized(StreamContainer streamContainer) {#save-internalized-com.aspose.psd.StreamContainer-}
```
public void save_internalized(StreamContainer streamContainer)
```


Enregistre [LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) dans le StreamContainer spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Le conteneur de flux où enregistrer les données. |

### setBottom(int value) {#setBottom-int-}
```
public final void setBottom(int value)
```


Obtient ou définit la position du masque de calque inférieur.

Valeur : la position inférieure du masque de calque.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setDefaultColor(byte value) {#setDefaultColor-byte-}
```
public final void setDefaultColor(byte value)
```


Obtient ou définit la couleur par défaut.

Valeur : la couleur par défaut.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte |  |

### setFlags(byte value) {#setFlags-byte-}
```
public final void setFlags(byte value)
```


Obtient ou définit les indicateurs du masque de calque.

Valeur : les indicateurs du masque de calque.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte |  |

### setImageData(byte[] value) {#setImageData-byte---}
```
public final void setImageData(byte[] value)
```


Obtient ou définit les données du masque de calque (ou le masque combiné / final s'il existe un masque vectoriel) dans le fichier PSD.

Valeur : les données de l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte[] |  |

### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


Obtient ou définit la position gauche du masque de calque.

Valeur : la position gauche du masque de calque.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setMaskRectangle(Rectangle value) {#setMaskRectangle-com.aspose.psd.Rectangle-}
```
public final void setMaskRectangle(Rectangle value)
```


Obtient ou définit le  Rectangle  du masque de calque dans le fichier PSD. Il prend les propriétés gauche, droite, supérieure et inférieure et crée un  Rectangle.

Valeur : le rectangle du masque.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setPadding(short value) {#setPadding-short-}
```
public final void setPadding(short value)
```


Obtient ou définit le remplissage du masque de calque.

Valeur : le remplissage du masque de calque.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | short |  |

### setRight(int value) {#setRight-int-}
```
public final void setRight(int value)
```


Obtient ou définit la position droite du masque de calque.

Valeur : la position droite du masque de calque.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


Obtient ou définit la position supérieure du masque de calque.

Valeur : la position supérieure du masque de calque.

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

