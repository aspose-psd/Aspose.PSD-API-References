---
title: "فئة LinearMulticolorGradientBrush"
type: docs
weight: 40
url: /ar/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/
---

**Summary:** Represents a [Brush](/psd/python-net/aspose.psd/brush/) with linear gradient defined by multiple colors and appropriate positions. This class cannot be inherited.

**Module:** [aspose.psd.brushes](/psd/python-net/aspose.psd.brushes/)

**Full Name:** aspose.psd.brushes.LinearMulticolorGradientBrush

**Inheritance:** LinearGradientBrushBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [LinearMulticolorGradientBrush()](#LinearMulticolorGradientBrush__1) | ينشئ مثيلاً جديدًا للفئة [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/) مع المعلمات الافتراضية.<br/>            اللون الابتدائي هو الأسود، واللون النهائي هو الأبيض، والزاوية 45 درجة والمستطيل يقع في (0,0) بحجم (1,1). |
| [LinearMulticolorGradientBrush(point1, point2)](#LinearMulticolorGradientBrush_point1_point2_2) | ينشئ مثيلاً جديدًا للفئة [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/) مع النقاط المحددة. |
| [LinearMulticolorGradientBrush(point1, point2)](#LinearMulticolorGradientBrush_point1_point2_3) | ينشئ مثيلاً جديدًا للفئة [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/) مع النقاط المحددة. |
| [LinearMulticolorGradientBrush(rect, angle)](#LinearMulticolorGradientBrush_rect_angle_4) | ينشئ مثيلاً جديدًا للفئة [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/) استنادًا إلى مستطيل وزاوية توجيه. |
| [LinearMulticolorGradientBrush(rect, angle)](#LinearMulticolorGradientBrush_rect_angle_5) | ينشئ مثيلاً جديدًا للفئة [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/) استنادًا إلى مستطيل وزاوية توجيه. |
| [LinearMulticolorGradientBrush(rect, angle, is_angle_scalable)](#LinearMulticolorGradientBrush_rect_angle_is_angle_scalable_6) | ينشئ مثيلاً جديدًا للفئة [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/) استنادًا إلى مستطيل وزاوية توجيه. |
| [LinearMulticolorGradientBrush(rect, angle, is_angle_scalable)](#LinearMulticolorGradientBrush_rect_angle_is_angle_scalable_7) | ينشئ مثيلاً جديدًا للفئة [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/) استنادًا إلى مستطيل وزاوية توجيه. |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| الزاوية | float | r/w | يحصل أو يضبط زاوية التدرج. |
| disposed | bool | r | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن قد تم التخلص منه. |
| gamma_correction | bool | r/w | يحصل أو يضبط قيمة تشير إلى ما إذا كان تصحيح غاما مفعلاً لهذا [LinearGradientBrushBase](/psd/python-net/aspose.psd.brushes/lineargradientbrushbase/). |
| interpolation_colors | [ColorBlend](/psd/python-net/aspose.psd/colorblend) | r/w | يحصل أو يضبط [ColorBlend](/psd/python-net/aspose.psd/colorblend/) الذي يحدد تدرجًا خطيًا متعدد الألوان. |
| is_angle_scalable | bool | r/w | يحصل أو يضبط قيمة تشير إلى ما إذا كان [LinearGradientBrushBase.angle](/psd/python-net/aspose.psd.brushes/lineargradientbrushbase/) يتغير أثناء التحويلات مع هذا [LinearGradientBrushBase](/psd/python-net/aspose.psd.brushes/lineargradientbrushbase/). |
| is_transform_changed | bool | r | يحصل على قيمة تشير إلى ما إذا كانت التحويلات قد تغيرت بطريقة ما. على سبيل المثال ضبط مصفوفة التحويل أو<br/>            استدعاء أي من الطرق التي تغير مصفوفة التحويل. تم تقديم الخاصية لضمان التوافق العكسي مع GDI+. |
| opacity | float | r/w | يحصل أو يضبط شفافية الفرشاة. يجب أن تكون القيمة بين 0 و 1. القيمة 0 تعني أن الفرشاة مرئية بالكامل، والقيمة 1 تعني أن الفرشاة معتمة بالكامل. |
| rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r/w | يحصل أو يضبط منطقة مستطيلة تحدد نقاط البداية والنهاية للتدرج. |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | r/w | يحصل أو يضبط نسخة من [Matrix](/psd/python-net/aspose.psd/matrix/) التي تحدد تحويلًا هندسيًا محليًا لهذا [TransformBrush](/psd/python-net/aspose.psd.brushes/transformbrush/). |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | r/w | يحصل أو يضبط تعداد [WrapMode](/psd/python-net/aspose.psd/wrapmode/) الذي يشير إلى وضع الالتفاف لهذا [TransformBrush](/psd/python-net/aspose.psd.brushes/transformbrush/). |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [deep_clone()](#deep_clone__1) | ينشئ نسخة عميقة جديدة من [Brush](/psd/python-net/aspose.psd/brush/). |
| [multiply_transform(matrix)](#multiply_transform_matrix_2) | يضرب الـ [Matrix](/psd/python-net/aspose.psd/matrix/) الذي يمثل التحويل الهندسي المحلي لهذا [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) بالمصفوفة المحددة [Matrix](/psd/python-net/aspose.psd/matrix/) عن طريق إلحاق المصفوفة المحددة [Matrix](/psd/python-net/aspose.psd/matrix/) في المقدمة. |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_3) | يضرب الـ [Matrix](/psd/python-net/aspose.psd/matrix/) الذي يمثل التحويل الهندسي المحلي لهذا [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) بالمصفوفة المحددة [Matrix](/psd/python-net/aspose.psd/matrix/) في الترتيب المحدد. |
| reset_transform() | يعيد تعيين خاصية [TransformBrush.transform](/psd/python-net/aspose.psd.brushes/transformbrush/) إلى الهوية. |
| [rotate_transform(angle)](#rotate_transform_angle_4) | يدور التحويل الهندسي المحلي بالمقدار المحدد. تضيف هذه الطريقة الدوران إلى التحويل في البداية. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_5) | يدور التحويل الهندسي المحلي بالمقدار المحدد وفقًا للترتيب المحدد. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_6) | يقوم بتكبير التحويل الهندسي المحلي بالمقادير المحددة. تضيف هذه الطريقة مصفوفة التكبير إلى التحويل في البداية. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_7) | يقوم بتكبير التحويل الهندسي المحلي بالمقادير المحددة وفقًا للترتيب المحدد. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_8) | ينقل التحويل الهندسي المحلي بالأبعاد المحددة. تضيف هذه الطريقة الإزاحة إلى التحويل في البداية. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_9) | ينقل التحويل الهندسي المحلي بالأبعاد المحددة وفقًا للترتيب المحدد. |


### Constructor: LinearMulticolorGradientBrush() {#LinearMulticolorGradientBrush__1}


```
 LinearMulticolorGradientBrush() 
```

ينشئ مثيلاً جديدًا للفئة [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/) مع المعلمات الافتراضية.<br/>            اللون الابتدائي هو الأسود، واللون النهائي هو الأبيض، والزاوية 45 درجة والمستطيل يقع في (0,0) بحجم (1,1).

### Constructor: LinearMulticolorGradientBrush(point1, point2) {#LinearMulticolorGradientBrush_point1_point2_2}


```
 LinearMulticolorGradientBrush(point1, point2) 
```

ينشئ مثيلاً جديدًا للفئة [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/) مع النقاط المحددة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| point1 | [Point](/psd/python-net/aspose.psd/point) | بنية [Point](/psd/python-net/aspose.psd/point/) تمثل نقطة البداية للتدرج الخطي. |
| point2 | [Point](/psd/python-net/aspose.psd/point) | بنية [Point](/psd/python-net/aspose.psd/point/) تمثل نقطة النهاية للتدرج الخطي. |

### Constructor: LinearMulticolorGradientBrush(point1, point2) {#LinearMulticolorGradientBrush_point1_point2_3}


```
 LinearMulticolorGradientBrush(point1, point2) 
```

ينشئ مثيلاً جديدًا للفئة [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/) مع النقاط المحددة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| point1 | [PointF](/psd/python-net/aspose.psd/pointf) | بنية [Point](/psd/python-net/aspose.psd/point/) تمثل نقطة البداية للتدرج الخطي. |
| point2 | [PointF](/psd/python-net/aspose.psd/pointf) | بنية [Point](/psd/python-net/aspose.psd/point/) تمثل نقطة النهاية للتدرج الخطي. |

### Constructor: LinearMulticolorGradientBrush(rect, angle) {#LinearMulticolorGradientBrush_rect_angle_4}


```
 LinearMulticolorGradientBrush(rect, angle) 
```

ينشئ مثيلاً جديدًا للفئة [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/) استنادًا إلى مستطيل وزاوية توجيه.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | بنية [RectangleF](/psd/python-net/aspose.psd/rectanglef/) تحدد حدود التدرج الخطي. |
| الزاوية | float | الزاوية، مقاسة بالدرجات في اتجاه عقارب الساعة من المحور السيني، لخط توجيه التدرج. |

### Constructor: LinearMulticolorGradientBrush(rect, angle) {#LinearMulticolorGradientBrush_rect_angle_5}


```
 LinearMulticolorGradientBrush(rect, angle) 
```

ينشئ مثيلاً جديدًا للفئة [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/) استنادًا إلى مستطيل وزاوية توجيه.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | بنية [RectangleF](/psd/python-net/aspose.psd/rectanglef/) تحدد حدود التدرج الخطي. |
| الزاوية | float | الزاوية، مقاسة بالدرجات في اتجاه عقارب الساعة من المحور السيني، لخط توجيه التدرج. |

### Constructor: LinearMulticolorGradientBrush(rect, angle, is_angle_scalable) {#LinearMulticolorGradientBrush_rect_angle_is_angle_scalable_6}


```
 LinearMulticolorGradientBrush(rect, angle, is_angle_scalable) 
```

ينشئ مثيلاً جديدًا للفئة [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/) استنادًا إلى مستطيل وزاوية توجيه.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | بنية [RectangleF](/psd/python-net/aspose.psd/rectanglef/) تحدد حدود التدرج الخطي. |
| الزاوية | float | الزاوية، مقاسة بالدرجات في اتجاه عقارب الساعة من المحور السيني، لخط توجيه التدرج. |
| is_angle_scalable | bool | إذا تم تعيينه إلى <c>true</c> يتم تغيير الزاوية أثناء التحويلات باستخدام هذا [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/). |

### Constructor: LinearMulticolorGradientBrush(rect, angle, is_angle_scalable) {#LinearMulticolorGradientBrush_rect_angle_is_angle_scalable_7}


```
 LinearMulticolorGradientBrush(rect, angle, is_angle_scalable) 
```

ينشئ مثيلاً جديدًا للفئة [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/) استنادًا إلى مستطيل وزاوية توجيه.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | بنية [RectangleF](/psd/python-net/aspose.psd/rectanglef/) تحدد حدود التدرج الخطي. |
| الزاوية | float | الزاوية، مقاسة بالدرجات في اتجاه عقارب الساعة من المحور السيني، لخط توجيه التدرج. |
| is_angle_scalable | bool | إذا تم تعيينه إلى <c>true</c> يتم تغيير الزاوية أثناء التحويلات باستخدام هذا [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/). |

### Method: deep_clone() {#deep_clone__1}


```
 deep_clone() 
```

ينشئ نسخة عميقة جديدة من [Brush](/psd/python-net/aspose.psd/brush/).

**Returns**

| النوع | الوصف |
| :- | :- |
| [Brush](/psd/python-net/aspose.psd/brush) | فرشاة [Brush](/psd/python-net/aspose.psd/brush/) جديدة هي نسخة عميقة من هذا الكائن من [Brush](/psd/python-net/aspose.psd/brush/). |


### Method: multiply_transform(matrix) {#multiply_transform_matrix_2}


```
 multiply_transform(matrix) 
```

يضرب الـ [Matrix](/psd/python-net/aspose.psd/matrix/) الذي يمثل التحويل الهندسي المحلي لهذا [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) بالمصفوفة المحددة [Matrix](/psd/python-net/aspose.psd/matrix/) عن طريق إلحاق المصفوفة المحددة [Matrix](/psd/python-net/aspose.psd/matrix/) في المقدمة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | [Matrix](/psd/python-net/aspose.psd/matrix/) التي يُضرب بها التحويل الهندسي. |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_3}


```
 multiply_transform(matrix, order) 
```

يضرب الـ [Matrix](/psd/python-net/aspose.psd/matrix/) الذي يمثل التحويل الهندسي المحلي لهذا [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) بالمصفوفة المحددة [Matrix](/psd/python-net/aspose.psd/matrix/) في الترتيب المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | [Matrix](/psd/python-net/aspose.psd/matrix/) التي يُضرب بها التحويل الهندسي. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) يحدد الترتيب الذي تُضرب فيه المصفوفتان. |

### Method: rotate_transform(angle) {#rotate_transform_angle_4}


```
 rotate_transform(angle) 
```

يدور التحويل الهندسي المحلي بالمقدار المحدد. تضيف هذه الطريقة الدوران إلى التحويل في البداية.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| الزاوية | float | زاوية الدوران. |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_5}


```
 rotate_transform(angle, order) 
```

يدور التحويل الهندسي المحلي بالمقدار المحدد وفقًا للترتيب المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| الزاوية | float | زاوية الدوران. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) يحدد ما إذا كان يجب إلحاق أو إلحاق مسبق لمصفوفة الدوران. |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_6}


```
 scale_transform(sx, sy) 
```

يقوم بتكبير التحويل الهندسي المحلي بالمقادير المحددة. تضيف هذه الطريقة مصفوفة التكبير إلى التحويل في البداية.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| sx | float | القيمة التي يُكَبَّر بها التحويل في اتجاه المحور السيني. |
| sy | float | القيمة التي يُكَبَّر بها التحويل في اتجاه المحور الصادي. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_7}


```
 scale_transform(sx, sy, order) 
```

يقوم بتكبير التحويل الهندسي المحلي بالمقادير المحددة وفقًا للترتيب المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| sx | float | القيمة التي يُكَبَّر بها التحويل في اتجاه المحور السيني. |
| sy | float | القيمة التي يُكَبَّر بها التحويل في اتجاه المحور الصادي. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) يحدد ما إذا كان يجب إلحاق أو إلحاق مسبق لمصفوفة التكبير. |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_8}


```
 translate_transform(dx, dy) 
```

ينقل التحويل الهندسي المحلي بالأبعاد المحددة. تضيف هذه الطريقة الإزاحة إلى التحويل في البداية.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| dx | float | قيمة الإزاحة في الاتجاه السيني. |
| dy | float | قيمة الترجمة في y. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_9}


```
 translate_transform(dx, dy, order) 
```

ينقل التحويل الهندسي المحلي بالأبعاد المحددة وفقًا للترتيب المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| dx | float | قيمة الإزاحة في الاتجاه السيني. |
| dy | float | قيمة الترجمة في y. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | الترتيب (إضافة مسبقة أو لاحقة) الذي يتم به تطبيق الترجمة. |

