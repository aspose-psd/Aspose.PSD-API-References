---
title: "فئة JpegOptions"
type: docs
weight: 60
url: /ar/python-net/aspose.psd.imageoptions/jpegoptions/
---

**Summary:** The jpeg file format create options.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.JpegOptions

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [JpegOptions()](#JpegOptions__1) | ينشئ مثلاً جديداً من الفئة [JpegOptions](/psd/python-net/aspose.psd.imageoptions/jpegoptions/). |
| [JpegOptions(jpeg_options)](#JpegOptions_jpeg_options_2) | ينشئ مثلاً جديداً من الفئة [JpegOptions](/psd/python-net/aspose.psd.imageoptions/jpegoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| bits_per_channel | byte | r/w | يحصل أو يضبط عدد البتات لكل قناة لصورة jpeg غير مضغوطة. الآن ندعم من 2 إلى 8 بتات لكل قناة. |
| تلميح_حجم_المخزن | int | r/w | يحصل أو يعيّن تلميح حجم المخزن المؤقت الذي يُعرّف كحد أقصى مسموح به لجميع المخازن الداخلية. |
| cmyk_color_profile | [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/) | r/w | ملف تعريف اللون CMYK الوجهة لصور JPEG بصيغة CMYK. يُستخدم لحفظ الصور. يجب أن يكون مقترنًا بـ RGBColorProfile للتحويل اللوني الصحيح. |
| color_type | [JpegCompressionColorMode](/psd/python-net/aspose.psd.fileformats.jpeg/jpegcompressioncolormode/) | r/w | يحصل أو يعيّن نوع اللون لصورة jpeg. |
| تعليق | string | r/w | يحصل أو يعيّن تعليق ملف jpeg. |
| compression_type | [JpegCompressionMode](/psd/python-net/aspose.psd.fileformats.jpeg/jpegcompressionmode/) | r/w | يحصل أو يعيّن نوع الضغط. |
| default_memory_allocation_limit | int | r/w | يحصل أو يعيّن حد تخصيص الذاكرة الافتراضي. |
| default_replacement_font | string | r/w | يحصل أو يعيّن خط الاستبدال الافتراضي (الخط الذي سيُستخدم لرسم النص عند التصدير إلى رستر، إذا لم يكن خط الطبقة الموجود في ملف PSD متوفرًا في النظام).<br/>            للحصول على اسم الخط الافتراضي الصحيح يمكن استخدام مقتطف الشيفرة التالي:<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| disposed | bool | r | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن قد تم التخلص منه. |
| exif_data | [JpegExifData](/psd/python-net/aspose.psd.exif/jpegexifdata/) | r/w | احصل أو عيّن حاوية بيانات exif |
| full_frame | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان [الإطار الكامل]. |
| horizontal_sampling | byte | r/w | يحصل أو يعيّن العينات الأفقية لكل مكوّن. |
| jfif | [JFIFData](/psd/python-net/aspose.psd.fileformats.jpeg/jfifdata/) | r/w | يحصل أو يعيّن jfif. |
| jpeg_ls_allowed_lossy_error | int | r/w | يحصل أو يعيّن حد الفرق لـ JPEG-LS للترميز شبه غير فقداني (معامل NEAR من مواصفات JPEG-LS). |
| jpeg_ls_interleave_mode | [JpegLsInterleaveMode](/psd/python-net/aspose.psd.fileformats.jpeg/jpeglsinterleavemode/) | r/w | يحصل أو يعيّن وضع التداخل لـ JPEG-LS. |
| jpeg_ls_preset | [JpegLsPresetCodingParameters](/psd/python-net/aspose.psd.fileformats.jpeg/jpeglspresetcodingparameters/) | r/w | يحصل أو يعيّن معلمات الإعداد المسبق لـ JPEG-LS. |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | خيارات الصفحات المتعددة |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | يحصل أو يعيّن لوحة الألوان. |
| preblend_alpha_if_present | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب خلط مكونات الأحمر والأخضر والأزرق مع لون الخلفية، إذا كان قناة ألفا موجودة. |
| جودة | int | r/w | يحصل أو يعيّن جودة الصورة. |
| rd_opt_settings | [RdOptimizerSettings](/psd/python-net/aspose.psd.imageoptions/rdoptimizersettings) | r/w | يحصل أو يعيّن إعدادات مُحسّن RD. |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | يحصل أو يعيّن إعدادات الدقة. |
| resolution_unit | [ResolutionUnit](/psd/python-net/aspose.psd.fileformats.psd.resources.resolutionenums/resolutionunit) | r/w | يحصل أو يعيّن وحدة الدقة. |
| rgb_color_profile | [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/) | r/w | ملف تعريف اللون RGB الوجهة لصور jpeg بصيغة CMYK. يُستخدم لحفظ الصور. يجب أن يكون مقترنًا بـ CMYKColorProfile للتحويل اللوني الصحيح. |
| sample_rounding_mode | [SampleRoundingMode](/psd/python-net/aspose.psd.fileformats.jpeg/sampleroundingmode/) | r/w | يحصل أو يعيّن وضع تقريب العينة لتلائم قيمة 8-بت إلى قيمة n-بت. <see cref=\"P:JpegOptions.BitsPerChannel\" /> |
| scaled_quality | int | r | الجودة المقاسة. |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | يحصل أو يضبط المصدر لإنشاء الصورة فيه. |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | يحصل أو يضبط خيارات تحويل المتجه إلى نقطية. |
| vertical_sampling | byte | r/w | يسترجع أو يعيّن عمليات أخذ العينات العمودية لكل مكوّن. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | يحصل أو يضبط حاوية بيانات التعريف XMP. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [clone()](#clone__1) | ينسخ هذه الحالة. |


### Constructor: JpegOptions() {#JpegOptions__1}


```
 JpegOptions() 
```

ينشئ مثلاً جديداً من الفئة [JpegOptions](/psd/python-net/aspose.psd.imageoptions/jpegoptions/).

### Constructor: JpegOptions(jpeg_options) {#JpegOptions_jpeg_options_2}


```
 JpegOptions(jpeg_options) 
```

ينشئ مثلاً جديداً من الفئة [JpegOptions](/psd/python-net/aspose.psd.imageoptions/jpegoptions/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| jpeg_options | [JpegOptions](/psd/python-net/aspose.psd.imageoptions/jpegoptions) | خيارات JPEG. |

### Method: clone() {#clone__1}


```
 clone() 
```

ينسخ هذه الحالة.

**Returns**

| النوع | الوصف |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | يعيد نسخة سطحية من هذه الحالة |


