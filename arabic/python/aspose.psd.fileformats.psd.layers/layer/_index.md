---
title: "فئة Layer"
type: docs
weight: 930
url: /ar/python-net/aspose.psd.fileformats.psd.layers/layer/
---

**Summary:** The psd layer.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.Layer

**Inheritance:** IObjectWithBounds, IRasterImageArgb32PixelLoader, IRasterImageRawDataLoader, RasterCachedImage

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [Layer()](#Layer__1) | يُنشئ مثلاً جديداً من الفئة [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/). مُنشئ للتهيئة الكسولة. |
| [Layer(bounds, red_bytes, green_bytes, blue_bytes, name)](#Layer_bounds_red_bytes_green_bytes_blue_bytes_name_2) | يُنشئ مثلاً جديداً من الفئة [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) من مصفوفات البايت. |
| [Layer(image, dispose_image)](#Layer_image_dispose_image_3) | يُنشئ مثلاً جديداً من الفئة [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/). |
| [Layer(stream)](#Layer_stream_4) | يُنشئ مثلاً جديداً من الفئة [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| BLEND_SIGNATURE [ثابت] | int | r | يمثل توقيع وضع الخلط. |
| LAYER_HEADER_SIZE [ثابت] | int | r | حجم رأس الطبقة. |
| تعديل_تلقائي_لوحة_الألوان | bool | r/w | يحصل أو يضبط قيمة تشير إلى ما إذا كان تعديل اللوحة تلقائيًا. |
| background_color | [Color](/psd/python-net/aspose.psd/color) | r/w | يحصل أو يضبط قيمة للون الخلفية. |
| بتات_لكل_بكسل | int | r | يحصل على عدد بتات الصورة لكل بكسل. |
| دمج_العناصر_المقصوصة | bool | r/w | يحصل أو يضبط خلط العنصر المقصوص. |
| blend_mode_key | [BlendMode](/psd/python-net/aspose.psd.fileformats.core.blending/blendmode/) | r/w | يحصل أو يضبط مفتاح وضع الدمج. |
| توقيع_وضع_الدمج | int | r | يحصل على توقيع وضع المزج. |
| blending_options | [BlendingOptions](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/) | r | يحصل على خيارات المزج. |
| أسفل | int | r/w | يحصل أو يضبط موضع الطبقة السفلية. |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | يحصل على حدود الكائن. |
| تلميح_حجم_المخزن | int | r/w | يحصل أو يعيّن تلميح حجم المخزن المؤقت الذي يُعرّف كحد أقصى مسموح به لجميع المخازن الداخلية. |
| channel_information | [ChannelInformation[]](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | r/w | يحصل أو يضبط معلومات القناة. |
| عدد_القنوات | ushort | r | يحصل على عدد قنوات الطبقة. |
| قص | byte | r/w | يحصل أو يضبط قص الطبقة. 0 = أساسي، 1 = غير أساسي. |
| container | [Image](/psd/python-net/aspose.psd/image) | r | يحصل على حاوية [Image](/psd/python-net/aspose.psd/image/). |
| data_stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | r | يحصل على تدفق بيانات الكائن. |
| اسم_العرض | string | r/w | يحصل أو يضبط الاسم المعروض للطبقة. |
| disposed | bool | r | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن قد تم التخلص منه. |
| extra_length | int | r | يحصل على طول المعلومات الإضافية للطبقة بالبايت. |
| file_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | يحصل على قيمة تنسيق الملف |
| fill_opacity | int | r/w | يحصل أو يضبط شفافية التعبئة. |
| filler | byte | r/w | يحصل أو يضبط ملء الطبقة. |
| flags | [LayerFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layerflags) | r/w | يحصل أو يضبط أعلام الطبقة.<br/>            bit 0 = حماية الشفافية;<br/>            bit 1 = مرئية;<br/>            bit 2 = قديمة;<br/>            bit 3 = 1 لبرنامج Photoshop 5.0 وما بعده، يوضح ما إذا كان bit 4 يحتوي على معلومات مفيدة;<br/>            bit 4 = بيانات البكسل غير ذات صلة بمظهر المستند. |
| has_alpha | bool | r | يحصل على قيمة تشير إلى ما إذا كانت هذه الحالة تحتوي على ألفا. |
| has_background_color | bool | r/w | يحصل أو يضبط قيمة تشير إلى ما إذا كانت الصورة لديها لون خلفية. |
| has_transparent_color | bool | r/w | يحصل على قيمة تشير إلى ما إذا كانت الصورة لديها لون شفاف. |
| الارتفاع | int | r | يحصل على ارتفاع الصورة. |
| horizontal_resolution | double | r/w | يحصل أو يضبط الدقة الأفقية، بوحدة البكسل لكل بوصة، لهذه [RasterImage](/psd/python-net/aspose.psd/rasterimage/). |
| image_opacity | float | r | يحصل على شفافية هذه الصورة. |
| interrupt_monitor | [InterruptMonitor](/psd/python-net/aspose.psd.multithreading/interruptmonitor/) | r/w | يحصل أو يضبط مراقب المقاطعة. |
| is_cached | bool | r | يحصل على قيمة تشير إلى ما إذا كانت بيانات الصورة مخزنة مؤقتًا حاليًا. |
| is_raw_data_available | bool | r | يحصل على قيمة تشير إلى ما إذا كان تحميل البيانات الخام مدعومًا. |
| is_visible | bool | r/w | يحصل أو يضبط قيمة تشير إلى ما إذا كانت الطبقة مرئية |
| is_visible_in_group | bool | r | يحصل على قيمة تشير إلى ما إذا كانت هذه الحالة مرئية في المجموعة (إذا لم تكن الطبقة في مجموعة فهذا يعني مجموعة الجذر). |
| layer_blending_ranges_data | [LayerBlendingRangesData](/psd/python-net/aspose.psd.fileformats.psd.layers/layerblendingrangesdata) | r/w | يحصل أو يضبط بيانات نطاقات مزج الطبقة. |
| layer_creation_date_time | datetime | r/w | يحصل أو يعيّن تاريخ ووقت إنشاء الطبقة. |
| layer_lock | [LayerLockType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/layerlocktype/) | r/w | Gets or sets the layer lock.<br/>            Note that if flag LayerFlags.TransparencyProtected is set it will be overwritten by layer lock flag.<br/>            To return LayerFlags.TransparencyProtected flag need to apply for layer option layer.Flags | = LayerFlags.TransparencyProtected |
| layer_mask_data | [LayerMaskData](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata) | r/w | يحصل أو يعيّن بيانات قناع الطبقة. |
| layer_options | [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/) | r | يحصل على خيارات الطبقة. |
| left | int | r/w | يحصل أو يعيّن موضع الطبقة اليسرى. |
| الطول | int | r | يحصل على الطول الكلي للطبقة بالبايت. |
| name | string | r/w | يحصل أو يعيّن اسم الطبقة. |
| opacity | byte | r/w | يحصل أو يعيّن شفافية الطبقة. 0 = شفاف، 255 = غير شفاف. |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | يحصل أو يعيّن لوحة الألوان. لا تُستخدم لوحة الألوان عندما يتم تمثيل البكسلات مباشرة. |
| premultiply_components | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب ضرب مكونات الصورة مسبقًا. |
| raw_custom_color_converter | [IColorConverter](/psd/python-net/aspose.psd/icolorconverter) | r/w | يحصل أو يعيّن محول الألوان المخصص |
| raw_data_format | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | يحصل على تنسيق البيانات الخام. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | r | يحصل على إعدادات البيانات الخام الحالية. لاحظ أنه عند استخدام هذه الإعدادات يتم تحميل البيانات دون تحويل. |
| raw_fallback_index | int | r/w | يحصل أو يعيّن فهرس الاحتياطي لاستخدامه عندما يكون فهرس لوحة الألوان خارج النطاق |
| raw_indexed_color_converter | [IIndexedColorConverter](/psd/python-net/aspose.psd/iindexedcolorconverter) | r/w | يحصل أو يعيّن محول الألوان المفهرسة |
| raw_line_size | int | r | يحصل على حجم السطر الخام بالبايت. |
| resources | [LayerResource[]](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource) | r/w | يحصل أو يعيّن موارد الطبقة. |
| right | int | r/w | يحصل أو يعيّن موضع الطبقة اليمنى. |
| sheet_color_highlight | [SheetColorHighlightEnum](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/sheetcolorhighlightenum/) | r/w | يحصل أو يعيّن تمييز لون ورقة الزخرفة في قائمة الطبقات |
| size | [Size](/psd/python-net/aspose.psd/size) | r | يحصل على حجم الكائن. |
| أعلى | int | r/w | يحصل أو يعيّن موضع الطبقة العليا. |
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
| [add_layer_mask(layer_mask)](#add_layer_mask_layer_mask_1) | يضيف القناع إلى الطبقة الحالية. |
| [adjust_brightness(brightness)](#adjust_brightness_brightness_2) | ضبط السطوع للصورة. |
| [adjust_contrast(contrast)](#adjust_contrast_contrast_3) | تباين الصورة |
| [adjust_gamma(gamma)](#adjust_gamma_gamma_4) | تصحيح جاما للصورة. |
| [adjust_gamma(gamma_red, gamma_green, gamma_blue)](#adjust_gamma_gamma_red_gamma_green_gamma_blue_5) | تصحيح جاما للصورة. |
| [binarize_bradley(brightness_difference)](#binarize_bradley_brightness_difference_6) | تحويل الصورة إلى ثنائية باستخدام خوارزمية العتبة التكيفية لبرايدلي باستخدام عتبة الصورة المتكاملة |
| [binarize_bradley(brightness_difference, window_size)](#binarize_bradley_brightness_difference_window_size_7) | تحويل الصورة إلى ثنائية باستخدام خوارزمية العتبة التكيفية لبرايدلي باستخدام عتبة الصورة المتكاملة |
| [binarize_fixed(threshold)](#binarize_fixed_threshold_8) | تحويل الصورة إلى ثنائية بعتبة محددة مسبقًا |
| binarize_otsu() | تحويل الصورة إلى ثنائية باستخدام عتبة أوتو |
| cache_data() | يقوم بتخزين البيانات مؤقتًا ويضمن عدم تحميل بيانات إضافية من [DataStreamSupporter.data_stream_container](/psd/python-net/aspose.psd/datastreamsupporter/). |
| [can_load(file_path)](#can_load_file_path_9) | يحدد ما إذا كان يمكن تحميل الصورة من مسار الملف المحدد. |
| [can_load(file_path, load_options)](#can_load_file_path_load_options_10) | يحدد ما إذا كان يمكن تحميل الصورة من مسار الملف المحدد واختياريًا باستخدام خيارات الفتح المحددة. |
| [can_load(stream)](#can_load_stream_11) | يحدد ما إذا كان يمكن تحميل الصورة من الدفق المحدد. |
| [can_load(stream, load_options)](#can_load_stream_load_options_12) | يحدد ما إذا كان يمكن تحميل الصورة من الدفق المحدد واختياريًا باستخدام <paramref name=\"loadOptions\" /> المحدد. |
| [can_save(options)](#can_save_options_13) | يحدد ما إذا كان يمكن حفظ الصورة إلى تنسيق الملف المحدد الممثل بخيارات الحفظ الممررة. |
| [create(image_options, width, height)](#create_image_options_width_height_14) | ينشئ صورة جديدة باستخدام خيارات الإنشاء المحددة. |
| crop(left_shift, right_shift, top_shift, bottom_shift) |  |
| [crop(rectangle)](#crop_rectangle_15) | قص الصورة. |
| [dither(dithering_method, bits_count)](#dither_dithering_method_bits_count_16) | ينفذ تمويه على الصورة الحالية. |
| [dither(dithering_method, bits_count, custom_palette)](#dither_dithering_method_bits_count_custom_palette_17) | ينفذ تمويه على الصورة الحالية. |
| [draw_image(location, image)](#draw_image_location_image_18) | يرسم الصورة على الطبقة. |
| filter(rectangle, options) |  |
| [get_argb_32_pixel(x, y)](#get_argb_32_pixel_x_y_19) | يحصل على بكسل ARGB 32-بت للصورة. |
| [get_default_argb_32_pixels(rectangle)](#get_default_argb_32_pixels_rectangle_20) | يحصل على مصفوفة بكسلات ARGB 32-بت الافتراضية. |
| [get_default_options(args)](#get_default_options_args_21) | يحصل على الخيارات الافتراضية. |
| [get_default_pixels(rectangle, partial_pixel_loader)](#get_default_pixels_rectangle_partial_pixel_loader_22) | يحصل على مصفوفة البكسلات الافتراضية باستخدام محمل البكسل الجزئي. |
| [get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings)](#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_23) | يحصل على مصفوفة البيانات الخام الافتراضية باستخدام محمل البكسل الجزئي. |
| [get_default_raw_data(rectangle, raw_data_settings)](#get_default_raw_data_rectangle_raw_data_settings_24) | يحصل على مصفوفة البيانات الخام الافتراضية. |
| [get_file_format(file_path)](#get_file_format_file_path_25) | يحصل على تنسيق الملف. |
| [get_file_format(stream)](#get_file_format_stream_26) | يحصل على تنسيق الملف. |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_27) | يحصل على المستطيل الذي يتناسب مع الصورة الحالية. |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_28) | يحصل على المستطيل الذي يتناسب مع الصورة الحالية. |
| [get_modify_date(use_default)](#get_modify_date_use_default_29) | يحصل على التاريخ والوقت الذي تم فيه تعديل صورة المورد آخر مرة. |
| [get_original_options()](#get_original_options__30) | يحصل على الخيارات بناءً على إعدادات الملف الأصلي.<br/>            قد يكون هذا مفيدًا للحفاظ على عمق البت وغيرها من معلمات الصورة الأصلية دون تغيير.<br/>            على سبيل المثال، إذا قمنا بتحميل صورة PNG بالأبيض والأسود بعمق 1 بت لكل بكسل ثم حفظناها باستخدام<br/>            [DataStreamSupporter.save(file_path)](/psd/python-net/aspose.psd/datastreamsupporter/) الطريقة، سيتم إنتاج صورة PNG ناتجة بعمق 8 بت لكل بكسل.<br/>            لتجنب ذلك وحفظ صورة PNG بعمق 1 بت لكل بكسل، استخدم هذه الطريقة للحصول على خيارات الحفظ المقابلة ومررها<br/>            إلى [Image.save(file_path, options)](/psd/python-net/aspose.psd/image/) الطريقة كمعامل ثانٍ. |
| [get_pixel(x, y)](#get_pixel_x_y_31) | يحصل على بكسل الصورة.<br/>            تحذير أداء: تجنب استخدام هذه الطريقة للتكرار على جميع بكسلات الصورة لأنها قد تؤدي إلى مشاكل أداء كبيرة.<br/>            للحصول على معالجة بكسلات أكثر كفاءة، استخدم طريقة `LoadArgb32Pixels` لاسترجاع مصفوفة البكسلات بالكامل في آن واحد. |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_32) | يحصل على ارتفاع نسبي. |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_33) | يحصل على عرض نسبي. |
| [get_skew_angle()](#get_skew_angle__34) |    |
| grayscale() | تحويل الصورة إلى تمثيلها بتدرج الرمادي |
| [load(file_path)](#load_file_path_35) | يقوم بتحميل صورة جديدة من الملف المحدد. |
| [load(file_path, load_options)](#load_file_path_load_options_36) | يقوم بتحميل صورة جديدة من الملف المحدد. |
| [load(stream)](#load_stream_37) | يقوم بتحميل صورة جديدة من الدفق المحدد. |
| [load(stream, load_options)](#load_stream_load_options_38) | يقوم بتحميل صورة جديدة من الدفق المحدد. |
| [load_argb_32_pixels(rectangle)](#load_argb_32_pixels_rectangle_39) | يقوم بتحميل بكسلات ARGB 32-بت. |
| [load_argb_64_pixels(rectangle)](#load_argb_64_pixels_rectangle_40) | يقوم بتحميل بكسلات ARGB 64-بت. |
| [load_cmyk_32_pixels(rectangle)](#load_cmyk_32_pixels_rectangle_41) | يقوم بتحميل بكسلات بتنسيق CMYK. |
| [load_cmyk_pixels(rectangle)](#load_cmyk_pixels_rectangle_42) | يقوم بتحميل بكسلات بتنسيق CMYK.<br/>            هذه الطريقة مهجورة. يرجى استخدام الطريقة الأكثر فاعلية [RasterImage.load_cmyk_32_pixels(rectangle)](/psd/python-net/aspose.psd/rasterimage/). |
| [load_partial_argb_32_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_43) | يحمّل بكسلات ARGB 32‑بت جزئياً (حسب الكتل). |
| [load_partial_pixels(desired_rectangle, pixel_loader)](#load_partial_pixels_desired_rectangle_pixel_loader_44) | يقوم بتحميل البكسلات جزئيًا على شكل حزم. |
| [load_pixels(rectangle)](#load_pixels_rectangle_45) | يقوم بتحميل البكسلات. |
| [load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_46) | يحمّل البيانات الخام. |
| [load_raw_data(rectangle, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_raw_data_settings_raw_data_loader_47) | يحمّل البيانات الخام. |
| [merge_layer_to(layer_to_merge_into)](#merge_layer_to_layer_to_merge_into_48) | يدمج الطبقة إلى الطبقة المحددة |
| normalize_angle() |  |
| normalize_angle(resize_proportionally, background_color) |  |
| [read_argb_32_scan_line(scan_line_index)](#read_argb_32_scan_line_scan_line_index_49) | يقرأ كامل سطر المسح وفقًا لمؤشر سطر المسح المحدد. |
| [read_scan_line(scan_line_index)](#read_scan_line_scan_line_index_50) | يقرأ كامل سطر المسح وفقًا لمؤشر سطر المسح المحدد. |
| replace_color(old_color, old_color_diff, new_color) |  |
| replace_color(old_color_argb, old_color_diff, new_color_argb) |  |
| replace_non_transparent_colors(new_color) |  |
| replace_non_transparent_colors(new_color_argb) |  |
| [resize(new_width, new_height)](#resize_new_width_new_height_51) | يعيد تحجيم الصورة. يتم استخدام [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) الافتراضي. |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_52) | يعيد تحجيم الصورة. |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_53) | يعيد تحجيم الصورة. |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_54) | يعيد تحجيم الارتفاع بنسبية. |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_55) | يعيد تحجيم الارتفاع بنسبية. |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_56) | يعيد تحجيم الارتفاع بنسبية. |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_57) | يعيد تحجيم العرض بنسبية. يتم استخدام [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) الافتراضي. |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_58) | يعيد تحجيم العرض بنسبية. |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_59) | يعيد تحجيم العرض بنسبية. |
| rotate(angle) |  |
| [rotate(angle, resize_proportionally, background_color)](#rotate_angle_resize_proportionally_background_color_60) | يدور الصورة حول المركز. |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_61) | يدور، يقلب، أو يدور ويقلب الصورة. |
| save() | يحفظ بيانات الصورة إلى الدفق الأساسي. |
| [save(file_path)](#save_file_path_62) | يحفظ بيانات الكائن إلى موقع الملف المحدد. |
| [save(file_path, options)](#save_file_path_options_63) | يحفظ بيانات الكائن إلى موقع الملف المحدد بالتنسيق المحدد للملف وفقًا لخيارات الحفظ. |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_64) | يحفظ بيانات الكائن إلى موقع الملف المحدد بالتنسيق المحدد للملف وفقًا لخيارات الحفظ. |
| [save(file_path, over_write)](#save_file_path_over_write_65) | يحفظ بيانات الكائن إلى موقع الملف المحدد. |
| [save(stream)](#save_stream_66) | يحفظ بيانات الكائن إلى الدفق المحدد. |
| [save(stream, options_base)](#save_stream_options_base_67) | يحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق المحدد للملف وفقًا لخيارات الحفظ. |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_68) | يحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق المحدد للملف وفقًا لخيارات الحفظ. |
| [save_argb_32_pixels(rectangle, pixels)](#save_argb_32_pixels_rectangle_pixels_69) | يحفظ بكسلات ARGB 32-بت. |
| save_cmyk_32_pixels(rectangle, pixels) |  |
| save_cmyk_pixels(rectangle, pixels) |  |
| [save_pixels(rectangle, pixels)](#save_pixels_rectangle_pixels_70) | يحفظ البكسلات (طريقة خاصة بالتنسيق). |
| [save_raw_data(data, data_offset, rectangle, raw_data_settings)](#save_raw_data_data_data_offset_rectangle_raw_data_settings_71) | يحفظ البيانات الخام. |
| [set_argb_32_pixel(x, y, argb_32_color)](#set_argb_32_pixel_x_y_argb_32_color_72) | يضبط بكسل ARGB 32-بت للصورة في الموضع المحدد. |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_73) | يضبط لوحة ألوان الصورة. |
| [set_pixel(x, y, color)](#set_pixel_x_y_color_74) | يضبط بكسل الصورة في الموضع المحدد. |
| set_resolution(dpi_x, dpi_y) |  |
| [shallow_copy()](#shallow_copy__75) | ينشئ نسخة سطحية من الطبقة الحالية.<br/>            يرجى <see href="https://msdn.microsoft.com/ru-ru/library/system.object.memberwiseclone(v=vs.110).aspx" /> للتوضيح. |
| [to_bitmap()](#to_bitmap__76) |    |
| [write_argb_32_scan_line(scan_line_index, argb_32_pixels)](#write_argb_32_scan_line_scan_line_index_argb_32_pixels_77) | يكتب السطر الكامل للمسح إلى فهرس سطر المسح المحدد. |
| [write_scan_line(scan_line_index, pixels)](#write_scan_line_scan_line_index_pixels_78) | يكتب السطر الكامل للمسح إلى فهرس سطر المسح المحدد. |


### Constructor: Layer() {#Layer__1}


```
 Layer() 
```

يُنشئ مثلاً جديداً من الفئة [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/). مُنشئ للتهيئة الكسولة.

### Constructor: Layer(bounds, red_bytes, green_bytes, blue_bytes, name) {#Layer_bounds_red_bytes_green_bytes_blue_bytes_name_2}


```
 Layer(bounds, red_bytes, green_bytes, blue_bytes, name) 
```

يُنشئ مثلاً جديداً من الفئة [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) من مصفوفات البايت.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | حدود الطبقة. |
| red_bytes | byte | البايتات الحمراء. |
| green_bytes | byte | البايتات الخضراء. |
| blue_bytes | byte | البايتات الزرقاء. |
| name | string | اسم الطبقة. |

### Constructor: Layer(image, dispose_image) {#Layer_image_dispose_image_3}


```
 Layer(image, dispose_image) 
```

يُنشئ مثلاً جديداً من الفئة [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | الصورة. |
| dispose_image | bool | إذا تم تعيينه إلى <c>true</c> [تخلص من الصورة]. |

### Constructor: Layer(stream) {#Layer_stream_4}


```
 Layer(stream) 
```

يُنشئ مثلاً جديداً من الفئة [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| تدفق | _io.BufferedRandom | دفق الصورة |

### Method: add_layer_mask(layer_mask) {#add_layer_mask_layer_mask_1}


```
 add_layer_mask(layer_mask) 
```

يضيف القناع إلى الطبقة الحالية.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| layer_mask | [LayerMaskData](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata) | قناع الطبقة. |

### Method: adjust_brightness(brightness) {#adjust_brightness_brightness_2}


```
 adjust_brightness(brightness) 
```

ضبط السطوع للصورة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| السطوع | int | قيمة السطوع. |

### Method: adjust_contrast(contrast) {#adjust_contrast_contrast_3}


```
 adjust_contrast(contrast) 
```

تباين الصورة

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| التباين | float | قيمة التباين (في النطاق [-100; 100]) |

### Method: adjust_gamma(gamma) {#adjust_gamma_gamma_4}


```
 adjust_gamma(gamma) 
```

تصحيح جاما للصورة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| جاما | float | معامل جاما لقنوات الأحمر والأخضر والأزرق |

### Method: adjust_gamma(gamma_red, gamma_green, gamma_blue) {#adjust_gamma_gamma_red_gamma_green_gamma_blue_5}


```
 adjust_gamma(gamma_red, gamma_green, gamma_blue) 
```

تصحيح جاما للصورة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| gamma_red | float | معامل جاما لقناة الأحمر |
| gamma_green | float | معامل جاما لقناة الأخضر |
| gamma_blue | float | معامل جاما لقناة الأزرق |

### Method: binarize_bradley(brightness_difference) {#binarize_bradley_brightness_difference_6}


```
 binarize_bradley(brightness_difference) 
```

تحويل الصورة إلى ثنائية باستخدام خوارزمية العتبة التكيفية لبرايدلي باستخدام عتبة الصورة المتكاملة

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| brightness_difference | double | فرق السطوع بين البكسل ومتوسط نافذة بحجم s × s من البكسلات المتمركزة حول هذا البكسل. |

### Method: binarize_bradley(brightness_difference, window_size) {#binarize_bradley_brightness_difference_window_size_7}


```
 binarize_bradley(brightness_difference, window_size) 
```

تحويل الصورة إلى ثنائية باستخدام خوارزمية العتبة التكيفية لبرايدلي باستخدام عتبة الصورة المتكاملة

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| brightness_difference | double | فرق السطوع بين البكسل ومتوسط نافذة بحجم s × s من البكسلات المتمركزة حول هذا البكسل. |
| window_size | int | حجم نافذة s × s من البكسلات المتمركزة حول هذا البكسل |

### Method: binarize_fixed(threshold) {#binarize_fixed_threshold_8}


```
 binarize_fixed(threshold) 
```

تحويل الصورة إلى ثنائية بعتبة محددة مسبقًا

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| العتبة | byte | قيمة العتبة. إذا كانت القيمة الرمادية المقابلة للبكسل أكبر من العتبة، سيتم تعيين القيمة 255 له، وإلا 0. |

### Method: can_load(file_path)  [static] {#can_load_file_path_9}


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


### Method: can_load(file_path, load_options)  [static] {#can_load_file_path_load_options_10}


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


### Method: can_load(stream)  [static] {#can_load_stream_11}


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


### Method: can_load(stream, load_options)  [static] {#can_load_stream_load_options_12}


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


### Method: can_save(options) {#can_save_options_13}


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


### Method: create(image_options, width, height)  [static] {#create_image_options_width_height_14}


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


### Method: crop(rectangle) {#crop_rectangle_15}


```
 crop(rectangle) 
```

قص الصورة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | المستطيل. |

### Method: dither(dithering_method, bits_count) {#dither_dithering_method_bits_count_16}


```
 dither(dithering_method, bits_count) 
```

ينفذ تمويه على الصورة الحالية.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/psd/python-net/aspose.psd/ditheringmethod) | طريقة التمويه. |
| bits_count | int | العدد النهائي للبتات للتمويه. |

### Method: dither(dithering_method, bits_count, custom_palette) {#dither_dithering_method_bits_count_custom_palette_17}


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

### Method: draw_image(location, image) {#draw_image_location_image_18}


```
 draw_image(location, image) 
```

يرسم الصورة على الطبقة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| location | [Point](/psd/python-net/aspose.psd/point) | الموقع. |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | الصورة. |

### Method: get_argb_32_pixel(x, y) {#get_argb_32_pixel_x_y_19}


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


### Method: get_default_argb_32_pixels(rectangle) {#get_default_argb_32_pixels_rectangle_20}


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


### Method: get_default_options(args) {#get_default_options_args_21}


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


### Method: get_default_pixels(rectangle, partial_pixel_loader) {#get_default_pixels_rectangle_partial_pixel_loader_22}


```
 get_default_pixels(rectangle, partial_pixel_loader) 
```

يحصل على مصفوفة البكسلات الافتراضية باستخدام محمل البكسل الجزئي.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | المستطيل للحصول على البكسلات. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/psd/python-net/aspose.psd/ipartialargb32pixelloader) | محمل البكسلات الجزئي. |

### Method: get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) {#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_23}


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

### Method: get_default_raw_data(rectangle, raw_data_settings) {#get_default_raw_data_rectangle_raw_data_settings_24}


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


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_25}


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


### Method: get_file_format(stream)  [static] {#get_file_format_stream_26}


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


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_27}


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


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_28}


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


### Method: get_modify_date(use_default) {#get_modify_date_use_default_29}


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


### Method: get_original_options() {#get_original_options__30}


```
 get_original_options() 
```

يحصل على الخيارات بناءً على إعدادات الملف الأصلي.<br/>            قد يكون هذا مفيدًا للحفاظ على عمق البت وغيرها من معلمات الصورة الأصلية دون تغيير.<br/>            على سبيل المثال، إذا قمنا بتحميل صورة PNG بالأبيض والأسود بعمق 1 بت لكل بكسل ثم حفظناها باستخدام<br/>            [DataStreamSupporter.save(file_path)](/psd/python-net/aspose.psd/datastreamsupporter/) الطريقة، سيتم إنتاج صورة PNG ناتجة بعمق 8 بت لكل بكسل.<br/>            لتجنب ذلك وحفظ صورة PNG بعمق 1 بت لكل بكسل، استخدم هذه الطريقة للحصول على خيارات الحفظ المقابلة ومررها<br/>            إلى [Image.save(file_path, options)](/psd/python-net/aspose.psd/image/) الطريقة كمعامل ثانٍ.

**Returns**

| النوع | الوصف |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | الخيارات بناءً على إعدادات الملف الأصلي. |


### Method: get_pixel(x, y) {#get_pixel_x_y_31}


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


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_32}


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


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_33}


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


### Method: get_skew_angle() {#get_skew_angle__34}


```
 get_skew_angle() 
```

  

**Returns**

| النوع | الوصف |
| :- | :- |
| float |  |


### Method: load(file_path)  [static] {#load_file_path_35}


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


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_36}


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


### Method: load(stream)  [static] {#load_stream_37}


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


### Method: load(stream, load_options)  [static] {#load_stream_load_options_38}


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


### Method: load_argb_32_pixels(rectangle) {#load_argb_32_pixels_rectangle_39}


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


### Method: load_argb_64_pixels(rectangle) {#load_argb_64_pixels_rectangle_40}


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


### Method: load_cmyk_32_pixels(rectangle) {#load_cmyk_32_pixels_rectangle_41}


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


### Method: load_cmyk_pixels(rectangle) {#load_cmyk_pixels_rectangle_42}


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


### Method: load_partial_argb_32_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_43}


```
 load_partial_argb_32_pixels(rectangle, partial_pixel_loader) 
```

يحمّل بكسلات ARGB 32‑بت جزئياً (حسب الكتل).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | المستطيل لتحميل البكسلات منه. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/psd/python-net/aspose.psd/ipartialargb32pixelloader) | محمل البكسلات الجزئي. |

### Method: load_partial_pixels(desired_rectangle, pixel_loader) {#load_partial_pixels_desired_rectangle_pixel_loader_44}


```
 load_partial_pixels(desired_rectangle, pixel_loader) 
```

يقوم بتحميل البكسلات جزئيًا على شكل حزم.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| desired_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | المستطيل المطلوب. |
| pixel_loader | [IPartialPixelLoader](/psd/python-net/aspose.psd/ipartialpixelloader) | محمل البكسلات. |

### Method: load_pixels(rectangle) {#load_pixels_rectangle_45}


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


### Method: load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_46}


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

### Method: load_raw_data(rectangle, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_raw_data_settings_raw_data_loader_47}


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

### Method: merge_layer_to(layer_to_merge_into) {#merge_layer_to_layer_to_merge_into_48}


```
 merge_layer_to(layer_to_merge_into) 
```

يدمج الطبقة إلى الطبقة المحددة

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| layer_to_merge_into | [Layer](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | الطبقة للدمج فيها. |

### Method: read_argb_32_scan_line(scan_line_index) {#read_argb_32_scan_line_scan_line_index_49}


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


### Method: read_scan_line(scan_line_index) {#read_scan_line_scan_line_index_50}


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


### Method: resize(new_width, new_height) {#resize_new_width_new_height_51}


```
 resize(new_width, new_height) 
```

يعيد تحجيم الصورة. يتم استخدام [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) الافتراضي.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| new_width | int | العرض الجديد. |
| new_height | int | الارتفاع الجديد. |

### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_52}


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

### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_53}


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

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_54}


```
 resize_height_proportionally(new_height) 
```

يعيد تحجيم الارتفاع بنسبية.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| new_height | int | الارتفاع الجديد. |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_55}


```
 resize_height_proportionally(new_height, resize_type) 
```

يعيد تحجيم الارتفاع بنسبية.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| new_height | int | الارتفاع الجديد. |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | نوع التحجيم. |

### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_56}


```
 resize_height_proportionally(new_height, settings) 
```

يعيد تحجيم الارتفاع بنسبية.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| new_height | int | الارتفاع الجديد. |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | إعدادات تحجيم الصورة. |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_57}


```
 resize_width_proportionally(new_width) 
```

يعيد تحجيم العرض بنسبية. يتم استخدام [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) الافتراضي.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| new_width | int | العرض الجديد. |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_58}


```
 resize_width_proportionally(new_width, resize_type) 
```

يعيد تحجيم العرض بنسبية.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| new_width | int | العرض الجديد. |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | نوع التحجيم. |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_59}


```
 resize_width_proportionally(new_width, settings) 
```

يعيد تحجيم العرض بنسبية.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| new_width | int | العرض الجديد. |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | إعدادات تحجيم الصورة. |

### Method: rotate(angle, resize_proportionally, background_color) {#rotate_angle_resize_proportionally_background_color_60}


```
 rotate(angle, resize_proportionally, background_color) 
```

يدور الصورة حول المركز.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| الزاوية | float | زاوية الدوران بالدرجات. القيم الموجبة ستدور باتجاه عقارب الساعة. |
| resize_proportionally | bool | إذا تم تعيينه إلى <c>true</c> سيتغير حجم الصورة وفقًا لإسقاطات المستطيل المدور (نقاط الزوايا) وإلا سيبقى الأبعاد دون تغيير وتدور محتويات الصورة الداخلية فقط. |
| background_color | [Color](/psd/python-net/aspose.psd/color) | لون الخلفية. |

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_61}


```
 rotate_flip(rotate_flip_type) 
```

يدور، يقلب، أو يدور ويقلب الصورة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/psd/python-net/aspose.psd/rotatefliptype) | نوع تدوير القلب. |

### Method: save(file_path) {#save_file_path_62}


```
 save(file_path) 
```

يحفظ بيانات الكائن إلى موقع الملف المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| file_path | string | مسار الملف لحفظ بيانات الكائن إليه. |

### Method: save(file_path, options) {#save_file_path_options_63}


```
 save(file_path, options) 
```

يحفظ بيانات الكائن إلى موقع الملف المحدد بالتنسيق المحدد للملف وفقًا لخيارات الحفظ.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| file_path | string | مسار الملف. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | الخيارات. |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_64}


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

### Method: save(file_path, over_write) {#save_file_path_over_write_65}


```
 save(file_path, over_write) 
```

يحفظ بيانات الكائن إلى موقع الملف المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| file_path | string | مسار الملف لحفظ بيانات الكائن إليه. |
| over_write | bool | إذا تم تعيينه إلى <c>true</c> سيُستبدل محتوى الملف، وإلا سيحدث الإلحاق. |

### Method: save(stream) {#save_stream_66}


```
 save(stream) 
```

يحفظ بيانات الكائن إلى الدفق المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| تدفق | _io.BufferedRandom | الدفق لحفظ بيانات الكائن إليه. |

### Method: save(stream, options_base) {#save_stream_options_base_67}


```
 save(stream, options_base) 
```

يحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق المحدد للملف وفقًا لخيارات الحفظ.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| تدفق | _io.BufferedRandom | الدفق لحفظ بيانات الصورة إليه. |
| options_base | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | خيارات الحفظ. |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_68}


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

### Method: save_argb_32_pixels(rectangle, pixels) {#save_argb_32_pixels_rectangle_pixels_69}


```
 save_argb_32_pixels(rectangle, pixels) 
```

يحفظ بكسلات ARGB 32-بت.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | المستطيل لحفظ البكسلات فيه. |
| pixels | int | مصفوفة بكسلات ARGB 32‑بت. |

### Method: save_pixels(rectangle, pixels) {#save_pixels_rectangle_pixels_70}


```
 save_pixels(rectangle, pixels) 
```

يحفظ البكسلات (طريقة خاصة بالتنسيق).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | المستطيل لحفظ البكسلات فيه. |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) | مصفوفة بكسلات ARGB 32‑بت. |

### Method: save_raw_data(data, data_offset, rectangle, raw_data_settings) {#save_raw_data_data_data_offset_rectangle_raw_data_settings_71}


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

### Method: set_argb_32_pixel(x, y, argb_32_color) {#set_argb_32_pixel_x_y_argb_32_color_72}


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

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_73}


```
 set_palette(palette, update_colors) 
```

يضبط لوحة ألوان الصورة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | لوحة الألوان لتعيينها. |
| update_colors | bool | إذا تم تعيينه إلى <c>true</c> سيتم تحديث الألوان وفقًا للوحة الألوان الجديدة؛ وإلا ستظل فهارس الألوان دون تغيير. لاحظ أن الفهارس غير المتغيرة قد تتسبب في تعطل الصورة عند التحميل إذا لم يكن لبعض الفهارس إدخالات مطابقة في لوحة الألوان. |

### Method: set_pixel(x, y, color) {#set_pixel_x_y_color_74}


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

### Method: shallow_copy() {#shallow_copy__75}


```
 shallow_copy() 
```

ينشئ نسخة سطحية من الطبقة الحالية.<br/>            يرجى <see href="https://msdn.microsoft.com/ru-ru/library/system.object.memberwiseclone(v=vs.110).aspx" /> للتوضيح.

**Returns**

| النوع | الوصف |
| :- | :- |
| [Layer](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | نسخة سطحية من الطبقة الحالية. |


### Method: to_bitmap() {#to_bitmap__76}


```
 to_bitmap() 
```

  

**Returns**

| النوع | الوصف |
| :- | :- |
| aspose.pydrawing.Bitmap |  |


### Method: write_argb_32_scan_line(scan_line_index, argb_32_pixels) {#write_argb_32_scan_line_scan_line_index_argb_32_pixels_77}


```
 write_argb_32_scan_line(scan_line_index, argb_32_pixels) 
```

يكتب السطر الكامل للمسح إلى فهرس سطر المسح المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| scan_line_index | int | فهرس يبدأ من الصفر لسطر المسح. |
| argb_32_pixels | int | مصفوفة ألوان ARGB 32-بت للكتابة. |

### Method: write_scan_line(scan_line_index, pixels) {#write_scan_line_scan_line_index_pixels_78}


```
 write_scan_line(scan_line_index, pixels) 
```

يكتب السطر الكامل للمسح إلى فهرس سطر المسح المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| scan_line_index | int | فهرس يبدأ من الصفر لسطر المسح. |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) | مصفوفة ألوان البكسل للكتابة. |

