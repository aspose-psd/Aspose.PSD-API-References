---
title: "فئة PsdImage"
type: docs
weight: 1760
url: /ar/python-net/aspose.psd.fileformats.psd/psdimage/
---

**Summary:** Defines the PsdImage class that provides the ability to load, edit, save PSD files as well as<br/>            update properties, add watermarks, perform graphics operations or convert one file format to another.<br/>            Aspose.PSD supports import as a layer and export to the following formats:<br/>            Png, Jpeg, Jpeg2000, Gif, Bmp, Tiff, Psd, Psb along with export to Pdf with selectable text

**Module:** [aspose.psd.fileformats.psd](/psd/python-net/aspose.psd.fileformats.psd/)

**Full Name:** aspose.psd.fileformats.psd.PsdImage

**Inheritance:** IObjectWithBounds, IRasterImageArgb32PixelLoader, IRasterImageRawDataLoader, RasterCachedImage

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [PsdImage(path)](#PsdImage_path_1) | يُهيئ مثيلاً جديدًا من فئة [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) من مسار محدد لصورة نقطية (ليس صورة psd في المسار). يُستخدم لتهيئة صورة psd بالمعلمات الافتراضية - وضع اللون - rgb، 4 قنوات، 8 بت لكل قناة، الضغط - Raw. |
| [PsdImage(path, color_mode, channel_bit_depth, channels, psd_version, compression)](#PsdImage_path_color_mode_channel_bit_depth_channels_psd_version_compression_2) | يُهيئ مثيلاً جديدًا من فئة [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) من مسار محدد لصورة نقطية (ليس صورة psd في المسار) مع معلمات البنية. |
| [PsdImage(raster_image)](#PsdImage_raster_image_3) | يُهيئ مثيلاً جديدًا من فئة [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) من صورة نقطية موجودة (ليس صورة psd) بوضع اللون RGB مع 4 قنوات 8 بت/قناة دون ضغط. |
| [PsdImage(raster_image, color_mode, channel_bit_depth, channels, psd_version, compression)](#PsdImage_raster_image_color_mode_channel_bit_depth_channels_psd_version_compression_4) | يُهيئ مثيلاً جديدًا من فئة [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) من صورة نقطية موجودة (ليس صورة psd) مع معلمات البنية. |
| [PsdImage(stream)](#PsdImage_stream_5) | يُهيئ مثيلاً جديدًا من فئة [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) من مسار محدد لصورة نقطية (ليس صورة psd في الدفق). يُستخدم لتهيئة صورة psd بالمعلمات الافتراضية - وضع اللون - rgb، 4 قنوات، 8 بت لكل قناة، الضغط - Raw. |
| [PsdImage(stream, color_mode, channel_bit_depth, channels, psd_version, compression)](#PsdImage_stream_color_mode_channel_bit_depth_channels_psd_version_compression_6) | يُهيئ مثيلاً جديدًا من فئة [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) من مسار محدد لصورة نقطية (ليس صورة psd في الدفق) مع معلمات البنية. |
| [PsdImage(width, height)](#PsdImage_width_height_7) | يُهيئ مثيلاً جديدًا من فئة [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) بالعرض والارتفاع المحددين. يُستخدم لتهيئة صورة psd فارغة. |
| [PsdImage(width, height, color_palette, color_mode, channel_bit_depth, channels, psd_version, compression)](#PsdImage_width_height_color_palette_color_mode_channel_bit_depth_channels_psd_version_compression_8) | يُهيئ مثيلاً جديدًا من فئة [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) بالعرض والارتفاع، واللوحة، ووضع اللون، وعدد القنوات وطول بت القنوات، ومعلمات وضع الضغط المحددة. يُستخدم لتهيئة صورة psd فارغة. |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| DEFAULT_VERSION [static] | int | r | الإصدار الافتراضي لـ PSD. |
| active_layer | [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | r/w | يحصل أو يضبط الطبقة النشطة. |
| تعديل_تلقائي_لوحة_الألوان | bool | r/w | يحصل أو يضبط قيمة تشير إلى ما إذا كان تعديل اللوحة تلقائيًا. |
| background_color | [Color](/psd/python-net/aspose.psd/color) | r/w | يحصل أو يضبط قيمة للون الخلفية. |
| bits_per_channel | int | r | يحصل على عدد البتات لكل قناة. |
| بتات_لكل_بكسل | int | r | يحصل على عدد بتات الصورة لكل بكسل. |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | يحصل على حدود الكائن. |
| تلميح_حجم_المخزن | int | r/w | يحصل أو يعيّن تلميح حجم المخزن المؤقت الذي يُعرّف كحد أقصى مسموح به لجميع المخازن الداخلية. |
| عدد_القنوات | int | r | يحصل على عدد قنوات PSD. |
| cmyk_color_profile | [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/) | r/w | يحصل أو يضبط ملف تعريف اللون CMYK لصور PSD بنظام CMYK. يجب أن يكون مقترناً بـ RgbColorProfile للتحويل اللوني الصحيح. |
| color_mode | [ColorModes](/psd/python-net/aspose.psd.fileformats.psd/colormodes) | r/w | يحصل أو يضبط وضع اللون. |
| compression | [CompressionMethod](/psd/python-net/aspose.psd.fileformats.psd/compressionmethod) | r | يحصل على طريقة الضغط. |
| container | [Image](/psd/python-net/aspose.psd/image) | r | يحصل على حاوية [Image](/psd/python-net/aspose.psd/image/). |
| data_stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | r | يحصل على تدفق بيانات الكائن. |
| disposed | bool | r | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن قد تم التخلص منه. |
| file_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | يحصل على قيمة تنسيق الملف |
| global_angle | int | r/w | يحصل أو يضبط الزاوية العامة. |
| global_layer_mask_info | [GlobalLayerMaskInfo](/psd/python-net/aspose.psd.fileformats.psd.layers/globallayermaskinfo/) | r | يحصل على معلومات قناع الطبقة العامة. |
| global_layer_resources | [LayerResource[]](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/) | r/w | يحصل أو يضبط موارد الطبقة العامة. |
| gray_color_profile | [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/) | r/w | يحصل أو يضبط ملف تعريف اللون GRAY (أحادي اللون) لصور PSD بتدرج الرمادي. |
| has_alpha | bool | r | يحصل أو يعيّن الدقة العمودية، بوحدات البكسل لكل بوصة، لهذه [RasterImage](/psd/python-net/aspose.psd/rasterimage/). |
| has_background_color | bool | r/w | يحصل أو يضبط قيمة تشير إلى ما إذا كانت الصورة لديها لون خلفية. |
| has_transparency_data | bool | r/w | يحصل أو يضبط قيمة تشير إلى ما إذا كانت قناة ألفا الأولى تحتوي على بيانات الشفافية للنتيجة المدمجة عند تحديد بيانات الطبقات. |
| has_transparent_color | bool | r/w | يحصل على قيمة تشير إلى ما إذا كانت الصورة لديها لون شفاف. |
| الارتفاع | int | r | يحصل على ارتفاع الصورة. |
| horizontal_resolution | double | r/w | يحصل أو يضبط الدقة الأفقية، بوحدات البكسل لكل بوصة، لهذا [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/). |
| image_opacity | float | r | يحصل على شفافية هذه الصورة. |
| image_resources | [ResourceBlock[]](/psd/python-net/aspose.psd.fileformats.psd/resourceblock) | r/w | يحصل أو يضبط موارد صورة PSD. |
| interrupt_monitor | [InterruptMonitor](/psd/python-net/aspose.psd.multithreading/interruptmonitor/) | r/w | يحصل أو يضبط مراقب المقاطعة. |
| is_cached | bool | r | يحصل على قيمة تشير إلى ما إذا كانت بيانات الصورة مخزنة مؤقتًا حاليًا. |
| is_flatten | bool | r | يحصل على قيمة تشير إلى ما إذا كانت صورة PSD مسطحة. |
| is_raw_data_available | bool | r | يحصل على قيمة تشير إلى ما إذا كان تحميل البيانات الخام مدعومًا. |
| layers | [Layer[]](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | r/w | يحصل أو يضبط طبقات PSD. |
| linked_layers_manager | [LinkedLayersManager](/psd/python-net/aspose.psd.fileformats.psd.layers/linkedlayersmanager/) | r | يحصل على مدير الطبقات المرتبطة. |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | يحصل أو يعيّن لوحة الألوان. لا تُستخدم لوحة الألوان عندما يتم تمثيل البكسلات مباشرة. |
| premultiply_components | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب ضرب مكونات الصورة مسبقًا. |
| raw_custom_color_converter | [IColorConverter](/psd/python-net/aspose.psd/icolorconverter) | r/w | يحصل أو يعيّن محول الألوان المخصص |
| raw_data_format | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | يحصل على تنسيق البيانات الخام. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | r | يحصل على إعدادات البيانات الخام الحالية. لاحظ أنه عند استخدام هذه الإعدادات يتم تحميل البيانات دون تحويل. |
| raw_fallback_index | int | r/w | يحصل أو يعيّن فهرس الاحتياطي لاستخدامه عندما يكون فهرس لوحة الألوان خارج النطاق |
| raw_indexed_color_converter | [IIndexedColorConverter](/psd/python-net/aspose.psd/iindexedcolorconverter) | r/w | يحصل أو يعيّن محول الألوان المفهرسة |
| raw_line_size | int | r | يحصل على حجم السطر الخام بالبايت. |
| rgb_color_profile | [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/) | r/w | يحصل أو يضبط ملف تعريف اللون RGB لصور PSD بنظام CMYK. يجب أن يكون مقترناً بـ CmykColorProfile للتحويل اللوني الصحيح. |
| size | [Size](/psd/python-net/aspose.psd/size) | r | يحصل على حجم الكائن. |
| smart_object_provider | [SmartObjectProvider](/psd/python-net/aspose.psd.fileformats.psd/smartobjectprovider) | r | يحصل على موفر الكائن الذكي. |
| timeline | [Timeline](/psd/python-net/aspose.psd.fileformats.psd.layers.animation/timeline/) | r | يحصل على [PsdImage.timeline](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) لهذا [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/). |
| transparent_color | [Color](/psd/python-net/aspose.psd/color) | r/w | يحصل على لون الشفافية للصورة. |
| update_xmp_data | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب تحديث بيانات XMP الوصفية. |
| use_palette | bool | r | يحصل على قيمة تشير إلى ما إذا كانت لوحة ألوان الصورة مستخدمة. |
| use_raw_data | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب استخدام تحميل البيانات الخام عندما يكون تحميل البيانات الخام متاحًا. |
| version | int | r/w | يحصل أو يعيّن الإصدار. |
| vertical_resolution | double | r/w | يحصل أو يضبط الدقة العمودية، بوحدات البكسل لكل بوصة، لهذا [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/). |
| width | int | r | يحصل على عرض الصورة. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | الحصول أو تعيين بيانات XMP الوصفية. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [add_black_white_adjustment_layer()](#add_black_white_adjustment_layer__1) | يضيف طبقة تعديل أبيض وأسود. |
| [add_brightness_contrast_adjustment_layer(brightness, contrast)](#add_brightness_contrast_adjustment_layer_brightness_contrast_2) | يضيف طبقة تعديل السطوع/التباين. |
| [add_channel_mixer_adjustment_layer()](#add_channel_mixer_adjustment_layer__3) | يضيف طبقة تعديل خالط القنوات مع المعلمات الافتراضية |
| [add_color_balance_adjustment_layer()](#add_color_balance_adjustment_layer__4) | يضيف طبقة تعديل توازن اللون. |
| [add_curves_adjustment_layer()](#add_curves_adjustment_layer__5) | يضيف طبقة تعديل المنحنيات. |
| [add_exposure_adjustment_layer(exposure, offset, gamma_correction)](#add_exposure_adjustment_layer_exposure_offset_gamma_correction_6) | يضيف طبقة تعديل التعرض. |
| [add_gradient_map_adjustment_layer()](#add_gradient_map_adjustment_layer__7) | يضيف طبقة تعديل خريطة التدرج. |
| [add_hue_saturation_adjustment_layer()](#add_hue_saturation_adjustment_layer__8) | يضيف طبقة تعديل الصبغة/التشبع. |
| [add_invert_adjustment_layer()](#add_invert_adjustment_layer__9) | يضيف طبقة تعديل عكس. |
| [add_layer(layer)](#add_layer_layer_10) | يضيف الطبقة. |
| [add_layer_group(group_name, index, start_behaviour)](#add_layer_group_group_name_index_start_behaviour_11) | يضيف مجموعة الطبقة. |
| [add_levels_adjustment_layer()](#add_levels_adjustment_layer__12) | يضيف طبقة تعديل المستويات. |
| [add_photo_filter_layer(color)](#add_photo_filter_layer_color_13) | يضيف طبقة مرشح الصورة. |
| [add_posterize_adjustment_layer()](#add_posterize_adjustment_layer__14) | يضيف طبقة تعديل التسطير. |
| [add_regular_layer()](#add_regular_layer__15) | يضيف طبقة عادية جديدة. |
| [add_selective_color_adjustment_layer()](#add_selective_color_adjustment_layer__16) | يضيف طبقة تعديل اللون الانتقائي. |
| [add_shape_layer()](#add_shape_layer__17) | أضف طبقة شكل فارغة.<br/>            بدون مسارات. يجب إضافتها إلى طبقة الشكل قبل الحفظ. |
| [add_text_layer(text, rect)](#add_text_layer_text_rect_18) | يضيف طبقة نص جديدة. |
| [add_threshold_adjustment_layer()](#add_threshold_adjustment_layer__19) | يضيف طبقة تعديل العتبة. |
| [add_vibrance_adjustment_layer()](#add_vibrance_adjustment_layer__20) | يضيف طبقة تعديل الحيوية. |
| [adjust_brightness(brightness)](#adjust_brightness_brightness_21) | ضبط السطوع للصورة. |
| [adjust_contrast(contrast)](#adjust_contrast_contrast_22) | تباين الصورة |
| [adjust_gamma(gamma)](#adjust_gamma_gamma_23) | تصحيح جاما للصورة. |
| [adjust_gamma(gamma_red, gamma_green, gamma_blue)](#adjust_gamma_gamma_red_gamma_green_gamma_blue_24) | تصحيح جاما للصورة. |
| [binarize_bradley(brightness_difference)](#binarize_bradley_brightness_difference_25) | تحويل الصورة إلى ثنائية باستخدام خوارزمية العتبة التكيفية لبرايدلي باستخدام عتبة الصورة المتكاملة |
| [binarize_bradley(brightness_difference, window_size)](#binarize_bradley_brightness_difference_window_size_26) | تحويل الصورة إلى ثنائية باستخدام خوارزمية العتبة التكيفية لبرايدلي باستخدام عتبة الصورة المتكاملة |
| [binarize_fixed(threshold)](#binarize_fixed_threshold_27) | تحويل الصورة إلى ثنائية بعتبة محددة مسبقًا |
| binarize_otsu() | تحويل الصورة إلى ثنائية باستخدام عتبة أوتو |
| cache_data() | يقوم بتخزين البيانات مؤقتًا ويضمن عدم تحميل بيانات إضافية من [DataStreamSupporter.data_stream_container](/psd/python-net/aspose.psd/datastreamsupporter/). |
| [can_load(file_path)](#can_load_file_path_28) | يحدد ما إذا كان يمكن تحميل الصورة من مسار الملف المحدد. |
| [can_load(file_path, load_options)](#can_load_file_path_load_options_29) | يحدد ما إذا كان يمكن تحميل الصورة من مسار الملف المحدد واختياريًا باستخدام خيارات الفتح المحددة. |
| [can_load(stream)](#can_load_stream_30) | يحدد ما إذا كان يمكن تحميل الصورة من الدفق المحدد. |
| [can_load(stream, load_options)](#can_load_stream_load_options_31) | يحدد ما إذا كان يمكن تحميل الصورة من الدفق المحدد واختياريًا باستخدام <paramref name=\"loadOptions\" /> المحدد. |
| [can_save(options)](#can_save_options_32) | يحدد ما إذا كان يمكن حفظ الصورة إلى تنسيق الملف المحدد الممثل بخيارات الحفظ الممررة. |
| [convert(new_options)](#convert_new_options_33) | يحوّل تنسيق هذه الصورة إلى التنسيق المحدد في الخيارات. |
| [create(image_options, width, height)](#create_image_options_width_height_34) | ينشئ صورة جديدة باستخدام خيارات الإنشاء المحددة. |
| crop(left_shift, right_shift, top_shift, bottom_shift) |  |
| [crop(rectangle)](#crop_rectangle_35) | قص الصورة. |
| [dither(dithering_method, bits_count)](#dither_dithering_method_bits_count_36) | ينفذ تمويه على الصورة الحالية. |
| [dither(dithering_method, bits_count, custom_palette)](#dither_dithering_method_bits_count_custom_palette_37) | ينفذ تمويه على الصورة الحالية. |
| [filter(rectangle, options)](#filter_rectangle_options_38) | يفلتر المستطيل المحدد. |
| flatten_image() | يضغط جميع الطبقات. |
| [get_argb_32_pixel(x, y)](#get_argb_32_pixel_x_y_39) | يحصل على بكسل ARGB 32-بت للصورة. |
| [get_default_argb_32_pixels(rectangle)](#get_default_argb_32_pixels_rectangle_40) | يحصل على مصفوفة بكسلات ARGB 32-بت الافتراضية. |
| [get_default_options(args)](#get_default_options_args_41) | يحصل على الخيارات الافتراضية. |
| [get_default_pixels(rectangle, partial_pixel_loader)](#get_default_pixels_rectangle_partial_pixel_loader_42) | يحصل على مصفوفة البكسلات الافتراضية باستخدام محمل البكسل الجزئي. |
| [get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings)](#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_43) | يحصل على مصفوفة البيانات الخام الافتراضية باستخدام محمل البكسل الجزئي. |
| [get_default_raw_data(rectangle, raw_data_settings)](#get_default_raw_data_rectangle_raw_data_settings_44) | يحصل على مصفوفة البيانات الخام الافتراضية. |
| [get_file_format(file_path)](#get_file_format_file_path_45) | يحصل على تنسيق الملف. |
| [get_file_format(stream)](#get_file_format_stream_46) | يحصل على تنسيق الملف. |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_47) | يحصل على المستطيل الذي يتناسب مع الصورة الحالية. |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_48) | يحصل على المستطيل الذي يتناسب مع الصورة الحالية. |
| [get_modify_date(use_default)](#get_modify_date_use_default_49) | يحصل على التاريخ والوقت الذي تم فيه تعديل صورة المورد آخر مرة. |
| [get_original_options()](#get_original_options__50) | يحصل على الخيارات بناءً على إعدادات الملف الأصلي.<br/>            قد يكون هذا مفيدًا للحفاظ على عمق البت وغيرها من معلمات الصورة الأصلية دون تغيير.<br/>            على سبيل المثال، إذا قمنا بتحميل صورة PNG بالأبيض والأسود بعمق 1 بت لكل بكسل ثم حفظناها باستخدام<br/>            [DataStreamSupporter.save(file_path)](/psd/python-net/aspose.psd/datastreamsupporter/) الطريقة، سيتم إنتاج صورة PNG ناتجة بعمق 8 بت لكل بكسل.<br/>            لتجنب ذلك وحفظ صورة PNG بعمق 1 بت لكل بكسل، استخدم هذه الطريقة للحصول على خيارات الحفظ المقابلة ومررها<br/>            إلى [Image.save(file_path, options)](/psd/python-net/aspose.psd/image/) الطريقة كمعامل ثانٍ. |
| [get_pixel(x, y)](#get_pixel_x_y_51) | يحصل على بكسل الصورة.<br/>            تحذير أداء: تجنب استخدام هذه الطريقة للتكرار على جميع بكسلات الصورة لأنها قد تؤدي إلى مشاكل أداء كبيرة.<br/>            للحصول على معالجة بكسلات أكثر كفاءة، استخدم طريقة `LoadArgb32Pixels` لاسترجاع مصفوفة البكسلات بالكامل في آن واحد. |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_52) | يحصل على ارتفاع نسبي. |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_53) | يحصل على عرض نسبي. |
| [get_skew_angle()](#get_skew_angle__54) |    |
| grayscale() | تحويل الصورة إلى تمثيلها بتدرج الرمادي |
| [load(file_path)](#load_file_path_55) | يقوم بتحميل صورة جديدة من الملف المحدد. |
| [load(file_path, load_options)](#load_file_path_load_options_56) | يقوم بتحميل صورة جديدة من الملف المحدد. |
| [load(stream)](#load_stream_57) | يقوم بتحميل صورة جديدة من الدفق المحدد. |
| [load(stream, load_options)](#load_stream_load_options_58) | يقوم بتحميل صورة جديدة من الدفق المحدد. |
| [load_argb_32_pixels(rectangle)](#load_argb_32_pixels_rectangle_59) | يقوم بتحميل بكسلات ARGB 32-بت. |
| [load_argb_64_pixels(rectangle)](#load_argb_64_pixels_rectangle_60) | يقوم بتحميل بكسلات ARGB 64-بت. |
| [load_cmyk_32_pixels(rectangle)](#load_cmyk_32_pixels_rectangle_61) | يقوم بتحميل بكسلات بتنسيق CMYK. |
| [load_cmyk_pixels(rectangle)](#load_cmyk_pixels_rectangle_62) | يقوم بتحميل بكسلات بتنسيق CMYK.<br/>            هذه الطريقة مهجورة. يرجى استخدام الطريقة الأكثر فاعلية [RasterImage.load_cmyk_32_pixels(rectangle)](/psd/python-net/aspose.psd/rasterimage/). |
| [load_partial_argb_32_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_63) | يحمّل بكسلات ARGB 32‑بت جزئياً (حسب الكتل). |
| [load_partial_pixels(desired_rectangle, pixel_loader)](#load_partial_pixels_desired_rectangle_pixel_loader_64) | يقوم بتحميل البكسلات جزئيًا على شكل حزم. |
| [load_pixels(rectangle)](#load_pixels_rectangle_65) | يقوم بتحميل البكسلات. |
| [load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_66) | يحمّل البيانات الخام. |
| [load_raw_data(rectangle, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_raw_data_settings_raw_data_loader_67) | يحمّل البيانات الخام. |
| [merge_layers(bottom_layer, top_layer)](#merge_layers_bottom_layer_top_layer_68) | يدمج الطبقات. |
| normalize_angle() |  |
| normalize_angle(resize_proportionally, background_color) |  |
| [read_argb_32_scan_line(scan_line_index)](#read_argb_32_scan_line_scan_line_index_69) | يقرأ كامل سطر المسح وفقًا لمؤشر سطر المسح المحدد. |
| [read_scan_line(scan_line_index)](#read_scan_line_scan_line_index_70) | يقرأ كامل سطر المسح وفقًا لمؤشر سطر المسح المحدد. |
| [replace_color(old_color, old_color_diff, new_color)](#replace_color_old_color_old_color_diff_new_color_71) | يستبدل لونًا بآخر مع فرق مسموح به ويحافظ على قيمة ألفا الأصلية للحفاظ على حواف ناعمة. |
| [replace_color(old_color_argb, old_color_diff, new_color_argb)](#replace_color_old_color_argb_old_color_diff_new_color_argb_72) | يستبدل لونًا بآخر مع فرق مسموح به ويحافظ على قيمة ألفا الأصلية للحفاظ على حواف ناعمة. |
| [replace_non_transparent_colors(new_color)](#replace_non_transparent_colors_new_color_73) | يستبدل جميع الألوان غير الشفافة بلون جديد ويحافظ على قيمة ألفا الأصلية للحفاظ على حواف ناعمة.<br/>            ملاحظة: إذا استخدمتها على صور بدون شفافية، سيتم استبدال جميع الألوان بلون واحد. |
| [replace_non_transparent_colors(new_color_argb)](#replace_non_transparent_colors_new_color_argb_74) | يستبدل جميع الألوان غير الشفافة بلون جديد ويحافظ على قيمة ألفا الأصلية للحفاظ على حواف ناعمة.<br/>            ملاحظة: إذا استخدمتها على صور بدون شفافية، سيتم استبدال جميع الألوان بلون واحد. |
| [resize(new_width, new_height)](#resize_new_width_new_height_75) | يعيد تحجيم الصورة. يتم استخدام [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) الافتراضي. |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_76) | يعيد تحجيم الصورة. |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_77) | يعيد تحجيم الصورة. |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_78) | يعيد تحجيم الارتفاع بنسبية. |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_79) | يعيد تحجيم الارتفاع بنسبية. |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_80) | يعيد تحجيم الارتفاع بنسبية. |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_81) | يعيد تحجيم العرض بنسبية. يتم استخدام [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) الافتراضي. |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_82) | يعيد تحجيم العرض بنسبية. |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_83) | يعيد تحجيم العرض بنسبية. |
| [rotate(angle)](#rotate_angle_84) | يدور الصورة حول المركز. |
| [rotate(angle, resize_proportionally, background_color)](#rotate_angle_resize_proportionally_background_color_85) | يدور الصورة حول المركز. |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_86) | يدور، يقلب، أو يدور ويقلب الصورة. |
| save() | يحفظ بيانات الصورة إلى الدفق الأساسي. |
| [save(file_path)](#save_file_path_87) | يحفظ بيانات الكائن إلى موقع الملف المحدد. |
| [save(file_path, options)](#save_file_path_options_88) | يحفظ بيانات الكائن إلى موقع الملف المحدد بالتنسيق المحدد للملف وفقًا لخيارات الحفظ. |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_89) | يحفظ بيانات الكائن إلى موقع الملف المحدد بالتنسيق المحدد للملف وفقًا لخيارات الحفظ. |
| [save(file_path, over_write)](#save_file_path_over_write_90) | يحفظ بيانات الكائن إلى موقع الملف المحدد. |
| [save(stream)](#save_stream_91) | يحفظ بيانات الكائن إلى الدفق المحدد. |
| [save(stream, options_base)](#save_stream_options_base_92) | يحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق المحدد للملف وفقًا لخيارات الحفظ. |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_93) | يحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق المحدد للملف وفقًا لخيارات الحفظ. |
| [save_argb_32_pixels(rectangle, pixels)](#save_argb_32_pixels_rectangle_pixels_94) | يحفظ بكسلات ARGB 32-بت. |
| save_cmyk_32_pixels(rectangle, pixels) |  |
| save_cmyk_pixels(rectangle, pixels) |  |
| [save_pixels(rectangle, pixels)](#save_pixels_rectangle_pixels_95) | يحفظ البكسلات (طريقة خاصة بالتنسيق). |
| [save_raw_data(data, data_offset, rectangle, raw_data_settings)](#save_raw_data_data_data_offset_rectangle_raw_data_settings_96) | يحفظ البيانات الخام. |
| [set_argb_32_pixel(x, y, argb_32_color)](#set_argb_32_pixel_x_y_argb_32_color_97) | يضبط بكسل ARGB 32-بت للصورة في الموضع المحدد. |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_98) | يضبط لوحة ألوان الصورة. |
| [set_pixel(x, y, color)](#set_pixel_x_y_color_99) | يضبط بكسل الصورة في الموضع المحدد. |
| [set_resolution(dpi_x, dpi_y)](#set_resolution_dpi_x_dpi_y_100) | يضبط الدقة لهذا [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/). |
| [to_bitmap()](#to_bitmap__101) |    |
| [write_argb_32_scan_line(scan_line_index, argb_32_pixels)](#write_argb_32_scan_line_scan_line_index_argb_32_pixels_102) | يكتب السطر الكامل للمسح إلى فهرس سطر المسح المحدد. |
| [write_scan_line(scan_line_index, pixels)](#write_scan_line_scan_line_index_pixels_103) | يكتب السطر الكامل للمسح إلى فهرس سطر المسح المحدد. |


### Constructor: PsdImage(path) {#PsdImage_path_1}


```
 PsdImage(path) 
```

يُهيئ مثيلاً جديدًا من فئة [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) من مسار محدد لصورة نقطية (ليس صورة psd في المسار). يُستخدم لتهيئة صورة psd بالمعلمات الافتراضية - وضع اللون - rgb، 4 قنوات، 8 بت لكل قناة، الضغط - Raw.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| المسار | string | المسار لتحميل بيانات البكسل واللوحة منه والتهيئة به. |

### Constructor: PsdImage(path, color_mode, channel_bit_depth, channels, psd_version, compression) {#PsdImage_path_color_mode_channel_bit_depth_channels_psd_version_compression_2}


```
 PsdImage(path, color_mode, channel_bit_depth, channels, psd_version, compression) 
```

يُهيئ مثيلاً جديدًا من فئة [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) من مسار محدد لصورة نقطية (ليس صورة psd في المسار) مع معلمات البنية.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| المسار | string | المسار لتحميل بيانات البكسل واللوحة منه والتهيئة به. |
| color_mode | [ColorModes](/psd/python-net/aspose.psd.fileformats.psd/colormodes) | وضع اللون. |
| channel_bit_depth | short | عمق البت لملف PSD لكل قناة. |
| قنوات | short | عدد قنوات PSD. |
| psd_version | int | إصدار PSD. |
| compression | [CompressionMethod](/psd/python-net/aspose.psd.fileformats.psd/compressionmethod) | ضغط الاستخدام. |

### Constructor: PsdImage(raster_image) {#PsdImage_raster_image_3}


```
 PsdImage(raster_image) 
```

يُهيئ مثيلاً جديدًا من فئة [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) من صورة نقطية موجودة (ليس صورة psd) بوضع اللون RGB مع 4 قنوات 8 بت/قناة دون ضغط.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| raster_image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | الصورة التي سيتم تحميل بيانات البكسل واللوحة منها والتهيئة بها. |

### Constructor: PsdImage(raster_image, color_mode, channel_bit_depth, channels, psd_version, compression) {#PsdImage_raster_image_color_mode_channel_bit_depth_channels_psd_version_compression_4}


```
 PsdImage(raster_image, color_mode, channel_bit_depth, channels, psd_version, compression) 
```

يُهيئ مثيلاً جديدًا من فئة [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) من صورة نقطية موجودة (ليس صورة psd) مع معلمات البنية.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| raster_image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | الصورة التي سيتم تحميل بيانات البكسل واللوحة منها والتهيئة بها. |
| color_mode | [ColorModes](/psd/python-net/aspose.psd.fileformats.psd/colormodes) | وضع اللون. |
| channel_bit_depth | short | عمق البت لملف PSD لكل قناة. |
| قنوات | short | عدد قنوات PSD. |
| psd_version | int | إصدار PSD. |
| compression | [CompressionMethod](/psd/python-net/aspose.psd.fileformats.psd/compressionmethod) | ضغط الاستخدام. |

### Constructor: PsdImage(stream) {#PsdImage_stream_5}


```
 PsdImage(stream) 
```

يُهيئ مثيلاً جديدًا من فئة [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) من مسار محدد لصورة نقطية (ليس صورة psd في الدفق). يُستخدم لتهيئة صورة psd بالمعلمات الافتراضية - وضع اللون - rgb، 4 قنوات، 8 بت لكل قناة، الضغط - Raw.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| تدفق | _io.BufferedRandom | المجرى الذي سيتم تحميل بيانات البكسل واللوحة منه والتهيئة به. |

### Constructor: PsdImage(stream, color_mode, channel_bit_depth, channels, psd_version, compression) {#PsdImage_stream_color_mode_channel_bit_depth_channels_psd_version_compression_6}


```
 PsdImage(stream, color_mode, channel_bit_depth, channels, psd_version, compression) 
```

يُهيئ مثيلاً جديدًا من فئة [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) من مسار محدد لصورة نقطية (ليس صورة psd في الدفق) مع معلمات البنية.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| تدفق | _io.BufferedRandom | المجرى الذي سيتم تحميل بيانات البكسل واللوحة منه والتهيئة به. |
| color_mode | [ColorModes](/psd/python-net/aspose.psd.fileformats.psd/colormodes) | وضع اللون. |
| channel_bit_depth | short | عمق البت لملف PSD لكل قناة. |
| قنوات | short | عدد قنوات PSD. |
| psd_version | int | إصدار PSD. |
| compression | [CompressionMethod](/psd/python-net/aspose.psd.fileformats.psd/compressionmethod) | ضغط الاستخدام. |

### Constructor: PsdImage(width, height) {#PsdImage_width_height_7}


```
 PsdImage(width, height) 
```

يُهيئ مثيلاً جديدًا من فئة [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) بالعرض والارتفاع المحددين. يُستخدم لتهيئة صورة psd فارغة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| width | int | عرض الصورة. |
| الارتفاع | int | ارتفاع الصورة. |

### Constructor: PsdImage(width, height, color_palette, color_mode, channel_bit_depth, channels, psd_version, compression) {#PsdImage_width_height_color_palette_color_mode_channel_bit_depth_channels_psd_version_compression_8}


```
 PsdImage(width, height, color_palette, color_mode, channel_bit_depth, channels, psd_version, compression) 
```

يُهيئ مثيلاً جديدًا من فئة [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) بالعرض والارتفاع، واللوحة، ووضع اللون، وعدد القنوات وطول بت القنوات، ومعلمات وضع الضغط المحددة. يُستخدم لتهيئة صورة psd فارغة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| width | int | عرض الصورة. |
| الارتفاع | int | ارتفاع الصورة. |
| color_palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | لوحة الألوان. |
| color_mode | [ColorModes](/psd/python-net/aspose.psd.fileformats.psd/colormodes) | وضع اللون. |
| channel_bit_depth | short | عمق البت لملف PSD لكل قناة. |
| قنوات | short | عدد قنوات PSD. |
| psd_version | int | إصدار PSD. |
| compression | [CompressionMethod](/psd/python-net/aspose.psd.fileformats.psd/compressionmethod) | ضغط الاستخدام. |

### Method: add_black_white_adjustment_layer() {#add_black_white_adjustment_layer__1}


```
 add_black_white_adjustment_layer() 
```

يضيف طبقة تعديل أبيض وأسود.

**Returns**

| النوع | الوصف |
| :- | :- |
| [BlackWhiteAdjustmentLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/blackwhiteadjustmentlayer/) | طبقة تعديل الأبيض والأسود التي تم إنشاؤها. |


### Method: add_brightness_contrast_adjustment_layer(brightness, contrast) {#add_brightness_contrast_adjustment_layer_brightness_contrast_2}


```
 add_brightness_contrast_adjustment_layer(brightness, contrast) 
```

يضيف طبقة تعديل السطوع/التباين.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| السطوع | int | السطوع. |
| التباين | int | التباين. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [BrightnessContrastLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/brightnesscontrastlayer/) | طبقة السطوع/التباين التي تم إنشاؤها |


### Method: add_channel_mixer_adjustment_layer() {#add_channel_mixer_adjustment_layer__3}


```
 add_channel_mixer_adjustment_layer() 
```

يضيف طبقة تعديل خالط القنوات مع المعلمات الافتراضية

**Returns**

| النوع | الوصف |
| :- | :- |
| [ChannelMixerLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/channelmixerlayer/) | تمت إضافة طبقة خالط القنوات |


### Method: add_color_balance_adjustment_layer() {#add_color_balance_adjustment_layer__4}


```
 add_color_balance_adjustment_layer() 
```

يضيف طبقة تعديل توازن اللون.

**Returns**

| النوع | الوصف |
| :- | :- |
| [ColorBalanceAdjustmentLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer/) | طبقة توازن اللون التي تم إنشاؤها حديثًا. |


### Method: add_curves_adjustment_layer() {#add_curves_adjustment_layer__5}


```
 add_curves_adjustment_layer() 
```

يضيف طبقة تعديل المنحنيات.

**Returns**

| النوع | الوصف |
| :- | :- |
| [CurvesLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/curveslayer/) | تم إنشاء طبقة [CurvesLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/curveslayer/) |


### Method: add_exposure_adjustment_layer(exposure, offset, gamma_correction) {#add_exposure_adjustment_layer_exposure_offset_gamma_correction_6}


```
 add_exposure_adjustment_layer(exposure, offset, gamma_correction) 
```

يضيف طبقة تعديل التعرض.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| التعريض | float | التعرض. |
| offset | float | الإزاحة. |
| تصحيح_الجاما | float | تصحيح غاما. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [ExposureLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/exposurelayer/) | تم إنشاء طبقة تعديل التعرض |


### Method: add_gradient_map_adjustment_layer() {#add_gradient_map_adjustment_layer__7}


```
 add_gradient_map_adjustment_layer() 
```

يضيف طبقة تعديل خريطة التدرج.

**Returns**

| النوع | الوصف |
| :- | :- |
| [GradientMapLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/gradientmaplayer/) | مثيل GradientMap. |


### Method: add_hue_saturation_adjustment_layer() {#add_hue_saturation_adjustment_layer__8}


```
 add_hue_saturation_adjustment_layer() 
```

يضيف طبقة تعديل الصبغة/التشبع.

**Returns**

| النوع | الوصف |
| :- | :- |
| [HueSaturationLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/huesaturationlayer/) | طبقة الصبغة/الإشباع التي تم إنشاؤها حديثًا. |


### Method: add_invert_adjustment_layer() {#add_invert_adjustment_layer__9}


```
 add_invert_adjustment_layer() 
```

يضيف طبقة تعديل عكس.

**Returns**

| النوع | الوصف |
| :- | :- |
| [InvertAdjustmentLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/invertadjustmentlayer/) | طبقة العكس التي تم إنشاؤها |


### Method: add_layer(layer) {#add_layer_layer_10}


```
 add_layer(layer) 
```

يضيف الطبقة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| layer | [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | الطبقة. |

### Method: add_layer_group(group_name, index, start_behaviour) {#add_layer_group_group_name_index_start_behaviour_11}


```
 add_layer_group(group_name, index, start_behaviour) 
```

يضيف مجموعة الطبقة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| group_name | string | اسم المجموعة. |
| index | int | فهرس الطبقة التي سيتم الإدراج بعدها. |
| start_behaviour | bool | إذا تم تعيينه إلى <c>true</c> [start behaviour] فإن المجموعة ستكون في حالة مفتوحة عند بدء التشغيل، وإلا ستكون في حالة مصغرة. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [LayerGroup](/psd/python-net/aspose.psd.fileformats.psd.layers/layergroup/) | فتح طبقة المجموعة |


### Method: add_levels_adjustment_layer() {#add_levels_adjustment_layer__12}


```
 add_levels_adjustment_layer() 
```

يضيف طبقة تعديل المستويات.

**Returns**

| النوع | الوصف |
| :- | :- |
| [LevelsLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/levelslayer/) | طبقة المستويات التي تم إنشاؤها حديثًا |


### Method: add_photo_filter_layer(color) {#add_photo_filter_layer_color_13}


```
 add_photo_filter_layer(color) 
```

يضيف طبقة مرشح الصورة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) | اللون. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [PhotoFilterLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/photofilterlayer/) | تم إنشاء طبقة PhotoFilter |


### Method: add_posterize_adjustment_layer() {#add_posterize_adjustment_layer__14}


```
 add_posterize_adjustment_layer() 
```

يضيف طبقة تعديل التسطير.

**Returns**

| النوع | الوصف |
| :- | :- |
| [PosterizeLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/posterizelayer/) | مثيل PosterizeLayer. |


### Method: add_regular_layer() {#add_regular_layer__15}


```
 add_regular_layer() 
```

يضيف طبقة عادية جديدة.

**Returns**

| النوع | الوصف |
| :- | :- |
| [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | تم إنشاء طبقة عادية. |


### Method: add_selective_color_adjustment_layer() {#add_selective_color_adjustment_layer__16}


```
 add_selective_color_adjustment_layer() 
```

يضيف طبقة تعديل اللون الانتقائي.

**Returns**

| النوع | الوصف |
| :- | :- |
| [SelectiveColorLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/selectivecolorlayer/) | طبقة تعديل اللون الانتقائي التي تم إنشاؤها. |


### Method: add_shape_layer() {#add_shape_layer__17}


```
 add_shape_layer() 
```

أضف طبقة شكل فارغة.<br/>            بدون مسارات. يجب إضافتها إلى طبقة الشكل قبل الحفظ.

**Returns**

| النوع | الوصف |
| :- | :- |
| [ShapeLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/shapelayer/) | مثيل ShapeLayer. |


### Method: add_text_layer(text, rect) {#add_text_layer_text_rect_18}


```
 add_text_layer(text, rect) 
```

يضيف طبقة نص جديدة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| text | string | نص الطبقة. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | مستطيل الطبقة. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [TextLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/textlayer/) | تم إنشاء طبقة نصية. |


### Method: add_threshold_adjustment_layer() {#add_threshold_adjustment_layer__19}


```
 add_threshold_adjustment_layer() 
```

يضيف طبقة تعديل العتبة.

**Returns**

| النوع | الوصف |
| :- | :- |
| [ThresholdLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/thresholdlayer/) | طبقة تعديل العتبة التي تم إنشاؤها. |


### Method: add_vibrance_adjustment_layer() {#add_vibrance_adjustment_layer__20}


```
 add_vibrance_adjustment_layer() 
```

يضيف طبقة تعديل الحيوية.

**Returns**

| النوع | الوصف |
| :- | :- |
| [VibranceLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/vibrancelayer/) | طبقة إشباع اللون التي تم إنشاؤها حديثًا. |


### Method: adjust_brightness(brightness) {#adjust_brightness_brightness_21}


```
 adjust_brightness(brightness) 
```

ضبط السطوع للصورة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| السطوع | int | قيمة السطوع. |

### Method: adjust_contrast(contrast) {#adjust_contrast_contrast_22}


```
 adjust_contrast(contrast) 
```

تباين الصورة

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| التباين | float | قيمة التباين (في النطاق [-100; 100]) |

### Method: adjust_gamma(gamma) {#adjust_gamma_gamma_23}


```
 adjust_gamma(gamma) 
```

تصحيح جاما للصورة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| جاما | float | معامل جاما لقنوات الأحمر والأخضر والأزرق |

### Method: adjust_gamma(gamma_red, gamma_green, gamma_blue) {#adjust_gamma_gamma_red_gamma_green_gamma_blue_24}


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

### Method: binarize_bradley(brightness_difference) {#binarize_bradley_brightness_difference_25}


```
 binarize_bradley(brightness_difference) 
```

تحويل الصورة إلى ثنائية باستخدام خوارزمية العتبة التكيفية لبرايدلي باستخدام عتبة الصورة المتكاملة

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| brightness_difference | double | فرق السطوع بين البكسل ومتوسط نافذة بحجم s × s من البكسلات المتمركزة حول هذا البكسل. |

### Method: binarize_bradley(brightness_difference, window_size) {#binarize_bradley_brightness_difference_window_size_26}


```
 binarize_bradley(brightness_difference, window_size) 
```

تحويل الصورة إلى ثنائية باستخدام خوارزمية العتبة التكيفية لبرايدلي باستخدام عتبة الصورة المتكاملة

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| brightness_difference | double | فرق السطوع بين البكسل ومتوسط نافذة بحجم s × s من البكسلات المتمركزة حول هذا البكسل. |
| window_size | int | حجم نافذة s × s من البكسلات المتمركزة حول هذا البكسل |

### Method: binarize_fixed(threshold) {#binarize_fixed_threshold_27}


```
 binarize_fixed(threshold) 
```

تحويل الصورة إلى ثنائية بعتبة محددة مسبقًا

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| العتبة | byte | قيمة العتبة. إذا كانت القيمة الرمادية المقابلة للبكسل أكبر من العتبة، سيتم تعيين القيمة 255 له، وإلا 0. |

### Method: can_load(file_path)  [static] {#can_load_file_path_28}


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


### Method: can_load(file_path, load_options)  [static] {#can_load_file_path_load_options_29}


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


### Method: can_load(stream)  [static] {#can_load_stream_30}


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


### Method: can_load(stream, load_options)  [static] {#can_load_stream_load_options_31}


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


### Method: can_save(options) {#can_save_options_32}


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


### Method: convert(new_options) {#convert_new_options_33}


```
 convert(new_options) 
```

يحوّل تنسيق هذه الصورة إلى التنسيق المحدد في الخيارات.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| new_options | [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/) | الخيارات الجديدة. |

### Method: create(image_options, width, height)  [static] {#create_image_options_width_height_34}


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


### Method: crop(rectangle) {#crop_rectangle_35}


```
 crop(rectangle) 
```

قص الصورة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | المستطيل. |

### Method: dither(dithering_method, bits_count) {#dither_dithering_method_bits_count_36}


```
 dither(dithering_method, bits_count) 
```

ينفذ تمويه على الصورة الحالية.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/psd/python-net/aspose.psd/ditheringmethod) | طريقة التمويه. |
| bits_count | int | العدد النهائي للبتات للتمويه. |

### Method: dither(dithering_method, bits_count, custom_palette) {#dither_dithering_method_bits_count_custom_palette_37}


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

### Method: filter(rectangle, options) {#filter_rectangle_options_38}


```
 filter(rectangle, options) 
```

يفلتر المستطيل المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | المستطيل. |
| options | [FilterOptionsBase](/psd/python-net/aspose.psd.imagefilters.filteroptions/filteroptionsbase/) | الخيارات. |

### Method: get_argb_32_pixel(x, y) {#get_argb_32_pixel_x_y_39}


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


### Method: get_default_argb_32_pixels(rectangle) {#get_default_argb_32_pixels_rectangle_40}


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


### Method: get_default_options(args) {#get_default_options_args_41}


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


### Method: get_default_pixels(rectangle, partial_pixel_loader) {#get_default_pixels_rectangle_partial_pixel_loader_42}


```
 get_default_pixels(rectangle, partial_pixel_loader) 
```

يحصل على مصفوفة البكسلات الافتراضية باستخدام محمل البكسل الجزئي.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | المستطيل للحصول على البكسلات. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/psd/python-net/aspose.psd/ipartialargb32pixelloader) | محمل البكسلات الجزئي. |

### Method: get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) {#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_43}


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

### Method: get_default_raw_data(rectangle, raw_data_settings) {#get_default_raw_data_rectangle_raw_data_settings_44}


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


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_45}


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


### Method: get_file_format(stream)  [static] {#get_file_format_stream_46}


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


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_47}


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


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_48}


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


### Method: get_modify_date(use_default) {#get_modify_date_use_default_49}


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


### Method: get_original_options() {#get_original_options__50}


```
 get_original_options() 
```

يحصل على الخيارات بناءً على إعدادات الملف الأصلي.<br/>            قد يكون هذا مفيدًا للحفاظ على عمق البت وغيرها من معلمات الصورة الأصلية دون تغيير.<br/>            على سبيل المثال، إذا قمنا بتحميل صورة PNG بالأبيض والأسود بعمق 1 بت لكل بكسل ثم حفظناها باستخدام<br/>            [DataStreamSupporter.save(file_path)](/psd/python-net/aspose.psd/datastreamsupporter/) الطريقة، سيتم إنتاج صورة PNG ناتجة بعمق 8 بت لكل بكسل.<br/>            لتجنب ذلك وحفظ صورة PNG بعمق 1 بت لكل بكسل، استخدم هذه الطريقة للحصول على خيارات الحفظ المقابلة ومررها<br/>            إلى [Image.save(file_path, options)](/psd/python-net/aspose.psd/image/) الطريقة كمعامل ثانٍ.

**Returns**

| النوع | الوصف |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | الخيارات بناءً على إعدادات الملف الأصلي. |


### Method: get_pixel(x, y) {#get_pixel_x_y_51}


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


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_52}


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


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_53}


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


### Method: get_skew_angle() {#get_skew_angle__54}


```
 get_skew_angle() 
```

  

**Returns**

| النوع | الوصف |
| :- | :- |
| float |  |


### Method: load(file_path)  [static] {#load_file_path_55}


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


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_56}


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


### Method: load(stream)  [static] {#load_stream_57}


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


### Method: load(stream, load_options)  [static] {#load_stream_load_options_58}


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


### Method: load_argb_32_pixels(rectangle) {#load_argb_32_pixels_rectangle_59}


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


### Method: load_argb_64_pixels(rectangle) {#load_argb_64_pixels_rectangle_60}


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


### Method: load_cmyk_32_pixels(rectangle) {#load_cmyk_32_pixels_rectangle_61}


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


### Method: load_cmyk_pixels(rectangle) {#load_cmyk_pixels_rectangle_62}


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


### Method: load_partial_argb_32_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_63}


```
 load_partial_argb_32_pixels(rectangle, partial_pixel_loader) 
```

يحمّل بكسلات ARGB 32‑بت جزئياً (حسب الكتل).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | المستطيل لتحميل البكسلات منه. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/psd/python-net/aspose.psd/ipartialargb32pixelloader) | محمل البكسلات الجزئي. |

### Method: load_partial_pixels(desired_rectangle, pixel_loader) {#load_partial_pixels_desired_rectangle_pixel_loader_64}


```
 load_partial_pixels(desired_rectangle, pixel_loader) 
```

يقوم بتحميل البكسلات جزئيًا على شكل حزم.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| desired_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | المستطيل المطلوب. |
| pixel_loader | [IPartialPixelLoader](/psd/python-net/aspose.psd/ipartialpixelloader) | محمل البكسلات. |

### Method: load_pixels(rectangle) {#load_pixels_rectangle_65}


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


### Method: load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_66}


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

### Method: load_raw_data(rectangle, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_raw_data_settings_raw_data_loader_67}


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

### Method: merge_layers(bottom_layer, top_layer) {#merge_layers_bottom_layer_top_layer_68}


```
 merge_layers(bottom_layer, top_layer) 
```

يدمج الطبقات.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| bottom_layer | [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | الطبقة السفلية. |
| top_layer | [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | الطبقة العلوية. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | الطبقة السفلية بعد الدمج |


### Method: read_argb_32_scan_line(scan_line_index) {#read_argb_32_scan_line_scan_line_index_69}


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


### Method: read_scan_line(scan_line_index) {#read_scan_line_scan_line_index_70}


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


### Method: replace_color(old_color, old_color_diff, new_color) {#replace_color_old_color_old_color_diff_new_color_71}


```
 replace_color(old_color, old_color_diff, new_color) 
```

يستبدل لونًا بآخر مع فرق مسموح به ويحافظ على قيمة ألفا الأصلية للحفاظ على حواف ناعمة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| old_color | [Color](/psd/python-net/aspose.psd/color) |  |
| old_color_diff | byte | الفرق المسموح به في اللون القديم لتمكين توسيع نغمة اللون المستبدل. |
| new_color | [Color](/psd/python-net/aspose.psd/color) |  |

### Method: replace_color(old_color_argb, old_color_diff, new_color_argb) {#replace_color_old_color_argb_old_color_diff_new_color_argb_72}


```
 replace_color(old_color_argb, old_color_diff, new_color_argb) 
```

يستبدل لونًا بآخر مع فرق مسموح به ويحافظ على قيمة ألفا الأصلية للحفاظ على حواف ناعمة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| old_color_argb | int | قيمة ARGB للون القديم التي سيتم استبدالها. |
| old_color_diff | byte | الفرق المسموح به في اللون القديم لتمكين توسيع نغمة اللون المستبدل. |
| new_color_argb | int | قيمة ARGB للون الجديد لاستبدال اللون القديم بها. |

### Method: replace_non_transparent_colors(new_color) {#replace_non_transparent_colors_new_color_73}


```
 replace_non_transparent_colors(new_color) 
```

يستبدل جميع الألوان غير الشفافة بلون جديد ويحافظ على قيمة ألفا الأصلية للحفاظ على حواف ناعمة.<br/>            ملاحظة: إذا استخدمتها على صور بدون شفافية، سيتم استبدال جميع الألوان بلون واحد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| new_color | [Color](/psd/python-net/aspose.psd/color) |  |

### Method: replace_non_transparent_colors(new_color_argb) {#replace_non_transparent_colors_new_color_argb_74}


```
 replace_non_transparent_colors(new_color_argb) 
```

يستبدل جميع الألوان غير الشفافة بلون جديد ويحافظ على قيمة ألفا الأصلية للحفاظ على حواف ناعمة.<br/>            ملاحظة: إذا استخدمتها على صور بدون شفافية، سيتم استبدال جميع الألوان بلون واحد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| new_color_argb | int | قيمة ARGB للون الجديد لاستبدال الألوان غير الشفافة بها. |

### Method: resize(new_width, new_height) {#resize_new_width_new_height_75}


```
 resize(new_width, new_height) 
```

يعيد تحجيم الصورة. يتم استخدام [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) الافتراضي.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| new_width | int | العرض الجديد. |
| new_height | int | الارتفاع الجديد. |

### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_76}


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

### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_77}


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

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_78}


```
 resize_height_proportionally(new_height) 
```

يعيد تحجيم الارتفاع بنسبية.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| new_height | int | الارتفاع الجديد. |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_79}


```
 resize_height_proportionally(new_height, resize_type) 
```

يعيد تحجيم الارتفاع بنسبية.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| new_height | int | الارتفاع الجديد. |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | نوع التحجيم. |

### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_80}


```
 resize_height_proportionally(new_height, settings) 
```

يعيد تحجيم الارتفاع بنسبية.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| new_height | int | الارتفاع الجديد. |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | إعدادات تحجيم الصورة. |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_81}


```
 resize_width_proportionally(new_width) 
```

يعيد تحجيم العرض بنسبية. يتم استخدام [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) الافتراضي.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| new_width | int | العرض الجديد. |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_82}


```
 resize_width_proportionally(new_width, resize_type) 
```

يعيد تحجيم العرض بنسبية.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| new_width | int | العرض الجديد. |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | نوع التحجيم. |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_83}


```
 resize_width_proportionally(new_width, settings) 
```

يعيد تحجيم العرض بنسبية.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| new_width | int | العرض الجديد. |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | إعدادات تحجيم الصورة. |

### Method: rotate(angle) {#rotate_angle_84}


```
 rotate(angle) 
```

يدور الصورة حول المركز.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| الزاوية | float | زاوية الدوران بالدرجات. القيم الموجبة ستدور باتجاه عقارب الساعة. |

### Method: rotate(angle, resize_proportionally, background_color) {#rotate_angle_resize_proportionally_background_color_85}


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

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_86}


```
 rotate_flip(rotate_flip_type) 
```

يدور، يقلب، أو يدور ويقلب الصورة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/psd/python-net/aspose.psd/rotatefliptype) | نوع تدوير القلب. |

### Method: save(file_path) {#save_file_path_87}


```
 save(file_path) 
```

يحفظ بيانات الكائن إلى موقع الملف المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| file_path | string | مسار الملف لحفظ بيانات الكائن إليه. |

### Method: save(file_path, options) {#save_file_path_options_88}


```
 save(file_path, options) 
```

يحفظ بيانات الكائن إلى موقع الملف المحدد بالتنسيق المحدد للملف وفقًا لخيارات الحفظ.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| file_path | string | مسار الملف. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | الخيارات. |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_89}


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

### Method: save(file_path, over_write) {#save_file_path_over_write_90}


```
 save(file_path, over_write) 
```

يحفظ بيانات الكائن إلى موقع الملف المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| file_path | string | مسار الملف لحفظ بيانات الكائن إليه. |
| over_write | bool | إذا تم تعيينه إلى <c>true</c> سيُستبدل محتوى الملف، وإلا سيحدث الإلحاق. |

### Method: save(stream) {#save_stream_91}


```
 save(stream) 
```

يحفظ بيانات الكائن إلى الدفق المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| تدفق | _io.BufferedRandom | الدفق لحفظ بيانات الكائن إليه. |

### Method: save(stream, options_base) {#save_stream_options_base_92}


```
 save(stream, options_base) 
```

يحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق المحدد للملف وفقًا لخيارات الحفظ.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| تدفق | _io.BufferedRandom | الدفق لحفظ بيانات الصورة إليه. |
| options_base | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | خيارات الحفظ. |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_93}


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

### Method: save_argb_32_pixels(rectangle, pixels) {#save_argb_32_pixels_rectangle_pixels_94}


```
 save_argb_32_pixels(rectangle, pixels) 
```

يحفظ بكسلات ARGB 32-بت.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | المستطيل لحفظ البكسلات فيه. |
| pixels | int | مصفوفة بكسلات ARGB 32‑بت. |

### Method: save_pixels(rectangle, pixels) {#save_pixels_rectangle_pixels_95}


```
 save_pixels(rectangle, pixels) 
```

يحفظ البكسلات (طريقة خاصة بالتنسيق).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | المستطيل لحفظ البكسلات فيه. |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) | مصفوفة بكسلات ARGB 32‑بت. |

### Method: save_raw_data(data, data_offset, rectangle, raw_data_settings) {#save_raw_data_data_data_offset_rectangle_raw_data_settings_96}


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

### Method: set_argb_32_pixel(x, y, argb_32_color) {#set_argb_32_pixel_x_y_argb_32_color_97}


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

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_98}


```
 set_palette(palette, update_colors) 
```

يضبط لوحة ألوان الصورة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | لوحة الألوان لتعيينها. |
| update_colors | bool | إذا تم تعيينه إلى <c>true</c> سيتم تحديث الألوان وفقًا للوحة الألوان الجديدة؛ وإلا ستظل فهارس الألوان دون تغيير. لاحظ أن الفهارس غير المتغيرة قد تتسبب في تعطل الصورة عند التحميل إذا لم يكن لبعض الفهارس إدخالات مطابقة في لوحة الألوان. |

### Method: set_pixel(x, y, color) {#set_pixel_x_y_color_99}


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

### Method: set_resolution(dpi_x, dpi_y) {#set_resolution_dpi_x_dpi_y_100}


```
 set_resolution(dpi_x, dpi_y) 
```

يضبط الدقة لهذا [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| dpi_x | double | الدقة الأفقية، بوحدات النقاط لكل بوصة، لـ [RasterImage](/psd/python-net/aspose.psd/rasterimage/). |
| dpi_y | double | الدقة العمودية، بوحدات النقاط لكل بوصة، لـ [RasterImage](/psd/python-net/aspose.psd/rasterimage/). |

### Method: to_bitmap() {#to_bitmap__101}


```
 to_bitmap() 
```

  

**Returns**

| النوع | الوصف |
| :- | :- |
| aspose.pydrawing.Bitmap |  |


### Method: write_argb_32_scan_line(scan_line_index, argb_32_pixels) {#write_argb_32_scan_line_scan_line_index_argb_32_pixels_102}


```
 write_argb_32_scan_line(scan_line_index, argb_32_pixels) 
```

يكتب السطر الكامل للمسح إلى فهرس سطر المسح المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| scan_line_index | int | فهرس يبدأ من الصفر لسطر المسح. |
| argb_32_pixels | int | مصفوفة ألوان ARGB 32-بت للكتابة. |

### Method: write_scan_line(scan_line_index, pixels) {#write_scan_line_scan_line_index_pixels_103}


```
 write_scan_line(scan_line_index, pixels) 
```

يكتب السطر الكامل للمسح إلى فهرس سطر المسح المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| scan_line_index | int | فهرس يبدأ من الصفر لسطر المسح. |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) | مصفوفة ألوان البكسل للكتابة. |

