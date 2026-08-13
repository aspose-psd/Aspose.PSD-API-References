---
title: "RasterImage فئة"
type: docs
weight: 3740
url: /ar/python-net/aspose.psd/rasterimage/
---

**Summary:** Represents a raster image supporting raster graphics operations.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.RasterImage

**Inheritance:** IObjectWithBounds, IRasterImageArgb32PixelLoader, IRasterImageRawDataLoader, Image

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| تعديل_تلقائي_لوحة_الألوان | bool | r/w | يحصل أو يضبط قيمة تشير إلى ما إذا كان تعديل اللوحة تلقائيًا. |
| background_color | [Color](/psd/python-net/aspose.psd/color) | r/w | يحصل أو يضبط قيمة للون الخلفية. |
| بتات_لكل_بكسل | int | r | يحصل على عدد بتات الصورة لكل بكسل. |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | يحصل على حدود الصورة. |
| تلميح_حجم_المخزن | int | r/w | يحصل أو يعيّن تلميح حجم المخزن المؤقت الذي يُعرّف كحد أقصى مسموح به لجميع المخازن الداخلية. |
| container | [Image](/psd/python-net/aspose.psd/image) | r | يحصل على حاوية [Image](/psd/python-net/aspose.psd/image/). |
| data_stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | r | يحصل على تدفق بيانات الكائن. |
| disposed | bool | r | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن قد تم التخلص منه. |
| file_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | يحصل على قيمة تنسيق الملف |
| has_alpha | bool | r | يحصل على قيمة تشير إلى ما إذا كانت هذه الحالة تحتوي على ألفا. |
| has_background_color | bool | r/w | يحصل أو يضبط قيمة تشير إلى ما إذا كانت الصورة لديها لون خلفية. |
| has_transparent_color | bool | r/w | يحصل على قيمة تشير إلى ما إذا كانت الصورة لديها لون شفاف. |
| الارتفاع | int | r | يحصل على ارتفاع الصورة. |
| horizontal_resolution | double | r/w | يحصل أو يضبط الدقة الأفقية، بوحدة البكسل لكل بوصة، لهذه [RasterImage](/psd/python-net/aspose.psd/rasterimage/). |
| image_opacity | float | r | يحصل على شفافية هذه الصورة. |
| interrupt_monitor | [InterruptMonitor](/psd/python-net/aspose.psd.multithreading/interruptmonitor/) | r/w | يحصل أو يضبط مراقب المقاطعة. |
| is_cached | bool | r | يحصل على قيمة تشير إلى ما إذا كانت بيانات الكائن مخزنة مؤقتاً حالياً ولا يلزم قراءة البيانات. |
| is_raw_data_available | bool | r | يحصل على قيمة تشير إلى ما إذا كان تحميل البيانات الخام متاحًا. |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | يحصل أو يعيّن لوحة الألوان. لا تُستخدم لوحة الألوان عندما يتم تمثيل البكسلات مباشرة. |
| premultiply_components | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب ضرب مكونات الصورة مسبقًا. |
| raw_custom_color_converter | [IColorConverter](/psd/python-net/aspose.psd/icolorconverter) | r/w | يحصل أو يعيّن محول الألوان المخصص |
| raw_data_format | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | يحصل على تنسيق البيانات الخام. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | r | يحصل على إعدادات البيانات الخام الحالية. لاحظ أنه عند استخدام هذه الإعدادات يتم تحميل البيانات دون تحويل. |
| raw_fallback_index | int | r/w | يحصل أو يعيّن فهرس الاحتياطي لاستخدامه عندما يكون فهرس لوحة الألوان خارج النطاق |
| raw_indexed_color_converter | [IIndexedColorConverter](/psd/python-net/aspose.psd/iindexedcolorconverter) | r/w | يحصل أو يعيّن محول الألوان المفهرسة |
| raw_line_size | int | r | يحصل على حجم السطر الخام بالبايت. |
| size | [Size](/psd/python-net/aspose.psd/size) | r | يحصل على حجم الصورة. |
| transparent_color | [Color](/psd/python-net/aspose.psd/color) | r/w | يحصل على لون الشفافية للصورة. |
| update_xmp_data | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب تحديث بيانات XMP الوصفية. |
| use_palette | bool | r | يحصل على قيمة تشير إلى ما إذا كانت لوحة ألوان الصورة مستخدمة. |
| use_raw_data | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب استخدام تحميل البيانات الخام عندما يكون تحميل البيانات الخام متاحًا. |
| vertical_resolution | double | r/w | يحصل أو يعيّن الدقة العمودية، بوحدات البكسل لكل بوصة، لهذه [RasterImage](/psd/python-net/aspose.psd/rasterimage/). |
| width | int | r | يحصل على عرض الصورة. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | الحصول أو تعيين بيانات XMP الوصفية. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| adjust_brightness(brightness) |  |
| adjust_contrast(contrast) |  |
| adjust_gamma(gamma) |  |
| adjust_gamma(gamma_red, gamma_green, gamma_blue) |  |
| binarize_bradley(brightness_difference) |  |
| binarize_bradley(brightness_difference, window_size) |  |
| binarize_fixed(threshold) |  |
| binarize_otsu() |  |
| cache_data() | يقوم بتخزين البيانات مؤقتًا ويضمن عدم تحميل بيانات إضافية من [DataStreamSupporter.data_stream_container](/psd/python-net/aspose.psd/datastreamsupporter/). |
| [can_load(file_path)](#can_load_file_path_1) | يحدد ما إذا كان يمكن تحميل الصورة من مسار الملف المحدد. |
| [can_load(file_path, load_options)](#can_load_file_path_load_options_2) | يحدد ما إذا كان يمكن تحميل الصورة من مسار الملف المحدد واختياريًا باستخدام خيارات الفتح المحددة. |
| [can_load(stream)](#can_load_stream_3) | يحدد ما إذا كان يمكن تحميل الصورة من الدفق المحدد. |
| [can_load(stream, load_options)](#can_load_stream_load_options_4) | يحدد ما إذا كان يمكن تحميل الصورة من الدفق المحدد واختياريًا باستخدام <paramref name=\"loadOptions\" /> المحدد. |
| [can_save(options)](#can_save_options_5) | يحدد ما إذا كان يمكن حفظ الصورة إلى تنسيق الملف المحدد الممثل بخيارات الحفظ الممررة. |
| [create(image_options, width, height)](#create_image_options_width_height_6) | ينشئ صورة جديدة باستخدام خيارات الإنشاء المحددة. |
| crop(left_shift, right_shift, top_shift, bottom_shift) |  |
| crop(rectangle) |  |
| [dither(dithering_method, bits_count)](#dither_dithering_method_bits_count_7) | ينفذ تمويه على الصورة الحالية. |
| [dither(dithering_method, bits_count, custom_palette)](#dither_dithering_method_bits_count_custom_palette_8) | ينفذ تمويه على الصورة الحالية. |
| filter(rectangle, options) |  |
| [get_argb_32_pixel(x, y)](#get_argb_32_pixel_x_y_9) | يحصل على بكسل ARGB 32-بت للصورة. |
| [get_default_argb_32_pixels(rectangle)](#get_default_argb_32_pixels_rectangle_10) | يحصل على مصفوفة بكسلات ARGB 32-بت الافتراضية. |
| [get_default_options(args)](#get_default_options_args_11) | يحصل على الخيارات الافتراضية. |
| [get_default_pixels(rectangle, partial_pixel_loader)](#get_default_pixels_rectangle_partial_pixel_loader_12) | يحصل على مصفوفة البكسلات الافتراضية باستخدام محمل البكسل الجزئي. |
| [get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings)](#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_13) | يحصل على مصفوفة البيانات الخام الافتراضية باستخدام محمل البكسل الجزئي. |
| [get_default_raw_data(rectangle, raw_data_settings)](#get_default_raw_data_rectangle_raw_data_settings_14) | يحصل على مصفوفة البيانات الخام الافتراضية. |
| [get_file_format(file_path)](#get_file_format_file_path_15) | يحصل على تنسيق الملف. |
| [get_file_format(stream)](#get_file_format_stream_16) | يحصل على تنسيق الملف. |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_17) | يحصل على المستطيل الذي يتناسب مع الصورة الحالية. |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_18) | يحصل على المستطيل الذي يتناسب مع الصورة الحالية. |
| [get_modify_date(use_default)](#get_modify_date_use_default_19) | يحصل على التاريخ والوقت الذي تم فيه تعديل صورة المورد آخر مرة. |
| [get_original_options()](#get_original_options__20) | يحصل على الخيارات بناءً على إعدادات الملف الأصلي.<br/>            قد يكون هذا مفيدًا للحفاظ على عمق البت وغيرها من معلمات الصورة الأصلية دون تغيير.<br/>            على سبيل المثال، إذا قمنا بتحميل صورة PNG بالأبيض والأسود بعمق 1 بت لكل بكسل ثم حفظناها باستخدام<br/>            [DataStreamSupporter.save(file_path)](/psd/python-net/aspose.psd/datastreamsupporter/) الطريقة، سيتم إنتاج صورة PNG ناتجة بعمق 8 بت لكل بكسل.<br/>            لتجنب ذلك وحفظ صورة PNG بعمق 1 بت لكل بكسل، استخدم هذه الطريقة للحصول على خيارات الحفظ المقابلة ومررها<br/>            إلى [Image.save(file_path, options)](/psd/python-net/aspose.psd/image/) الطريقة كمعامل ثانٍ. |
| [get_pixel(x, y)](#get_pixel_x_y_21) | يحصل على بكسل الصورة.<br/>            تحذير أداء: تجنب استخدام هذه الطريقة للتكرار على جميع بكسلات الصورة لأنها قد تؤدي إلى مشاكل أداء كبيرة.<br/>            للحصول على معالجة بكسلات أكثر كفاءة، استخدم طريقة `LoadArgb32Pixels` لاسترجاع مصفوفة البكسلات بالكامل في آن واحد. |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_22) | يحصل على ارتفاع نسبي. |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_23) | يحصل على عرض نسبي. |
| [get_skew_angle()](#get_skew_angle__24) |    |
| grayscale() |  |
| [load(file_path)](#load_file_path_25) | يقوم بتحميل صورة جديدة من الملف المحدد. |
| [load(file_path, load_options)](#load_file_path_load_options_26) | يقوم بتحميل صورة جديدة من الملف المحدد. |
| [load(stream)](#load_stream_27) | يقوم بتحميل صورة جديدة من الدفق المحدد. |
| [load(stream, load_options)](#load_stream_load_options_28) | يقوم بتحميل صورة جديدة من الدفق المحدد. |
| [load_argb_32_pixels(rectangle)](#load_argb_32_pixels_rectangle_29) | يقوم بتحميل بكسلات ARGB 32-بت. |
| [load_argb_64_pixels(rectangle)](#load_argb_64_pixels_rectangle_30) | يقوم بتحميل بكسلات ARGB 64-بت. |
| [load_cmyk_32_pixels(rectangle)](#load_cmyk_32_pixels_rectangle_31) | يقوم بتحميل بكسلات بتنسيق CMYK. |
| [load_cmyk_pixels(rectangle)](#load_cmyk_pixels_rectangle_32) | يقوم بتحميل بكسلات بتنسيق CMYK.<br/>            هذه الطريقة مهجورة. يرجى استخدام الطريقة الأكثر فاعلية [RasterImage.load_cmyk_32_pixels(rectangle)](/psd/python-net/aspose.psd/rasterimage/). |
| [load_partial_argb_32_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_33) | يقوم بتحميل بكسلات ARGB 32-بت جزئيًا على شكل حزم. |
| [load_partial_pixels(desired_rectangle, pixel_loader)](#load_partial_pixels_desired_rectangle_pixel_loader_34) | يقوم بتحميل البكسلات جزئيًا على شكل حزم. |
| [load_pixels(rectangle)](#load_pixels_rectangle_35) | يقوم بتحميل البكسلات. |
| [load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_36) | يحمّل البيانات الخام. |
| [load_raw_data(rectangle, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_raw_data_settings_raw_data_loader_37) | يحمّل البيانات الخام. |
| normalize_angle() |  |
| normalize_angle(resize_proportionally, background_color) |  |
| [read_argb_32_scan_line(scan_line_index)](#read_argb_32_scan_line_scan_line_index_38) | يقرأ كامل سطر المسح وفقًا لمؤشر سطر المسح المحدد. |
| [read_scan_line(scan_line_index)](#read_scan_line_scan_line_index_39) | يقرأ كامل سطر المسح وفقًا لمؤشر سطر المسح المحدد. |
| replace_color(old_color, old_color_diff, new_color) |  |
| replace_color(old_color_argb, old_color_diff, new_color_argb) |  |
| replace_non_transparent_colors(new_color) |  |
| replace_non_transparent_colors(new_color_argb) |  |
| [resize(new_width, new_height)](#resize_new_width_new_height_40) | يعيد تحجيم الصورة. يتم استخدام [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) الافتراضي. |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_41) | يعيد تحجيم الصورة. |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_42) | يعيد تحجيم الصورة. |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_43) | يعيد تحجيم الارتفاع بنسبية. |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_44) | يعيد تحجيم الارتفاع بنسبية. |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_45) | يعيد تحجيم الارتفاع بنسبية. |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_46) | يعيد تحجيم العرض بنسبية. يتم استخدام [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) الافتراضي. |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_47) | يعيد تحجيم العرض بنسبية. |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_48) | يعيد تحجيم العرض بنسبية. |
| rotate(angle) |  |
| rotate(angle, resize_proportionally, background_color) |  |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_49) | يدور، يقلب، أو يدور ويقلب الصورة. |
| save() | يحفظ بيانات الصورة إلى الدفق الأساسي. |
| [save(file_path)](#save_file_path_50) | يحفظ بيانات الكائن إلى موقع الملف المحدد. |
| [save(file_path, options)](#save_file_path_options_51) | يحفظ بيانات الكائن إلى موقع الملف المحدد بالتنسيق المحدد للملف وفقًا لخيارات الحفظ. |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_52) | يحفظ بيانات الكائن إلى موقع الملف المحدد بالتنسيق المحدد للملف وفقًا لخيارات الحفظ. |
| [save(file_path, over_write)](#save_file_path_over_write_53) | يحفظ بيانات الكائن إلى موقع الملف المحدد. |
| [save(stream)](#save_stream_54) | يحفظ بيانات الكائن إلى الدفق المحدد. |
| [save(stream, options_base)](#save_stream_options_base_55) | يحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق المحدد للملف وفقًا لخيارات الحفظ. |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_56) | يحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق المحدد للملف وفقًا لخيارات الحفظ. |
| [save_argb_32_pixels(rectangle, pixels)](#save_argb_32_pixels_rectangle_pixels_57) | يحفظ بكسلات ARGB 32-بت. |
| save_cmyk_32_pixels(rectangle, pixels) |  |
| save_cmyk_pixels(rectangle, pixels) |  |
| [save_pixels(rectangle, pixels)](#save_pixels_rectangle_pixels_58) | يحفظ البكسلات. |
| [save_raw_data(data, data_offset, rectangle, raw_data_settings)](#save_raw_data_data_data_offset_rectangle_raw_data_settings_59) | يحفظ البيانات الخام. |
| [set_argb_32_pixel(x, y, argb_32_color)](#set_argb_32_pixel_x_y_argb_32_color_60) | يضبط بكسل ARGB 32-بت للصورة في الموضع المحدد. |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_61) | يضبط لوحة ألوان الصورة. |
| [set_pixel(x, y, color)](#set_pixel_x_y_color_62) | يضبط بكسل الصورة في الموضع المحدد. |
| set_resolution(dpi_x, dpi_y) |  |
| [to_bitmap()](#to_bitmap__63) |    |
| [write_argb_32_scan_line(scan_line_index, argb_32_pixels)](#write_argb_32_scan_line_scan_line_index_argb_32_pixels_64) | يكتب السطر الكامل للمسح إلى فهرس سطر المسح المحدد. |
| [write_scan_line(scan_line_index, pixels)](#write_scan_line_scan_line_index_pixels_65) | يكتب السطر الكامل للمسح إلى فهرس سطر المسح المحدد. |


### Method: can_load(file_path)  [static] {#can_load_file_path_1}


```
 can_load(file_path) 
```

يحدد ما إذا كان يمكن تحميل الصورة من مسار الملف المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| file_path | string | مسار الملف. |

**Returns**

| النوع | الوصف |
| :- | :- |
| bool | <c>true</c> إذا كان يمكن تحميل الصورة من الملف المحدد؛ وإلا، <c>false</c>. |


### Method: can_load(file_path, load_options)  [static] {#can_load_file_path_load_options_2}


```
 can_load(file_path, load_options) 
```

يحدد ما إذا كان يمكن تحميل الصورة من مسار الملف المحدد واختياريًا باستخدام خيارات الفتح المحددة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| file_path | string | مسار الملف. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | خيارات التحميل. |

**Returns**

| النوع | الوصف |
| :- | :- |
| bool | <c>true</c> إذا كان يمكن تحميل الصورة من الملف المحدد؛ وإلا، <c>false</c>. |


### Method: can_load(stream)  [static] {#can_load_stream_3}


```
 can_load(stream) 
```

يحدد ما إذا كان يمكن تحميل الصورة من الدفق المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| تدفق | _io.BufferedRandom | الدفق للتحميل منه. |

**Returns**

| النوع | الوصف |
| :- | :- |
| bool | <c>true</c> إذا كان يمكن تحميل الصورة من الدفق المحدد؛ وإلا، <c>false</c>. |


### Method: can_load(stream, load_options)  [static] {#can_load_stream_load_options_4}


```
 can_load(stream, load_options) 
```

يحدد ما إذا كان يمكن تحميل الصورة من الدفق المحدد واختياريًا باستخدام <paramref name=\"loadOptions\" /> المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| تدفق | _io.BufferedRandom | الدفق للتحميل منه. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | خيارات التحميل. |

**Returns**

| النوع | الوصف |
| :- | :- |
| bool | <c>true</c> إذا كان يمكن تحميل الصورة من الدفق المحدد؛ وإلا، <c>false</c>. |


### Method: can_save(options) {#can_save_options_5}


```
 can_save(options) 
```

يحدد ما إذا كان يمكن حفظ الصورة إلى تنسيق الملف المحدد الممثل بخيارات الحفظ الممررة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | خيارات الحفظ للاستخدام. |

**Returns**

| النوع | الوصف |
| :- | :- |
| bool | <c>true</c> إذا كان يمكن حفظ الصورة إلى تنسيق الملف المحدد الممثل بخيارات الحفظ الممررة؛ وإلا، <c>false</c>. |


### Method: create(image_options, width, height)  [static] {#create_image_options_width_height_6}


```
 create(image_options, width, height) 
```

ينشئ صورة جديدة باستخدام خيارات الإنشاء المحددة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | خيارات الصورة. |
| width | int | العرض. |
| الارتفاع | int | الارتفاع. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | الصورة التي تم إنشاؤها حديثًا. |


### Method: dither(dithering_method, bits_count) {#dither_dithering_method_bits_count_7}


```
 dither(dithering_method, bits_count) 
```

ينفذ تمويه على الصورة الحالية.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/psd/python-net/aspose.psd/ditheringmethod) | طريقة التمويه. |
| bits_count | int | العدد النهائي للبتات للتمويه. |

### Method: dither(dithering_method, bits_count, custom_palette) {#dither_dithering_method_bits_count_custom_palette_8}


```
 dither(dithering_method, bits_count, custom_palette) 
```

ينفذ تمويه على الصورة الحالية.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/psd/python-net/aspose.psd/ditheringmethod) | طريقة التمويه. |
| bits_count | int | العدد النهائي للبتات للتمويه. |
| custom_palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | لوحة الألوان المخصصة للتمويه. |

### Method: get_argb_32_pixel(x, y) {#get_argb_32_pixel_x_y_9}


```
 get_argb_32_pixel(x, y) 
```

يحصل على بكسل ARGB 32-بت للصورة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| x | int | موقع بكسل x. |
| y | int | موقع بكسل y. |

**Returns**

| النوع | الوصف |
| :- | :- |
| int | بكسل ARGB 32-بت للموقع المحدد. |


### Method: get_default_argb_32_pixels(rectangle) {#get_default_argb_32_pixels_rectangle_10}


```
 get_default_argb_32_pixels(rectangle) 
```

يحصل على مصفوفة بكسلات ARGB 32-بت الافتراضية.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | المستطيل للحصول على البكسلات. |

**Returns**

| النوع | الوصف |
| :- | :- |
| int | مصفوفة البكسلات الافتراضية. |


### Method: get_default_options(args) {#get_default_options_args_11}


```
 get_default_options(args) 
```

يحصل على الخيارات الافتراضية.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| args | object | المعلمات. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | الخيارات الافتراضية |


### Method: get_default_pixels(rectangle, partial_pixel_loader) {#get_default_pixels_rectangle_partial_pixel_loader_12}


```
 get_default_pixels(rectangle, partial_pixel_loader) 
```

يحصل على مصفوفة البكسلات الافتراضية باستخدام محمل البكسل الجزئي.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | المستطيل للحصول على البكسلات. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/psd/python-net/aspose.psd/ipartialargb32pixelloader) | محمل البكسلات الجزئي. |

### Method: get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) {#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_13}


```
 get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) 
```

يحصل على مصفوفة البيانات الخام الافتراضية باستخدام محمل البكسل الجزئي.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | المستطيل للحصول على البكسلات. |
| partial_raw_data_loader | [IPartialRawDataLoader](/psd/python-net/aspose.psd/ipartialrawdataloader) | محمل البيانات الخام الجزئي. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | إعدادات البيانات الخام. |

### Method: get_default_raw_data(rectangle, raw_data_settings) {#get_default_raw_data_rectangle_raw_data_settings_14}


```
 get_default_raw_data(rectangle, raw_data_settings) 
```

يحصل على مصفوفة البيانات الخام الافتراضية.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | المستطيل للحصول على البيانات الخام. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | إعدادات البيانات الخام. |

**Returns**

| النوع | الوصف |
| :- | :- |
| byte | مصفوفة البيانات الخام الافتراضية. |


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_15}


```
 get_file_format(file_path) 
```

يحصل على تنسيق الملف.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| file_path | string | مسار الملف. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [FileFormat](/psd/python-net/aspose.psd/fileformat) | تنسيق الملف المحدد. |


### Method: get_file_format(stream)  [static] {#get_file_format_stream_16}


```
 get_file_format(stream) 
```

يحصل على تنسيق الملف.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| تدفق | _io.BufferedRandom | التدفق. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [FileFormat](/psd/python-net/aspose.psd/fileformat) | تنسيق الملف المحدد. |


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_17}


```
 get_fitting_rectangle(rectangle, pixels, width, height) 
```

يحصل على المستطيل الذي يتناسب مع الصورة الحالية.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | المستطيل للحصول على المستطيل المناسب. |
| pixels | int | بكسلات ARGB 32-بت. |
| width | int | عرض الكائن. |
| الارتفاع | int | ارتفاع الكائن. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | المستطيل المناسب أو استثناء إذا لم يتم العثور على مستطيل مناسب. |


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_18}


```
 get_fitting_rectangle(rectangle, width, height) 
```

يحصل على المستطيل الذي يتناسب مع الصورة الحالية.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | المستطيل للحصول على المستطيل المناسب. |
| width | int | عرض الكائن. |
| الارتفاع | int | ارتفاع الكائن. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | المستطيل المناسب أو استثناء إذا لم يتم العثور على مستطيل مناسب. |


### Method: get_modify_date(use_default) {#get_modify_date_use_default_19}


```
 get_modify_date(use_default) 
```

يحصل على التاريخ والوقت الذي تم فيه تعديل صورة المورد آخر مرة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| use_default | bool | إذا تم تعيينه إلى <c>true</c> يستخدم المعلومات من FileInfo كقيمة افتراضية. |

**Returns**

| النوع | الوصف |
| :- | :- |
| datetime | التاريخ والوقت الذي تم تعديل صورة المورد فيه آخر مرة. |


### Method: get_original_options() {#get_original_options__20}


```
 get_original_options() 
```

يحصل على الخيارات بناءً على إعدادات الملف الأصلي.<br/>            قد يكون هذا مفيدًا للحفاظ على عمق البت وغيرها من معلمات الصورة الأصلية دون تغيير.<br/>            على سبيل المثال، إذا قمنا بتحميل صورة PNG بالأبيض والأسود بعمق 1 بت لكل بكسل ثم حفظناها باستخدام<br/>            [DataStreamSupporter.save(file_path)](/psd/python-net/aspose.psd/datastreamsupporter/) الطريقة، سيتم إنتاج صورة PNG ناتجة بعمق 8 بت لكل بكسل.<br/>            لتجنب ذلك وحفظ صورة PNG بعمق 1 بت لكل بكسل، استخدم هذه الطريقة للحصول على خيارات الحفظ المقابلة ومررها<br/>            إلى [Image.save(file_path, options)](/psd/python-net/aspose.psd/image/) الطريقة كمعامل ثانٍ.

**Returns**

| النوع | الوصف |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | الخيارات بناءً على إعدادات الملف الأصلي. |


### Method: get_pixel(x, y) {#get_pixel_x_y_21}


```
 get_pixel(x, y) 
```

يحصل على بكسل الصورة.<br/>            تحذير أداء: تجنب استخدام هذه الطريقة للتكرار على جميع بكسلات الصورة لأنها قد تؤدي إلى مشاكل أداء كبيرة.<br/>            للحصول على معالجة بكسلات أكثر كفاءة، استخدم طريقة `LoadArgb32Pixels` لاسترجاع مصفوفة البكسلات بالكامل في آن واحد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| x | int | موقع بكسل x. |
| y | int | موقع بكسل y. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | لون البكسل للموقع المحدد. |


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_22}


```
 get_proportional_height(width, height, new_width) 
```

يحصل على ارتفاع نسبي.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| width | int | العرض. |
| الارتفاع | int | الارتفاع. |
| new_width | int | العرض الجديد. |

**Returns**

| النوع | الوصف |
| :- | :- |
| int | الارتفاع النسبي. |


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_23}


```
 get_proportional_width(width, height, new_height) 
```

يحصل على عرض نسبي.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| width | int | العرض. |
| الارتفاع | int | الارتفاع. |
| new_height | int | الارتفاع الجديد. |

**Returns**

| النوع | الوصف |
| :- | :- |
| int | العرض النسبي. |


### Method: get_skew_angle() {#get_skew_angle__24}


```
 get_skew_angle() 
```

  

**Returns**

| النوع | الوصف |
| :- | :- |
| float |  |


### Method: load(file_path)  [static] {#load_file_path_25}


```
 load(file_path) 
```

يقوم بتحميل صورة جديدة من الملف المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| file_path | string | مسار الملف لتحميل الصورة منه. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | الصورة المحملة. |


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_26}


```
 load(file_path, load_options) 
```

يقوم بتحميل صورة جديدة من الملف المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| file_path | string | مسار الملف لتحميل الصورة منه. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | خيارات التحميل. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | الصورة المحملة. |


### Method: load(stream)  [static] {#load_stream_27}


```
 load(stream) 
```

يقوم بتحميل صورة جديدة من الدفق المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| تدفق | _io.BufferedRandom | الدفق لتحميل الصورة منه. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | الصورة المحملة. |


### Method: load(stream, load_options)  [static] {#load_stream_load_options_28}


```
 load(stream, load_options) 
```

يقوم بتحميل صورة جديدة من الدفق المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| تدفق | _io.BufferedRandom | الدفق لتحميل الصورة منه. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | خيارات التحميل. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | الصورة المحملة. |


### Method: load_argb_32_pixels(rectangle) {#load_argb_32_pixels_rectangle_29}


```
 load_argb_32_pixels(rectangle) 
```

يقوم بتحميل بكسلات ARGB 32-بت.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | المستطيل لتحميل البكسلات منه. |

**Returns**

| النوع | الوصف |
| :- | :- |
| int | مصفوفة بكسلات ARGB 32‑بت المحملة. |


### Method: load_argb_64_pixels(rectangle) {#load_argb_64_pixels_rectangle_30}


```
 load_argb_64_pixels(rectangle) 
```

يقوم بتحميل بكسلات ARGB 64-بت.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | المستطيل لتحميل البكسلات منه. |

**Returns**

| النوع | الوصف |
| :- | :- |
| long | مصفوفة بكسلات ARGB 64‑بت المحملة. |


### Method: load_cmyk_32_pixels(rectangle) {#load_cmyk_32_pixels_rectangle_31}


```
 load_cmyk_32_pixels(rectangle) 
```

يقوم بتحميل بكسلات بتنسيق CMYK.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | المستطيل لتحميل البكسلات منه. |

**Returns**

| النوع | الوصف |
| :- | :- |
| int | بكسلات CMYK المحملة مقدمة كقيم صحيحة 32‑بت. |


### Method: load_cmyk_pixels(rectangle) {#load_cmyk_pixels_rectangle_32}


```
 load_cmyk_pixels(rectangle) 
```

يقوم بتحميل بكسلات بتنسيق CMYK.<br/>            هذه الطريقة مهجورة. يرجى استخدام الطريقة الأكثر فاعلية [RasterImage.load_cmyk_32_pixels(rectangle)](/psd/python-net/aspose.psd/rasterimage/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | المستطيل لتحميل البكسلات منه. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | مصفوفة بكسلات CMYK المحملة. |


### Method: load_partial_argb_32_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_33}


```
 load_partial_argb_32_pixels(rectangle, partial_pixel_loader) 
```

يقوم بتحميل بكسلات ARGB 32-بت جزئيًا على شكل حزم.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | المستطيل المطلوب. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/psd/python-net/aspose.psd/ipartialargb32pixelloader) | محمل بكسلات ARGB 32-بت. |

### Method: load_partial_pixels(desired_rectangle, pixel_loader) {#load_partial_pixels_desired_rectangle_pixel_loader_34}


```
 load_partial_pixels(desired_rectangle, pixel_loader) 
```

يقوم بتحميل البكسلات جزئيًا على شكل حزم.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| desired_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | المستطيل المطلوب. |
| pixel_loader | [IPartialPixelLoader](/psd/python-net/aspose.psd/ipartialpixelloader) | محمل البكسلات. |

### Method: load_pixels(rectangle) {#load_pixels_rectangle_35}


```
 load_pixels(rectangle) 
```

يقوم بتحميل البكسلات.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | المستطيل لتحميل البكسلات منه. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | مصفوفة البكسلات المحملة. |


### Method: load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_36}


```
 load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) 
```

يحمّل البيانات الخام.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | المستطيل لتحميل البيانات الخام منه. |
| dest_image_bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | حدود صورة الوجهة. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | إعدادات البيانات الخام لاستخدامها مع البيانات المحملة. ملاحظة: إذا لم تكن البيانات بالتنسيق المحدد فسيتم تحويل البيانات. |
| raw_data_loader | [IPartialRawDataLoader](/psd/python-net/aspose.psd/ipartialrawdataloader) | محمل البيانات الخام. |

### Method: load_raw_data(rectangle, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_raw_data_settings_raw_data_loader_37}


```
 load_raw_data(rectangle, raw_data_settings, raw_data_loader) 
```

يحمّل البيانات الخام.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | المستطيل لتحميل البيانات الخام منه. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | إعدادات البيانات الخام لاستخدامها مع البيانات المحملة. ملاحظة: إذا لم تكن البيانات بالتنسيق المحدد فسيتم تحويل البيانات. |
| raw_data_loader | [IPartialRawDataLoader](/psd/python-net/aspose.psd/ipartialrawdataloader) | محمل البيانات الخام. |

### Method: read_argb_32_scan_line(scan_line_index) {#read_argb_32_scan_line_scan_line_index_38}


```
 read_argb_32_scan_line(scan_line_index) 
```

يقرأ كامل سطر المسح وفقًا لمؤشر سطر المسح المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| scan_line_index | int | فهرس يبدأ من الصفر لسطر المسح. |

**Returns**

| النوع | الوصف |
| :- | :- |
| int | مصفوفة قيم ألوان ARGB 32‑بت لسطر المسح. |


### Method: read_scan_line(scan_line_index) {#read_scan_line_scan_line_index_39}


```
 read_scan_line(scan_line_index) 
```

يقرأ كامل سطر المسح وفقًا لمؤشر سطر المسح المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| scan_line_index | int | فهرس يبدأ من الصفر لسطر المسح. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | مصفوفة قيم ألوان بكسل سطر المسح. |


### Method: resize(new_width, new_height) {#resize_new_width_new_height_40}


```
 resize(new_width, new_height) 
```

يعيد تحجيم الصورة. يتم استخدام [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) الافتراضي.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| new_width | int | العرض الجديد. |
| new_height | int | الارتفاع الجديد. |

### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_41}


```
 resize(new_width, new_height, resize_type) 
```

يعيد تحجيم الصورة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| new_width | int | العرض الجديد. |
| new_height | int | الارتفاع الجديد. |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | نوع التحجيم. |

### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_42}


```
 resize(new_width, new_height, settings) 
```

يعيد تحجيم الصورة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| new_width | int | العرض الجديد. |
| new_height | int | الارتفاع الجديد. |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | إعدادات التحجيم. |

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_43}


```
 resize_height_proportionally(new_height) 
```

يعيد تحجيم الارتفاع بنسبية.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| new_height | int | الارتفاع الجديد. |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_44}


```
 resize_height_proportionally(new_height, resize_type) 
```

يعيد تحجيم الارتفاع بنسبية.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| new_height | int | الارتفاع الجديد. |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | نوع التحجيم. |

### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_45}


```
 resize_height_proportionally(new_height, settings) 
```

يعيد تحجيم الارتفاع بنسبية.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| new_height | int | الارتفاع الجديد. |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | إعدادات تحجيم الصورة. |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_46}


```
 resize_width_proportionally(new_width) 
```

يعيد تحجيم العرض بنسبية. يتم استخدام [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) الافتراضي.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| new_width | int | العرض الجديد. |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_47}


```
 resize_width_proportionally(new_width, resize_type) 
```

يعيد تحجيم العرض بنسبية.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| new_width | int | العرض الجديد. |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | نوع التحجيم. |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_48}


```
 resize_width_proportionally(new_width, settings) 
```

يعيد تحجيم العرض بنسبية.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| new_width | int | العرض الجديد. |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | إعدادات تحجيم الصورة. |

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_49}


```
 rotate_flip(rotate_flip_type) 
```

يدور، يقلب، أو يدور ويقلب الصورة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/psd/python-net/aspose.psd/rotatefliptype) | نوع التدوير أو القلب. |

### Method: save(file_path) {#save_file_path_50}


```
 save(file_path) 
```

يحفظ بيانات الكائن إلى موقع الملف المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| file_path | string | مسار الملف لحفظ بيانات الكائن إليه. |

### Method: save(file_path, options) {#save_file_path_options_51}


```
 save(file_path, options) 
```

يحفظ بيانات الكائن إلى موقع الملف المحدد بالتنسيق المحدد للملف وفقًا لخيارات الحفظ.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| file_path | string | مسار الملف. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | الخيارات. |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_52}


```
 save(file_path, options, bounds_rectangle) 
```

يحفظ بيانات الكائن إلى موقع الملف المحدد بالتنسيق المحدد للملف وفقًا لخيارات الحفظ.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| file_path | string | مسار الملف. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | الخيارات. |
| bounds_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | مستطيل حدود الصورة الوجهة. اضبط المستطيل الفارغ لاستخدام حدود المصدر. |

### Method: save(file_path, over_write) {#save_file_path_over_write_53}


```
 save(file_path, over_write) 
```

يحفظ بيانات الكائن إلى موقع الملف المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| file_path | string | مسار الملف لحفظ بيانات الكائن إليه. |
| over_write | bool | إذا تم تعيينه إلى <c>true</c> سيُستبدل محتوى الملف، وإلا سيحدث الإلحاق. |

### Method: save(stream) {#save_stream_54}


```
 save(stream) 
```

يحفظ بيانات الكائن إلى الدفق المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| تدفق | _io.BufferedRandom | الدفق لحفظ بيانات الكائن إليه. |

### Method: save(stream, options_base) {#save_stream_options_base_55}


```
 save(stream, options_base) 
```

يحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق المحدد للملف وفقًا لخيارات الحفظ.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| تدفق | _io.BufferedRandom | الدفق لحفظ بيانات الصورة إليه. |
| options_base | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | خيارات الحفظ. |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_56}


```
 save(stream, options_base, bounds_rectangle) 
```

يحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق المحدد للملف وفقًا لخيارات الحفظ.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| تدفق | _io.BufferedRandom | الدفق لحفظ بيانات الصورة إليه. |
| options_base | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | خيارات الحفظ. |
| bounds_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | مستطيل حدود الصورة الوجهة. اضبط المستطيل الفارغ لاستخدام حدود المصدر. |

### Method: save_argb_32_pixels(rectangle, pixels) {#save_argb_32_pixels_rectangle_pixels_57}


```
 save_argb_32_pixels(rectangle, pixels) 
```

يحفظ بكسلات ARGB 32-بت.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | المستطيل لحفظ البكسلات فيه. |
| pixels | int | مصفوفة بكسلات ARGB 32‑بت. |

### Method: save_pixels(rectangle, pixels) {#save_pixels_rectangle_pixels_58}


```
 save_pixels(rectangle, pixels) 
```

يحفظ البكسلات.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | المستطيل لحفظ البكسلات فيه. |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) | مصفوفة البكسلات. |

### Method: save_raw_data(data, data_offset, rectangle, raw_data_settings) {#save_raw_data_data_data_offset_rectangle_raw_data_settings_59}


```
 save_raw_data(data, data_offset, rectangle, raw_data_settings) 
```

يحفظ البيانات الخام.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| البيانات | byte | البيانات الخام. |
| data_offset | int | إزاحة البيانات الخام الابتدائية. |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | مستطيل البيانات الخام. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | إعدادات البيانات الخام التي توجد فيها البيانات. |

### Method: set_argb_32_pixel(x, y, argb_32_color) {#set_argb_32_pixel_x_y_argb_32_color_60}


```
 set_argb_32_pixel(x, y, argb_32_color) 
```

يضبط بكسل ARGB 32-بت للصورة في الموضع المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| x | int | موقع بكسل x. |
| y | int | موقع بكسل y. |
| argb_32_color | int | بكسل ARGB 32‑بت للموقع المحدد. |

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_61}


```
 set_palette(palette, update_colors) 
```

يضبط لوحة ألوان الصورة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | لوحة الألوان لتعيينها. |
| update_colors | bool | إذا تم تعيينه إلى <c>true</c> سيتم تحديث الألوان وفقًا للوحة الألوان الجديدة؛ وإلا ستظل فهارس الألوان دون تغيير. لاحظ أن الفهارس غير المتغيرة قد تتسبب في تعطل الصورة عند التحميل إذا لم يكن لبعض الفهارس إدخالات مطابقة في لوحة الألوان. |

### Method: set_pixel(x, y, color) {#set_pixel_x_y_color_62}


```
 set_pixel(x, y, color) 
```

يضبط بكسل الصورة في الموضع المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| x | int | موقع بكسل x. |
| y | int | موقع بكسل y. |
| color | [Color](/psd/python-net/aspose.psd/color) | لون البكسل للموقع المحدد. |

### Method: to_bitmap() {#to_bitmap__63}


```
 to_bitmap() 
```

  

**Returns**

| النوع | الوصف |
| :- | :- |
| aspose.pydrawing.Bitmap |  |


### Method: write_argb_32_scan_line(scan_line_index, argb_32_pixels) {#write_argb_32_scan_line_scan_line_index_argb_32_pixels_64}


```
 write_argb_32_scan_line(scan_line_index, argb_32_pixels) 
```

يكتب السطر الكامل للمسح إلى فهرس سطر المسح المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| scan_line_index | int | فهرس يبدأ من الصفر لسطر المسح. |
| argb_32_pixels | int | مصفوفة ألوان ARGB 32-بت للكتابة. |

### Method: write_scan_line(scan_line_index, pixels) {#write_scan_line_scan_line_index_pixels_65}


```
 write_scan_line(scan_line_index, pixels) 
```

يكتب السطر الكامل للمسح إلى فهرس سطر المسح المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| scan_line_index | int | فهرس يبدأ من الصفر لسطر المسح. |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) | مصفوفة ألوان البكسل للكتابة. |

