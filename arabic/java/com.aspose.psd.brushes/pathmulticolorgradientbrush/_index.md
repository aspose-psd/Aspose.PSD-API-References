---
title: "PathMulticolorGradientBrush"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "يحتوي على كائن Aspose.Imaging.Brush مع تدرج لوني."
type: docs
weight: 16
url: /ar/java/com.aspose.psd.brushes/pathmulticolorgradientbrush/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.Brush](../../com.aspose.psd/brush), [com.aspose.psd.brushes.TransformBrush](../../com.aspose.psd.brushes/transformbrush), [com.aspose.psd.brushes.PathGradientBrushBase](../../com.aspose.psd.brushes/pathgradientbrushbase)
```
public final class PathMulticolorGradientBrush extends PathGradientBrushBase
```

يحتوي على كائن Aspose.Imaging.Brush مع تدرج لوني. لا يمكن وراثة هذه الفئة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [PathMulticolorGradientBrush(PointF[] points)](#PathMulticolorGradientBrush-com.aspose.psd.PointF---) | ينشئ مثيلاً جديداً من الفئة PathMulticolorGradientBrush باستخدام النقاط المحددة. |
| [PathMulticolorGradientBrush(PointF[] points, int wrapMode)](#PathMulticolorGradientBrush-com.aspose.psd.PointF---int-) | ينشئ مثيلاً جديداً من الفئة PathMulticolorGradientBrush باستخدام النقاط المحددة ووضع الالتفاف. |
| [PathMulticolorGradientBrush(Point[] points)](#PathMulticolorGradientBrush-com.aspose.psd.Point---) | ينشئ مثيلاً جديداً من الفئة PathMulticolorGradientBrush باستخدام النقاط المحددة. |
| [PathMulticolorGradientBrush(Point[] points, int wrapMode)](#PathMulticolorGradientBrush-com.aspose.psd.Point---int-) | ينشئ مثيلاً جديداً من الفئة PathMulticolorGradientBrush باستخدام النقاط المحددة ووضع الالتفاف. |
| [PathMulticolorGradientBrush(GraphicsPath path)](#PathMulticolorGradientBrush-com.aspose.psd.GraphicsPath-) | ينشئ مثيلاً جديداً من الفئة PathMulticolorGradientBrush باستخدام المسار المحدد. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [close()](#close--) | تنفذ واجهة Closable ويمكن استخدامها في عبارة try-with-resources منذ JDK 1.7. |
| [deepClone()](#deepClone--) | ينشئ نسخة عميقة جديدة من الـ Brush الحالي. |
| [dispose()](#dispose--) | يحرر النسخة الحالية. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCenterPoint()](#getCenterPoint--) | يحصل أو يضبط نقطة المركز لتدرج المسار. |
| [getClass()](#getClass--) |  |
| [getDisposed()](#getDisposed--) | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن قد تم التخلص منه. |
| [getFocusScales()](#getFocusScales--) | يحصل على نقطة التركيز لتلاشي التدرج. |
| [getGraphicsPath()](#getGraphicsPath--) | يحصل على مسار الرسومات الذي بُنيت عليه هذه الفرشاة. |
| [getInterpolationColors()](#getInterpolationColors--) | يحصل أو يعيّن كائن com.aspose.psd.ColorBlend الذي يحدد تدرجًا خطيًا متعدد الألوان. |
| [getOpacity()](#getOpacity--) | يحصل على شفافية الفرشاة. |
| [getPathPoints()](#getPathPoints--) | يحصل على نقاط المسار التي بُنيت عليها هذه الفرشاة. |
| [getTransform()](#getTransform--) | يحصل أو يضبط نسخة Aspose.Imaging.Matrix التي تحدد تحويلًا هندسيًا محليًا لهذا TransformBrush. |
| [getWrapMode()](#getWrapMode--) | يحصل أو يضبط تعداد Aspose.Imaging.WrapMode الذي يشير إلى وضع الالتفاف لهذا TransformBrush. |
| [hashCode()](#hashCode--) |  |
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
| [setCenterPoint(PointF value)](#setCenterPoint-com.aspose.psd.PointF-) | يحصل أو يضبط نقطة المركز لتدرج المسار. |
| [setFocusScales(PointF value)](#setFocusScales-com.aspose.psd.PointF-) | يحصل أو يضبط نقطة التركيز لتلاشي التدرج. |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.psd.ColorBlend-) | يحصل أو يعيّن كائن com.aspose.psd.ColorBlend الذي يحدد تدرجًا خطيًا متعدد الألوان. |
| [setOpacity(float value)](#setOpacity-float-) | يضبط شفافية الفرشاة. |
| [setTransform(Matrix value)](#setTransform-com.aspose.psd.Matrix-) | يحصل أو يضبط نسخة Aspose.Imaging.Matrix التي تحدد تحويلًا هندسيًا محليًا لهذا TransformBrush. |
| [setWrapMode(int value)](#setWrapMode-int-) | يحصل أو يضبط تعداد Aspose.Imaging.WrapMode الذي يشير إلى وضع الالتفاف لهذا TransformBrush. |
| [toString()](#toString--) |  |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | ينقل التحويل الهندسي المحلي بالأبعاد المحددة. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | ينقل التحويل الهندسي المحلي بالأبعاد المحددة وفق الترتيب المحدد. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PathMulticolorGradientBrush(PointF[] points) {#PathMulticolorGradientBrush-com.aspose.psd.PointF---}
```
public PathMulticolorGradientBrush(PointF[] points)
```


ينشئ مثيلاً جديداً من الفئة PathMulticolorGradientBrush باستخدام النقاط المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | مصفوفة من هياكل Aspose.Imaging.PointF تمثل النقاط التي تشكل رؤوس المسار. |

### PathMulticolorGradientBrush(PointF[] points, int wrapMode) {#PathMulticolorGradientBrush-com.aspose.psd.PointF---int-}
```
public PathMulticolorGradientBrush(PointF[] points, int wrapMode)
```


ينشئ مثيلاً جديداً من الفئة PathMulticolorGradientBrush باستخدام النقاط المحددة ووضع الالتفاف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | مصفوفة من هياكل Aspose.Imaging.PointF تمثل النقاط التي تشكل رؤوس المسار. |
| wrapMode | int | Aspose.Imaging.WrapMode يحدد كيفية تكرار التعبئات المرسومة باستخدام PathMulticolorGradientBrush. |

### PathMulticolorGradientBrush(Point[] points) {#PathMulticolorGradientBrush-com.aspose.psd.Point---}
```
public PathMulticolorGradientBrush(Point[] points)
```


ينشئ مثيلاً جديداً من الفئة PathMulticolorGradientBrush باستخدام النقاط المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| points | [Point\[\]](../../com.aspose.psd/point) | مصفوفة من هياكل Aspose.Imaging.Point تمثل النقاط التي تشكل رؤوس المسار. |

### PathMulticolorGradientBrush(Point[] points, int wrapMode) {#PathMulticolorGradientBrush-com.aspose.psd.Point---int-}
```
public PathMulticolorGradientBrush(Point[] points, int wrapMode)
```


ينشئ مثيلاً جديداً من الفئة PathMulticolorGradientBrush باستخدام النقاط المحددة ووضع الالتفاف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| points | [Point\[\]](../../com.aspose.psd/point) | مصفوفة من هياكل Aspose.Imaging.Point تمثل النقاط التي تشكل رؤوس المسار. |
| wrapMode | int | Aspose.Imaging.WrapMode يحدد كيفية تكرار التعبئات المرسومة باستخدام PathMulticolorGradientBrush. |

### PathMulticolorGradientBrush(GraphicsPath path) {#PathMulticolorGradientBrush-com.aspose.psd.GraphicsPath-}
```
public PathMulticolorGradientBrush(GraphicsPath path)
```


ينشئ مثيلاً جديداً من الفئة PathMulticolorGradientBrush باستخدام المسار المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | GraphicsPath الذي يحدد المنطقة المملوءة بواسطة PathMulticolorGradientBrush. |

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
### getCenterPoint() {#getCenterPoint--}
```
public PointF getCenterPoint()
```


يحصل أو يضبط نقطة المركز لتدرج المسار.

**Returns:**
[PointF](../../com.aspose.psd/pointf) - A  Aspose.Imaging.PointF  that represents the center point of the path gradient.
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
### getFocusScales() {#getFocusScales--}
```
public PointF getFocusScales()
```


يحصل على نقطة التركيز لتلاشي التدرج.

**Returns:**
[PointF](../../com.aspose.psd/pointf) - A  Aspose.Imaging.PointF  that represents the focus point for the gradient falloff.
### getGraphicsPath() {#getGraphicsPath--}
```
public GraphicsPath getGraphicsPath()
```


يحصل على مسار الرسومات الذي بُنيت عليه هذه الفرشاة.

**Returns:**
[GraphicsPath](../../com.aspose.psd/graphicspath) - The graphics path.
### getInterpolationColors() {#getInterpolationColors--}
```
public ColorBlend getInterpolationColors()
```


يحصل أو يعيّن كائن com.aspose.psd.ColorBlend الذي يحدد تدرجًا خطيًا متعدد الألوان.

القيمة: com.aspose.psd.ColorBlend الذي يحدد تدرجًا خطيًا متعدد الألوان.

**Returns:**
[ColorBlend](../../com.aspose.psd/colorblend)
### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


يحصل على شفافية الفرشاة. يجب أن تكون القيمة بين 0 و 1. القيمة 0 تعني أن الفرشاة مرئية بالكامل، والقيمة 1 تعني أن الفرشاة غير شفافة تمامًا.

**Returns:**
float - قيمة شفافية الفرشاة.
### getPathPoints() {#getPathPoints--}
```
public PointF[] getPathPoints()
```


يحصل على نقاط المسار التي بُنيت عليها هذه الفرشاة.

**Returns:**
com.aspose.psd.PointF[] - نقاط المسار.
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

### setCenterPoint(PointF value) {#setCenterPoint-com.aspose.psd.PointF-}
```
public void setCenterPoint(PointF value)
```


يحصل أو يضبط نقطة المركز لتدرج المسار.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [PointF](../../com.aspose.psd/pointf) | كائن Aspose.Imaging.PointF يمثل نقطة المركز لتدرج المسار. |

### setFocusScales(PointF value) {#setFocusScales-com.aspose.psd.PointF-}
```
public void setFocusScales(PointF value)
```


يحصل أو يضبط نقطة التركيز لتلاشي التدرج.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [PointF](../../com.aspose.psd/pointf) | كائن Aspose.Imaging.PointF يمثل نقطة التركيز لتلاشي التدرج. |

### setInterpolationColors(ColorBlend value) {#setInterpolationColors-com.aspose.psd.ColorBlend-}
```
public void setInterpolationColors(ColorBlend value)
```


يحصل أو يعيّن كائن com.aspose.psd.ColorBlend الذي يحدد تدرجًا خطيًا متعدد الألوان.

القيمة: com.aspose.psd.ColorBlend الذي يحدد تدرجًا خطيًا متعدد الألوان.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [ColorBlend](../../com.aspose.psd/colorblend) |  |

### setOpacity(float value) {#setOpacity-float-}
```
public void setOpacity(float value)
```


يضبط شفافية الفرشاة. يجب أن تكون القيمة بين 0 و 1. القيمة 0 تعني أن الفرشاة مرئية بالكامل، والقيمة 1 تعني أن الفرشاة غير شفافة تمامًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float | قيمة شفافية الفرشاة. |

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

