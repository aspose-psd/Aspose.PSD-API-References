---
title: "فئة VscgResource"
type: docs
weight: 30
url: /ar/python-net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vscgresource/
---

**Summary:** Vector Stroke Content Data resource.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources.strokeresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.strokeresources.VscgResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [VscgResource()](#VscgResource__1) | يُنشئ مثيلاً جديدًا لفئة VscgResource |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | توقيع المورد الخاص بـ PSB. |
| RESOURCE_SIGNATURE [static] | int | r | توقيع المورد المشترك. |
| TYPE_TOOL_KEY [static] | int | r | مفتاح معلومات أداة النوع. |
| items | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | r | يحصل أو يضبط مصفوفة عناصر البنية.<br/>            **Warning:** يجب أن تتطابق قيم مصفوفة `Items` مع الخاصية `KeyForData`، التي تحدد نوع إعدادات التعبئة المخزنة في البنى داخل `Items`. |
| key | int | r | يحصل على مفتاح مورد الطبقة. |
| key_for_data | int | r | يحصل على المفتاح الصحيح الذي يحدد نوع إعدادات التعبئة المخزنة في المورد:<br/>            * Color - 0x536f436f - SoCoResource.TypeToolKey<br/>            * Gradient - 0x4764466c - GdFlResource.TypeToolKey<br/>            * Pattern - 0x5074466c - PtFlResource.TypeToolKey<br/>            Warning! يجب أن تتطابق قيمة الخاصية KeyForData مع نوع إعدادات التعبئة المخزنة في بنى Items. |
| الطول | int | r | يحصل على طول مورد الطبقة بالبايتات. |
| psd_version | int | r | يحصل على الحد الأدنى لإصدار psd المطلوب لمورد الطبقة. 0 يعني عدم وجود قيود. |
| signature | int | r | يحصل على التوقيع. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | يحفظ المورد في حاوية الدفق المحددة. |


### Constructor: VscgResource() {#VscgResource__1}


```
 VscgResource() 
```

يُنشئ مثيلاً جديدًا لفئة VscgResource

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

