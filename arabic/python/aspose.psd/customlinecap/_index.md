---
title: "فئة CustomLineCap"
type: docs
weight: 1010
url: /ar/python-net/aspose.psd/customlinecap/
---

**Summary:** Encapsulates a custom user-defined line cap.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.CustomLineCap

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [CustomLineCap(fill_path, stroke_path)](#CustomLineCap_fill_path_stroke_path_1) | يقوم بإنشاء نسخة جديدة من الفئة [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) مع المخطط المحدد والملء المحدد. |
| [CustomLineCap(fill_path, stroke_path, base_cap)](#CustomLineCap_fill_path_stroke_path_base_cap_2) | يقوم بإنشاء نسخة جديدة من الفئة [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) من تعداد [LineCap](/psd/python-net/aspose.psd/linecap/) الموجود المحدد مع المخطط المحدد والملء المحدد. |
| [CustomLineCap(fill_path, stroke_path, base_cap, base_inset)](#CustomLineCap_fill_path_stroke_path_base_cap_base_inset_3) | يقوم بإنشاء نسخة جديدة من الفئة [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) من تعداد [LineCap](/psd/python-net/aspose.psd/linecap/) الموجود المحدد مع المخطط المحدد والملء والجزء الداخلي المحدد. |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| base_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | r/w | يحصل أو يضبط تعداد [LineCap](/psd/python-net/aspose.psd/linecap/) الذي تستند إليه هذه [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/). |
| base_inset | float | r/w | يحصل أو يضبط المسافة بين الغطاء والخط. |
| fill_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | r/w | يحصل أو يضبط الكائن الذي يحدد التعبئة للغطاء المخصص. |
| stroke_join | [LineJoin](/psd/python-net/aspose.psd/linejoin) | r/w | يحصل أو يضبط تعداد [LineJoin](/psd/python-net/aspose.psd/linejoin/) الذي يحدد كيفية ربط الخطوط التي تشكل هذا الكائن [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/). |
| stroke_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | r/w | يحصل أو يضبط الكائن الذي يحدد المخطط الخارجي للغطاء المخصص. |
| width_scale | float | r/w | يحصل أو يضبط مقدار التحجيم لهذا الكائن من الفئة [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) بالنسبة إلى عرض الكائن. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [get_stroke_caps(start_cap, end_cap)](#get_stroke_caps_start_cap_end_cap_1) | يحصل على الأغطية المستخدمة لبدء وإنهاء الخطوط التي تشكل هذا الغطاء المخصص. |
| [set_stroke_caps(start_cap, end_cap)](#set_stroke_caps_start_cap_end_cap_2) | يضبط الأغطية المستخدمة لبدء وإنهاء الخطوط التي تشكل هذا الغطاء المخصص. |


### Constructor: CustomLineCap(fill_path, stroke_path) {#CustomLineCap_fill_path_stroke_path_1}


```
 CustomLineCap(fill_path, stroke_path) 
```

يقوم بإنشاء نسخة جديدة من الفئة [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) مع المخطط المحدد والملء المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| fill_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | كائن [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) يحدد التعبئة للغطاء المخصص. |
| stroke_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | كائن [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) يحدد المخطط الخارجي للغطاء المخصص. |

### Constructor: CustomLineCap(fill_path, stroke_path, base_cap) {#CustomLineCap_fill_path_stroke_path_base_cap_2}


```
 CustomLineCap(fill_path, stroke_path, base_cap) 
```

يقوم بإنشاء نسخة جديدة من الفئة [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) من تعداد [LineCap](/psd/python-net/aspose.psd/linecap/) الموجود المحدد مع المخطط المحدد والملء المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| fill_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | كائن [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) يحدد التعبئة للغطاء المخصص. |
| stroke_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | كائن [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) يحدد المخطط الخارجي للغطاء المخصص. |
| base_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | غطاء الخط الذي يُنشأ منه الغطاء المخصص. |

### Constructor: CustomLineCap(fill_path, stroke_path, base_cap, base_inset) {#CustomLineCap_fill_path_stroke_path_base_cap_base_inset_3}


```
 CustomLineCap(fill_path, stroke_path, base_cap, base_inset) 
```

يقوم بإنشاء نسخة جديدة من الفئة [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) من تعداد [LineCap](/psd/python-net/aspose.psd/linecap/) الموجود المحدد مع المخطط المحدد والملء والجزء الداخلي المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| fill_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | كائن [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) يحدد التعبئة للغطاء المخصص. |
| stroke_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | كائن [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) يحدد المخطط الخارجي للغطاء المخصص. |
| base_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | غطاء الخط الذي يُنشأ منه الغطاء المخصص. |
| base_inset | float | المسافة بين الغطاء والخط. |

### Method: get_stroke_caps(start_cap, end_cap) {#get_stroke_caps_start_cap_end_cap_1}


```
 get_stroke_caps(start_cap, end_cap) 
```

يحصل على الأغطية المستخدمة لبدء وإنهاء الخطوط التي تشكل هذا الغطاء المخصص.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| start_cap | [LineCap[]](/psd/python-net/aspose.psd/linecap) | تعداد [LineCap](/psd/python-net/aspose.psd/linecap/) المستخدم في بداية الخط داخل هذا الغطاء. |
| end_cap | [LineCap[]](/psd/python-net/aspose.psd/linecap) | تعداد [LineCap](/psd/python-net/aspose.psd/linecap/) المستخدم في نهاية الخط داخل هذا الغطاء. |

### Method: set_stroke_caps(start_cap, end_cap) {#set_stroke_caps_start_cap_end_cap_2}


```
 set_stroke_caps(start_cap, end_cap) 
```

يضبط الأغطية المستخدمة لبدء وإنهاء الخطوط التي تشكل هذا الغطاء المخصص.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| start_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | تعداد [LineCap](/psd/python-net/aspose.psd/linecap/) المستخدم في بداية الخط داخل هذا الغطاء. |
| end_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | تعداد [LineCap](/psd/python-net/aspose.psd/linecap/) المستخدم في نهاية الخط داخل هذا الغطاء. |

