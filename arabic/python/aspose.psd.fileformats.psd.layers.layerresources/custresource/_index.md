---
title: "فئة CustResource"
type: docs
weight: 230
url: /ar/python-net/aspose.psd.fileformats.psd.layers.layerresources/custresource/
---

**Summary:** Class CustResource.<br/>            This resource contains information about blending of clipped element.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.CustResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [CustResource()](#CustResource__1) | ينشئ مثلاً جديداً من الفئة [CustResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/custresource/). |
| [CustResource(data)](#CustResource_data_2) | ينشئ مثلاً جديداً من الفئة [CustResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/custresource/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | توقيع المورد الخاص بـ PSB. |
| RESOURCE_SIGNATURE [static] | int | r | توقيع المورد المشترك. |
| TYPE_TOOL_KEY [static] | int | r | مفتاح معلومات أداة النوع. |
| key | int | r | يحصل على مفتاح مورد الطبقة. |
| layer_created_date_time | datetime | r/w | يحصل أو يعيّن تاريخ إنشاء الطبقة. |
| الطول | int | r | يحصل على طول مورد الطبقة بالبايتات. |
| psd_version | int | r | يحصل على الحد الأدنى لإصدار psd المطلوب لمورد الطبقة. 0 يعني عدم وجود قيود. |
| signature | int | r | يحصل على التوقيع. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | يحفظ المورد في حاوية الدفق المحددة. |


### Constructor: CustResource() {#CustResource__1}


```
 CustResource() 
```

ينشئ مثلاً جديداً من الفئة [CustResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/custresource/).

### Constructor: CustResource(data) {#CustResource_data_2}


```
 CustResource(data) 
```

ينشئ مثلاً جديداً من الفئة [CustResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/custresource/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| البيانات | byte | بيانات المورد. |

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

