---
title: "ExpaResource فئة"
type: docs
weight: 280
url: /ar/python-net/aspose.psd.fileformats.psd.layers.layerresources/exparesource/
---

**Summary:** Class ExpaResource. Resource of Exposure Adjustment Layer

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.ExpaResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [ExpaResource()](#ExpaResource__1) | يُنشئ مثلاً جديداً من الفئة [ExpaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/exparesource/). |
| [ExpaResource(bytes)](#ExpaResource_bytes_2) | يُنشئ مثلاً جديداً من الفئة [ExpaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/exparesource/). |
| [ExpaResource(exposure, offset, gamma)](#ExpaResource_exposure_offset_gamma_3) | يُنشئ مثلاً جديداً من الفئة [ExpaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/exparesource/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | توقيع المورد الخاص بـ PSB. |
| RESOURCE_SIGNATURE [static] | int | r | توقيع المورد المشترك. |
| TYPE_TOOL_KEY [static] | int | r | مفتاح معلومات أداة النوع. |
| التعريض | float | r/w | يحصل أو يضبط التعرض. |
| تصحيح_الجاما | float | r/w | يحصل أو يضبط غاما. |
| key | int | r | يحصل على مفتاح مورد الطبقة. |
| الطول | int | r | يحصل على طول مورد الطبقة بالبايتات. |
| offset | float | r/w | يحصل أو يضبط الإزاحة. |
| psd_version | int | r | يحصل على الحد الأدنى لإصدار psd المطلوب لمورد الطبقة. 0 يعني عدم وجود قيود. |
| signature | int | r | يحصل على التوقيع. |
| version | short | r | يحصل على الإصدار. الافتراضي هو 1 |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | يحفظ المورد في حاوية الدفق المحددة. |


### Constructor: ExpaResource() {#ExpaResource__1}


```
 ExpaResource() 
```

يُنشئ مثلاً جديداً من الفئة [ExpaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/exparesource/).

### Constructor: ExpaResource(bytes) {#ExpaResource_bytes_2}


```
 ExpaResource(bytes) 
```

يُنشئ مثلاً جديداً من الفئة [ExpaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/exparesource/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| بايت | byte | الـ بايت. |

### Constructor: ExpaResource(exposure, offset, gamma) {#ExpaResource_exposure_offset_gamma_3}


```
 ExpaResource(exposure, offset, gamma) 
```

يُنشئ مثلاً جديداً من الفئة [ExpaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/exparesource/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| التعريض | float | التعرض. |
| offset | float | الإزاحة. |
| جاما | float | غاما. |

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

