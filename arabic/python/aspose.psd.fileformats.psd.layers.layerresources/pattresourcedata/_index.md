---
title: "فئة PattResourceData"
type: docs
weight: 780
url: /ar/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata/
---

**Summary:** The class to store the pattern data for [PattResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/) resource.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.PattResourceData

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [PattResourceData()](#PattResourceData__1) | ينشئ مثلاً جديدًا من فئة PattResourceData |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| الارتفاع | short | r | يحصل على الارتفاع. |
| image_mode | [ColorModes](/psd/python-net/aspose.psd.fileformats.psd/colormodes) | r | يحصل على وضع الصورة. |
| الطول | int | r | يحصل على طول النمط. |
| name | string | r/w | يحصل أو يعيّن الاسم. |
| pattern_data | int | r | يحصل على بيانات النمط. |
| pattern_id | string | r/w | الحصول أو تعيين معرف النمط. |
| version | int | r | يحصل على الإصدار. |
| width | short | r | يحصل على العرض. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [save(stream_container)](#save_stream_container_1) | يحفظ بيانات النمط. |
| [set_pattern(pixels, bounds)](#set_pattern_pixels_bounds_2) | يعيّن النمط. |


### Constructor: PattResourceData() {#PattResourceData__1}


```
 PattResourceData() 
```

ينشئ مثلاً جديدًا من فئة PattResourceData

### Method: save(stream_container) {#save_stream_container_1}


```
 save(stream_container) 
```

يحفظ بيانات النمط.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | حاوية الدفق التي سيتم الحفظ فيها. |

### Method: set_pattern(pixels, bounds) {#set_pattern_pixels_bounds_2}


```
 set_pattern(pixels, bounds) 
```

يعيّن النمط.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| pixels | int | البكسلات. |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | الحدود. |

