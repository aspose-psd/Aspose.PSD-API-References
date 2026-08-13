---
title: "فئة LspfResource"
type: docs
weight: 640
url: /ar/python-net/aspose.psd.fileformats.psd.layers.layerresources/lspfresource/
---

**Summary:** Layer protected settings

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LspfResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [LspfResource()](#LspfResource__1) | يُنشئ مثيلاً جديدًا للفئة [LspfResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lspfresource/) فئة. |
| [LspfResource(data)](#LspfResource_data_2) | يُنشئ مثيلاً جديدًا للفئة [LspfResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lspfresource/) فئة.<br/>            مع قيمة مخصصة أو غير معروفة |
| [LspfResource(is_transparency_protected, is_composite_protected, is_position_protected)](#LspfResource_is_transparency_protected_is_composite_protected_is_position_protected_3) | يُنشئ مثيلاً جديدًا للفئة [LspfResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lspfresource/) فئة. |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | توقيع المورد الخاص بـ PSB. |
| RESOURCE_SIGNATURE [static] | int | r | توقيع المورد المشترك. |
| TYPE_TOOL_KEY [static] | int | r | مفتاح معلومات أداة النوع 1819504742 |
| is_composite_protected | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا المثيل محميًا مركبًا. |
| is_position_protected | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا المثيل محميًا موضعياً. |
| is_transparency_protected | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا المثيل محميًا للشفافية. |
| key | int | r | يحصل على مفتاح مورد الطبقة. |
| الطول | int | r | يحصل على طول مورد الطبقة بالبايتات. |
| lock_type | [LayerLockType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/layerlocktype) | r/w | يحصل أو يعيّن نوع القفل. |
| psd_version | int | r | يحصل على الحد الأدنى لإصدار psd المطلوب لمورد الطبقة. 0 يعني عدم وجود قيود. |
| signature | int | r | يحصل على التوقيع. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | يحفظ المورد في حاوية الدفق المحددة. |


### Constructor: LspfResource() {#LspfResource__1}


```
 LspfResource() 
```

يُنشئ مثيلاً جديدًا للفئة [LspfResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lspfresource/) فئة.

### Constructor: LspfResource(data) {#LspfResource_data_2}


```
 LspfResource(data) 
```

يُنشئ مثيلاً جديدًا للفئة [LspfResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lspfresource/) فئة.<br/>            مع قيمة مخصصة أو غير معروفة

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| البيانات | byte | بيانات المورد. |

### Constructor: LspfResource(is_transparency_protected, is_composite_protected, is_position_protected) {#LspfResource_is_transparency_protected_is_composite_protected_is_position_protected_3}


```
 LspfResource(is_transparency_protected, is_composite_protected, is_position_protected) 
```

يُنشئ مثيلاً جديدًا للفئة [LspfResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lspfresource/) فئة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| is_transparency_protected | bool | إذا تم تعيينه إلى <c>true</c> [محمي من الشفافية]. |
| is_composite_protected | bool | إذا تم تعيينه إلى <c>true</c> [محمي من التجميع]. |
| is_position_protected | bool | إذا تم تعيينه إلى <c>true</c> [محمي من الموقع]. |

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

