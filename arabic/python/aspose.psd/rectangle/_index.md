---
title: "فئة Rectangle"
type: docs
weight: 3810
url: /ar/python-net/aspose.psd/rectangle/
---

**Summary:** Stores a set of four integers that represent the location and size of a rectangle.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Rectangle

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [Rectangle()](#Rectangle__1) | يُهيئ نسخة جديدة من فئة Rectangle. |
| [Rectangle(location, size)](#Rectangle_location_size_2) | يُهيئ نسخة جديدة من بنية [Rectangle](/psd/python-net/aspose.psd/rectangle/) بالموقع والحجم المحددين. |
| [Rectangle(x, y, width, height)](#Rectangle_x_y_width_height_3) | يُهيئ نسخة جديدة من بنية [Rectangle](/psd/python-net/aspose.psd/rectangle/) بالموقع والحجم المحددين. |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| bottom | int | r/w | يحصل أو يعيّن إحداثي y الذي هو مجموع قيمتي الخاصيتين [Rectangle.y](/psd/python-net/aspose.psd/rectangle/) و [Rectangle.height](/psd/python-net/aspose.psd/rectangle/) لهذه البنية [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| empty [static] | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | يحصل على نسخة جديدة من بنية [Rectangle](/psd/python-net/aspose.psd/rectangle/) التي تكون قيم [Rectangle.x](/psd/python-net/aspose.psd/rectangle/)، [Rectangle.y](/psd/python-net/aspose.psd/rectangle/)، [Rectangle.width](/psd/python-net/aspose.psd/rectangle/) و [Rectangle.height](/psd/python-net/aspose.psd/rectangle/) فيها صفرًا. |
| height | int | r/w | يحصل أو يعيّن ارتفاع هذه البنية [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| is_empty | bool | r | يحصل على قيمة تشير إلى ما إذا كانت جميع الخصائص الرقمية لهذه البنية [Rectangle](/psd/python-net/aspose.psd/rectangle/) لها قيم صفر. |
| left | int | r/w | يحصل أو يعيّن إحداثي x للحافة اليسرى لهذه البنية [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| location | [Point](/psd/python-net/aspose.psd/point) | r/w | يحصل أو يعيّن إحداثيات الزاوية العليا اليسرى لهذه البنية [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| right | int | r/w | يحصل أو يعيّن إحداثي x الذي هو مجموع قيمتي الخاصيتين [Rectangle.x](/psd/python-net/aspose.psd/rectangle/) و [Rectangle.width](/psd/python-net/aspose.psd/rectangle/) لهذه البنية [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| size | [Size](/psd/python-net/aspose.psd/size) | r/w | يحصل أو يعيّن حجم هذه البنية [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| top | int | r/w | يحصل أو يعيّن إحداثي y للحافة العليا لهذه البنية [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| width | int | r/w | يحصل أو يعيّن عرض هذه البنية [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| x | int | r/w | يحصل أو يعيّن إحداثي x للزاوية العليا اليسرى لهذه البنية [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| y | int | r/w | يحصل أو يعيّن إحداثي y للزاوية العليا اليسرى لهذه البنية [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [ceiling(value)](#ceiling_value_1) | يحوّل بنية [RectangleF](/psd/python-net/aspose.psd/rectanglef/) المحددة إلى بنية [Rectangle](/psd/python-net/aspose.psd/rectangle/) عن طريق تقريب قيم [RectangleF](/psd/python-net/aspose.psd/rectanglef/) إلى أقرب عدد صحيح أعلى. |
| [contains(point)](#contains_point_2) | يحدد ما إذا كانت النقطة المحددة موجودة داخل هذه البنية [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| [contains(rect)](#contains_rect_3) | يحدد ما إذا كانت المنطقة المستطيلة التي يمثلها <paramref name="rect" /> موجودة بالكامل داخل هذه البنية [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| [contains(x, y)](#contains_x_y_4) | يحدد ما إذا كانت النقطة المحددة موجودة داخل هذه البنية [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| [from_left_top_right_bottom(left, top, right, bottom)](#from_left_top_right_bottom_left_top_right_bottom_5) | ينشئ بنية [Rectangle](/psd/python-net/aspose.psd/rectangle/) بالمواقع المحددة للحواف. |
| [from_points(point1, point2)](#from_points_point1_point2_6) | ينشئ [Rectangle] جديدًا من نقطتين محددتين. سيكون الجانبان العموديان للـ [Rectangle] المُنشأ مساويين للنقطتين <paramref name="point1" /> و <paramref name="point2" /> الممرّتين. عادةً ما تكون هاتان النقطتان رؤوسًا متقابلة. |
| [inflate(rect, x, y)](#inflate_rect_x_y_7) | ينشئ ويعيد نسخة مُضخمة من بنية [Rectangle](/psd/python-net/aspose.psd/rectangle/) المحددة. يتم تضخيم النسخة بالمقدار المحدد. تظل بنية [Rectangle](/psd/python-net/aspose.psd/rectangle/) الأصلية دون تعديل. |
| [inflate(size)](#inflate_size_8) | يوسع هذا [Rectangle](/psd/python-net/aspose.psd/rectangle/) بالمقدار المحدد. |
| [inflate(width, height)](#inflate_width_height_9) | يوسع هذا [Rectangle](/psd/python-net/aspose.psd/rectangle/) بالمقدار المحدد. |
| [intersect(a, b)](#intersect_a_b_10) | يعيد بنية [Rectangle](/psd/python-net/aspose.psd/rectangle/) ثالثة تمثل تقاطع بنيتين [Rectangle](/psd/python-net/aspose.psd/rectangle/) أخريين. إذا لم يكن هناك تقاطع، يتم إرجاع [Rectangle](/psd/python-net/aspose.psd/rectangle/) فارغ. |
| [intersect(rect)](#intersect_rect_11) | يستبدل هذا [Rectangle](/psd/python-net/aspose.psd/rectangle/) بتقاطع نفسه مع [Rectangle](/psd/python-net/aspose.psd/rectangle/) المحدد. |
| [intersects_with(rect)](#intersects_with_rect_12) | يحدد ما إذا كان هذا المستطيل يتقاطع مع <paramref name="rect" />. |
| normalize() | يضبط المستطيل بحيث يصبح عرضه وارتفاعه إيجابيين، ويكون الجانب الأيسر أصغر من الأيمن والعلوي أصغر من السفلي. |
| [offset(pos)](#offset_pos_13) | يضبط موقع هذا المستطيل بالمقدار المحدد. |
| [offset(x, y)](#offset_x_y_14) | يضبط موقع هذا المستطيل بالمقدار المحدد. |
| [round(value)](#round_value_15) | يحوّل [RectangleF](/psd/python-net/aspose.psd/rectanglef/) المحدد إلى [Rectangle](/psd/python-net/aspose.psd/rectangle/) عن طريق تقريب قيم [RectangleF](/psd/python-net/aspose.psd/rectanglef/) إلى أقرب قيم صحيحة. |
| [truncate(value)](#truncate_value_16) | يحوّل [RectangleF](/psd/python-net/aspose.psd/rectanglef/) المحدد إلى [Rectangle](/psd/python-net/aspose.psd/rectangle/) عن طريق قطع قيم [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [union(a, b)](#union_a_b_17) | يحصل على بنية [Rectangle](/psd/python-net/aspose.psd/rectangle/) تحتوي على اتحاد بنيتين [Rectangle](/psd/python-net/aspose.psd/rectangle/). |


### Constructor: Rectangle() {#Rectangle__1}


```
 Rectangle() 
```

يُهيئ نسخة جديدة من فئة Rectangle.

### Constructor: Rectangle(location, size) {#Rectangle_location_size_2}


```
 Rectangle(location, size) 
```

يُهيئ نسخة جديدة من بنية [Rectangle](/psd/python-net/aspose.psd/rectangle/) بالموقع والحجم المحددين.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| location | [Point](/psd/python-net/aspose.psd/point) | [Point](/psd/python-net/aspose.psd/point/) يمثل الزاوية العليا اليسرى للمنطقة المستطيلة. |
| size | [Size](/psd/python-net/aspose.psd/size) | [Size](/psd/python-net/aspose.psd/size/) يمثل العرض والارتفاع للمنطقة المستطيلة. |

### Constructor: Rectangle(x, y, width, height) {#Rectangle_x_y_width_height_3}


```
 Rectangle(x, y, width, height) 
```

يُهيئ نسخة جديدة من بنية [Rectangle](/psd/python-net/aspose.psd/rectangle/) بالموقع والحجم المحددين.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| x | int | الإحداثي السيني للزاوية العلوية اليسرى للمستطيل. |
| y | int | الإحداثي الصادي للزاوية العلوية اليسرى للمستطيل. |
| width | int | عرض المستطيل. |
| الارتفاع | int | ارتفاع المستطيل. |

### Method: ceiling(value)  [static] {#ceiling_value_1}


```
 ceiling(value) 
```

يحوّل بنية [RectangleF](/psd/python-net/aspose.psd/rectanglef/) المحددة إلى بنية [Rectangle](/psd/python-net/aspose.psd/rectangle/) عن طريق تقريب قيم [RectangleF](/psd/python-net/aspose.psd/rectanglef/) إلى أقرب عدد صحيح أعلى.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| value | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | بنية [RectangleF](/psd/python-net/aspose.psd/rectanglef/) التي سيتم تحويلها. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | يعيد [Rectangle](/psd/python-net/aspose.psd/rectangle/). |


### Method: contains(point) {#contains_point_2}


```
 contains(point) 
```

يحدد ما إذا كانت النقطة المحددة موجودة داخل هذه البنية [Rectangle](/psd/python-net/aspose.psd/rectangle/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | [Point](/psd/python-net/aspose.psd/point/) للاختبار. |

**Returns**

| النوع | الوصف |
| :- | :- |
| bool | تعيد هذه الطريقة true إذا كانت النقطة الممثلة بـ <paramref name=\"point\" /> موجودة داخل بنية [Rectangle](/psd/python-net/aspose.psd/rectangle/); وإلا false. |


### Method: contains(rect) {#contains_rect_3}


```
 contains(rect) 
```

يحدد ما إذا كانت المنطقة المستطيلة التي يمثلها <paramref name="rect" /> موجودة بالكامل داخل هذه البنية [Rectangle](/psd/python-net/aspose.psd/rectangle/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | [Rectangle](/psd/python-net/aspose.psd/rectangle/) للاختبار. |

**Returns**

| النوع | الوصف |
| :- | :- |
| bool | تعيد هذه الطريقة true إذا كانت المنطقة المستطيلة الممثلة بـ <paramref name=\"rect\" /> موجودة بالكامل داخل بنية [Rectangle](/psd/python-net/aspose.psd/rectangle/); وإلا false. |


### Method: contains(x, y) {#contains_x_y_4}


```
 contains(x, y) 
```

يحدد ما إذا كانت النقطة المحددة موجودة داخل هذه البنية [Rectangle](/psd/python-net/aspose.psd/rectangle/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| x | int | الإحداثي السيني للنقطة المراد اختبارها. |
| y | int | الإحداثي الصادي للنقطة المراد اختبارها. |

**Returns**

| النوع | الوصف |
| :- | :- |
| bool | تعيد هذه الطريقة true إذا كانت النقطة المحددة بـ <paramref name=\"x\" /> و <paramref name=\"y\" /> موجودة داخل بنية [Rectangle](/psd/python-net/aspose.psd/rectangle/); وإلا false. |


### Method: from_left_top_right_bottom(left, top, right, bottom)  [static] {#from_left_top_right_bottom_left_top_right_bottom_5}


```
 from_left_top_right_bottom(left, top, right, bottom) 
```

ينشئ بنية [Rectangle](/psd/python-net/aspose.psd/rectangle/) بالمواقع المحددة للحواف.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| left | int | الإحداثي السيني للزاوية العليا اليسرى لهذه بنية [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| top | int | الإحداثي الصادي للزاوية العليا اليسرى لهذه بنية [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| right | int | الإحداثي السيني للزاوية السفلية اليمنى لهذه بنية [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| bottom | int | الإحداثي الصادي للزاوية السفلية اليمنى لهذه بنية [Rectangle](/psd/python-net/aspose.psd/rectangle/). |

**Returns**

| النوع | الوصف |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | [Rectangle](/psd/python-net/aspose.psd/rectangle/) الجديد الذي تنشئه هذه الطريقة. |


### Method: from_points(point1, point2)  [static] {#from_points_point1_point2_6}


```
 from_points(point1, point2) 
```

ينشئ [Rectangle] جديدًا من نقطتين محددتين. سيكون الجانبان العموديان للـ [Rectangle] المُنشأ مساويين للنقطتين <paramref name="point1" /> و <paramref name="point2" /> الممرّتين. عادةً ما تكون هاتان النقطتان رؤوسًا متقابلة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| point1 | [Point](/psd/python-net/aspose.psd/point) | النقطة الأولى [Point](/psd/python-net/aspose.psd/point/) للمستطيل الجديد. |
| point2 | [Point](/psd/python-net/aspose.psd/point) | النقطة الثانية [Point](/psd/python-net/aspose.psd/point/) للمستطيل الجديد. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | تم إنشاء [Rectangle](/psd/python-net/aspose.psd/rectangle/) حديثًا. |


### Method: inflate(rect, x, y)  [static] {#inflate_rect_x_y_7}


```
 inflate(rect, x, y) 
```

ينشئ ويعيد نسخة مُضخمة من بنية [Rectangle](/psd/python-net/aspose.psd/rectangle/) المحددة. يتم تضخيم النسخة بالمقدار المحدد. تظل بنية [Rectangle](/psd/python-net/aspose.psd/rectangle/) الأصلية دون تعديل.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | [Rectangle](/psd/python-net/aspose.psd/rectangle/) للبدء به. هذا المستطيل غير معدل. |
| x | int | المقدار لتوسيع هذا [Rectangle](/psd/python-net/aspose.psd/rectangle/) أفقيًا. |
| y | int | المقدار لتوسيع هذا [Rectangle](/psd/python-net/aspose.psd/rectangle/) عموديًا. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | [Rectangle](/psd/python-net/aspose.psd/rectangle/) الموسع. |


### Method: inflate(size) {#inflate_size_8}


```
 inflate(size) 
```

يوسع هذا [Rectangle](/psd/python-net/aspose.psd/rectangle/) بالمقدار المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| size | [Size](/psd/python-net/aspose.psd/size) | القيمة لتوسيع هذا المستطيل. |

### Method: inflate(width, height) {#inflate_width_height_9}


```
 inflate(width, height) 
```

يوسع هذا [Rectangle](/psd/python-net/aspose.psd/rectangle/) بالمقدار المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| width | int | المقدار لتوسيع هذا [Rectangle](/psd/python-net/aspose.psd/rectangle/) أفقيًا. |
| height | int | المقدار لتوسيع هذا [Rectangle](/psd/python-net/aspose.psd/rectangle/) عموديًا. |

### Method: intersect(a, b)  [static] {#intersect_a_b_10}


```
 intersect(a, b) 
```

يعيد بنية [Rectangle](/psd/python-net/aspose.psd/rectangle/) ثالثة تمثل تقاطع بنيتين [Rectangle](/psd/python-net/aspose.psd/rectangle/) أخريين. إذا لم يكن هناك تقاطع، يتم إرجاع [Rectangle](/psd/python-net/aspose.psd/rectangle/) فارغ.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| a | [Rectangle](/psd/python-net/aspose.psd/rectangle) | المستطيل الأول للتقاطع. |
| b | [Rectangle](/psd/python-net/aspose.psd/rectangle) | المستطيل الثاني للتقاطع. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | [Rectangle](/psd/python-net/aspose.psd/rectangle/) يمثل تقاطع <paramref name=\"a\" /> و <paramref name=\"b\" />. |


### Method: intersect(rect) {#intersect_rect_11}


```
 intersect(rect) 
```

يستبدل هذا [Rectangle](/psd/python-net/aspose.psd/rectangle/) بتقاطع نفسه مع [Rectangle](/psd/python-net/aspose.psd/rectangle/) المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | الـ [Rectangle](/psd/python-net/aspose.psd/rectangle/) الذي سيتم التقاطع معه. |

### Method: intersects_with(rect) {#intersects_with_rect_12}


```
 intersects_with(rect) 
```

يحدد ما إذا كان هذا المستطيل يتقاطع مع <paramref name="rect" />.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | المستطيل للاختبار. |

**Returns**

| النوع | الوصف |
| :- | :- |
| bool | تُعيد هذه الطريقة true إذا كان هناك أي تقاطع، وإلا false. |


### Method: offset(pos) {#offset_pos_13}


```
 offset(pos) 
```

يضبط موقع هذا المستطيل بالمقدار المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| pos | [Point](/psd/python-net/aspose.psd/point) | المقدار لإزاحة الموقع. |

### Method: offset(x, y) {#offset_x_y_14}


```
 offset(x, y) 
```

يضبط موقع هذا المستطيل بالمقدار المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| x | int | الإزاحة الأفقية. |
| y | int | الإزاحة العمودية. |

### Method: round(value)  [static] {#round_value_15}


```
 round(value) 
```

يحوّل [RectangleF](/psd/python-net/aspose.psd/rectanglef/) المحدد إلى [Rectangle](/psd/python-net/aspose.psd/rectangle/) عن طريق تقريب قيم [RectangleF](/psd/python-net/aspose.psd/rectanglef/) إلى أقرب قيم صحيحة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| value | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | الـ [RectangleF](/psd/python-net/aspose.psd/rectanglef/) الذي سيُحوَّل. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | ‏[Rectangle](/psd/python-net/aspose.psd/rectangle/) جديد. |


### Method: truncate(value)  [static] {#truncate_value_16}


```
 truncate(value) 
```

يحوّل [RectangleF](/psd/python-net/aspose.psd/rectanglef/) المحدد إلى [Rectangle](/psd/python-net/aspose.psd/rectangle/) عن طريق قطع قيم [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| value | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | الـ [RectangleF](/psd/python-net/aspose.psd/rectanglef/) الذي سيُحوَّل. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | ‏[Rectangle](/psd/python-net/aspose.psd/rectangle/) جديد. |


### Method: union(a, b)  [static] {#union_a_b_17}


```
 union(a, b) 
```

يحصل على بنية [Rectangle](/psd/python-net/aspose.psd/rectangle/) تحتوي على اتحاد بنيتين [Rectangle](/psd/python-net/aspose.psd/rectangle/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| a | [Rectangle](/psd/python-net/aspose.psd/rectangle) | المستطيل الأول للاتحاد. |
| b | [Rectangle](/psd/python-net/aspose.psd/rectangle) | المستطيل الثاني للاتحاد. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | ‏[Rectangle](/psd/python-net/aspose.psd/rectangle/) هيكل يحدّ الاتحاد بين هيكلي [Rectangle](/psd/python-net/aspose.psd/rectangle/) الاثنين. |


