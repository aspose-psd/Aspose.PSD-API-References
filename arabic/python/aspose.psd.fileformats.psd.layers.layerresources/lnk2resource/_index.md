---
title: "الفئة Lnk2Resource"
type: docs
weight: 570
url: /ar/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnk2resource/
---

**Summary:** Defines the class which contains information about embedded files in the PSD format image.<br/>            The link resource may contain several [LiFdDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/) instances which can be accessed by the indexer.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.Lnk2Resource

**Inheritance:** LinkResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [Lnk2Resource()](#Lnk2Resource__1) | يُنشئ مثيلاً جديدًا من الفئة [Lnk2Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnk2resource/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | توقيع المورد الخاص بـ PSB. |
| RESOURCE_SIGNATURE [static] | int | r | توقيع المورد المشترك. |
| TYPE_TOOL_KEY [static] | int | r | مفتاح معلومات أداة النوع. |
| data_source_count | int | r | يحصل على عدد مصادر بيانات الروابط التي يمكن الوصول إليها عبر الفهرس. |
| is_empty | bool | r | يحصل على قيمة تشير إلى ما إذا كان هذا المثال من مورد الرابط فارغًا. |
| key | int | r | يحصل على مفتاح مورد الطبقة. |
| الطول | int | r | يحصل على طول مورد الرابط العالمي في PSD بالبايت. |
| psd_version | int | r | يحصل على الحد الأدنى لإصدار psd المطلوب لمورد الطبقة. 0 يعني عدم وجود قيود. |
| signature | int | r | يحصل على التوقيع. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | يحفظ بيانات كتلة المورد. |


### Constructor: Lnk2Resource() {#Lnk2Resource__1}


```
 Lnk2Resource() 
```

يُنشئ مثيلاً جديدًا من الفئة [Lnk2Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnk2resource/).

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

