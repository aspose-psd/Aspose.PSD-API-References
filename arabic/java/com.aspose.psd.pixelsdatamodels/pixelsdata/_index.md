---
title: "PixelsData"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "الفئة لتخزين بيانات بكسلات الصورة وحدودها."
type: docs
weight: 10
url: /ar/java/com.aspose.psd.pixelsdatamodels/pixelsdata/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable
```
public final class PixelsData implements System.ICloneable
```

الفئة لتخزين بيانات بكسلات الصورة وحدودها.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [PixelsData()](#PixelsData--) | يُنشئ نسخة جديدة من الفئة [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata). |
| [PixelsData(int[] pixels, Rectangle bounds)](#PixelsData-int---com.aspose.psd.Rectangle-) | يُنشئ نسخة جديدة من الفئة [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata). |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [createLoader_internalized()](#createLoader-internalized--) | ينشئ مثيل PixelsDataLoader للنسخة الحالية من [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata). |
| [createSaver_internalized()](#createSaver-internalized--) | ينشئ مثيل PixelsDataSaver للنسخة الحالية من [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata). |
| [deepClone()](#deepClone--) | إنه ينشئ نسخة كاملة من المثيل. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBounds()](#getBounds--) | يحصل أو يعيّن حدود بيانات البكسلات. |
| [getClass()](#getClass--) |  |
| [getPixels()](#getPixels--) | يحصل أو يعيّن بيانات البكسلات. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBounds(Rectangle value)](#setBounds-com.aspose.psd.Rectangle-) | يحصل أو يعيّن حدود بيانات البكسلات. |
| [setPixels(int[] value)](#setPixels-int---) | يحصل أو يعيّن بيانات البكسلات. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PixelsData() {#PixelsData--}
```
public PixelsData()
```


يُنشئ نسخة جديدة من الفئة [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata).

### PixelsData(int[] pixels, Rectangle bounds) {#PixelsData-int---com.aspose.psd.Rectangle-}
```
public PixelsData(int[] pixels, Rectangle bounds)
```


يُنشئ نسخة جديدة من الفئة [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| بكسلات | int[] | بيانات البكسلات. |
| bounds | [Rectangle](../../com.aspose.psd/rectangle) | مستطيل حدود البكسلات. |

### createLoader_internalized() {#createLoader-internalized--}
```
public final IRasterImageArgb32PixelLoader createLoader_internalized()
```


ينشئ مثيل PixelsDataLoader للنسخة الحالية من [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata).

**Returns:**
[IRasterImageArgb32PixelLoader](../../com.aspose.psd/irasterimageargb32pixelloader) - The new instance of PixelsDataLoader base on current instance of [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata).
### createSaver_internalized() {#createSaver-internalized--}
```
public final IPixelsSaver createSaver_internalized()
```


ينشئ مثيل PixelsDataSaver للنسخة الحالية من [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata).

**Returns:**
com.aspose.internal.IPixelsSaver - المثيل الجديد من PixelsDataSaver يعتمد على النسخة الحالية من [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata).
### deepClone() {#deepClone--}
```
public final Object deepClone()
```


إنه ينشئ نسخة كاملة من المثيل.

**Returns:**
java.lang.Object - نسخة من المثيل.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBounds() {#getBounds--}
```
public final Rectangle getBounds()
```


يحصل أو يعيّن حدود بيانات البكسلات.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getPixels() {#getPixels--}
```
public final int[] getPixels()
```


يحصل أو يعيّن بيانات البكسلات.

**Returns:**
int[]
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




### setBounds(Rectangle value) {#setBounds-com.aspose.psd.Rectangle-}
```
public final void setBounds(Rectangle value)
```


يحصل أو يعيّن حدود بيانات البكسلات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setPixels(int[] value) {#setPixels-int---}
```
public final void setPixels(int[] value)
```


يحصل أو يعيّن بيانات البكسلات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int[] |  |

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
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

