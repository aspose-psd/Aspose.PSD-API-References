---
title: "فئة RectangleF"
type: docs
weight: 3830
url: /ar/python-net/aspose.psd/rectanglef/
---

**Summary:** Stores a set of four floating-point numbers that represent the location and size of a rectangle.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.RectangleF

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [RectangleF()](#RectangleF__1) | يُنشئ نسخة جديدة من فئة RectangleF |
| [RectangleF(location, size)](#RectangleF_location_size_2) | يُنشئ نسخة جديدة من بنية [RectangleF](/psd/python-net/aspose.psd/rectanglef/) بالموقع والحجم المحددين. |
| [RectangleF(x, y, width, height)](#RectangleF_x_y_width_height_3) | يُنشئ نسخة جديدة من بنية [RectangleF](/psd/python-net/aspose.psd/rectanglef/) بالموقع والحجم المحددين. |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| bottom | float | r/w | يحصل أو يعيّن الإحداثي ص الذي هو مجموع [RectangleF.y](/psd/python-net/aspose.psd/rectanglef/) و [RectangleF.height](/psd/python-net/aspose.psd/rectanglef/) لهذه البنية [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| empty [static] | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | يحصل على نسخة جديدة من بنية [RectangleF](/psd/python-net/aspose.psd/rectanglef/) التي لها قيم [RectangleF.x](/psd/python-net/aspose.psd/rectanglef/)، [RectangleF.y](/psd/python-net/aspose.psd/rectanglef/)، [RectangleF.width](/psd/python-net/aspose.psd/rectanglef/) و [RectangleF.height](/psd/python-net/aspose.psd/rectanglef/) مضبوطة على الصفر. |
| height | float | r/w | يحصل أو يعيّن ارتفاع هذه البنية [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| is_empty | bool | r | يحصل على قيمة تشير إلى ما إذا كانت خاصية [RectangleF.width](/psd/python-net/aspose.psd/rectanglef/) أو [RectangleF.height](/psd/python-net/aspose.psd/rectanglef/) لهذه البنية [RectangleF](/psd/python-net/aspose.psd/rectanglef/) لها قيمة صفر. |
| left | float | r/w | يحصل أو يعيّن الإحداثي س للحافة اليسرى لهذه البنية [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| location | [PointF](/psd/python-net/aspose.psd/pointf) | r/w | يحصل أو يعيّن إحداثيات الزاوية العليا اليسرى لهذه البنية [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| right | float | r/w | يحصل أو يعيّن الإحداثي س الذي هو مجموع [RectangleF.x](/psd/python-net/aspose.psd/rectanglef/) و [RectangleF.width](/psd/python-net/aspose.psd/rectanglef/) لهذه البنية [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | r/w | يحصل أو يعيّن حجم هذه البنية [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| top | float | r/w | يحصل أو يعيّن الإحداثي ص للحافة العلوية لهذه البنية [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| width | float | r/w | يحصل أو يعيّن عرض هذه البنية [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| x | float | r/w | يحصل أو يعيّن الإحداثي س للزاوية العليا اليسرى لهذه البنية [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| y | float | r/w | يحصل أو يعيّن الإحداثي ص للزاوية العليا اليسرى لهذه البنية [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [contains(point)](#contains_point_1) | يحدد ما إذا كانت النقطة المحددة موجودة داخل هذه البنية [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [contains(rect)](#contains_rect_2) | يحدد ما إذا كانت المنطقة المستطيلة الممثلة بـ <paramref name="rect" /> موجودة بالكامل داخل هذا الهيكل [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [contains(x, y)](#contains_x_y_3) | يحدد ما إذا كانت النقطة المحددة موجودة داخل هذه البنية [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [from_left_top_right_bottom(left, top, right, bottom)](#from_left_top_right_bottom_left_top_right_bottom_4) | ينشئ هيكلاً من نوع [RectangleF](/psd/python-net/aspose.psd/rectanglef/) بزاوية علوية يسرى وزاوية سفلية يمنى في المواقع المحددة. |
| [from_points(point1, point2)](#from_points_point1_point2_5) | ينشئ [Rectangle](/psd/python-net/aspose.psd/rectangle/) جديدًا من نقطتين محددتين. ستكون رؤوس المستطيل المُنشأ مساوية للقيمتين <paramref name="point1" /> و <paramref name="point2" />. عادةً ما تكون هذه هي الرؤوس المتقابلة. |
| [inflate(rect, x, y)](#inflate_rect_x_y_6) | ينشئ ويعيد نسخة مُوسعة من الهيكل [RectangleF](/psd/python-net/aspose.psd/rectanglef/) المحدد. يتم توسيع النسخة بالمقدار المحدد. يظل المستطيل الأصلي غير معدل. |
| [inflate(size)](#inflate_size_7) | يوسع هذا [RectangleF](/psd/python-net/aspose.psd/rectanglef/) بالمقدار المحدد. |
| [inflate(x, y)](#inflate_x_y_8) | يوسع هيكل [RectangleF](/psd/python-net/aspose.psd/rectanglef/) هذا بالمقدار المحدد. |
| [intersect(a, b)](#intersect_a_b_9) | يعيد هيكلاً من نوع [RectangleF](/psd/python-net/aspose.psd/rectanglef/) يمثل تقاطع مستطيلين. إذا لم يكن هناك تقاطع، يتم إرجاع [RectangleF](/psd/python-net/aspose.psd/rectanglef/) فارغ. |
| [intersect(rect)](#intersect_rect_10) | يستبدل هذا الهيكل [RectangleF](/psd/python-net/aspose.psd/rectanglef/) بالتقاطع بينه وبين الهيكل [RectangleF](/psd/python-net/aspose.psd/rectanglef/) المحدد. |
| [intersects_with(rect)](#intersects_with_rect_11) | يحدد ما إذا كان هذا المستطيل يتقاطع مع <paramref name="rect" />. |
| normalize() | يضبط المستطيل بحيث يصبح عرضه وارتفاعه إيجابيين، ويكون الجانب الأيسر أصغر من الأيمن والعلوي أصغر من السفلي. |
| [offset(pos)](#offset_pos_12) | يضبط موقع هذا المستطيل بالمقدار المحدد. |
| [offset(x, y)](#offset_x_y_13) | يضبط موقع هذا المستطيل بالمقدار المحدد. |
| [union(a, b)](#union_a_b_14) | ينشئ أصغر مستطيل ثالث ممكن يمكنه احتواء المستطيلين الذين يشكلان اتحادًا. |


### Constructor: RectangleF() {#RectangleF__1}


```
 RectangleF() 
```

يُنشئ نسخة جديدة من فئة RectangleF

### Constructor: RectangleF(location, size) {#RectangleF_location_size_2}


```
 RectangleF(location, size) 
```

يُنشئ نسخة جديدة من بنية [RectangleF](/psd/python-net/aspose.psd/rectanglef/) بالموقع والحجم المحددين.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| location | [PointF](/psd/python-net/aspose.psd/pointf) | نقطة من نوع [PointF](/psd/python-net/aspose.psd/pointf/) تمثل الزاوية العلوية اليسرى للمنطقة المستطيلة. |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | كائن من نوع [SizeF](/psd/python-net/aspose.psd/sizef/) يمثل عرض وارتفاع المنطقة المستطيلة. |

### Constructor: RectangleF(x, y, width, height) {#RectangleF_x_y_width_height_3}


```
 RectangleF(x, y, width, height) 
```

يُنشئ نسخة جديدة من بنية [RectangleF](/psd/python-net/aspose.psd/rectanglef/) بالموقع والحجم المحددين.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| x | float | الإحداثي السيني للزاوية العلوية اليسرى للمستطيل. |
| y | float | الإحداثي الصادي للزاوية العلوية اليسرى للمستطيل. |
| width | float | عرض المستطيل. |
| الارتفاع | float | ارتفاع المستطيل. |

### Method: contains(point) {#contains_point_1}


```
 contains(point) 
```

يحدد ما إذا كانت النقطة المحددة موجودة داخل هذه البنية [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | نقطة [PointF](/psd/python-net/aspose.psd/pointf/) للاختبار. |

**Returns**

| النوع | الوصف |
| :- | :- |
| bool | تعيد هذه الطريقة true إذا كانت النقطة الممثلة بالمعامل <paramref name="point" /> موجودة داخل هذا الهيكل [RectangleF](/psd/python-net/aspose.psd/rectanglef/); وإلا false. |


### Method: contains(rect) {#contains_rect_2}


```
 contains(rect) 
```

يحدد ما إذا كانت المنطقة المستطيلة الممثلة بـ <paramref name="rect" /> موجودة بالكامل داخل هذا الهيكل [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) للاختبار. |

**Returns**

| النوع | الوصف |
| :- | :- |
| bool | تعيد هذه الطريقة true إذا كانت المنطقة المستطيلة الممثلة بـ <paramref name="rect" /> موجودة بالكامل داخل المنطقة المستطيلة الممثلة بهذا [RectangleF](/psd/python-net/aspose.psd/rectanglef/); وإلا false. |


### Method: contains(x, y) {#contains_x_y_3}


```
 contains(x, y) 
```

يحدد ما إذا كانت النقطة المحددة موجودة داخل هذه البنية [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| x | float | الإحداثي السيني للنقطة المراد اختبارها. |
| y | float | الإحداثي الصادي للنقطة المراد اختبارها. |

**Returns**

| النوع | الوصف |
| :- | :- |
| bool | ترجع هذه الطريقة true إذا كانت النقطة المحددة بواسطة <paramref name="x" /> و <paramref name="y" /> موجودة داخل بنية [RectangleF](/psd/python-net/aspose.psd/rectanglef/) هذه؛ وإلا false. |


### Method: from_left_top_right_bottom(left, top, right, bottom)  [static] {#from_left_top_right_bottom_left_top_right_bottom_4}


```
 from_left_top_right_bottom(left, top, right, bottom) 
```

ينشئ هيكلاً من نوع [RectangleF](/psd/python-net/aspose.psd/rectanglef/) بزاوية علوية يسرى وزاوية سفلية يمنى في المواقع المحددة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| left | float | الإحداثي x للزاوية العلوية اليسرى للمنطقة المستطيلة. |
| أعلى | float | الإحداثي y للزاوية العلوية اليسرى للمنطقة المستطيلة. |
| right | float | الإحداثي x للزاوية السفلية اليمنى للمنطقة المستطيلة. |
| أسفل | float | الإحداثي y للزاوية السفلية اليمنى للمنطقة المستطيلة. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | الـ [RectangleF](/psd/python-net/aspose.psd/rectanglef/) الجديد الذي تنشئه هذه الطريقة. |


### Method: from_points(point1, point2)  [static] {#from_points_point1_point2_5}


```
 from_points(point1, point2) 
```

ينشئ [Rectangle](/psd/python-net/aspose.psd/rectangle/) جديدًا من نقطتين محددتين. ستكون رؤوس المستطيل المُنشأ مساوية للقيمتين <paramref name="point1" /> و <paramref name="point2" />. عادةً ما تكون هذه هي الرؤوس المتقابلة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| point1 | [PointF](/psd/python-net/aspose.psd/pointf) | النقطة الأولى [Point](/psd/python-net/aspose.psd/point/) للمستطيل الجديد. |
| point2 | [PointF](/psd/python-net/aspose.psd/pointf) | النقطة الثانية [Point](/psd/python-net/aspose.psd/point/) للمستطيل الجديد. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | تم إنشاء [Rectangle](/psd/python-net/aspose.psd/rectangle/) حديثًا. |


### Method: inflate(rect, x, y)  [static] {#inflate_rect_x_y_6}


```
 inflate(rect, x, y) 
```

ينشئ ويعيد نسخة مُوسعة من الهيكل [RectangleF](/psd/python-net/aspose.psd/rectanglef/) المحدد. يتم توسيع النسخة بالمقدار المحدد. يظل المستطيل الأصلي غير معدل.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) الذي سيُنسخ. هذا المستطيل غير معدل. |
| x | float | القيمة لتوسيع نسخة المستطيل أفقيًا. |
| y | float | القيمة لتوسيع نسخة المستطيل عموديًا. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) الموسع. |


### Method: inflate(size) {#inflate_size_7}


```
 inflate(size) 
```

يوسع هذا [RectangleF](/psd/python-net/aspose.psd/rectanglef/) بالمقدار المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | القيمة لتوسيع هذا المستطيل. |

### Method: inflate(x, y) {#inflate_x_y_8}


```
 inflate(x, y) 
```

يوسع هيكل [RectangleF](/psd/python-net/aspose.psd/rectanglef/) هذا بالمقدار المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| x | float | القيمة لتوسيع بنية [RectangleF](/psd/python-net/aspose.psd/rectanglef/) هذه أفقيًا. |
| y | float | القيمة لتوسيع بنية [RectangleF](/psd/python-net/aspose.psd/rectanglef/) هذه عموديًا. |

### Method: intersect(a, b)  [static] {#intersect_a_b_9}


```
 intersect(a, b) 
```

يعيد هيكلاً من نوع [RectangleF](/psd/python-net/aspose.psd/rectanglef/) يمثل تقاطع مستطيلين. إذا لم يكن هناك تقاطع، يتم إرجاع [RectangleF](/psd/python-net/aspose.psd/rectanglef/) فارغ.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| a | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | المستطيل الأول للتقاطع. |
| b | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | المستطيل الثاني للتقاطع. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | بنية [RectangleF](/psd/python-net/aspose.psd/rectanglef/) الثالثة التي يمثل حجمها المنطقة المتداخلة بين المستطيلين المحددين. |


### Method: intersect(rect) {#intersect_rect_10}


```
 intersect(rect) 
```

يستبدل هذا الهيكل [RectangleF](/psd/python-net/aspose.psd/rectanglef/) بالتقاطع بينه وبين الهيكل [RectangleF](/psd/python-net/aspose.psd/rectanglef/) المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | المستطيل للتقاطع. |

### Method: intersects_with(rect) {#intersects_with_rect_11}


```
 intersects_with(rect) 
```

يحدد ما إذا كان هذا المستطيل يتقاطع مع <paramref name="rect" />.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | المستطيل للاختبار. |

**Returns**

| النوع | الوصف |
| :- | :- |
| bool | ترجع هذه الطريقة true إذا كان هناك أي تقاطع. |


### Method: offset(pos) {#offset_pos_12}


```
 offset(pos) 
```

يضبط موقع هذا المستطيل بالمقدار المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| pos | [PointF](/psd/python-net/aspose.psd/pointf) | القيمة لإزاحة الموقع. |

### Method: offset(x, y) {#offset_x_y_13}


```
 offset(x, y) 
```

يضبط موقع هذا المستطيل بالمقدار المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| x | float | القيمة لإزاحة الموقع أفقيًا. |
| y | float | القيمة لإزاحة الموقع عموديًا. |

### Method: union(a, b)  [static] {#union_a_b_14}


```
 union(a, b) 
```

ينشئ أصغر مستطيل ثالث ممكن يمكنه احتواء المستطيلين الذين يشكلان اتحادًا.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| a | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | المستطيل الأول للاتحاد. |
| b | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | المستطيل الثاني للاتحاد. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | الهيكل الثالث [RectangleF](/psd/python-net/aspose.psd/rectanglef/) الذي يحتوي على كلا المستطيلين اللذين يشكلان الاتحاد. |


