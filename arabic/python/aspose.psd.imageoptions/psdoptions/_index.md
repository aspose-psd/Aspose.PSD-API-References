---
title: "فئة PsdOptions"
type: docs
weight: 100
url: /ar/python-net/aspose.psd.imageoptions/psdoptions/
---

**Summary:** The psd file format create options.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.PsdOptions

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [PsdOptions()](#PsdOptions__1) | يُنشئ مثلاً جديداً من الفئة [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/). |
| [PsdOptions(image)](#PsdOptions_image_2) | يُنشئ مثلاً جديداً من الفئة [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/). |
| [PsdOptions(options)](#PsdOptions_options_3) | يُنشئ مثلاً جديداً من الفئة [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| background_contents | [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) | r/w | يسترجع أو يعيّن لون الخلفية.<br/>            يمكن رؤيته تحت الكائنات الشفافة. |
| تلميح_حجم_المخزن | int | r/w | يحصل أو يعيّن تلميح حجم المخزن المؤقت الذي يُعرّف كحد أقصى مسموح به لجميع المخازن الداخلية. |
| channel_bits_count | short | r/w | يسترجع أو يعيّن عدد البتات لكل قناة لونية. |
| عدد_القنوات | short | r/w | يسترجع أو يعيّن عدد قنوات اللون. |
| color_mode | [ColorModes](/psd/python-net/aspose.psd.fileformats.psd/colormodes/) | r/w | يسترجع أو يعيّن وضع لون PSD. |
| compression_method | [CompressionMethod](/psd/python-net/aspose.psd.fileformats.psd/compressionmethod/) | r/w | يسترجع أو يعيّن طريقة ضغط PSD. |
| default_replacement_font | string | r/w | يحصل أو يعيّن خط الاستبدال الافتراضي (الخط الذي سيُستخدم لرسم النص عند التصدير إلى رستر، إذا لم يكن خط الطبقة الموجود في ملف PSD متوفرًا في النظام).<br/>            للحصول على اسم الخط الافتراضي الصحيح يمكن استخدام مقتطف الشيفرة التالي:<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| disposed | bool | r | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن قد تم التخلص منه. |
| full_frame | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان [الإطار الكامل]. |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | خيارات الصفحات المتعددة |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | يحصل أو يعيّن لوحة الألوان. |
| psd_version | [PsdVersion](/psd/python-net/aspose.psd.fileformats.psd/psdversion/) | r/w | يسترجع أو يعيّن نسخة تنسيق الملف. يمكن أن تكون PSD أو PSB. |
| refresh_image_preview_data | bool | r/w | يسترجع أو يعيّن قيمة تشير إلى ما إذا كان [refresh image preview data] - خيار يُستخدم لتعزيز التوافق مع عارضات صور PSD الأخرى.<br/>            يرجى ملاحظة أن رسم طبقات النص إلى التخطيط النهائي غير مدعوم لمنصة Compact Framework. |
| remove_global_text_engine_resource | bool | r/w | يسترجع أو يعيّن قيمة تشير إلى ما إذا كان - إزالة مورد محرك النص العالمي - يُستخدم لبعض ملفات PSD ذات الطبقات النصية، في الحالة الوحيدة عندما لا يمكن فتحها في Adobe Photoshop بعد المعالجة (غالباً ما يتعلق بطبقات النص التي تفتقد الخطوط).<br/>            بعد استخدام هذا الخيار، يحتاج المستخدم إلى القيام بما يلي في الملف المفتوح في Photoshop: القائمة \"Text\" -> \"Process absent fonts\". بعد تلك العملية سيظهر كل النص مرة أخرى.<br/>            يرجى ملاحظة أن هذه العملية قد تتسبب في بعض تغييرات التخطيط النهائي. |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | يحصل أو يعيّن إعدادات الدقة. |
| resources | [ResourceBlock[]](/psd/python-net/aspose.psd.fileformats.psd/resourceblock/) | r/w | يسترجع أو يعيّن موارد PSD. |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | يحصل أو يضبط المصدر لإنشاء الصورة فيه. |
| update_metadata | bool | r/w | يسترجع أو يعيّن قيمة تشير إلى ما إذا كان [update metadata].<br/>            إذا كانت القيمة true، سيتم تحديث البيانات الوصفية أثناء حفظ الصورة. |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | يحصل أو يضبط خيارات تحويل المتجه إلى نقطية. |
| version | int | r/w | يسترجع أو يعيّن نسخة ملف PSD. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | احصل أو عيّن حاوية بيانات XMP |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [clone()](#clone__1) | ينسخ هذه الحالة. |


### Constructor: PsdOptions() {#PsdOptions__1}


```
 PsdOptions() 
```

يُنشئ مثلاً جديداً من الفئة [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/).

### Constructor: PsdOptions(image) {#PsdOptions_image_2}


```
 PsdOptions(image) 
```

يُنشئ مثلاً جديداً من الفئة [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| image | [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) | الصورة. |

### Constructor: PsdOptions(options) {#PsdOptions_options_3}


```
 PsdOptions(options) 
```

يُنشئ مثلاً جديداً من الفئة [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| options | [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions) | الخيارات. |

### Method: clone() {#clone__1}


```
 clone() 
```

ينسخ هذه الحالة.

**Returns**

| النوع | الوصف |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | يعيد نسخة سطحية من هذه الحالة |


