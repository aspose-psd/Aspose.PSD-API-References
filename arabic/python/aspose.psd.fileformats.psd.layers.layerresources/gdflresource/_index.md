---
title: "فئة GdFlResource"
type: docs
weight: 330
url: /ar/python-net/aspose.psd.fileformats.psd.layers.layerresources/gdflresource/
---

**Summary:** Class GdFlResource.<br/>            This resource contains information about blending of clipped element.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.GdFlResource

**Inheritance:** FillLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [GdFlResource()](#GdFlResource__1) | ينشئ مثيلاً جديدًا لفئة GdFlResource |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | توقيع المورد الخاص بـ PSB. |
| RESOURCE_SIGNATURE [static] | int | r | توقيع المورد المشترك. |
| TYPE_TOOL_KEY [static] | int | r | مفتاح معلومات أداة النوع. |
| align_with_layer | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان [align with layer]. |
| الزاوية | double | r/w | يحصل أو يضبط الزاوية. |
| color | [Color](/psd/python-net/aspose.psd/color) | r/w | يحصل على لون الـ RGB. |
| color_model | string | r/w | نموذج اللون - RGB/HSB/LAB ("RGBC"/"HSBl"/"LbCl"). |
| color_points | [IGradientColorPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers/igradientcolorpoint) | r/w | يحصل على نقاط اللون. |
| dither | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا [GdFlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/gdflresource/) هو dither. |
| gradient_interval | double | r/w | يحصل أو يعيّن فترة التدرج. |
| gradient_mode | string | r/w | الوضع لهذا التدرج.<br/>            يحدد 'نوع التدرج' = 'Solid/Noise' = "CstS"/"ClNs". |
| gradient_name | string | r/w | يحصل أو يعيّن اسم التدرج. |
| gradient_type | [GradientType](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradienttype/) | r/w | يحصل أو يعيّن نوع التدرج. |
| horizontal_offset | double | r/w | يحصل أو يضبط الإزاحة الأفقية. |
| key | int | r | يحصل على مفتاح مورد الطبقة. |
| الطول | int | r | يحصل على طول مورد الطبقة بالبايتات. |
| maximum_color | [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) | r/w | اللون الأقصى لـ PixelDataFormat. |
| minimum_color | [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) | r/w | اللون الأدنى لـ PixelDataFormat. |
| psd_version | int | r | يحصل على الحد الأدنى لإصدار psd المطلوب لمورد الطبقة. 0 يعني عدم وجود قيود. |
| reverse | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا [GdFlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/gdflresource/) هو reverse. |
| rnd_number_seed | int | r/w | البذرة العشوائية المستخدمة لتوليد الألوان لتدرج Noise. |
| roughness | int | r/w | عامل الخشونة. |
| scale | int | r/w | يحصل أو يضبط المقياس. |
| show_transparency | bool | r/w | علامة لإظهار الشفافية. |
| signature | int | r | يحصل على التوقيع. |
| transparency_points | [IGradientTransparencyPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint/) | r/w | يحصل على نقاط الشفافية. |
| use_vector_color | bool | r/w | علامة لاستخدام اللون المتجه. |
| vertical_offset | double | r/w | الحصول أو تعيين الإزاحة العمودية. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | يحفظ المورد في حاوية الدفق المحددة. |


### Constructor: GdFlResource() {#GdFlResource__1}


```
 GdFlResource() 
```

ينشئ مثيلاً جديدًا لفئة GdFlResource

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

