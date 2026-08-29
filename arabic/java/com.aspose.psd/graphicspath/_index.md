---
title: "GraphicsPath"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "يمثل سلسلة من الخطوط والمنحنيات المتصلة."
type: docs
weight: 50
url: /ar/java/com.aspose.psd/graphicspath/
---

**Inheritance:**
java.lang.Object، [com.aspose.psd.ObjectWithBounds](../../com.aspose.psd/objectwithbounds)
```
public final class GraphicsPath extends ObjectWithBounds
```

يمثل سلسلة من الخطوط والمنحنيات المتصلة. لا يمكن وراثة هذه الفئة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [GraphicsPath()](#GraphicsPath--) | ينشئ مثيلاً جديداً لفئة  GraphicsPath  class. |
| [GraphicsPath(Figure[] figures)](#GraphicsPath-com.aspose.psd.Figure---) | ينشئ مثيلاً جديداً لفئة  GraphicsPath  class. |
| [GraphicsPath(Figure[] figures, int fillMode)](#GraphicsPath-com.aspose.psd.Figure---int-) | ينشئ مثيلاً جديداً لفئة  GraphicsPath  class. |
| [GraphicsPath(int fillMode)](#GraphicsPath-int-) | ينشئ مثيلاً جديداً لفئة  GraphicsPath  class. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [addFigure(Figure figure)](#addFigure-com.aspose.psd.Figure-) | يضيف شكلاً جديداً. |
| [addFigures(Figure[] figures)](#addFigures-com.aspose.psd.Figure---) | يضيف أشكالاً جديدة. |
| [addPath(GraphicsPath addingPath)](#addPath-com.aspose.psd.GraphicsPath-) | يضيف المسار المحدد  com.aspose.psd.GraphicsPath  إلى هذا المسار. |
| [addPath(GraphicsPath addingPath, boolean connect)](#addPath-com.aspose.psd.GraphicsPath-boolean-) | يضيف المسار المحدد  com.aspose.psd.GraphicsPath  إلى هذا المسار. |
| [deepClone()](#deepClone--) | ينفذ استنساخاً عميقاً لهذا المسار الرسومي. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [flatten()](#flatten--) | يحوّل كل منحنى في هذا المسار إلى سلسلة من القطع الخطية المتصلة. |
| [flatten(Matrix matrix)](#flatten-com.aspose.psd.Matrix-) | يطبق التحويل المحدد ثم يحوّل كل منحنى في هذا  com.aspose.psd.GraphicsPath  إلى سلسلة من القطع الخطية المتصلة. |
| [flatten(Matrix matrix, float flatness)](#flatten-com.aspose.psd.Matrix-float-) | يحوّل كل منحنى في هذا  com.aspose.psd.GraphicsPath  إلى سلسلة من القطع الخطية المتصلة. |
| [getBounds()](#getBounds--) | يحصل أو يعيّن حدود الكائن. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.psd.Matrix-) | يحصل على حدود الكائن. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-) | يحصل على حدود الكائن. |
| [getClass()](#getClass--) |  |
| [getFigures()](#getFigures--) | يحصل على أشكال المسار. |
| [getFillMode()](#getFillMode--) | يحصل على تعداد  com.aspose.psd.FillMode  الذي يحدد كيفية تعبئة داخل الأشكال في هذا  com.aspose.psd.GraphicsPath . |
| [hashCode()](#hashCode--) |  |
| [isOutlineVisible(Point point, Pen pen)](#isOutlineVisible-com.aspose.psd.Point-com.aspose.psd.Pen-) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل (تحت) حدود هذا  com.aspose.psd.GraphicsPath  عند رسمه بالقلم المحدد  com.aspose.psd.pen . |
| [isOutlineVisible(Point pt, Pen pen, Graphics graphics)](#isOutlineVisible-com.aspose.psd.Point-com.aspose.psd.Pen-com.aspose.psd.Graphics-) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل (تحت) حدود هذا  com.aspose.psd.GraphicsPath  عند رسمه بالقلم المحدد  com.aspose.psd.Pen  وباستخدام الرسومات المحددة  com.aspose.psd.graphics . |
| [isOutlineVisible(PointF point, Pen pen)](#isOutlineVisible-com.aspose.psd.PointF-com.aspose.psd.Pen-) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل (تحت) حدود هذا  com.aspose.psd.GraphicsPath  عند رسمه بالقلم المحدد  com.aspose.psd.pen . |
| [isOutlineVisible(PointF pt, Pen pen, Graphics graphics)](#isOutlineVisible-com.aspose.psd.PointF-com.aspose.psd.Pen-com.aspose.psd.Graphics-) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل (تحت) حدود هذا  com.aspose.psd.GraphicsPath  عند رسمه بالقلم المحدد  com.aspose.psd.Pen  وباستخدام الرسومات المحددة  com.aspose.psd.graphics . |
| [isOutlineVisible(float x, float y, Pen pen)](#isOutlineVisible-float-float-com.aspose.psd.Pen-) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل (تحت) حدود هذا  com.aspose.psd.GraphicsPath  عند رسمه بالقلم المحدد  com.aspose.psd.pen . |
| [isOutlineVisible(float x, float y, Pen pen, Graphics graphics)](#isOutlineVisible-float-float-com.aspose.psd.Pen-com.aspose.psd.Graphics-) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل (تحت) حدود هذا  com.aspose.psd.GraphicsPath  عند رسمه بالقلم المحدد  com.aspose.psd.Pen  وباستخدام الرسومات المحددة  com.aspose.psd.graphics . |
| [isOutlineVisible(int x, int y, Pen pen)](#isOutlineVisible-int-int-com.aspose.psd.Pen-) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل (تحت) حدود هذا  com.aspose.psd.GraphicsPath  عند رسمه بالقلم المحدد  com.aspose.psd.pen . |
| [isOutlineVisible(int x, int y, Pen pen, Graphics graphics)](#isOutlineVisible-int-int-com.aspose.psd.Pen-com.aspose.psd.Graphics-) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل (تحت) حدود هذا  com.aspose.psd.GraphicsPath  عند رسمه بالقلم المحدد  com.aspose.psd.Pen  وباستخدام الرسومات المحددة  com.aspose.psd.graphics . |
| [isVisible(Point point)](#isVisible-com.aspose.psd.Point-) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل هذا  com.aspose.psd.graphicsPath . |
| [isVisible(Point pt, Graphics graphics)](#isVisible-com.aspose.psd.Point-com.aspose.psd.Graphics-) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل هذا  com.aspose.psd.graphicsPath . |
| [isVisible(PointF point)](#isVisible-com.aspose.psd.PointF-) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل هذا  com.aspose.psd.graphicsPath . |
| [isVisible(PointF pt, Graphics graphics)](#isVisible-com.aspose.psd.PointF-com.aspose.psd.Graphics-) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل هذا  com.aspose.psd.graphicsPath . |
| [isVisible(float x, float y)](#isVisible-float-float-) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل هذا  com.aspose.psd.graphicsPath . |
| [isVisible(float x, float y, Graphics graphics)](#isVisible-float-float-com.aspose.psd.Graphics-) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل هذا  com.aspose.psd.GraphicsPath  في منطقة القص المرئية للرسومات المحددة  com.aspose.psd.graphics . |
| [isVisible(int x, int y)](#isVisible-int-int-) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل هذا  com.aspose.psd.graphicsPath . |
| [isVisible(int x, int y, Graphics graphics)](#isVisible-int-int-com.aspose.psd.Graphics-) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل هذا  com.aspose.psd.GraphicsPath ، باستخدام الرسومات المحددة  com.aspose.psd.graphics . |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeFigure(Figure figure)](#removeFigure-com.aspose.psd.Figure-) | يزيل شكلاً. |
| [removeFigures(Figure[] figures)](#removeFigures-com.aspose.psd.Figure---) | يزيل أشكالاً. |
| [reset()](#reset--) | يفرغ مسار الرسومات ويضبط  com.aspose.psd.FillMode  إلى  F:com.aspose.psd.fillMode.alternate . |
| [reverse()](#reverse--) | يعكس ترتيب الأشكال، والرسومات، والنقاط في كل شكل من هذا  com.aspose.psd.graphicsPath . |
| [setFillMode(int value)](#setFillMode-int-) | يضبط تعداد  com.aspose.psd.FillMode  الذي يحدد كيفية تعبئة داخلية الأشكال في هذا  com.aspose.psd.GraphicsPath . |
| [toString()](#toString--) |  |
| [transform(Matrix transform)](#transform-com.aspose.psd.Matrix-) | يطبق التحويل المحدد على الشكل. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [warp(PointF[] destPoints, RectangleF srcRect)](#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-) | يطبق تحويل تشويه، معرف بواسطة مستطيل ومتوازي أضلاع، على هذا  com.aspose.psd.graphicsPath . |
| [warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix)](#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-) | يطبق تحويل تشويه، معرف بواسطة مستطيل ومتوازي أضلاع، على هذا  com.aspose.psd.graphicsPath . |
| [warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode)](#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-int-) | يطبق تحويل تشويه، معرف بواسطة مستطيل ومتوازي أضلاع، على هذا  com.aspose.psd.graphicsPath . |
| [warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode, float flatness)](#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-int-float-) | يطبق تحويل تشويه، معرف بواسطة مستطيل ومتوازي أضلاع، على هذا  com.aspose.psd.graphicsPath . |
| [widen(Pen pen)](#widen-com.aspose.psd.Pen-) | يضيف مخططًا إضافيًا إلى المسار. |
| [widen(Pen pen, Matrix matrix)](#widen-com.aspose.psd.Pen-com.aspose.psd.Matrix-) | يضيف مخططًا إضافيًا إلى  com.aspose.psd.graphicsPath . |
| [widen(Pen pen, Matrix matrix, float flatness)](#widen-com.aspose.psd.Pen-com.aspose.psd.Matrix-float-) | يستبدل هذا  com.aspose.psd.GraphicsPath  بمنحنيات تحيط بالمنطقة التي تُملأ عندما يُرسم هذا المسار بالقلم المحدد. |
### GraphicsPath() {#GraphicsPath--}
```
public GraphicsPath()
```


ينشئ مثيلاً جديداً لفئة  GraphicsPath  class.

### GraphicsPath(Figure[] figures) {#GraphicsPath-com.aspose.psd.Figure---}
```
public GraphicsPath(Figure[] figures)
```


ينشئ مثيلاً جديداً لفئة  GraphicsPath  class.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.psd/figure) | الأشكال للبدء منها. |

### GraphicsPath(Figure[] figures, int fillMode) {#GraphicsPath-com.aspose.psd.Figure---int-}
```
public GraphicsPath(Figure[] figures, int fillMode)
```


ينشئ مثيلاً جديداً لفئة  GraphicsPath  class.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.psd/figure) | الأشكال للبدء منها. |
| fillMode | int | وضع التعبئة. |

### GraphicsPath(int fillMode) {#GraphicsPath-int-}
```
public GraphicsPath(int fillMode)
```


ينشئ مثيلاً جديداً لفئة  GraphicsPath  class.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fillMode | int | وضع التعبئة. |

### addFigure(Figure figure) {#addFigure-com.aspose.psd.Figure-}
```
public void addFigure(Figure figure)
```


يضيف شكلاً جديداً.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| figure | [Figure](../../com.aspose.psd/figure) | الشكل لإضافته. |

### addFigures(Figure[] figures) {#addFigures-com.aspose.psd.Figure---}
```
public void addFigures(Figure[] figures)
```


يضيف أشكالاً جديدة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.psd/figure) | الأشكال لإضافتها. |

### addPath(GraphicsPath addingPath) {#addPath-com.aspose.psd.GraphicsPath-}
```
public void addPath(GraphicsPath addingPath)
```


يضيف المسار المحدد  com.aspose.psd.GraphicsPath  إلى هذا المسار.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| addingPath | [GraphicsPath](../../com.aspose.psd/graphicspath) | الـ  com.aspose.psd.GraphicsPath  للإضافة. |

### addPath(GraphicsPath addingPath, boolean connect) {#addPath-com.aspose.psd.GraphicsPath-boolean-}
```
public void addPath(GraphicsPath addingPath, boolean connect)
```


يضيف المسار المحدد  com.aspose.psd.GraphicsPath  إلى هذا المسار.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| addingPath | [GraphicsPath](../../com.aspose.psd/graphicspath) | الـ  com.aspose.psd.GraphicsPath  للإضافة. |
| connect | boolean | قيمة منطقية تحدد ما إذا كان الشكل الأول في المسار المضاف جزءًا من الشكل الأخير في هذا المسار. قيمة true تشير إلى أن الشكل الأول في المسار المضاف جزء من الشكل الأخير في هذا المسار. قيمة false تشير إلى أن الشكل الأول في المسار المضاف منفصل عن الشكل الأخير في هذا المسار. |

### deepClone() {#deepClone--}
```
public GraphicsPath deepClone()
```


ينفذ استنساخاً عميقاً لهذا المسار الرسومي.

**Returns:**
[GraphicsPath](../../com.aspose.psd/graphicspath) - A deep clone of the graphics path.
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
### flatten() {#flatten--}
```
public void flatten()
```


يحوّل كل منحنى في هذا المسار إلى سلسلة من القطع الخطية المتصلة.

### flatten(Matrix matrix) {#flatten-com.aspose.psd.Matrix-}
```
public void flatten(Matrix matrix)
```


يطبق التحويل المحدد ثم يحوّل كل منحنى في هذا  com.aspose.psd.GraphicsPath  إلى سلسلة من القطع الخطية المتصلة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | مصفوفة  com.aspose.psd.Matrix  التي تُستخدم لتحويل هذا  com.aspose.psd.GraphicsPath  قبل التسطيح. |

### flatten(Matrix matrix, float flatness) {#flatten-com.aspose.psd.Matrix-float-}
```
public void flatten(Matrix matrix, float flatness)
```


يحوّل كل منحنى في هذا  com.aspose.psd.GraphicsPath  إلى سلسلة من القطع الخطية المتصلة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | مصفوفة  com.aspose.psd.Matrix  التي تُستخدم لتحويل هذا  com.aspose.psd.GraphicsPath  قبل التسطيح. |
| flatness | float | يحدد الحد الأقصى للخطأ المسموح بين المنحنى وتقريبه المسطح. القيمة الافتراضية هي 0.25. تقليل قيمة السطحية سيزيد عدد مقاطع الخط في التقريب. |

### getBounds() {#getBounds--}
```
public RectangleF getBounds()
```


يحصل أو يعيّن حدود الكائن.

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The object's bounds.
### getBounds(Matrix matrix) {#getBounds-com.aspose.psd.Matrix-}
```
public RectangleF getBounds(Matrix matrix)
```


يحصل على حدود الكائن.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | المصفوفة التي سيتم تطبيقها قبل حساب الحدود. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The estimated object's bounds.
### getBounds(Matrix matrix, Pen pen) {#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-}
```
public RectangleF getBounds(Matrix matrix, Pen pen)
```


يحصل على حدود الكائن.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | المصفوفة التي سيتم تطبيقها قبل حساب الحدود. |
| pen | [Pen](../../com.aspose.psd/pen) | القلم المستخدم للكائن. يمكن أن يؤثر ذلك على حجم حدود الكائن. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The estimated object's bounds.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFigures() {#getFigures--}
```
public Figure[] getFigures()
```


يحصل على أشكال المسار.

**Returns:**
com.aspose.psd.Figure[] - أشكال المسار.
### getFillMode() {#getFillMode--}
```
public int getFillMode()
```


يحصل على تعداد  com.aspose.psd.FillMode  الذي يحدد كيفية تعبئة داخل الأشكال في هذا  com.aspose.psd.GraphicsPath .

**Returns:**
int - وضع التعبئة. تعداد  com.aspose.psd.FillMode  يحدد كيفية تعبئة داخلية الأشكال في هذا  com.aspose.psd.GraphicsPath .
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isOutlineVisible(Point point, Pen pen) {#isOutlineVisible-com.aspose.psd.Point-com.aspose.psd.Pen-}
```
public boolean isOutlineVisible(Point point, Pen pen)
```


يشير إلى ما إذا كانت النقطة المحددة موجودة داخل (تحت) حدود هذا  com.aspose.psd.GraphicsPath  عند رسمه بالقلم المحدد  com.aspose.psd.pen .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | نقطة  com.aspose.psd.Point  تحدد الموقع المراد اختباره. |
| pen | [Pen](../../com.aspose.psd/pen) | القلم  com.aspose.psd.Pen  للاختبار. |

**Returns:**
boolean - تُعيد هذه الطريقة true إذا كانت النقطة المحددة داخل مخطط هذا  com.aspose.psd.GraphicsPath  عند رسمه بالقلم المحدد  com.aspose.psd.Pen ; وإلا false.
### isOutlineVisible(Point pt, Pen pen, Graphics graphics) {#isOutlineVisible-com.aspose.psd.Point-com.aspose.psd.Pen-com.aspose.psd.Graphics-}
```
public boolean isOutlineVisible(Point pt, Pen pen, Graphics graphics)
```


يشير إلى ما إذا كانت النقطة المحددة موجودة داخل (تحت) حدود هذا  com.aspose.psd.GraphicsPath  عند رسمه بالقلم المحدد  com.aspose.psd.Pen  وباستخدام الرسومات المحددة  com.aspose.psd.graphics .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pt | [Point](../../com.aspose.psd/point) | نقطة  com.aspose.psd.Point  تحدد الموقع المراد اختباره. |
| pen | [Pen](../../com.aspose.psd/pen) | القلم  com.aspose.psd.Pen  للاختبار. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | الكائن  com.aspose.psd.Graphics  الذي يُختبر ظهوره. |

**Returns:**
boolean - تُعيد هذه الطريقة true إذا كانت النقطة المحددة داخل مخطط هذا  com.aspose.psd.GraphicsPath  كما يُرسم بالقلم المحدد  com.aspose.psd.Pen ; وإلا false.
### isOutlineVisible(PointF point, Pen pen) {#isOutlineVisible-com.aspose.psd.PointF-com.aspose.psd.Pen-}
```
public boolean isOutlineVisible(PointF point, Pen pen)
```


يشير إلى ما إذا كانت النقطة المحددة موجودة داخل (تحت) حدود هذا  com.aspose.psd.GraphicsPath  عند رسمه بالقلم المحدد  com.aspose.psd.pen .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | نقطة  com.aspose.psd.PointF  تحدد الموقع المراد اختباره. |
| pen | [Pen](../../com.aspose.psd/pen) | القلم  com.aspose.psd.Pen  للاختبار. |

**Returns:**
boolean - تُعيد هذه الطريقة true إذا كانت النقطة المحددة داخل مخطط هذا  com.aspose.psd.GraphicsPath  عند رسمه بالقلم المحدد  com.aspose.psd.Pen ; وإلا false.
### isOutlineVisible(PointF pt, Pen pen, Graphics graphics) {#isOutlineVisible-com.aspose.psd.PointF-com.aspose.psd.Pen-com.aspose.psd.Graphics-}
```
public boolean isOutlineVisible(PointF pt, Pen pen, Graphics graphics)
```


يشير إلى ما إذا كانت النقطة المحددة موجودة داخل (تحت) حدود هذا  com.aspose.psd.GraphicsPath  عند رسمه بالقلم المحدد  com.aspose.psd.Pen  وباستخدام الرسومات المحددة  com.aspose.psd.graphics .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.psd/pointf) | نقطة  com.aspose.psd.PointF  تحدد الموقع المراد اختباره. |
| pen | [Pen](../../com.aspose.psd/pen) | القلم  com.aspose.psd.Pen  للاختبار. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | الكائن  com.aspose.psd.Graphics  الذي يُختبر ظهوره. |

**Returns:**
منطقي - تُرجع هذه الطريقة true إذا كانت النقطة المحددة موجودة داخل (تحت) مخطط هذا com.aspose.psd.GraphicsPath كما تم رسمه باستخدام com.aspose.psd.Pen المحدد؛ وإلا، false.
### isOutlineVisible(float x, float y, Pen pen) {#isOutlineVisible-float-float-com.aspose.psd.Pen-}
```
public boolean isOutlineVisible(float x, float y, Pen pen)
```


يشير إلى ما إذا كانت النقطة المحددة موجودة داخل (تحت) حدود هذا  com.aspose.psd.GraphicsPath  عند رسمه بالقلم المحدد  com.aspose.psd.pen .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| س | float | الإحداثي السيني للنقطة للاختبار. |
| ص | float | الإحداثي الصادي للنقطة للاختبار. |
| pen | [Pen](../../com.aspose.psd/pen) | القلم  com.aspose.psd.Pen  للاختبار. |

**Returns:**
boolean - تُعيد هذه الطريقة true إذا كانت النقطة المحددة داخل مخطط هذا  com.aspose.psd.GraphicsPath  عند رسمه بالقلم المحدد  com.aspose.psd.Pen ; وإلا false.
### isOutlineVisible(float x, float y, Pen pen, Graphics graphics) {#isOutlineVisible-float-float-com.aspose.psd.Pen-com.aspose.psd.Graphics-}
```
public boolean isOutlineVisible(float x, float y, Pen pen, Graphics graphics)
```


يشير إلى ما إذا كانت النقطة المحددة موجودة داخل (تحت) حدود هذا  com.aspose.psd.GraphicsPath  عند رسمه بالقلم المحدد  com.aspose.psd.Pen  وباستخدام الرسومات المحددة  com.aspose.psd.graphics .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| س | float | الإحداثي السيني للنقطة للاختبار. |
| ص | float | الإحداثي الصادي للنقطة للاختبار. |
| pen | [Pen](../../com.aspose.psd/pen) | القلم  com.aspose.psd.Pen  للاختبار. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | الكائن  com.aspose.psd.Graphics  الذي يُختبر ظهوره. |

**Returns:**
منطقي - تُرجع هذه الطريقة true إذا كانت النقطة المحددة موجودة داخل (تحت) مخطط هذا com.aspose.psd.GraphicsPath كما تم رسمه باستخدام com.aspose.psd.Pen المحدد؛ وإلا، false.
### isOutlineVisible(int x, int y, Pen pen) {#isOutlineVisible-int-int-com.aspose.psd.Pen-}
```
public boolean isOutlineVisible(int x, int y, Pen pen)
```


يشير إلى ما إذا كانت النقطة المحددة موجودة داخل (تحت) حدود هذا  com.aspose.psd.GraphicsPath  عند رسمه بالقلم المحدد  com.aspose.psd.pen .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| س | int | الإحداثي السيني للنقطة للاختبار. |
| ص | int | الإحداثي الصادي للنقطة للاختبار. |
| pen | [Pen](../../com.aspose.psd/pen) | القلم  com.aspose.psd.Pen  للاختبار. |

**Returns:**
boolean - تُعيد هذه الطريقة true إذا كانت النقطة المحددة داخل مخطط هذا  com.aspose.psd.GraphicsPath  عند رسمه بالقلم المحدد  com.aspose.psd.Pen ; وإلا false.
### isOutlineVisible(int x, int y, Pen pen, Graphics graphics) {#isOutlineVisible-int-int-com.aspose.psd.Pen-com.aspose.psd.Graphics-}
```
public boolean isOutlineVisible(int x, int y, Pen pen, Graphics graphics)
```


يشير إلى ما إذا كانت النقطة المحددة موجودة داخل (تحت) حدود هذا  com.aspose.psd.GraphicsPath  عند رسمه بالقلم المحدد  com.aspose.psd.Pen  وباستخدام الرسومات المحددة  com.aspose.psd.graphics .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| س | int | الإحداثي السيني للنقطة للاختبار. |
| ص | int | الإحداثي الصادي للنقطة للاختبار. |
| pen | [Pen](../../com.aspose.psd/pen) | القلم  com.aspose.psd.Pen  للاختبار. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | الكائن  com.aspose.psd.Graphics  الذي يُختبر ظهوره. |

**Returns:**
boolean - تُعيد هذه الطريقة true إذا كانت النقطة المحددة داخل مخطط هذا  com.aspose.psd.GraphicsPath  كما يُرسم بالقلم المحدد  com.aspose.psd.Pen ; وإلا false.
### isVisible(Point point) {#isVisible-com.aspose.psd.Point-}
```
public boolean isVisible(Point point)
```


يشير إلى ما إذا كانت النقطة المحددة موجودة داخل هذا  com.aspose.psd.graphicsPath .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | كائن com.aspose.psd.Point يمثل النقطة المراد اختبارها. |

**Returns:**
منطقي - تُرجع هذه الطريقة true إذا كانت النقطة المحددة موجودة داخل هذا com.aspose.psd.GraphicsPath؛ وإلا، false.
### isVisible(Point pt, Graphics graphics) {#isVisible-com.aspose.psd.Point-com.aspose.psd.Graphics-}
```
public boolean isVisible(Point pt, Graphics graphics)
```


يشير إلى ما إذا كانت النقطة المحددة موجودة داخل هذا  com.aspose.psd.graphicsPath .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pt | [Point](../../com.aspose.psd/point) | كائن com.aspose.psd.Point يمثل النقطة المراد اختبارها. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | الكائن  com.aspose.psd.Graphics  الذي يُختبر ظهوره. |

**Returns:**
منطقي - تُرجع هذه الطريقة true إذا كانت النقطة المحددة موجودة داخل هذا com.aspose.psd.GraphicsPath؛ وإلا، false.
### isVisible(PointF point) {#isVisible-com.aspose.psd.PointF-}
```
public boolean isVisible(PointF point)
```


يشير إلى ما إذا كانت النقطة المحددة موجودة داخل هذا  com.aspose.psd.graphicsPath .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | كائن com.aspose.psd.PointF يمثل النقطة المراد اختبارها. |

**Returns:**
منطقي - تُرجع هذه الطريقة true إذا كانت النقطة المحددة موجودة داخل هذا com.aspose.psd.GraphicsPath؛ وإلا، false.
### isVisible(PointF pt, Graphics graphics) {#isVisible-com.aspose.psd.PointF-com.aspose.psd.Graphics-}
```
public boolean isVisible(PointF pt, Graphics graphics)
```


يشير إلى ما إذا كانت النقطة المحددة موجودة داخل هذا  com.aspose.psd.graphicsPath .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.psd/pointf) | كائن com.aspose.psd.PointF يمثل النقطة المراد اختبارها. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | الكائن  com.aspose.psd.Graphics  الذي يُختبر ظهوره. |

**Returns:**
منطقي - تُرجع هذه الطريقة true إذا كانت النقطة المحددة موجودة داخل هذا؛ وإلا، false.
### isVisible(float x, float y) {#isVisible-float-float-}
```
public boolean isVisible(float x, float y)
```


يشير إلى ما إذا كانت النقطة المحددة موجودة داخل هذا  com.aspose.psd.graphicsPath .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| س | float | الإحداثي السيني للنقطة للاختبار. |
| ص | float | الإحداثي الصادي للنقطة للاختبار. |

**Returns:**
منطقي - تُرجع هذه الطريقة true إذا كانت النقطة المحددة موجودة داخل هذا com.aspose.psd.GraphicsPath؛ وإلا، false.
### isVisible(float x, float y, Graphics graphics) {#isVisible-float-float-com.aspose.psd.Graphics-}
```
public boolean isVisible(float x, float y, Graphics graphics)
```


يشير إلى ما إذا كانت النقطة المحددة موجودة داخل هذا  com.aspose.psd.GraphicsPath  في منطقة القص المرئية للرسومات المحددة  com.aspose.psd.graphics .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| س | float | الإحداثي السيني للنقطة للاختبار. |
| ص | float | الإحداثي الصادي للنقطة للاختبار. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | الكائن  com.aspose.psd.Graphics  الذي يُختبر ظهوره. |

**Returns:**
منطقي - تُرجع هذه الطريقة true إذا كانت النقطة المحددة موجودة داخل هذا com.aspose.psd.GraphicsPath؛ وإلا، false.
### isVisible(int x, int y) {#isVisible-int-int-}
```
public boolean isVisible(int x, int y)
```


يشير إلى ما إذا كانت النقطة المحددة موجودة داخل هذا  com.aspose.psd.graphicsPath .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| س | int | الإحداثي السيني للنقطة للاختبار. |
| ص | int | الإحداثي الصادي للنقطة للاختبار. |

**Returns:**
منطقي - تُرجع هذه الطريقة true إذا كانت النقطة المحددة موجودة داخل هذا com.aspose.psd.GraphicsPath؛ وإلا، false.
### isVisible(int x, int y, Graphics graphics) {#isVisible-int-int-com.aspose.psd.Graphics-}
```
public boolean isVisible(int x, int y, Graphics graphics)
```


يشير إلى ما إذا كانت النقطة المحددة موجودة داخل هذا  com.aspose.psd.GraphicsPath ، باستخدام الرسومات المحددة  com.aspose.psd.graphics .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| س | int | الإحداثي السيني للنقطة للاختبار. |
| ص | int | الإحداثي الصادي للنقطة للاختبار. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | الكائن  com.aspose.psd.Graphics  الذي يُختبر ظهوره. |

**Returns:**
منطقي - تُرجع هذه الطريقة true إذا كانت النقطة المحددة موجودة داخل هذا com.aspose.psd.GraphicsPath؛ وإلا، false.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeFigure(Figure figure) {#removeFigure-com.aspose.psd.Figure-}
```
public void removeFigure(Figure figure)
```


يزيل شكلاً.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| figure | [Figure](../../com.aspose.psd/figure) | الشكل المراد إزالته. |

### removeFigures(Figure[] figures) {#removeFigures-com.aspose.psd.Figure---}
```
public void removeFigures(Figure[] figures)
```


يزيل أشكالاً.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.psd/figure) | الأشكال المراد إزالتها. |

### reset() {#reset--}
```
public void reset()
```


يفرغ مسار الرسومات ويضبط  com.aspose.psd.FillMode  إلى  F:com.aspose.psd.fillMode.alternate .

### reverse() {#reverse--}
```
public void reverse()
```


يعكس ترتيب الأشكال، والرسومات، والنقاط في كل شكل من هذا  com.aspose.psd.graphicsPath .

### setFillMode(int value) {#setFillMode-int-}
```
public void setFillMode(int value)
```


يضبط تعداد  com.aspose.psd.FillMode  الذي يحدد كيفية تعبئة داخلية الأشكال في هذا  com.aspose.psd.GraphicsPath .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | وضع التعبئة. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### transform(Matrix transform) {#transform-com.aspose.psd.Matrix-}
```
public void transform(Matrix transform)
```


يطبق التحويل المحدد على الشكل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.psd/matrix) | التحويل المراد تطبيقه. |

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

### warp(PointF[] destPoints, RectangleF srcRect) {#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-}
```
public void warp(PointF[] destPoints, RectangleF srcRect)
```


يطبق تحويل تشويه، معرف بواسطة مستطيل ومتوازي أضلاع، على هذا  com.aspose.psd.graphicsPath .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | مصفوفة من هياكل com.aspose.psd.PointF التي تحدد متوازي أضلاع يتم تحويل المستطيل المحدد بواسطة srcRect إليه. يمكن أن تحتوي المصفوفة على ثلاثة أو أربعة عناصر. إذا احتوت المصفوفة على ثلاثة عناصر، فإن الزاوية السفلية اليمنى للمتوازي أضلاع تُستنتج من النقاط الثلاث الأولى. |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | كائن com.aspose.psd.RectangleF يمثل المستطيل الذي يتم تحويله إلى متوازي الأضلاع المحدد بواسطة destPoints. |

### warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix) {#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-}
```
public void warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix)
```


يطبق تحويل تشويه، معرف بواسطة مستطيل ومتوازي أضلاع، على هذا  com.aspose.psd.graphicsPath .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | مصفوفة من هياكل com.aspose.psd.PointF التي تحدد متوازي أضلاع يتم تحويل المستطيل المحدد بواسطة srcRect إليه. يمكن أن تحتوي المصفوفة على ثلاثة أو أربعة عناصر. إذا احتوت المصفوفة على ثلاثة عناصر، فإن الزاوية السفلية اليمنى للمتوازي أضلاع تُستنتج من النقاط الثلاث الأولى. |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | كائن com.aspose.psd.RectangleF يمثل المستطيل الذي يتم تحويله إلى متوازي الأضلاع المحدد بواسطة destPoints. |
| matrix | [Matrix](../../com.aspose.psd/matrix) | كائن com.aspose.psd.Matrix يحدد تحويلًا هندسيًا لتطبيقه على المسار. |

### warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode) {#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-int-}
```
public void warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode)
```


يطبق تحويل تشويه، معرف بواسطة مستطيل ومتوازي أضلاع، على هذا  com.aspose.psd.graphicsPath .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | مصفوفة من هياكل com.aspose.psd.PointF التي تحدد متوازي أضلاع يتم تحويل المستطيل المحدد بواسطة srcRect إليه. يمكن أن تحتوي المصفوفة على ثلاثة أو أربعة عناصر. إذا احتوت المصفوفة على ثلاثة عناصر، فإن الزاوية السفلية اليمنى للمتوازي أضلاع تُستنتج من النقاط الثلاث الأولى. |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | كائن com.aspose.psd.RectangleF يمثل المستطيل الذي يتم تحويله إلى متوازي الأضلاع المحدد بواسطة destPoints. |
| matrix | [Matrix](../../com.aspose.psd/matrix) | كائن com.aspose.psd.Matrix يحدد تحويلًا هندسيًا لتطبيقه على المسار. |
| warpMode | int | تعداد com.aspose.psd.WarpMode يحدد ما إذا كانت عملية التشويه هذه تستخدم وضع المنظور أو الوضع الثنائي الخطّي. |

### warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode, float flatness) {#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-int-float-}
```
public void warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode, float flatness)
```


يطبق تحويل تشويه، معرف بواسطة مستطيل ومتوازي أضلاع، على هذا  com.aspose.psd.graphicsPath .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | مصفوفة من هياكل com.aspose.psd.PointF التي تحدد متوازي أضلاع يتم تحويل المستطيل المحدد بواسطة srcRect إليه. يمكن أن تحتوي المصفوفة على ثلاثة أو أربعة عناصر. إذا احتوت المصفوفة على ثلاثة عناصر، فإن الزاوية السفلية اليمنى للمتوازي أضلاع تُستنتج من النقاط الثلاث الأولى. |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | كائن com.aspose.psd.RectangleF يمثل المستطيل الذي يتم تحويله إلى متوازي الأضلاع المحدد بواسطة destPoints. |
| matrix | [Matrix](../../com.aspose.psd/matrix) | كائن com.aspose.psd.Matrix يحدد تحويلًا هندسيًا لتطبيقه على المسار. |
| warpMode | int | تعداد com.aspose.psd.WarpMode يحدد ما إذا كانت عملية التشويه هذه تستخدم وضع المنظور أو الوضع الثنائي الخطّي. |
| flatness | float | قيمة من 0 إلى 1 تحدد مدى تسطيح المسار الناتج. لمزيد من المعلومات، راجع طرق com.aspose.psd.GraphicsPath.flatten. |

### widen(Pen pen) {#widen-com.aspose.psd.Pen-}
```
public void widen(Pen pen)
```


يضيف مخططًا إضافيًا إلى المسار.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | كائن com.aspose.psd.Pen يحدد العرض بين المخطط الأصلي للمسار والمخطط الجديد الذي تنشئه هذه الطريقة. |

### widen(Pen pen, Matrix matrix) {#widen-com.aspose.psd.Pen-com.aspose.psd.Matrix-}
```
public void widen(Pen pen, Matrix matrix)
```


يضيف مخططًا إضافيًا إلى  com.aspose.psd.graphicsPath .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | كائن com.aspose.psd.Pen يحدد العرض بين المخطط الأصلي للمسار والمخطط الجديد الذي تنشئه هذه الطريقة. |
| matrix | [Matrix](../../com.aspose.psd/matrix) | كائن com.aspose.psd.Matrix يحدد تحويلًا لتطبيقه على المسار قبل توسيعه. |

### widen(Pen pen, Matrix matrix, float flatness) {#widen-com.aspose.psd.Pen-com.aspose.psd.Matrix-float-}
```
public void widen(Pen pen, Matrix matrix, float flatness)
```


يستبدل هذا  com.aspose.psd.GraphicsPath  بمنحنيات تحيط بالمنطقة التي تُملأ عندما يُرسم هذا المسار بالقلم المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | كائن com.aspose.psd.Pen يحدد العرض بين المخطط الأصلي للمسار والمخطط الجديد الذي تنشئه هذه الطريقة. |
| matrix | [Matrix](../../com.aspose.psd/matrix) | كائن com.aspose.psd.Matrix يحدد تحويلًا لتطبيقه على المسار قبل توسيعه. |
| flatness | float | قيمة تحدد مستوى التسطيح للمنحنيات. |

