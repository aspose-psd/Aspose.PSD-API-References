---
title: "Класс PsdImage"
type: docs
weight: 1760
url: /ru/python-net/aspose.psd.fileformats.psd/psdimage/
---

**Summary:** Defines the PsdImage class that provides the ability to load, edit, save PSD files as well as<br/>            update properties, add watermarks, perform graphics operations or convert one file format to another.<br/>            Aspose.PSD supports import as a layer and export to the following formats:<br/>            Png, Jpeg, Jpeg2000, Gif, Bmp, Tiff, Psd, Psb along with export to Pdf with selectable text

**Module:** [aspose.psd.fileformats.psd](/psd/python-net/aspose.psd.fileformats.psd/)

**Full Name:** aspose.psd.fileformats.psd.PsdImage

**Inheritance:** IObjectWithBounds, IRasterImageArgb32PixelLoader, IRasterImageRawDataLoader, RasterCachedImage

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [PsdImage(path)](#PsdImage_path_1) | Инициализирует новый экземпляр класса [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) из указанного пути к растровому изображению (не psd‑изображению в пути). Используется для инициализации psd‑изображения с параметрами по умолчанию — режим цвета — rgb, 4 канала, 8 бит на канал, сжатие — Raw. |
| [PsdImage(path, color_mode, channel_bit_depth, channels, psd_version, compression)](#PsdImage_path_color_mode_channel_bit_depth_channels_psd_version_compression_2) | Инициализирует новый экземпляр класса [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) из указанного пути к растровому изображению (не psd‑изображению в пути) с параметрами конструктора. |
| [PsdImage(raster_image)](#PsdImage_raster_image_3) | Инициализирует новый экземпляр класса [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) из существующего растрового изображения (не psd‑изображения) с режимом цвета RGB, 4 канала, 8 бит/канал и без сжатия. |
| [PsdImage(raster_image, color_mode, channel_bit_depth, channels, psd_version, compression)](#PsdImage_raster_image_color_mode_channel_bit_depth_channels_psd_version_compression_4) | Инициализирует новый экземпляр класса [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) из существующего растрового изображения (не psd‑изображения) с параметрами конструктора. |
| [PsdImage(stream)](#PsdImage_stream_5) | Инициализирует новый экземпляр класса [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) из указанного пути к растровому изображению (не psd‑изображению в потоке). Используется для инициализации psd‑изображения с параметрами по умолчанию — режим цвета — rgb, 4 канала, 8 бит на канал, сжатие — Raw. |
| [PsdImage(stream, color_mode, channel_bit_depth, channels, psd_version, compression)](#PsdImage_stream_color_mode_channel_bit_depth_channels_psd_version_compression_6) | Инициализирует новый экземпляр класса [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) из указанного пути к растровому изображению (не psd‑изображению в потоке) с параметрами конструктора. |
| [PsdImage(width, height)](#PsdImage_width_height_7) | Инициализирует новый экземпляр класса [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) с указанными шириной и высотой. Используется для инициализации пустого psd‑изображения. |
| [PsdImage(width, height, color_palette, color_mode, channel_bit_depth, channels, psd_version, compression)](#PsdImage_width_height_color_palette_color_mode_channel_bit_depth_channels_psd_version_compression_8) | Инициализирует новый экземпляр класса [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) с указанными шириной, высотой, палитрой, режимом цвета, количеством каналов и разрядностью каналов, а также параметрами указанного режима сжатия. Используется для инициализации пустого psd‑изображения. |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| DEFAULT_VERSION [static] | int | r | Версия PSD по умолчанию. |
| active_layer | [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | r/w | Получает или задает активный слой. |
| auto_adjust_palette | bool | r/w | Получает или задаёт значение, указывающее, следует ли автоматически корректировать палитру. |
| background_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Получает или задаёт значение фонового цвета. |
| bits_per_channel | int | r | Получает количество бит на канал. |
| bits_per_pixel | int | r | Получает количество бит на пиксель изображения. |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | Получает границы объекта. |
| buffer_size_hint | int | r/w | Получает или задаёт подсказку размера буфера, определяющую максимальный допустимый размер для всех внутренних буферов. |
| channels_count | int | r | Получает количество каналов PSD. |
| cmyk_color_profile | [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/) | r/w | Получает или задает профиль цвета CMYK для изображений CMYK PSD. Должен быть в паре с RgbColorProfile для корректного преобразования цвета. |
| color_mode | [ColorModes](/psd/python-net/aspose.psd.fileformats.psd/colormodes) | r/w | Получает или задает режим цвета. |
| compression | [CompressionMethod](/psd/python-net/aspose.psd.fileformats.psd/compressionmethod) | r | Получает метод сжатия. |
| container | [Image](/psd/python-net/aspose.psd/image) | r | Получает контейнер [Image](/psd/python-net/aspose.psd/image/). |
| data_stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | r | Получает поток данных объекта. |
| освобождено | bool | r | Получает значение, указывающее, освобожден ли данный экземпляр. |
| file_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | Получает значение формата файла |
| global_angle | int | r/w | Получает или задает глобальный угол. |
| global_layer_mask_info | [GlobalLayerMaskInfo](/psd/python-net/aspose.psd.fileformats.psd.layers/globallayermaskinfo/) | r | Получает информацию о глобальной маске слоя. |
| global_layer_resources | [LayerResource[]](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/) | r/w | Получает или задает глобальные ресурсы слоя. |
| gray_color_profile | [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/) | r/w | Получает или задает профиль цвета GRAY (монохромный) для изображений Grayscale PSD. |
| has_alpha | bool | r | Получает или задает вертикальное разрешение в пикселях на дюйм для этого [RasterImage](/psd/python-net/aspose.psd/rasterimage/). |
| имеет_цвет_фона | bool | r/w | Получает или задает значение, указывающее, имеет ли изображение фоновой цвет. |
| has_transparency_data | bool | r/w | Получает или задает значение, указывающее, содержит ли первый альфа-канал данные о прозрачности для объединённого результата при указании данных слоёв. |
| имеет_прозрачный_цвет | bool | r/w | Получает значение, указывающее, имеет ли изображение прозрачный цвет. |
| height | int | r | Получает высоту изображения. |
| horizontal_resolution | double | r/w | Получает или задает горизонтальное разрешение в пикселях на дюйм для этого [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/). |
| непрозрачность_изображения | float | r | Получает непрозрачность этого изображения. |
| image_resources | [ResourceBlock[]](/psd/python-net/aspose.psd.fileformats.psd/resourceblock) | r/w | Получает или задает ресурсы изображения PSD. |
| interrupt_monitor | [InterruptMonitor](/psd/python-net/aspose.psd.multithreading/interruptmonitor/) | r/w | Получает или задает монитор прерываний. |
| закешировано | bool | r | Получает значение, указывающее, кэшируются ли данные изображения в данный момент. |
| is_flatten | bool | r | Получает значение, указывающее, является ли изображение PSD сплющенным. |
| сырые_данные_доступны | bool | r | Получает значение, указывающее, поддерживается ли загрузка сырых данных. |
| layers | [Layer[]](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | r/w | Получает или задает слои PSD. |
| linked_layers_manager | [LinkedLayersManager](/psd/python-net/aspose.psd.fileformats.psd.layers/linkedlayersmanager/) | r | Получает менеджер связанных слоёв. |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Получает или задает цветовую палитру. Цветовая палитра не используется, когда пиксели представлены напрямую. |
| предумножить_компоненты | bool | r/w | Получает или задает значение, указывающее, должны ли компоненты изображения быть предварительно умноженными. |
| raw_custom_color_converter | [IColorConverter](/psd/python-net/aspose.psd/icolorconverter) | r/w | Получает или задает пользовательский конвертер цветов |
| raw_data_format | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | Получает формат необработанных данных. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | r | Получает текущие настройки сырых данных. Примечание: при использовании этих настроек данные загружаются без конвертации. |
| индекс_резервного_варианта | int | r/w | Получает или задает запасной индекс, используемый, когда индекс палитры выходит за пределы |
| raw_indexed_color_converter | [IIndexedColorConverter](/psd/python-net/aspose.psd/iindexedcolorconverter) | r/w | Получает или задает индексированный конвертер цветов |
| размер_строки_сырых | int | r | Получает размер необработанной строки в байтах. |
| rgb_color_profile | [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/) | r/w | Получает или задает профиль цвета RGB для изображений CMYK PSD. Должен быть в паре с CmykColorProfile для корректного преобразования цвета. |
| size | [Size](/psd/python-net/aspose.psd/size) | r | Получает размер объекта. |
| smart_object_provider | [SmartObjectProvider](/psd/python-net/aspose.psd.fileformats.psd/smartobjectprovider) | r | Получает поставщика смарт‑объекта. |
| timeline | [Timeline](/psd/python-net/aspose.psd.fileformats.psd.layers.animation/timeline/) | r | Получает [PsdImage.timeline](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) этого [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/). |
| transparent_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Получает прозрачный цвет изображения. |
| update_xmp_data | bool | r/w | Получает или задает значение, указывающее, следует ли обновлять метаданные XMP. |
| use_palette | bool | r | Получает значение, указывающее, используется ли палитра изображения. |
| use_raw_data | bool | r/w | Получает или задает значение, указывающее, следует ли использовать загрузку необработанных данных, когда такая загрузка доступна. |
| version | int | r/w | Получает или задает версию. |
| vertical_resolution | double | r/w | Получает или задает вертикальное разрешение в пикселях на дюйм для этого [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/). |
| width | int | r | Получает ширину изображения. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | Получает или задает XMP‑метаданные. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [add_black_white_adjustment_layer()](#add_black_white_adjustment_layer__1) | Добавляет слой корректировки чёрно‑белого. |
| [add_brightness_contrast_adjustment_layer(brightness, contrast)](#add_brightness_contrast_adjustment_layer_brightness_contrast_2) | Добавляет слой корректировки яркости/контраста. |
| [add_channel_mixer_adjustment_layer()](#add_channel_mixer_adjustment_layer__3) | Добавляет слой корректировки микшера каналов с параметрами по умолчанию |
| [add_color_balance_adjustment_layer()](#add_color_balance_adjustment_layer__4) | Добавляет слой коррекции цветового баланса. |
| [add_curves_adjustment_layer()](#add_curves_adjustment_layer__5) | Добавляет слой коррекции кривых. |
| [add_exposure_adjustment_layer(exposure, offset, gamma_correction)](#add_exposure_adjustment_layer_exposure_offset_gamma_correction_6) | Добавляет слой коррекции экспозиции. |
| [add_gradient_map_adjustment_layer()](#add_gradient_map_adjustment_layer__7) | Добавляет слой коррекции градиентной карты. |
| [add_hue_saturation_adjustment_layer()](#add_hue_saturation_adjustment_layer__8) | Добавляет слой коррекции оттенка/насыщенности. |
| [add_invert_adjustment_layer()](#add_invert_adjustment_layer__9) | Добавляет слой инверсии. |
| [add_layer(layer)](#add_layer_layer_10) | Добавляет слой. |
| [add_layer_group(group_name, index, start_behaviour)](#add_layer_group_group_name_index_start_behaviour_11) | Добавляет группу слоёв. |
| [add_levels_adjustment_layer()](#add_levels_adjustment_layer__12) | Добавляет слой коррекции уровней. |
| [add_photo_filter_layer(color)](#add_photo_filter_layer_color_13) | Добавляет слой фотофильтра. |
| [add_posterize_adjustment_layer()](#add_posterize_adjustment_layer__14) | Добавляет слой коррекции постеризации. |
| [add_regular_layer()](#add_regular_layer__15) | Добавляет новый обычный слой. |
| [add_selective_color_adjustment_layer()](#add_selective_color_adjustment_layer__16) | Добавляет слой коррекции выборочного цвета. |
| [add_shape_layer()](#add_shape_layer__17) | Добавить пустой слой формы.<br/>            Без путей. Их следует добавить в слой формы перед сохранением. |
| [add_text_layer(text, rect)](#add_text_layer_text_rect_18) | Добавляет новый текстовый слой. |
| [add_threshold_adjustment_layer()](#add_threshold_adjustment_layer__19) | Добавляет слой коррекции порога. |
| [add_vibrance_adjustment_layer()](#add_vibrance_adjustment_layer__20) | Добавляет слой коррекции яркости. |
| [adjust_brightness(brightness)](#adjust_brightness_brightness_21) | Регулировка яркости изображения. |
| [adjust_contrast(contrast)](#adjust_contrast_contrast_22) | Контрастирование изображения |
| [adjust_gamma(gamma)](#adjust_gamma_gamma_23) | Гамма‑коррекция изображения. |
| [adjust_gamma(gamma_red, gamma_green, gamma_blue)](#adjust_gamma_gamma_red_gamma_green_gamma_blue_24) | Гамма‑коррекция изображения. |
| [binarize_bradley(brightness_difference)](#binarize_bradley_brightness_difference_25) | Бинаризация изображения с использованием адаптивного порогового алгоритма Брэдли, основанного на интегральном изображении |
| [binarize_bradley(brightness_difference, window_size)](#binarize_bradley_brightness_difference_window_size_26) | Бинаризация изображения с использованием адаптивного порогового алгоритма Брэдли, основанного на интегральном изображении |
| [binarize_fixed(threshold)](#binarize_fixed_threshold_27) | Бинаризация изображения с предопределённым порогом. |
| binarize_otsu() | Бинаризация изображения с порогом Оцу. |
| cache_data() | Кеширует данные и гарантирует, что дополнительная загрузка данных из базового [DataStreamSupporter.data_stream_container](/psd/python-net/aspose.psd/datastreamsupporter/) не будет выполнена. |
| [can_load(file_path)](#can_load_file_path_28) | Определяет, может ли изображение быть загружено из указанного пути к файлу. |
| [can_load(file_path, load_options)](#can_load_file_path_load_options_29) | Определяет, может ли изображение быть загружено из указанного пути к файлу и, при необходимости, с использованием указанных параметров открытия. |
| [can_load(stream)](#can_load_stream_30) | Определяет, может ли изображение быть загружено из указанного потока. |
| [can_load(stream, load_options)](#can_load_stream_load_options_31) | Определяет, может ли изображение быть загружено из указанного потока и, при необходимости, с использованием указанного <paramref name="loadOptions" />. |
| [can_save(options)](#can_save_options_32) | Определяет, может ли изображение быть сохранено в указанный формат файла, представленный переданными параметрами сохранения. |
| [convert(new_options)](#convert_new_options_33) | Преобразует формат этого изображения в указанный в параметрах. |
| [create(image_options, width, height)](#create_image_options_width_height_34) | Создаёт новое изображение с использованием указанных параметров создания. |
| crop(left_shift, right_shift, top_shift, bottom_shift) |  |
| [crop(rectangle)](#crop_rectangle_35) | Обрезка изображения. |
| [dither(dithering_method, bits_count)](#dither_dithering_method_bits_count_36) | Выполняет дизеринг текущего изображения. |
| [dither(dithering_method, bits_count, custom_palette)](#dither_dithering_method_bits_count_custom_palette_37) | Выполняет дизеринг текущего изображения. |
| [filter(rectangle, options)](#filter_rectangle_options_38) | Фильтрует указанный прямоугольник. |
| flatten_image() | Объединяет все слои. |
| [get_argb_32_pixel(x, y)](#get_argb_32_pixel_x_y_39) | Получает 32‑битный ARGB‑пиксель изображения. |
| [get_default_argb_32_pixels(rectangle)](#get_default_argb_32_pixels_rectangle_40) | Получает массив пикселей по умолчанию в формате 32‑бит ARGB. |
| [get_default_options(args)](#get_default_options_args_41) | Получает параметры по умолчанию. |
| [get_default_pixels(rectangle, partial_pixel_loader)](#get_default_pixels_rectangle_partial_pixel_loader_42) | Получает массив пикселей по умолчанию с использованием частичного загрузчика пикселей. |
| [get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings)](#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_43) | Получает массив необработанных данных по умолчанию с использованием частичного загрузчика пикселей. |
| [get_default_raw_data(rectangle, raw_data_settings)](#get_default_raw_data_rectangle_raw_data_settings_44) | Получает массив необработанных данных по умолчанию. |
| [get_file_format(file_path)](#get_file_format_file_path_45) | Получает формат файла. |
| [get_file_format(stream)](#get_file_format_stream_46) | Получает формат файла. |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_47) | Получает прямоугольник, который вписывается в текущее изображение. |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_48) | Получает прямоугольник, который вписывается в текущее изображение. |
| [get_modify_date(use_default)](#get_modify_date_use_default_49) | Получает дату и время последнего изменения ресурсного изображения. |
| [get_original_options()](#get_original_options__50) | Получает параметры на основе настроек исходного файла.<br/>            Это может быть полезно для сохранения глубины цвета и других параметров исходного изображения без изменений.<br/>            Например, если мы загружаем черно-белое PNG‑изображение с 1 битом на пиксель, а затем сохраняем его с помощью<br/>            метода [DataStreamSupporter.save(file_path)](/psd/python-net/aspose.psd/datastreamsupporter/), будет получено PNG‑изображение с 8 битами на пиксель.<br/>            Чтобы избежать этого и сохранить PNG‑изображение с 1 битом на пиксель, используйте этот метод для получения соответствующих параметров сохранения и передайте их<br/>            методу [Image.save(file_path, options)](/psd/python-net/aspose.psd/image/) в качестве второго параметра. |
| [get_pixel(x, y)](#get_pixel_x_y_51) | Получает пиксель изображения.<br/>            Предупреждение о производительности: избегайте использования этого метода для обхода всех пикселей изображения, так как это может привести к значительным проблемам с производительностью.<br/>            Для более эффективного управления пикселями используйте метод `LoadArgb32Pixels` для одновременного получения всего массива пикселей. |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_52) | Получает пропорциональную высоту. |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_53) | Получает пропорциональную ширину. |
| [get_skew_angle()](#get_skew_angle__54) |    |
| grayscale() | Преобразование изображения в его градации серого |
| [load(file_path)](#load_file_path_55) | Загружает новое изображение из указанного файла. |
| [load(file_path, load_options)](#load_file_path_load_options_56) | Загружает новое изображение из указанного файла. |
| [load(stream)](#load_stream_57) | Загружает новое изображение из указанного потока. |
| [load(stream, load_options)](#load_stream_load_options_58) | Загружает новое изображение из указанного потока. |
| [load_argb_32_pixels(rectangle)](#load_argb_32_pixels_rectangle_59) | Загружает 32‑битные ARGB‑пиксели. |
| [load_argb_64_pixels(rectangle)](#load_argb_64_pixels_rectangle_60) | Загружает 64‑битные ARGB‑пиксели. |
| [load_cmyk_32_pixels(rectangle)](#load_cmyk_32_pixels_rectangle_61) | Загружает пиксели в формате CMYK. |
| [load_cmyk_pixels(rectangle)](#load_cmyk_pixels_rectangle_62) | Загружает пиксели в формате CMYK.<br/>            Этот метод устарел. Пожалуйста, используйте более эффективный метод [RasterImage.load_cmyk_32_pixels(rectangle)](/psd/python-net/aspose.psd/rasterimage/). |
| [load_partial_argb_32_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_63) | Частично загружает 32‑битные ARGB‑пиксели (по блокам). |
| [load_partial_pixels(desired_rectangle, pixel_loader)](#load_partial_pixels_desired_rectangle_pixel_loader_64) | Частично загружает пиксели пакетами. |
| [load_pixels(rectangle)](#load_pixels_rectangle_65) | Загружает пиксели. |
| [load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_66) | Загружает необработанные данные. |
| [load_raw_data(rectangle, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_raw_data_settings_raw_data_loader_67) | Загружает необработанные данные. |
| [merge_layers(bottom_layer, top_layer)](#merge_layers_bottom_layer_top_layer_68) | Сливает слои. |
| normalize_angle() |  |
| normalize_angle(resize_proportionally, background_color) |  |
| [read_argb_32_scan_line(scan_line_index)](#read_argb_32_scan_line_scan_line_index_69) | Читает всю строку сканирования по указанному индексу строки сканирования. |
| [read_scan_line(scan_line_index)](#read_scan_line_scan_line_index_70) | Читает всю строку сканирования по указанному индексу строки сканирования. |
| [replace_color(old_color, old_color_diff, new_color)](#replace_color_old_color_old_color_diff_new_color_71) | Заменяет один цвет другим с допустимой разницей и сохраняет исходное значение альфа для получения плавных краев. |
| [replace_color(old_color_argb, old_color_diff, new_color_argb)](#replace_color_old_color_argb_old_color_diff_new_color_argb_72) | Заменяет один цвет другим с допустимой разницей и сохраняет исходное значение альфа для получения плавных краев. |
| [replace_non_transparent_colors(new_color)](#replace_non_transparent_colors_new_color_73) | Заменяет все непрозрачные цвета новым цветом и сохраняет исходное значение альфа для получения плавных краёв.<br/>            Примечание: если использовать его на изображениях без прозрачности, все цвета будут заменены одним цветом. |
| [replace_non_transparent_colors(new_color_argb)](#replace_non_transparent_colors_new_color_argb_74) | Заменяет все непрозрачные цвета новым цветом и сохраняет исходное значение альфа для получения плавных краёв.<br/>            Примечание: если использовать его на изображениях без прозрачности, все цвета будут заменены одним цветом. |
| [resize(new_width, new_height)](#resize_new_width_new_height_75) | Изменяет размер изображения. Используется значение по умолчанию [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/). |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_76) | Изменяет размер изображения. |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_77) | Изменяет размер изображения. |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_78) | Пропорционально изменяет высоту. |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_79) | Пропорционально изменяет высоту. |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_80) | Пропорционально изменяет высоту. |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_81) | Пропорционально изменяет ширину. Используется значение по умолчанию [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/). |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_82) | Пропорционально изменяет ширину. |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_83) | Пропорционально изменяет ширину. |
| [rotate(angle)](#rotate_angle_84) | Поворачивает изображение вокруг центра. |
| [rotate(angle, resize_proportionally, background_color)](#rotate_angle_resize_proportionally_background_color_85) | Поворачивает изображение вокруг центра. |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_86) | Поворачивает, отражает или одновременно поворачивает и отражает изображение. |
| save() | Сохраняет данные изображения в базовый поток. |
| [save(file_path)](#save_file_path_87) | Сохраняет данные объекта в указанное расположение файла. |
| [save(file_path, options)](#save_file_path_options_88) | Сохраняет данные объекта в указанное расположение файла в указанном формате файла согласно параметрам сохранения. |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_89) | Сохраняет данные объекта в указанное расположение файла в указанном формате файла согласно параметрам сохранения. |
| [save(file_path, over_write)](#save_file_path_over_write_90) | Сохраняет данные объекта в указанное расположение файла. |
| [save(stream)](#save_stream_91) | Сохраняет данные объекта в указанный поток. |
| [save(stream, options_base)](#save_stream_options_base_92) | Сохраняет данные изображения в указанный поток в указанном формате файла согласно параметрам сохранения. |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_93) | Сохраняет данные изображения в указанный поток в указанном формате файла согласно параметрам сохранения. |
| [save_argb_32_pixels(rectangle, pixels)](#save_argb_32_pixels_rectangle_pixels_94) | Сохраняет 32‑битные ARGB‑пиксели. |
| save_cmyk_32_pixels(rectangle, pixels) |  |
| save_cmyk_pixels(rectangle, pixels) |  |
| [save_pixels(rectangle, pixels)](#save_pixels_rectangle_pixels_95) | Сохраняет пиксели (метод, специфичный для формата). |
| [save_raw_data(data, data_offset, rectangle, raw_data_settings)](#save_raw_data_data_data_offset_rectangle_raw_data_settings_96) | Сохраняет необработанные данные. |
| [set_argb_32_pixel(x, y, argb_32_color)](#set_argb_32_pixel_x_y_argb_32_color_97) | Устанавливает 32‑битный ARGB‑пиксель изображения для указанной позиции. |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_98) | Устанавливает палитру изображения. |
| [set_pixel(x, y, color)](#set_pixel_x_y_color_99) | Устанавливает пиксель изображения для указанной позиции. |
| [set_resolution(dpi_x, dpi_y)](#set_resolution_dpi_x_dpi_y_100) | Устанавливает разрешение для этого [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/). |
| [to_bitmap()](#to_bitmap__101) |    |
| [write_argb_32_scan_line(scan_line_index, argb_32_pixels)](#write_argb_32_scan_line_scan_line_index_argb_32_pixels_102) | Записывает всю строку сканирования в указанный индекс строки сканирования. |
| [write_scan_line(scan_line_index, pixels)](#write_scan_line_scan_line_index_pixels_103) | Записывает всю строку сканирования в указанный индекс строки сканирования. |


### Constructor: PsdImage(path) {#PsdImage_path_1}


```
 PsdImage(path) 
```

Инициализирует новый экземпляр класса [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) из указанного пути к растровому изображению (не psd‑изображению в пути). Используется для инициализации psd‑изображения с параметрами по умолчанию — режим цвета — rgb, 4 канала, 8 бит на канал, сжатие — Raw.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| путь | string | Путь для загрузки данных пикселей и палитры и инициализации. |

### Constructor: PsdImage(path, color_mode, channel_bit_depth, channels, psd_version, compression) {#PsdImage_path_color_mode_channel_bit_depth_channels_psd_version_compression_2}


```
 PsdImage(path, color_mode, channel_bit_depth, channels, psd_version, compression) 
```

Инициализирует новый экземпляр класса [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) из указанного пути к растровому изображению (не psd‑изображению в пути) с параметрами конструктора.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| путь | string | Путь для загрузки данных пикселей и палитры и инициализации. |
| color_mode | [ColorModes](/psd/python-net/aspose.psd.fileformats.psd/colormodes) | Режим цвета. |
| channel_bit_depth | short | Глубина цвета PSD на канал. |
| каналы | short | Количество каналов PSD. |
| psd_version | int | Версия PSD. |
| compression | [CompressionMethod](/psd/python-net/aspose.psd.fileformats.psd/compressionmethod) | Сжатие, которое следует использовать. |

### Constructor: PsdImage(raster_image) {#PsdImage_raster_image_3}


```
 PsdImage(raster_image) 
```

Инициализирует новый экземпляр класса [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) из существующего растрового изображения (не psd‑изображения) с режимом цвета RGB, 4 канала, 8 бит/канал и без сжатия.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| raster_image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | Изображение, из которого загружать данные пикселей и палитры и инициализировать. |

### Constructor: PsdImage(raster_image, color_mode, channel_bit_depth, channels, psd_version, compression) {#PsdImage_raster_image_color_mode_channel_bit_depth_channels_psd_version_compression_4}


```
 PsdImage(raster_image, color_mode, channel_bit_depth, channels, psd_version, compression) 
```

Инициализирует новый экземпляр класса [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) из существующего растрового изображения (не psd‑изображения) с параметрами конструктора.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| raster_image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | Изображение, из которого загружать данные пикселей и палитры и инициализировать. |
| color_mode | [ColorModes](/psd/python-net/aspose.psd.fileformats.psd/colormodes) | Режим цвета. |
| channel_bit_depth | short | Глубина цвета PSD на канал. |
| каналы | short | Количество каналов PSD. |
| psd_version | int | Версия PSD. |
| compression | [CompressionMethod](/psd/python-net/aspose.psd.fileformats.psd/compressionmethod) | Сжатие, которое следует использовать. |

### Constructor: PsdImage(stream) {#PsdImage_stream_5}


```
 PsdImage(stream) 
```

Инициализирует новый экземпляр класса [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) из указанного пути к растровому изображению (не psd‑изображению в потоке). Используется для инициализации psd‑изображения с параметрами по умолчанию — режим цвета — rgb, 4 канала, 8 бит на канал, сжатие — Raw.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| поток | _io.BufferedRandom | Поток, из которого загружать данные пикселей и палитры и инициализировать. |

### Constructor: PsdImage(stream, color_mode, channel_bit_depth, channels, psd_version, compression) {#PsdImage_stream_color_mode_channel_bit_depth_channels_psd_version_compression_6}


```
 PsdImage(stream, color_mode, channel_bit_depth, channels, psd_version, compression) 
```

Инициализирует новый экземпляр класса [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) из указанного пути к растровому изображению (не psd‑изображению в потоке) с параметрами конструктора.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| поток | _io.BufferedRandom | Поток, из которого загружать данные пикселей и палитры и инициализировать. |
| color_mode | [ColorModes](/psd/python-net/aspose.psd.fileformats.psd/colormodes) | Режим цвета. |
| channel_bit_depth | short | Глубина цвета PSD на канал. |
| каналы | short | Количество каналов PSD. |
| psd_version | int | Версия PSD. |
| compression | [CompressionMethod](/psd/python-net/aspose.psd.fileformats.psd/compressionmethod) | Сжатие, которое следует использовать. |

### Constructor: PsdImage(width, height) {#PsdImage_width_height_7}


```
 PsdImage(width, height) 
```

Инициализирует новый экземпляр класса [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) с указанными шириной и высотой. Используется для инициализации пустого psd‑изображения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| width | int | Ширина изображения. |
| height | int | Высота изображения. |

### Constructor: PsdImage(width, height, color_palette, color_mode, channel_bit_depth, channels, psd_version, compression) {#PsdImage_width_height_color_palette_color_mode_channel_bit_depth_channels_psd_version_compression_8}


```
 PsdImage(width, height, color_palette, color_mode, channel_bit_depth, channels, psd_version, compression) 
```

Инициализирует новый экземпляр класса [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) с указанными шириной, высотой, палитрой, режимом цвета, количеством каналов и разрядностью каналов, а также параметрами указанного режима сжатия. Используется для инициализации пустого psd‑изображения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| width | int | Ширина изображения. |
| height | int | Высота изображения. |
| color_palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Цветовая палитра. |
| color_mode | [ColorModes](/psd/python-net/aspose.psd.fileformats.psd/colormodes) | Режим цвета. |
| channel_bit_depth | short | Глубина цвета PSD на канал. |
| каналы | short | Количество каналов PSD. |
| psd_version | int | Версия PSD. |
| compression | [CompressionMethod](/psd/python-net/aspose.psd.fileformats.psd/compressionmethod) | Сжатие, которое следует использовать. |

### Method: add_black_white_adjustment_layer() {#add_black_white_adjustment_layer__1}


```
 add_black_white_adjustment_layer() 
```

Добавляет слой корректировки чёрно‑белого.

**Returns**

| Тип | Описание |
| :- | :- |
| [BlackWhiteAdjustmentLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/blackwhiteadjustmentlayer/) | Созданный слой корректировки черно‑белого. |


### Method: add_brightness_contrast_adjustment_layer(brightness, contrast) {#add_brightness_contrast_adjustment_layer_brightness_contrast_2}


```
 add_brightness_contrast_adjustment_layer(brightness, contrast) 
```

Добавляет слой корректировки яркости/контраста.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| яркость | int | Яркость. |
| контраст | int | Контраст. |

**Returns**

| Тип | Описание |
| :- | :- |
| [BrightnessContrastLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/brightnesscontrastlayer/) | Созданный слой яркости/контраста |


### Method: add_channel_mixer_adjustment_layer() {#add_channel_mixer_adjustment_layer__3}


```
 add_channel_mixer_adjustment_layer() 
```

Добавляет слой корректировки микшера каналов с параметрами по умолчанию

**Returns**

| Тип | Описание |
| :- | :- |
| [ChannelMixerLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/channelmixerlayer/) | Добавлен слой микшера каналов |


### Method: add_color_balance_adjustment_layer() {#add_color_balance_adjustment_layer__4}


```
 add_color_balance_adjustment_layer() 
```

Добавляет слой коррекции цветового баланса.

**Returns**

| Тип | Описание |
| :- | :- |
| [ColorBalanceAdjustmentLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer/) | Новый созданный слой цветового баланса. |


### Method: add_curves_adjustment_layer() {#add_curves_adjustment_layer__5}


```
 add_curves_adjustment_layer() 
```

Добавляет слой коррекции кривых.

**Returns**

| Тип | Описание |
| :- | :- |
| [CurvesLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/curveslayer/) | Созданный слой [CurvesLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/curveslayer/) |


### Method: add_exposure_adjustment_layer(exposure, offset, gamma_correction) {#add_exposure_adjustment_layer_exposure_offset_gamma_correction_6}


```
 add_exposure_adjustment_layer(exposure, offset, gamma_correction) 
```

Добавляет слой коррекции экспозиции.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| экспозиция | float | Экспозиция. |
| offset | float | Смещение. |
| коррекция_гаммы | float | Гамма‑коррекция. |

**Returns**

| Тип | Описание |
| :- | :- |
| [ExposureLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/exposurelayer/) | Созданный слой корректировки экспозиции |


### Method: add_gradient_map_adjustment_layer() {#add_gradient_map_adjustment_layer__7}


```
 add_gradient_map_adjustment_layer() 
```

Добавляет слой коррекции градиентной карты.

**Returns**

| Тип | Описание |
| :- | :- |
| [GradientMapLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/gradientmaplayer/) | Экземпляр GradientMap. |


### Method: add_hue_saturation_adjustment_layer() {#add_hue_saturation_adjustment_layer__8}


```
 add_hue_saturation_adjustment_layer() 
```

Добавляет слой коррекции оттенка/насыщенности.

**Returns**

| Тип | Описание |
| :- | :- |
| [HueSaturationLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/huesaturationlayer/) | Новый созданный слой оттенка/насыщенности. |


### Method: add_invert_adjustment_layer() {#add_invert_adjustment_layer__9}


```
 add_invert_adjustment_layer() 
```

Добавляет слой инверсии.

**Returns**

| Тип | Описание |
| :- | :- |
| [InvertAdjustmentLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/invertadjustmentlayer/) | Созданный слой инвертирования |


### Method: add_layer(layer) {#add_layer_layer_10}


```
 add_layer(layer) 
```

Добавляет слой.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| layer | [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | Слой. |

### Method: add_layer_group(group_name, index, start_behaviour) {#add_layer_group_group_name_index_start_behaviour_11}


```
 add_layer_group(group_name, index, start_behaviour) 
```

Добавляет группу слоёв.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| group_name | string | Имя группы. |
| index | int | Индекс слоя, после которого вставлять. |
| start_behaviour | bool | если установлено в <c>true</c> [start behaviour], то группа будет открыта при запуске, иначе будет свернута. |

**Returns**

| Тип | Описание |
| :- | :- |
| [LayerGroup](/psd/python-net/aspose.psd.fileformats.psd.layers/layergroup/) | Открытие группы слоёв |


### Method: add_levels_adjustment_layer() {#add_levels_adjustment_layer__12}


```
 add_levels_adjustment_layer() 
```

Добавляет слой коррекции уровней.

**Returns**

| Тип | Описание |
| :- | :- |
| [LevelsLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/levelslayer/) | Новый созданный слой уровней |


### Method: add_photo_filter_layer(color) {#add_photo_filter_layer_color_13}


```
 add_photo_filter_layer(color) 
```

Добавляет слой фотофильтра.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) | Цвет. |

**Returns**

| Тип | Описание |
| :- | :- |
| [PhotoFilterLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/photofilterlayer/) | Созданный слой фотофильтра |


### Method: add_posterize_adjustment_layer() {#add_posterize_adjustment_layer__14}


```
 add_posterize_adjustment_layer() 
```

Добавляет слой коррекции постеризации.

**Returns**

| Тип | Описание |
| :- | :- |
| [PosterizeLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/posterizelayer/) | Экземпляр PosterizeLayer. |


### Method: add_regular_layer() {#add_regular_layer__15}


```
 add_regular_layer() 
```

Добавляет новый обычный слой.

**Returns**

| Тип | Описание |
| :- | :- |
| [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | Созданный обычный слой. |


### Method: add_selective_color_adjustment_layer() {#add_selective_color_adjustment_layer__16}


```
 add_selective_color_adjustment_layer() 
```

Добавляет слой коррекции выборочного цвета.

**Returns**

| Тип | Описание |
| :- | :- |
| [SelectiveColorLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/selectivecolorlayer/) | Созданный слой корректировки выборочного цвета. |


### Method: add_shape_layer() {#add_shape_layer__17}


```
 add_shape_layer() 
```

Добавить пустой слой формы.<br/>            Без путей. Их следует добавить в слой формы перед сохранением.

**Returns**

| Тип | Описание |
| :- | :- |
| [ShapeLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/shapelayer/) | Экземпляр ShapeLayer. |


### Method: add_text_layer(text, rect) {#add_text_layer_text_rect_18}


```
 add_text_layer(text, rect) 
```

Добавляет новый текстовый слой.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| text | string | Текст слоя. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Прямоугольник слоя. |

**Returns**

| Тип | Описание |
| :- | :- |
| [TextLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/textlayer/) | Создан текстовый слой. |


### Method: add_threshold_adjustment_layer() {#add_threshold_adjustment_layer__19}


```
 add_threshold_adjustment_layer() 
```

Добавляет слой коррекции порога.

**Returns**

| Тип | Описание |
| :- | :- |
| [ThresholdLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/thresholdlayer/) | Созданный слой коррекции Threshold. |


### Method: add_vibrance_adjustment_layer() {#add_vibrance_adjustment_layer__20}


```
 add_vibrance_adjustment_layer() 
```

Добавляет слой коррекции яркости.

**Returns**

| Тип | Описание |
| :- | :- |
| [VibranceLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/vibrancelayer/) | Недавно созданный слой Vibrance. |


### Method: adjust_brightness(brightness) {#adjust_brightness_brightness_21}


```
 adjust_brightness(brightness) 
```

Регулировка яркости изображения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| яркость | int | Значение яркости. |

### Method: adjust_contrast(contrast) {#adjust_contrast_contrast_22}


```
 adjust_contrast(contrast) 
```

Контрастирование изображения

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| контраст | float | Значение контраста (в диапазоне [-100; 100]) |

### Method: adjust_gamma(gamma) {#adjust_gamma_gamma_23}


```
 adjust_gamma(gamma) 
```

Гамма‑коррекция изображения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| гамма | float | Коэффициент гаммы для красного, зелёного и синего каналов |

### Method: adjust_gamma(gamma_red, gamma_green, gamma_blue) {#adjust_gamma_gamma_red_gamma_green_gamma_blue_24}


```
 adjust_gamma(gamma_red, gamma_green, gamma_blue) 
```

Гамма‑коррекция изображения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| gamma_red | float | Коэффициент гаммы для красного канала |
| gamma_green | float | Коэффициент гаммы для зелёного канала |
| gamma_blue | float | Коэффициент гаммы для синего канала |

### Method: binarize_bradley(brightness_difference) {#binarize_bradley_brightness_difference_25}


```
 binarize_bradley(brightness_difference) 
```

Бинаризация изображения с использованием адаптивного порогового алгоритма Брэдли, основанного на интегральном изображении

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| brightness_difference | double | Разница яркости между пикселем и средним значением окна s x s пикселей, центрированного вокруг этого пикселя |

### Method: binarize_bradley(brightness_difference, window_size) {#binarize_bradley_brightness_difference_window_size_26}


```
 binarize_bradley(brightness_difference, window_size) 
```

Бинаризация изображения с использованием адаптивного порогового алгоритма Брэдли, основанного на интегральном изображении

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| brightness_difference | double | Разница яркости между пикселем и средним значением окна s x s пикселей, центрированного вокруг этого пикселя |
| window_size | int | Размер окна s x s пикселей, центрированного вокруг этого пикселя |

### Method: binarize_fixed(threshold) {#binarize_fixed_threshold_27}


```
 binarize_fixed(threshold) 
```

Бинаризация изображения с предопределённым порогом.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| порог | байт | Значение порога. Если соответствующее серое значение пикселя больше порога, ему будет присвоено значение 255, иначе 0. |

### Method: can_load(file_path)  [static] {#can_load_file_path_28}


```
 can_load(file_path) 
```

Определяет, может ли изображение быть загружено из указанного пути к файлу.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | string | Путь к файлу. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | <c>true</c> если изображение может быть загружено из указанного файла; в противном случае, <c>false</c>. |


### Method: can_load(file_path, load_options)  [static] {#can_load_file_path_load_options_29}


```
 can_load(file_path, load_options) 
```

Определяет, может ли изображение быть загружено из указанного пути к файлу и, при необходимости, с использованием указанных параметров открытия.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | string | Путь к файлу. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | Параметры загрузки. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | <c>true</c> если изображение может быть загружено из указанного файла; в противном случае, <c>false</c>. |


### Method: can_load(stream)  [static] {#can_load_stream_30}


```
 can_load(stream) 
```

Определяет, может ли изображение быть загружено из указанного потока.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| поток | _io.BufferedRandom | Поток, из которого загружать. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | <c>true</c> если изображение может быть загружено из указанного потока; в противном случае, <c>false</c>. |


### Method: can_load(stream, load_options)  [static] {#can_load_stream_load_options_31}


```
 can_load(stream, load_options) 
```

Определяет, может ли изображение быть загружено из указанного потока и, при необходимости, с использованием указанного <paramref name="loadOptions" />.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| поток | _io.BufferedRandom | Поток, из которого загружать. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | Параметры загрузки. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | <c>true</c> если изображение может быть загружено из указанного потока; в противном случае, <c>false</c>. |


### Method: can_save(options) {#can_save_options_32}


```
 can_save(options) 
```

Определяет, может ли изображение быть сохранено в указанный формат файла, представленный переданными параметрами сохранения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Параметры сохранения для использования. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | <c>true</c> если изображение может быть сохранено в указанный формат файла, представленный переданными параметрами сохранения; в противном случае, <c>false</c>. |


### Method: convert(new_options) {#convert_new_options_33}


```
 convert(new_options) 
```

Преобразует формат этого изображения в указанный в параметрах.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_options | [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/) | Новые параметры. |

### Method: create(image_options, width, height)  [static] {#create_image_options_width_height_34}


```
 create(image_options, width, height) 
```

Создаёт новое изображение с использованием указанных параметров создания.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Параметры изображения. |
| width | int | Ширина. |
| height | int | Высота. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | Новое созданное изображение. |


### Method: crop(rectangle) {#crop_rectangle_35}


```
 crop(rectangle) 
```

Обрезка изображения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Прямоугольник. |

### Method: dither(dithering_method, bits_count) {#dither_dithering_method_bits_count_36}


```
 dither(dithering_method, bits_count) 
```

Выполняет дизеринг текущего изображения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/psd/python-net/aspose.psd/ditheringmethod) | Метод дизеринга. |
| bits_count | int | Окончательное количество бит для дизеринга. |

### Method: dither(dithering_method, bits_count, custom_palette) {#dither_dithering_method_bits_count_custom_palette_37}


```
 dither(dithering_method, bits_count, custom_palette) 
```

Выполняет дизеринг текущего изображения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/psd/python-net/aspose.psd/ditheringmethod) | Метод дизеринга. |
| bits_count | int | Окончательное количество бит для дизеринга. |
| custom_palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Пользовательская палитра для дизеринга. |

### Method: filter(rectangle, options) {#filter_rectangle_options_38}


```
 filter(rectangle, options) 
```

Фильтрует указанный прямоугольник.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Прямоугольник. |
| options | [FilterOptionsBase](/psd/python-net/aspose.psd.imagefilters.filteroptions/filteroptionsbase/) | Параметры. |

### Method: get_argb_32_pixel(x, y) {#get_argb_32_pixel_x_y_39}


```
 get_argb_32_pixel(x, y) 
```

Получает 32‑битный ARGB‑пиксель изображения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | int | Координата x пикселя. |
| y | int | Координата y пикселя. |

**Returns**

| Тип | Описание |
| :- | :- |
| int | 32‑битный ARGB‑пиксель для указанного расположения. |


### Method: get_default_argb_32_pixels(rectangle) {#get_default_argb_32_pixels_rectangle_40}


```
 get_default_argb_32_pixels(rectangle) 
```

Получает массив пикселей по умолчанию в формате 32‑бит ARGB.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Прямоугольник, из которого получать пиксели. |

**Returns**

| Тип | Описание |
| :- | :- |
| int | Массив пикселей по умолчанию. |


### Method: get_default_options(args) {#get_default_options_args_41}


```
 get_default_options(args) 
```

Получает параметры по умолчанию.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| args | object | Аргументы. |

**Returns**

| Тип | Описание |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Параметры по умолчанию |


### Method: get_default_pixels(rectangle, partial_pixel_loader) {#get_default_pixels_rectangle_partial_pixel_loader_42}


```
 get_default_pixels(rectangle, partial_pixel_loader) 
```

Получает массив пикселей по умолчанию с использованием частичного загрузчика пикселей.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Прямоугольник, из которого получать пиксели. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/psd/python-net/aspose.psd/ipartialargb32pixelloader) | Частичный загрузчик пикселей. |

### Method: get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) {#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_43}


```
 get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) 
```

Получает массив необработанных данных по умолчанию с использованием частичного загрузчика пикселей.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Прямоугольник, из которого получать пиксели. |
| partial_raw_data_loader | [IPartialRawDataLoader](/psd/python-net/aspose.psd/ipartialrawdataloader) | Частичный загрузчик необработанных данных. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | Настройки необработанных данных. |

### Method: get_default_raw_data(rectangle, raw_data_settings) {#get_default_raw_data_rectangle_raw_data_settings_44}


```
 get_default_raw_data(rectangle, raw_data_settings) 
```

Получает массив необработанных данных по умолчанию.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Прямоугольник, из которого получать необработанные данные. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | Настройки необработанных данных. |

**Returns**

| Тип | Описание |
| :- | :- |
| байт | Массив необработанных данных по умолчанию. |


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_45}


```
 get_file_format(file_path) 
```

Получает формат файла.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | string | Путь к файлу. |

**Returns**

| Тип | Описание |
| :- | :- |
| [FileFormat](/psd/python-net/aspose.psd/fileformat) | Определённый формат файла. |


### Method: get_file_format(stream)  [static] {#get_file_format_stream_46}


```
 get_file_format(stream) 
```

Получает формат файла.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| поток | _io.BufferedRandom | Поток. |

**Returns**

| Тип | Описание |
| :- | :- |
| [FileFormat](/psd/python-net/aspose.psd/fileformat) | Определённый формат файла. |


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_47}


```
 get_fitting_rectangle(rectangle, pixels, width, height) 
```

Получает прямоугольник, который вписывается в текущее изображение.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Прямоугольник, для которого получить подходящий прямоугольник. |
| pixels | int | 32‑битные ARGB‑пиксели. |
| width | int | Ширина объекта. |
| height | int | Высота объекта. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | Подходящий прямоугольник или исключение, если подходящий прямоугольник не найден. |


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_48}


```
 get_fitting_rectangle(rectangle, width, height) 
```

Получает прямоугольник, который вписывается в текущее изображение.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Прямоугольник, для которого получить подходящий прямоугольник. |
| width | int | Ширина объекта. |
| height | int | Высота объекта. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | Подходящий прямоугольник или исключение, если подходящий прямоугольник не найден. |


### Method: get_modify_date(use_default) {#get_modify_date_use_default_49}


```
 get_modify_date(use_default) 
```

Получает дату и время последнего изменения ресурсного изображения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| use_default | bool | если установлено в <c>true</c>, использует информацию из FileInfo в качестве значения по умолчанию. |

**Returns**

| Тип | Описание |
| :- | :- |
| datetime | Дата и время последнего изменения изображения ресурса. |


### Method: get_original_options() {#get_original_options__50}


```
 get_original_options() 
```

Получает параметры на основе настроек исходного файла.<br/>            Это может быть полезно для сохранения глубины цвета и других параметров исходного изображения без изменений.<br/>            Например, если мы загружаем черно-белое PNG‑изображение с 1 битом на пиксель, а затем сохраняем его с помощью<br/>            метода [DataStreamSupporter.save(file_path)](/psd/python-net/aspose.psd/datastreamsupporter/), будет получено PNG‑изображение с 8 битами на пиксель.<br/>            Чтобы избежать этого и сохранить PNG‑изображение с 1 битом на пиксель, используйте этот метод для получения соответствующих параметров сохранения и передайте их<br/>            методу [Image.save(file_path, options)](/psd/python-net/aspose.psd/image/) в качестве второго параметра.

**Returns**

| Тип | Описание |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Параметры, основанные на настройках оригинального файла. |


### Method: get_pixel(x, y) {#get_pixel_x_y_51}


```
 get_pixel(x, y) 
```

Получает пиксель изображения.<br/>            Предупреждение о производительности: избегайте использования этого метода для обхода всех пикселей изображения, так как это может привести к значительным проблемам с производительностью.<br/>            Для более эффективного управления пикселями используйте метод `LoadArgb32Pixels` для одновременного получения всего массива пикселей.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | int | Координата x пикселя. |
| y | int | Координата y пикселя. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | Цвет пикселя для указанного положения. |


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_52}


```
 get_proportional_height(width, height, new_width) 
```

Получает пропорциональную высоту.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| width | int | Ширина. |
| height | int | Высота. |
| new_width | int | Новая ширина. |

**Returns**

| Тип | Описание |
| :- | :- |
| int | Пропорциональная высота. |


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_53}


```
 get_proportional_width(width, height, new_height) 
```

Получает пропорциональную ширину.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| width | int | Ширина. |
| height | int | Высота. |
| new_height | int | Новая высота. |

**Returns**

| Тип | Описание |
| :- | :- |
| int | Пропорциональная ширина. |


### Method: get_skew_angle() {#get_skew_angle__54}


```
 get_skew_angle() 
```

  

**Returns**

| Тип | Описание |
| :- | :- |
| float |  |


### Method: load(file_path)  [static] {#load_file_path_55}


```
 load(file_path) 
```

Загружает новое изображение из указанного файла.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | string | Путь к файлу, из которого загружать изображение. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | Загруженное изображение. |


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_56}


```
 load(file_path, load_options) 
```

Загружает новое изображение из указанного файла.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | string | Путь к файлу, из которого загружать изображение. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | Параметры загрузки. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | Загруженное изображение. |


### Method: load(stream)  [static] {#load_stream_57}


```
 load(stream) 
```

Загружает новое изображение из указанного потока.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| поток | _io.BufferedRandom | Поток, из которого загружать изображение. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | Загруженное изображение. |


### Method: load(stream, load_options)  [static] {#load_stream_load_options_58}


```
 load(stream, load_options) 
```

Загружает новое изображение из указанного потока.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| поток | _io.BufferedRandom | Поток, из которого загружать изображение. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | Параметры загрузки. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | Загруженное изображение. |


### Method: load_argb_32_pixels(rectangle) {#load_argb_32_pixels_rectangle_59}


```
 load_argb_32_pixels(rectangle) 
```

Загружает 32‑битные ARGB‑пиксели.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Прямоугольник, из которого загружать пиксели. |

**Returns**

| Тип | Описание |
| :- | :- |
| int | Загруженный массив 32‑битных ARGB пикселей. |


### Method: load_argb_64_pixels(rectangle) {#load_argb_64_pixels_rectangle_60}


```
 load_argb_64_pixels(rectangle) 
```

Загружает 64‑битные ARGB‑пиксели.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Прямоугольник, из которого загружать пиксели. |

**Returns**

| Тип | Описание |
| :- | :- |
| long | Загруженный массив 64‑битных ARGB пикселей. |


### Method: load_cmyk_32_pixels(rectangle) {#load_cmyk_32_pixels_rectangle_61}


```
 load_cmyk_32_pixels(rectangle) 
```

Загружает пиксели в формате CMYK.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Прямоугольник, из которого загружать пиксели. |

**Returns**

| Тип | Описание |
| :- | :- |
| int | Загруженные CMYK пиксели, представленные как 32‑битные целочисленные значения. |


### Method: load_cmyk_pixels(rectangle) {#load_cmyk_pixels_rectangle_62}


```
 load_cmyk_pixels(rectangle) 
```

Загружает пиксели в формате CMYK.<br/>            Этот метод устарел. Пожалуйста, используйте более эффективный метод [RasterImage.load_cmyk_32_pixels(rectangle)](/psd/python-net/aspose.psd/rasterimage/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Прямоугольник, из которого загружать пиксели. |

**Returns**

| Тип | Описание |
| :- | :- |
| [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | Загруженный массив CMYK пикселей. |


### Method: load_partial_argb_32_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_63}


```
 load_partial_argb_32_pixels(rectangle, partial_pixel_loader) 
```

Частично загружает 32‑битные ARGB‑пиксели (по блокам).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Прямоугольник, из которого загружать пиксели. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/psd/python-net/aspose.psd/ipartialargb32pixelloader) | Частичный загрузчик пикселей. |

### Method: load_partial_pixels(desired_rectangle, pixel_loader) {#load_partial_pixels_desired_rectangle_pixel_loader_64}


```
 load_partial_pixels(desired_rectangle, pixel_loader) 
```

Частично загружает пиксели пакетами.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| desired_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Желаемый прямоугольник. |
| pixel_loader | [IPartialPixelLoader](/psd/python-net/aspose.psd/ipartialpixelloader) | Загрузчик пикселей. |

### Method: load_pixels(rectangle) {#load_pixels_rectangle_65}


```
 load_pixels(rectangle) 
```

Загружает пиксели.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Прямоугольник, из которого загружать пиксели. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | Загруженный массив пикселей. |


### Method: load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_66}


```
 load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) 
```

Загружает необработанные данные.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Прямоугольник, из которого загружаются необработанные данные. |
| dest_image_bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Границы целевого изображения. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | Настройки необработанных данных, используемые для загруженных данных. Обратите внимание, что если данные не в указанном формате, будет выполнено преобразование данных. |
| raw_data_loader | [IPartialRawDataLoader](/psd/python-net/aspose.psd/ipartialrawdataloader) | Загрузчик необработанных данных. |

### Method: load_raw_data(rectangle, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_raw_data_settings_raw_data_loader_67}


```
 load_raw_data(rectangle, raw_data_settings, raw_data_loader) 
```

Загружает необработанные данные.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Прямоугольник, из которого загружаются необработанные данные. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | Настройки необработанных данных, используемые для загруженных данных. Обратите внимание, что если данные не в указанном формате, будет выполнено преобразование данных. |
| raw_data_loader | [IPartialRawDataLoader](/psd/python-net/aspose.psd/ipartialrawdataloader) | Загрузчик необработанных данных. |

### Method: merge_layers(bottom_layer, top_layer) {#merge_layers_bottom_layer_top_layer_68}


```
 merge_layers(bottom_layer, top_layer) 
```

Сливает слои.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| bottom_layer | [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | Нижний слой. |
| top_layer | [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | Верхний слой. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | Нижний слой после объединения |


### Method: read_argb_32_scan_line(scan_line_index) {#read_argb_32_scan_line_scan_line_index_69}


```
 read_argb_32_scan_line(scan_line_index) 
```

Читает всю строку сканирования по указанному индексу строки сканирования.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| scan_line_index | int | Нулевой индекс строки сканирования. |

**Returns**

| Тип | Описание |
| :- | :- |
| int | Массив 32‑битных ARGB значений цвета строки сканирования. |


### Method: read_scan_line(scan_line_index) {#read_scan_line_scan_line_index_70}


```
 read_scan_line(scan_line_index) 
```

Читает всю строку сканирования по указанному индексу строки сканирования.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| scan_line_index | int | Нулевой индекс строки сканирования. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | Массив значений цвета пикселей строки сканирования. |


### Method: replace_color(old_color, old_color_diff, new_color) {#replace_color_old_color_old_color_diff_new_color_71}


```
 replace_color(old_color, old_color_diff, new_color) 
```

Заменяет один цвет другим с допустимой разницей и сохраняет исходное значение альфа для получения плавных краев.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| old_color | [Color](/psd/python-net/aspose.psd/color) |  |
| old_color_diff | байт | Допустимая разница в старом цвете, позволяющая расширить заменённый тон цвета. |
| new_color | [Color](/psd/python-net/aspose.psd/color) |  |

### Method: replace_color(old_color_argb, old_color_diff, new_color_argb) {#replace_color_old_color_argb_old_color_diff_new_color_argb_72}


```
 replace_color(old_color_argb, old_color_diff, new_color_argb) 
```

Заменяет один цвет другим с допустимой разницей и сохраняет исходное значение альфа для получения плавных краев.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| old_color_argb | int | Значение ARGB старого цвета, которое будет заменено. |
| old_color_diff | байт | Допустимая разница в старом цвете, позволяющая расширить заменённый тон цвета. |
| new_color_argb | int | Значение ARGB нового цвета, которым заменяется старый цвет. |

### Method: replace_non_transparent_colors(new_color) {#replace_non_transparent_colors_new_color_73}


```
 replace_non_transparent_colors(new_color) 
```

Заменяет все непрозрачные цвета новым цветом и сохраняет исходное значение альфа для получения плавных краёв.<br/>            Примечание: если использовать его на изображениях без прозрачности, все цвета будут заменены одним цветом.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_color | [Color](/psd/python-net/aspose.psd/color) |  |

### Method: replace_non_transparent_colors(new_color_argb) {#replace_non_transparent_colors_new_color_argb_74}


```
 replace_non_transparent_colors(new_color_argb) 
```

Заменяет все непрозрачные цвета новым цветом и сохраняет исходное значение альфа для получения плавных краёв.<br/>            Примечание: если использовать его на изображениях без прозрачности, все цвета будут заменены одним цветом.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_color_argb | int | Новое значение ARGB цвета для замены непрозрачных цветов. |

### Method: resize(new_width, new_height) {#resize_new_width_new_height_75}


```
 resize(new_width, new_height) 
```

Изменяет размер изображения. Используется значение по умолчанию [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_width | int | Новая ширина. |
| new_height | int | Новая высота. |

### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_76}


```
 resize(new_width, new_height, resize_type) 
```

Изменяет размер изображения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_width | int | Новая ширина. |
| new_height | int | Новая высота. |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | Тип изменения размера. |

### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_77}


```
 resize(new_width, new_height, settings) 
```

Изменяет размер изображения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_width | int | Новая ширина. |
| new_height | int | Новая высота. |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | Настройки изменения размера. |

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_78}


```
 resize_height_proportionally(new_height) 
```

Пропорционально изменяет высоту.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_height | int | Новая высота. |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_79}


```
 resize_height_proportionally(new_height, resize_type) 
```

Пропорционально изменяет высоту.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_height | int | Новая высота. |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | Тип изменения размера. |

### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_80}


```
 resize_height_proportionally(new_height, settings) 
```

Пропорционально изменяет высоту.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_height | int | Новая высота. |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | Настройки изменения размера изображения. |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_81}


```
 resize_width_proportionally(new_width) 
```

Пропорционально изменяет ширину. Используется значение по умолчанию [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_width | int | Новая ширина. |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_82}


```
 resize_width_proportionally(new_width, resize_type) 
```

Пропорционально изменяет ширину.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_width | int | Новая ширина. |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | Тип изменения размера. |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_83}


```
 resize_width_proportionally(new_width, settings) 
```

Пропорционально изменяет ширину.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_width | int | Новая ширина. |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | Настройки изменения размера изображения. |

### Method: rotate(angle) {#rotate_angle_84}


```
 rotate(angle) 
```

Поворачивает изображение вокруг центра.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| угол | float | Угол вращения в градусах. Положительные значения вращают по часовой стрелке. |

### Method: rotate(angle, resize_proportionally, background_color) {#rotate_angle_resize_proportionally_background_color_85}


```
 rotate(angle, resize_proportionally, background_color) 
```

Поворачивает изображение вокруг центра.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| угол | float | Угол вращения в градусах. Положительные значения вращают по часовой стрелке. |
| resize_proportionally | bool | если установить в <c>true</c>, размер изображения будет изменён в соответствии с проекциями повернутого прямоугольника (угловых точек); в противном случае размеры останутся неизменными, и будет вращено только внутреннее содержимое изображения. |
| background_color | [Color](/psd/python-net/aspose.psd/color) | Цвет фона. |

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_86}


```
 rotate_flip(rotate_flip_type) 
```

Поворачивает, отражает или одновременно поворачивает и отражает изображение.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/psd/python-net/aspose.psd/rotatefliptype) | Тип вращения и отражения. |

### Method: save(file_path) {#save_file_path_87}


```
 save(file_path) 
```

Сохраняет данные объекта в указанное расположение файла.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | string | Путь к файлу для сохранения данных объекта. |

### Method: save(file_path, options) {#save_file_path_options_88}


```
 save(file_path, options) 
```

Сохраняет данные объекта в указанное расположение файла в указанном формате файла согласно параметрам сохранения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | string | Путь к файлу. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Параметры. |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_89}


```
 save(file_path, options, bounds_rectangle) 
```

Сохраняет данные объекта в указанное расположение файла в указанном формате файла согласно параметрам сохранения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | string | Путь к файлу. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Параметры. |
| bounds_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Прямоугольник границ целевого изображения. Установите пустой прямоугольник для использования границ источника. |

### Method: save(file_path, over_write) {#save_file_path_over_write_90}


```
 save(file_path, over_write) 
```

Сохраняет данные объекта в указанное расположение файла.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | string | Путь к файлу для сохранения данных объекта. |
| over_write | bool | если установить в <c>true</c>, содержимое файла будет перезаписано, иначе будет выполнено добавление. |

### Method: save(stream) {#save_stream_91}


```
 save(stream) 
```

Сохраняет данные объекта в указанный поток.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| поток | _io.BufferedRandom | Поток для сохранения данных объекта. |

### Method: save(stream, options_base) {#save_stream_options_base_92}


```
 save(stream, options_base) 
```

Сохраняет данные изображения в указанный поток в указанном формате файла согласно параметрам сохранения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| поток | _io.BufferedRandom | Поток для сохранения данных изображения. |
| options_base | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Параметры сохранения. |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_93}


```
 save(stream, options_base, bounds_rectangle) 
```

Сохраняет данные изображения в указанный поток в указанном формате файла согласно параметрам сохранения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| поток | _io.BufferedRandom | Поток для сохранения данных изображения. |
| options_base | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Параметры сохранения. |
| bounds_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Прямоугольник границ целевого изображения. Установите пустой прямоугольник для использования границ источника. |

### Method: save_argb_32_pixels(rectangle, pixels) {#save_argb_32_pixels_rectangle_pixels_94}


```
 save_argb_32_pixels(rectangle, pixels) 
```

Сохраняет 32‑битные ARGB‑пиксели.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Прямоугольник для сохранения пикселей. |
| pixels | int | Массив 32‑битных ARGB‑пикселей. |

### Method: save_pixels(rectangle, pixels) {#save_pixels_rectangle_pixels_95}


```
 save_pixels(rectangle, pixels) 
```

Сохраняет пиксели (метод, специфичный для формата).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Прямоугольник для сохранения пикселей. |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) | Массив 32‑битных ARGB‑пикселей. |

### Method: save_raw_data(data, data_offset, rectangle, raw_data_settings) {#save_raw_data_data_data_offset_rectangle_raw_data_settings_96}


```
 save_raw_data(data, data_offset, rectangle, raw_data_settings) 
```

Сохраняет необработанные данные.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| данные | байт | Необработанные данные. |
| data_offset | int | Начальное смещение необработанных данных. |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Прямоугольник необработанных данных. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | Настройки формата необработанных данных. |

### Method: set_argb_32_pixel(x, y, argb_32_color) {#set_argb_32_pixel_x_y_argb_32_color_97}


```
 set_argb_32_pixel(x, y, argb_32_color) 
```

Устанавливает 32‑битный ARGB‑пиксель изображения для указанной позиции.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | int | Координата x пикселя. |
| y | int | Координата y пикселя. |
| argb_32_color | int | 32‑битный ARGB‑пиксель для указанной позиции. |

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_98}


```
 set_palette(palette, update_colors) 
```

Устанавливает палитру изображения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Палитра для установки. |
| update_colors | bool | если установить значение <c>true</c>, цвета будут обновлены в соответствии с новой палитрой; в противном случае индексы цветов останутся без изменений. Обратите внимание, что неизменённые индексы могут вызвать сбой изображения при загрузке, если у некоторых индексов нет соответствующих записей в палитре. |

### Method: set_pixel(x, y, color) {#set_pixel_x_y_color_99}


```
 set_pixel(x, y, color) 
```

Устанавливает пиксель изображения для указанной позиции.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | int | Координата x пикселя. |
| y | int | Координата y пикселя. |
| color | [Color](/psd/python-net/aspose.psd/color) | Цвет пикселя для указанной позиции. |

### Method: set_resolution(dpi_x, dpi_y) {#set_resolution_dpi_x_dpi_y_100}


```
 set_resolution(dpi_x, dpi_y) 
```

Устанавливает разрешение для этого [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| dpi_x | double | Горизонтальное разрешение в точках на дюйм для [RasterImage](/psd/python-net/aspose.psd/rasterimage/). |
| dpi_y | double | Вертикальное разрешение в точках на дюйм для [RasterImage](/psd/python-net/aspose.psd/rasterimage/). |

### Method: to_bitmap() {#to_bitmap__101}


```
 to_bitmap() 
```

  

**Returns**

| Тип | Описание |
| :- | :- |
| aspose.pydrawing.Bitmap |  |


### Method: write_argb_32_scan_line(scan_line_index, argb_32_pixels) {#write_argb_32_scan_line_scan_line_index_argb_32_pixels_102}


```
 write_argb_32_scan_line(scan_line_index, argb_32_pixels) 
```

Записывает всю строку сканирования в указанный индекс строки сканирования.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| scan_line_index | int | Нулевой индекс строки сканирования. |
| argb_32_pixels | int | Массив 32‑битных ARGB‑цветов для записи. |

### Method: write_scan_line(scan_line_index, pixels) {#write_scan_line_scan_line_index_pixels_103}


```
 write_scan_line(scan_line_index, pixels) 
```

Записывает всю строку сканирования в указанный индекс строки сканирования.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| scan_line_index | int | Нулевой индекс строки сканирования. |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) | Массив цветов пикселей для записи. |

