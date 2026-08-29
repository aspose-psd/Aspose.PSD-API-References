---
title: "IPathShape"
second_title: "Java için Aspose.PSD API Referansı"
description: "Bezier eğrisinin düğümlerinden oluşan Şekil."
type: docs
weight: 31
url: /tr/java/com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/ipathshape/
---
```
public interface IPathShape
```

Bezier eğrisinin düğümlerinden oluşan Şekil.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getItems()](#getItems--) | Bezier düğümlerinin dizisini alır. |
| [getPathOperations()](#getPathOperations--) | Yol şekillerinin birleştirilmesi (Mantıksal işlemler) için işlemler. |
| [isClosed()](#isClosed--) | Şeklin kapalı olup olmadığını belirleyen özelliği alır veya ayarlar. |
| [setClosed(boolean value)](#setClosed-boolean-) | Şeklin kapalı olup olmadığını belirleyen özelliği alır veya ayarlar. |
| [setItems(BezierKnotRecord[] bezierPoints)](#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord---) | Bexier düğümlerinin dizisini atar. |
| [setPathOperations(int value)](#setPathOperations-int-) | Yol şekillerinin birleştirilmesi (Mantıksal işlemler) için işlemler. |
### getItems() {#getItems--}
```
public abstract BezierKnotRecord[] getItems()
```


Bezier düğümlerinin dizisini alır.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord[] - BezierKnotRecord dizisi.
### getPathOperations() {#getPathOperations--}
```
public abstract int getPathOperations()
```


Yol şekillerinin birleştirilmesi (Mantıksal işlemler) için işlemler.

**Returns:**
int
### isClosed() {#isClosed--}
```
public abstract boolean isClosed()
```


Şeklin kapalı olup olmadığını belirleyen özelliği alır veya ayarlar.

**Returns:**
boolean
### setClosed(boolean value) {#setClosed-boolean-}
```
public abstract void setClosed(boolean value)
```


Şeklin kapalı olup olmadığını belirleyen özelliği alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setItems(BezierKnotRecord[] bezierPoints) {#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord---}
```
public abstract void setItems(BezierKnotRecord[] bezierPoints)
```


Bexier düğümlerinin dizisini atar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bezierPoints | [BezierKnotRecord\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/bezierknotrecord) | Bezier düğümlerinin dizisi |

### setPathOperations(int value) {#setPathOperations-int-}
```
public abstract void setPathOperations(int value)
```


Yol şekillerinin birleştirilmesi (Mantıksal işlemler) için işlemler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

