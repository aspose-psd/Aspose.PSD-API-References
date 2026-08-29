---
title: "LinearGradientBrush"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "يحتوي على Aspose.Imaging.Brush مع تدرج خطي."
type: docs
weight: 11
url: /ar/java/com.aspose.psd.brushes/lineargradientbrush/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.Brush](../../com.aspose.psd/brush), [com.aspose.psd.brushes.TransformBrush](../../com.aspose.psd.brushes/transformbrush), [com.aspose.psd.brushes.LinearGradientBrushBase](../../com.aspose.psd.brushes/lineargradientbrushbase)
```
public final class LinearGradientBrush extends LinearGradientBrushBase
```

يحتوي على Aspose.Imaging.Brush مع تدرج خطي. لا يمكن توريث هذه الفئة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [LinearGradientBrush()](#LinearGradientBrush--) | ينشئ مثيلاً جديداً من فئة LinearGradientBrush بالمعلمات الافتراضية. |
| [LinearGradientBrush(Point point1, Point point2, Color color1, Color color2)](#LinearGradientBrush-com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.Color-com.aspose.psd.Color-) | ينشئ مثيلاً جديداً من فئة LinearGradientBrush بالنقاط والألوان المحددة. |
| [LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2)](#LinearGradientBrush-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.Color-com.aspose.psd.Color-) | ينشئ مثيلاً جديداً من فئة LinearGradientBrush بالنقاط والألوان المحددة. |
| [LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle)](#LinearGradientBrush-com.aspose.psd.Rectangle-com.aspose.psd.Color-com.aspose.psd.Color-float-) | ينشئ مثيلاً جديداً من فئة LinearGradientBrush استناداً إلى مستطيل، والألوان الابتدائية والنهائية، وزاوية الاتجاه. |
| [LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle)](#LinearGradientBrush-com.aspose.psd.RectangleF-com.aspose.psd.Color-com.aspose.psd.Color-float-) | ينشئ مثيلاً جديداً من فئة LinearGradientBrush استناداً إلى مستطيل، والألوان الابتدائية والنهائية، وزاوية الاتجاه. |
| [LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScalable)](#LinearGradientBrush-com.aspose.psd.Rectangle-com.aspose.psd.Color-com.aspose.psd.Color-float-boolean-) | ينشئ مثيلاً جديداً من فئة LinearGradientBrush استناداً إلى مستطيل، والألوان الابتدائية والنهائية، وزاوية الاتجاه. |
| [LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScalable)](#LinearGradientBrush-com.aspose.psd.RectangleF-com.aspose.psd.Color-com.aspose.psd.Color-float-boolean-) | ينشئ مثيلاً جديداً من فئة LinearGradientBrush استناداً إلى مستطيل، والألوان الابتدائية والنهائية، وزاوية الاتجاه. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [close()](#close--) | تنفذ واجهة Closable ويمكن استخدامها في عبارة try-with-resources منذ JDK 1.7. |
| [deepClone()](#deepClone--) | ينشئ نسخة عميقة جديدة من الـ Brush الحالي. |
| [dispose()](#dispose--) | يحرر النسخة الحالية. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAngle()](#getAngle--) | يحصل على زاوية التدرج. |
| [getBlend()](#getBlend--) | يحصل على Aspose.Imaging.Blend الذي يحدد المواقع والعوامل التي تعرف انخفاضاً مخصصاً للتدرج. |
| [getClass()](#getClass--) |  |
| [getDisposed()](#getDisposed--) | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن قد تم التخلص منه. |
| [getEndColor()](#getEndColor--) | يحصل على لون التدرج النهائي. |
| [getGammaCorrection()](#getGammaCorrection--) | يحصل على قيمة تشير إلى ما إذا كان تصحيح غاما مفعلاً لهذا  LinearGradientBrushBase . |
| [getInterpolationColors()](#getInterpolationColors--) | يحصل على  com.aspose.psd.ColorBlend  الذي يحدد تدرجاً خطياً متعدد الألوان. |
| [getLinearColors()](#getLinearColors--) | يحصل على الألوان الابتدائية والنهائية للتدرج. |
| [getOpacity()](#getOpacity--) | يحصل على شفافية الفرشاة. |
| [getRectangle()](#getRectangle--) | يحصل على منطقة مستطيلة تحدد نقطتي البداية والنهاية للتدرج. |
| [getStartColor()](#getStartColor--) | يحصل على لون التدرج الابتدائي. |
| [getTransform()](#getTransform--) | يحصل أو يضبط نسخة Aspose.Imaging.Matrix التي تحدد تحويلًا هندسيًا محليًا لهذا TransformBrush. |
| [getWrapMode()](#getWrapMode--) | يحصل أو يضبط تعداد Aspose.Imaging.WrapMode الذي يشير إلى وضع الالتفاف لهذا TransformBrush. |
| [hashCode()](#hashCode--) |  |
| [isAngleScalable()](#isAngleScalable--) | يحصل على قيمة تشير إلى ما إذا كان LinearGradientBrushBase.Angle يتغير أثناء التحولات باستخدام هذا LinearGradientBrushBase. |
| [isTransformChanged()](#isTransformChanged--) | يحصل على قيمة تشير إلى ما إذا تم تغيير التحولات بطريقة ما. |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.psd.Matrix-) | يضرب Aspose.Imaging.Matrix الذي يمثل التحويل الهندسي المحلي لهذا LinearGradientBrush بالمصفوفة المحددة Aspose.Imaging.Matrix عن طريق إلحاق المصفوفة المحددة Aspose.Imaging.Matrix في البداية. |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.psd.Matrix-int-) | يضرب Aspose.Imaging.Matrix الذي يمثل التحويل الهندسي المحلي لهذا LinearGradientBrush بالمصفوفة المحددة Aspose.Imaging.Matrix وفق الترتيب المحدد. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [resetTransform()](#resetTransform--) | يعيد تعيين الخاصية TransformBrush.Transform إلى هوية. |
| [rotateTransform(float angle)](#rotateTransform-float-) | يدور التحويل الهندسي المحلي بالمقدار المحدد. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | يدور التحويل الهندسي المحلي بالمقدار المحدد وفق الترتيب المحدد. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | يقوم بتحجيم التحويل الهندسي المحلي بالمقاسات المحددة. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | يقوم بتحجيم التحويل الهندسي المحلي بالمقاسات المحددة وفق الترتيب المحدد. |
| [setAngle(float value)](#setAngle-float-) | يضبط زاوية التدرج. |
| [setAngleScalable(boolean value)](#setAngleScalable-boolean-) | يضبط قيمة تشير إلى ما إذا كان LinearGradientBrushBase.Angle يتغير أثناء التحولات باستخدام هذا LinearGradientBrushBase. |
| [setBlend(Blend value)](#setBlend-com.aspose.psd.Blend-) | يضبط Aspose.Imaging.Blend الذي يحدد المواقع والعوامل التي تعرف انخفاضاً مخصصاً للتدرج. |
| [setBlendTriangularShape(float focus)](#setBlendTriangularShape-float-) | ينشئ تدرجاً خطياً بلون مركزي وانخفاضاً خطياً إلى لون واحد في الطرفين. |
| [setBlendTriangularShape(float focus, float scale)](#setBlendTriangularShape-float-float-) | ينشئ تدرجاً خطياً بلون مركزي وانخفاضاً خطياً إلى لون واحد في الطرفين. |
| [setEndColor(Color value)](#setEndColor-com.aspose.psd.Color-) | يضبط لون التدرج النهائي. |
| [setGammaCorrection(boolean value)](#setGammaCorrection-boolean-) | يضبط قيمة تشير إلى ما إذا كان تصحيح غاما مفعلاً لهذا LinearGradientBrushBase. |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.psd.ColorBlend-) | يضبط com.aspose.psd.ColorBlend الذي يحدد تدرجًا خطيًا متعدد الألوان. |
| [setLinearColors(Color[] value)](#setLinearColors-com.aspose.psd.Color---) | يضبط الألوان الابتدائية والنهائية للتدرج. |
| [setOpacity(float value)](#setOpacity-float-) | يضبط شفافية الفرشاة. |
| [setRectangle(RectangleF value)](#setRectangle-com.aspose.psd.RectangleF-) | يضبط منطقة مستطيلة تحدد نقطتي البداية والنهاية للتدرج. |
| [setSigmaBellShape(float focus)](#setSigmaBellShape-float-) | ينشئ انخفاضاً للتدرج بناءً على منحنى على شكل جرس. |
| [setSigmaBellShape(float focus, float scale)](#setSigmaBellShape-float-float-) | ينشئ انخفاضاً للتدرج بناءً على منحنى على شكل جرس. |
| [setStartColor(Color value)](#setStartColor-com.aspose.psd.Color-) | يضبط لون التدرج الابتدائي. |
| [setTransform(Matrix value)](#setTransform-com.aspose.psd.Matrix-) | يحصل أو يضبط نسخة Aspose.Imaging.Matrix التي تحدد تحويلًا هندسيًا محليًا لهذا TransformBrush. |
| [setWrapMode(int value)](#setWrapMode-int-) | يحصل أو يضبط تعداد Aspose.Imaging.WrapMode الذي يشير إلى وضع الالتفاف لهذا TransformBrush. |
| [toString()](#toString--) |  |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | ينقل التحويل الهندسي المحلي بالأبعاد المحددة. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | ينقل التحويل الهندسي المحلي بالأبعاد المحددة وفق الترتيب المحدد. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LinearGradientBrush() {#LinearGradientBrush--}
```
public LinearGradientBrush()
```


ينشئ مثيلاً جديداً من فئة LinearGradientBrush بالمعلمات الافتراضية. اللون الابتدائي هو الأسود، واللون النهائي هو الأبيض، والزاوية 45 درجة، والمستطيل يقع في (0,0) بحجم (1,1).

### LinearGradientBrush(Point point1, Point point2, Color color1, Color color2) {#LinearGradientBrush-com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.Color-com.aspose.psd.Color-}
```
public LinearGradientBrush(Point point1, Point point2, Color color1, Color color2)
```


ينشئ مثيلاً جديداً من فئة LinearGradientBrush بالنقاط والألوان المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.psd/point) | هيكل Aspose.Imaging.Point الذي يمثل نقطة البداية للتدرج الخطي. |
| point2 | [Point](../../com.aspose.psd/point) | هيكل Aspose.Imaging.Point الذي يمثل نقطة النهاية للتدرج الخطي. |
| color1 | [Color](../../com.aspose.psd/color) | هيكل com.aspose.psd.Color يمثل اللون الابتدائي للتدرج الخطي. |
| color2 | [Color](../../com.aspose.psd/color) | هيكل com.aspose.psd.Color يمثل اللون النهائي للتدرج الخطي. |

### LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2) {#LinearGradientBrush-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.Color-com.aspose.psd.Color-}
```
public LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2)
```


ينشئ مثيلاً جديداً من فئة LinearGradientBrush بالنقاط والألوان المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.psd/pointf) | هيكل Aspose.Imaging.PointF الذي يمثل نقطة البداية للتدرج الخطي. |
| point2 | [PointF](../../com.aspose.psd/pointf) | هيكل  Aspose.Imaging.PointF  يمثل نقطة النهاية للتدرج الخطي. |
| color1 | [Color](../../com.aspose.psd/color) | هيكل com.aspose.psd.Color يمثل اللون الابتدائي للتدرج الخطي. |
| color2 | [Color](../../com.aspose.psd/color) | هيكل com.aspose.psd.Color يمثل اللون النهائي للتدرج الخطي. |

### LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle) {#LinearGradientBrush-com.aspose.psd.Rectangle-com.aspose.psd.Color-com.aspose.psd.Color-float-}
```
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle)
```


ينشئ مثيلاً جديداً من فئة LinearGradientBrush استناداً إلى مستطيل، والألوان الابتدائية والنهائية، وزاوية الاتجاه.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | هيكل  Aspose.Imaging.RectangleF  يحدد حدود التدرج الخطي. |
| color1 | [Color](../../com.aspose.psd/color) | هيكل com.aspose.psd.Color يمثل اللون الابتدائي للتدرج. |
| color2 | [Color](../../com.aspose.psd/color) | هيكل com.aspose.psd.Color يمثل اللون النهائي للتدرج. |
| زاوية | float | الزاوية، مقاسة بالدرجات في اتجاه عقارب الساعة من محور x، لخط توجيه التدرج. |

### LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle) {#LinearGradientBrush-com.aspose.psd.RectangleF-com.aspose.psd.Color-com.aspose.psd.Color-float-}
```
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle)
```


ينشئ مثيلاً جديداً من فئة LinearGradientBrush استناداً إلى مستطيل، والألوان الابتدائية والنهائية، وزاوية الاتجاه.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | هيكل  Aspose.Imaging.RectangleF  يحدد حدود التدرج الخطي. |
| color1 | [Color](../../com.aspose.psd/color) | هيكل com.aspose.psd.Color يمثل اللون الابتدائي للتدرج. |
| color2 | [Color](../../com.aspose.psd/color) | هيكل com.aspose.psd.Color يمثل اللون النهائي للتدرج. |
| زاوية | float | الزاوية، مقاسة بالدرجات في اتجاه عقارب الساعة من محور x، لخط توجيه التدرج. |

### LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScalable) {#LinearGradientBrush-com.aspose.psd.Rectangle-com.aspose.psd.Color-com.aspose.psd.Color-float-boolean-}
```
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScalable)
```


ينشئ مثيلاً جديداً من فئة LinearGradientBrush استناداً إلى مستطيل، والألوان الابتدائية والنهائية، وزاوية الاتجاه.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | هيكل  Aspose.Imaging.RectangleF  يحدد حدود التدرج الخطي. |
| color1 | [Color](../../com.aspose.psd/color) | هيكل com.aspose.psd.Color يمثل اللون الابتدائي للتدرج. |
| color2 | [Color](../../com.aspose.psd/color) | هيكل com.aspose.psd.Color يمثل اللون النهائي للتدرج. |
| زاوية | float | الزاوية، مقاسة بالدرجات في اتجاه عقارب الساعة من محور x، لخط توجيه التدرج. |
| isAngleScalable | boolean | إذا تم تعيينه إلى true، يتم تغيير الزاوية أثناء التحويلات باستخدام LinearGradientBrush. |

### LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScalable) {#LinearGradientBrush-com.aspose.psd.RectangleF-com.aspose.psd.Color-com.aspose.psd.Color-float-boolean-}
```
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScalable)
```


ينشئ مثيلاً جديداً من فئة LinearGradientBrush استناداً إلى مستطيل، والألوان الابتدائية والنهائية، وزاوية الاتجاه.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | هيكل  Aspose.Imaging.RectangleF  يحدد حدود التدرج الخطي. |
| color1 | [Color](../../com.aspose.psd/color) | هيكل com.aspose.psd.Color يمثل اللون الابتدائي للتدرج. |
| color2 | [Color](../../com.aspose.psd/color) | هيكل com.aspose.psd.Color يمثل اللون النهائي للتدرج. |
| زاوية | float | الزاوية، مقاسة بالدرجات في اتجاه عقارب الساعة من محور x، لخط توجيه التدرج. |
| isAngleScalable | boolean | إذا تم تعيينه إلى true، يتم تغيير الزاوية أثناء التحويلات باستخدام LinearGradientBrush. |

### close() {#close--}
```
public void close()
```


تنفيذ واجهة Closable ويمكن استخدامها في بيان try-with-resources منذ JDK 1.7. هذه الطريقة تستدعي ببساطة طريقة dispose.

### deepClone() {#deepClone--}
```
public Brush deepClone()
```


ينشئ نسخة عميقة جديدة من الـ Brush الحالي.

**Returns:**
[Brush](../../com.aspose.psd/brush) - A new  Brush  which is the deep clone of this  Brush  instance.
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
### getAngle() {#getAngle--}
```
public float getAngle()
```


يحصل على زاوية التدرج.

**Returns:**
float - زاوية التدرج.
### getBlend() {#getBlend--}
```
public Blend getBlend()
```


يحصل على Aspose.Imaging.Blend الذي يحدد المواقع والعوامل التي تعرف انخفاضاً مخصصاً للتدرج.

**Returns:**
[Blend](../../com.aspose.psd/blend) - A  Aspose.Imaging.Blend  that represents a custom falloff for the gradient.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


يحصل على قيمة تشير إلى ما إذا كان هذا الكائن قد تم التخلص منه.

**Returns:**
boolean -  true  إذا تم التخلص؛ وإلا،  false .
### getEndColor() {#getEndColor--}
```
public Color getEndColor()
```


يحصل على لون التدرج النهائي.

**Returns:**
[Color](../../com.aspose.psd/color) - The ending gradient color.
### getGammaCorrection() {#getGammaCorrection--}
```
public boolean getGammaCorrection()
```


يحصل على قيمة تشير إلى ما إذا كان تصحيح غاما مفعلاً لهذا  LinearGradientBrushBase .

**Returns:**
boolean - القيمة تكون true إذا تم تمكين تصحيح غاما لهذا  LinearGradientBrushBase ؛ وإلا false.
### getInterpolationColors() {#getInterpolationColors--}
```
public ColorBlend getInterpolationColors()
```


يحصل على  com.aspose.psd.ColorBlend  الذي يحدد تدرجاً خطياً متعدد الألوان.

**Returns:**
[ColorBlend](../../com.aspose.psd/colorblend) - A  com.aspose.psd.ColorBlend  that defines a multicolor linear gradient.
### getLinearColors() {#getLinearColors--}
```
public Color[] getLinearColors()
```


يحصل على الألوان الابتدائية والنهائية للتدرج.

**Returns:**
com.aspose.psd.Color[] - مصفوفة من هيكلين من نوع Color تمثل الألوان الابتدائية والنهائية للتدرج.
### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


يحصل على شفافية الفرشاة. يجب أن تكون القيمة بين 0 و 1. القيمة 0 تعني أن الفرشاة مرئية بالكامل، والقيمة 1 تعني أن الفرشاة غير شفافة تمامًا.

**Returns:**
float - قيمة شفافية الفرشاة.
### getRectangle() {#getRectangle--}
```
public RectangleF getRectangle()
```


يحصل على منطقة مستطيلة تحدد نقطتي البداية والنهاية للتدرج.

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - A  com.aspose.psd.RectangleF  structure that specifies the starting and ending points of the gradient.
### getStartColor() {#getStartColor--}
```
public Color getStartColor()
```


يحصل على لون التدرج الابتدائي.

**Returns:**
[Color](../../com.aspose.psd/color) - The starting gradient color.
### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


يحصل أو يضبط نسخة Aspose.Imaging.Matrix التي تحدد تحويلًا هندسيًا محليًا لهذا TransformBrush.

**Returns:**
[Matrix](../../com.aspose.psd/matrix) - A copy of the  Aspose.Imaging.Matrix  that defines a geometric transform that applies only to fills drawn with this  TransformBrush .
### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


يحصل أو يضبط تعداد Aspose.Imaging.WrapMode الذي يشير إلى وضع الالتفاف لهذا TransformBrush.

**Returns:**
int -  Aspose.Imaging.WrapMode  يحدد كيفية تكرار التعبئات المرسومة باستخدام  TransformBrush .
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isAngleScalable() {#isAngleScalable--}
```
public boolean isAngleScalable()
```


يحصل على قيمة تشير إلى ما إذا كان LinearGradientBrushBase.Angle يتغير أثناء التحولات باستخدام هذا LinearGradientBrushBase.

**Returns:**
boolean -  true  إذا تم تغيير  LinearGradientBrushBase.Angle  أثناء التحويلات باستخدام هذا  LinearGradientBrushBase ؛ وإلا false.
### isTransformChanged() {#isTransformChanged--}
```
public boolean isTransformChanged()
```


يحصل على قيمة تشير إلى ما إذا تم تغيير التحويلات بطريقة ما. على سبيل المثال ضبط مصفوفة التحويل أو استدعاء أي من الطرق التي تغير مصفوفة التحويل. تم تقديم الخاصية لتوافقية خلفية مع GDI+.

القيمة:  True  إذا تم تغيير التحويل؛ وإلا false.

**Returns:**
boolean
### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.psd.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


يضرب Aspose.Imaging.Matrix الذي يمثل التحويل الهندسي المحلي لهذا LinearGradientBrush بالمصفوفة المحددة Aspose.Imaging.Matrix عن طريق إلحاق المصفوفة المحددة Aspose.Imaging.Matrix في البداية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | المصفوفة  Aspose.Imaging.Matrix  التي يتم ضرب التحويل الهندسي بها. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.psd.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


يضرب Aspose.Imaging.Matrix الذي يمثل التحويل الهندسي المحلي لهذا LinearGradientBrush بالمصفوفة المحددة Aspose.Imaging.Matrix وفق الترتيب المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | المصفوفة  Aspose.Imaging.Matrix  التي يتم ضرب التحويل الهندسي بها. |
| الترتيب | int |   Aspose.Imaging.MatrixOrder  يحدد الترتيب الذي يتم به ضرب المصفوفتين. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### resetTransform() {#resetTransform--}
```
public void resetTransform()
```


يعيد تعيين الخاصية TransformBrush.Transform إلى هوية.

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


يدور التحويل الهندسي المحلي بالمقدار المحدد. هذه الطريقة تسبق الدوران إلى التحويل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| زاوية | float | زاوية الدوران. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


يدور التحويل الهندسي المحلي بالمقدار المحدد وفق الترتيب المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| زاوية | float | زاوية الدوران. |
| الترتيب | int |   Aspose.Imaging.MatrixOrder  يحدد ما إذا كان سيتم إلحاق أو إلحاق مسبق لمصفوفة الدوران. |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


يقوم بتكبير التحويل الهندسي المحلي بالمقادير المحددة. هذه الطريقة تسبق مصفوفة التكبير إلى التحويل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| sx | float | المقدار الذي يتم به تكبير التحويل في اتجاه محور x. |
| sy | float | المقدار الذي يتم به تكبير التحويل في اتجاه محور y. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


يقوم بتحجيم التحويل الهندسي المحلي بالمقاسات المحددة وفق الترتيب المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| sx | float | المقدار الذي يتم به تكبير التحويل في اتجاه محور x. |
| sy | float | المقدار الذي يتم به تكبير التحويل في اتجاه محور y. |
| الترتيب | int |   Aspose.Imaging.MatrixOrder  يحدد ما إذا كان سيتم إلحاق أو إلحاق مسبق لمصفوفة التكبير. |

### setAngle(float value) {#setAngle-float-}
```
public void setAngle(float value)
```


يضبط زاوية التدرج.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float | زاوية التدرج. |

### setAngleScalable(boolean value) {#setAngleScalable-boolean-}
```
public void setAngleScalable(boolean value)
```


يضبط قيمة تشير إلى ما إذا كان LinearGradientBrushBase.Angle يتغير أثناء التحولات باستخدام هذا LinearGradientBrushBase.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | true إذا تم تغيير LinearGradientBrushBase.Angle أثناء التحويلات باستخدام هذا LinearGradientBrushBase؛ وإلا، false. |

### setBlend(Blend value) {#setBlend-com.aspose.psd.Blend-}
```
public void setBlend(Blend value)
```


يضبط Aspose.Imaging.Blend الذي يحدد المواقع والعوامل التي تعرف انخفاضاً مخصصاً للتدرج.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Blend](../../com.aspose.psd/blend) | كائن Aspose.Imaging.Blend يمثل انخفاضًا مخصصًا للتدرج. |

### setBlendTriangularShape(float focus) {#setBlendTriangularShape-float-}
```
public void setBlendTriangularShape(float focus)
```


ينشئ تدرجاً خطياً بلون مركزي وانخفاضاً خطياً إلى لون واحد في الطرفين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| التركيز | float | قيمة من 0 إلى 1 تحدد مركز التدرج (النقطة التي يتكون فيها التدرج من اللون النهائي فقط). |

### setBlendTriangularShape(float focus, float scale) {#setBlendTriangularShape-float-float-}
```
public void setBlendTriangularShape(float focus, float scale)
```


ينشئ تدرجاً خطياً بلون مركزي وانخفاضاً خطياً إلى لون واحد في الطرفين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| التركيز | float | قيمة من 0 إلى 1 تحدد مركز التدرج (النقطة التي يتكون فيها التدرج من اللون النهائي فقط). |
| المقياس | float | قيمة من 0 إلى 1 تحدد سرعة انخفاض الألوان من اللون الابتدائي إلى التركيز (اللون النهائي). |

### setEndColor(Color value) {#setEndColor-com.aspose.psd.Color-}
```
public void setEndColor(Color value)
```


يضبط لون التدرج النهائي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | لون التدرج النهائي. |

### setGammaCorrection(boolean value) {#setGammaCorrection-boolean-}
```
public void setGammaCorrection(boolean value)
```


يضبط قيمة تشير إلى ما إذا كان تصحيح غاما مفعلاً لهذا LinearGradientBrushBase.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | القيمة true إذا تم تمكين تصحيح غاما لهذا LinearGradientBrushBase؛ وإلا، false. |

### setInterpolationColors(ColorBlend value) {#setInterpolationColors-com.aspose.psd.ColorBlend-}
```
public void setInterpolationColors(ColorBlend value)
```


يضبط com.aspose.psd.ColorBlend الذي يحدد تدرجًا خطيًا متعدد الألوان.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [ColorBlend](../../com.aspose.psd/colorblend) | كائن com.aspose.psd.ColorBlend يحدد تدرجًا خطيًا متعدد الألوان. |

### setLinearColors(Color[] value) {#setLinearColors-com.aspose.psd.Color---}
```
public void setLinearColors(Color[] value)
```


يضبط الألوان الابتدائية والنهائية للتدرج.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Color\[\]](../../com.aspose.psd/color) | مصفوفة من هيكلين من نوع Color تمثل الألوان الابتدائية والنهائية للتدرج. |

### setOpacity(float value) {#setOpacity-float-}
```
public void setOpacity(float value)
```


يضبط شفافية الفرشاة. يجب أن تكون القيمة بين 0 و 1. القيمة 0 تعني أن الفرشاة مرئية بالكامل، والقيمة 1 تعني أن الفرشاة غير شفافة تمامًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float | قيمة شفافية الفرشاة. |

### setRectangle(RectangleF value) {#setRectangle-com.aspose.psd.RectangleF-}
```
public void setRectangle(RectangleF value)
```


يضبط منطقة مستطيلة تحدد نقطتي البداية والنهاية للتدرج.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.psd/rectanglef) | هيكل com.aspose.psd.RectangleF يحدد نقطتي البداية والنهاية للتدرج. |

### setSigmaBellShape(float focus) {#setSigmaBellShape-float-}
```
public void setSigmaBellShape(float focus)
```


ينشئ انخفاضاً للتدرج بناءً على منحنى على شكل جرس.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| التركيز | float | قيمة من 0 إلى 1 تحدد مركز التدرج (النقطة التي يختلط فيها اللون الابتدائي والنهائي بالتساوي). |

### setSigmaBellShape(float focus, float scale) {#setSigmaBellShape-float-float-}
```
public void setSigmaBellShape(float focus, float scale)
```


ينشئ انخفاضاً للتدرج بناءً على منحنى على شكل جرس.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| التركيز | float | قيمة من 0 إلى 1 تحدد مركز التدرج (النقطة التي يتكون فيها التدرج من اللون النهائي فقط). |
| المقياس | float | قيمة من 0 إلى 1 تحدد سرعة انخفاض الألوان من التركيز. |

### setStartColor(Color value) {#setStartColor-com.aspose.psd.Color-}
```
public void setStartColor(Color value)
```


يضبط لون التدرج الابتدائي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | لون التدرج الابتدائي. |

### setTransform(Matrix value) {#setTransform-com.aspose.psd.Matrix-}
```
public void setTransform(Matrix value)
```


يحصل أو يضبط نسخة Aspose.Imaging.Matrix التي تحدد تحويلًا هندسيًا محليًا لهذا TransformBrush.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.psd/matrix) |  |

### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


يحصل أو يضبط تعداد Aspose.Imaging.WrapMode الذي يشير إلى وضع الالتفاف لهذا TransformBrush.

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
### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public void translateTransform(float dx, float dy)
```


يترجم التحويل الهندسي المحلي بالأبعاد المحددة. هذه الطريقة تسبق الترجمة إلى التحويل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| dx | float | قيمة الترجمة في المحور x. |
| dy | float | قيمة الترجمة في المحور y. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


ينقل التحويل الهندسي المحلي بالأبعاد المحددة وفق الترتيب المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| dx | float | قيمة الترجمة في المحور x. |
| dy | float | قيمة الترجمة في المحور y. |
| الترتيب | int | الترتيب (سابق أو لاحق) لتطبيق الترجمة. |

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

