---
title: "GraphicsPath فئة"
type: docs
weight: 1570
url: /ar/python-net/aspose.psd/graphicspath/
---

**Summary:** Represents a series of connected lines and curves. This class cannot be inherited.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.GraphicsPath

**Inheritance:** ObjectWithBounds

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [GraphicsPath()](#GraphicsPath__1) | يُهيئ نسخة جديدة من الفئة [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [GraphicsPath(figures)](#GraphicsPath_figures_2) | يُهيئ نسخة جديدة من الفئة [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [GraphicsPath(figures, fill_mode)](#GraphicsPath_figures_fill_mode_3) | يُهيئ نسخة جديدة من الفئة [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [GraphicsPath(fill_mode)](#GraphicsPath_fill_mode_4) | يُهيئ نسخة جديدة من الفئة [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | يحصل أو يضبط حدود الكائن. |
| figures | [Figure[]](/psd/python-net/aspose.psd/figure) | r | الحصول على أشكال المسار. |
| fill_mode | [FillMode](/psd/python-net/aspose.psd/fillmode) | r/w | يحصل أو يضبط تعداد [FillMode](/psd/python-net/aspose.psd/fillmode/) الذي يحدد كيفية تعبئة داخل الأشكال في هذا [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [add_figure(figure)](#add_figure_figure_1) | يضيف شكلاً جديدًا. |
| [add_figures(figures)](#add_figures_figures_2) | يضيف أشكالًا جديدة. |
| [add_path(adding_path)](#add_path_adding_path_3) | يضيف [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) المحدد إلى هذا المسار. |
| [add_path(adding_path, connect)](#add_path_adding_path_connect_4) | يضيف [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) المحدد إلى هذا المسار. |
| [deep_clone()](#deep_clone__5) | ينفّذ استنساخًا عميقًا لهذا مسار الرسومات. |
| flatten() | يحوّل كل منحنى في هذا المسار إلى سلسلة من المقاطع الخطية المتصلة. |
| [flatten(matrix)](#flatten_matrix_6) | يطبق التحويل المحدد ثم يحوّل كل منحنى في هذا [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) إلى سلسلة من المقاطع الخطية المتصلة. |
| [flatten(matrix, flatness)](#flatten_matrix_flatness_7) | يحوّل كل منحنى في هذا [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) إلى سلسلة من المقاطع الخطية المتصلة. |
| [get_bounds(matrix)](#get_bounds_matrix_8) | يحصل على حدود الكائن. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_9) | يحصل على حدود الكائن. |
| [is_outline_visible(point, pen)](#is_outline_visible_point_pen_10) | يحدد ما إذا كانت النقطة المحددة موجودة داخل (تحت) مخطط هذا [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) عند رسمه باستخدام الـ[Pen](/psd/python-net/aspose.psd/pen/) المحدد. |
| [is_outline_visible(point, pen)](#is_outline_visible_point_pen_11) | يحدد ما إذا كانت النقطة المحددة موجودة داخل (تحت) مخطط هذا [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) عند رسمه باستخدام الـ[Pen](/psd/python-net/aspose.psd/pen/) المحدد. |
| [is_outline_visible(pt, pen, graphics)](#is_outline_visible_pt_pen_graphics_12) | يحدد ما إذا كانت النقطة المحددة موجودة داخل (تحت) مخطط هذا [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) عند رسمه باستخدام الـ[Pen](/psd/python-net/aspose.psd/pen/) وباستخدام الـ[Graphics](/psd/python-net/aspose.psd/graphics/) المحدد. |
| [is_outline_visible(pt, pen, graphics)](#is_outline_visible_pt_pen_graphics_13) | يحدد ما إذا كانت النقطة المحددة موجودة داخل (تحت) مخطط هذا [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) عند رسمه باستخدام الـ[Pen](/psd/python-net/aspose.psd/pen/) وباستخدام الـ[Graphics](/psd/python-net/aspose.psd/graphics/) المحدد. |
| [is_outline_visible(x, y, pen)](#is_outline_visible_x_y_pen_14) | يحدد ما إذا كانت النقطة المحددة موجودة داخل (تحت) مخطط هذا [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) عند رسمه باستخدام الـ[Pen](/psd/python-net/aspose.psd/pen/) المحدد. |
| [is_outline_visible(x, y, pen)](#is_outline_visible_x_y_pen_15) | يحدد ما إذا كانت النقطة المحددة موجودة داخل (تحت) مخطط هذا [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) عند رسمه باستخدام الـ[Pen](/psd/python-net/aspose.psd/pen/) المحدد. |
| [is_outline_visible(x, y, pen, graphics)](#is_outline_visible_x_y_pen_graphics_16) | يحدد ما إذا كانت النقطة المحددة موجودة داخل (تحت) مخطط هذا [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) عند رسمه باستخدام الـ[Pen](/psd/python-net/aspose.psd/pen/) وباستخدام الـ[Graphics](/psd/python-net/aspose.psd/graphics/) المحدد. |
| [is_outline_visible(x, y, pen, graphics)](#is_outline_visible_x_y_pen_graphics_17) | يحدد ما إذا كانت النقطة المحددة موجودة داخل (تحت) مخطط هذا [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) عند رسمه باستخدام الـ[Pen](/psd/python-net/aspose.psd/pen/) وباستخدام الـ[Graphics](/psd/python-net/aspose.psd/graphics/) المحدد. |
| [is_visible(point)](#is_visible_point_18) | يحدد ما إذا كانت النقطة المحددة موجودة داخل هذا [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [is_visible(point)](#is_visible_point_19) | يحدد ما إذا كانت النقطة المحددة موجودة داخل هذا [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [is_visible(pt, graphics)](#is_visible_pt_graphics_20) | يحدد ما إذا كانت النقطة المحددة موجودة داخل هذا [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [is_visible(pt, graphics)](#is_visible_pt_graphics_21) | يحدد ما إذا كانت النقطة المحددة موجودة داخل هذا [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [is_visible(x, y)](#is_visible_x_y_22) | يحدد ما إذا كانت النقطة المحددة موجودة داخل هذا [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [is_visible(x, y)](#is_visible_x_y_23) | يحدد ما إذا كانت النقطة المحددة موجودة داخل هذا [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [is_visible(x, y, graphics)](#is_visible_x_y_graphics_24) | يحدد ما إذا كانت النقطة المحددة موجودة داخل هذا [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) في منطقة القص المرئية للـ[Graphics](/psd/python-net/aspose.psd/graphics/) المحدد. |
| [is_visible(x, y, graphics)](#is_visible_x_y_graphics_25) | يحدد ما إذا كانت النقطة المحددة موجودة داخل هذا [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) في منطقة القص المرئية للـ[Graphics](/psd/python-net/aspose.psd/graphics/) المحدد. |
| [remove_figure(figure)](#remove_figure_figure_26) | يزيل شكلاً. |
| [remove_figures(figures)](#remove_figures_figures_27) | يزيل أشكالًا. |
| reset() | يفرغ مسار الرسومات ويضبط [FillMode](/psd/python-net/aspose.psd/fillmode/) إلى [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/). |
| reverse() | يعكس ترتيب الأشكال، والرسومات، والنقاط في كل شكل من هذا [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [transform(transform)](#transform_transform_28) | يطبق التحويل المحدد على الشكل. |
| [warp(dest_points, src_rect)](#warp_dest_points_src_rect_29) | يطبق تحويل تشويه، يُعرّف بواسطة مستطيل ومتوازي أضلاع، على هذا [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [warp(dest_points, src_rect, matrix)](#warp_dest_points_src_rect_matrix_30) | يطبق تحويل تشويه، يُعرّف بواسطة مستطيل ومتوازي أضلاع، على هذا [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [warp(dest_points, src_rect, matrix, warp_mode)](#warp_dest_points_src_rect_matrix_warp_mode_31) | يطبق تحويل تشويه، يُعرّف بواسطة مستطيل ومتوازي أضلاع، على هذا [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [warp(dest_points, src_rect, matrix, warp_mode, flatness)](#warp_dest_points_src_rect_matrix_warp_mode_flatness_32) | يطبق تحويل تشويه، يُعرّف بواسطة مستطيل ومتوازي أضلاع، على هذا [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [widen(pen)](#widen_pen_33) | يضيف مخططًا إضافيًا إلى المسار. |
| [widen(pen, matrix)](#widen_pen_matrix_34) | يضيف مخططًا إضافيًا إلى الـ[GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [widen(pen, matrix, flatness)](#widen_pen_matrix_flatness_35) | يستبدل هذا [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) بمنحنيات تحيط بالمنطقة التي تُملأ عندما يُرسم هذا المسار باستخدام القلم المحدد. |


### Constructor: GraphicsPath() {#GraphicsPath__1}


```
 GraphicsPath() 
```

يُهيئ نسخة جديدة من الفئة [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

### Constructor: GraphicsPath(figures) {#GraphicsPath_figures_2}


```
 GraphicsPath(figures) 
```

يُهيئ نسخة جديدة من الفئة [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| figures | [Figure[]](/psd/python-net/aspose.psd/figure) | الأشكال للتهيئة منها. |

### Constructor: GraphicsPath(figures, fill_mode) {#GraphicsPath_figures_fill_mode_3}


```
 GraphicsPath(figures, fill_mode) 
```

يُهيئ نسخة جديدة من الفئة [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| figures | [Figure[]](/psd/python-net/aspose.psd/figure) | الأشكال للتهيئة منها. |
| fill_mode | [FillMode](/psd/python-net/aspose.psd/fillmode) | وضع التعبئة. |

### Constructor: GraphicsPath(fill_mode) {#GraphicsPath_fill_mode_4}


```
 GraphicsPath(fill_mode) 
```

يُهيئ نسخة جديدة من الفئة [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| fill_mode | [FillMode](/psd/python-net/aspose.psd/fillmode) | وضع التعبئة. |

### Method: add_figure(figure) {#add_figure_figure_1}


```
 add_figure(figure) 
```

يضيف شكلاً جديدًا.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| figure | [Figure](/psd/python-net/aspose.psd/figure) | الشكل لإضافته. |

### Method: add_figures(figures) {#add_figures_figures_2}


```
 add_figures(figures) 
```

يضيف أشكالًا جديدة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| figures | [Figure[]](/psd/python-net/aspose.psd/figure) | الأشكال للإضافة. |

### Method: add_path(adding_path) {#add_path_adding_path_3}


```
 add_path(adding_path) 
```

يضيف [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) المحدد إلى هذا المسار.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| adding_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | مسار [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) للإضافة. |

### Method: add_path(adding_path, connect) {#add_path_adding_path_connect_4}


```
 add_path(adding_path, connect) 
```

يضيف [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) المحدد إلى هذا المسار.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| adding_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | مسار [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) للإضافة. |
| اتصال | bool | قيمة منطقية تحدد ما إذا كان الشكل الأول في المسار المضاف جزءًا من الشكل الأخير في هذا المسار. القيمة true تحدد أن الشكل الأول في المسار المضاف جزء من الشكل الأخير في هذا المسار. القيمة false تحدد أن الشكل الأول في المسار المضاف منفصل عن الشكل الأخير في هذا المسار. |

### Method: deep_clone() {#deep_clone__5}


```
 deep_clone() 
```

ينفّذ استنساخًا عميقًا لهذا مسار الرسومات.

**Returns**

| النوع | الوصف |
| :- | :- |
| [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | نسخة عميقة من مسار الرسومات. |


### Method: flatten(matrix) {#flatten_matrix_6}


```
 flatten(matrix) 
```

يطبق التحويل المحدد ثم يحوّل كل منحنى في هذا [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) إلى سلسلة من المقاطع الخطية المتصلة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | مصفوفة [Matrix](/psd/python-net/aspose.psd/matrix/) يتم استخدامها لتحويل هذا [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) قبل التسوية. |

### Method: flatten(matrix, flatness) {#flatten_matrix_flatness_7}


```
 flatten(matrix, flatness) 
```

يحوّل كل منحنى في هذا [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) إلى سلسلة من المقاطع الخطية المتصلة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | مصفوفة [Matrix](/psd/python-net/aspose.psd/matrix/) يتم استخدامها لتحويل هذا [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) قبل التسوية. |
| السطحية | float | يحدد الحد الأقصى للخطأ المسموح بين المنحنى وتقريبه المسطح. القيمة الافتراضية هي 0.25. تقليل قيمة السطحية سيزيد عدد مقاطع الخط في التقريب. |

### Method: get_bounds(matrix) {#get_bounds_matrix_8}


```
 get_bounds(matrix) 
```

يحصل على حدود الكائن.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | سيتم حساب المصفوفة التي ستُطبق قبل الحدود. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | حدود الكائن المقدرة. |


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_9}


```
 get_bounds(matrix, pen) 
```

يحصل على حدود الكائن.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | سيتم حساب المصفوفة التي ستُطبق قبل الحدود. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | القلم المستخدم للكائن. يمكن أن يؤثر ذلك على حجم حدود الكائن. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | حدود الكائن المقدرة. |


### Method: is_outline_visible(point, pen) {#is_outline_visible_point_pen_10}


```
 is_outline_visible(point, pen) 
```

يحدد ما إذا كانت النقطة المحددة موجودة داخل (تحت) مخطط هذا [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) عند رسمه باستخدام الـ[Pen](/psd/python-net/aspose.psd/pen/) المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | نقطة [PointF](/psd/python-net/aspose.psd/pointf/) تحدد الموقع للاختبار. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | قلم [Pen](/psd/python-net/aspose.psd/pen/) للاختبار. |

**Returns**

| النوع | الوصف |
| :- | :- |
| bool | ترجع هذه الطريقة true إذا كانت النقطة المحددة موجودة داخل حدود هذا [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) عند رسمها بالقلم المحدد [Pen](/psd/python-net/aspose.psd/pen/); وإلا false. |


### Method: is_outline_visible(point, pen) {#is_outline_visible_point_pen_11}


```
 is_outline_visible(point, pen) 
```

يحدد ما إذا كانت النقطة المحددة موجودة داخل (تحت) مخطط هذا [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) عند رسمه باستخدام الـ[Pen](/psd/python-net/aspose.psd/pen/) المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | نقطة [PointF](/psd/python-net/aspose.psd/pointf/) تحدد الموقع للاختبار. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | قلم [Pen](/psd/python-net/aspose.psd/pen/) للاختبار. |

**Returns**

| النوع | الوصف |
| :- | :- |
| bool | ترجع هذه الطريقة true إذا كانت النقطة المحددة موجودة داخل حدود هذا [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) عند رسمها بالقلم المحدد [Pen](/psd/python-net/aspose.psd/pen/); وإلا false. |


### Method: is_outline_visible(pt, pen, graphics) {#is_outline_visible_pt_pen_graphics_12}


```
 is_outline_visible(pt, pen, graphics) 
```

يحدد ما إذا كانت النقطة المحددة موجودة داخل (تحت) مخطط هذا [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) عند رسمه باستخدام الـ[Pen](/psd/python-net/aspose.psd/pen/) وباستخدام الـ[Graphics](/psd/python-net/aspose.psd/graphics/) المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| pt | [PointF](/psd/python-net/aspose.psd/pointf) | نقطة [PointF](/psd/python-net/aspose.psd/pointf/) تحدد الموقع للاختبار. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | قلم [Pen](/psd/python-net/aspose.psd/pen/) للاختبار. |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | الـ [Graphics](/psd/python-net/aspose.psd/graphics/) لاختبار الرؤية. |

**Returns**

| النوع | الوصف |
| :- | :- |
| bool | ترجع هذه الطريقة true إذا كانت النقطة المحددة موجودة داخل (تحت) حدود هذا [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) كما تم رسمها بالقلم المحدد [Pen](/psd/python-net/aspose.psd/pen/); وإلا false. |


### Method: is_outline_visible(pt, pen, graphics) {#is_outline_visible_pt_pen_graphics_13}


```
 is_outline_visible(pt, pen, graphics) 
```

يحدد ما إذا كانت النقطة المحددة موجودة داخل (تحت) مخطط هذا [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) عند رسمه باستخدام الـ[Pen](/psd/python-net/aspose.psd/pen/) وباستخدام الـ[Graphics](/psd/python-net/aspose.psd/graphics/) المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| pt | [Point](/psd/python-net/aspose.psd/point) | نقطة [PointF](/psd/python-net/aspose.psd/pointf/) تحدد الموقع للاختبار. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | قلم [Pen](/psd/python-net/aspose.psd/pen/) للاختبار. |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | الـ [Graphics](/psd/python-net/aspose.psd/graphics/) لاختبار الرؤية. |

**Returns**

| النوع | الوصف |
| :- | :- |
| bool | ترجع هذه الطريقة true إذا كانت النقطة المحددة موجودة داخل (تحت) حدود هذا [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) كما تم رسمها بالقلم المحدد [Pen](/psd/python-net/aspose.psd/pen/); وإلا false. |


### Method: is_outline_visible(x, y, pen) {#is_outline_visible_x_y_pen_14}


```
 is_outline_visible(x, y, pen) 
```

يحدد ما إذا كانت النقطة المحددة موجودة داخل (تحت) مخطط هذا [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) عند رسمه باستخدام الـ[Pen](/psd/python-net/aspose.psd/pen/) المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| x | float | الإحداثي السيني للنقطة المراد اختبارها. |
| y | float | الإحداثي الصادي للنقطة المراد اختبارها. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | قلم [Pen](/psd/python-net/aspose.psd/pen/) للاختبار. |

**Returns**

| النوع | الوصف |
| :- | :- |
| bool | ترجع هذه الطريقة true إذا كانت النقطة المحددة موجودة داخل حدود هذا [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) عند رسمها بالقلم المحدد [Pen](/psd/python-net/aspose.psd/pen/); وإلا false. |


### Method: is_outline_visible(x, y, pen) {#is_outline_visible_x_y_pen_15}


```
 is_outline_visible(x, y, pen) 
```

يحدد ما إذا كانت النقطة المحددة موجودة داخل (تحت) مخطط هذا [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) عند رسمه باستخدام الـ[Pen](/psd/python-net/aspose.psd/pen/) المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| x | int | الإحداثي السيني للنقطة المراد اختبارها. |
| y | int | الإحداثي الصادي للنقطة المراد اختبارها. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | قلم [Pen](/psd/python-net/aspose.psd/pen/) للاختبار. |

**Returns**

| النوع | الوصف |
| :- | :- |
| bool | ترجع هذه الطريقة true إذا كانت النقطة المحددة موجودة داخل حدود هذا [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) عند رسمها بالقلم المحدد [Pen](/psd/python-net/aspose.psd/pen/); وإلا false. |


### Method: is_outline_visible(x, y, pen, graphics) {#is_outline_visible_x_y_pen_graphics_16}


```
 is_outline_visible(x, y, pen, graphics) 
```

يحدد ما إذا كانت النقطة المحددة موجودة داخل (تحت) مخطط هذا [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) عند رسمه باستخدام الـ[Pen](/psd/python-net/aspose.psd/pen/) وباستخدام الـ[Graphics](/psd/python-net/aspose.psd/graphics/) المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| x | float | الإحداثي السيني للنقطة المراد اختبارها. |
| y | float | الإحداثي الصادي للنقطة المراد اختبارها. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | قلم [Pen](/psd/python-net/aspose.psd/pen/) للاختبار. |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | الـ [Graphics](/psd/python-net/aspose.psd/graphics/) لاختبار الرؤية. |

**Returns**

| النوع | الوصف |
| :- | :- |
| bool | ترجع هذه الطريقة true إذا كانت النقطة المحددة موجودة داخل (تحت) حدود هذا [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) كما تم رسمها بالقلم المحدد [Pen](/psd/python-net/aspose.psd/pen/); وإلا false. |


### Method: is_outline_visible(x, y, pen, graphics) {#is_outline_visible_x_y_pen_graphics_17}


```
 is_outline_visible(x, y, pen, graphics) 
```

يحدد ما إذا كانت النقطة المحددة موجودة داخل (تحت) مخطط هذا [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) عند رسمه باستخدام الـ[Pen](/psd/python-net/aspose.psd/pen/) وباستخدام الـ[Graphics](/psd/python-net/aspose.psd/graphics/) المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| x | int | الإحداثي السيني للنقطة المراد اختبارها. |
| y | int | الإحداثي الصادي للنقطة المراد اختبارها. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | قلم [Pen](/psd/python-net/aspose.psd/pen/) للاختبار. |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | الـ [Graphics](/psd/python-net/aspose.psd/graphics/) لاختبار الرؤية. |

**Returns**

| النوع | الوصف |
| :- | :- |
| bool | ترجع هذه الطريقة true إذا كانت النقطة المحددة موجودة داخل (تحت) حدود هذا [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) كما تم رسمها بالقلم المحدد [Pen](/psd/python-net/aspose.psd/pen/); وإلا false. |


### Method: is_visible(point) {#is_visible_point_18}


```
 is_visible(point) 
```

يحدد ما إذا كانت النقطة المحددة موجودة داخل هذا [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | نقطة [PointF](/psd/python-net/aspose.psd/pointf/) تمثل النقطة للاختبار. |

**Returns**

| النوع | الوصف |
| :- | :- |
| bool | ترجع هذه الطريقة true إذا كانت النقطة المحددة موجودة داخل هذا [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/); وإلا false. |


### Method: is_visible(point) {#is_visible_point_19}


```
 is_visible(point) 
```

يحدد ما إذا كانت النقطة المحددة موجودة داخل هذا [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | نقطة [PointF](/psd/python-net/aspose.psd/pointf/) تمثل النقطة للاختبار. |

**Returns**

| النوع | الوصف |
| :- | :- |
| bool | ترجع هذه الطريقة true إذا كانت النقطة المحددة موجودة داخل هذا [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/); وإلا false. |


### Method: is_visible(pt, graphics) {#is_visible_pt_graphics_20}


```
 is_visible(pt, graphics) 
```

يحدد ما إذا كانت النقطة المحددة موجودة داخل هذا [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| pt | [PointF](/psd/python-net/aspose.psd/pointf) | نقطة [PointF](/psd/python-net/aspose.psd/pointf/) تمثل النقطة للاختبار. |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | الـ [Graphics](/psd/python-net/aspose.psd/graphics/) لاختبار الرؤية. |

**Returns**

| النوع | الوصف |
| :- | :- |
| bool | ترجع هذه الطريقة true إذا كانت النقطة المحددة موجودة داخل هذا؛ وإلا false. |


### Method: is_visible(pt, graphics) {#is_visible_pt_graphics_21}


```
 is_visible(pt, graphics) 
```

يحدد ما إذا كانت النقطة المحددة موجودة داخل هذا [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| pt | [Point](/psd/python-net/aspose.psd/point) | نقطة [PointF](/psd/python-net/aspose.psd/pointf/) تمثل النقطة للاختبار. |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | الـ [Graphics](/psd/python-net/aspose.psd/graphics/) لاختبار الرؤية. |

**Returns**

| النوع | الوصف |
| :- | :- |
| bool | ترجع هذه الطريقة true إذا كانت النقطة المحددة موجودة داخل هذا؛ وإلا false. |


### Method: is_visible(x, y) {#is_visible_x_y_22}


```
 is_visible(x, y) 
```

يحدد ما إذا كانت النقطة المحددة موجودة داخل هذا [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| x | float | الإحداثي السيني للنقطة المراد اختبارها. |
| y | float | الإحداثي الصادي للنقطة المراد اختبارها. |

**Returns**

| النوع | الوصف |
| :- | :- |
| bool | ترجع هذه الطريقة true إذا كانت النقطة المحددة موجودة داخل هذا [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/); وإلا false. |


### Method: is_visible(x, y) {#is_visible_x_y_23}


```
 is_visible(x, y) 
```

يحدد ما إذا كانت النقطة المحددة موجودة داخل هذا [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| x | int | الإحداثي السيني للنقطة المراد اختبارها. |
| y | int | الإحداثي الصادي للنقطة المراد اختبارها. |

**Returns**

| النوع | الوصف |
| :- | :- |
| bool | ترجع هذه الطريقة true إذا كانت النقطة المحددة موجودة داخل هذا [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/); وإلا false. |


### Method: is_visible(x, y, graphics) {#is_visible_x_y_graphics_24}


```
 is_visible(x, y, graphics) 
```

يحدد ما إذا كانت النقطة المحددة موجودة داخل هذا [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) في منطقة القص المرئية للـ[Graphics](/psd/python-net/aspose.psd/graphics/) المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| x | float | الإحداثي السيني للنقطة المراد اختبارها. |
| y | float | الإحداثي الصادي للنقطة المراد اختبارها. |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | الـ [Graphics](/psd/python-net/aspose.psd/graphics/) لاختبار الرؤية. |

**Returns**

| النوع | الوصف |
| :- | :- |
| bool | ترجع هذه الطريقة true إذا كانت النقطة المحددة موجودة داخل هذا [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/); وإلا false. |


### Method: is_visible(x, y, graphics) {#is_visible_x_y_graphics_25}


```
 is_visible(x, y, graphics) 
```

يحدد ما إذا كانت النقطة المحددة موجودة داخل هذا [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) في منطقة القص المرئية للـ[Graphics](/psd/python-net/aspose.psd/graphics/) المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| x | int | الإحداثي السيني للنقطة المراد اختبارها. |
| y | int | الإحداثي الصادي للنقطة المراد اختبارها. |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | الـ [Graphics](/psd/python-net/aspose.psd/graphics/) لاختبار الرؤية. |

**Returns**

| النوع | الوصف |
| :- | :- |
| bool | ترجع هذه الطريقة true إذا كانت النقطة المحددة موجودة داخل هذا [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/); وإلا false. |


### Method: remove_figure(figure) {#remove_figure_figure_26}


```
 remove_figure(figure) 
```

يزيل شكلاً.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| figure | [Figure](/psd/python-net/aspose.psd/figure) | الشكل لإزالته. |

### Method: remove_figures(figures) {#remove_figures_figures_27}


```
 remove_figures(figures) 
```

يزيل أشكالًا.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| figures | [Figure[]](/psd/python-net/aspose.psd/figure) | الأشكال لإزالتها. |

### Method: transform(transform) {#transform_transform_28}


```
 transform(transform) 
```

يطبق التحويل المحدد على الشكل.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | التحويل الذي سيُطبق. |

### Method: warp(dest_points, src_rect) {#warp_dest_points_src_rect_29}


```
 warp(dest_points, src_rect) 
```

يطبق تحويل تشويه، يُعرّف بواسطة مستطيل ومتوازي أضلاع، على هذا [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | مصفوفة من هياكل [PointF](/psd/python-net/aspose.psd/pointf/) التي تحدد متوازي أضلاع يتم تحويل المستطيل المحدد بواسطة <paramref name=\"srcRect\" /> إليه. يمكن أن تحتوي المصفوفة على ثلاثة أو أربعة عناصر. إذا احتوت المصفوفة على ثلاثة عناصر، فإن الزاوية السفلية اليمنى للمتوازي أضلاع تُستنتج من النقاط الثلاث الأولى. |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | مستطيل [RectangleF](/psd/python-net/aspose.psd/rectanglef/) يمثل المستطيل الذي يتم تحويله إلى المتوازي أضلاع المحدد بواسطة <paramref name=\"destPoints\" />. |

### Method: warp(dest_points, src_rect, matrix) {#warp_dest_points_src_rect_matrix_30}


```
 warp(dest_points, src_rect, matrix) 
```

يطبق تحويل تشويه، يُعرّف بواسطة مستطيل ومتوازي أضلاع، على هذا [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | مصفوفة من هياكل [PointF](/psd/python-net/aspose.psd/pointf/) التي تحدد متوازي أضلاع يتم تحويل المستطيل المحدد بواسطة <paramref name=\"srcRect\" /> إليه. يمكن أن تحتوي المصفوفة على ثلاثة أو أربعة عناصر. إذا احتوت المصفوفة على ثلاثة عناصر، فإن الزاوية السفلية اليمنى للمتوازي أضلاع تُستنتج من النقاط الثلاث الأولى. |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | مستطيل [RectangleF](/psd/python-net/aspose.psd/rectanglef/) يمثل المستطيل الذي يتم تحويله إلى المتوازي أضلاع المحدد بواسطة <paramref name=\"destPoints\" />. |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | مصفوفة [Matrix](/psd/python-net/aspose.psd/matrix/) تحدد تحويلًا هندسيًا لتطبيقه على المسار. |

### Method: warp(dest_points, src_rect, matrix, warp_mode) {#warp_dest_points_src_rect_matrix_warp_mode_31}


```
 warp(dest_points, src_rect, matrix, warp_mode) 
```

يطبق تحويل تشويه، يُعرّف بواسطة مستطيل ومتوازي أضلاع، على هذا [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | مصفوفة من هياكل [PointF](/psd/python-net/aspose.psd/pointf/) التي تحدد متوازي أضلاع يتم تحويل المستطيل المحدد بواسطة <paramref name=\"srcRect\" /> إليه. يمكن أن تحتوي المصفوفة على ثلاثة أو أربعة عناصر. إذا احتوت المصفوفة على ثلاثة عناصر، فإن الزاوية السفلية اليمنى للمتوازي أضلاع تُستنتج من النقاط الثلاث الأولى. |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | مستطيل [RectangleF](/psd/python-net/aspose.psd/rectanglef/) يمثل المستطيل الذي يتم تحويله إلى المتوازي أضلاع المحدد بواسطة <paramref name=\"destPoints\" />. |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | مصفوفة [Matrix](/psd/python-net/aspose.psd/matrix/) تحدد تحويلًا هندسيًا لتطبيقه على المسار. |
| warp_mode | [WarpMode](/psd/python-net/aspose.psd/warpmode) | تعداد [WarpMode](/psd/python-net/aspose.psd/warpmode/) يحدد ما إذا كانت عملية التشويه هذه تستخدم وضع المنظور أو الوضع الثنائي الخط. |

### Method: warp(dest_points, src_rect, matrix, warp_mode, flatness) {#warp_dest_points_src_rect_matrix_warp_mode_flatness_32}


```
 warp(dest_points, src_rect, matrix, warp_mode, flatness) 
```

يطبق تحويل تشويه، يُعرّف بواسطة مستطيل ومتوازي أضلاع، على هذا [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | مصفوفة من هياكل [PointF](/psd/python-net/aspose.psd/pointf/) التي تحدد متوازي أضلاع يتم تحويل المستطيل المحدد بواسطة <paramref name=\"srcRect\" /> إليه. يمكن أن تحتوي المصفوفة على ثلاثة أو أربعة عناصر. إذا احتوت المصفوفة على ثلاثة عناصر، فإن الزاوية السفلية اليمنى للمتوازي أضلاع تُستنتج من النقاط الثلاث الأولى. |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | مستطيل [RectangleF](/psd/python-net/aspose.psd/rectanglef/) يمثل المستطيل الذي يتم تحويله إلى المتوازي أضلاع المحدد بواسطة <paramref name=\"destPoints\" />. |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | مصفوفة [Matrix](/psd/python-net/aspose.psd/matrix/) تحدد تحويلًا هندسيًا لتطبيقه على المسار. |
| warp_mode | [WarpMode](/psd/python-net/aspose.psd/warpmode) | تعداد [WarpMode](/psd/python-net/aspose.psd/warpmode/) يحدد ما إذا كانت عملية التشويه هذه تستخدم وضع المنظور أو الوضع الثنائي الخط. |
| flatness | float | قيمة من 0 إلى 1 تحدد مدى تسطح المسار الناتج. لمزيد من المعلومات، راجع طرق [GraphicsPath.flatten()](/psd/python-net/aspose.psd/graphicspath/) . |

### Method: widen(pen) {#widen_pen_33}


```
 widen(pen) 
```

يضيف مخططًا إضافيًا إلى المسار.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | قلم [Pen](/psd/python-net/aspose.psd/pen/) يحدد العرض بين الحدود الأصلية للمسار والحدود الجديدة التي تنشئها هذه الطريقة. |

### Method: widen(pen, matrix) {#widen_pen_matrix_34}


```
 widen(pen, matrix) 
```

يضيف مخططًا إضافيًا إلى الـ[GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | قلم [Pen](/psd/python-net/aspose.psd/pen/) يحدد العرض بين الحدود الأصلية للمسار والحدود الجديدة التي تنشئها هذه الطريقة. |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | مصفوفة [Matrix](/psd/python-net/aspose.psd/matrix/) تحدد التحويل لتطبيقه على المسار قبل توسيعه. |

### Method: widen(pen, matrix, flatness) {#widen_pen_matrix_flatness_35}


```
 widen(pen, matrix, flatness) 
```

يستبدل هذا [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) بمنحنيات تحيط بالمنطقة التي تُملأ عندما يُرسم هذا المسار باستخدام القلم المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | قلم [Pen](/psd/python-net/aspose.psd/pen/) يحدد العرض بين الحدود الأصلية للمسار والحدود الجديدة التي تنشئها هذه الطريقة. |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | مصفوفة [Matrix](/psd/python-net/aspose.psd/matrix/) تحدد التحويل لتطبيقه على المسار قبل توسيعه. |
| السطحية | float | قيمة تحدد مستوى الاستواء للمنحنيات. |

