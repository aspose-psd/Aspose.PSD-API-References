---
title: "الفئة VmskResource"
type: docs
weight: 1100
url: /ar/python-net/aspose.psd.fileformats.psd.layers.layerresources/vmskresource/
---

**Summary:** Class VmskResource.<br/>            This resource contains information about vector layer mask

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.VmskResource

**Inheritance:** IVectorPathData, VectorPathDataResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [VmskResource()](#VmskResource__1) | ينشئ مثيلًا جديدًا من الفئة [VmskResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vmskresource/). |
| [VmskResource(data)](#VmskResource_data_2) | ينشئ مثيلًا جديدًا من الفئة [VmskResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vmskresource/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | توقيع المورد الخاص بـ PSB. |
| RESOURCE_SIGNATURE [static] | int | r | توقيع المورد المشترك. |
| TYPE_TOOL_KEY [static] | int | r | مفتاح معلومات أداة النوع. |
| is_disabled | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا المثيل معطلاً. |
| is_inverted | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا المثيل مقلوبًا. |
| is_not_linked | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا المثيل غير مرتبط. |
| key | int | r | يحصل على مفتاح مورد الطبقة. |
| الطول | int | r | يحصل على طول مورد الطبقة بالبايتات. |
| paths | [VectorPathRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/vectorpathrecord/) | r/w | يحصل أو يعيّن سجلات المسار. |
| psd_version | int | r | يحصل على الحد الأدنى لإصدار psd المطلوب لمورد الطبقة. 0 يعني عدم وجود قيود. |
| signature | int | r | يحصل على التوقيع. |
| version | int | r/w | يحصل أو يعيّن الإصدار. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | يحفظ المورد في حاوية الدفق المحددة. |


### Constructor: VmskResource() {#VmskResource__1}


```
 VmskResource() 
```

ينشئ مثيلًا جديدًا من الفئة [VmskResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vmskresource/).

### Constructor: VmskResource(data) {#VmskResource_data_2}


```
 VmskResource(data) 
```

ينشئ مثيلًا جديدًا من الفئة [VmskResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vmskresource/).

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

