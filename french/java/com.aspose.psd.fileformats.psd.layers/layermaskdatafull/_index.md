---
title: "LayerMaskDataFull"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Définit la classe LayerMaskDataFull qui contient des informations sur les données de masque dans le calque du fichier PSD lorsque le calque possède à la fois des masques de calque et des masques vectoriels."
type: docs
weight: 22
url: /fr/java/com.aspose.psd.fileformats.psd.layers/layermaskdatafull/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata)
```
public final class LayerMaskDataFull extends LayerMaskData
```

Définit la classe LayerMaskDataFull qui contient des informations sur les données de masque dans le calque du fichier PSD lorsque le calque possède à la fois des masques de calque et des masques vectoriels. Sinon, un [LayerMaskDataShort](../../com.aspose.psd.fileformats.psd.layers/layermaskdatashort) est utilisé. ImageData contient le masque raster et le masque vectoriel rasterisé combinés. La longueur des octets d'ImageData doit être égale aux propriétés MaskRectangle.Width \* MaskRectangle.Height.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [LayerMaskDataFull()](#LayerMaskDataFull--) | Initialise une nouvelle instance de la classe [LayerMaskDataFull](../../com.aspose.psd.fileformats.psd.layers/layermaskdatafull). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [deepClone_internalized()](#deepClone-internalized--) | Clone cette instance. |
| [deepClone_internalized(LayerMaskData mask)](#deepClone-internalized-com.aspose.psd.fileformats.psd.layers.LayerMaskData-) | Clone le masque de calque. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackgroundColor()](#getBackgroundColor--) | Obtient ou définit la couleur d'arrière-plan. |
| [getBottom()](#getBottom--) | Obtient ou définit la position du masque de calque inférieur. |
| [getClass()](#getClass--) |  |
| [getDataSize()](#getDataSize--) | Obtient la taille des données du masque de calque. |
| [getDefaultColor()](#getDefaultColor--) | Obtient ou définit la couleur par défaut. |
| [getEnclosingBottom()](#getEnclosingBottom--) | Obtient ou définit la position inférieure du masque raster englobant dans le calque d'image PSD. |
| [getEnclosingLeft()](#getEnclosingLeft--) | Obtient ou définit la position gauche du masque raster englobant dans le calque du fichier PSD. |
| [getEnclosingRight()](#getEnclosingRight--) | Obtient ou définit la position droite du masque raster englobant dans le calque du fichier PSD. |
| [getEnclosingTop()](#getEnclosingTop--) | Obtient ou définit la position supérieure du masque raster englobant dans le calque d'image PSD. |
| [getFlags()](#getFlags--) | Obtient ou définit les indicateurs du masque de calque. |
| [getHeight_internalized()](#getHeight-internalized--) | Obtient la hauteur du masque. |
| [getImageData()](#getImageData--) | Obtient ou définit les données du masque de calque (ou le masque combiné / final s'il existe un masque vectoriel) dans le fichier PSD. |
| [getLeft()](#getLeft--) | Obtient ou définit la position gauche du masque de calque. |
| [getMaskRectangle()](#getMaskRectangle--) | Obtient ou définit le  Rectangle  du masque de calque dans le fichier PSD. |
| [getRealFlags()](#getRealFlags--) | Obtient ou définit les indicateurs du masque de calque utilisés pour le masque utilisateur / raster. |
| [getRight()](#getRight--) | Obtient ou définit la position droite du masque de calque. |
| [getTop()](#getTop--) | Obtient ou définit la position supérieure du masque de calque. |
| [getUserMaskData()](#getUserMaskData--) | Obtient ou définit les données du masque utilisateur (raster) d'un calque dans le fichier PSD. |
| [getUserMaskRectangle()](#getUserMaskRectangle--) | Obtient ou définit le rectangle du masque utilisateur (englobant) dans le calque d'image PSD. |
| [getWidth_internalized()](#getWidth-internalized--) | Obtient la largeur du masque. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save_internalized(StreamContainer streamContainer)](#save-internalized-com.aspose.psd.StreamContainer-) | Enregistre [LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) dans le StreamContainer spécifié. |
| [setBackgroundColor(byte value)](#setBackgroundColor-byte-) | Obtient ou définit la couleur d'arrière-plan. |
| [setBottom(int value)](#setBottom-int-) | Obtient ou définit la position du masque de calque inférieur. |
| [setDefaultColor(byte value)](#setDefaultColor-byte-) | Obtient ou définit la couleur par défaut. |
| [setEnclosingBottom(int value)](#setEnclosingBottom-int-) | Obtient ou définit la position inférieure du masque raster englobant dans le calque d'image PSD. |
| [setEnclosingLeft(int value)](#setEnclosingLeft-int-) | Obtient ou définit la position gauche du masque raster englobant dans le calque du fichier PSD. |
| [setEnclosingRight(int value)](#setEnclosingRight-int-) | Obtient ou définit la position droite du masque raster englobant dans le calque du fichier PSD. |
| [setEnclosingTop(int value)](#setEnclosingTop-int-) | Obtient ou définit la position supérieure du masque raster englobant dans le calque d'image PSD. |
| [setFlags(byte value)](#setFlags-byte-) | Obtient ou définit les indicateurs du masque de calque. |
| [setImageData(byte[] value)](#setImageData-byte---) | Obtient ou définit les données du masque de calque (ou le masque combiné / final s'il existe un masque vectoriel) dans le fichier PSD. |
| [setLeft(int value)](#setLeft-int-) | Obtient ou définit la position gauche du masque de calque. |
| [setMaskRectangle(Rectangle value)](#setMaskRectangle-com.aspose.psd.Rectangle-) | Obtient ou définit le  Rectangle  du masque de calque dans le fichier PSD. |
| [setRealFlags(byte value)](#setRealFlags-byte-) | Obtient ou définit les indicateurs du masque de calque utilisés pour le masque utilisateur / raster. |
| [setRight(int value)](#setRight-int-) | Obtient ou définit la position droite du masque de calque. |
| [setTop(int value)](#setTop-int-) | Obtient ou définit la position supérieure du masque de calque. |
| [setUserMaskData(byte[] value)](#setUserMaskData-byte---) | Obtient ou définit les données du masque utilisateur (raster) d'un calque dans le fichier PSD. |
| [setUserMaskRectangle(Rectangle value)](#setUserMaskRectangle-com.aspose.psd.Rectangle-) | Obtient ou définit le rectangle du masque utilisateur (englobant) dans le calque d'image PSD. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LayerMaskDataFull() {#LayerMaskDataFull--}
```
public LayerMaskDataFull()
```


Initialise une nouvelle instance de la classe [LayerMaskDataFull](../../com.aspose.psd.fileformats.psd.layers/layermaskdatafull).

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
### getBackgroundColor() {#getBackgroundColor--}
```
public final byte getBackgroundColor()
```


Obtient ou définit la couleur d'arrière-plan.

Valeur : la couleur d'arrière-plan.

**Returns:**
byte
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
### getEnclosingBottom() {#getEnclosingBottom--}
```
public final int getEnclosingBottom()
```


Obtient ou définit la position inférieure du masque raster englobant dans le calque d'image PSD.

Valeur : la position inférieure du masque de calque.

**Returns:**
int
### getEnclosingLeft() {#getEnclosingLeft--}
```
public final int getEnclosingLeft()
```


Obtient ou définit la position gauche du masque raster englobant dans le calque du fichier PSD.

Valeur : la position gauche du masque de calque.

**Returns:**
int
### getEnclosingRight() {#getEnclosingRight--}
```
public final int getEnclosingRight()
```


Obtient ou définit la position droite du masque raster englobant dans le calque du fichier PSD.

Valeur : la position droite du masque de calque.

**Returns:**
int
### getEnclosingTop() {#getEnclosingTop--}
```
public final int getEnclosingTop()
```


Obtient ou définit la position supérieure du masque raster englobant dans le calque d'image PSD.

Valeur : la position supérieure du masque de calque.

**Returns:**
int
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
### getRealFlags() {#getRealFlags--}
```
public final byte getRealFlags()
```


Obtient ou définit les indicateurs du masque de calque utilisés pour le masque utilisateur / raster. Pour le masque vectoriel, la propriété Flags est utilisée.

Valeur : les indicateurs réels du masque de calque.

**Returns:**
byte
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
### getUserMaskData() {#getUserMaskData--}
```
public final byte[] getUserMaskData()
```


Obtient ou définit les données du masque utilisateur (raster) d'un calque dans le fichier PSD. (Il y a un masque vectoriel rasterisé dans la propriété MaskData).

Valeur : les données d'image du calque dans l'image PSD.

**Returns:**
byte[]
### getUserMaskRectangle() {#getUserMaskRectangle--}
```
public final Rectangle getUserMaskRectangle()
```


Obtient ou définit le rectangle du masque utilisateur (englobant) dans le calque d'image PSD.

Valeur : le rectangle du masque utilisateur.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
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

### setBackgroundColor(byte value) {#setBackgroundColor-byte-}
```
public final void setBackgroundColor(byte value)
```


Obtient ou définit la couleur d'arrière-plan.

Valeur : la couleur d'arrière-plan.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte |  |

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

### setEnclosingBottom(int value) {#setEnclosingBottom-int-}
```
public final void setEnclosingBottom(int value)
```


Obtient ou définit la position inférieure du masque raster englobant dans le calque d'image PSD.

Valeur : la position inférieure du masque de calque.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setEnclosingLeft(int value) {#setEnclosingLeft-int-}
```
public final void setEnclosingLeft(int value)
```


Obtient ou définit la position gauche du masque raster englobant dans le calque du fichier PSD.

Valeur : la position gauche du masque de calque.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setEnclosingRight(int value) {#setEnclosingRight-int-}
```
public final void setEnclosingRight(int value)
```


Obtient ou définit la position droite du masque raster englobant dans le calque du fichier PSD.

Valeur : la position droite du masque de calque.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setEnclosingTop(int value) {#setEnclosingTop-int-}
```
public final void setEnclosingTop(int value)
```


Obtient ou définit la position supérieure du masque raster englobant dans le calque d'image PSD.

Valeur : la position supérieure du masque de calque.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

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

### setRealFlags(byte value) {#setRealFlags-byte-}
```
public final void setRealFlags(byte value)
```


Obtient ou définit les indicateurs du masque de calque utilisés pour le masque utilisateur / raster. Pour le masque vectoriel, la propriété Flags est utilisée.

Valeur : les indicateurs réels du masque de calque.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte |  |

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

### setUserMaskData(byte[] value) {#setUserMaskData-byte---}
```
public final void setUserMaskData(byte[] value)
```


Obtient ou définit les données du masque utilisateur (raster) d'un calque dans le fichier PSD. (Il y a un masque vectoriel rasterisé dans la propriété MaskData).

Valeur : les données d'image du calque dans l'image PSD.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte[] |  |

### setUserMaskRectangle(Rectangle value) {#setUserMaskRectangle-com.aspose.psd.Rectangle-}
```
public final void setUserMaskRectangle(Rectangle value)
```


Obtient ou définit le rectangle du masque utilisateur (englobant) dans le calque d'image PSD.

Valeur : le rectangle du masque utilisateur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

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

