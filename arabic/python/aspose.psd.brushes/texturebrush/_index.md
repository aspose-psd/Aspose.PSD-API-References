---
title: "فئة TextureBrush"
type: docs
weight: 90
url: /ar/python-net/aspose.psd.brushes/texturebrush/
---

**Summary:** Each property of the [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) class is a [Brush](/psd/python-net/aspose.psd/brush/) object that uses an image to fill the interior of a shape. This class cannot be inherited.

**Module:** [aspose.psd.brushes](/psd/python-net/aspose.psd.brushes/)

**Full Name:** aspose.psd.brushes.TextureBrush

**Inheritance:** TransformBrush

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [TextureBrush(image)](#TextureBrush_image_1) | يُنشئ مثلاً جديدًا من الفئة [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) التي تستخدم الصورة المحددة. |
| [TextureBrush(image, destination_rectangle)](#TextureBrush_image_destination_rectangle_2) | يُنشئ مثلاً جديدًا من الفئة [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) التي تستخدم الصورة المحددة والمستطيل المحيط. |
| [TextureBrush(image, destination_rectangle)](#TextureBrush_image_destination_rectangle_3) | يُنشئ مثلاً جديدًا من الفئة [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) التي تستخدم الصورة المحددة والمستطيل المحيط. |
| [TextureBrush(image, destination_rectangle, image_attributes)](#TextureBrush_image_destination_rectangle_image_attributes_4) | يُنشئ مثلاً جديدًا من الفئة [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) التي تستخدم الصورة المحددة، والمستطيل المحيط، وخصائص الصورة. |
| [TextureBrush(image, destination_rectangle, image_attributes)](#TextureBrush_image_destination_rectangle_image_attributes_5) | يُنشئ مثلاً جديدًا من الفئة [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) التي تستخدم الصورة المحددة، والمستطيل المحيط، وخصائص الصورة. |
| [TextureBrush(image, wrap_mode)](#TextureBrush_image_wrap_mode_6) | يُنشئ مثلاً جديدًا من الفئة [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) التي تستخدم الصورة المحددة ووضع الالتفاف. |
| [TextureBrush(image, wrap_mode, destination_rectangle)](#TextureBrush_image_wrap_mode_destination_rectangle_7) | يُنشئ مثلاً جديدًا من الفئة [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) التي تستخدم الصورة المحددة، وضع الالتفاف، والمستطيل المحيط. |
| [TextureBrush(image, wrap_mode, destination_rectangle)](#TextureBrush_image_wrap_mode_destination_rectangle_8) | يُنشئ مثلاً جديدًا من الفئة [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) التي تستخدم الصورة المحددة، وضع الالتفاف، والمستطيل المحيط. |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| disposed | bool | r | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن قد تم التخلص منه. |
| image | [Image](/psd/python-net/aspose.psd/image) | r | يحصل على كائن [Image](/psd/python-net/aspose.psd/image/) المرتبط بهذا كائن [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/). |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | r | يحصل على [TextureBrush.image_attributes](/psd/python-net/aspose.psd.brushes/texturebrush/) المرتبط بهذا [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/). |
| image_rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | يحصل على كائن [Rectangle](/psd/python-net/aspose.psd/rectangle/) المرتبط بهذا [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/). |
| is_transform_changed | bool | r | يحصل على قيمة تشير إلى ما إذا كانت التحويلات قد تغيرت بطريقة ما. على سبيل المثال ضبط مصفوفة التحويل أو<br/>            استدعاء أي من الطرق التي تغير مصفوفة التحويل. تم تقديم الخاصية لضمان التوافق العكسي مع GDI+. |
| opacity | float | r/w | يحصل أو يضبط شفافية الفرشاة. يجب أن تكون القيمة بين 0 و 1. القيمة 0 تعني أن الفرشاة مرئية بالكامل، والقيمة 1 تعني أن الفرشاة معتمة بالكامل. |
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


### Constructor: TextureBrush(image) {#TextureBrush_image_1}


```
 TextureBrush(image) 
```

يُنشئ مثلاً جديدًا من الفئة [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) التي تستخدم الصورة المحددة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | كائن [Image](/psd/python-net/aspose.psd/image/) الذي يستخدمه هذا [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) لملء الداخل. |

### Constructor: TextureBrush(image, destination_rectangle) {#TextureBrush_image_destination_rectangle_2}


```
 TextureBrush(image, destination_rectangle) 
```

يُنشئ مثلاً جديدًا من الفئة [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) التي تستخدم الصورة المحددة والمستطيل المحيط.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | كائن [Image](/psd/python-net/aspose.psd/image/) الذي يستخدمه هذا [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) لملء الداخل. |
| destination_rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | هيكل [RectangleF](/psd/python-net/aspose.psd/rectanglef/) الذي يمثل المستطيل المحيط لهذا [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/). |

### Constructor: TextureBrush(image, destination_rectangle) {#TextureBrush_image_destination_rectangle_3}


```
 TextureBrush(image, destination_rectangle) 
```

يُنشئ مثلاً جديدًا من الفئة [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) التي تستخدم الصورة المحددة والمستطيل المحيط.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | كائن [Image](/psd/python-net/aspose.psd/image/) الذي يستخدمه هذا [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) لملء الداخل. |
| destination_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | هيكل [RectangleF](/psd/python-net/aspose.psd/rectanglef/) الذي يمثل المستطيل المحيط لهذا [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/). |

### Constructor: TextureBrush(image, destination_rectangle, image_attributes) {#TextureBrush_image_destination_rectangle_image_attributes_4}


```
 TextureBrush(image, destination_rectangle, image_attributes) 
```

يُنشئ مثلاً جديدًا من الفئة [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) التي تستخدم الصورة المحددة، والمستطيل المحيط، وخصائص الصورة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | كائن [Image](/psd/python-net/aspose.psd/image/) الذي يستخدمه هذا [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) لملء الداخل. |
| destination_rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | هيكل [RectangleF](/psd/python-net/aspose.psd/rectanglef/) الذي يمثل المستطيل المحيط لهذا [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/). |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | كائن [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) يحتوي على معلومات إضافية حول الصورة المستخدمة بواسطة هذا كائن [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/). |

### Constructor: TextureBrush(image, destination_rectangle, image_attributes) {#TextureBrush_image_destination_rectangle_image_attributes_5}


```
 TextureBrush(image, destination_rectangle, image_attributes) 
```

يُنشئ مثلاً جديدًا من الفئة [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) التي تستخدم الصورة المحددة، والمستطيل المحيط، وخصائص الصورة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | كائن [Image](/psd/python-net/aspose.psd/image/) الذي يستخدمه هذا [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) لملء الداخل. |
| destination_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | هيكل [RectangleF](/psd/python-net/aspose.psd/rectanglef/) الذي يمثل المستطيل المحيط لهذا [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/). |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | كائن [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) يحتوي على معلومات إضافية حول الصورة المستخدمة بواسطة هذا كائن [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/). |

### Constructor: TextureBrush(image, wrap_mode) {#TextureBrush_image_wrap_mode_6}


```
 TextureBrush(image, wrap_mode) 
```

يُنشئ مثلاً جديدًا من الفئة [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) التي تستخدم الصورة المحددة ووضع الالتفاف.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | كائن [Image](/psd/python-net/aspose.psd/image/) الذي يستخدمه هذا [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) لملء الداخل. |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | تعداد [WrapMode](/psd/python-net/aspose.psd/wrapmode/) يحدد كيفية تجانب هذا كائن [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/). |

### Constructor: TextureBrush(image, wrap_mode, destination_rectangle) {#TextureBrush_image_wrap_mode_destination_rectangle_7}


```
 TextureBrush(image, wrap_mode, destination_rectangle) 
```

يُنشئ مثلاً جديدًا من الفئة [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) التي تستخدم الصورة المحددة، وضع الالتفاف، والمستطيل المحيط.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | كائن [Image](/psd/python-net/aspose.psd/image/) الذي يستخدمه هذا [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) لملء الداخل. |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | تعداد [WrapMode](/psd/python-net/aspose.psd/wrapmode/) يحدد كيفية تجانب هذا كائن [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/). |
| destination_rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | هيكل [RectangleF](/psd/python-net/aspose.psd/rectanglef/) الذي يمثل المستطيل المحيط لهذا [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/). |

### Constructor: TextureBrush(image, wrap_mode, destination_rectangle) {#TextureBrush_image_wrap_mode_destination_rectangle_8}


```
 TextureBrush(image, wrap_mode, destination_rectangle) 
```

يُنشئ مثلاً جديدًا من الفئة [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) التي تستخدم الصورة المحددة، وضع الالتفاف، والمستطيل المحيط.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | كائن [Image](/psd/python-net/aspose.psd/image/) الذي يستخدمه هذا [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) لملء الداخل. |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | تعداد [WrapMode](/psd/python-net/aspose.psd/wrapmode/) يحدد كيفية تجانب هذا كائن [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/). |
| destination_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | هيكل [RectangleF](/psd/python-net/aspose.psd/rectanglef/) الذي يمثل المستطيل المحيط لهذا [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/). |

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

