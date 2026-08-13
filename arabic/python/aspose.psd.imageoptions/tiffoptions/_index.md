---
title: "فئة TiffOptions"
type: docs
weight: 130
url: /ar/python-net/aspose.psd.imageoptions/tiffoptions/
---

**Summary:** The tiff file format options.<br/>                Note that width and height tags will get overwritten on image creation by width and height parameters so there is no need to specify them directly.<br/>                Note that many options return a default value but that does not mean that this option is set explicitly as a tag value. To verify the tag is present use Tags property or the corresponding IsTagPresent method.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.TiffOptions

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [TiffOptions(expected_format)](#TiffOptions_expected_format_1) | يُنشئ مثلاً جديداً من فئة [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/). يتم استخدام نظام النهاية الصغرى (little endian) بشكل افتراضي. |
| [TiffOptions(expected_format, byte_order)](#TiffOptions_expected_format_byte_order_2) | يُنشئ مثلاً جديداً من فئة [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/). |
| [TiffOptions(options)](#TiffOptions_options_3) | يُنشئ مثلاً جديداً من فئة [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/). |
| [TiffOptions(tags)](#TiffOptions_tags_4) | يُنشئ مثلاً جديداً من فئة [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| alpha_storage | [TiffAlphaStorage](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffalphastorage/) | r/w | يحصل أو يعيّن خيار تخزين ألفا. تُستخدم الخيارات غير [TiffAlphaStorage.UNSPECIFIED](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffalphastorage/)<br/>            عندما يكون هناك أكثر من 3 [TiffOptions.samples_per_pixel](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) معرفة. |
| الفنان | string | r/w | يحصل أو يعيّن الفنان. |
| بتات_لكل_بكسل | int | r | يحصل على عدد البتات لكل بكسل. |
| bits_per_sample | ushort | r/w | يحصل أو يعيّن عدد البتات لكل عينة. |
| تلميح_حجم_المخزن | int | r/w | يحصل أو يعيّن تلميح حجم المخزن المؤقت الذي يُعرّف كحد أقصى مسموح به لجميع المخازن الداخلية. |
| byte_order | [TiffByteOrder](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffbyteorder/) | r/w | يحصل أو يعيّن قيمة تشير إلى ترتيب بايتات TIFF. |
| color_map | ushort | r/w | يحصل أو يعيّن خريطة الألوان. |
| compressed_quality | int | r/w | يحصل أو يعيّن جودة الصورة المضغوطة.<br/>            يستخدم مع ضغط Jpeg. |
| compression | [TiffCompressions](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffcompressions/) | r/w | يحصل أو يضبط الضغط. |
| copyright | string | r/w | يحصل أو يعيّن حقوق النشر. |
| date_time | string | r/w | يحصل أو يعيّن التاريخ والوقت. |
| default_memory_allocation_limit | int | r/w | يحصل أو يعيّن حد تخصيص الذاكرة الافتراضي. |
| default_replacement_font | string | r/w | يحصل أو يعيّن خط الاستبدال الافتراضي (الخط الذي سيُستخدم لرسم النص عند التصدير إلى رستر، إذا لم يكن خط الطبقة الموجود في ملف PSD متوفرًا في النظام).<br/>            للحصول على اسم الخط الافتراضي الصحيح يمكن استخدام مقتطف الشيفرة التالي:<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| disposed | bool | r | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن قد تم التخلص منه. |
| document_name | string | r/w | يحصل أو يعيّن اسم المستند. |
| exif_ifd | [TiffExifIfd](/psd/python-net/aspose.psd.fileformats.tiff/tiffexififd/) | r | يحصل أو يعيّن المؤشر إلى EXIF IFD. |
| fax_t4_options | [Group3Options](/psd/python-net/aspose.psd.fileformats.tiff.enums/group3options/) | r/w | يحصل أو يعيّن خيارات الفاكس t4. |
| file_standard | [TiffFileStandards](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifffilestandards/) | r/w | يحصل أو يعيّن معيار ملف TIFF. |
| fill_order | [TiffFillOrders](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifffillorders/) | r/w | يحصل أو يعيّن ترتيب تعبئة بتات البايت. |
| full_frame | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان [الإطار الكامل]. |
| half_tone_hints | ushort | r/w | يحصل أو يعيّن تلميحات النقاط المتوسطة. |
| image_description | string | r/w | يحصل أو يعيّن وصف الصورة. |
| image_length | uint | r/w | يحصل أو يعيّن طول الصورة. |
| image_width | uint | r/w | يحصل أو يعيّن عرض الصورة. |
| ink_names | string | r/w | يحصل أو يعيّن أسماء الحبر. |
| is_extra_samples_present | bool | r | يحصل على قيمة تشير إلى ما إذا كانت العينات الإضافية موجودة. |
| is_tiled | bool | r | يحصل على قيمة تشير إلى ما إذا كانت الصورة موزعة على مربعات. |
| is_valid | bool | r | يحصل على قيمة تشير إلى ما إذا كان [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) تم تكوينه بشكل صحيح. استخدم طريقة Validate للعثور على سبب الفشل. |
| max_sample_value | ushort | r/w | يحصل أو يضبط قيمة max sample value. |
| min_sample_value | ushort | r/w | يحصل أو يضبط قيمة min sample value. |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | خيارات الصفحات المتعددة |
| orientation | [TiffOrientations](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifforientations/) | r/w | يحصل أو يضبط الاتجاه. |
| page_name | string | r/w | يحصل أو يضبط اسم الصفحة. |
| page_number | ushort | r/w | يحصل أو يضبط علامة رقم الصفحة. |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | يحصل أو يعيّن لوحة الألوان. |
| photometric | [TiffPhotometrics](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffphotometrics/) | r/w | يحصل أو يضبط photometric. |
| planar_configuration | [TiffPlanarConfigs](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffplanarconfigs/) | r/w | يحصل أو يضبط تكوين المستوى. |
| predictor | [TiffPredictor](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffpredictor/) | r/w | يحصل أو يضبط المتنبئ لضغط LZW. |
| premultiply_components | bool | r/w | يحصل أو يضبط قيمة تشير إلى ما إذا كان يجب ضرب المكونات مسبقًا. |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | يحصل أو يعيّن إعدادات الدقة. |
| resolution_unit | [TiffResolutionUnits](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffresolutionunits/) | r/w | يحصل أو يعيّن وحدة الدقة. |
| rows_per_strip | uint | r/w | يحصل أو يضبط عدد الصفوف لكل شريط. |
| sample_format | [TiffSampleFormats[]](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffsampleformats/) | r/w | يحصل أو يضبط تنسيق العينة. |
| samples_per_pixel | ushort | r | يحصل على عدد العينات لكل بكسل. لتغيير قيمة هذه الخاصية استخدم مُعيّن الخاصية [TiffOptions.bits_per_sample](/psd/python-net/aspose.psd.imageoptions/tiffoptions/). |
| scanner_manufacturer | string | r/w | يحصل أو يضبط شركة تصنيع الماسح الضوئي. |
| scanner_model | string | r/w | يحصل أو يضبط طراز الماسح الضوئي. |
| smax_sample_value | uint | r/w | يحصل أو يضبط قيمة max sample value. القيمة لها نوع حقل يتطابق بأفضل شكل مع بيانات العينة (Byte أو Short أو Long). |
| smin_sample_value | uint | r/w | يحصل أو يضبط قيمة العينة الدنيا. القيمة لها نوع حقل يتطابق بأفضل شكل مع بيانات العينة (Byte, Short أو Long). |
| software_type | string | r/w | يحصل أو يضبط نوع البرنامج. |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | يحصل أو يضبط المصدر لإنشاء الصورة فيه. |
| strip_byte_counts | uint | r/w | يحصل أو يضبط عدد بايتات الشريط. |
| strip_offsets | uint | r/w | يحصل أو يضبط إزاحات الشريط. |
| sub_file_type | [TiffNewSubFileTypes](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffnewsubfiletypes/) | r/w | يحصل أو يضبط إشارة عامة لنوع البيانات الموجودة في هذا الملف الفرعي. |
| tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r/w | يحصل أو يضبط العلامات. |
| target_printer | string | r/w | يحصل أو يضبط الطابعة الهدف. |
| threshholding | [TiffThresholds](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffthresholds/) | r/w | يحصل أو يضبط العتبة. |
| tile_byte_counts | uint | r/w | يحصل أو يضبط عدد بايتات البلاط. |
| tile_length | uint | r/w | يحصل أو يضبط طول البلاط. |
| tile_offsets | uint | r/w | يحصل أو يضبط إزاحات البلاط. |
| tile_width | uint | r/w | يحصل أو يضبط عرض البلاط. |
| total_pages | ushort | r | يحصل على إجمالي الصفحات. |
| valid_tag_count | int | r | يحصل على عدد العلامات الصالحة. هذا ليس إجمالي عدد العلامات ولكن عدد العلامات التي قد تُحفظ. |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | يحصل أو يضبط خيارات تحويل المتجه إلى نقطية. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | يحصل أو يضبط حاوية بيانات التعريف XMP. |
| xp_author | string | r/w | يحصل أو يعيّن مؤلف الصورة، والذي يستخدمه Windows Explorer. |
| xp_comment | string | r/w | يحصل أو يعيّن التعليق على الصورة، والذي يستخدمه Windows Explorer. |
| xp_keywords | string | r/w | يحصل أو يعيّن موضوع الصورة، والذي يستخدمه Windows Explorer. |
| xp_subject | string | r/w | يحصل أو يعيّن معلومات حول الصورة، والذي يستخدمه Windows Explorer. |
| xp_title | string | r/w | يحصل أو يعيّن معلومات حول الصورة، والذي يستخدمه Windows Explorer. |
| xposition | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | يحصل أو يعيّن موضع x. |
| xresolution | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | يحصل أو يعيّن دقة x. |
| y_cb_cr_coefficients | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | يحصل أو يعيّن معاملات YCbCrCoefficients. |
| y_cb_cr_subsampling | ushort | r/w | يحصل أو يعيّن عوامل أخذ العينات الفرعية للخصائص الضوئية YCbCr. |
| yposition | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | يحصل أو يعيّن موضع y. |
| yresolution | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | يحصل أو يعيّن دقة y. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [add_tag(tag_to_add)](#add_tag_tag_to_add_1) | يضيف علامة جديدة. |
| [add_tags(tags_to_add)](#add_tags_tags_to_add_2) | يضيف العلامات. |
| [clone()](#clone__3) | ينسخ هذه الحالة. |
| [get_tag_by_type(tag_key)](#get_tag_by_type_tag_key_4) | يحصل على نسخة العلامة حسب النوع. |
| [get_valid_tags_count(tags)](#get_valid_tags_count_tags_5) | يحصل على عدد العلامات الصالحة. |
| [is_tag_present(tag)](#is_tag_present_tag_6) | يحدد ما إذا كانت العلامة موجودة في الخيارات أم لا. |
| [remove_tag(tag)](#remove_tag_tag_7) | يزيل العلامة. |
| validate() | يتحقق مما إذا كانت الخيارات تحتوي على تركيبة صالحة من العلامات |


### Constructor: TiffOptions(expected_format) {#TiffOptions_expected_format_1}


```
 TiffOptions(expected_format) 
```

يُنشئ مثلاً جديداً من فئة [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/). يتم استخدام نظام النهاية الصغرى (little endian) بشكل افتراضي.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| expected_format | [TiffExpectedFormat](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffexpectedformat/) | تنسيق ملف TIFF المتوقع. |

### Constructor: TiffOptions(expected_format, byte_order) {#TiffOptions_expected_format_byte_order_2}


```
 TiffOptions(expected_format, byte_order) 
```

يُنشئ مثلاً جديداً من فئة [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| expected_format | [TiffExpectedFormat](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffexpectedformat/) | تنسيق ملف TIFF المتوقع. |
| byte_order | [TiffByteOrder](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffbyteorder/) | ترتيب البايت لتنسيق ملف TIFF المستخدم. |

### Constructor: TiffOptions(options) {#TiffOptions_options_3}


```
 TiffOptions(options) 
```

يُنشئ مثلاً جديداً من فئة [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| options | [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions) | الخيارات التي يتم النسخ منها. |

### Constructor: TiffOptions(tags) {#TiffOptions_tags_4}


```
 TiffOptions(tags) 
```

يُنشئ مثلاً جديداً من فئة [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | العلامات لتهيئة الخيارات بها. |

### Method: add_tag(tag_to_add) {#add_tag_tag_to_add_1}


```
 add_tag(tag_to_add) 
```

يضيف علامة جديدة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| tag_to_add | [TiffDataType](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | العلامة لإضافتها. |

### Method: add_tags(tags_to_add) {#add_tags_tags_to_add_2}


```
 add_tags(tags_to_add) 
```

يضيف العلامات.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| tags_to_add | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | العلامات لإضافتها. |

### Method: clone() {#clone__3}


```
 clone() 
```

ينسخ هذه الحالة.

**Returns**

| النوع | الوصف |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | يعيد نسخة سطحية من هذه الحالة |


### Method: get_tag_by_type(tag_key) {#get_tag_by_type_tag_key_4}


```
 get_tag_by_type(tag_key) 
```

يحصل على نسخة العلامة حسب النوع.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| tag_key | [TiffTags](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifftags/) | مفتاح العلامة. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [TiffDataType](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | مثيل العلامة إذا كان موجودًا أو null خلاف ذلك. |


### Method: get_valid_tags_count(tags)  [static] {#get_valid_tags_count_tags_5}


```
 get_valid_tags_count(tags) 
```

يحصل على عدد العلامات الصالحة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | العلامات المراد التحقق منها. |

**Returns**

| النوع | الوصف |
| :- | :- |
| int | عدد العلامات الصالحة. |


### Method: is_tag_present(tag) {#is_tag_present_tag_6}


```
 is_tag_present(tag) 
```

يحدد ما إذا كانت العلامة موجودة في الخيارات أم لا.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| tag | [TiffTags](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifftags/) | معرّف العلامة للتحقق منه. |

**Returns**

| النوع | الوصف |
| :- | :- |
| bool | <c>true</c> إذا كانت العلامة موجودة؛ وإلا <c>false</c>. |


### Method: remove_tag(tag) {#remove_tag_tag_7}


```
 remove_tag(tag) 
```

يزيل العلامة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| tag | [TiffTags](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifftags/) | العلامة لإزالتها. |

**Returns**

| النوع | الوصف |
| :- | :- |
| bool | true إذا تم الإزالة بنجاح |


