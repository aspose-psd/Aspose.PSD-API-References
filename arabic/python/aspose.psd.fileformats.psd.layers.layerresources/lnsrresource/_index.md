---
title: "فئة LnsrResource"
type: docs
weight: 600
url: /ar/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnsrresource/
---

**Summary:** Class lnsrResource.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LnsrResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [LnsrResource(bytes)](#LnsrResource_bytes_1) | يُنشئ مثلاً جديدًا من فئة [LnsrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnsrresource/).<br/>            مع قيمة مخصصة أو غير معروفة |
| [LnsrResource(lnsr_resource_type)](#LnsrResource_lnsr_resource_type_2) | يُنشئ مثلاً جديدًا من فئة [LnsrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnsrresource/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | توقيع المورد الخاص بـ PSB. |
| RESOURCE_SIGNATURE [static] | int | r | توقيع المورد المشترك. |
| TYPE_TOOL_KEY [static] | int | r | مفتاح معلومات أداة النوع. |
| البيانات | byte | r | يحصل على البيانات الخام. |
| key | int | r | يحصل على مفتاح مورد الطبقة. |
| الطول | int | r | يحصل على طول مورد الطبقة بالبايتات. |
| psd_version | int | r | يحصل على الحد الأدنى لإصدار psd المطلوب لمورد الطبقة. 0 يعني عدم وجود قيود. |
| signature | int | r | يحصل على التوقيع. |
| value | [LnsrResourceType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnsrresourcetype) | r | يحصل على القيمة كـ LnsrResourceType إذا تم وصف التعداد المقابل.<br/>            وإلا يرجع Unknown |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | يحفظ حاوية الدفق المحددة. |


### Constructor: LnsrResource(bytes) {#LnsrResource_bytes_1}


```
 LnsrResource(bytes) 
```

يُنشئ مثلاً جديدًا من فئة [LnsrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnsrresource/).<br/>            مع قيمة مخصصة أو غير معروفة

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| بايت | byte | الـ بايت. |

### Constructor: LnsrResource(lnsr_resource_type) {#LnsrResource_lnsr_resource_type_2}


```
 LnsrResource(lnsr_resource_type) 
```

يُنشئ مثلاً جديدًا من فئة [LnsrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnsrresource/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| lnsr_resource_type | [LnsrResourceType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnsrresourcetype) | نوع الـ LNSR. |

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

