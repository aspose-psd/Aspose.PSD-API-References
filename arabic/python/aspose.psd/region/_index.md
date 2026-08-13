---
title: "فئة Region"
type: docs
weight: 3870
url: /ar/python-net/aspose.psd/region/
---

**Summary:** Describes the interior of a graphics shape composed of rectangles and paths. This class cannot be inherited.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Region

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [Region()](#Region__1) | ينشئ [Region](/psd/python-net/aspose.psd/region/) جديدًا. |
| [Region(path)](#Region_path_2) | ينشئ [Region](/psd/python-net/aspose.psd/region/) جديدًا باستخدام [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) المحدد. |
| [Region(rect)](#Region_rect_3) | ينشئ [Region](/psd/python-net/aspose.psd/region/) جديدًا من بنية [RectangleF](/psd/python-net/aspose.psd/rectanglef/) المحددة. |
| [Region(rect)](#Region_rect_4) | ينشئ [Region](/psd/python-net/aspose.psd/region/) جديدًا من بنية [RectangleF](/psd/python-net/aspose.psd/rectanglef/) المحددة. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [complement(path)](#complement_path_1) | يحدّث هذا [Region](/psd/python-net/aspose.psd/region/) ليحتوي على الجزء من [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) المحدد الذي لا يتقاطع مع هذا [Region](/psd/python-net/aspose.psd/region/). |
| [complement(rect)](#complement_rect_2) | يحدّث هذا [Region](/psd/python-net/aspose.psd/region/) ليحتوي على الجزء من البنية [RectangleF](/psd/python-net/aspose.psd/rectanglef/) المحددة الذي لا يتقاطع مع هذا [Region](/psd/python-net/aspose.psd/region/). |
| [complement(rect)](#complement_rect_3) | يحدّث هذا [Region](/psd/python-net/aspose.psd/region/) ليحتوي على الجزء من البنية [RectangleF](/psd/python-net/aspose.psd/rectanglef/) المحددة الذي لا يتقاطع مع هذا [Region](/psd/python-net/aspose.psd/region/). |
| [complement(region)](#complement_region_4) | يحدّث هذا [Region](/psd/python-net/aspose.psd/region/) ليحتوي على الجزء من [Region](/psd/python-net/aspose.psd/region/) المحدد الذي لا يتقاطع مع هذا [Region](/psd/python-net/aspose.psd/region/). |
| [deep_clone()](#deep_clone__5) | ينشئ نسخة عميقة دقيقة من هذا [Region](/psd/python-net/aspose.psd/region/). |
| [exclude(path)](#exclude_path_6) | يحدّث هذا [Region](/psd/python-net/aspose.psd/region/) ليحتوي فقط على الجزء الداخلي منه الذي لا يتقاطع مع [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) المحدد. |
| [exclude(rect)](#exclude_rect_7) | يحدّث هذا [Region](/psd/python-net/aspose.psd/region/) ليحتوي فقط على الجزء الداخلي منه الذي لا يتقاطع مع البنية [RectangleF](/psd/python-net/aspose.psd/rectanglef/) المحددة. |
| [exclude(rect)](#exclude_rect_8) | يحدّث هذا [Region](/psd/python-net/aspose.psd/region/) ليحتوي فقط على الجزء الداخلي منه الذي لا يتقاطع مع البنية [RectangleF](/psd/python-net/aspose.psd/rectanglef/) المحددة. |
| [exclude(region)](#exclude_region_9) | يحدّث هذا [Region](/psd/python-net/aspose.psd/region/) ليحتوي فقط على الجزء الداخلي منه الذي لا يتقاطع مع [Region](/psd/python-net/aspose.psd/region/) المحدد. |
| [intersect(path)](#intersect_path_10) | يحدّث هذا [Region](/psd/python-net/aspose.psd/region/) إلى تقاطع نفسه مع [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) المحدد. |
| [intersect(rect)](#intersect_rect_11) | يحدّث هذا [Region](/psd/python-net/aspose.psd/region/) إلى تقاطع نفسه مع البنية [RectangleF](/psd/python-net/aspose.psd/rectanglef/) المحددة. |
| [intersect(rect)](#intersect_rect_12) | يحدّث هذا [Region](/psd/python-net/aspose.psd/region/) إلى تقاطع نفسه مع البنية [RectangleF](/psd/python-net/aspose.psd/rectanglef/) المحددة. |
| [intersect(region)](#intersect_region_13) | يحدّث هذا [Region](/psd/python-net/aspose.psd/region/) إلى تقاطع نفسه مع [Region](/psd/python-net/aspose.psd/region/) المحدد. |
| [is_empty(g)](#is_empty_g_14) | يفحص ما إذا كان لهذا [Region](/psd/python-net/aspose.psd/region/) داخلًا فارغًا على سطح الرسم المحدد. |
| [is_infinite(g)](#is_infinite_g_15) | يفحص ما إذا كان لهذا [Region](/psd/python-net/aspose.psd/region/) داخلًا لا نهائيًا على سطح الرسم المحدد. |
| [is_visible(point)](#is_visible_point_16) | يفحص ما إذا كانت بنية [PointF](/psd/python-net/aspose.psd/pointf/) المحددة موجودة داخل هذا [Region](/psd/python-net/aspose.psd/region/). |
| [is_visible(point)](#is_visible_point_17) | يفحص ما إذا كانت بنية [PointF](/psd/python-net/aspose.psd/pointf/) المحددة موجودة داخل هذا [Region](/psd/python-net/aspose.psd/region/). |
| [is_visible(point, g)](#is_visible_point_g_18) | يفحص ما إذا كانت بنية [PointF](/psd/python-net/aspose.psd/pointf/) المحددة موجودة داخل هذا [Region](/psd/python-net/aspose.psd/region/) عند الرسم باستخدام [Graphics](/psd/python-net/aspose.psd/graphics/). |
| [is_visible(point, g)](#is_visible_point_g_19) | يفحص ما إذا كانت بنية [PointF](/psd/python-net/aspose.psd/pointf/) المحددة موجودة داخل هذا [Region](/psd/python-net/aspose.psd/region/) عند الرسم باستخدام [Graphics](/psd/python-net/aspose.psd/graphics/). |
| [is_visible(rect)](#is_visible_rect_20) | يفحص ما إذا كان أي جزء من البنية [RectangleF](/psd/python-net/aspose.psd/rectanglef/) المحددة موجودًا داخل هذا [Region](/psd/python-net/aspose.psd/region/). |
| [is_visible(rect)](#is_visible_rect_21) | يفحص ما إذا كان أي جزء من البنية [RectangleF](/psd/python-net/aspose.psd/rectanglef/) المحددة موجودًا داخل هذا [Region](/psd/python-net/aspose.psd/region/). |
| [is_visible(rect, g)](#is_visible_rect_g_22) | يفحص ما إذا كان أي جزء من البنية [RectangleF](/psd/python-net/aspose.psd/rectanglef/) المحددة موجودًا داخل هذا [Region](/psd/python-net/aspose.psd/region/) عند الرسم باستخدام [Graphics](/psd/python-net/aspose.psd/graphics/). |
| [is_visible(rect, g)](#is_visible_rect_g_23) | يفحص ما إذا كان أي جزء من البنية [RectangleF](/psd/python-net/aspose.psd/rectanglef/) المحددة موجودًا داخل هذا [Region](/psd/python-net/aspose.psd/region/) عند الرسم باستخدام [Graphics](/psd/python-net/aspose.psd/graphics/). |
| [is_visible(x, y)](#is_visible_x_y_24) | يفحص ما إذا كانت النقطة المحددة موجودة داخل هذا [Region](/psd/python-net/aspose.psd/region/). |
| [is_visible(x, y, g)](#is_visible_x_y_g_25) | يفحص ما إذا كانت النقطة المحددة موجودة داخل هذا [Region](/psd/python-net/aspose.psd/region/) عند الرسم باستخدام [Graphics](/psd/python-net/aspose.psd/graphics/). |
| [is_visible(x, y, g)](#is_visible_x_y_g_26) | يفحص ما إذا كانت النقطة المحددة موجودة داخل هذا [Region](/psd/python-net/aspose.psd/region/) عند الرسم باستخدام [Graphics](/psd/python-net/aspose.psd/graphics/). |
| [is_visible(x, y, width, height)](#is_visible_x_y_width_height_27) | يفحص ما إذا كان أي جزء من المستطيل المحدد موجودًا داخل هذه [Region](/psd/python-net/aspose.psd/region/). |
| [is_visible(x, y, width, height)](#is_visible_x_y_width_height_28) | يفحص ما إذا كان أي جزء من المستطيل المحدد موجودًا داخل هذه [Region](/psd/python-net/aspose.psd/region/). |
| [is_visible(x, y, width, height, g)](#is_visible_x_y_width_height_g_29) | يفحص ما إذا كان أي جزء من المستطيل المحدد موجودًا داخل هذه [Region](/psd/python-net/aspose.psd/region/) عند رسمه باستخدام الـ [Graphics](/psd/python-net/aspose.psd/graphics/). |
| [is_visible(x, y, width, height, g)](#is_visible_x_y_width_height_g_30) | يفحص ما إذا كان أي جزء من المستطيل المحدد موجودًا داخل هذه [Region](/psd/python-net/aspose.psd/region/) عند رسمه باستخدام الـ [Graphics](/psd/python-net/aspose.psd/graphics/). |
| make_empty() | يُهيئ هذه [Region](/psd/python-net/aspose.psd/region/) لتكون ذات داخلية فارغة. |
| make_infinite() | يُهيئ كائن [Region](/psd/python-net/aspose.psd/region/) هذا لتكون ذات داخلية لا نهائية. |
| [transform(matrix)](#transform_matrix_31) | يحوّل هذه [Region](/psd/python-net/aspose.psd/region/) باستخدام الـ [Matrix](/psd/python-net/aspose.psd/matrix/) المحدد. |
| [translate(dx, dy)](#translate_dx_dy_32) | يُزاحِ إحداثيات هذه [Region](/psd/python-net/aspose.psd/region/) بالمقدار المحدد. |
| [translate(dx, dy)](#translate_dx_dy_33) | يُزاحِ إحداثيات هذه [Region](/psd/python-net/aspose.psd/region/) بالمقدار المحدد. |
| [union(path)](#union_path_34) | يُحدّث هذه [Region](/psd/python-net/aspose.psd/region/) لتصبح اتحادًا بين نفسها و[GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) المحدد. |
| [union(rect)](#union_rect_35) | يُحدّث هذه [Region](/psd/python-net/aspose.psd/region/) لتصبح اتحادًا بين نفسها وبنية [RectangleF](/psd/python-net/aspose.psd/rectanglef/) المحددة. |
| [union(rect)](#union_rect_36) | يُحدّث هذه [Region](/psd/python-net/aspose.psd/region/) لتصبح اتحادًا بين نفسها وبنية [RectangleF](/psd/python-net/aspose.psd/rectanglef/) المحددة. |
| [union(region)](#union_region_37) | يُحدّث هذه [Region](/psd/python-net/aspose.psd/region/) لتصبح اتحادًا بين نفسها و[Region](/psd/python-net/aspose.psd/region/) المحدد. |
| [xor(path)](#xor_path_38) | يُحدّث هذه [Region](/psd/python-net/aspose.psd/region/) لتصبح اتحادًا مطروحًا منه تقاطعها مع [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) المحدد. |
| [xor(rect)](#xor_rect_39) | يُحدّث هذه [Region](/psd/python-net/aspose.psd/region/) لتصبح اتحادًا مطروحًا منه تقاطعها مع بنية [RectangleF](/psd/python-net/aspose.psd/rectanglef/) المحددة. |
| [xor(rect)](#xor_rect_40) | يُحدّث هذه [Region](/psd/python-net/aspose.psd/region/) لتصبح اتحادًا مطروحًا منه تقاطعها مع بنية [RectangleF](/psd/python-net/aspose.psd/rectanglef/) المحددة. |
| [xor(region)](#xor_region_41) | يُحدّث هذه [Region](/psd/python-net/aspose.psd/region/) لتصبح اتحادًا مطروحًا منه تقاطعها مع [Region](/psd/python-net/aspose.psd/region/) المحدد. |


### Constructor: Region() {#Region__1}


```
 Region() 
```

ينشئ [Region](/psd/python-net/aspose.psd/region/) جديدًا.

### Constructor: Region(path) {#Region_path_2}


```
 Region(path) 
```

ينشئ [Region](/psd/python-net/aspose.psd/region/) جديدًا باستخدام [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) يحدد الـ [Region](/psd/python-net/aspose.psd/region/) الجديد. |

### Constructor: Region(rect) {#Region_rect_3}


```
 Region(rect) 
```

ينشئ [Region](/psd/python-net/aspose.psd/region/) جديدًا من بنية [RectangleF](/psd/python-net/aspose.psd/rectanglef/) المحددة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) يحدد داخل الـ [Region](/psd/python-net/aspose.psd/region/) الجديد. |

### Constructor: Region(rect) {#Region_rect_4}


```
 Region(rect) 
```

ينشئ [Region](/psd/python-net/aspose.psd/region/) جديدًا من بنية [RectangleF](/psd/python-net/aspose.psd/rectanglef/) المحددة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) يحدد داخل الـ [Region](/psd/python-net/aspose.psd/region/) الجديد. |

### Method: complement(path) {#complement_path_1}


```
 complement(path) 
```

يحدّث هذا [Region](/psd/python-net/aspose.psd/region/) ليحتوي على الجزء من [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) المحدد الذي لا يتقاطع مع هذا [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) لتكملة هذه [Region](/psd/python-net/aspose.psd/region/). |

### Method: complement(rect) {#complement_rect_2}


```
 complement(rect) 
```

يحدّث هذا [Region](/psd/python-net/aspose.psd/region/) ليحتوي على الجزء من البنية [RectangleF](/psd/python-net/aspose.psd/rectanglef/) المحددة الذي لا يتقاطع مع هذا [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | بنية [RectangleF](/psd/python-net/aspose.psd/rectanglef/) لتكملة هذه [Region](/psd/python-net/aspose.psd/region/). |

### Method: complement(rect) {#complement_rect_3}


```
 complement(rect) 
```

يحدّث هذا [Region](/psd/python-net/aspose.psd/region/) ليحتوي على الجزء من البنية [RectangleF](/psd/python-net/aspose.psd/rectanglef/) المحددة الذي لا يتقاطع مع هذا [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | بنية [RectangleF](/psd/python-net/aspose.psd/rectanglef/) لتكملة هذه [Region](/psd/python-net/aspose.psd/region/). |

### Method: complement(region) {#complement_region_4}


```
 complement(region) 
```

يحدّث هذا [Region](/psd/python-net/aspose.psd/region/) ليحتوي على الجزء من [Region](/psd/python-net/aspose.psd/region/) المحدد الذي لا يتقاطع مع هذا [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| region | [Region](/psd/python-net/aspose.psd/region) | كائن [Region](/psd/python-net/aspose.psd/region/) لتكملة كائن [Region](/psd/python-net/aspose.psd/region/) هذا. |

### Method: deep_clone() {#deep_clone__5}


```
 deep_clone() 
```

ينشئ نسخة عميقة دقيقة من هذا [Region](/psd/python-net/aspose.psd/region/).

**Returns**

| النوع | الوصف |
| :- | :- |
| [Region](/psd/python-net/aspose.psd/region) | [Region](/psd/python-net/aspose.psd/region/) الذي تُنشئه هذه الطريقة. |


### Method: exclude(path) {#exclude_path_6}


```
 exclude(path) 
```

يحدّث هذا [Region](/psd/python-net/aspose.psd/region/) ليحتوي فقط على الجزء الداخلي منه الذي لا يتقاطع مع [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) لاستثنائه من هذه [Region](/psd/python-net/aspose.psd/region/). |

### Method: exclude(rect) {#exclude_rect_7}


```
 exclude(rect) 
```

يحدّث هذا [Region](/psd/python-net/aspose.psd/region/) ليحتوي فقط على الجزء الداخلي منه الذي لا يتقاطع مع البنية [RectangleF](/psd/python-net/aspose.psd/rectanglef/) المحددة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | بنية [RectangleF](/psd/python-net/aspose.psd/rectanglef/) لاستثنائها من هذه [Region](/psd/python-net/aspose.psd/region/). |

### Method: exclude(rect) {#exclude_rect_8}


```
 exclude(rect) 
```

يحدّث هذا [Region](/psd/python-net/aspose.psd/region/) ليحتوي فقط على الجزء الداخلي منه الذي لا يتقاطع مع البنية [RectangleF](/psd/python-net/aspose.psd/rectanglef/) المحددة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | بنية [RectangleF](/psd/python-net/aspose.psd/rectanglef/) لاستثنائها من هذه [Region](/psd/python-net/aspose.psd/region/). |

### Method: exclude(region) {#exclude_region_9}


```
 exclude(region) 
```

يحدّث هذا [Region](/psd/python-net/aspose.psd/region/) ليحتوي فقط على الجزء الداخلي منه الذي لا يتقاطع مع [Region](/psd/python-net/aspose.psd/region/) المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| region | [Region](/psd/python-net/aspose.psd/region) | [Region](/psd/python-net/aspose.psd/region/) لاستثنائه من هذه [Region](/psd/python-net/aspose.psd/region/). |

### Method: intersect(path) {#intersect_path_10}


```
 intersect(path) 
```

يحدّث هذا [Region](/psd/python-net/aspose.psd/region/) إلى تقاطع نفسه مع [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) للتقاطع مع هذه [Region](/psd/python-net/aspose.psd/region/). |

### Method: intersect(rect) {#intersect_rect_11}


```
 intersect(rect) 
```

يحدّث هذا [Region](/psd/python-net/aspose.psd/region/) إلى تقاطع نفسه مع البنية [RectangleF](/psd/python-net/aspose.psd/rectanglef/) المحددة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | بنية [RectangleF](/psd/python-net/aspose.psd/rectanglef/) للتقاطع مع هذه [Region](/psd/python-net/aspose.psd/region/). |

### Method: intersect(rect) {#intersect_rect_12}


```
 intersect(rect) 
```

يحدّث هذا [Region](/psd/python-net/aspose.psd/region/) إلى تقاطع نفسه مع البنية [RectangleF](/psd/python-net/aspose.psd/rectanglef/) المحددة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | بنية [RectangleF](/psd/python-net/aspose.psd/rectanglef/) للتقاطع مع هذه [Region](/psd/python-net/aspose.psd/region/). |

### Method: intersect(region) {#intersect_region_13}


```
 intersect(region) 
```

يحدّث هذا [Region](/psd/python-net/aspose.psd/region/) إلى تقاطع نفسه مع [Region](/psd/python-net/aspose.psd/region/) المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| region | [Region](/psd/python-net/aspose.psd/region) | [Region](/psd/python-net/aspose.psd/region/) للتقاطع مع هذه [Region](/psd/python-net/aspose.psd/region/). |

### Method: is_empty(g) {#is_empty_g_14}


```
 is_empty(g) 
```

يفحص ما إذا كان لهذا [Region](/psd/python-net/aspose.psd/region/) داخلًا فارغًا على سطح الرسم المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | [Graphics](/psd/python-net/aspose.psd/graphics/) يمثل سطح رسم. |

**Returns**

| النوع | الوصف |
| :- | :- |
| bool | true إذا كان داخل هذا [Region](/psd/python-net/aspose.psd/region/) فارغًا عندما يتم تطبيق التحويل المرتبط بـ <paramref name=\"g\" />؛ وإلا false. |


### Method: is_infinite(g) {#is_infinite_g_15}


```
 is_infinite(g) 
```

يفحص ما إذا كان لهذا [Region](/psd/python-net/aspose.psd/region/) داخلًا لا نهائيًا على سطح الرسم المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | [Graphics](/psd/python-net/aspose.psd/graphics/) يمثل سطح رسم. |

**Returns**

| النوع | الوصف |
| :- | :- |
| bool | true إذا كان داخل هذا [Region](/psd/python-net/aspose.psd/region/) لا نهائيًا عندما يتم تطبيق التحويل المرتبط بـ <paramref name=\"g\" />؛ وإلا false. |


### Method: is_visible(point) {#is_visible_point_16}


```
 is_visible(point) 
```

يفحص ما إذا كانت بنية [PointF](/psd/python-net/aspose.psd/pointf/) المحددة موجودة داخل هذا [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | الـ [PointF](/psd/python-net/aspose.psd/pointf/) الهيكل للاختبار. |

**Returns**

| النوع | الوصف |
| :- | :- |
| bool | true عندما يكون <paramref name=\"point\" /> موجودًا داخل هذا [Region](/psd/python-net/aspose.psd/region/); وإلا false. |


### Method: is_visible(point) {#is_visible_point_17}


```
 is_visible(point) 
```

يفحص ما إذا كانت بنية [PointF](/psd/python-net/aspose.psd/pointf/) المحددة موجودة داخل هذا [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | الـ [PointF](/psd/python-net/aspose.psd/pointf/) الهيكل للاختبار. |

**Returns**

| النوع | الوصف |
| :- | :- |
| bool | true عندما يكون <paramref name=\"point\" /> موجودًا داخل هذا [Region](/psd/python-net/aspose.psd/region/); وإلا false. |


### Method: is_visible(point, g) {#is_visible_point_g_18}


```
 is_visible(point, g) 
```

يفحص ما إذا كانت بنية [PointF](/psd/python-net/aspose.psd/pointf/) المحددة موجودة داخل هذا [Region](/psd/python-net/aspose.psd/region/) عند الرسم باستخدام [Graphics](/psd/python-net/aspose.psd/graphics/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | الـ [PointF](/psd/python-net/aspose.psd/pointf/) الهيكل للاختبار. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | ـ [Graphics](/psd/python-net/aspose.psd/graphics/) يمثل سياقًا رسوميًا. |

**Returns**

| النوع | الوصف |
| :- | :- |
| bool | true عندما يكون <paramref name=\"point\" /> موجودًا داخل هذا [Region](/psd/python-net/aspose.psd/region/); وإلا false. |


### Method: is_visible(point, g) {#is_visible_point_g_19}


```
 is_visible(point, g) 
```

يفحص ما إذا كانت بنية [PointF](/psd/python-net/aspose.psd/pointf/) المحددة موجودة داخل هذا [Region](/psd/python-net/aspose.psd/region/) عند الرسم باستخدام [Graphics](/psd/python-net/aspose.psd/graphics/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | الـ [PointF](/psd/python-net/aspose.psd/pointf/) الهيكل للاختبار. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | ـ [Graphics](/psd/python-net/aspose.psd/graphics/) يمثل سياقًا رسوميًا. |

**Returns**

| النوع | الوصف |
| :- | :- |
| bool | true عندما يكون <paramref name=\"point\" /> موجودًا داخل هذا [Region](/psd/python-net/aspose.psd/region/); وإلا false. |


### Method: is_visible(rect) {#is_visible_rect_20}


```
 is_visible(rect) 
```

يفحص ما إذا كان أي جزء من البنية [RectangleF](/psd/python-net/aspose.psd/rectanglef/) المحددة موجودًا داخل هذا [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | الـ [RectangleF](/psd/python-net/aspose.psd/rectanglef/) الهيكل للاختبار. |

**Returns**

| النوع | الوصف |
| :- | :- |
| bool | true عندما يكون أي جزء من <paramref name=\"rect\" /> موجودًا داخل هذا [Region](/psd/python-net/aspose.psd/region/); وإلا false. |


### Method: is_visible(rect) {#is_visible_rect_21}


```
 is_visible(rect) 
```

يفحص ما إذا كان أي جزء من البنية [RectangleF](/psd/python-net/aspose.psd/rectanglef/) المحددة موجودًا داخل هذا [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | الـ [RectangleF](/psd/python-net/aspose.psd/rectanglef/) الهيكل للاختبار. |

**Returns**

| النوع | الوصف |
| :- | :- |
| bool | true عندما يكون أي جزء من <paramref name=\"rect\" /> موجودًا داخل هذا [Region](/psd/python-net/aspose.psd/region/); وإلا false. |


### Method: is_visible(rect, g) {#is_visible_rect_g_22}


```
 is_visible(rect, g) 
```

يفحص ما إذا كان أي جزء من البنية [RectangleF](/psd/python-net/aspose.psd/rectanglef/) المحددة موجودًا داخل هذا [Region](/psd/python-net/aspose.psd/region/) عند الرسم باستخدام [Graphics](/psd/python-net/aspose.psd/graphics/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | الـ [RectangleF](/psd/python-net/aspose.psd/rectanglef/) الهيكل للاختبار. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | ـ [Graphics](/psd/python-net/aspose.psd/graphics/) يمثل سياقًا رسوميًا. |

**Returns**

| النوع | الوصف |
| :- | :- |
| bool | true عندما يكون <paramref name=\"rect\" /> موجودًا داخل هذا [Region](/psd/python-net/aspose.psd/region/); وإلا false. |


### Method: is_visible(rect, g) {#is_visible_rect_g_23}


```
 is_visible(rect, g) 
```

يفحص ما إذا كان أي جزء من البنية [RectangleF](/psd/python-net/aspose.psd/rectanglef/) المحددة موجودًا داخل هذا [Region](/psd/python-net/aspose.psd/region/) عند الرسم باستخدام [Graphics](/psd/python-net/aspose.psd/graphics/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | الـ [RectangleF](/psd/python-net/aspose.psd/rectanglef/) الهيكل للاختبار. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | ـ [Graphics](/psd/python-net/aspose.psd/graphics/) يمثل سياقًا رسوميًا. |

**Returns**

| النوع | الوصف |
| :- | :- |
| bool | true عندما يكون <paramref name=\"rect\" /> موجودًا داخل هذا [Region](/psd/python-net/aspose.psd/region/); وإلا false. |


### Method: is_visible(x, y) {#is_visible_x_y_24}


```
 is_visible(x, y) 
```

يفحص ما إذا كانت النقطة المحددة موجودة داخل هذا [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| x | float | الإحداثي السيني للنقطة المراد اختبارها. |
| y | float | الإحداثي الصادي للنقطة المراد اختبارها. |

**Returns**

| النوع | الوصف |
| :- | :- |
| bool | True عندما تكون النقطة المحددة موجودة داخل هذا [Region](/psd/python-net/aspose.psd/region/); وإلا false. |


### Method: is_visible(x, y, g) {#is_visible_x_y_g_25}


```
 is_visible(x, y, g) 
```

يفحص ما إذا كانت النقطة المحددة موجودة داخل هذا [Region](/psd/python-net/aspose.psd/region/) عند الرسم باستخدام [Graphics](/psd/python-net/aspose.psd/graphics/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| x | float | الإحداثي السيني للنقطة المراد اختبارها. |
| y | float | الإحداثي الصادي للنقطة المراد اختبارها. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | ـ [Graphics](/psd/python-net/aspose.psd/graphics/) يمثل سياقًا رسوميًا. |

**Returns**

| النوع | الوصف |
| :- | :- |
| bool | True عندما تكون النقطة المحددة موجودة داخل هذا [Region](/psd/python-net/aspose.psd/region/); وإلا false. |


### Method: is_visible(x, y, g) {#is_visible_x_y_g_26}


```
 is_visible(x, y, g) 
```

يفحص ما إذا كانت النقطة المحددة موجودة داخل هذا [Region](/psd/python-net/aspose.psd/region/) عند الرسم باستخدام [Graphics](/psd/python-net/aspose.psd/graphics/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| x | int | الإحداثي السيني للنقطة المراد اختبارها. |
| y | int | الإحداثي الصادي للنقطة المراد اختبارها. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | ـ [Graphics](/psd/python-net/aspose.psd/graphics/) يمثل سياقًا رسوميًا. |

**Returns**

| النوع | الوصف |
| :- | :- |
| bool | True عندما تكون النقطة المحددة موجودة داخل هذا [Region](/psd/python-net/aspose.psd/region/); وإلا false. |


### Method: is_visible(x, y, width, height) {#is_visible_x_y_width_height_27}


```
 is_visible(x, y, width, height) 
```

يفحص ما إذا كان أي جزء من المستطيل المحدد موجودًا داخل هذه [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| x | float | الإحداثي السيني للزاوية العليا اليسرى للمستطيل المراد اختباره. |
| y | float | الإحداثي الصادي للزاوية العليا اليسرى للمستطيل المراد اختباره. |
| width | float | عرض المستطيل المراد اختباره. |
| الارتفاع | float | ارتفاع المستطيل المراد اختباره. |

**Returns**

| النوع | الوصف |
| :- | :- |
| bool | true عندما يكون أي جزء من المستطيل المحدد موجودًا داخل كائن هذا [Region](/psd/python-net/aspose.psd/region/); وإلا false. |


### Method: is_visible(x, y, width, height) {#is_visible_x_y_width_height_28}


```
 is_visible(x, y, width, height) 
```

يفحص ما إذا كان أي جزء من المستطيل المحدد موجودًا داخل هذه [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| x | int | الإحداثي السيني للزاوية العليا اليسرى للمستطيل المراد اختباره. |
| y | int | الإحداثي الصادي للزاوية العليا اليسرى للمستطيل المراد اختباره. |
| width | int | عرض المستطيل المراد اختباره. |
| الارتفاع | int | ارتفاع المستطيل المراد اختباره. |

**Returns**

| النوع | الوصف |
| :- | :- |
| bool | true عندما يكون أي جزء من المستطيل المحدد موجودًا داخل كائن هذا [Region](/psd/python-net/aspose.psd/region/); وإلا false. |


### Method: is_visible(x, y, width, height, g) {#is_visible_x_y_width_height_g_29}


```
 is_visible(x, y, width, height, g) 
```

يفحص ما إذا كان أي جزء من المستطيل المحدد موجودًا داخل هذه [Region](/psd/python-net/aspose.psd/region/) عند رسمه باستخدام الـ [Graphics](/psd/python-net/aspose.psd/graphics/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| x | float | الإحداثي السيني للزاوية العليا اليسرى للمستطيل المراد اختباره. |
| y | float | الإحداثي الصادي للزاوية العليا اليسرى للمستطيل المراد اختباره. |
| width | float | عرض المستطيل المراد اختباره. |
| الارتفاع | float | ارتفاع المستطيل المراد اختباره. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | ـ [Graphics](/psd/python-net/aspose.psd/graphics/) يمثل سياقًا رسوميًا. |

**Returns**

| النوع | الوصف |
| :- | :- |
| bool | true عندما يكون أي جزء من المستطيل المحدد موجودًا داخل هذا [Region](/psd/python-net/aspose.psd/region/); وإلا false. |


### Method: is_visible(x, y, width, height, g) {#is_visible_x_y_width_height_g_30}


```
 is_visible(x, y, width, height, g) 
```

يفحص ما إذا كان أي جزء من المستطيل المحدد موجودًا داخل هذه [Region](/psd/python-net/aspose.psd/region/) عند رسمه باستخدام الـ [Graphics](/psd/python-net/aspose.psd/graphics/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| x | int | الإحداثي السيني للزاوية العليا اليسرى للمستطيل المراد اختباره. |
| y | int | الإحداثي الصادي للزاوية العليا اليسرى للمستطيل المراد اختباره. |
| width | int | عرض المستطيل المراد اختباره. |
| الارتفاع | int | ارتفاع المستطيل المراد اختباره. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | ـ [Graphics](/psd/python-net/aspose.psd/graphics/) يمثل سياقًا رسوميًا. |

**Returns**

| النوع | الوصف |
| :- | :- |
| bool | true عندما يكون أي جزء من المستطيل المحدد موجودًا داخل هذا [Region](/psd/python-net/aspose.psd/region/); وإلا false. |


### Method: transform(matrix) {#transform_matrix_31}


```
 transform(matrix) 
```

يحوّل هذه [Region](/psd/python-net/aspose.psd/region/) باستخدام الـ [Matrix](/psd/python-net/aspose.psd/matrix/) المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | الـ [Matrix](/psd/python-net/aspose.psd/matrix/) الذي يُستخدم لتحويل هذا [Region](/psd/python-net/aspose.psd/region/). |

### Method: translate(dx, dy) {#translate_dx_dy_32}


```
 translate(dx, dy) 
```

يُزاحِ إحداثيات هذه [Region](/psd/python-net/aspose.psd/region/) بالمقدار المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| dx | float | المقدار لإزاحة هذا [Region](/psd/python-net/aspose.psd/region/) أفقيًا. |
| dy | float | المقدار لإزاحة هذا [Region](/psd/python-net/aspose.psd/region/) عموديًا. |

### Method: translate(dx, dy) {#translate_dx_dy_33}


```
 translate(dx, dy) 
```

يُزاحِ إحداثيات هذه [Region](/psd/python-net/aspose.psd/region/) بالمقدار المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| dx | int | المقدار لإزاحة هذا [Region](/psd/python-net/aspose.psd/region/) أفقيًا. |
| dy | int | المقدار لإزاحة هذا [Region](/psd/python-net/aspose.psd/region/) عموديًا. |

### Method: union(path) {#union_path_34}


```
 union(path) 
```

يُحدّث هذه [Region](/psd/python-net/aspose.psd/region/) لتصبح اتحادًا بين نفسها و[GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | الـ [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) للاتحاد مع هذا [Region](/psd/python-net/aspose.psd/region/). |

### Method: union(rect) {#union_rect_35}


```
 union(rect) 
```

يُحدّث هذه [Region](/psd/python-net/aspose.psd/region/) لتصبح اتحادًا بين نفسها وبنية [RectangleF](/psd/python-net/aspose.psd/rectanglef/) المحددة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | الـ [RectangleF](/psd/python-net/aspose.psd/rectanglef/) الهيكل للاتحاد مع هذا [Region](/psd/python-net/aspose.psd/region/). |

### Method: union(rect) {#union_rect_36}


```
 union(rect) 
```

يُحدّث هذه [Region](/psd/python-net/aspose.psd/region/) لتصبح اتحادًا بين نفسها وبنية [RectangleF](/psd/python-net/aspose.psd/rectanglef/) المحددة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | الـ [RectangleF](/psd/python-net/aspose.psd/rectanglef/) الهيكل للاتحاد مع هذا [Region](/psd/python-net/aspose.psd/region/). |

### Method: union(region) {#union_region_37}


```
 union(region) 
```

يُحدّث هذه [Region](/psd/python-net/aspose.psd/region/) لتصبح اتحادًا بين نفسها و[Region](/psd/python-net/aspose.psd/region/) المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| region | [Region](/psd/python-net/aspose.psd/region) | الـ [Region](/psd/python-net/aspose.psd/region/) للاتحاد مع هذا [Region](/psd/python-net/aspose.psd/region/). |

### Method: xor(path) {#xor_path_38}


```
 xor(path) 
```

يُحدّث هذه [Region](/psd/python-net/aspose.psd/region/) لتصبح اتحادًا مطروحًا منه تقاطعها مع [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | الـ [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) للقيام بعملية XOR مع هذا [Region](/psd/python-net/aspose.psd/region/). |

### Method: xor(rect) {#xor_rect_39}


```
 xor(rect) 
```

يُحدّث هذه [Region](/psd/python-net/aspose.psd/region/) لتصبح اتحادًا مطروحًا منه تقاطعها مع بنية [RectangleF](/psd/python-net/aspose.psd/rectanglef/) المحددة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | الـ [RectangleF](/psd/python-net/aspose.psd/rectanglef/) الهيكل للقيام بعملية XOR مع هذا [Region](/psd/python-net/aspose.psd/region/). |

### Method: xor(rect) {#xor_rect_40}


```
 xor(rect) 
```

يُحدّث هذه [Region](/psd/python-net/aspose.psd/region/) لتصبح اتحادًا مطروحًا منه تقاطعها مع بنية [RectangleF](/psd/python-net/aspose.psd/rectanglef/) المحددة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | الـ [RectangleF](/psd/python-net/aspose.psd/rectanglef/) الهيكل للقيام بعملية XOR مع هذا [Region](/psd/python-net/aspose.psd/region/). |

### Method: xor(region) {#xor_region_41}


```
 xor(region) 
```

يُحدّث هذه [Region](/psd/python-net/aspose.psd/region/) لتصبح اتحادًا مطروحًا منه تقاطعها مع [Region](/psd/python-net/aspose.psd/region/) المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| region | [Region](/psd/python-net/aspose.psd/region) | الـ [Region](/psd/python-net/aspose.psd/region/) للقيام بعملية XOR مع هذا [Region](/psd/python-net/aspose.psd/region/). |

