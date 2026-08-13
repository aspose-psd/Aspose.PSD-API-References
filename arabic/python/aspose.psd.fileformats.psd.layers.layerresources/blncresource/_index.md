---
title: "فئة BlncResource"
type: docs
weight: 80
url: /ar/python-net/aspose.psd.fileformats.psd.layers.layerresources/blncresource/
---

**Summary:** BlncResource class is a resource of Color Adjustment Layer.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.BlncResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [BlncResource()](#BlncResource__1) | يُنشئ مثلاً جديداً من الفئة [BlncResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/blncresource/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | توقيع المورد الخاص بـ PSB. |
| RESOURCE_SIGNATURE [static] | int | r | توقيع المورد المشترك. |
| TYPE_TOOL_KEY [static] | int | r | مفتاح معلومات أداة النوع. |
| highlights_cyan_red_balance | short | r/w | يحصل أو يعيّن توازن الإضاءات السماوي الأحمر. |
| highlights_magenta_green_balance | short | r/w | يحصل أو يعيّن توازن الإضاءات الأرجواني الأخضر. |
| highlights_yellow_blue_balance | short | r/w | يحصل أو يعيّن توازن الإضاءات الأصفر الأزرق. |
| key | int | r | يحصل على مفتاح مورد الطبقة. |
| الطول | int | r | يحصل على طول مورد الطبقة بالبايتات. |
| midtones_cyan_red_balance | short | r/w | يحصل أو يعيّن توازن الألوان المتوسطة السماوي الأحمر. |
| midtones_magenta_green_balance | short | r/w | يحصل أو يعيّن Midtones Magenta Green Balance. |
| midtones_yellow_blue_balance | short | r/w | يحصل أو يعيّن Midtones Yellow Blue Balance. |
| preserve_luminosity | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا [BlncResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/blncresource/) يحافظ على الإضاءة. |
| psd_version | int | r | يحصل على الحد الأدنى لإصدار psd المطلوب لمورد الطبقة. 0 يعني عدم وجود قيود. |
| shadows_cyan_red_balance | short | r/w | يحصل أو يعيّن Shadows Cyan Red Balance. |
| shadows_magenta_green_balance | short | r/w | يحصل أو يعيّن Shadows Magenta Green Balance. |
| shadows_yellow_blue_balance | short | r/w | يحصل أو يعيّن Shadows Yellow Blue Balance. |
| signature | int | r | يحصل على التوقيع. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | يحفظ المورد في حاوية الدفق المحددة. |


### Constructor: BlncResource() {#BlncResource__1}


```
 BlncResource() 
```

يُنشئ مثلاً جديداً من الفئة [BlncResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/blncresource/) class.

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

