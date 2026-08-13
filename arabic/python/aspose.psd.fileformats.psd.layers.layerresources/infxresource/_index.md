---
title: "فئة InfxResource"
type: docs
weight: 420
url: /ar/python-net/aspose.psd.fileformats.psd.layers.layerresources/infxresource/
---

**Summary:** Class InfxResource.<br/>            This resource contains information about blending of clipped element.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.InfxResource

**Inheritance:** BooleanResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [InfxResource()](#InfxResource__1) | ينشئ مثيلاً جديدًا لفئة [InfxResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/infxresource/). |
| [InfxResource(blend_interior_elements)](#InfxResource_blend_interior_elements_2) | ينشئ مثيلاً جديدًا لفئة [InfxResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/infxresource/). |
| [InfxResource(data)](#InfxResource_data_3) | ينشئ مثيلاً جديدًا لفئة [InfxResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/infxresource/).<br/>            مع قيمة مخصصة أو غير معروفة |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | توقيع المورد الخاص بـ PSB. |
| RESOURCE_SIGNATURE [static] | int | r | توقيع المورد المشترك. |
| TYPE_TOOL_KEY [static] | int | r | مفتاح معلومات أداة النوع. |
| blend_interior_elements | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان [blend interior elements]. |
| key | int | r | يحصل على مفتاح مورد الطبقة. |
| الطول | int | r | يحصل على طول مورد الطبقة بالبايتات. |
| psd_version | int | r | يحصل على الحد الأدنى لإصدار psd المطلوب لمورد الطبقة. 0 يعني عدم وجود قيود. |
| signature | int | r | يحصل على التوقيع. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | يحفظ حاوية الدفق المحددة. |


### Constructor: InfxResource() {#InfxResource__1}


```
 InfxResource() 
```

ينشئ مثيلاً جديدًا لفئة [InfxResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/infxresource/).

### Constructor: InfxResource(blend_interior_elements) {#InfxResource_blend_interior_elements_2}


```
 InfxResource(blend_interior_elements) 
```

ينشئ مثيلاً جديدًا لفئة [InfxResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/infxresource/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| blend_interior_elements | bool | إذا تم تعيينه إلى <c>true</c> [blend interior elements]. |

### Constructor: InfxResource(data) {#InfxResource_data_3}


```
 InfxResource(data) 
```

ينشئ مثيلاً جديدًا لفئة [InfxResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/infxresource/).<br/>            مع قيمة مخصصة أو غير معروفة

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

