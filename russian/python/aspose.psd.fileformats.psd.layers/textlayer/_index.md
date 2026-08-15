---
title: "Класс TextLayer"
type: docs
weight: 1750
url: /ru/python-net/aspose.psd.fileformats.psd.layers/textlayer/
---

**Summary:** The text layer class

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.TextLayer

**Inheritance:** IObjectWithBounds, IRasterImageArgb32PixelLoader, IRasterImageRawDataLoader, Layer

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| BLEND_SIGNATURE [static] | int | r |  |
| LAYER_HEADER_SIZE [static] | int | r |  |
| auto_adjust_palette | bool | r/w |  |
| background_color | [Color](/psd/python-net/aspose.psd/color) | r/w |    |
| bits_per_pixel | int | r |  |
| blend_clipped_elements | bool | r/w |  |
| blend_mode_key | [BlendMode](/psd/python-net/aspose.psd.fileformats.core.blending/blendmode/) | r/w |    |
| blend_mode_signature | int | r |  |
| blending_options | [BlendingOptions](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/) | r |    |
| bottom | int | r/w |  |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | Получает границы объекта. |
| buffer_size_hint | int | r/w |  |
| channel_information | [ChannelInformation[]](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | r/w |    |
| channels_count | ushort | r |  |
| clipping | байт | r/w |  |
| container | [Image](/psd/python-net/aspose.psd/image) | r |    |
| data_stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | r |    |
| display_name | string | r/w |  |
| освобождено | bool | r |  |
| дополнительная_длина | int | r |  |
| file_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r |    |
| непрозрачность_заполнения | int | r/w |  |
| заполнитель | байт | r/w |  |
| flags | [LayerFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layerflags) | r/w |    |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | r | Получает шрифт. |
| имеет_alpha | bool | r |  |
| имеет_цвет_фона | bool | r/w |  |
| имеет_прозрачный_цвет | bool | r/w |  |
| height | int | r | Получает высоту объекта. |
| горизонтальное_разрешение | double | r/w |  |
| непрозрачность_изображения | float | r |  |
| inner_text | string | r | Получает текст слоя |
| interrupt_monitor | [InterruptMonitor](/psd/python-net/aspose.psd.multithreading/interruptmonitor/) | r/w |    |
| закешировано | bool | r |  |
| сырые_данные_доступны | bool | r | Получает значение, указывающее, поддерживается ли загрузка сырых данных. |
| видим | bool | r/w |  |
| видим_в_группе | bool | r |  |
| layer_blending_ranges_data | [LayerBlendingRangesData](/psd/python-net/aspose.psd.fileformats.psd.layers/layerblendingrangesdata) | r/w |    |
| дата_и_время_создания_слоя | datetime | r/w |  |
| layer_lock | [LayerLockType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/layerlocktype/) | r/w |    |
| layer_mask_data | [LayerMaskData](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata) | r/w |    |
| layer_options | [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/) | r |    |
| слева | int | r/w |  |
| длина | int | r |  |
| name | string | r/w | Получает или задает имя текстового слоя. |
| opacity | байт | r/w |  |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w |    |
| предумножить_компоненты | bool | r/w |  |
| raw_custom_color_converter | [IColorConverter](/psd/python-net/aspose.psd/icolorconverter) | r/w |    |
| raw_data_format | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r |    |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | r | Получает текущие настройки сырых данных. Примечание: при использовании этих настроек данные загружаются без конвертации. |
| индекс_резервного_варианта | int | r/w |  |
| raw_indexed_color_converter | [IIndexedColorConverter](/psd/python-net/aspose.psd/iindexedcolorconverter) | r/w |    |
| размер_строки_сырых | int | r |  |
| resources | [LayerResource[]](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource) | r/w |    |
| справа | int | r/w |  |
| sheet_color_highlight | [SheetColorHighlightEnum](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/sheetcolorhighlightenum/) | r/w |    |
| size | [Size](/psd/python-net/aspose.psd/size) | r | Получает размер объекта. |
| text | string | r | Получает текст. |
| text_bound_box | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r/w | Получает или задает ограничивающий прямоугольник текста. |
| text_color | [Color](/psd/python-net/aspose.psd/color) | r | Получает цвет текста. |
| text_data | [IText](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itext/) | r | Получает части текста. |
| верх | int | r/w |  |
| transform_matrix | double | r/w | Получает или задает матрицу преобразования |
| transparent_color | [Color](/psd/python-net/aspose.psd/color) | r/w |    |
| update_xmp_data | bool | r/w |  |
| use_palette | bool | r |  |
| use_raw_data | bool | r/w |  |
| vertical_resolution | double | r/w |  |
| warp_settings | [WarpSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.warp/warpsettings/) | r/w | Получает или задаёт параметры Warp, которые были установлены или получены из ресурса (по умолчанию) |
| width | int | r | Получает ширину объекта. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w |    |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| add_layer_mask(layer_mask) |  |
| adjust_brightness(brightness) |  |
| adjust_contrast(contrast) |  |
| adjust_gamma(gamma) |  |
| adjust_gamma(gamma_red, gamma_green, gamma_blue) |  |
| binarize_bradley(brightness_difference) |  |
| binarize_bradley(brightness_difference, window_size) |  |
| binarize_fixed(threshold) |  |
| binarize_otsu() |  |
| cache_data() |  |
| [can_load(file_path)](#can_load_file_path_1) |    |
| [can_load(file_path, load_options)](#can_load_file_path_load_options_2) |    |
| [can_load(stream)](#can_load_stream_3) |    |
| [can_load(stream, load_options)](#can_load_stream_load_options_4) |    |
| [can_save(options)](#can_save_options_5) |    |
| [create(image_options, width, height)](#create_image_options_width_height_6) |    |
| crop(left_shift, right_shift, top_shift, bottom_shift) |  |
| crop(rectangle) |  |
| dither(dithering_method, bits_count) |  |
| dither(dithering_method, bits_count, custom_palette) |  |
| draw_image(location, image) |  |
| filter(rectangle, options) |  |
| [get_argb_32_pixel(x, y)](#get_argb_32_pixel_x_y_7) |    |
| [get_default_argb_32_pixels(rectangle)](#get_default_argb_32_pixels_rectangle_8) |    |
| [get_default_options(args)](#get_default_options_args_9) |    |
| get_default_pixels(rectangle, partial_pixel_loader) |  |
| get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) |  |
| [get_default_raw_data(rectangle, raw_data_settings)](#get_default_raw_data_rectangle_raw_data_settings_10) |    |
| [get_file_format(file_path)](#get_file_format_file_path_11) |    |
| [get_file_format(stream)](#get_file_format_stream_12) |    |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_13) |    |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_14) |    |
| [get_fonts()](#get_fonts__15) | Получает набор шрифтов текстового слоя. |
| [get_modify_date(use_default)](#get_modify_date_use_default_16) |    |
| [get_original_options()](#get_original_options__17) |    |
| [get_pixel(x, y)](#get_pixel_x_y_18) |    |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_19) |    |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_20) |    |
| [get_skew_angle()](#get_skew_angle__21) |    |
| grayscale() |  |
| [load(file_path)](#load_file_path_22) |    |
| [load(file_path, load_options)](#load_file_path_load_options_23) |    |
| [load(stream)](#load_stream_24) |    |
| [load(stream, load_options)](#load_stream_load_options_25) |    |
| [load_argb_32_pixels(rectangle)](#load_argb_32_pixels_rectangle_26) |    |
| [load_argb_64_pixels(rectangle)](#load_argb_64_pixels_rectangle_27) |    |
| [load_cmyk_32_pixels(rectangle)](#load_cmyk_32_pixels_rectangle_28) |    |
| [load_cmyk_pixels(rectangle)](#load_cmyk_pixels_rectangle_29) |    |
| [load_partial_argb_32_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_30) | Частично загружает 32‑битные ARGB‑пиксели (по блокам). |
| load_partial_pixels(desired_rectangle, pixel_loader) |  |
| [load_pixels(rectangle)](#load_pixels_rectangle_31) |    |
| load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) |  |
| [load_raw_data(rectangle, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_raw_data_settings_raw_data_loader_32) | Загружает необработанные данные. |
| merge_layer_to(layer_to_merge_into) |  |
| normalize_angle() |  |
| normalize_angle(resize_proportionally, background_color) |  |
| [read_argb_32_scan_line(scan_line_index)](#read_argb_32_scan_line_scan_line_index_33) |    |
| [read_scan_line(scan_line_index)](#read_scan_line_scan_line_index_34) |    |
| replace_color(old_color, old_color_diff, new_color) |  |
| replace_color(old_color_argb, old_color_diff, new_color_argb) |  |
| replace_non_transparent_colors(new_color) |  |
| replace_non_transparent_colors(new_color_argb) |  |
| resize(new_width, new_height) |  |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_35) | Изменяет размер изображения. По умолчанию используется [ResizeType.LEFT_TOP_TO_LEFT_TOP](/psd/python-net/aspose.psd/resizetype/). |
| resize(new_width, new_height, settings) |  |
| resize_height_proportionally(new_height) |  |
| resize_height_proportionally(new_height, resize_type) |  |
| resize_height_proportionally(new_height, settings) |  |
| resize_width_proportionally(new_width) |  |
| resize_width_proportionally(new_width, resize_type) |  |
| resize_width_proportionally(new_width, settings) |  |
| rotate(angle) |  |
| rotate(angle, resize_proportionally, background_color) |  |
| rotate_flip(rotate_flip_type) |  |
| save() |  |
| save(file_path) |  |
| save(file_path, options) |  |
| save(file_path, options, bounds_rectangle) |  |
| save(file_path, over_write) |  |
| save(stream) |  |
| save(stream, options_base) |  |
| save(stream, options_base, bounds_rectangle) |  |
| save_argb_32_pixels(rectangle, pixels) |  |
| save_cmyk_32_pixels(rectangle, pixels) |  |
| save_cmyk_pixels(rectangle, pixels) |  |
| save_pixels(rectangle, pixels) |  |
| save_raw_data(data, data_offset, rectangle, raw_data_settings) |  |
| set_argb_32_pixel(x, y, argb_32_color) |  |
| set_palette(palette, update_colors) |  |
| set_pixel(x, y, color) |  |
| set_resolution(dpi_x, dpi_y) |  |
| [shallow_copy()](#shallow_copy__36) |    |
| [to_bitmap()](#to_bitmap__37) |    |
| [update_text(text)](#update_text_text_38) | Обновляет текст. |
| [update_text(text, color)](#update_text_text_color_39) | Обновляет текст. |
| [update_text(text, font_size)](#update_text_text_font_size_40) | Обновляет текст. |
| [update_text(text, font_size, color)](#update_text_text_font_size_color_41) | Обновляет текст. |
| [update_text(text, left_top_coordinate)](#update_text_text_left_top_coordinate_42) | Обновляет текст. |
| [update_text(text, left_top_coordinate, color)](#update_text_text_left_top_coordinate_color_43) | Обновляет текст. |
| [update_text(text, left_top_coordinate, font_size)](#update_text_text_left_top_coordinate_font_size_44) | Обновляет текст. |
| [update_text(text, left_top_coordinate, font_size, color)](#update_text_text_left_top_coordinate_font_size_color_45) | Обновляет текст. |
| write_argb_32_scan_line(scan_line_index, argb_32_pixels) |  |
| write_scan_line(scan_line_index, pixels) |  |


### Method: can_load(file_path)  [static] {#can_load_file_path_1}


```
 can_load(file_path) 
```

  

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | string |  |

**Returns**

| Тип | Описание |
| :- | :- |
| bool |  |


### Method: can_load(file_path, load_options)  [static] {#can_load_file_path_load_options_2}


```
 can_load(file_path, load_options) 
```

  

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | string |  |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) |  |

**Returns**

| Тип | Описание |
| :- | :- |
| bool |  |


### Method: can_load(stream)  [static] {#can_load_stream_3}


```
 can_load(stream) 
```

  

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| поток | _io.BufferedRandom |  |

**Returns**

| Тип | Описание |
| :- | :- |
| bool |  |


### Method: can_load(stream, load_options)  [static] {#can_load_stream_load_options_4}


```
 can_load(stream, load_options) 
```

  

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| поток | _io.BufferedRandom |  |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) |  |

**Returns**

| Тип | Описание |
| :- | :- |
| bool |  |


### Method: can_save(options) {#can_save_options_5}


```
 can_save(options) 
```

  

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) |  |

**Returns**

| Тип | Описание |
| :- | :- |
| bool |  |


### Method: create(image_options, width, height)  [static] {#create_image_options_width_height_6}


```
 create(image_options, width, height) 
```

  

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) |  |
| width | int |  |
| height | int |  |

**Returns**

| Тип | Описание |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) |  |


### Method: get_argb_32_pixel(x, y) {#get_argb_32_pixel_x_y_7}


```
 get_argb_32_pixel(x, y) 
```

  

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | int |  |
| y | int |  |

**Returns**

| Тип | Описание |
| :- | :- |
| int |  |


### Method: get_default_argb_32_pixels(rectangle) {#get_default_argb_32_pixels_rectangle_8}


```
 get_default_argb_32_pixels(rectangle) 
```

  

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |

**Returns**

| Тип | Описание |
| :- | :- |
| int |  |


### Method: get_default_options(args) {#get_default_options_args_9}


```
 get_default_options(args) 
```

  

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| args | object |  |

**Returns**

| Тип | Описание |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) |  |


### Method: get_default_raw_data(rectangle, raw_data_settings) {#get_default_raw_data_rectangle_raw_data_settings_10}


```
 get_default_raw_data(rectangle, raw_data_settings) 
```

  

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) |  |

**Returns**

| Тип | Описание |
| :- | :- |
| байт |  |


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_11}


```
 get_file_format(file_path) 
```

  

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | string |  |

**Returns**

| Тип | Описание |
| :- | :- |
| [FileFormat](/psd/python-net/aspose.psd/fileformat) |  |


### Method: get_file_format(stream)  [static] {#get_file_format_stream_12}


```
 get_file_format(stream) 
```

  

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| поток | _io.BufferedRandom |  |

**Returns**

| Тип | Описание |
| :- | :- |
| [FileFormat](/psd/python-net/aspose.psd/fileformat) |  |


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_13}


```
 get_fitting_rectangle(rectangle, pixels, width, height) 
```

  

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |
| pixels | int |  |
| width | int |  |
| height | int |  |

**Returns**

| Тип | Описание |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_14}


```
 get_fitting_rectangle(rectangle, width, height) 
```

  

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |
| width | int |  |
| height | int |  |

**Returns**

| Тип | Описание |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |


### Method: get_fonts() {#get_fonts__15}


```
 get_fonts() 
```

Получает набор шрифтов текстового слоя.

**Returns**

| Тип | Описание |
| :- | :- |
| [TextFontInfo[]](/psd/python-net/aspose.psd.fileformats.psd.layers.text/textfontinfo/) | Набор шрифтов текстового слоя. |


### Method: get_modify_date(use_default) {#get_modify_date_use_default_16}


```
 get_modify_date(use_default) 
```

  

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| use_default | bool |  |

**Returns**

| Тип | Описание |
| :- | :- |
| datetime |  |


### Method: get_original_options() {#get_original_options__17}


```
 get_original_options() 
```

  

**Returns**

| Тип | Описание |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) |  |


### Method: get_pixel(x, y) {#get_pixel_x_y_18}


```
 get_pixel(x, y) 
```

  

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | int |  |
| y | int |  |

**Returns**

| Тип | Описание |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) |  |


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_19}


```
 get_proportional_height(width, height, new_width) 
```

  

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| width | int |  |
| height | int |  |
| new_width | int |  |

**Returns**

| Тип | Описание |
| :- | :- |
| int |  |


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_20}


```
 get_proportional_width(width, height, new_height) 
```

  

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| width | int |  |
| height | int |  |
| new_height | int |  |

**Returns**

| Тип | Описание |
| :- | :- |
| int |  |


### Method: get_skew_angle() {#get_skew_angle__21}


```
 get_skew_angle() 
```

  

**Returns**

| Тип | Описание |
| :- | :- |
| float |  |


### Method: load(file_path)  [static] {#load_file_path_22}


```
 load(file_path) 
```

  

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | string |  |

**Returns**

| Тип | Описание |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) |  |


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_23}


```
 load(file_path, load_options) 
```

  

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | string |  |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) |  |

**Returns**

| Тип | Описание |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) |  |


### Method: load(stream)  [static] {#load_stream_24}


```
 load(stream) 
```

  

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| поток | _io.BufferedRandom |  |

**Returns**

| Тип | Описание |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) |  |


### Method: load(stream, load_options)  [static] {#load_stream_load_options_25}


```
 load(stream, load_options) 
```

  

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| поток | _io.BufferedRandom |  |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) |  |

**Returns**

| Тип | Описание |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) |  |


### Method: load_argb_32_pixels(rectangle) {#load_argb_32_pixels_rectangle_26}


```
 load_argb_32_pixels(rectangle) 
```

  

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |

**Returns**

| Тип | Описание |
| :- | :- |
| int |  |


### Method: load_argb_64_pixels(rectangle) {#load_argb_64_pixels_rectangle_27}


```
 load_argb_64_pixels(rectangle) 
```

  

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |

**Returns**

| Тип | Описание |
| :- | :- |
| long |  |


### Method: load_cmyk_32_pixels(rectangle) {#load_cmyk_32_pixels_rectangle_28}


```
 load_cmyk_32_pixels(rectangle) 
```

  

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |

**Returns**

| Тип | Описание |
| :- | :- |
| int |  |


### Method: load_cmyk_pixels(rectangle) {#load_cmyk_pixels_rectangle_29}


```
 load_cmyk_pixels(rectangle) 
```

  

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |

**Returns**

| Тип | Описание |
| :- | :- |
| [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) |  |


### Method: load_partial_argb_32_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_30}


```
 load_partial_argb_32_pixels(rectangle, partial_pixel_loader) 
```

Частично загружает 32‑битные ARGB‑пиксели (по блокам).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Прямоугольник, из которого загружать пиксели. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/psd/python-net/aspose.psd/ipartialargb32pixelloader) | Частичный загрузчик пикселей. |

### Method: load_pixels(rectangle) {#load_pixels_rectangle_31}


```
 load_pixels(rectangle) 
```

  

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |

**Returns**

| Тип | Описание |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) |  |


### Method: load_raw_data(rectangle, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_raw_data_settings_raw_data_loader_32}


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

### Method: read_argb_32_scan_line(scan_line_index) {#read_argb_32_scan_line_scan_line_index_33}


```
 read_argb_32_scan_line(scan_line_index) 
```

  

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| scan_line_index | int |  |

**Returns**

| Тип | Описание |
| :- | :- |
| int |  |


### Method: read_scan_line(scan_line_index) {#read_scan_line_scan_line_index_34}


```
 read_scan_line(scan_line_index) 
```

  

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| scan_line_index | int |  |

**Returns**

| Тип | Описание |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) |  |


### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_35}


```
 resize(new_width, new_height, resize_type) 
```

Изменяет размер изображения. По умолчанию используется [ResizeType.LEFT_TOP_TO_LEFT_TOP](/psd/python-net/aspose.psd/resizetype/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_width | int | Новая ширина. |
| new_height | int | Новая высота. |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | Тип трансформации изменения размера [ResizeType](/psd/python-net/aspose.psd/resizetype/) |

### Method: shallow_copy() {#shallow_copy__36}


```
 shallow_copy() 
```

  

**Returns**

| Тип | Описание |
| :- | :- |
| [Layer](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) |  |


### Method: to_bitmap() {#to_bitmap__37}


```
 to_bitmap() 
```

  

**Returns**

| Тип | Описание |
| :- | :- |
| aspose.pydrawing.Bitmap |  |


### Method: update_text(text) {#update_text_text_38}


```
 update_text(text) 
```

Обновляет текст.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| text | string | Значение текста. |

### Method: update_text(text, color) {#update_text_text_color_39}


```
 update_text(text, color) 
```

Обновляет текст.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| text | string | Значение текста. |
| color | [Color](/psd/python-net/aspose.psd/color) | Значение цвета. |

### Method: update_text(text, font_size) {#update_text_text_font_size_40}


```
 update_text(text, font_size) 
```

Обновляет текст.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| text | string | Значение текста. |
| font_size | float | Размер шрифта. |

### Method: update_text(text, font_size, color) {#update_text_text_font_size_color_41}


```
 update_text(text, font_size, color) 
```

Обновляет текст.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| text | string | Значение текста. |
| font_size | float | Размер шрифта. |
| color | [Color](/psd/python-net/aspose.psd/color) | Значение цвета. |

### Method: update_text(text, left_top_coordinate) {#update_text_text_left_top_coordinate_42}


```
 update_text(text, left_top_coordinate) 
```

Обновляет текст.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| text | string | Значение текста. |
| left_top_coordinate | [Point](/psd/python-net/aspose.psd/point) | Координата левого верхнего угла. |

### Method: update_text(text, left_top_coordinate, color) {#update_text_text_left_top_coordinate_color_43}


```
 update_text(text, left_top_coordinate, color) 
```

Обновляет текст.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| text | string | Значение текста. |
| left_top_coordinate | [Point](/psd/python-net/aspose.psd/point) | Координата левого верхнего угла. |
| color | [Color](/psd/python-net/aspose.psd/color) | Значение цвета. |

### Method: update_text(text, left_top_coordinate, font_size) {#update_text_text_left_top_coordinate_font_size_44}


```
 update_text(text, left_top_coordinate, font_size) 
```

Обновляет текст.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| text | string | Значение текста. |
| left_top_coordinate | [Point](/psd/python-net/aspose.psd/point) | Координата левого верхнего угла. |
| font_size | float | Размер шрифта. |

### Method: update_text(text, left_top_coordinate, font_size, color) {#update_text_text_left_top_coordinate_font_size_color_45}


```
 update_text(text, left_top_coordinate, font_size, color) 
```

Обновляет текст.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| text | string | Значение текста. |
| left_top_coordinate | [Point](/psd/python-net/aspose.psd/point) | Координата левого верхнего угла. |
| font_size | float | Размер шрифта. |
| color | [Color](/psd/python-net/aspose.psd/color) | Значение цвета. |

