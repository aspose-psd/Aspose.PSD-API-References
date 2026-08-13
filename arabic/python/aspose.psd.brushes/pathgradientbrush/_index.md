---
title: "فئة PathGradientBrush"
type: docs
weight: 50
url: /ar/python-net/aspose.psd.brushes/pathgradientbrush/
---

**Summary:** Encapsulates a [Brush](/psd/python-net/aspose.psd/brush/) object with a gradient. This class cannot be inherited.

**Module:** [aspose.psd.brushes](/psd/python-net/aspose.psd.brushes/)

**Full Name:** aspose.psd.brushes.PathGradientBrush

**Inheritance:** PathGradientBrushBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [PathGradientBrush(path)](#PathGradientBrush_path_1) | ينشئ مثيلاً جديداً لفئة [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) بالمسار المحدد. |
| [PathGradientBrush(points)](#PathGradientBrush_points_2) | ينشئ مثيلاً جديداً لفئة [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) بالنقاط المحددة. |
| [PathGradientBrush(points)](#PathGradientBrush_points_3) | ينشئ مثيلاً جديداً لفئة [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) بالنقاط المحددة. |
| [PathGradientBrush(points, wrap_mode)](#PathGradientBrush_points_wrap_mode_4) | ينشئ مثيلاً جديداً لفئة [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) بالنقاط المحددة ووضع الالتفاف. |
| [PathGradientBrush(points, wrap_mode)](#PathGradientBrush_points_wrap_mode_5) | ينشئ مثيلاً جديداً لفئة [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) بالنقاط المحددة ووضع الالتفاف. |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| blend | [Blend](/psd/python-net/aspose.psd/blend) | r/w | يحصل أو يضبط [Blend](/psd/python-net/aspose.psd/blend/) الذي يحدد المواقع والعوامل التي تعرف انخفاضًا مخصصًا للتدرج. |
| center_color | [Color](/psd/python-net/aspose.psd/color) | r/w | يحصل أو يعيّن اللون في مركز تدرج المسار. |
| center_point | [PointF](/psd/python-net/aspose.psd/pointf) | r/w | يحصل أو يضبط نقطة المركز لتدرج المسار. |
| disposed | bool | r | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن قد تم التخلص منه. |
| focus_scales | [PointF](/psd/python-net/aspose.psd/pointf) | r/w | يحصل أو يضبط نقطة التركيز لتلاشي التدرج. |
| graphics_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | r | يحصل على مسار الرسومات الذي بُني عليه هذا الفرش. |
| interpolation_colors | [ColorBlend](/psd/python-net/aspose.psd/colorblend) | r/w | يحصل أو يضبط [ColorBlend](/psd/python-net/aspose.psd/colorblend/) الذي يحدد تدرجًا خطيًا متعدد الألوان. |
| is_transform_changed | bool | r | يحصل على قيمة تشير إلى ما إذا كانت التحويلات قد تغيرت بطريقة ما. على سبيل المثال ضبط مصفوفة التحويل أو<br/>            استدعاء أي من الطرق التي تغير مصفوفة التحويل. تم تقديم الخاصية لضمان التوافق العكسي مع GDI+. |
| opacity | float | r/w | يحصل أو يضبط شفافية الفرشاة. يجب أن تكون القيمة بين 0 و 1. القيمة 0 تعني أن الفرشاة مرئية بالكامل، والقيمة 1 تعني أن الفرشاة معتمة بالكامل. |
| path_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | r | يحصل على نقاط المسار التي بُني عليها هذا الفرش. |
| surround_colors | [Color[]](/psd/python-net/aspose.psd/color) | r/w | يحصل أو يعيّن مصفوفة من الألوان التي تتطابق مع النقاط في المسار الذي يملأه هذا [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/). |
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
| [set_blend_triangular_shape(focus)](#set_blend_triangular_shape_focus_8) | ينشئ تدرجاً بلون مركزي وتلاشي خطي إلى لون محيط واحد. |
| [set_blend_triangular_shape(focus, scale)](#set_blend_triangular_shape_focus_scale_9) | ينشئ تدرجاً بلون مركزي وتلاشي خطي إلى كل لون محيط. |
| [set_sigma_bell_shape(focus)](#set_sigma_bell_shape_focus_10) | ينشئ فرشاة تدرج تغير اللون بدءاً من مركز المسار إلى حدوده الخارجية. الانتقال من لون إلى آخر يعتمد على منحنى على شكل جرس. |
| [set_sigma_bell_shape(focus, scale)](#set_sigma_bell_shape_focus_scale_11) | ينشئ فرشاة تدرج تغير اللون بدءاً من مركز المسار إلى حدوده الخارجية. الانتقال من لون إلى آخر يعتمد على منحنى على شكل جرس. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_12) | ينقل التحويل الهندسي المحلي بالأبعاد المحددة. تضيف هذه الطريقة الإزاحة إلى التحويل في البداية. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_13) | ينقل التحويل الهندسي المحلي بالأبعاد المحددة وفقًا للترتيب المحدد. |


### Constructor: PathGradientBrush(path) {#PathGradientBrush_path_1}


```
 PathGradientBrush(path) 
```

ينشئ مثيلاً جديداً لفئة [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) بالمسار المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) الذي يحدد المنطقة التي يملأها هذا [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/). |

### Constructor: PathGradientBrush(points) {#PathGradientBrush_points_2}


```
 PathGradientBrush(points) 
```

ينشئ مثيلاً جديداً لفئة [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) بالنقاط المحددة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | مصفوفة من هياكل [PointF](/psd/python-net/aspose.psd/pointf/) التي تمثل النقاط التي تشكّل رؤوس المسار. |

### Constructor: PathGradientBrush(points) {#PathGradientBrush_points_3}


```
 PathGradientBrush(points) 
```

ينشئ مثيلاً جديداً لفئة [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) بالنقاط المحددة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| points | [Point[]](/psd/python-net/aspose.psd/point) | مصفوفة من هياكل [PointF](/psd/python-net/aspose.psd/pointf/) التي تمثل النقاط التي تشكّل رؤوس المسار. |

### Constructor: PathGradientBrush(points, wrap_mode) {#PathGradientBrush_points_wrap_mode_4}


```
 PathGradientBrush(points, wrap_mode) 
```

ينشئ مثيلاً جديداً لفئة [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) بالنقاط المحددة ووضع الالتفاف.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | مصفوفة من هياكل [PointF](/psd/python-net/aspose.psd/pointf/) التي تمثل النقاط التي تشكّل رؤوس المسار. |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | [WrapMode](/psd/python-net/aspose.psd/wrapmode/) يحدد كيفية تكرار التعبئات المرسومة بهذه [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/). |

### Constructor: PathGradientBrush(points, wrap_mode) {#PathGradientBrush_points_wrap_mode_5}


```
 PathGradientBrush(points, wrap_mode) 
```

ينشئ مثيلاً جديداً لفئة [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) بالنقاط المحددة ووضع الالتفاف.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| points | [Point[]](/psd/python-net/aspose.psd/point) | مصفوفة من هياكل [PointF](/psd/python-net/aspose.psd/pointf/) التي تمثل النقاط التي تشكّل رؤوس المسار. |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | [WrapMode](/psd/python-net/aspose.psd/wrapmode/) يحدد كيفية تكرار التعبئات المرسومة بهذه [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/). |

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

### Method: set_blend_triangular_shape(focus) {#set_blend_triangular_shape_focus_8}


```
 set_blend_triangular_shape(focus) 
```

ينشئ تدرجاً بلون مركزي وتلاشي خطي إلى لون محيط واحد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| التركيز | float | قيمة من 0 إلى 1 تحدد أين، على أي شعاع من مركز المسار إلى حدوده، سيكون اللون المركزي بأعلى شدة له. قيمة 1 (الافتراضية) تضع أعلى شدة في مركز المسار. |

### Method: set_blend_triangular_shape(focus, scale) {#set_blend_triangular_shape_focus_scale_9}


```
 set_blend_triangular_shape(focus, scale) 
```

ينشئ تدرجاً بلون مركزي وتلاشي خطي إلى كل لون محيط.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| التركيز | float | قيمة من 0 إلى 1 تحدد أين، على أي شعاع من مركز المسار إلى حدوده، سيكون اللون المركزي بأعلى شدة له. قيمة 1 (الافتراضية) تضع أعلى شدة في مركز المسار. |
| scale | float | قيمة من 0 إلى 1 تحدد أقصى شدة للون المركزي الذي يختلط بلون الحد. قيمة 1 تسبب أعلى شدة ممكنة للون المركزي، وهي القيمة الافتراضية. |

### Method: set_sigma_bell_shape(focus) {#set_sigma_bell_shape_focus_10}


```
 set_sigma_bell_shape(focus) 
```

ينشئ فرشاة تدرج تغير اللون بدءاً من مركز المسار إلى حدوده الخارجية. الانتقال من لون إلى آخر يعتمد على منحنى على شكل جرس.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| التركيز | float | قيمة من 0 إلى 1 تحدد أين، على أي شعاع من مركز المسار إلى حدوده، سيكون اللون المركزي بأعلى شدة له. قيمة 1 (الافتراضية) تضع أعلى شدة في مركز المسار. |

### Method: set_sigma_bell_shape(focus, scale) {#set_sigma_bell_shape_focus_scale_11}


```
 set_sigma_bell_shape(focus, scale) 
```

ينشئ فرشاة تدرج تغير اللون بدءاً من مركز المسار إلى حدوده الخارجية. الانتقال من لون إلى آخر يعتمد على منحنى على شكل جرس.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| التركيز | float | قيمة من 0 إلى 1 تحدد أين، على أي شعاع من مركز المسار إلى حدوده، سيكون اللون المركزي بأعلى شدة له. قيمة 1 (الافتراضية) تضع أعلى شدة في مركز المسار. |
| scale | float | قيمة من 0 إلى 1 تحدد أقصى شدة للون المركزي الذي يختلط بلون الحد. قيمة 1 تسبب أعلى شدة ممكنة للون المركزي، وهي القيمة الافتراضية. |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_12}


```
 translate_transform(dx, dy) 
```

ينقل التحويل الهندسي المحلي بالأبعاد المحددة. تضيف هذه الطريقة الإزاحة إلى التحويل في البداية.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| dx | float | قيمة الإزاحة في الاتجاه السيني. |
| dy | float | قيمة الترجمة في y. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_13}


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

