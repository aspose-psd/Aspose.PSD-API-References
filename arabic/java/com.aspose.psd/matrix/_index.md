---
title: "Matrix"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "يستبدل GDI Matrix."
type: docs
weight: 69
url: /ar/java/com.aspose.psd/matrix/
---

**Inheritance:**
java.lang.Object
```
public class Matrix
```

يستبدل مصفوفة GDI+.

معظم الخوارزميات مأخوذة من AffineTransform.java الخاص بـ Sun. أسماء جافا لعناصر المصفوفة المستخدمة داخليًا. خريطة أسماء جافا إلى أسماء .net مع الوصف: m00 M11 مقياس X m10 M12 قص Y m01 M21 قص X m11 M22 مقياس Y m02 M31 ترجمة X m12 M32 ترجمة Y
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [Matrix()](#Matrix--) | ينشئ نسخة جديدة من فئة Matrix كمصفوفة هوية. |
| [Matrix(float m11, float m12, float m21, float m22, float m31, float m32)](#Matrix-float-float-float-float-float-float-) | ينشئ نسخة جديدة من فئة Matrix. |
| [Matrix(Matrix origin)](#Matrix-com.aspose.psd.Matrix-) | ينشئ نسخة من فئة Matrix. |
| [Matrix(RectangleF rect, PointF[] plgpts)](#Matrix-com.aspose.psd.RectangleF-com.aspose.psd.PointF---) | ينشئ نسخة جديدة من فئة Aspose.Imaging.Matrix للتحويل الهندسي المحدد بالمستطيل المحدد ومصفوفة النقاط. |
| [Matrix(Rectangle rect, Point[] plgpts)](#Matrix-com.aspose.psd.Rectangle-com.aspose.psd.Point---) | ينشئ نسخة جديدة من فئة Aspose.Imaging.Matrix للتحويل الهندسي المحدد بالمستطيل المحدد ومصفوفة النقاط. |
## الحقول

| حقل | الوصف |
| --- | --- |
| [TYPE_FLIP](#TYPE-FLIP) | تشير هذه البتة flag إلى أن التحويل المحدد بواسطة هذا الكائن يقوم بعكس صورة مرآة حول محور ما، مما يغيّر نظام الإحداثيات الأيمن المعتاد إلى نظام أيسر، بالإضافة إلى التحويلات المشار إليها ببتات flag الأخرى. |
| [TYPE_GENERAL_ROTATION](#TYPE-GENERAL-ROTATION) | تشير هذه البتة flag إلى أن التحويل المحدد بواسطة هذا الكائن يقوم بدوران بزاوية عشوائية، بالإضافة إلى التحويلات المشار إليها ببتات flag الأخرى. |
| [TYPE_GENERAL_SCALE](#TYPE-GENERAL-SCALE) | المقياس العام يضرب طول المتجهات بمقادير مختلفة في اتجاهي x و y دون تغيير الزاوية بين المتجهات المتعامدة. |
| [TYPE_GENERAL_TRANSFORM](#TYPE-GENERAL-TRANSFORM) | تشير هذه الثابت إلى أن التحويل المحدد بواسطة هذا الكائن يقوم بتحويل عشوائي لإحداثيات الإدخال. |
| [TYPE_IDENTITY](#TYPE-IDENTITY) | التحويل الهوية هو التحويل الذي تكون فيه إحداثيات الخرج دائمًا هي نفسها إحداثيات الإدخال. |
| [TYPE_MASK_ROTATION](#TYPE-MASK-ROTATION) | هذه الثابتة هي قناع بت لأي من بتات flag الخاصة بالدوران. |
| [TYPE_MASK_SCALE](#TYPE-MASK-SCALE) | هذه الثابتة هي قناع بت لأي من بتات flag الخاصة بالمقياس. |
| [TYPE_QUADRANT_ROTATION](#TYPE-QUADRANT-ROTATION) | تشير هذه البتة flag إلى أن التحويل المحدد بواسطة هذا الكائن يقوم بدوران ربعي بضعف من 90 درجة، بالإضافة إلى التحويلات المشار إليها ببتات flag الأخرى. |
| [TYPE_TRANSLATION](#TYPE-TRANSLATION) | الترجمة تنقل الإحداثيات بمقدار ثابت في x و y دون تغيير طول أو زاوية المتجهات. |
| [TYPE_UNIFORM_SCALE](#TYPE-UNIFORM-SCALE) | المقياس المتساوي يضاعف طول المتجهات بنفس المقدار في اتجاهي x و y دون تغيير الزاوية بين المتجهات. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | يحدد ما إذا كان الكائن System.Object المحدد يساوي هذه الحالة. |
| [getClass()](#getClass--) |  |
| [getElements()](#getElements--) | يحصل على نسخة من عناصر المصفوفة. |
| [getM11()](#getM11--) | يحصل على عنصر المصفوفة في الصف الأول والعمود الأول. |
| [getM12()](#getM12--) | يحصل على عنصر المصفوفة في الصف الأول والعمود الثاني. |
| [getM21()](#getM21--) | يحصل على عنصر المصفوفة في الصف الثاني والعمود الأول. |
| [getM22()](#getM22--) | يحصل على عنصر المصفوفة في الصف الثاني والعمود الثاني. |
| [getM31()](#getM31--) | يحصل على عنصر المصفوفة في الصف الثالث والعمود الأول. |
| [getM32()](#getM32--) | يحصل على عنصر المصفوفة في الصف الثالث والعمود الأول. |
| [hashCode()](#hashCode--) | يرجع رمز تجزئة لهذا الكائن. |
| [isEquals(Matrix a, Matrix b)](#isEquals-com.aspose.psd.Matrix-com.aspose.psd.Matrix-) | يحدد ما إذا كان المصفوفتان متساويتان. |
| [isIdentity()](#isIdentity--) | يعيد `true` إذا كان هذا `AffineTransform` تحويل هوية. |
| [multiply(Matrix Tx)](#multiply-com.aspose.psd.Matrix-) | يضرب هذه المصفوفة بالمصفوفة المحددة في معامل المصفوفة باستخدام ترتيب (Prepend) الافتراضي. |
| [multiply(Matrix Tx, int order)](#multiply-com.aspose.psd.Matrix-int-) | يضرب هذه المصفوفة بالمصفوفة المحددة في معامل المصفوفة، وبالترتيب المحدد في معامل order. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [reset()](#reset--) | يعيد ضبط هذه المصفوفة لتحتوي على عناصر مصفوفة الهوية. |
| [rotate(float angle)](#rotate-float-) | يطبق دورانًا باتجاه عقارب الساعة بمقدار محدد في معامل الزاوية، حول الأصل (إحداثيات x و y صفر) لهذه المصفوفة بالترتيب الافتراضي (Prepend). |
| [rotate(float angle, int order)](#rotate-float-int-) | يطبق دورانًا باتجاه عقارب الساعة بمقدار محدد في معامل الزاوية، حول الأصل (إحداثيات x و y صفر) لهذه المصفوفة بالترتيب المحدد. |
| [rotateAt(float angle, PointF point)](#rotateAt-float-com.aspose.psd.PointF-) | يطبق دورانًا باتجاه عقارب الساعة حول النقطة المحددة على هذه المصفوفة بالترتيب الافتراضي (Prepend). |
| [rotateAt(float angle, PointF point, int order)](#rotateAt-float-com.aspose.psd.PointF-int-) | يطبق دورانًا باتجاه عقارب الساعة حول النقطة المحددة على هذه المصفوفة بالترتيب المحدد. |
| [scale(float sx, float sy)](#scale-float-float-) | يطبق متجه المقياس المحدد (scaleX و scaleY) على هذه المصفوفة باستخدام ترتيب (Prepend) الافتراضي. |
| [scale(float scaleX, float scaleY, int order)](#scale-float-float-int-) | يطبق متجه المقياس المحدد (scaleX و scaleY) على هذه المصفوفة باستخدام الترتيب المحدد. |
| [toString()](#toString--) | يرجع  System.String  الذي يمثل هذه الحالة. |
| [transformPoints(PointF[] points)](#transformPoints-com.aspose.psd.PointF---) | يطبق التحويل الهندسي الممثل بهذه المصفوفة على مصفوفة محددة من النقاط. |
| [translate(float tx, float ty)](#translate-float-float-) | يطبق متجه الإزاحة المحدد على هذه المصفوفة باستخدام ترتيب (Prepend) الافتراضي. |
| [translate(float offsetX, float offsetY, int order)](#translate-float-float-int-) | يطبق متجه الإزاحة المحدد على هذه المصفوفة بالترتيب المحدد. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Matrix() {#Matrix--}
```
public Matrix()
```


ينشئ نسخة جديدة من فئة Matrix كمصفوفة هوية.

### Matrix(float m11, float m12, float m21, float m22, float m31, float m32) {#Matrix-float-float-float-float-float-float-}
```
public Matrix(float m11, float m12, float m21, float m22, float m31, float m32)
```


ينشئ نسخة جديدة من فئة Matrix.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| m11 | float | m00 M11 مقياس X |
| m12 | float | m10 M12 قص Y |
| m21 | float | m01 M21 قص X |
| m22 | float | m11 M22 مقياس Y |
| m31 | float | m02 M31 ترجمة X |
| m32 | float | m12 M32 ترجمة Y |

### Matrix(Matrix origin) {#Matrix-com.aspose.psd.Matrix-}
```
public Matrix(Matrix origin)
```


ينشئ نسخة من فئة Matrix.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| origin | [Matrix](../../com.aspose.psd/matrix) | المصفوفة الأساسية للمعالجة |

### Matrix(RectangleF rect, PointF[] plgpts) {#Matrix-com.aspose.psd.RectangleF-com.aspose.psd.PointF---}
```
public Matrix(RectangleF rect, PointF[] plgpts)
```


ينشئ نسخة جديدة من فئة Aspose.Imaging.Matrix للتحويل الهندسي المحدد بالمستطيل المحدد ومصفوفة النقاط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | ‏‏ بنية Aspose.Imaging.RectangleF تمثل المستطيل الذي سيتم تحويله. |
| plgpts | [PointF\[\]](../../com.aspose.psd/pointf) | ‏‏ مصفوفة من ثلاث بنى Aspose.Imaging.PointF تمثل نقاط متوازي أضلاع يتم تحويل الزوايا العلوية اليسرى والعليا اليمنى والسفلية اليسرى للمستطيل إليه. الزاوية السفلية اليمنى للمتوازي أضلاع مستنتجة من الثلاث زوايا الأولى. |

### Matrix(Rectangle rect, Point[] plgpts) {#Matrix-com.aspose.psd.Rectangle-com.aspose.psd.Point---}
```
public Matrix(Rectangle rect, Point[] plgpts)
```


ينشئ نسخة جديدة من فئة Aspose.Imaging.Matrix للتحويل الهندسي المحدد بالمستطيل المحدد ومصفوفة النقاط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | ‏‏ بنية Aspose.Imaging.Rectangle تمثل المستطيل الذي سيتم تحويله. |
| plgpts | [Point\[\]](../../com.aspose.psd/point) | ‏‏ مصفوفة من ثلاث بنى Aspose.Imaging.Point تمثل نقاط متوازي أضلاع يتم تحويل الزوايا العلوية اليسرى والعليا اليمنى والسفلية اليسرى للمستطيل إليه. الزاوية السفلية اليمنى للمتوازي أضلاع مستنتجة من الثلاث زوايا الأولى. |

### TYPE_FLIP {#TYPE-FLIP}
```
public static final int TYPE_FLIP
```


تشير هذه البتة flag إلى أن التحويل المحدد بواسطة هذا الكائن يقوم بعكس صورة مرآة حول محور ما مما يغيّر نظام الإحداثيات اليدوي الأيمن إلى نظام يدوي أيسر بالإضافة إلى التحويلات المشار إليها بواسطة بتات flag الأخرى. نظام الإحداثيات اليدوي الأيمن هو النظام الذي يدور فيه المحور X الموجب عكس اتجاه عقارب الساعة ليصطف مع المحور Y الموجب، مشابه لاتجاه انحناء أصابع يدك اليمنى عندما تنظر إلى إبهامك من الطرف. نظام الإحداثيات اليدوي الأيسر هو النظام الذي يدور فيه المحور X الموجب مع اتجاه عقارب الساعة ليصطف مع المحور Y الموجب، مشابه لاتجاه انحناء أصابع يدك اليسرى. لا توجد طريقة رياضية لتحديد زاوية التحويل الأصلي للانعكاس أو المرآة لأن جميع زوايا الانعكاس متطابقة عند إضافة دوران مناسب. ملاحظة: تم إضافة TypeFlip بعد أن أصبح GENERAL\_TRANSFORM متاحاً للجمهور ولم يعد من الممكن إعادة ترقيم بتات flag دون إحداث عدم توافق ثنائي في الشيفرة الخارجية.

### TYPE_GENERAL_ROTATION {#TYPE-GENERAL-ROTATION}
```
public static final int TYPE_GENERAL_ROTATION
```


تشير هذه البتة flag إلى أن التحويل المحدد بواسطة هذا الكائن يقوم بدوران بزاوية عشوائية بالإضافة إلى التحويلات المشار إليها بواسطة بتات flag الأخرى. يغير الدوران زوايا المتجهات بنفس المقدار بغض النظر عن الاتجاه الأصلي للمتجه وبدون تغيير طول المتجه. هذه البتة flag لا يمكن أن تتواجد مع الـ

### TYPE_GENERAL_SCALE {#TYPE-GENERAL-SCALE}
```
public static final int TYPE_GENERAL_SCALE
```


يقوم مقياس عام بضرب طول المتجهات بمقادير مختلفة في اتجاهي x و y دون تغيير الزاوية بين المتجهات المتعامدة. هذه البتة flag لا يمكن أن تتواجد مع بتة TypeUniformScale flag.

### TYPE_GENERAL_TRANSFORM {#TYPE-GENERAL-TRANSFORM}
```
public static final int TYPE_GENERAL_TRANSFORM
```


تشير هذه الثابتة إلى أن التحويل المحدد بواسطة هذا الكائن يقوم بتحويل عشوائي لإحداثيات الإدخال. إذا كان يمكن تصنيف هذا التحويل بأحد الثوابت المذكورة أعلاه، فسيكون النوع إما الثابت TypeIdentity أو مزيجاً من بتات flag المناسبة للتحويلات المختلفة للإحداثيات التي يقوم بها هذا التحويل.

### TYPE_IDENTITY {#TYPE-IDENTITY}
```
public static final int TYPE_IDENTITY
```


التحويل الهوية هو التحويل الذي تكون فيه إحداثيات الخرج دائمًا هي نفسها إحداثيات الإدخال. إذا كان هذا التحويل غير هوية، فسيكون النوع إما الثابت GENERAL\_TRANSFORM أو مزيجاً من بتات flag المناسبة للتحويلات المختلفة للإحداثيات التي يقوم بها هذا التحويل.

### TYPE_MASK_ROTATION {#TYPE-MASK-ROTATION}
```
public static final int TYPE_MASK_ROTATION
```


هذه الثابتة هي قناع بت لأي من بتات flag الخاصة بالدوران.

### TYPE_MASK_SCALE {#TYPE-MASK-SCALE}
```
public static final int TYPE_MASK_SCALE
```


هذه الثابتة هي قناع بت لأي من بتات flag الخاصة بالمقياس.

### TYPE_QUADRANT_ROTATION {#TYPE-QUADRANT-ROTATION}
```
public static final int TYPE_QUADRANT_ROTATION
```


تشير هذه البتة flag إلى أن التحويل المحدد بواسطة هذا الكائن يقوم بدوران ربعي بضعف من 90 درجة بالإضافة إلى التحويلات المشار إليها بواسطة بتات flag الأخرى. يغير الدوران زوايا المتجهات بنفس المقدار بغض النظر عن الاتجاه الأصلي للمتجه وبدون تغيير طول المتجه. هذه البتة flag لا يمكن أن تتواجد مع بتة TypeGeneralRotation flag.

### TYPE_TRANSLATION {#TYPE-TRANSLATION}
```
public static final int TYPE_TRANSLATION
```


الترجمة تنقل الإحداثيات بمقدار ثابت في x و y دون تغيير طول أو زاوية المتجهات.

### TYPE_UNIFORM_SCALE {#TYPE-UNIFORM-SCALE}
```
public static final int TYPE_UNIFORM_SCALE
```


المقياس المتساوي يضاعف طول المتجهات بنفس المقدار في كل من اتجاهي x و y دون تغيير الزاوية بين المتجهات. هذه البتة flag لا يمكن أن تتواجد مع بتة TypeGeneralScale flag.

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يحدد ما إذا كان الكائن System.Object المحدد يساوي هذه الحالة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | الكائن System.Object للمقارنة مع هذا الكائن. |

**Returns:**
منطقية - true إذا كان الكائن System.Object المحدد مساويًا لهذا الكائن؛ وإلا false.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getElements() {#getElements--}
```
public float[] getElements()
```


يحصل على نسخة من عناصر المصفوفة.

**Returns:**
float[] - نسخة من عناصر المصفوفة.
### getM11() {#getM11--}
```
public float getM11()
```


يحصل على عنصر المصفوفة في الصف الأول العمود الأول. يمثل مقياسًا على المحور X.

**Returns:**
float
### getM12() {#getM12--}
```
public float getM12()
```


يحصل على عنصر المصفوفة في الصف الأول العمود الثاني. يمثل قصًا على المحور Y.

**Returns:**
float
### getM21() {#getM21--}
```
public float getM21()
```


يحصل على عنصر المصفوفة في الصف الثاني العمود الأول. يمثل القص على المحور X.

**Returns:**
float
### getM22() {#getM22--}
```
public float getM22()
```


يحصل على عنصر المصفوفة في الصف الثاني العمود الثاني. يمثل التحجيم على المحور Y.

**Returns:**
float
### getM31() {#getM31--}
```
public float getM31()
```


يحصل على عنصر المصفوفة في الصف الثالث العمود الأول. يمثل الإزاحة على المحور X.

**Returns:**
float
### getM32() {#getM32--}
```
public float getM32()
```


يحصل على عنصر المصفوفة في الصف الثالث العمود الأول. يمثل الإزاحة على المحور Y.

**Returns:**
float
### hashCode() {#hashCode--}
```
public int hashCode()
```


يرجع رمز تجزئة لهذا الكائن.

**Returns:**
int - رمز تجزئة لهذا الكائن، مناسب للاستخدام في خوارزميات التجزئة وهياكل البيانات مثل جدول التجزئة.
### isEquals(Matrix a, Matrix b) {#isEquals-com.aspose.psd.Matrix-com.aspose.psd.Matrix-}
```
public static boolean isEquals(Matrix a, Matrix b)
```


يحدد ما إذا كان المصفوفتان متساويتان.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| a | [Matrix](../../com.aspose.psd/matrix) | المصفوفة الأولى للمقارنة. |
| b | [Matrix](../../com.aspose.psd/matrix) | المصفوفة الثانية للمقارنة. |

**Returns:**
منطقي - صحيح إذا كانت المصفوفات متساوية.
### isIdentity() {#isIdentity--}
```
public boolean isIdentity()
```


يعيد `true` إذا كان هذا `AffineTransform` تحويل هوية.

**Returns:**
منطقي - `true` إذا كان هذا `AffineTransform` تحويل هوية؛ `false` خلاف ذلك.
### multiply(Matrix Tx) {#multiply-com.aspose.psd.Matrix-}
```
public void multiply(Matrix Tx)
```


يضرب هذه المصفوفة بالمصفوفة المحددة في معامل المصفوفة باستخدام ترتيب (Prepend) الافتراضي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| Tx | [Matrix](../../com.aspose.psd/matrix) | المصفوفة التي سيتم الضرب معها. |

### multiply(Matrix Tx, int order) {#multiply-com.aspose.psd.Matrix-int-}
```
public void multiply(Matrix Tx, int order)
```


يضرب هذه المصفوفة بالمصفوفة المحددة في معامل المصفوفة، وبالترتيب المحدد في معامل order.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| Tx | [Matrix](../../com.aspose.psd/matrix) | الـ tx. الـ tx. الـ tx. |
| الترتيب | int | الترتيب. الترتيب. الترتيب. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### reset() {#reset--}
```
public void reset()
```


يعيد ضبط هذه المصفوفة لتحتوي على عناصر مصفوفة الهوية.

### rotate(float angle) {#rotate-float-}
```
public void rotate(float angle)
```


يطبق دورانًا باتجاه عقارب الساعة بمقدار محدد في معامل الزاوية، حول الأصل (إحداثيات x و y صفر) لهذه المصفوفة بالترتيب الافتراضي (Prepend).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| زاوية | float | زاوية الدوران. |

### rotate(float angle, int order) {#rotate-float-int-}
```
public void rotate(float angle, int order)
```


يطبق دورانًا باتجاه عقارب الساعة بمقدار محدد في معامل الزاوية، حول الأصل (إحداثيات x و y صفر) لهذه المصفوفة بالترتيب المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| زاوية | float | زاوية الدوران. |
| الترتيب | int | ترتيب المصفوفة. |

### rotateAt(float angle, PointF point) {#rotateAt-float-com.aspose.psd.PointF-}
```
public void rotateAt(float angle, PointF point)
```


يطبق دورانًا باتجاه عقارب الساعة حول النقطة المحددة على هذه المصفوفة بالترتيب الافتراضي (Prepend).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| زاوية | float | الزاوية. |
| point | [PointF](../../com.aspose.psd/pointf) | النقطة. |

### rotateAt(float angle, PointF point, int order) {#rotateAt-float-com.aspose.psd.PointF-int-}
```
public void rotateAt(float angle, PointF point, int order)
```


يطبق دورانًا باتجاه عقارب الساعة حول النقطة المحددة على هذه المصفوفة بالترتيب المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| زاوية | float | الزاوية. |
| point | [PointF](../../com.aspose.psd/pointf) | النقطة. |
| الترتيب | int | الترتيب. |

### scale(float sx, float sy) {#scale-float-float-}
```
public void scale(float sx, float sy)
```


يطبق متجه المقياس المحدد (scaleX و scaleY) على هذه المصفوفة باستخدام ترتيب (Prepend) الافتراضي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| sx | float | الـ sx. الـ sx. الـ sx. |
| sy | float | الـ sy. الـ sy. الـ sy. |

### scale(float scaleX, float scaleY, int order) {#scale-float-float-int-}
```
public void scale(float scaleX, float scaleY, int order)
```


يطبق متجه المقياس المحدد (scaleX و scaleY) على هذه المصفوفة باستخدام الترتيب المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| scaleX | float | المقياس X. |
| scaleY | float | المقياس Y. |
| الترتيب | int | الترتيب. |

### toString() {#toString--}
```
public String toString()
```


يرجع  System.String  الذي يمثل هذه الحالة.

**Returns:**
java.lang.String - سلسلة System.String تمثل هذه الحالة.
### transformPoints(PointF[] points) {#transformPoints-com.aspose.psd.PointF---}
```
public void transformPoints(PointF[] points)
```


يطبق التحويل الهندسي الممثل بهذه المصفوفة على مصفوفة محددة من النقاط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | النقاط. |

### translate(float tx, float ty) {#translate-float-float-}
```
public void translate(float tx, float ty)
```


يطبق متجه الإزاحة المحدد على هذه المصفوفة باستخدام ترتيب (Prepend) الافتراضي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| tx | float | الـ tx. الـ tx. الـ tx. |
| ty | float | الـ ty. الـ ty. الـ ty. |

### translate(float offsetX, float offsetY, int order) {#translate-float-float-int-}
```
public void translate(float offsetX, float offsetY, int order)
```


يطبق متجه الإزاحة المحدد على هذه المصفوفة بالترتيب المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| offsetX | float | الإزاحة X. |
| offsetY | float | الإزاحة Y. |
| الترتيب | int | الترتيب. |

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

