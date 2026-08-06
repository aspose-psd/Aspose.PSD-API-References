---
title: "LayerMaskData"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Définit la classe de base LayerMaskData qui contient des informations sur les données du masque de calque dans le fichier PSD."
type: docs
weight: 21
url: /fr/java/com.aspose.psd.fileformats.psd.layers/layermaskdata/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Cloneable
```
public abstract class LayerMaskData implements Cloneable
```

Définit la classe de base LayerMaskData qui contient des informations sur les données du masque de calque dans le fichier PSD. Elle peut aider à modifier les fichiers Adobe\ufffd Photoshop\ufffd de manière programmatique et à automatiser l'édition du format PSD. Si le calque possède uniquement un masque raster, l'ImageData contient les octets des données du masque raster. Si le calque possède uniquement un masque vectoriel, l'ImageData contient les octets des données du masque vectoriel rasterisé (mis en cache). Si le calque possède à la fois des masques raster et vectoriels, l'ImageData contient le masque raster et le masque vectoriel rasterisé combinés. La longueur en octets de l'ImageData ([getImageData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata\#getImageData)/[setImageData(byte[])](../../com.aspose.psd.fileformats.psd.layers/layermaskdata\#setImageData-byte---)) doit être égale à Width \* Height du MaskRectangle ([getMaskRectangle](../../com.aspose.psd.fileformats.psd.layers/layermaskdata\#getMaskRectangle)/[setMaskRectangle(Rectangle)](../../com.aspose.psd.fileformats.psd.layers/layermaskdata\#setMaskRectangle-Rectangle-)) propriétés. Notez que simplement supprimer / ajouter / mettre à jour le LayerMaskData n'est pas suffisant pour un enregistrement correct car les canaux ne sont pas mis à jour ; bien que cela puisse fournir un rendu correct. La méthode [Layer.addLayerMask(LayerMaskData)](../../com.aspose.psd.fileformats.psd.layers/layer\#addLayerMask-LayerMaskData-) doit être utilisée pour cela.
## Méthodes

| Méthode | Description |
| --- | --- |
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
| [setRight(int value)](#setRight-int-) | Obtient ou définit la position droite du masque de calque. |
| [setTop(int value)](#setTop-int-) | Obtient ou définit la position supérieure du masque de calque. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
public abstract void save_internalized(StreamContainer streamContainer)
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

