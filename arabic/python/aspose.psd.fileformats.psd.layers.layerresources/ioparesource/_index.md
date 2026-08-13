---
title: "فئة IopaResource"
type: docs
weight: 440
url: /ar/python-net/aspose.psd.fileformats.psd.layers.layerresources/ioparesource/
---

**Summary:** Class IopaResource.<br/>            This resource contains information about the fill opacity property from the layer style form

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.IopaResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [IopaResource()](#IopaResource__1) | يُنشئ مثالا جديدًا من الفئة [IopaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ioparesource/). |
| [IopaResource(data)](#IopaResource_data_2) | يُنشئ مثالا جديدًا من الفئة [IopaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ioparesource/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | توقيع المورد الخاص بـ PSB. |
| RESOURCE_SIGNATURE [static] | int | r | توقيع المورد المشترك. |
| TYPE_TOOL_KEY [static] | int | r | مفتاح معلومات أداة النوع. |
| fill_opacity | byte | r/w | يحصل أو يضبط شفافية التعبئة. |
| key | int | r | يحصل على مفتاح مورد الطبقة. |
| الطول | int | r | يحصل على طول مورد الطبقة بالبايتات. |
| psd_version | int | r | يحصل على الحد الأدنى لإصدار psd المطلوب لمورد الطبقة. 0 يعني عدم وجود قيود. |
| signature | int | r | يحصل على التوقيع. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | يحفظ المورد في حاوية الدفق المحددة. |


### Constructor: IopaResource() {#IopaResource__1}


```
 IopaResource() 
```

يُنشئ مثالا جديدًا من الفئة [IopaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ioparesource/).

### Constructor: IopaResource(data) {#IopaResource_data_2}


```
 IopaResource(data) 
```

يُنشئ مثالا جديدًا من الفئة [IopaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ioparesource/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| البيانات | byte | بيانات البايت الخام. |

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

