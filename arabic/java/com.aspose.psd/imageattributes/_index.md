---
title: "ImageAttributes"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "كائن com.aspose.psd.ImageAttributes يحتوي على معلومات حول كيفية تعديل ألوان bitmap و metafile أثناء عملية العرض."
type: docs
weight: 55
url: /ar/java/com.aspose.psd/imageattributes/
---

**Inheritance:**
java.lang.Object
```
public final class ImageAttributes
```

كائن com.aspose.psd.ImageAttributes يحتوي على معلومات حول كيفية تعديل ألوان البت ماب وملفات الميتا خلال عملية التصيير. كائن com.aspose.psd.ImageAttributes يحافظ على عدة إعدادات لتعديل اللون، بما في ذلك مصفوفات تعديل اللون، ومصفوفات تعديل التدرج الرمادي، وقيم تصحيح جاما، وجداول خريطة الألوان، وقيم عتبة اللون. خلال التصيير، يمكن تصحيح الألوان، تعتيمها، تفتيحها، وإزالتها. لتطبيق مثل هذه التعديلات، قم بتهيئة كائن com.aspose.psd.ImageAttributes ومرّر مسار ذلك الكائن (مع مسار [Image](../../com.aspose.psd/image)) إلى طريقة drawImage.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [ImageAttributes()](#ImageAttributes--) | يُهيئ نسخة جديدة من فئة com.aspose.psd.ImageAttributes. |
## الحقول

| حقل | الوصف |
| --- | --- |
| [imageAttributes_internalized](#imageAttributes-internalized) | سمات صورة GDI. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [clearBrushRemapTable()](#clearBrushRemapTable--) | يمسح جدول إعادة تعيين ألوان الفرشاة لهذا الكائن com.aspose.psd.ImageAttributes. |
| [clearColorKey()](#clearColorKey--) | يمسح مفتاح اللون (نطاق الشفافية) للفئة الافتراضية. |
| [clearColorKey(int type)](#clearColorKey-int-) | يمسح مفتاح اللون (نطاق الشفافية) لفئة محددة. |
| [clearColorMatrix()](#clearColorMatrix--) | يمسح مصفوفة تعديل اللون للفئة الافتراضية. |
| [clearColorMatrix(int type)](#clearColorMatrix-int-) | يمسح مصفوفة تعديل اللون لفئة محددة. |
| [clearGamma()](#clearGamma--) | يعطل تصحيح جاما للفئة الافتراضية. |
| [clearGamma(int type)](#clearGamma-int-) | يعطل تصحيح جاما لفئة محددة. |
| [clearNoOp()](#clearNoOp--) | يمسح إعداد NoOp للفئة الافتراضية. |
| [clearNoOp(int type)](#clearNoOp-int-) | يمسح إعداد NoOp لفئة محددة. |
| [clearOutputChannel()](#clearOutputChannel--) | يمسح إعداد قناة الإخراج CMYK (سماوي-ماجنتا-أصفر-أسود) للفئة الافتراضية. |
| [clearOutputChannel(int type)](#clearOutputChannel-int-) | يمسح إعداد قناة الإخراج (سماوي-ماجنتا-أصفر-أسود) لفئة محددة. |
| [clearOutputChannelColorProfile()](#clearOutputChannelColorProfile--) | يمسح إعداد ملف تعريف لون قناة الإخراج للفئة الافتراضية. |
| [clearOutputChannelColorProfile(int type)](#clearOutputChannelColorProfile-int-) | يمسح إعداد ملف تعريف لون قناة الإخراج لفئة محددة. |
| [clearRemapTable()](#clearRemapTable--) | يمسح جدول إعادة تعيين اللون للفئة الافتراضية. |
| [clearRemapTable(int type)](#clearRemapTable-int-) | يمسح جدول إعادة تعيين اللون لفئة محددة. |
| [clearThreshold()](#clearThreshold--) | يمسح قيمة العتبة للفئة الافتراضية. |
| [clearThreshold(int type)](#clearThreshold-int-) | يمسح قيمة العتبة لفئة محددة. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBrushRemapTable(ColorMap[] map)](#setBrushRemapTable-com.aspose.psd.ColorMap---) | يضبط جدول إعادة تعيين اللون لفئة الفرشاة. |
| [setColorKey(Color colorLow, Color colorHigh)](#setColorKey-com.aspose.psd.Color-com.aspose.psd.Color-) | يضبط مفتاح اللون للفئة الافتراضية. |
| [setColorKey(Color colorLow, Color colorHigh, int type)](#setColorKey-com.aspose.psd.Color-com.aspose.psd.Color-int-) | يضبط مفتاح اللون (نطاق الشفافية) لفئة محددة. |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix)](#setColorMatrices-com.aspose.psd.ColorMatrix-com.aspose.psd.ColorMatrix-) | يضبط مصفوفة تعديل اللون ومصفوفة تعديل التدرج الرمادي للفئة الافتراضية. |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags)](#setColorMatrices-com.aspose.psd.ColorMatrix-com.aspose.psd.ColorMatrix-int-) | يضبط مصفوفة تعديل اللون ومصفوفة تعديل التدرج الرمادي للفئة الافتراضية. |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type)](#setColorMatrices-com.aspose.psd.ColorMatrix-com.aspose.psd.ColorMatrix-int-int-) | يضبط مصفوفة تعديل اللون ومصفوفة تعديل التدرج الرمادي لفئة محددة. |
| [setColorMatrix(ColorMatrix newColorMatrix)](#setColorMatrix-com.aspose.psd.ColorMatrix-) | يضبط مصفوفة تعديل اللون للفئة الافتراضية. |
| [setColorMatrix(ColorMatrix newColorMatrix, int flags)](#setColorMatrix-com.aspose.psd.ColorMatrix-int-) | يضبط مصفوفة تعديل اللون للفئة الافتراضية. |
| [setColorMatrix(ColorMatrix newColorMatrix, int mode, int type)](#setColorMatrix-com.aspose.psd.ColorMatrix-int-int-) | يضبط مصفوفة تعديل اللون لفئة محددة. |
| [setGamma(float gamma)](#setGamma-float-) | يضبط قيمة غاما للفئة الافتراضية. |
| [setGamma(float gamma, int type)](#setGamma-float-int-) | يضبط قيمة غاما لفئة محددة. |
| [setNoOp()](#setNoOp--) | يعطل تعديل اللون للفئة الافتراضية. |
| [setNoOp(int type)](#setNoOp-int-) | يعطل تعديل اللون لفئة محددة. |
| [setOutputChannel(int flags)](#setOutputChannel-int-) | يضبط قناة الإخراج CMYK (سماوي-ماجنطا-أصفر-أسود) للفئة الافتراضية. |
| [setOutputChannel(int flags, int type)](#setOutputChannel-int-int-) | يضبط قناة الإخراج CMYK (سماوي-ماجنطا-أصفر-أسود) لفئة محددة. |
| [setOutputChannelColorProfile(String colorProfileFilename)](#setOutputChannelColorProfile-java.lang.String-) | يضبط ملف ملف تعريف اللون لقناة الإخراج للفئة الافتراضية. |
| [setOutputChannelColorProfile(String colorProfileFilename, int type)](#setOutputChannelColorProfile-java.lang.String-int-) | يضبط ملف ملف تعريف اللون لقناة الإخراج لفئة محددة. |
| [setRemapTable(ColorMap[] map)](#setRemapTable-com.aspose.psd.ColorMap---) | يضبط جدول إعادة تعيين اللون للفئة الافتراضية. |
| [setRemapTable(ColorMap[] map, int type)](#setRemapTable-com.aspose.psd.ColorMap---int-) | يضبط جدول إعادة تعيين اللون لفئة محددة. |
| [setThreshold(float threshold)](#setThreshold-float-) | يضبط العتبة (نطاق الشفافية) للفئة الافتراضية. |
| [setThreshold(float threshold, int type)](#setThreshold-float-int-) | يضبط العتبة (نطاق الشفافية) لفئة محددة. |
| [setWrapMode(int mode)](#setWrapMode-int-) | يضبط وضع الالتفاف المستخدم لتحديد كيفية تكرار النسيج عبر الشكل أو عند حدود الشكل. |
| [setWrapMode(int mode, Color color)](#setWrapMode-int-com.aspose.psd.Color-) | يضبط وضع الالتفاف واللون المستخدم لتحديد كيفية تكرار النسيج عبر الشكل أو عند حدود الشكل. |
| [setWrapMode(int mode, Color color, boolean clamp)](#setWrapMode-int-com.aspose.psd.Color-boolean-) | يضبط وضع الالتفاف واللون المستخدم لتحديد كيفية تكرار النسيج عبر الشكل أو عند حدود الشكل. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ImageAttributes() {#ImageAttributes--}
```
public ImageAttributes()
```


يُهيئ نسخة جديدة من فئة com.aspose.psd.ImageAttributes.

### imageAttributes_internalized {#imageAttributes-internalized}
```
public final System.Drawing.Imaging.ImageAttributes imageAttributes_internalized
```


سمات صورة GDI.

### clearBrushRemapTable() {#clearBrushRemapTable--}
```
public void clearBrushRemapTable()
```


يمسح جدول إعادة تعيين ألوان الفرشاة لهذا الكائن com.aspose.psd.ImageAttributes.

### clearColorKey() {#clearColorKey--}
```
public void clearColorKey()
```


يمسح مفتاح اللون (نطاق الشفافية) للفئة الافتراضية.

### clearColorKey(int type) {#clearColorKey-int-}
```
public void clearColorKey(int type)
```


يمسح مفتاح اللون (نطاق الشفافية) لفئة محددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| نوع | int | عنصر من  Aspose.Imaging.ColorAdjustType  يحدد الفئة التي يتم مسح مفتاح اللون لها. |

### clearColorMatrix() {#clearColorMatrix--}
```
public void clearColorMatrix()
```


يمسح مصفوفة تعديل اللون للفئة الافتراضية.

### clearColorMatrix(int type) {#clearColorMatrix-int-}
```
public void clearColorMatrix(int type)
```


يمسح مصفوفة تعديل اللون لفئة محددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| نوع | int | عنصر من  Aspose.Imaging.ColorAdjustType  يحدد الفئة التي يتم مسح مصفوفة تعديل اللون لها. |

### clearGamma() {#clearGamma--}
```
public void clearGamma()
```


يعطل تصحيح جاما للفئة الافتراضية.

### clearGamma(int type) {#clearGamma-int-}
```
public void clearGamma(int type)
```


يعطل تصحيح جاما لفئة محددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| نوع | int | عنصر من  Aspose.Imaging.ColorAdjustType  يحدد الفئة التي يتم تعطيل تصحيح غاما لها. |

### clearNoOp() {#clearNoOp--}
```
public void clearNoOp()
```


يمسح إعداد NoOp للفئة الافتراضية.

### clearNoOp(int type) {#clearNoOp-int-}
```
public void clearNoOp(int type)
```


يمسح إعداد NoOp لفئة محددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| نوع | int | عنصر من  Aspose.Imaging.ColorAdjustType  يحدد الفئة التي يتم مسح إعداد NoOp لها. |

### clearOutputChannel() {#clearOutputChannel--}
```
public void clearOutputChannel()
```


يمسح إعداد قناة الإخراج CMYK (سماوي-ماجنتا-أصفر-أسود) للفئة الافتراضية.

### clearOutputChannel(int type) {#clearOutputChannel-int-}
```
public void clearOutputChannel(int type)
```


يمسح إعداد قناة الإخراج (سماوي-ماجنتا-أصفر-أسود) لفئة محددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| نوع | int | عنصر من  Aspose.Imaging.ColorAdjustType  يحدد الفئة التي يتم مسح إعداد قناة الإخراج لها. |

### clearOutputChannelColorProfile() {#clearOutputChannelColorProfile--}
```
public void clearOutputChannelColorProfile()
```


يمسح إعداد ملف تعريف لون قناة الإخراج للفئة الافتراضية.

### clearOutputChannelColorProfile(int type) {#clearOutputChannelColorProfile-int-}
```
public void clearOutputChannelColorProfile(int type)
```


يمسح إعداد ملف تعريف لون قناة الإخراج لفئة محددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| نوع | int | عنصر من  Aspose.Imaging.ColorAdjustType  يحدد الفئة التي يتم مسح إعداد ملف تعريف قناة الإخراج لها. |

### clearRemapTable() {#clearRemapTable--}
```
public void clearRemapTable()
```


يمسح جدول إعادة تعيين اللون للفئة الافتراضية.

### clearRemapTable(int type) {#clearRemapTable-int-}
```
public void clearRemapTable(int type)
```


يمسح جدول إعادة تعيين اللون لفئة محددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| نوع | int | عنصر من  Aspose.Imaging.ColorAdjustType  يحدد الفئة التي يتم مسح جدول إعادة التعيين لها. |

### clearThreshold() {#clearThreshold--}
```
public void clearThreshold()
```


يمسح قيمة العتبة للفئة الافتراضية.

### clearThreshold(int type) {#clearThreshold-int-}
```
public void clearThreshold(int type)
```


يمسح قيمة العتبة لفئة محددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| نوع | int | عنصر من  Aspose.Imaging.ColorAdjustType  يحدد الفئة التي يتم مسح العتبة لها. |

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




### setBrushRemapTable(ColorMap[] map) {#setBrushRemapTable-com.aspose.psd.ColorMap---}
```
public void setBrushRemapTable(ColorMap[] map)
```


يضبط جدول إعادة تعيين اللون لفئة الفرشاة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.psd/colormap) | مصفوفة من كائنات  com.aspose.psd.ColorMap  . |

### setColorKey(Color colorLow, Color colorHigh) {#setColorKey-com.aspose.psd.Color-com.aspose.psd.Color-}
```
public void setColorKey(Color colorLow, Color colorHigh)
```


يضبط مفتاح اللون للفئة الافتراضية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| colorLow | [Color](../../com.aspose.psd/color) | القيمة المنخفضة لمفتاح اللون. |
| colorHigh | [Color](../../com.aspose.psd/color) | القيمة العالية لمفتاح اللون. |

### setColorKey(Color colorLow, Color colorHigh, int type) {#setColorKey-com.aspose.psd.Color-com.aspose.psd.Color-int-}
```
public void setColorKey(Color colorLow, Color colorHigh, int type)
```


يضبط مفتاح اللون (نطاق الشفافية) لفئة محددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| colorLow | [Color](../../com.aspose.psd/color) | القيمة المنخفضة لمفتاح اللون. |
| colorHigh | [Color](../../com.aspose.psd/color) | القيمة العالية لمفتاح اللون. |
| نوع | int | عنصر من Aspose.Imaging.ColorAdjustType يحدد الفئة التي يتم تعيين مفتاح اللون لها. |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix) {#setColorMatrices-com.aspose.psd.ColorMatrix-com.aspose.psd.ColorMatrix-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix)
```


يضبط مصفوفة تعديل اللون ومصفوفة تعديل التدرج الرمادي للفئة الافتراضية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | مصفوفة تعديل اللون. |
| grayMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | مصفوفة تعديل التدرج الرمادي. |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags) {#setColorMatrices-com.aspose.psd.ColorMatrix-com.aspose.psd.ColorMatrix-int-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags)
```


يضبط مصفوفة تعديل اللون ومصفوفة تعديل التدرج الرمادي للفئة الافتراضية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | مصفوفة تعديل اللون. |
| grayMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | مصفوفة تعديل التدرج الرمادي. |
| علامات | int | عنصر من Aspose.Imaging.ColorMatrixFlag يحدد نوع الصورة واللون الذي سيتأثر بمصفوفات تعديل اللون وتعديل التدرج الرمادي. |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type) {#setColorMatrices-com.aspose.psd.ColorMatrix-com.aspose.psd.ColorMatrix-int-int-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type)
```


يضبط مصفوفة تعديل اللون ومصفوفة تعديل التدرج الرمادي لفئة محددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | مصفوفة تعديل اللون. |
| grayMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | مصفوفة تعديل التدرج الرمادي. |
| الوضع | int | عنصر من Aspose.Imaging.ColorMatrixFlag يحدد نوع الصورة واللون الذي سيتأثر بمصفوفات تعديل اللون وتعديل التدرج الرمادي. |
| نوع | int | عنصر من Aspose.Imaging.ColorAdjustType يحدد الفئة التي يتم تعيين مصفوفات تعديل اللون وتعديل التدرج الرمادي لها. |

### setColorMatrix(ColorMatrix newColorMatrix) {#setColorMatrix-com.aspose.psd.ColorMatrix-}
```
public void setColorMatrix(ColorMatrix newColorMatrix)
```


يضبط مصفوفة تعديل اللون للفئة الافتراضية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | مصفوفة تعديل اللون. |

### setColorMatrix(ColorMatrix newColorMatrix, int flags) {#setColorMatrix-com.aspose.psd.ColorMatrix-int-}
```
public void setColorMatrix(ColorMatrix newColorMatrix, int flags)
```


يضبط مصفوفة تعديل اللون للفئة الافتراضية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | مصفوفة تعديل اللون. |
| علامات | int | عنصر من Aspose.Imaging.ColorMatrixFlag يحدد نوع الصورة واللون الذي سيتأثر بمصفوفة تعديل اللون. |

### setColorMatrix(ColorMatrix newColorMatrix, int mode, int type) {#setColorMatrix-com.aspose.psd.ColorMatrix-int-int-}
```
public void setColorMatrix(ColorMatrix newColorMatrix, int mode, int type)
```


يضبط مصفوفة تعديل اللون لفئة محددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | مصفوفة تعديل اللون. |
| الوضع | int | عنصر من Aspose.Imaging.ColorMatrixFlag يحدد نوع الصورة واللون الذي سيتأثر بمصفوفة تعديل اللون. |
| نوع | int | عنصر من Aspose.Imaging.ColorAdjustType يحدد الفئة التي يتم تعيين مصفوفة تعديل اللون لها. |

### setGamma(float gamma) {#setGamma-float-}
```
public void setGamma(float gamma)
```


يضبط قيمة غاما للفئة الافتراضية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| جاما | float | قيمة تصحيح جاما. |

### setGamma(float gamma, int type) {#setGamma-float-int-}
```
public void setGamma(float gamma, int type)
```


يضبط قيمة غاما لفئة محددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| جاما | float | قيمة تصحيح جاما. |
| نوع | int | عنصر من تعداد Aspose.Imaging.ColorAdjustType يحدد الفئة التي يتم تعيين قيمة الجاما لها. |

### setNoOp() {#setNoOp--}
```
public void setNoOp()
```


يعطل تعديل اللون للفئة الافتراضية.

### setNoOp(int type) {#setNoOp-int-}
```
public void setNoOp(int type)
```


يعطل تعديل اللون لفئة محددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| نوع | int | عنصر من Aspose.Imaging.ColorAdjustType يحدد الفئة التي يتم إيقاف تصحيح اللون لها. |

### setOutputChannel(int flags) {#setOutputChannel-int-}
```
public void setOutputChannel(int flags)
```


يضبط قناة الإخراج CMYK (سماوي-ماجنطا-أصفر-أسود) للفئة الافتراضية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| علامات | int | عنصر من Aspose.Imaging.ColorChannelFlag يحدد القناة الخارجة. |

### setOutputChannel(int flags, int type) {#setOutputChannel-int-int-}
```
public void setOutputChannel(int flags, int type)
```


يضبط قناة الإخراج CMYK (سماوي-ماجنطا-أصفر-أسود) لفئة محددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| علامات | int | عنصر من Aspose.Imaging.ColorChannelFlag يحدد القناة الخارجة. |
| نوع | int | عنصر من Aspose.Imaging.ColorAdjustType يحدد الفئة التي يتم تعيين القناة الخارجة لها. |

### setOutputChannelColorProfile(String colorProfileFilename) {#setOutputChannelColorProfile-java.lang.String-}
```
public void setOutputChannelColorProfile(String colorProfileFilename)
```


يضبط ملف ملف تعريف اللون لقناة الإخراج للفئة الافتراضية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| colorProfileFilename | java.lang.String | اسم المسار لملف ملف تعريف اللون. إذا كان ملف تعريف اللون موجودًا في الدليل %SystemRoot%\\System32\\Spool\\Drivers\\Color، يمكن أن يكون هذا المعامل اسم الملف. وإلا، يجب أن يكون هذا المعامل اسم المسار المؤهل بالكامل. |

### setOutputChannelColorProfile(String colorProfileFilename, int type) {#setOutputChannelColorProfile-java.lang.String-int-}
```
public void setOutputChannelColorProfile(String colorProfileFilename, int type)
```


يضبط ملف ملف تعريف اللون لقناة الإخراج لفئة محددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| colorProfileFilename | java.lang.String | اسم المسار لملف ملف تعريف اللون. إذا كان ملف تعريف اللون موجودًا في الدليل %SystemRoot%\\System32\\Spool\\Drivers\\Color، يمكن أن يكون هذا المعامل اسم الملف. وإلا، يجب أن يكون هذا المعامل اسم المسار المؤهل بالكامل. |
| نوع | int | عنصر من Aspose.Imaging.ColorAdjustType يحدد الفئة التي يتم تعيين ملف تعريف لون القناة الخارجة لها. |

### setRemapTable(ColorMap[] map) {#setRemapTable-com.aspose.psd.ColorMap---}
```
public void setRemapTable(ColorMap[] map)
```


يضبط جدول إعادة تعيين اللون للفئة الافتراضية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.psd/colormap) | مصفوفة من أزواج الألوان من النوع com.aspose.psd.ColorMap. يحتوي كل زوج ألوان على لون موجود (القيمة الأولى) واللون الذي سيتم تحويله إليه (القيمة الثانية). |

### setRemapTable(ColorMap[] map, int type) {#setRemapTable-com.aspose.psd.ColorMap---int-}
```
public void setRemapTable(ColorMap[] map, int type)
```


يضبط جدول إعادة تعيين اللون لفئة محددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.psd/colormap) | مصفوفة من أزواج الألوان من النوع com.aspose.psd.ColorMap. يحتوي كل زوج ألوان على لون موجود (القيمة الأولى) واللون الذي سيتم تحويله إليه (القيمة الثانية). |
| نوع | int | عنصر من Aspose.Imaging.ColorAdjustType يحدد الفئة التي يتم تعيين جدول إعادة تعيين اللون لها. |

### setThreshold(float threshold) {#setThreshold-float-}
```
public void setThreshold(float threshold)
```


يضبط العتبة (نطاق الشفافية) للفئة الافتراضية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| threshold | float | عدد حقيقي يحدد قيمة العتبة. |

### setThreshold(float threshold, int type) {#setThreshold-float-int-}
```
public void setThreshold(float threshold, int type)
```


يضبط العتبة (نطاق الشفافية) لفئة محددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| threshold | float | قيمة عتبة من 0.0 إلى 1.0 تُستخدم كنقطة فصل لفرز الألوان التي سيتم تحويلها إلى قيمة قصوى أو دنيا. |
| نوع | int | عنصر من Aspose.Imaging.ColorAdjustType يحدد الفئة التي يتم تعيين عتبة اللون لها. |

### setWrapMode(int mode) {#setWrapMode-int-}
```
public void setWrapMode(int mode)
```


يضبط وضع الالتفاف المستخدم لتحديد كيفية تكرار النسيج عبر الشكل أو على حدود الشكل. يتم تكرار النسيج عبر الشكل لملئه عندما يكون النسيج أصغر من الشكل الذي يُملأ.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الوضع | int | عنصر من Aspose.Imaging.WrapMode يحدد كيفية استخدام النسخ المتكررة من الصورة لتغطية منطقة. |

### setWrapMode(int mode, Color color) {#setWrapMode-int-com.aspose.psd.Color-}
```
public void setWrapMode(int mode, Color color)
```


يضبط وضع الالتفاف واللون المستخدم لتحديد كيفية تكرار النسيج عبر الشكل، أو عند حدود الشكل. يتم تكرار النسيج عبر الشكل لملئه عندما يكون النسيج أصغر من الشكل الذي يتم ملئه.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الوضع | int | عنصر من Aspose.Imaging.WrapMode يحدد كيفية استخدام النسخ المتكررة من الصورة لتغطية منطقة. |
| color | [Color](../../com.aspose.psd/color) | كائن  com.aspose.psd.ImageAttributes  يحدد لون البكسلات خارج الصورة المُعالجة. يكون هذا اللون مرئياً إذا تم تعيين معامل الوضع إلى  WrapMode.Clamp  وكان المستطيل المصدر الممرّر إلى DrawImage أكبر من الصورة نفسها. |

### setWrapMode(int mode, Color color, boolean clamp) {#setWrapMode-int-com.aspose.psd.Color-boolean-}
```
public void setWrapMode(int mode, Color color, boolean clamp)
```


يضبط وضع الالتفاف واللون المستخدم لتحديد كيفية تكرار النسيج عبر الشكل، أو عند حدود الشكل. يتم تكرار النسيج عبر الشكل لملئه عندما يكون النسيج أصغر من الشكل الذي يتم ملئه.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الوضع | int | عنصر من Aspose.Imaging.WrapMode يحدد كيفية استخدام النسخ المتكررة من الصورة لتغطية منطقة. |
| color | [Color](../../com.aspose.psd/color) | كائن اللون يحدد لون البكسلات خارج الصورة المُعالجة. يكون هذا اللون مرئياً إذا تم تعيين معامل الوضع إلى  WrapMode.Clamp  وكان المستطيل المصدر الممرّر إلى DrawImage أكبر من الصورة نفسها. |
| قفل | boolean | هذا المعامل ليس له تأثير. اضبطه على false. |

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

