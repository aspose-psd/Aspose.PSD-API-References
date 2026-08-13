---
title: "فئة Jpeg2000Options"
type: docs
weight: 50
url: /ar/python-net/aspose.psd.imageoptions/jpeg2000options/
---

**Summary:** The Jpeg2000 file format options.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.Jpeg2000Options

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [Jpeg2000Options()](#Jpeg2000Options__1) | ينشئ مثلاً جديداً من الفئة [Jpeg2000Options](/psd/python-net/aspose.psd.imageoptions/jpeg2000options/). |
| [Jpeg2000Options(jpeg_2000_options)](#Jpeg2000Options_jpeg_2000_options_2) | ينشئ مثلاً جديداً من الفئة [Jpeg2000Options](/psd/python-net/aspose.psd.imageoptions/jpeg2000options/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| تلميح_حجم_المخزن | int | r/w | يحصل أو يعيّن تلميح حجم المخزن المؤقت الذي يُعرّف كحد أقصى مسموح به لجميع المخازن الداخلية. |
| codec | [Jpeg2000Codec](/psd/python-net/aspose.psd.fileformats.jpeg2000/jpeg2000codec/) | r/w | يحصل أو يعيّن برنامج الترميز JPEG2000 |
| comments | string | r/w | يحصل أو يعيّن علامات تعليقات Jpeg. |
| compression_ratios | int | r/w | يحصل أو يعيّن مصفوفة نسب الضغط.<br/>            نسب ضغط مختلفة للطبقات المتتالية.<br/>            المعدل المحدد لكل مستوى جودة هو عامل الضغط المطلوب.<br/>            مطلوب نسب انخفاض. |
| default_replacement_font | string | r/w | يحصل أو يعيّن خط الاستبدال الافتراضي (الخط الذي سيُستخدم لرسم النص عند التصدير إلى رستر، إذا لم يكن خط الطبقة الموجود في ملف PSD متوفرًا في النظام).<br/>            للحصول على اسم الخط الافتراضي الصحيح يمكن استخدام مقتطف الشيفرة التالي:<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| disposed | bool | r | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن قد تم التخلص منه. |
| full_frame | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان [الإطار الكامل]. |
| irreversible | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يستخدم DWT غير العكسي 9-7 (true) أو يستخدم ضغط DWT غير الفاقد 5-3 (الافتراضي). |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | خيارات الصفحات المتعددة |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | يحصل أو يعيّن لوحة الألوان. |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | يحصل أو يعيّن إعدادات الدقة. |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | يحصل أو يضبط المصدر لإنشاء الصورة فيه. |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | يحصل أو يضبط خيارات تحويل المتجه إلى نقطية. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | يحصل أو يضبط حاوية بيانات التعريف XMP. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [clone()](#clone__1) | ينسخ هذه الحالة. |


### Constructor: Jpeg2000Options() {#Jpeg2000Options__1}


```
 Jpeg2000Options() 
```

ينشئ مثلاً جديداً من الفئة [Jpeg2000Options](/psd/python-net/aspose.psd.imageoptions/jpeg2000options/).

### Constructor: Jpeg2000Options(jpeg_2000_options) {#Jpeg2000Options_jpeg_2000_options_2}


```
 Jpeg2000Options(jpeg_2000_options) 
```

ينشئ مثلاً جديداً من الفئة [Jpeg2000Options](/psd/python-net/aspose.psd.imageoptions/jpeg2000options/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| jpeg_2000_options | [Jpeg2000Options](/psd/python-net/aspose.psd.imageoptions/jpeg2000options) | خيارات تنسيق ملف Jpeg2000 لنسخ الإعدادات منها. |

### Method: clone() {#clone__1}


```
 clone() 
```

ينسخ هذه الحالة.

**Returns**

| النوع | الوصف |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | يعيد نسخة سطحية من هذه الحالة |


