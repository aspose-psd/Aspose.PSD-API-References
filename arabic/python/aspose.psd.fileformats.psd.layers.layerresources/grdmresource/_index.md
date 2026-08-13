---
title: "فئة GrdmResource"
type: docs
weight: 340
url: /ar/python-net/aspose.psd.fileformats.psd.layers.layerresources/grdmresource/
---

**Summary:** Class GrdmResource. Contains information about Gradient-Map layer.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.GrdmResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [GrdmResource(psd_version)](#GrdmResource_psd_version_1) | يُنشئ مثلاً جديداً للفئة [GrdmResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/grdmresource/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | توقيع المورد الخاص بـ PSB. |
| RESOURCE_SIGNATURE [static] | int | r | توقيع المورد المشترك. |
| TYPE_TOOL_KEY [static] | int | r | مفتاح معلومات أداة النوع. |
| color_model | short | r/w | نموذج اللون.<br/>            عندما يكون 'Gradient type' = 'Noise'، يمكننا تعيين 'Color Model' إلى RGB/SHB/LAB (3/4/6). |
| color_points | [IGradientColorPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers/igradientcolorpoint) | r/w | يحصل أو يعيّن نقاط اللون. |
| تخفيف | bool | r/w | هل تم تخفيف التدرج. |
| expansion_count | short | r/w | عدد التوسيع ( = 2 لبرنامج Photoshop 6.0). |
| gradient_mode | [GradientKind](/psd/python-net/aspose.psd.fileformats.psd.layers.gradient/gradientkind/) | r/w | الوضع لهذا التدرج<br/>            يحدد 'Gradient Type' = 'Solid/Noise' (0/1). |
| gradient_name | string | r/w | اسم التدرج: سلسلة يونيكود، مملوءة. |
| الاستيفاء | short | r/w | الاستيفاء. يحدد السلاسة، عندما يكون 'Gradient Type' = 'Solid' (GradientMode = 0). |
| key | int | r | يحصل على مفتاح مورد الطبقة. |
| الطول | int | r | يحصل على طول مورد الطبقة بالبايتات. |
| maximum_color | [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) | r/w | اللون الأقصى لتنسيق PixelDataFormat.Rgba64Bpp.<br/>            اللون يحتوي على قنوات ARGB، كل قناة 16 بت. |
| minimum_color | [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) | r/w | اللون الأدنى لتنسيق PixelDataFormat.Rgba64Bpp.<br/>            اللون يحتوي على قنوات ARGB، كل قناة 16 بت. |
| psd_version | int | r | يحصل على الحد الأدنى لإصدار psd المطلوب لمورد الطبقة. 0 يعني عدم وجود قيود. |
| عكس | bool | r/w | هل تم عكس التدرج. |
| rnd_number_seed | int | r/w | البذرة العشوائية المستخدمة لتوليد الألوان لتدرج Noise. |
| roughness | int | r/w | عامل الخشونة<br/>            عندما يكون 'Gradient type' = 'Noise'، يمكننا تعيين 'Roughness' (0 - 2048). |
| show_transparency | short | r/w | علامة لإظهار الشفافية<br/>            عندما يكون 'Gradient type' = 'Noise'، يمكننا تعيين 'Add transparency' إلى true. |
| signature | int | r | يحصل على التوقيع. |
| transparency_points | [IGradientTransparencyPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint/) | r/w | يحصل أو يعيّن نقاط الشفافية. |
| use_vector_color | short | r/w | علامة لاستخدام اللون المتجه. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | يحفظ بيانات المورد إلى حاوية الدفق المحددة. |


### Constructor: GrdmResource(psd_version) {#GrdmResource_psd_version_1}


```
 GrdmResource(psd_version) 
```

يُنشئ مثلاً جديداً للفئة [GrdmResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/grdmresource/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| psd_version | int | إصدار الـ psd للمورد. |

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

يحفظ بيانات المورد إلى حاوية الدفق المحددة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | حاوية الدفق. |
| psd_version | int | إصدار PSD. |

