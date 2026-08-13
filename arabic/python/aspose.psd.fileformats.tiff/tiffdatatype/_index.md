---
title: "فئة TiffDataType"
type: docs
weight: 10
url: /ar/python-net/aspose.psd.fileformats.tiff/tiffdatatype/
---

**Summary:** The tiff data type.

**Module:** [aspose.psd.fileformats.tiff](/psd/python-net/aspose.psd.fileformats.tiff/)

**Full Name:** aspose.psd.fileformats.tiff.TiffDataType

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| aligned_data_size | uint | r | يحصل على حجم البيانات الإضافية بالبايتات (في حال أن 12 بايتًا غير كافية لاستيعاب بيانات العلامة). |
| count | uint | r | يحصل على عدد العناصر. |
| data_size | uint | r | يحصل على حجم البيانات الإضافية بالبايتات (في حال أن 12 بايتًا غير كافية لاستيعاب بيانات العلامة). |
| id | ushort | r | يحصل على تمثيل معرف العلامة كعدد صحيح. |
| is_valid | bool | r | يحصل على قيمة تشير إلى ما إذا كانت بيانات العلامة صالحة. العلامة الصالحة تحتوي على بيانات يمكن حفظها. العلامة غير الصالحة لا يمكن تخزينها. |
| tag_id | [TiffTags](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifftags/) | r | يحصل على معرف العلامة. |
| tag_type | [TiffDataTypes](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffdatatypes/) | r | يحصل على نوع العلامة. |
| قيمة | object | r/w | يحصل أو يعيّن القيمة التي يحتويها هذا النوع من البيانات. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [compare_to(obj)](#compare_to_obj_1) | يقارن المثيل الحالي مع كائن آخر من نفس النوع ويعيد عددًا صحيحًا يشير إلى ما إذا كان المثيل الحالي يسبق أو يتبع أو يقع في نفس الموضع في ترتيب الفرز مقارنةً بالكائن الآخر. |
| [deep_clone()](#deep_clone__2) | ينفّذ استنساخًا عميقًا لهذا المثيل. |
| [read_tag(data_stream, position)](#read_tag_data_stream_position_3) | يقرأ بيانات العلامة. |
| [write_additional_data(data_stream)](#write_additional_data_data_stream_4) | يكتب بيانات العلامة الإضافية. |
| [write_tag(data_stream, additional_data_offset)](#write_tag_data_stream_additional_data_offset_5) | يكتب بيانات العلامة. |


### Method: compare_to(obj) {#compare_to_obj_1}


```
 compare_to(obj) 
```

يقارن المثيل الحالي مع كائن آخر من نفس النوع ويعيد عددًا صحيحًا يشير إلى ما إذا كان المثيل الحالي يسبق أو يتبع أو يقع في نفس الموضع في ترتيب الفرز مقارنةً بالكائن الآخر.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| obj | object | كائن للمقارنة مع هذه المثيلة. |

**Returns**

| النوع | الوصف |
| :- | :- |
| int | عدد صحيح موقّع 32‑بت يحدد الترتيب النسبي للكائنات التي يتم مقارنتها. قيمة الإرجاع لها هذه المعاني:<br/>            القيمة<br/>            المعنى<br/>            أقل من الصفر<br/>            هذه المثيلة أقل من <paramref name="obj" />.<br/>            صفر<br/>            هذه المثيلة مساوية لـ <paramref name="obj" />.<br/>            أكبر من الصفر<br/>            هذه المثيلة أكبر من <paramref name="obj" />. |


### Method: deep_clone() {#deep_clone__2}


```
 deep_clone() 
```

ينفّذ استنساخًا عميقًا لهذا المثيل.

**Returns**

| النوع | الوصف |
| :- | :- |
| [TiffDataType](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype) | نسخة عميقة من المثيلة الحالية. |


### Method: read_tag(data_stream, position)  [static] {#read_tag_data_stream_position_3}


```
 read_tag(data_stream, position) 
```

يقرأ بيانات العلامة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| data_stream | [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/) | دفق البيانات. |
| position | long | موضع العلامة. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [TiffDataType](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype) | العلامة المقروءة. |


### Method: write_additional_data(data_stream) {#write_additional_data_data_stream_4}


```
 write_additional_data(data_stream) 
```

يكتب بيانات العلامة الإضافية.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| data_stream | [TiffStreamWriter](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter/) | دفق البيانات. |

**Returns**

| النوع | الوصف |
| :- | :- |
| long | عدد البايتات الفعلية المكتوبة. |


### Method: write_tag(data_stream, additional_data_offset) {#write_tag_data_stream_additional_data_offset_5}


```
 write_tag(data_stream, additional_data_offset) 
```

يكتب بيانات العلامة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| data_stream | [TiffStreamWriter](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter/) | دفق البيانات. |
| additional_data_offset | long | الإزاحة لكتابة البيانات الإضافية إليها. |

