---
title: "فئة FxrpResource"
type: docs
weight: 320
url: /ar/python-net/aspose.psd.fileformats.psd.layers.layerresources/fxrpresource/
---

**Summary:** Class FxrpResource. The reference point of layer

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.FxrpResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [FxrpResource()](#FxrpResource__1) | ينشئ مثيلًا جديدًا من الفئة [FxrpResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/fxrpresource/). |
| [FxrpResource(data)](#FxrpResource_data_2) | ينشئ مثيلًا جديدًا من الفئة [FxrpResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/fxrpresource/).<br/>            مع قيمة مخصصة أو غير معروفة |
| [FxrpResource(x, y)](#FxrpResource_x_y_3) | ينشئ مثيلًا جديدًا من الفئة [FxrpResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/fxrpresource/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | توقيع المورد الخاص بـ PSB. |
| RESOURCE_SIGNATURE [static] | int | r | توقيع المورد المشترك. |
| TYPE_TOOL_KEY [static] | int | r | مفتاح معلومات أداة النوع. |
| key | int | r | يحصل على مفتاح مورد الطبقة. |
| الطول | int | r | يحصل على طول مورد الطبقة بالبايتات. |
| psd_version | int | r | يحصل على الحد الأدنى لإصدار psd المطلوب لمورد الطبقة. 0 يعني عدم وجود قيود. |
| signature | int | r | يحصل على التوقيع. |
| x | double | r/w | يحصل أو يعيّن x لنقطة المرجع |
| y | double | r/w | يحصل أو يعيّن y لنقطة المرجع |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | يحفظ إلى حاوية الدفق المحددة. |


### Constructor: FxrpResource() {#FxrpResource__1}


```
 FxrpResource() 
```

ينشئ مثيلًا جديدًا من الفئة [FxrpResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/fxrpresource/).

### Constructor: FxrpResource(data) {#FxrpResource_data_2}


```
 FxrpResource(data) 
```

ينشئ مثيلًا جديدًا من الفئة [FxrpResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/fxrpresource/).<br/>            مع قيمة مخصصة أو غير معروفة

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| البيانات | byte | بيانات المورد. |

### Constructor: FxrpResource(x, y) {#FxrpResource_x_y_3}


```
 FxrpResource(x, y) 
```

ينشئ مثيلًا جديدًا من الفئة [FxrpResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/fxrpresource/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| x | double | الإحداثي x لنقطة المرجع |
| y | double | الإحداثي y لنقطة المرجع |

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

يحفظ إلى حاوية الدفق المحددة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | حاوية الدفق. |
| psd_version | int | إصدار PSD. |

