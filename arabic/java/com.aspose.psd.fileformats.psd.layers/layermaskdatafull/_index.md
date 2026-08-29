---
title: "LayerMaskDataFull"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "يحدد فئة LayerMaskDataFull التي تحتوي على معلومات حول بيانات القناع في طبقة ملف PSD عندما تكون الطبقة لديها كل من أقنعة الطبقة والقناع المتجه."
type: docs
weight: 22
url: /ar/java/com.aspose.psd.fileformats.psd.layers/layermaskdatafull/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata)
```
public final class LayerMaskDataFull extends LayerMaskData
```

يعرّف فئة LayerMaskDataFull التي تحتوي على معلومات حول بيانات القناع في طبقة ملف PSD عندما تحتوي الطبقة على كل من الأقنعة الطبقية والمتجهية. وإلا، يتم استخدام [LayerMaskDataShort](../../com.aspose.psd.fileformats.psd.layers/layermaskdatashort). يحتوي ImageData على القناع النقطي والقناع المتجهي المرسوم نقطيًا معًا. يجب أن يكون طول بايتات ImageData مساويًا لخصائص MaskRectangle.Width \* MaskRectangle.Height.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [LayerMaskDataFull()](#LayerMaskDataFull--) | يُنشئ مثيلًا جديدًا من الفئة [LayerMaskDataFull](../../com.aspose.psd.fileformats.psd.layers/layermaskdatafull). |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [deepClone_internalized()](#deepClone-internalized--) | ينسخ هذه النسخة. |
| [deepClone_internalized(LayerMaskData mask)](#deepClone-internalized-com.aspose.psd.fileformats.psd.layers.LayerMaskData-) | ينسخ قناع الطبقة. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackgroundColor()](#getBackgroundColor--) | يحصل أو يعيّن لون الخلفية. |
| [getBottom()](#getBottom--) | يحصل أو يعيّن موضع قناع الطبقة السفلي. |
| [getClass()](#getClass--) |  |
| [getDataSize()](#getDataSize--) | يحصل على حجم بيانات قناع الطبقة. |
| [getDefaultColor()](#getDefaultColor--) | يحصل أو يعيّن اللون الافتراضي. |
| [getEnclosingBottom()](#getEnclosingBottom--) | يحصل أو يعيّن موضع القناع النقطي السفلي المحيط في طبقة صورة PSD. |
| [getEnclosingLeft()](#getEnclosingLeft--) | يحصل أو يعيّن موضع القناع النقطي الأيسر المحيط في طبقة ملف PSD. |
| [getEnclosingRight()](#getEnclosingRight--) | يحصل أو يعيّن موضع القناع النقطي الأيمن المحيط في طبقة ملف PSD. |
| [getEnclosingTop()](#getEnclosingTop--) | يحصل أو يعيّن موضع القناع النقطي العلوي المحيط في طبقة صورة PSD. |
| [getFlags()](#getFlags--) | يحصل أو يعيّن أعلام قناع الطبقة. |
| [getHeight_internalized()](#getHeight-internalized--) | يحصل على ارتفاع القناع. |
| [getImageData()](#getImageData--) | يحصل أو يضبط بيانات قناع الطبقة (أو القناع المدمج / النهائي إذا كان هناك قناع متجه) في ملف PSD. |
| [getLeft()](#getLeft--) | يحصل أو يضبط موضع قناع الطبقة الأيسر. |
| [getMaskRectangle()](#getMaskRectangle--) | يحصل أو يضبط  Rectangle  القناع للطبقة في ملف PSD. |
| [getRealFlags()](#getRealFlags--) | يحصل أو يعيّن أعلام قناع الطبقة المستخدمة لقناع المستخدم / النقطي. |
| [getRight()](#getRight--) | يحصل أو يضبط موضع قناع الطبقة الأيمن. |
| [getTop()](#getTop--) | يحصل أو يضبط موضع قناع الطبقة العلوي. |
| [getUserMaskData()](#getUserMaskData--) | يحصل أو يعيّن بيانات قناع المستخدم (النقطي) لطبقة في ملف PSD. |
| [getUserMaskRectangle()](#getUserMaskRectangle--) | يحصل أو يعيّن مستطيل القناع المستخدم (المحاط) في طبقة صورة PSD. |
| [getWidth_internalized()](#getWidth-internalized--) | يحصل على عرض القناع. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save_internalized(StreamContainer streamContainer)](#save-internalized-com.aspose.psd.StreamContainer-) | يحفظ [LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) إلى StreamContainer المحدد. |
| [setBackgroundColor(byte value)](#setBackgroundColor-byte-) | يحصل أو يعيّن لون الخلفية. |
| [setBottom(int value)](#setBottom-int-) | يحصل أو يعيّن موضع قناع الطبقة السفلي. |
| [setDefaultColor(byte value)](#setDefaultColor-byte-) | يحصل أو يعيّن اللون الافتراضي. |
| [setEnclosingBottom(int value)](#setEnclosingBottom-int-) | يحصل أو يعيّن موضع القناع النقطي السفلي المحيط في طبقة صورة PSD. |
| [setEnclosingLeft(int value)](#setEnclosingLeft-int-) | يحصل أو يعيّن موضع القناع النقطي الأيسر المحيط في طبقة ملف PSD. |
| [setEnclosingRight(int value)](#setEnclosingRight-int-) | يحصل أو يعيّن موضع القناع النقطي الأيمن المحيط في طبقة ملف PSD. |
| [setEnclosingTop(int value)](#setEnclosingTop-int-) | يحصل أو يعيّن موضع القناع النقطي العلوي المحيط في طبقة صورة PSD. |
| [setFlags(byte value)](#setFlags-byte-) | يحصل أو يعيّن أعلام قناع الطبقة. |
| [setImageData(byte[] value)](#setImageData-byte---) | يحصل أو يضبط بيانات قناع الطبقة (أو القناع المدمج / النهائي إذا كان هناك قناع متجه) في ملف PSD. |
| [setLeft(int value)](#setLeft-int-) | يحصل أو يضبط موضع قناع الطبقة الأيسر. |
| [setMaskRectangle(Rectangle value)](#setMaskRectangle-com.aspose.psd.Rectangle-) | يحصل أو يضبط  Rectangle  القناع للطبقة في ملف PSD. |
| [setRealFlags(byte value)](#setRealFlags-byte-) | يحصل أو يعيّن أعلام قناع الطبقة المستخدمة لقناع المستخدم / النقطي. |
| [setRight(int value)](#setRight-int-) | يحصل أو يضبط موضع قناع الطبقة الأيمن. |
| [setTop(int value)](#setTop-int-) | يحصل أو يضبط موضع قناع الطبقة العلوي. |
| [setUserMaskData(byte[] value)](#setUserMaskData-byte---) | يحصل أو يعيّن بيانات قناع المستخدم (النقطي) لطبقة في ملف PSD. |
| [setUserMaskRectangle(Rectangle value)](#setUserMaskRectangle-com.aspose.psd.Rectangle-) | يحصل أو يعيّن مستطيل القناع المستخدم (المحاط) في طبقة صورة PSD. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LayerMaskDataFull() {#LayerMaskDataFull--}
```
public LayerMaskDataFull()
```


يُنشئ مثيلًا جديدًا من الفئة [LayerMaskDataFull](../../com.aspose.psd.fileformats.psd.layers/layermaskdatafull).

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
### getBackgroundColor() {#getBackgroundColor--}
```
public final byte getBackgroundColor()
```


يحصل أو يعيّن لون الخلفية.

القيمة: لون الخلفية.

**Returns:**
byte
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
### getEnclosingBottom() {#getEnclosingBottom--}
```
public final int getEnclosingBottom()
```


يحصل أو يعيّن موضع القناع النقطي السفلي المحيط في طبقة صورة PSD.

القيمة: موضع قناع الطبقة السفلي.

**Returns:**
int
### getEnclosingLeft() {#getEnclosingLeft--}
```
public final int getEnclosingLeft()
```


يحصل أو يعيّن موضع القناع النقطي الأيسر المحيط في طبقة ملف PSD.

القيمة: موضع قناع الطبقة الأيسر.

**Returns:**
int
### getEnclosingRight() {#getEnclosingRight--}
```
public final int getEnclosingRight()
```


يحصل أو يعيّن موضع القناع النقطي الأيمن المحيط في طبقة ملف PSD.

القيمة: موضع قناع الطبقة الأيمن.

**Returns:**
int
### getEnclosingTop() {#getEnclosingTop--}
```
public final int getEnclosingTop()
```


يحصل أو يعيّن موضع القناع النقطي العلوي المحيط في طبقة صورة PSD.

القيمة: موضع قناع الطبقة العلوي.

**Returns:**
int
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
### getRealFlags() {#getRealFlags--}
```
public final byte getRealFlags()
```


يحصل أو يعيّن أعلام قناع الطبقة المستخدمة لقناع المستخدم / النقطي. للقناع المتجهي تُستخدم خاصية Flags.

القيمة: أعلام قناع الطبقة الفعلية.

**Returns:**
byte
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
### getUserMaskData() {#getUserMaskData--}
```
public final byte[] getUserMaskData()
```


يحصل أو يعيّن بيانات قناع المستخدم (النقطي) لطبقة في ملف PSD. (هناك قناع متجهي مرسوم نقطيًا في خاصية MaskData).

القيمة: بيانات صورة الطبقة في صورة PSD.

**Returns:**
byte[]
### getUserMaskRectangle() {#getUserMaskRectangle--}
```
public final Rectangle getUserMaskRectangle()
```


يحصل أو يعيّن مستطيل القناع المستخدم (المحاط) في طبقة صورة PSD.

القيمة: مستطيل قناع المستخدم.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
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
public void save_internalized(StreamContainer streamContainer)
```


يحفظ [LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) إلى StreamContainer المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | حاوية الدفق لحفظ البيانات إليها. |

### setBackgroundColor(byte value) {#setBackgroundColor-byte-}
```
public final void setBackgroundColor(byte value)
```


يحصل أو يعيّن لون الخلفية.

القيمة: لون الخلفية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte |  |

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

### setEnclosingBottom(int value) {#setEnclosingBottom-int-}
```
public final void setEnclosingBottom(int value)
```


يحصل أو يعيّن موضع القناع النقطي السفلي المحيط في طبقة صورة PSD.

القيمة: موضع قناع الطبقة السفلي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setEnclosingLeft(int value) {#setEnclosingLeft-int-}
```
public final void setEnclosingLeft(int value)
```


يحصل أو يعيّن موضع القناع النقطي الأيسر المحيط في طبقة ملف PSD.

القيمة: موضع قناع الطبقة الأيسر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setEnclosingRight(int value) {#setEnclosingRight-int-}
```
public final void setEnclosingRight(int value)
```


يحصل أو يعيّن موضع القناع النقطي الأيمن المحيط في طبقة ملف PSD.

القيمة: موضع قناع الطبقة الأيمن.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setEnclosingTop(int value) {#setEnclosingTop-int-}
```
public final void setEnclosingTop(int value)
```


يحصل أو يعيّن موضع القناع النقطي العلوي المحيط في طبقة صورة PSD.

القيمة: موضع قناع الطبقة العلوي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

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

### setRealFlags(byte value) {#setRealFlags-byte-}
```
public final void setRealFlags(byte value)
```


يحصل أو يعيّن أعلام قناع الطبقة المستخدمة لقناع المستخدم / النقطي. للقناع المتجهي تُستخدم خاصية Flags.

القيمة: أعلام قناع الطبقة الفعلية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte |  |

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

### setUserMaskData(byte[] value) {#setUserMaskData-byte---}
```
public final void setUserMaskData(byte[] value)
```


يحصل أو يعيّن بيانات قناع المستخدم (النقطي) لطبقة في ملف PSD. (هناك قناع متجهي مرسوم نقطيًا في خاصية MaskData).

القيمة: بيانات صورة الطبقة في صورة PSD.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte[] |  |

### setUserMaskRectangle(Rectangle value) {#setUserMaskRectangle-com.aspose.psd.Rectangle-}
```
public final void setUserMaskRectangle(Rectangle value)
```


يحصل أو يعيّن مستطيل القناع المستخدم (المحاط) في طبقة صورة PSD.

القيمة: مستطيل قناع المستخدم.

**Parameters:**
| معامل | نوع | الوصف |
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

