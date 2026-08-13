---
title: "فئة GifOptions"
type: docs
weight: 30
url: /ar/python-net/aspose.psd.imageoptions/gifoptions/
---

**Summary:** The gif file format creation options.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.GifOptions

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [GifOptions()](#GifOptions__1) | ينشئ مثلاً جديداً من الفئة [GifOptions](/psd/python-net/aspose.psd.imageoptions/gifoptions/). |
| [GifOptions(gif_options)](#GifOptions_gif_options_2) | ينشئ مثلاً جديداً من الفئة [GifOptions](/psd/python-net/aspose.psd.imageoptions/gifoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| background_color_index | byte | r/w | يحصل أو يضبط فهرس لون الخلفية لـ GIF. |
| تلميح_حجم_المخزن | int | r/w | يحصل أو يعيّن تلميح حجم المخزن المؤقت الذي يُعرّف كحد أقصى مسموح به لجميع المخازن الداخلية. |
| color_resolution | byte | r/w | يحصل أو يضبط دقة ألوان GIF. |
| default_replacement_font | string | r/w | يحصل أو يعيّن خط الاستبدال الافتراضي (الخط الذي سيُستخدم لرسم النص عند التصدير إلى رستر، إذا لم يكن خط الطبقة الموجود في ملف PSD متوفرًا في النظام).<br/>            للحصول على اسم الخط الافتراضي الصحيح يمكن استخدام مقتطف الشيفرة التالي:<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| disposed | bool | r | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن قد تم التخلص منه. |
| do_palette_correction | bool | r/w | يحصل أو يضبط قيمة تشير إلى ما إذا تم تطبيق تصحيح لوحة الألوان. |
| full_frame | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان [الإطار الكامل]. |
| has_trailer | bool | r/w | يحصل أو يضبط قيمة تشير إلى ما إذا كان GIF يحتوي على مقطع نهائي. |
| interlaced | bool | r/w | صحيح إذا كان يجب أن تكون الصورة متشابكة. |
| is_palette_sorted | bool | r/w | يحصل أو يضبط قيمة تشير إلى ما إذا كانت مدخلات لوحة الألوان مرتبة. |
| max_diff | int | r/w | يحصل أو يضبط الحد الأقصى المسموح به لاختلاف البكسل. إذا كان أكبر من الصفر، سيتم استخدام ضغط فقدان البيانات.<br/>            القيمة الموصى بها لضغط فقدان البيانات الأمثل هي 80. 30 هو ضغط خفيف جداً، و200 هو ضغط عالي.<br/>            يعمل بشكل أفضل عندما يتم إدخال فقدان قليل فقط، وبسبب قيود خوارزمية الضغط لا تعطي مستويات الفقدان العالية جداً الكثير من الفائدة.<br/>            نطاق القيم المسموح بها هو [0, 1000]. |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | خيارات الصفحات المتعددة |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | يحصل أو يعيّن لوحة الألوان. |
| pixel_aspect_ratio | byte | r/w | يحصل أو يضبط نسبة أبعاد بكسل GIF. |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | يحصل أو يعيّن إعدادات الدقة. |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | يحصل أو يضبط المصدر لإنشاء الصورة فيه. |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | يحصل أو يضبط خيارات تحويل المتجه إلى نقطية. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | يحصل أو يضبط حاوية بيانات التعريف XMP. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [clone()](#clone__1) | ينسخ هذه الحالة. |


### Constructor: GifOptions() {#GifOptions__1}


```
 GifOptions() 
```

ينشئ مثلاً جديداً من الفئة [GifOptions](/psd/python-net/aspose.psd.imageoptions/gifoptions/).

### Constructor: GifOptions(gif_options) {#GifOptions_gif_options_2}


```
 GifOptions(gif_options) 
```

ينشئ مثلاً جديداً من الفئة [GifOptions](/psd/python-net/aspose.psd.imageoptions/gifoptions/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| gif_options | [GifOptions](/psd/python-net/aspose.psd.imageoptions/gifoptions) | خيارات GIF. |

### Method: clone() {#clone__1}


```
 clone() 
```

ينسخ هذه الحالة.

**Returns**

| النوع | الوصف |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | يعيد نسخة سطحية من هذه الحالة |


