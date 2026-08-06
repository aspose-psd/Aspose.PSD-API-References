---
title: "IPathShape"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "الشكل من عقد منحنى بيزييه."
type: docs
weight: 31
url: /ar/java/com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/ipathshape/
---
```
public interface IPathShape
```

الشكل من عقد منحنى بيزييه.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getItems()](#getItems--) | يحصل على مصفوفة من عقد بيزيير. |
| [getPathOperations()](#getPathOperations--) | العمليات لتجميع أشكال المسار (عمليات بوليانية). |
| [isClosed()](#isClosed--) | يحصل أو يعيّن الخاصية التي تحدد ما إذا كان الشكل مغلقًا. |
| [setClosed(boolean value)](#setClosed-boolean-) | يحصل أو يعيّن الخاصية التي تحدد ما إذا كان الشكل مغلقًا. |
| [setItems(BezierKnotRecord[] bezierPoints)](#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord---) | تعيين مصفوفة من عقد Bexier. |
| [setPathOperations(int value)](#setPathOperations-int-) | العمليات لتجميع أشكال المسار (عمليات بوليانية). |
### getItems() {#getItems--}
```
public abstract BezierKnotRecord[] getItems()
```


يحصل على مصفوفة من عقد بيزيير.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord[] - مصفوفة من BezierKnotRecord.
### getPathOperations() {#getPathOperations--}
```
public abstract int getPathOperations()
```


العمليات لتجميع أشكال المسار (عمليات بوليانية).

**Returns:**
int
### isClosed() {#isClosed--}
```
public abstract boolean isClosed()
```


يحصل أو يعيّن الخاصية التي تحدد ما إذا كان الشكل مغلقًا.

**Returns:**
boolean
### setClosed(boolean value) {#setClosed-boolean-}
```
public abstract void setClosed(boolean value)
```


يحصل أو يعيّن الخاصية التي تحدد ما إذا كان الشكل مغلقًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setItems(BezierKnotRecord[] bezierPoints) {#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord---}
```
public abstract void setItems(BezierKnotRecord[] bezierPoints)
```


تعيين مصفوفة من عقد Bexier.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| bezierPoints | [BezierKnotRecord\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/bezierknotrecord) | مصفوفة من عقد بيزيير |

### setPathOperations(int value) {#setPathOperations-int-}
```
public abstract void setPathOperations(int value)
```


العمليات لتجميع أشكال المسار (عمليات بوليانية).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

