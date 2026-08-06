---
title: "AiLayerSection"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "قسم طبقة تنسيق Ai"
type: docs
weight: 15
url: /ar/java/com.aspose.psd.fileformats.ai/ailayersection/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.fileformats.ai.AiDataSection](../../com.aspose.psd.fileformats.ai/aidatasection)
```
public final class AiLayerSection extends AiDataSection
```

قسم طبقة تنسيق Ai
## الطرق

| طريقة | الوصف |
| --- | --- |
| [addRasterImage(AiRasterImageSection rasterImage)](#addRasterImage-com.aspose.psd.fileformats.ai.AiRasterImageSection-) | يضيف صورة نقطية. |
| [close()](#close--) | تنفذ واجهة Closable ويمكن استخدامها في عبارة try-with-resources منذ JDK 1.7. |
| [create_internalized(StreamContainer stream)](#create-internalized-com.aspose.psd.StreamContainer-) |  |
| [create_internalized(String name, String[] properties, StreamContainer stream)](#create-internalized-java.lang.String-java.lang.String---com.aspose.psd.StreamContainer-) |  |
| [dispose()](#dispose--) | يحرر النسخة الحالية. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlue()](#getBlue--) | يحصل أو يضبط مكوّن اللون الأزرق. |
| [getClass()](#getClass--) |  |
| [getColorIndex()](#getColorIndex--) | يحصل أو يضبط فهرس اللون. |
| [getColorNumber()](#getColorNumber--) | يحصل أو يضبط رقم اللون. |
| [getData()](#getData--) | يحصل على بيانات السلسلة. |
| [getDimValue()](#getDimValue--) | يحصل أو يضبط قيمة التعتيم كنسبة مئوية. |
| [getDisposed()](#getDisposed--) | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن قد تم التخلص منه. |
| [getGreen()](#getGreen--) | يحصل أو يضبط مكوّن اللون الأخضر. |
| [getName()](#getName--) | يحصل أو يضبط اسم الطبقة. |
| [getRasterImages()](#getRasterImages--) | يحصل على صور نقطية. |
| [getRed()](#getRed--) | يحصل أو يضبط مكوّن اللون الأحمر. |
| [getStream_internalized()](#getStream-internalized--) | يحصل على الدفق الداخلي |
| [hasMultiLayerMasks()](#hasMultiLayerMasks--) | يحصل أو يضبط قيمة تشير إلى ما إذا كان هذا الكائن يحتوي على أقنعة متعددة الطبقات. |
| [hashCode()](#hashCode--) |  |
| [isImagesDimmed()](#isImagesDimmed--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت هذه الطبقة مخفّضة. |
| [isLocked()](#isLocked--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت هذه الطبقة مقفلة. |
| [isPreview()](#isPreview--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت هذه الطبقة في وضع المعاينة. |
| [isPrinted()](#isPrinted--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت هذه الطبقة مطبوعة. |
| [isShown()](#isShown--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت هذه الطبقة معروضة. |
| [isTemplate()](#isTemplate--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت هذه الطبقة طبقة قالب. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBlue(int value)](#setBlue-int-) | يحصل أو يضبط مكوّن اللون الأزرق. |
| [setColorIndex(int value)](#setColorIndex-int-) | يحصل أو يضبط فهرس اللون. |
| [setColorNumber(int value)](#setColorNumber-int-) | يحصل أو يضبط رقم اللون. |
| [setDimValue(int value)](#setDimValue-int-) | يحصل أو يضبط قيمة التعتيم كنسبة مئوية. |
| [setGreen(int value)](#setGreen-int-) | يحصل أو يضبط مكوّن اللون الأخضر. |
| [setImagesDimmed(boolean value)](#setImagesDimmed-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت هذه الطبقة مخفّضة. |
| [setLocked(boolean value)](#setLocked-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت هذه الطبقة مقفلة. |
| [setMultiLayerMasks(boolean value)](#setMultiLayerMasks-boolean-) | يحصل أو يضبط قيمة تشير إلى ما إذا كان هذا الكائن يحتوي على أقنعة متعددة الطبقات. |
| [setName(String value)](#setName-java.lang.String-) | يحصل أو يضبط اسم الطبقة. |
| [setPreview(boolean value)](#setPreview-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت هذه الطبقة في وضع المعاينة. |
| [setPrinted(boolean value)](#setPrinted-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت هذه الطبقة مطبوعة. |
| [setRed(int value)](#setRed-int-) | يحصل أو يضبط مكوّن اللون الأحمر. |
| [setShown(boolean value)](#setShown-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت هذه الطبقة معروضة. |
| [setTemplate(boolean value)](#setTemplate-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت هذه الطبقة طبقة قالب. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### addRasterImage(AiRasterImageSection rasterImage) {#addRasterImage-com.aspose.psd.fileformats.ai.AiRasterImageSection-}
```
public final void addRasterImage(AiRasterImageSection rasterImage)
```


يضيف صورة نقطية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rasterImage | [AiRasterImageSection](../../com.aspose.psd.fileformats.ai/airasterimagesection) | الصورة النقطية. |

### close() {#close--}
```
public void close()
```


تنفيذ واجهة Closable ويمكن استخدامها في بيان try-with-resources منذ JDK 1.7. هذه الطريقة تستدعي ببساطة طريقة dispose.

### create_internalized(StreamContainer stream) {#create-internalized-com.aspose.psd.StreamContainer-}
```
public static AiDataSection create_internalized(StreamContainer stream)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.psd/streamcontainer) |  |

**Returns:**
[AiDataSection](../../com.aspose.psd.fileformats.ai/aidatasection)
### create_internalized(String name, String[] properties, StreamContainer stream) {#create-internalized-java.lang.String-java.lang.String---com.aspose.psd.StreamContainer-}
```
public static AiLayerSection create_internalized(String name, String[] properties, StreamContainer stream)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String |  |
| الخصائص | java.lang.String[] |  |
| stream | [StreamContainer](../../com.aspose.psd/streamcontainer) |  |

**Returns:**
[AiLayerSection](../../com.aspose.psd.fileformats.ai/ailayersection)
### dispose() {#dispose--}
```
public final void dispose()
```


يحرر النسخة الحالية.

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
### getBlue() {#getBlue--}
```
public final int getBlue()
```


يحصل أو يضبط مكوّن اللون الأزرق.

القيمة: مكوّن اللون الأزرق.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorIndex() {#getColorIndex--}
```
public final int getColorIndex()
```


يحصل أو يعيّن فهرس اللون. يمكن أن يأخذ هذا الوسيط قيمًا بين \\u20131 و 26. كل عدد صحيح يمثل لونًا يمكن تعيينه للطبقة لأغراض تعريف المستخدم.

القيمة: فهرس اللون.

**Returns:**
int
### getColorNumber() {#getColorNumber--}
```
public final int getColorNumber()
```


يحصل أو يعيّن رقم اللون. -1 هو قيمة اللون المخصصة من خصائص الأحمر والأخضر والأزرق. يحدد إعداد لون الطبقة\\u2019s.

القيمة: رقم اللون.

**Returns:**
int
### getData() {#getData--}
```
public final String getData()
```


يحصل على بيانات السلسلة.

**Returns:**
java.lang.String - بيانات السلسلة للقسم
### getDimValue() {#getDimValue--}
```
public final int getDimValue()
```


يحصل أو يعيّن قيمة التخفيف كنسبة مئوية. يقلل من شدة الصور المرتبطة وصور البت ماب الموجودة في الطبقة إلى النسبة المئوية المحددة.

القيمة: قيمة التخفيف كنسبة مئوية.

**Returns:**
int
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


يحصل على قيمة تشير إلى ما إذا كان هذا الكائن قد تم التخلص منه.

**Returns:**
boolean -  true  إذا تم التخلص؛ وإلا،  false .
### getGreen() {#getGreen--}
```
public final int getGreen()
```


يحصل أو يضبط مكوّن اللون الأخضر.

القيمة: مكوّن اللون الأخضر.

**Returns:**
int
### getName() {#getName--}
```
public final String getName()
```


يحصل أو يعيّن اسم الطبقة. يحدد اسم العنصر كما يظهر في لوحة الطبقات.

القيمة: اسم الطبقة.

**Returns:**
java.lang.String
### getRasterImages() {#getRasterImages--}
```
public final AiRasterImageSection[] getRasterImages()
```


يحصل على صور نقطية.

القيمة: صور نقطية.

**Returns:**
com.aspose.psd.fileformats.ai.AiRasterImageSection[]
### getRed() {#getRed--}
```
public final int getRed()
```


يحصل أو يضبط مكوّن اللون الأحمر.

القيمة: مكوّن اللون الأحمر.

**Returns:**
int
### getStream_internalized() {#getStream-internalized--}
```
public final StreamContainer getStream_internalized()
```


يحصل على الدفق الداخلي

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer) - The  StreamContainer  instance.
### hasMultiLayerMasks() {#hasMultiLayerMasks--}
```
public final boolean hasMultiLayerMasks()
```


يحصل أو يضبط قيمة تشير إلى ما إذا كان هذا الكائن يحتوي على أقنعة متعددة الطبقات.

القيمة:  true  إذا كان لهذا الكائن أقنعة متعددة الطبقات؛ وإلا،  false .

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isImagesDimmed() {#isImagesDimmed--}
```
public final boolean isImagesDimmed()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كانت هذه الطبقة مخفّضة. يقلل من شدة الصور المرتبطة وصور البت ماب الموجودة في الطبقة.

القيمة:  true  إذا كانت هذه الطبقة مخفّضة؛ وإلا،  false .

**Returns:**
boolean
### isLocked() {#isLocked--}
```
public final boolean isLocked()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كانت هذه الطبقة مقفلة. يمنع التغييرات على العنصر.

القيمة:  true  إذا كانت هذه الطبقة مقفلة؛ وإلا،  false .

**Returns:**
boolean
### isPreview() {#isPreview--}
```
public final boolean isPreview()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كانت هذه الطبقة في وضع المعاينة. يعرض الأعمال الفنية الموجودة في الطبقة بالألوان بدلاً من الخطوط الخارجية.

القيمة:  true  إذا كانت هذه الطبقة في وضع المعاينة؛ وإلا،  false .

**Returns:**
boolean
### isPrinted() {#isPrinted--}
```
public final boolean isPrinted()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا تم طباعة هذه الطبقة. يجعل العمل الفني الموجود في الطبقة قابلًا للطباعة إذا كان true.

القيمة:  true  إذا تم طباعة هذه الطبقة؛ وإلا،  false .

**Returns:**
boolean
### isShown() {#isShown--}
```
public final boolean isShown()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كانت هذه الطبقة معروضة. يعرض جميع العمل الفني الموجود في الطبقة على لوحة الرسم إذا كان true.

القيمة:  true  إذا كانت هذه الطبقة معروضة؛ وإلا،  false .

**Returns:**
boolean
### isTemplate() {#isTemplate--}
```
public final boolean isTemplate()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كانت هذه الطبقة طبقة قالب.

القيمة:  true  إذا كانت هذه الطبقة قالبًا؛ وإلا،  false .

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




### setBlue(int value) {#setBlue-int-}
```
public final void setBlue(int value)
```


يحصل أو يضبط مكوّن اللون الأزرق.

القيمة: مكوّن اللون الأزرق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setColorIndex(int value) {#setColorIndex-int-}
```
public final void setColorIndex(int value)
```


يحصل أو يعيّن فهرس اللون. يمكن أن يأخذ هذا الوسيط قيمًا بين \\u20131 و 26. كل عدد صحيح يمثل لونًا يمكن تعيينه للطبقة لأغراض تعريف المستخدم.

القيمة: فهرس اللون.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setColorNumber(int value) {#setColorNumber-int-}
```
public final void setColorNumber(int value)
```


يحصل أو يعيّن رقم اللون. -1 هو قيمة اللون المخصصة من خصائص الأحمر والأخضر والأزرق. يحدد إعداد لون الطبقة\\u2019s.

القيمة: رقم اللون.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setDimValue(int value) {#setDimValue-int-}
```
public final void setDimValue(int value)
```


يحصل أو يعيّن قيمة التخفيف كنسبة مئوية. يقلل من شدة الصور المرتبطة وصور البت ماب الموجودة في الطبقة إلى النسبة المئوية المحددة.

القيمة: قيمة التخفيف كنسبة مئوية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setGreen(int value) {#setGreen-int-}
```
public final void setGreen(int value)
```


يحصل أو يضبط مكوّن اللون الأخضر.

القيمة: مكوّن اللون الأخضر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setImagesDimmed(boolean value) {#setImagesDimmed-boolean-}
```
public final void setImagesDimmed(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كانت هذه الطبقة مخفّضة. يقلل من شدة الصور المرتبطة وصور البت ماب الموجودة في الطبقة.

القيمة:  true  إذا كانت هذه الطبقة مخفّضة؛ وإلا،  false .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setLocked(boolean value) {#setLocked-boolean-}
```
public final void setLocked(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كانت هذه الطبقة مقفلة. يمنع التغييرات على العنصر.

القيمة:  true  إذا كانت هذه الطبقة مقفلة؛ وإلا،  false .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setMultiLayerMasks(boolean value) {#setMultiLayerMasks-boolean-}
```
public final void setMultiLayerMasks(boolean value)
```


يحصل أو يضبط قيمة تشير إلى ما إذا كان هذا الكائن يحتوي على أقنعة متعددة الطبقات.

القيمة:  true  إذا كان لهذا الكائن أقنعة متعددة الطبقات؛ وإلا،  false .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


يحصل أو يعيّن اسم الطبقة. يحدد اسم العنصر كما يظهر في لوحة الطبقات.

القيمة: اسم الطبقة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setPreview(boolean value) {#setPreview-boolean-}
```
public final void setPreview(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كانت هذه الطبقة في وضع المعاينة. يعرض الأعمال الفنية الموجودة في الطبقة بالألوان بدلاً من الخطوط الخارجية.

القيمة:  true  إذا كانت هذه الطبقة في وضع المعاينة؛ وإلا،  false .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setPrinted(boolean value) {#setPrinted-boolean-}
```
public final void setPrinted(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا تم طباعة هذه الطبقة. يجعل العمل الفني الموجود في الطبقة قابلًا للطباعة إذا كان true.

القيمة:  true  إذا تم طباعة هذه الطبقة؛ وإلا،  false .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setRed(int value) {#setRed-int-}
```
public final void setRed(int value)
```


يحصل أو يضبط مكوّن اللون الأحمر.

القيمة: مكوّن اللون الأحمر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setShown(boolean value) {#setShown-boolean-}
```
public final void setShown(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كانت هذه الطبقة معروضة. يعرض جميع العمل الفني الموجود في الطبقة على لوحة الرسم إذا كان true.

القيمة:  true  إذا كانت هذه الطبقة معروضة؛ وإلا،  false .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setTemplate(boolean value) {#setTemplate-boolean-}
```
public final void setTemplate(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كانت هذه الطبقة طبقة قالب.

القيمة:  true  إذا كانت هذه الطبقة قالبًا؛ وإلا،  false .

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

