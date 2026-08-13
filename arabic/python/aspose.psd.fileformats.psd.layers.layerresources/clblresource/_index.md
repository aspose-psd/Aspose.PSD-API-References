---
title: "فئة ClblResource"
type: docs
weight: 160
url: /ar/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/
---

**Summary:** Class ClblResource.<br/>            This resource contains information about blending of clipped element.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.ClblResource

**Inheritance:** BooleanResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [ClblResource()](#ClblResource__1) | ينشئ مثلاً جديداً من الفئة [ClblResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/). |
| [ClblResource(blend_clipped_elements)](#ClblResource_blend_clipped_elements_2) | ينشئ مثلاً جديداً من الفئة [ClblResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/). |
| [ClblResource(data)](#ClblResource_data_3) | ينشئ مثلاً جديداً من الفئة [ClblResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/) فئة.<br/>            بقيمة مخصصة أو غير معروفة |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | توقيع المورد الخاص بـ PSB. |
| RESOURCE_SIGNATURE [static] | int | r | توقيع المورد المشترك. |
| TYPE_TOOL_KEY [static] | int | r | مفتاح معلومات أداة النوع. |
| دمج_العناصر_المقصوصة | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان [دمج العناصر المقصوصة]. |
| key | int | r | يحصل على مفتاح مورد الطبقة. |
| الطول | int | r | يحصل على طول مورد الطبقة بالبايتات. |
| psd_version | int | r | يحصل على الحد الأدنى لإصدار psd المطلوب لمورد الطبقة. 0 يعني عدم وجود قيود. |
| signature | int | r | يحصل على التوقيع. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | يحفظ حاوية الدفق المحددة. |


### Constructor: ClblResource() {#ClblResource__1}


```
 ClblResource() 
```

ينشئ مثلاً جديداً من الفئة [ClblResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/).

### Constructor: ClblResource(blend_clipped_elements) {#ClblResource_blend_clipped_elements_2}


```
 ClblResource(blend_clipped_elements) 
```

ينشئ مثلاً جديداً من الفئة [ClblResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| دمج_العناصر_المقصوصة | bool | إذا تم تعيينه إلى <c>true</c> [دمج العناصر المقصوصة]. |

### Constructor: ClblResource(data) {#ClblResource_data_3}


```
 ClblResource(data) 
```

ينشئ مثلاً جديداً من الفئة [ClblResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/) فئة.<br/>            بقيمة مخصصة أو غير معروفة

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| البيانات | byte | بيانات المورد. |

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

يحفظ حاوية الدفق المحددة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | حاوية الدفق. |
| psd_version | int | إصدار PSD. |

