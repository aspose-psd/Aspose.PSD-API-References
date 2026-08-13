---
title: "فئة AiLayerSection"
type: docs
weight: 50
url: /ar/python-net/aspose.psd.fileformats.ai/ailayersection/
---

**Summary:** The Ai format Layer Section

**Module:** [aspose.psd.fileformats.ai](/psd/python-net/aspose.psd.fileformats.ai/)

**Full Name:** aspose.psd.fileformats.ai.AiLayerSection

**Inheritance:** AiDataSection

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| أزرق | int | r/w | يحصل أو يضبط مكوّن اللون الأزرق. |
| color_index | int | r/w | يحصل أو يضبط فهرس اللون.<br/>            يمكن أن يأخذ هذا الوسيط قيمًا بين –1 و 26. كل عدد صحيح<br/>            يمثل لونًا يمكن تعيينه للطبقة لأغراض تعريف المستخدم.<br/> |
| color_number | int | r/w | يحصل أو يضبط رقم اللون. -1 هو قيمة اللون المخصصة من خصائص الأحمر والأخضر والأزرق.<br/>            يحدد إعداد لون الطبقة. |
| dim_value | int | r/w | يحصل أو يضبط قيمة التعتيم كنسبة مئوية.<br/>            يقلل من شدة الصور المرتبطة وصور البت ماب الموجودة في الطبقة إلى النسبة المئوية المحددة. |
| disposed | bool | r | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن قد تم التخلص منه. |
| أخضر | int | r/w | يحصل أو يعيّن مكوّن اللون الأخضر. |
| has_multi_layer_masks | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا الكائن يحتوي على أقنعة متعددة الطبقات. |
| is_images_dimmed | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت هذه الطبقة مخفضة الإضاءة.<br/>            يقلل من شدة الصور المرتبطة وصور البت ماب الموجودة في الطبقة. |
| is_locked | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت هذه الطبقة مقفلة.<br/>            يمنع تغييرات العنصر. |
| is_preview | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت هذه الطبقة في وضع المعاينة.<br/>            يعرض الأعمال الفنية الموجودة في الطبقة بالألوان بدلاً من الخطوط العريضة. |
| is_printed | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت هذه الطبقة مطبوعة.<br/>            يجعل الأعمال الفنية الموجودة في الطبقة قابلة للطباعة إذا كانت صحيحة. |
| is_shown | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت هذه الطبقة معروضة.<br/>            يعرض جميع الأعمال الفنية الموجودة في الطبقة على لوحة الرسم إذا كانت صحيحة. |
| is_template | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت هذه الطبقة طبقة قالب. |
| name | string | r/w | يحصل أو يعيّن اسم الطبقة.<br/>            يحدد اسم العنصر كما يظهر في لوحة الطبقات. |
| raster_images | [AiRasterImageSection[]](/psd/python-net/aspose.psd.fileformats.ai/airasterimagesection) | r | يحصل على صور الراستر. |
| أحمر | int | r/w | يحصل أو يعيّن مكوّن اللون الأحمر. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [add_raster_image(raster_image)](#add_raster_image_raster_image_1) | يضيف صورة الراستر. |
| [get_data()](#get_data__2) | يحصل على بيانات السلسلة. |


### Method: add_raster_image(raster_image) {#add_raster_image_raster_image_1}


```
 add_raster_image(raster_image) 
```

يضيف صورة الراستر.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| raster_image | [AiRasterImageSection](/psd/python-net/aspose.psd.fileformats.ai/airasterimagesection) | صورة الراستر. |

### Method: get_data() {#get_data__2}


```
 get_data() 
```

يحصل على بيانات السلسلة.

**Returns**

| النوع | الوصف |
| :- | :- |
| string | بيانات السلسلة للقسم |


