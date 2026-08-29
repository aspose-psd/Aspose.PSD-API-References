---
title: "AutoMaskingGraphCutOptions"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "خيارات القناع التلقائي GraphCut."
type: docs
weight: 12
url: /ar/java/com.aspose.psd.masking.options/automaskinggraphcutoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.masking.options.MaskingOptions](../../com.aspose.psd.masking.options/maskingoptions), [com.aspose.psd.masking.options.GraphCutMaskingOptions](../../com.aspose.psd.masking.options/graphcutmaskingoptions)
```
public class AutoMaskingGraphCutOptions extends GraphCutMaskingOptions
```

خيارات القناع التلقائي GraphCut.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [AutoMaskingGraphCutOptions()](#AutoMaskingGraphCutOptions--) | ينشئ مثيلاً جديدًا من الفئة [AutoMaskingGraphCutOptions](../../com.aspose.psd.masking.options/automaskinggraphcutoptions). |
## الحقول

| حقل | الوصف |
| --- | --- |
| [BACKGROUND_OBJECT_NUMBER](#BACKGROUND-OBJECT-NUMBER) | رقم كائن الخلفية |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [appendAutoMaskingArgs_internalized(RasterImage image)](#appendAutoMaskingArgs-internalized-com.aspose.psd.RasterImage-) | إضافة وسائط القناع التلقائي. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fillInnDefaultStrokes_internalized(RasterImage image)](#fillInnDefaultStrokes-internalized-com.aspose.psd.RasterImage-) | ملء الخطوط الافتراضية. |
| [getArgs()](#getArgs--) | يحصل على المعاملات لخوارزمية التجزئة. |
| [getAssumedObjects()](#getAssumedObjects--) | يحصل على الكائنات المفترضة. |
| [getAssumedObjects_internalized()](#getAssumedObjects-internalized--) |  |
| [getBackgroundReplacementColor()](#getBackgroundReplacementColor--) | يحصل على لون استبدال الخلفية. |
| [getCalculateDefaultStrokes()](#getCalculateDefaultStrokes--) | يحصل على قيمة تشير إلى ما إذا كان يجب حساب الخطوط الافتراضية. |
| [getClass()](#getClass--) |  |
| [getCombinedObjectsRectangle_internalized()](#getCombinedObjectsRectangle-internalized--) | يحصل على مستطيل الكائنات المدمجة. |
| [getDecompose()](#getDecompose--) | يحصل على قيمة تشير إلى ما إذا كان من غير الضروري فصل كل Shape عن القناع ككائن فردي أو ككائن موحد من القناع مفصول عن الخلفية. |
| [getDefaultBackgroundStrokes()](#getDefaultBackgroundStrokes--) | يحصل على الخطوط الخلفية الافتراضية. |
| [getDefaultForegroundStrokes()](#getDefaultForegroundStrokes--) | يحصل على الخطوط الأمامية الافتراضية المحسوبة مسبقًا. |
| [getDefaultObjectsRectangles()](#getDefaultObjectsRectangles--) | يحصل على مستطيلات الكائنات الافتراضية. |
| [getExportOptions()](#getExportOptions--) | يحصل على خيارات تصدير الصورة. |
| [getFeatheringRadius()](#getFeatheringRadius--) | يحصل على نصف قطر التنعيم. |
| [getMaskingArea()](#getMaskingArea--) | يحصل على منطقة القناع. |
| [getMethod()](#getMethod--) | يحصل على طريقة التجزئة. |
| [getPrecalculationProgressEventHandler()](#getPrecalculationProgressEventHandler--) | يحصل على معالج حدث تقدم عملية حساب النقاط الافتراضية مسبقًا. |
| [hasHumans_internalized()](#hasHumans-internalized--) | يحصل على قيمة تشير إلى ما إذا كانت مجموعة الكائنات المفترضة تحتوي على كائنات بشرية. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setArgs(IMaskingArgs value)](#setArgs-com.aspose.psd.masking.options.IMaskingArgs-) | يضبط المعاملات لخوارزمية التجزئة. |
| [setAssumedObjects(List<AssumedObjectData> value)](#setAssumedObjects-java.util.List-com.aspose.psd.masking.options.AssumedObjectData--) | يضبط الكائنات المفترضة. |
| [setAssumedObjects_internalized(System.Collections.Generic.List<AssumedObjectData> value)](#setAssumedObjects-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.masking.options.AssumedObjectData--) |  |
| [setBackgroundReplacementColor(Color value)](#setBackgroundReplacementColor-com.aspose.psd.Color-) | يضبط لون استبدال الخلفية. |
| [setCalculateDefaultStrokes(boolean value)](#setCalculateDefaultStrokes-boolean-) | يضبط قيمة تشير إلى ما إذا كان يجب حساب الخطوط الافتراضية. |
| [setCombinedObjectsRectangle_internalized(Rectangle value)](#setCombinedObjectsRectangle-internalized-com.aspose.psd.Rectangle-) | مستطيل الكائنات المدمجة. |
| [setDecompose(boolean value)](#setDecompose-boolean-) | يضبط قيمة تشير إلى ما إذا كان من غير الضروري فصل كل Shape عن القناع ككائن فردي أو ككائن موحد من القناع مفصول عن الخلفية. |
| [setDefaultBackgroundStrokes_internalized(Point[] value)](#setDefaultBackgroundStrokes-internalized-com.aspose.psd.Point---) | الخطوط الخلفية الافتراضية. |
| [setDefaultForegroundStrokes_internalized(Point[] value)](#setDefaultForegroundStrokes-internalized-com.aspose.psd.Point---) | الخطوط الأمامية الافتراضية المحسوبة مسبقًا. |
| [setDefaultObjectsRectangles_internalized(Rectangle[] value)](#setDefaultObjectsRectangles-internalized-com.aspose.psd.Rectangle---) | مستطيلات الكائنات الافتراضية. |
| [setExportOptions(ImageOptionsBase value)](#setExportOptions-com.aspose.psd.ImageOptionsBase-) | يضبط خيارات تصدير الصورة. |
| [setFeatheringRadius(int value)](#setFeatheringRadius-int-) | يضبط نصف قطر التنعيم. |
| [setHumans_internalized(boolean value)](#setHumans-internalized-boolean-) | قيمة تشير إلى ما إذا كانت مجموعة الكائنات المفترضة تحتوي على كائنات بشرية. |
| [setMaskingArea(Rectangle value)](#setMaskingArea-com.aspose.psd.Rectangle-) | يضبط منطقة القناع. |
| [setMethod(int value)](#setMethod-int-) | يضبط طريقة التجزئة. |
| [setPrecalculationProgressEventHandler(ProgressEventHandler value)](#setPrecalculationProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | يضبط معالج حدث تقدم عملية حساب النقاط الافتراضية مسبقًا. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AutoMaskingGraphCutOptions() {#AutoMaskingGraphCutOptions--}
```
public AutoMaskingGraphCutOptions()
```


ينشئ مثيلاً جديدًا من الفئة [AutoMaskingGraphCutOptions](../../com.aspose.psd.masking.options/automaskinggraphcutoptions).

### BACKGROUND_OBJECT_NUMBER {#BACKGROUND-OBJECT-NUMBER}
```
public static final int BACKGROUND_OBJECT_NUMBER
```


رقم كائن الخلفية

### appendAutoMaskingArgs_internalized(RasterImage image) {#appendAutoMaskingArgs-internalized-com.aspose.psd.RasterImage-}
```
public final void appendAutoMaskingArgs_internalized(RasterImage image)
```


إضافة وسائط القناع التلقائي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | الصورة. |

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
### fillInnDefaultStrokes_internalized(RasterImage image) {#fillInnDefaultStrokes-internalized-com.aspose.psd.RasterImage-}
```
public final void fillInnDefaultStrokes_internalized(RasterImage image)
```


ملء الخطوط الافتراضية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | الصورة. |

### getArgs() {#getArgs--}
```
public final IMaskingArgs getArgs()
```


يحصل على المعاملات لخوارزمية التجزئة.

القيمة: المعاملات لخوارزمية التجزئة.

**Returns:**
[IMaskingArgs](../../com.aspose.psd.masking.options/imaskingargs) - the arguments for segmentation algorithm.
### getAssumedObjects() {#getAssumedObjects--}
```
public final List<AssumedObjectData> getAssumedObjects()
```


يحصل على الكائنات المفترضة.

**Returns:**
java.util.List<com.aspose.psd.masking.options.AssumedObjectData> - الكائنات المفترضة.
### getAssumedObjects_internalized() {#getAssumedObjects-internalized--}
```
public final System.Collections.Generic.List<AssumedObjectData> getAssumedObjects_internalized()
```




**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.masking.options.AssumedObjectData>
### getBackgroundReplacementColor() {#getBackgroundReplacementColor--}
```
public final Color getBackgroundReplacementColor()
```


يحصل على لون استبدال الخلفية.

القيمة: لون استبدال الخلفية. سيُستخدم هذا اللون كلون خلفية في الصور الناتجة.

**Returns:**
[Color](../../com.aspose.psd/color) - the background replacement color.
### getCalculateDefaultStrokes() {#getCalculateDefaultStrokes--}
```
public final boolean getCalculateDefaultStrokes()
```


يحصل على قيمة تشير إلى ما إذا كان يجب حساب الخطوط الافتراضية.

**Returns:**
boolean - قيمة تشير إلى ما إذا كان يجب حساب الضربات الافتراضية.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCombinedObjectsRectangle_internalized() {#getCombinedObjectsRectangle-internalized--}
```
public final Rectangle getCombinedObjectsRectangle_internalized()
```


يحصل على مستطيل الكائنات المدمجة.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - the combined objects rectangle.
### getDecompose() {#getDecompose--}
```
public final boolean getDecompose()
```


يحصل على قيمة تشير إلى ما إذا كان من غير الضروري فصل كل Shape عن القناع ككائن فردي أو ككائن موحد من القناع مفصول عن الخلفية.

القيمة:  true  إذا تم التفكيك؛ وإلا،  false .

**Returns:**
boolean - قيمة تشير إلى ما إذا كان من غير الضروري فصل كل Shape عن القناع ككائن فردي أو ككائن موحد من القناع مفصول عن الخلفية.
### getDefaultBackgroundStrokes() {#getDefaultBackgroundStrokes--}
```
public final Point[] getDefaultBackgroundStrokes()
```


يحصل على الخطوط الخلفية الافتراضية.

**Returns:**
com.aspose.psd.Point[] - الضربات الخلفية الافتراضية.
### getDefaultForegroundStrokes() {#getDefaultForegroundStrokes--}
```
public final Point[] getDefaultForegroundStrokes()
```


يحصل على الخطوط الأمامية الافتراضية المحسوبة مسبقًا.

**Returns:**
com.aspose.psd.Point[] - الضربات الأمامية الافتراضية المحسوبة مسبقًا.
### getDefaultObjectsRectangles() {#getDefaultObjectsRectangles--}
```
public final Rectangle[] getDefaultObjectsRectangles()
```


يحصل على مستطيلات الكائنات الافتراضية.

**Returns:**
com.aspose.psd.Rectangle[] - مستطيلات الكائنات الافتراضية.
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
### getPrecalculationProgressEventHandler() {#getPrecalculationProgressEventHandler--}
```
public final ProgressEventHandler getPrecalculationProgressEventHandler()
```


يحصل على معالج حدث تقدم عملية حساب النقاط الافتراضية مسبقًا.

القيمة: معالج حدث التقدم.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the default points pre-calculation process progress event handler.
### hasHumans_internalized() {#hasHumans-internalized--}
```
public final boolean hasHumans_internalized()
```


يحصل على قيمة تشير إلى ما إذا كانت مجموعة الكائنات المفترضة تحتوي على كائنات بشرية.

**Returns:**
boolean - قيمة تشير إلى ما إذا كانت مجموعة الكائنات المفترضة تحتوي على كائنات بشرية.
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

### setAssumedObjects(List<AssumedObjectData> value) {#setAssumedObjects-java.util.List-com.aspose.psd.masking.options.AssumedObjectData--}
```
public final void setAssumedObjects(List<AssumedObjectData> value)
```


يضبط الكائنات المفترضة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.util.List<com.aspose.psd.masking.options.AssumedObjectData> | الكائنات المفترضة. |

### setAssumedObjects_internalized(System.Collections.Generic.List<AssumedObjectData> value) {#setAssumedObjects-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.masking.options.AssumedObjectData--}
```
public final void setAssumedObjects_internalized(System.Collections.Generic.List<AssumedObjectData> value)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.masking.options.AssumedObjectData> |  |

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

### setCalculateDefaultStrokes(boolean value) {#setCalculateDefaultStrokes-boolean-}
```
public final void setCalculateDefaultStrokes(boolean value)
```


يضبط قيمة تشير إلى ما إذا كان يجب حساب الخطوط الافتراضية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | قيمة تشير إلى ما إذا كان يجب حساب الضربات الافتراضية. |

### setCombinedObjectsRectangle_internalized(Rectangle value) {#setCombinedObjectsRectangle-internalized-com.aspose.psd.Rectangle-}
```
public final void setCombinedObjectsRectangle_internalized(Rectangle value)
```


مستطيل الكائنات المدمجة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) | مستطيل الكائنات المدمجة. |

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

### setDefaultBackgroundStrokes_internalized(Point[] value) {#setDefaultBackgroundStrokes-internalized-com.aspose.psd.Point---}
```
public final void setDefaultBackgroundStrokes_internalized(Point[] value)
```


الخطوط الخلفية الافتراضية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.psd/point) | الضربات الخلفية الافتراضية. |

### setDefaultForegroundStrokes_internalized(Point[] value) {#setDefaultForegroundStrokes-internalized-com.aspose.psd.Point---}
```
public final void setDefaultForegroundStrokes_internalized(Point[] value)
```


الخطوط الأمامية الافتراضية المحسوبة مسبقًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.psd/point) | الضربات الأمامية الافتراضية المحسوبة مسبقًا. |

### setDefaultObjectsRectangles_internalized(Rectangle[] value) {#setDefaultObjectsRectangles-internalized-com.aspose.psd.Rectangle---}
```
public final void setDefaultObjectsRectangles_internalized(Rectangle[] value)
```


مستطيلات الكائنات الافتراضية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Rectangle\[\]](../../com.aspose.psd/rectangle) | مستطيلات الكائنات الافتراضية. |

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

### setHumans_internalized(boolean value) {#setHumans-internalized-boolean-}
```
public final void setHumans_internalized(boolean value)
```


قيمة تشير إلى ما إذا كانت مجموعة الكائنات المفترضة تحتوي على كائنات بشرية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | قيمة تشير إلى ما إذا كانت مجموعة الكائنات المفترضة تحتوي على كائنات بشرية. |

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

### setPrecalculationProgressEventHandler(ProgressEventHandler value) {#setPrecalculationProgressEventHandler-com.aspose.psd.ProgressEventHandler-}
```
public final void setPrecalculationProgressEventHandler(ProgressEventHandler value)
```


يضبط معالج حدث تقدم عملية حساب النقاط الافتراضية مسبقًا.

القيمة: معالج حدث التقدم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.psd/progresseventhandler) | معالج حدث تقدم عملية حساب النقاط الافتراضية مسبقًا. |

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

