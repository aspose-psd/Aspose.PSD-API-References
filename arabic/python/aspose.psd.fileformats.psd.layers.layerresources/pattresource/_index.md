---
title: "فئة PattResource"
type: docs
weight: 770
url: /ar/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/
---

**Summary:** Class PattResource. Resource with pattern data

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.PattResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [PattResource()](#PattResource__1) | يُنشئ مثالا جديدًا من الفئة [PattResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/). |
| [PattResource(key, patterns)](#PattResource_key_patterns_2) | يُنشئ مثالا جديدًا من الفئة [PattResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | توقيع المورد الخاص بـ PSB. |
| RESOURCE_SIGNATURE [static] | int | r | توقيع المورد المشترك. |
| TYPE_TOOL_KEY [static] | int | r | مفتاح معلومات أداة النوع 'Patt' للبتات 8. |
| TYPE_TOOL_KEY2 [static] | int | r | مفتاح معلومات أداة النوع 'Pat2' للبتات 16. |
| TYPE_TOOL_KEY3 [static] | int | r | مفتاح معلومات أداة النوع 'Pat3' للبتات 32. |
| key | int | r | يحصل على مفتاح مورد الطبقة. |
| الطول | int | r | يحصل على طول مورد الطبقة بالبايتات. |
| patterns | [PattResourceData[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata) | r/w | يحصل أو يعيّن بيانات الأنماط; |
| psd_version | int | r | يحصل على الحد الأدنى لإصدار psd المطلوب لمورد الطبقة. 0 يعني عدم وجود قيود. |
| signature | int | r | يحصل على التوقيع. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | يحفظ بيانات كتلة المورد. |


### Constructor: PattResource() {#PattResource__1}


```
 PattResource() 
```

يُنشئ مثالا جديدًا من الفئة [PattResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/).

### Constructor: PattResource(key, patterns) {#PattResource_key_patterns_2}


```
 PattResource(key, patterns) 
```

يُنشئ مثالا جديدًا من الفئة [PattResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| key | int | مفتاح نوع المورد. |
| patterns | [PattResourceData[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata) | بيانات الأنماط. |

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

يحفظ بيانات كتلة المورد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | حاوية الدفق التي سيتم الحفظ فيها. |
| psd_version | int | إصدار PSD. |

