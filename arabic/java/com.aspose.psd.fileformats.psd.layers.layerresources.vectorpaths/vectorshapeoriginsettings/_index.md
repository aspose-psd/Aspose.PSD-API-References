---
title: "VectorShapeOriginSettings"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "إعدادات أصل الشكل المتجه."
type: docs
weight: 24
url: /ar/java/com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorshapeoriginsettings/
---

**Inheritance:**
java.lang.Object
```
public final class VectorShapeOriginSettings
```

إعدادات أصل الشكل المتجه.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [VectorShapeOriginSettings(boolean isShapeInvalidated, int originIndex)](#VectorShapeOriginSettings-boolean-int-) | يُنشئ مثيلاً جديدًا للفئة [VectorShapeOriginSettings](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorshapeoriginsettings). |
| [VectorShapeOriginSettings()](#VectorShapeOriginSettings--) |  |
## الحقول

| حقل | الوصف |
| --- | --- |
| [KeyOriginIndex_internalized](#KeyOriginIndex-internalized) | مفتاح الوصف لحفظ فهرس أصل الشكل. |
| [KeyOriginRRectRadii_internalized](#KeyOriginRRectRadii-internalized) | مفتاح وصف نصف قطر المستطيل الأصلي |
| [KeyOriginResolution_internalized](#KeyOriginResolution-internalized) | مفتاح وصف دقة الأصل |
| [KeyOriginShapeBBox_internalized](#KeyOriginShapeBBox-internalized) | مفتاح وصف صندوق إطارات الشكل الأصلي |
| [KeyOriginType_internalized](#KeyOriginType-internalized) | مفتاح موصِّف نوع الأصل |
| [KeyShapeInvalidated_internalized](#KeyShapeInvalidated-internalized) | مفتاح الموصف لحفظ قيمة إبطال الشكل. |
| [KnownKeys_internalized](#KnownKeys-internalized) | مفاتيح الخصائص المعروفة |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getId_internalized()](#getId-internalized--) | يحصل على المعرف الفريد. |
| [getOriginBoxCorners()](#getOriginBoxCorners--) | يحصل أو يضبط زوايا صندوق الأصل. |
| [getOriginIndex()](#getOriginIndex--) | يحصل أو يضبط فهرس شكل الأصل. |
| [getOriginRadiiRectangle()](#getOriginRadiiRectangle--) | يحصل أو يضبط مستطيل أقطار الأصل. |
| [getOriginResolution()](#getOriginResolution--) | يحصل أو يضبط دقة الأصل. |
| [getOriginShapeBox()](#getOriginShapeBox--) | يحصل أو يضبط صندوق الإحاطة لشكل الأصل. |
| [getOriginType()](#getOriginType--) | يحصل أو يضبط نوع الأصل. |
| [getTransform()](#getTransform--) | يحصل أو يضبط مصفوفة التحويل. |
| [hasUnknownProperties_internalized()](#hasUnknownProperties-internalized--) | يحصل أو يضبط قيمة تشير إلى ما إذا كان هذا الكائن يحتوي على خصائص غير معروفة. |
| [hashCode()](#hashCode--) |  |
| [isChanged_internalized()](#isChanged-internalized--) | يحصل أو يضبط قيمة تشير إلى ما إذا كان هذا الكائن قد تغير. |
| [isOriginBoxCornersPresent()](#isOriginBoxCornersPresent--) | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن يمتلك خاصية زوايا صندوق الأصل. |
| [isOriginIndexPresent()](#isOriginIndexPresent--) | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن يمتلك خاصية فهرس الأصل. |
| [isOriginRadiiRectanglePresent()](#isOriginRadiiRectanglePresent--) | يحصل على قيمة تشير إلى ما إذا كان مستطيل أقطار الأصل موجودًا. |
| [isOriginResolutionPresent()](#isOriginResolutionPresent--) | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن يمتلك خاصية دقة الأصل. |
| [isOriginShapeBBoxPresent()](#isOriginShapeBBoxPresent--) | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن يمتلك خاصية المستطيل. |
| [isOriginTypePresent()](#isOriginTypePresent--) | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن يمتلك خاصية نوع الأصل. |
| [isPropertyPresent_internalized(String key)](#isPropertyPresent-internalized-java.lang.String-) | يحدد ما إذا كانت الخاصية بالمفتاح المحدد موجودة. |
| [isShapeInvalidated()](#isShapeInvalidated--) | يحصل أو يضبط قيمة تشير إلى ما إذا كان الشكل مُعطَّل. |
| [isShapeInvalidatedPresent()](#isShapeInvalidatedPresent--) | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن يحتوي على خاصية إبطال الشكل مُعينة. |
| [isTransformPresent()](#isTransformPresent--) | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن يمتلك خاصية التحويل. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setChanged_internalized(boolean value)](#setChanged-internalized-boolean-) | يحصل أو يضبط قيمة تشير إلى ما إذا كان هذا الكائن قد تغير. |
| [setOriginBoxCorners(double[] value)](#setOriginBoxCorners-double---) | يحصل أو يضبط زوايا صندوق الأصل. |
| [setOriginIndex(int value)](#setOriginIndex-int-) | يحصل أو يضبط فهرس شكل الأصل. |
| [setOriginRadiiRectangle(VectorShapeRadiiRectangle value)](#setOriginRadiiRectangle-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorShapeRadiiRectangle-) | يحصل أو يضبط مستطيل أقطار الأصل. |
| [setOriginResolution(double value)](#setOriginResolution-double-) | يحصل أو يضبط دقة الأصل. |
| [setOriginShapeBox(VectorShapeBoundingBox value)](#setOriginShapeBox-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorShapeBoundingBox-) | يحصل أو يضبط صندوق الإحاطة لشكل الأصل. |
| [setOriginType(int value)](#setOriginType-int-) | يحصل أو يضبط نوع الأصل. |
| [setShapeInvalidated(boolean value)](#setShapeInvalidated-boolean-) | يحصل أو يضبط قيمة تشير إلى ما إذا كان الشكل مُعطَّل. |
| [setTransform(VectorShapeTransform value)](#setTransform-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorShapeTransform-) | يحصل أو يضبط مصفوفة التحويل. |
| [setUnknownProperties_internalized(boolean value)](#setUnknownProperties-internalized-boolean-) | يحصل أو يضبط قيمة تشير إلى ما إذا كان هذا الكائن يحتوي على خصائص غير معروفة. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### VectorShapeOriginSettings(boolean isShapeInvalidated, int originIndex) {#VectorShapeOriginSettings-boolean-int-}
```
public VectorShapeOriginSettings(boolean isShapeInvalidated, int originIndex)
```


يُنشئ مثيلاً جديدًا للفئة [VectorShapeOriginSettings](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorshapeoriginsettings).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| isShapeInvalidated | boolean | قيمة إبطال الشكل. |
| originIndex | int | فهرس أصل الشكل. |

### VectorShapeOriginSettings() {#VectorShapeOriginSettings--}
```
public VectorShapeOriginSettings()
```


### KeyOriginIndex_internalized {#KeyOriginIndex-internalized}
```
public static final String KeyOriginIndex_internalized
```


مفتاح الوصف لحفظ فهرس أصل الشكل.

### KeyOriginRRectRadii_internalized {#KeyOriginRRectRadii-internalized}
```
public static final String KeyOriginRRectRadii_internalized
```


مفتاح وصف نصف قطر المستطيل الأصلي

### KeyOriginResolution_internalized {#KeyOriginResolution-internalized}
```
public static final String KeyOriginResolution_internalized
```


مفتاح وصف دقة الأصل

### KeyOriginShapeBBox_internalized {#KeyOriginShapeBBox-internalized}
```
public static final String KeyOriginShapeBBox_internalized
```


مفتاح وصف صندوق إطارات الشكل الأصلي

### KeyOriginType_internalized {#KeyOriginType-internalized}
```
public static final String KeyOriginType_internalized
```


مفتاح موصِّف نوع الأصل

### KeyShapeInvalidated_internalized {#KeyShapeInvalidated-internalized}
```
public static final String KeyShapeInvalidated_internalized
```


مفتاح الموصف لحفظ قيمة إبطال الشكل.

### KnownKeys_internalized {#KnownKeys-internalized}
```
public static final String[] KnownKeys_internalized
```


مفاتيح الخصائص المعروفة

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getId_internalized() {#getId-internalized--}
```
public final System.Guid getId_internalized()
```


يحصل على المعرف الفريد.

القيمة: المعرف الفريد.

**Returns:**
com.aspose.ms.System.Guid
### getOriginBoxCorners() {#getOriginBoxCorners--}
```
public final double[] getOriginBoxCorners()
```


يحصل أو يضبط زوايا صندوق الأصل.

القيمة: زوايا صندوق الأصل.

**Returns:**
double[]
### getOriginIndex() {#getOriginIndex--}
```
public final int getOriginIndex()
```


يحصل أو يضبط فهرس شكل الأصل.

**Returns:**
int
### getOriginRadiiRectangle() {#getOriginRadiiRectangle--}
```
public final VectorShapeRadiiRectangle getOriginRadiiRectangle()
```


يحصل أو يضبط مستطيل أقطار الأصل.

القيمة: مستطيل أقطار الأصل.

**Returns:**
[VectorShapeRadiiRectangle](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorshaperadiirectangle)
### getOriginResolution() {#getOriginResolution--}
```
public final double getOriginResolution()
```


يحصل أو يضبط دقة الأصل.

القيمة: دقة الأصل.

**Returns:**
double
### getOriginShapeBox() {#getOriginShapeBox--}
```
public final VectorShapeBoundingBox getOriginShapeBox()
```


يحصل أو يضبط صندوق الإحاطة لشكل الأصل.

القيمة: صندوق شكل الأصل.

**Returns:**
[VectorShapeBoundingBox](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorshapeboundingbox)
### getOriginType() {#getOriginType--}
```
public final int getOriginType()
```


يحصل أو يضبط نوع الأصل.

القيمة: نوع الأصل.

**Returns:**
int
### getTransform() {#getTransform--}
```
public final VectorShapeTransform getTransform()
```


يحصل أو يضبط مصفوفة التحويل.

القيمة: مصفوفة التحويل.

**Returns:**
[VectorShapeTransform](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorshapetransform)
### hasUnknownProperties_internalized() {#hasUnknownProperties-internalized--}
```
public final boolean hasUnknownProperties_internalized()
```


يحصل أو يضبط قيمة تشير إلى ما إذا كان هذا الكائن يحتوي على خصائص غير معروفة.

القيمة:  true  إذا كان لهذا الكائن خصائص غير معروفة؛ وإلا،  false .

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isChanged_internalized() {#isChanged-internalized--}
```
public final boolean isChanged_internalized()
```


يحصل أو يضبط قيمة تشير إلى ما إذا كان هذا الكائن قد تغير.

القيمة:  true  إذا تم تغيير هذا الكائن؛ وإلا،  false .

**Returns:**
boolean
### isOriginBoxCornersPresent() {#isOriginBoxCornersPresent--}
```
public final boolean isOriginBoxCornersPresent()
```


يحصل على قيمة تشير إلى ما إذا كان هذا الكائن يمتلك خاصية زوايا صندوق الأصل.

القيمة:  true  إذا كان لهذا الكائن خاصية زوايا صندوق الأصل؛ وإلا،  false .

**Returns:**
boolean
### isOriginIndexPresent() {#isOriginIndexPresent--}
```
public final boolean isOriginIndexPresent()
```


يحصل على قيمة تشير إلى ما إذا كان هذا الكائن يمتلك خاصية فهرس الأصل.

القيمة:  true  إذا كان لهذا الكائن خاصية فهرس الأصل؛ وإلا،  false .

**Returns:**
boolean
### isOriginRadiiRectanglePresent() {#isOriginRadiiRectanglePresent--}
```
public final boolean isOriginRadiiRectanglePresent()
```


يحصل على قيمة تشير إلى ما إذا كان مستطيل أقطار الأصل موجودًا.

القيمة:  true  إذا كان لهذا الكائن خاصية مستطيل أقطار الأصل؛ وإلا،  false .

**Returns:**
boolean
### isOriginResolutionPresent() {#isOriginResolutionPresent--}
```
public final boolean isOriginResolutionPresent()
```


يحصل على قيمة تشير إلى ما إذا كان هذا الكائن يمتلك خاصية دقة الأصل.

القيمة:  true  إذا كان لهذا الكائن خاصية دقة الأصل؛ وإلا،  false .

**Returns:**
boolean
### isOriginShapeBBoxPresent() {#isOriginShapeBBoxPresent--}
```
public final boolean isOriginShapeBBoxPresent()
```


يحصل على قيمة تشير إلى ما إذا كان هذا الكائن يمتلك خاصية المستطيل.

القيمة:  true  إذا كان لهذا الكائن خاصية مستطيل شكل الأصل؛ وإلا،  false .

**Returns:**
boolean
### isOriginTypePresent() {#isOriginTypePresent--}
```
public final boolean isOriginTypePresent()
```


يحصل على قيمة تشير إلى ما إذا كان هذا الكائن يمتلك خاصية نوع الأصل.

القيمة:  true  إذا كان لهذا الكائن خاصية نوع الأصل؛ وإلا،  false .

**Returns:**
boolean
### isPropertyPresent_internalized(String key) {#isPropertyPresent-internalized-java.lang.String-}
```
public final boolean isPropertyPresent_internalized(String key)
```


يحدد ما إذا كانت الخاصية بالمفتاح المحدد موجودة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| المفتاح | java.lang.String | مفتاح الخاصية. |

**Returns:**
منطقي -  true  إذا كانت الخاصية بالمفتاح المحدد موجودة؛ وإلا،  false .
### isShapeInvalidated() {#isShapeInvalidated--}
```
public final boolean isShapeInvalidated()
```


يحصل أو يضبط قيمة تشير إلى ما إذا كان الشكل مُعطَّل.

**Returns:**
boolean
### isShapeInvalidatedPresent() {#isShapeInvalidatedPresent--}
```
public final boolean isShapeInvalidatedPresent()
```


يحصل على قيمة تشير إلى ما إذا كان هذا الكائن يحتوي على خاصية إبطال الشكل مُعينة.

القيمة:  true  إذا كان لهذا الكائن مجموعة خاصية إبطال الشكل؛ وإلا،  false .

**Returns:**
boolean
### isTransformPresent() {#isTransformPresent--}
```
public final boolean isTransformPresent()
```


يحصل على قيمة تشير إلى ما إذا كان هذا الكائن يمتلك خاصية التحويل.

القيمة:  true  إذا كان لهذا الكائن خاصية التحويل؛ وإلا،  false .

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setChanged_internalized(boolean value) {#setChanged-internalized-boolean-}
```
public final void setChanged_internalized(boolean value)
```


يحصل أو يضبط قيمة تشير إلى ما إذا كان هذا الكائن قد تغير.

القيمة:  true  إذا تم تغيير هذا الكائن؛ وإلا،  false .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setOriginBoxCorners(double[] value) {#setOriginBoxCorners-double---}
```
public final void setOriginBoxCorners(double[] value)
```


يحصل أو يضبط زوايا صندوق الأصل.

القيمة: زوايا صندوق الأصل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double[] |  |

### setOriginIndex(int value) {#setOriginIndex-int-}
```
public final void setOriginIndex(int value)
```


يحصل أو يضبط فهرس شكل الأصل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setOriginRadiiRectangle(VectorShapeRadiiRectangle value) {#setOriginRadiiRectangle-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorShapeRadiiRectangle-}
```
public final void setOriginRadiiRectangle(VectorShapeRadiiRectangle value)
```


يحصل أو يضبط مستطيل أقطار الأصل.

القيمة: مستطيل أقطار الأصل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [VectorShapeRadiiRectangle](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorshaperadiirectangle) |  |

### setOriginResolution(double value) {#setOriginResolution-double-}
```
public final void setOriginResolution(double value)
```


يحصل أو يضبط دقة الأصل.

القيمة: دقة الأصل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double |  |

### setOriginShapeBox(VectorShapeBoundingBox value) {#setOriginShapeBox-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorShapeBoundingBox-}
```
public final void setOriginShapeBox(VectorShapeBoundingBox value)
```


يحصل أو يضبط صندوق الإحاطة لشكل الأصل.

القيمة: صندوق شكل الأصل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [VectorShapeBoundingBox](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorshapeboundingbox) |  |

### setOriginType(int value) {#setOriginType-int-}
```
public final void setOriginType(int value)
```


يحصل أو يضبط نوع الأصل.

القيمة: نوع الأصل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setShapeInvalidated(boolean value) {#setShapeInvalidated-boolean-}
```
public final void setShapeInvalidated(boolean value)
```


يحصل أو يضبط قيمة تشير إلى ما إذا كان الشكل مُعطَّل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setTransform(VectorShapeTransform value) {#setTransform-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorShapeTransform-}
```
public final void setTransform(VectorShapeTransform value)
```


يحصل أو يضبط مصفوفة التحويل.

القيمة: مصفوفة التحويل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [VectorShapeTransform](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorshapetransform) |  |

### setUnknownProperties_internalized(boolean value) {#setUnknownProperties-internalized-boolean-}
```
public final void setUnknownProperties_internalized(boolean value)
```


يحصل أو يضبط قيمة تشير إلى ما إذا كان هذا الكائن يحتوي على خصائص غير معروفة.

القيمة:  true  إذا كان لهذا الكائن خصائص غير معروفة؛ وإلا،  false .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

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

