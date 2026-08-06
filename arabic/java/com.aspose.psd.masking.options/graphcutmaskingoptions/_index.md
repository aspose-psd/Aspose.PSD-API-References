---
title: "GraphCutMaskingOptions"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "خيارات القناع التلقائي GraphCut."
type: docs
weight: 14
url: /ar/java/com.aspose.psd.masking.options/graphcutmaskingoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.masking.options.MaskingOptions](../../com.aspose.psd.masking.options/maskingoptions)
```
public class GraphCutMaskingOptions extends MaskingOptions
```

خيارات القناع التلقائي GraphCut.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [GraphCutMaskingOptions()](#GraphCutMaskingOptions--) |  |
## الحقول

| حقل | الوصف |
| --- | --- |
| [BACKGROUND_OBJECT_NUMBER](#BACKGROUND-OBJECT-NUMBER) | رقم كائن الخلفية |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getArgs()](#getArgs--) | يحصل على المعاملات لخوارزمية التجزئة. |
| [getBackgroundReplacementColor()](#getBackgroundReplacementColor--) | يحصل على لون استبدال الخلفية. |
| [getClass()](#getClass--) |  |
| [getDecompose()](#getDecompose--) | يحصل على قيمة تشير إلى ما إذا كان من غير الضروري فصل كل Shape عن القناع ككائن فردي أو ككائن موحد من القناع مفصول عن الخلفية. |
| [getExportOptions()](#getExportOptions--) | يحصل على خيارات تصدير الصورة. |
| [getFeatheringRadius()](#getFeatheringRadius--) | يحصل على نصف قطر التنعيم. |
| [getMaskingArea()](#getMaskingArea--) | يحصل على منطقة القناع. |
| [getMethod()](#getMethod--) | يحصل على طريقة التجزئة. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setArgs(IMaskingArgs value)](#setArgs-com.aspose.psd.masking.options.IMaskingArgs-) | يضبط المعاملات لخوارزمية التجزئة. |
| [setBackgroundReplacementColor(Color value)](#setBackgroundReplacementColor-com.aspose.psd.Color-) | يضبط لون استبدال الخلفية. |
| [setDecompose(boolean value)](#setDecompose-boolean-) | يضبط قيمة تشير إلى ما إذا كان من غير الضروري فصل كل Shape عن القناع ككائن فردي أو ككائن موحد من القناع مفصول عن الخلفية. |
| [setExportOptions(ImageOptionsBase value)](#setExportOptions-com.aspose.psd.ImageOptionsBase-) | يضبط خيارات تصدير الصورة. |
| [setFeatheringRadius(int value)](#setFeatheringRadius-int-) | يضبط نصف قطر التنعيم. |
| [setMaskingArea(Rectangle value)](#setMaskingArea-com.aspose.psd.Rectangle-) | يضبط منطقة القناع. |
| [setMethod(int value)](#setMethod-int-) | يضبط طريقة التجزئة. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GraphCutMaskingOptions() {#GraphCutMaskingOptions--}
```
public GraphCutMaskingOptions()
```


### BACKGROUND_OBJECT_NUMBER {#BACKGROUND-OBJECT-NUMBER}
```
public static final int BACKGROUND_OBJECT_NUMBER
```


رقم كائن الخلفية

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
### getArgs() {#getArgs--}
```
public final IMaskingArgs getArgs()
```


يحصل على المعاملات لخوارزمية التجزئة.

القيمة: المعاملات لخوارزمية التجزئة.

**Returns:**
[IMaskingArgs](../../com.aspose.psd.masking.options/imaskingargs) - the arguments for segmentation algorithm.
### getBackgroundReplacementColor() {#getBackgroundReplacementColor--}
```
public final Color getBackgroundReplacementColor()
```


يحصل على لون استبدال الخلفية.

القيمة: لون استبدال الخلفية. سيُستخدم هذا اللون كلون خلفية في الصور الناتجة.

**Returns:**
[Color](../../com.aspose.psd/color) - the background replacement color.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDecompose() {#getDecompose--}
```
public final boolean getDecompose()
```


يحصل على قيمة تشير إلى ما إذا كان من غير الضروري فصل كل Shape عن القناع ككائن فردي أو ككائن موحد من القناع مفصول عن الخلفية.

القيمة:  true  إذا تم التفكيك؛ وإلا،  false .

**Returns:**
boolean - قيمة تشير إلى ما إذا كان من غير الضروري فصل كل Shape عن القناع ككائن فردي أو ككائن موحد من القناع مفصول عن الخلفية.
### getExportOptions() {#getExportOptions--}
```
public final ImageOptionsBase getExportOptions()
```


يحصل على خيارات تصدير الصورة.

القيمة: خيارات تصدير الصورة التي ستُستخدم لإنشاء الصور الناتجة.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - the image export options.
### getFeatheringRadius() {#getFeatheringRadius--}
```
public final int getFeatheringRadius()
```


يحصل على نصف قطر التنعيم.

**Returns:**
int - نصف قطر التريش.
### getMaskingArea() {#getMaskingArea--}
```
public final Rectangle getMaskingArea()
```


يحصل على منطقة القناع.

القيمة: منطقة القناع التي هي جزء من صورة المصدر. قيمة Rectangle.Empty تعني مساحة صورة المصدر بالكامل.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - the masking area.
### getMethod() {#getMethod--}
```
public final int getMethod()
```


يحصل على طريقة التجزئة.

القيمة: طريقة التجزئة.

**Returns:**
int - طريقة التجزئة.
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




### setArgs(IMaskingArgs value) {#setArgs-com.aspose.psd.masking.options.IMaskingArgs-}
```
public final void setArgs(IMaskingArgs value)
```


يضبط المعاملات لخوارزمية التجزئة.

القيمة: المعاملات لخوارزمية التجزئة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [IMaskingArgs](../../com.aspose.psd.masking.options/imaskingargs) | المعاملات لخوارزمية التجزئة. |

### setBackgroundReplacementColor(Color value) {#setBackgroundReplacementColor-com.aspose.psd.Color-}
```
public final void setBackgroundReplacementColor(Color value)
```


يضبط لون استبدال الخلفية.

القيمة: لون استبدال الخلفية. سيُستخدم هذا اللون كلون خلفية في الصور الناتجة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | لون استبدال الخلفية. |

### setDecompose(boolean value) {#setDecompose-boolean-}
```
public final void setDecompose(boolean value)
```


يضبط قيمة تشير إلى ما إذا كان من غير الضروري فصل كل Shape عن القناع ككائن فردي أو ككائن موحد من القناع مفصول عن الخلفية.

القيمة:  true  إذا تم التفكيك؛ وإلا،  false .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | قيمة تشير إلى ما إذا كان من غير الضروري فصل كل Shape من القناع ككائن فردي أو ككائن موحد من القناع مفصول عن الخلفية. |

### setExportOptions(ImageOptionsBase value) {#setExportOptions-com.aspose.psd.ImageOptionsBase-}
```
public final void setExportOptions(ImageOptionsBase value)
```


يضبط خيارات تصدير الصورة.

القيمة: خيارات تصدير الصورة التي ستُستخدم لإنشاء الصور الناتجة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | خيارات تصدير الصورة. |

### setFeatheringRadius(int value) {#setFeatheringRadius-int-}
```
public final void setFeatheringRadius(int value)
```


يضبط نصف قطر التنعيم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | نصف قطر التريش. |

### setMaskingArea(Rectangle value) {#setMaskingArea-com.aspose.psd.Rectangle-}
```
public final void setMaskingArea(Rectangle value)
```


يضبط منطقة القناع.

القيمة: منطقة القناع التي هي جزء من صورة المصدر. قيمة Rectangle.Empty تعني مساحة صورة المصدر بالكامل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) | منطقة القناع. |

### setMethod(int value) {#setMethod-int-}
```
public final void setMethod(int value)
```


يضبط طريقة التجزئة.

القيمة: طريقة التجزئة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | طريقة التجزئة. |

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

