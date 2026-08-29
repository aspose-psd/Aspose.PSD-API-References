---
title: "IPathShape"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Shape dari simpul-simpul kurva Bezier."
type: docs
weight: 31
url: /id/java/com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/ipathshape/
---
```
public interface IPathShape
```

Shape dari simpul-simpul kurva Bezier.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getItems()](#getItems--) | Mendapatkan array simpul Bezier. |
| [getPathOperations()](#getPathOperations--) | Operasi untuk menggabungkan bentuk jalur (operasi Boolean). |
| [isClosed()](#isClosed--) | Mendapatkan atau mengatur properti yang menentukan apakah Shape ditutup. |
| [setClosed(boolean value)](#setClosed-boolean-) | Mendapatkan atau mengatur properti yang menentukan apakah Shape ditutup. |
| [setItems(BezierKnotRecord[] bezierPoints)](#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord---) | Menetapkan array simpul Bexier. |
| [setPathOperations(int value)](#setPathOperations-int-) | Operasi untuk menggabungkan bentuk jalur (operasi Boolean). |
### getItems() {#getItems--}
```
public abstract BezierKnotRecord[] getItems()
```


Mendapatkan array simpul Bezier.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord[] - Array dari BezierKnotRecord.
### getPathOperations() {#getPathOperations--}
```
public abstract int getPathOperations()
```


Operasi untuk menggabungkan bentuk jalur (operasi Boolean).

**Returns:**
int
### isClosed() {#isClosed--}
```
public abstract boolean isClosed()
```


Mendapatkan atau mengatur properti yang menentukan apakah Shape ditutup.

**Returns:**
boolean
### setClosed(boolean value) {#setClosed-boolean-}
```
public abstract void setClosed(boolean value)
```


Mendapatkan atau mengatur properti yang menentukan apakah Shape ditutup.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setItems(BezierKnotRecord[] bezierPoints) {#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord---}
```
public abstract void setItems(BezierKnotRecord[] bezierPoints)
```


Menetapkan array simpul Bexier.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bezierPoints | [BezierKnotRecord\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/bezierknotrecord) | Array dari simpul bezier |

### setPathOperations(int value) {#setPathOperations-int-}
```
public abstract void setPathOperations(int value)
```


Operasi untuk menggabungkan bentuk jalur (operasi Boolean).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

