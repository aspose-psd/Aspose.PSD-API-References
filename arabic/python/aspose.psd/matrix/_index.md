---
title: "فئة Matrix"
type: docs
weight: 3000
url: /ar/python-net/aspose.psd/matrix/
---

**Summary:** Replaces the GDI+ Matrix.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Matrix

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [Matrix()](#Matrix__1) | ينشئ مثيلاً جديداً من فئة Matrix كمصفوفة الهوية. |
| [Matrix(m11, m12, m21, m22, m31, m32)](#Matrix_m11_m12_m21_m22_m31_m32_2) | ينشئ مثيلاً جديداً من فئة [Matrix](/psd/python-net/aspose.psd/matrix/). |
| [Matrix(origin)](#Matrix_origin_3) | ينشئ نسخة من فئة [Matrix](/psd/python-net/aspose.psd/matrix/). |
| [Matrix(rect, plgpts)](#Matrix_rect_plgpts_4) | ينشئ مثيلاً جديداً من فئة [Matrix](/psd/python-net/aspose.psd/matrix/) للتحويل الهندسي المحدد بواسطة المستطيل المحدد ومصفوفة النقاط. |
| [Matrix(rect, plgpts)](#Matrix_rect_plgpts_5) | ينشئ مثيلاً جديداً من فئة [Matrix](/psd/python-net/aspose.psd/matrix/) للتحويل الهندسي المحدد بواسطة المستطيل المحدد ومصفوفة النقاط. |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| TYPE_FLIP [static] | int | r | تشير هذه البتة flag إلى أن التحويل المحدد بواسطة هذا الكائن<br/> يقوم بعكس صورة مرآة حول محور ما مما يغيّر نظام الإحداثيات اليدوي الأيمن المعتاد إلى نظام يدوي أيسر بالإضافة إلى التحويلات المشار إليها بواسطة بتات flag الأخرى.<br/> نظام الإحداثيات اليدوي الأيمن هو النظام الذي يدور فيه المحور X الموجب عكس اتجاه عقارب الساعة ليطابق المحور Y الموجب مشابهًا للاتجاه الذي تنحني فيه أصابع يدك اليمنى عندما تنظر مباشرة إلى إبهامك.<br/> نظام الإحداثيات اليدوي الأيسر هو النظام الذي يدور فيه المحور X الموجب مع اتجاه عقارب الساعة ليطابق المحور Y الموجب مشابهًا للاتجاه الذي تنحني فيه أصابع يدك اليسرى.<br/> لا توجد طريقة رياضية لتحديد زاوية القلب أو العكس الأصلي لأن جميع زوايا القلب متطابقة عند تطبيق دوران تعديل مناسب.<br/> ملاحظة: تم إضافة TypeFlip بعد أن كان GENERAL_TRANSFORM متاحًا للجمهور وبالتالي لم يعد من الممكن إعادة ترقيم بتات flag بسهولة دون إدخال عدم توافق ثنائي في الشيفرة الخارجية. |
| TYPE_GENERAL_ROTATION [static] | int | r | تشير هذه البتة flag إلى أن التحويل المحدد بواسطة هذا الكائن<br/> يقوم بدوران بزاوية عشوائية بالإضافة إلى التحويلات المشار إليها بواسطة بتات flag الأخرى.<br/> يغيّر الدوران زوايا المتجهات بنفس المقدار بغض النظر عن الاتجاه الأصلي للمتجه ودون تغيير طول المتجه.<br/> هذه البتة flag متعارضة بشكل متبادل مع ال |
| TYPE_GENERAL_SCALE [static] | int | r | يقوم مقياس عام بضرب طول المتجهات بقيم مختلفة<br/> في اتجاهي x و y دون تغيير الزاوية بين المتجهات المتعامدة.<br/> هذه البتة flag متعارضة بشكل متبادل مع علم TypeUniformScale. |
| TYPE_GENERAL_TRANSFORM [static] | int | r | تشير هذه الثابتة إلى أن التحويل المحدد بواسطة هذا الكائن<br/> يقوم بتحويل عشوائي لإحداثيات الإدخال.<br/> إذا كان يمكن تصنيف هذا التحويل بأي من الثوابت المذكورة أعلاه، فسيكون النوع إما الثابت TypeIdentity أو مجموعة من بتات flag المناسبة للتحويلات المختلفة للإحداثيات التي يقوم بها هذا التحويل. |
| TYPE_IDENTITY [static] | int | r | التحويل الهوية هو التحويل الذي تكون فيه إحداثيات الخرج دائمًا هي نفسها إحداثيات الإدخال.<br/> إذا كان هذا التحويل شيئًا غير التحويل الهوية، فسيكون النوع إما الثابت GENERAL_TRANSFORM أو مجموعة من بتات flag المناسبة للتحويلات المختلفة للإحداثيات التي يقوم بها هذا التحويل. |
| TYPE_MASK_ROTATION [static] | int | r | هذه الثابتة هي قناع بت لأي من بتات flag الخاصة بالدوران. |
| TYPE_MASK_SCALE [static] | int | r | هذه الثابتة هي قناع بت لأي من بتات flag الخاصة بالمقياس. |
| TYPE_QUADRANT_ROTATION [static] | int | r | تشير هذه البتة flag إلى أن التحويل المحدد بواسطة هذا الكائن<br/> يقوم بدوران ربعي بضعف من 90 درجة<br/> بالإضافة إلى التحويلات المشار إليها بواسطة بتات flag الأخرى.<br/> يغيّر الدوران زوايا المتجهات بنفس المقدار بغض النظر عن الاتجاه الأصلي للمتجه ودون تغيير طول المتجه.<br/> هذه البتة flag متعارضة بشكل متبادل مع علم TypeGeneralRotation. |
| TYPE_TRANSLATION [static] | int | r | الترجمة تنقل الإحداثيات بمقدار ثابت في x<br/> و y دون تغيير طول المتجه أو زاويته. |
| TYPE_UNIFORM_SCALE [static] | int | r | المقياس المتساوي يضاعف طول المتجهات بنفس المقدار<br/>            في كل من الاتجاهين x و y دون تغيير الزاوية بين<br/>            المتجهات.<br/>            هذه البتة من العلامة متعارضة تمامًا مع علامة TypeGeneralScale. |
| elements | float | r | يحصل على مصفوفة من القيم العشرية التي تمثل عناصر هذا [Matrix](/psd/python-net/aspose.psd/matrix/). |
| m11 | float | r | يحصل على عنصر المصفوفة في الصف الأول والعمود الأول. يمثل المقياس على المحور X. |
| m12 | float | r | يحصل على عنصر المصفوفة في الصف الأول والعمود الثاني. يمثل القص على المحور Y. |
| m21 | float | r | يحصل على عنصر المصفوفة في الصف الثاني والعمود الأول. يمثل القص على المحور X. |
| m22 | float | r | يحصل على عنصر المصفوفة في الصف الثاني والعمود الثاني. يمثل المقياس على المحور Y. |
| m31 | float | r | يحصل على عنصر المصفوفة في الصف الثالث والعمود الأول. يمثل الإزاحة على المحور X. |
| m32 | float | r | يحصل على عنصر المصفوفة في الصف الثالث والعمود الأول. يمثل الإزاحة على المحور Y. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [get_elements()](#get_elements__1) | يحصل على نسخة من عناصر المصفوفة. |
| [multiply(tx)](#multiply_tx_2) | يضرب هذا Matrix بالمصفوفة المحددة في معامل matrix باستخدام ترتيب (الافتراضي) Prepend. |
| [multiply(tx, order)](#multiply_tx_order_3) | يضرب هذا Matrix بالمصفوفة المحددة في معامل matrix، وبالترتيب المحدد في معامل order. |
| reset() | يعيد تعيين هذا Matrix ليحتوي على عناصر مصفوفة الهوية. |
| [rotate(angle)](#rotate_angle_4) | يطبق دورانًا باتجاه عقارب الساعة بمقدار محدد في معامل الزاوية، حول الأصل (إحداثيات x و y صفر) لهذا Matrix بالترتيب الافتراضي (Prepend). |
| [rotate(angle, order)](#rotate_angle_order_5) | يطبق دورانًا باتجاه عقارب الساعة بمقدار محدد في معامل الزاوية، حول الأصل (إحداثيات x و y صفر) لهذا Matrix بالترتيب المحدد. |
| [rotate_at(angle, point)](#rotate_at_angle_point_6) | يطبق دورانًا باتجاه عقارب الساعة حول النقطة المحددة على هذا Matrix بالترتيب الافتراضي (Prepend). |
| [rotate_at(angle, point, order)](#rotate_at_angle_point_order_7) | يطبق دورانًا باتجاه عقارب الساعة حول النقطة المحددة على هذا Matrix بالترتيب المحدد. |
| [scale(scale_x, scale_y, order)](#scale_scale_x_scale_y_order_8) | يطبق متجه المقياس المحدد (scaleX و scaleY) على هذا [Matrix](/psd/python-net/aspose.psd/matrix/) باستخدام الترتيب المحدد. |
| [scale(sx, sy)](#scale_sx_sy_9) | يطبق متجه المقياس المحدد (scaleX و scaleY) على هذا Matrix باستخدام ترتيب (الافتراضي) Prepend. |
| [transform_points(points)](#transform_points_points_10) | يطبق التحويل الهندسي الممثل بهذا [Matrix](/psd/python-net/aspose.psd/matrix/) على مصفوفة محددة من النقاط. |
| [translate(offset_x, offset_y, order)](#translate_offset_x_offset_y_order_11) | يطبق متجه الإزاحة المحدد على هذه المصفوفة بالترتيب المحدد. |
| [translate(tx, ty)](#translate_tx_ty_12) | يطبق متجه الإزاحة المحدد على هذه [Matrix](/psd/python-net/aspose.psd/matrix/) باستخدام ترتيب (الافتراضي) Prepend. |


### Constructor: Matrix() {#Matrix__1}


```
 Matrix() 
```

ينشئ مثيلاً جديداً من فئة Matrix كمصفوفة الهوية.

### Constructor: Matrix(m11, m12, m21, m22, m31, m32) {#Matrix_m11_m12_m21_m22_m31_m32_2}


```
 Matrix(m11, m12, m21, m22, m31, m32) 
```

ينشئ مثيلاً جديداً من فئة [Matrix](/psd/python-net/aspose.psd/matrix/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| m11 | float | m00     M11     تحجيم X |
| m12 | float | m10     M12     قص Y |
| m21 | float | m01     M21     قص X |
| m22 | float | m11     M22     تحجيم Y |
| m31 | float | m02     M31     إزاحة X |
| m32 | float | m12     M32     إزاحة Y |

### Constructor: Matrix(origin) {#Matrix_origin_3}


```
 Matrix(origin) 
```

ينشئ نسخة من فئة [Matrix](/psd/python-net/aspose.psd/matrix/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| origin | [Matrix](/psd/python-net/aspose.psd/matrix) | مصفوفة أساسية للنسخ |

### Constructor: Matrix(rect, plgpts) {#Matrix_rect_plgpts_4}


```
 Matrix(rect, plgpts) 
```

ينشئ مثيلاً جديداً من فئة [Matrix](/psd/python-net/aspose.psd/matrix/) للتحويل الهندسي المحدد بواسطة المستطيل المحدد ومصفوفة النقاط.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | هيكل [RectangleF](/psd/python-net/aspose.psd/rectanglef/) الذي يمثل المستطيل الذي سيُحوَّل. |
| plgpts | [PointF[]](/psd/python-net/aspose.psd/pointf) | مصفوفة من ثلاثة هياكل [PointF](/psd/python-net/aspose.psd/pointf/) تمثل نقاط متوازي أضلاع التي سيُحوَّل إليها الزوايا العلوية اليسرى والعليا اليمنى والسفلية اليسرى للمستطيل. الزاوية السفلية اليمنى لمتوازي الأضلاع مفترضة بناءً على الزوايا الثلاث الأولى. |

### Constructor: Matrix(rect, plgpts) {#Matrix_rect_plgpts_5}


```
 Matrix(rect, plgpts) 
```

ينشئ مثيلاً جديداً من فئة [Matrix](/psd/python-net/aspose.psd/matrix/) للتحويل الهندسي المحدد بواسطة المستطيل المحدد ومصفوفة النقاط.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | هيكل [RectangleF](/psd/python-net/aspose.psd/rectanglef/) الذي يمثل المستطيل الذي سيُحوَّل. |
| plgpts | [Point[]](/psd/python-net/aspose.psd/point) | مصفوفة من ثلاثة هياكل [PointF](/psd/python-net/aspose.psd/pointf/) تمثل نقاط متوازي أضلاع التي سيُحوَّل إليها الزوايا العلوية اليسرى والعليا اليمنى والسفلية اليسرى للمستطيل. الزاوية السفلية اليمنى لمتوازي الأضلاع مفترضة بناءً على الزوايا الثلاث الأولى. |

### Method: get_elements() {#get_elements__1}


```
 get_elements() 
```

يحصل على نسخة من عناصر المصفوفة.

**Returns**

| النوع | الوصف |
| :- | :- |
| float | نسخة من عناصر المصفوفة. |


### Method: multiply(tx) {#multiply_tx_2}


```
 multiply(tx) 
```

يضرب هذا Matrix بالمصفوفة المحددة في معامل matrix باستخدام ترتيب (الافتراضي) Prepend.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| tx | [Matrix](/psd/python-net/aspose.psd/matrix) | المصفوفة التي سيتم الضرب معها. |

### Method: multiply(tx, order) {#multiply_tx_order_3}


```
 multiply(tx, order) 
```

يضرب هذا Matrix بالمصفوفة المحددة في معامل matrix، وبالترتيب المحدد في معامل order.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| tx | [Matrix](/psd/python-net/aspose.psd/matrix) | القيمة tx. القيمة tx. القيمة tx. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | الترتيب. الترتيب. الترتيب. |

### Method: rotate(angle) {#rotate_angle_4}


```
 rotate(angle) 
```

يطبق دورانًا باتجاه عقارب الساعة بمقدار محدد في معامل الزاوية، حول الأصل (إحداثيات x و y صفر) لهذا Matrix بالترتيب الافتراضي (Prepend).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| الزاوية | float | زاوية الدوران. |

### Method: rotate(angle, order) {#rotate_angle_order_5}


```
 rotate(angle, order) 
```

يطبق دورانًا باتجاه عقارب الساعة بمقدار محدد في معامل الزاوية، حول الأصل (إحداثيات x و y صفر) لهذا Matrix بالترتيب المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| الزاوية | float | زاوية الدوران. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | ترتيب المصفوفة. |

### Method: rotate_at(angle, point) {#rotate_at_angle_point_6}


```
 rotate_at(angle, point) 
```

يطبق دورانًا باتجاه عقارب الساعة حول النقطة المحددة على هذا Matrix بالترتيب الافتراضي (Prepend).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| الزاوية | float | الزاوية. |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | النقطة. |

### Method: rotate_at(angle, point, order) {#rotate_at_angle_point_order_7}


```
 rotate_at(angle, point, order) 
```

يطبق دورانًا باتجاه عقارب الساعة حول النقطة المحددة على هذا Matrix بالترتيب المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| الزاوية | float | الزاوية. |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | النقطة. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | الترتيب. |

### Method: scale(scale_x, scale_y, order) {#scale_scale_x_scale_y_order_8}


```
 scale(scale_x, scale_y, order) 
```

يطبق متجه المقياس المحدد (scaleX و scaleY) على هذا [Matrix](/psd/python-net/aspose.psd/matrix/) باستخدام الترتيب المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| scale_x | float | تحجيم X. |
| scale_y | float | تحجيم Y. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | الترتيب. |

### Method: scale(sx, sy) {#scale_sx_sy_9}


```
 scale(sx, sy) 
```

يطبق متجه المقياس المحدد (scaleX و scaleY) على هذا Matrix باستخدام ترتيب (الافتراضي) Prepend.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| sx | float | القيمة sx. القيمة sx. القيمة sx. |
| sy | float | القيمة sy. القيمة sy. القيمة sy. |

### Method: transform_points(points) {#transform_points_points_10}


```
 transform_points(points) 
```

يطبق التحويل الهندسي الممثل بهذا [Matrix](/psd/python-net/aspose.psd/matrix/) على مصفوفة محددة من النقاط.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | النقاط. |

### Method: translate(offset_x, offset_y, order) {#translate_offset_x_offset_y_order_11}


```
 translate(offset_x, offset_y, order) 
```

يطبق متجه الإزاحة المحدد على هذه المصفوفة بالترتيب المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| offset_x | float | الإزاحة X. |
| offset_y | float | الإزاحة Y. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | الترتيب. |

### Method: translate(tx, ty) {#translate_tx_ty_12}


```
 translate(tx, ty) 
```

يطبق متجه الإزاحة المحدد على هذه [Matrix](/psd/python-net/aspose.psd/matrix/) باستخدام ترتيب (الافتراضي) Prepend.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| tx | float | القيمة tx. القيمة tx. القيمة tx. |
| ty | float | النوع. النوع. النوع. |

