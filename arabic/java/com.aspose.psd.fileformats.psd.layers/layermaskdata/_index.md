---
title: "LayerMaskData"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "يحدد فئة LayerMaskData الأساسية التي تحتوي على معلومات حول بيانات قناع الطبقة في ملف PSD."
type: docs
weight: 21
url: /ar/java/com.aspose.psd.fileformats.psd.layers/layermaskdata/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Cloneable
```
public abstract class LayerMaskData implements Cloneable
```

يعرّف الفئة الأساسية LayerMaskData التي تحتوي على معلومات حول بيانات قناع الطبقة في ملف PSD. يمكن أن يساعد في تعديل ملفات Adobe\\ufffd Photoshop\\ufffd برمجياً وأتمتة تحرير تنسيق PSD. إذا كان للطبقة قناع نقطي فقط فإن ImageData يحتوي على بايتات بيانات القناع النقطي. إذا كان للطبقة قناع متجه فقط فإن ImageData يحتوي على بايتات بيانات القناع المتجه المرسوم (المخزن مؤقتاً). إذا كان للطبقة كل من القناع النقطي والمتجه فإن ImageData يحتوي على القناع النقطي والقناع المتجه المرسوم معاً. يجب أن يكون طول بايتات ImageData ([getImageData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata\\#getImageData)/[setImageData(byte[])](../../com.aspose.psd.fileformats.psd.layers/layermaskdata\\#setImageData-byte---)) مساويًا للعرض \\* الارتفاع لـ MaskRectangle ([getMaskRectangle](../../com.aspose.psd.fileformats.psd.layers/layermaskdata\\#getMaskRectangle)/[setMaskRectangle(Rectangle)](../../com.aspose.psd.fileformats.psd.layers/layermaskdata\\#setMaskRectangle-Rectangle-)) الخاصيات. لاحظ أن مجرد إزالة / إضافة / تحديث LayerMaskData ليس كافياً للحفظ الصحيح لأن القنوات لا تُحدّث؛ رغم أنه قد يوفر عرضًا صحيحًا. يجب استخدام طريقة [Layer.addLayerMask(LayerMaskData)](../../com.aspose.psd.fileformats.psd.layers/layer\\#addLayerMask-LayerMaskData-) لهذا.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [deepClone_internalized()](#deepClone-internalized--) | ينسخ هذه النسخة. |
| [deepClone_internalized(LayerMaskData mask)](#deepClone-internalized-com.aspose.psd.fileformats.psd.layers.LayerMaskData-) | ينسخ قناع الطبقة. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBottom()](#getBottom--) | يحصل أو يعيّن موضع قناع الطبقة السفلي. |
| [getClass()](#getClass--) |  |
| [getDataSize()](#getDataSize--) | يحصل على حجم بيانات قناع الطبقة. |
| [getDefaultColor()](#getDefaultColor--) | يحصل أو يعيّن اللون الافتراضي. |
| [getFlags()](#getFlags--) | يحصل أو يعيّن أعلام قناع الطبقة. |
| [getHeight_internalized()](#getHeight-internalized--) | يحصل على ارتفاع القناع. |
| [getImageData()](#getImageData--) | يحصل أو يضبط بيانات قناع الطبقة (أو القناع المدمج / النهائي إذا كان هناك قناع متجه) في ملف PSD. |
| [getLeft()](#getLeft--) | يحصل أو يضبط موضع قناع الطبقة الأيسر. |
| [getMaskRectangle()](#getMaskRectangle--) | يحصل أو يضبط  Rectangle  القناع للطبقة في ملف PSD. |
| [getRight()](#getRight--) | يحصل أو يضبط موضع قناع الطبقة الأيمن. |
| [getTop()](#getTop--) | يحصل أو يضبط موضع قناع الطبقة العلوي. |
| [getWidth_internalized()](#getWidth-internalized--) | يحصل على عرض القناع. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save_internalized(StreamContainer streamContainer)](#save-internalized-com.aspose.psd.StreamContainer-) | يحفظ [LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) إلى StreamContainer المحدد. |
| [setBottom(int value)](#setBottom-int-) | يحصل أو يعيّن موضع قناع الطبقة السفلي. |
| [setDefaultColor(byte value)](#setDefaultColor-byte-) | يحصل أو يعيّن اللون الافتراضي. |
| [setFlags(byte value)](#setFlags-byte-) | يحصل أو يعيّن أعلام قناع الطبقة. |
| [setImageData(byte[] value)](#setImageData-byte---) | يحصل أو يضبط بيانات قناع الطبقة (أو القناع المدمج / النهائي إذا كان هناك قناع متجه) في ملف PSD. |
| [setLeft(int value)](#setLeft-int-) | يحصل أو يضبط موضع قناع الطبقة الأيسر. |
| [setMaskRectangle(Rectangle value)](#setMaskRectangle-com.aspose.psd.Rectangle-) | يحصل أو يضبط  Rectangle  القناع للطبقة في ملف PSD. |
| [setRight(int value)](#setRight-int-) | يحصل أو يضبط موضع قناع الطبقة الأيمن. |
| [setTop(int value)](#setTop-int-) | يحصل أو يضبط موضع قناع الطبقة العلوي. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### deepClone_internalized() {#deepClone-internalized--}
```
public LayerMaskData deepClone_internalized()
```


ينسخ هذه النسخة.

**Returns:**
[LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) - The cloned layer mask.
### deepClone_internalized(LayerMaskData mask) {#deepClone-internalized-com.aspose.psd.fileformats.psd.layers.LayerMaskData-}
```
public static LayerMaskData deepClone_internalized(LayerMaskData mask)
```


ينسخ قناع الطبقة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| mask | [LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) | القناع. |

**Returns:**
[LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) - The cloned layer mask.
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
### getBottom() {#getBottom--}
```
public final int getBottom()
```


يحصل أو يعيّن موضع قناع الطبقة السفلي.

القيمة: موضع قناع الطبقة السفلي.

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


يحصل على حجم بيانات قناع الطبقة.

القيمة: حجم بيانات قناع الطبقة.

**Returns:**
int
### getDefaultColor() {#getDefaultColor--}
```
public final byte getDefaultColor()
```


يحصل أو يعيّن اللون الافتراضي.

القيمة: اللون الافتراضي.

**Returns:**
byte
### getFlags() {#getFlags--}
```
public final byte getFlags()
```


يحصل أو يعيّن أعلام قناع الطبقة.

القيمة: علامات قناع الطبقة.

**Returns:**
byte
### getHeight_internalized() {#getHeight-internalized--}
```
public final int getHeight_internalized()
```


يحصل على ارتفاع القناع.

القيمة: الارتفاع.

**Returns:**
int
### getImageData() {#getImageData--}
```
public final byte[] getImageData()
```


يحصل أو يضبط بيانات قناع الطبقة (أو القناع المدمج / النهائي إذا كان هناك قناع متجه) في ملف PSD.

القيمة: بيانات الصورة.

**Returns:**
byte[]
### getLeft() {#getLeft--}
```
public final int getLeft()
```


يحصل أو يضبط موضع قناع الطبقة الأيسر.

القيمة: موضع قناع الطبقة الأيسر.

**Returns:**
int
### getMaskRectangle() {#getMaskRectangle--}
```
public final Rectangle getMaskRectangle()
```


يحصل أو يضبط  Rectangle  القناع للطبقة في ملف PSD. يأخذ الخصائص اليسار، اليمين، الأعلى والأسفل وينشئ  Rectangle.

القيمة: مستطيل القناع.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getRight() {#getRight--}
```
public final int getRight()
```


يحصل أو يضبط موضع قناع الطبقة الأيمن.

القيمة: موضع قناع الطبقة الأيمن.

**Returns:**
int
### getTop() {#getTop--}
```
public final int getTop()
```


يحصل أو يضبط موضع قناع الطبقة العلوي.

القيمة: موضع قناع الطبقة العلوي.

**Returns:**
int
### getWidth_internalized() {#getWidth-internalized--}
```
public final int getWidth_internalized()
```


يحصل على عرض القناع.

القيمة: العرض.

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


يحفظ [LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) إلى StreamContainer المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | حاوية الدفق لحفظ البيانات إليها. |

### setBottom(int value) {#setBottom-int-}
```
public final void setBottom(int value)
```


يحصل أو يعيّن موضع قناع الطبقة السفلي.

القيمة: موضع قناع الطبقة السفلي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setDefaultColor(byte value) {#setDefaultColor-byte-}
```
public final void setDefaultColor(byte value)
```


يحصل أو يعيّن اللون الافتراضي.

القيمة: اللون الافتراضي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte |  |

### setFlags(byte value) {#setFlags-byte-}
```
public final void setFlags(byte value)
```


يحصل أو يعيّن أعلام قناع الطبقة.

القيمة: علامات قناع الطبقة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte |  |

### setImageData(byte[] value) {#setImageData-byte---}
```
public final void setImageData(byte[] value)
```


يحصل أو يضبط بيانات قناع الطبقة (أو القناع المدمج / النهائي إذا كان هناك قناع متجه) في ملف PSD.

القيمة: بيانات الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte[] |  |

### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


يحصل أو يضبط موضع قناع الطبقة الأيسر.

القيمة: موضع قناع الطبقة الأيسر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setMaskRectangle(Rectangle value) {#setMaskRectangle-com.aspose.psd.Rectangle-}
```
public final void setMaskRectangle(Rectangle value)
```


يحصل أو يضبط  Rectangle  القناع للطبقة في ملف PSD. يأخذ الخصائص اليسار، اليمين، الأعلى والأسفل وينشئ  Rectangle.

القيمة: مستطيل القناع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setRight(int value) {#setRight-int-}
```
public final void setRight(int value)
```


يحصل أو يضبط موضع قناع الطبقة الأيمن.

القيمة: موضع قناع الطبقة الأيمن.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


يحصل أو يضبط موضع قناع الطبقة العلوي.

القيمة: موضع قناع الطبقة العلوي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

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

