---
title: "فئة PtFlResource"
type: docs
weight: 860
url: /ar/python-net/aspose.psd.fileformats.psd.layers.layerresources/ptflresource/
---

**Summary:** Class PtFlResource. Contains Pattern Fill Layer Data.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.PtFlResource

**Inheritance:** FillLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [PtFlResource()](#PtFlResource__1) | ينشئ مثلاً جديدًا من الفئة [PtFlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ptflresource/). |
| [PtFlResource(pattern_name, pattern_id)](#PtFlResource_pattern_name_pattern_id_2) | ينشئ مثلاً جديدًا من الفئة [PtFlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ptflresource/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | توقيع المورد الخاص بـ PSB. |
| RESOURCE_SIGNATURE [static] | int | r | توقيع المورد المشترك. |
| TYPE_TOOL_KEY [static] | int | r | مفتاح معلومات أداة النوع. |
| align_with_layer | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان [align with layer]. |
| الزاوية | double | r/w | يحصل أو يضبط الزاوية. |
| is_linked_with_layer | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا المثيل مرتبطًا بالطبقة. |
| key | int | r | يحصل على مفتاح مورد الطبقة. |
| الطول | int | r | يحصل على طول مورد الطبقة بالبايتات. |
| offset | [Point](/psd/python-net/aspose.psd/point) | r/w | يحصل أو يضبط الإزاحة. |
| pattern_id | string | r/w | الحصول أو تعيين معرف النمط. |
| pattern_name | string | r/w | الحصول أو تعيين اسم النمط. |
| psd_version | int | r | يحصل على الحد الأدنى لإصدار psd المطلوب لمورد الطبقة. 0 يعني عدم وجود قيود. |
| scale | double | r/w | يحصل أو يضبط المقياس. |
| signature | int | r | يحصل على التوقيع. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | يحفظ المورد في حاوية الدفق المحددة. |


### Constructor: PtFlResource() {#PtFlResource__1}


```
 PtFlResource() 
```

ينشئ مثلاً جديدًا من الفئة [PtFlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ptflresource/).

### Constructor: PtFlResource(pattern_name, pattern_id) {#PtFlResource_pattern_name_pattern_id_2}


```
 PtFlResource(pattern_name, pattern_id) 
```

ينشئ مثلاً جديدًا من الفئة [PtFlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ptflresource/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| pattern_name | string | اسم النمط. |
| pattern_id | string | معرّف النمط. |

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

يحفظ المورد في حاوية الدفق المحددة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | حاوية الدفق التي سيتم الحفظ فيها. |
| psd_version | int | إصدار PSD. |

