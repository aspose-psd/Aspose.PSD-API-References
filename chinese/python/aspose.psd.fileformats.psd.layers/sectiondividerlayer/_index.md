---
title: "SectionDividerLayer 类"
type: docs
weight: 1580
url: /zh/python-net/aspose.psd.fileformats.psd.layers/sectiondividerlayer/
---

**Summary:** The section divider layer to mark the bounds of the folder (layer group).

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.SectionDividerLayer

**Inheritance:** IObjectWithBounds, IRasterImageArgb32PixelLoader, IRasterImageRawDataLoader, Layer

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| BLEND_SIGNATURE [static] | int | r |  |
| LAYER_HEADER_SIZE [static] | int | r |  |
| auto_adjust_palette | bool | 读/写 |  |
| background_color | [Color](/psd/python-net/aspose.psd/color) | r/w |    |
| bits_per_pixel | int | r |  |
| blend_clipped_elements | bool | 读/写 |  |
| blend_mode_key | [BlendMode](/psd/python-net/aspose.psd.fileformats.core.blending/blendmode/) | r/w |    |
| blend_mode_signature | int | r |  |
| blending_options | [BlendingOptions](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/) | r |    |
| 底部 | int | 读/写 |  |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | 获取对象边界。 |
| buffer_size_hint | int | 读/写 |  |
| channel_information | [ChannelInformation[]](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | r/w |    |
| channels_count | ushort | r |  |
| clipping | byte | 读/写 |  |
| container | [Image](/psd/python-net/aspose.psd/image) | r |    |
| data_stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | r |    |
| display_name | 字符串 | 读/写 |  |
| 已释放 | bool | r |  |
| 额外长度 | int | r |  |
| file_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r |    |
| 填充不透明度 | int | 读/写 |  |
| 填充器 | byte | 读/写 |  |
| flags | [LayerFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layerflags) | r/w |    |
| has_alpha | bool | r |  |
| has_background_color | bool | 读/写 |  |
| has_transparent_color | bool | 读/写 |  |
| height | int | r | 获取对象的高度。 |
| horizontal_resolution | double | 读/写 |  |
| image_opacity | float | r |  |
| interrupt_monitor | [InterruptMonitor](/psd/python-net/aspose.psd.multithreading/interruptmonitor/) | r/w |    |
| is_cached | bool | r |  |
| is_raw_data_available | bool | r | 获取指示是否支持原始数据加载的值。 |
| is_visible | bool | 读/写 |  |
| is_visible_in_group | bool | r | 获取一个值，指示此实例在组中是否可见（如果图层不在组中，则表示根组）。 |
| layer_blending_ranges_data | [LayerBlendingRangesData](/psd/python-net/aspose.psd.fileformats.psd.layers/layerblendingrangesdata) | r/w |    |
| layer_creation_date_time | datetime | 读/写 |  |
| layer_lock | [LayerLockType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/layerlocktype/) | r/w |    |
| layer_mask_data | [LayerMaskData](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata) | r/w |    |
| layer_options | [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/) | r |    |
| left | int | 读/写 |  |
| 长度 | int | r |  |
| name | 字符串 | 读/写 | 获取或设置文本层的名称。 |
| opacity | byte | 读/写 |  |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w |    |
| premultiply_components | bool | 读/写 |  |
| raw_custom_color_converter | [IColorConverter](/psd/python-net/aspose.psd/icolorconverter) | r/w |    |
| raw_data_format | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r |    |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | r | 获取当前的原始数据设置。注意，使用这些设置时，数据将在不进行转换的情况下加载。 |
| raw_fallback_index | int | 读/写 |  |
| raw_indexed_color_converter | [IIndexedColorConverter](/psd/python-net/aspose.psd/iindexedcolorconverter) | r/w |    |
| raw_line_size | int | r |  |
| resources | [LayerResource[]](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource) | r/w |    |
| right | int | 读/写 |  |
| sheet_color_highlight | [SheetColorHighlightEnum](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/sheetcolorhighlightenum/) | r/w |    |
| size | [Size](/psd/python-net/aspose.psd/size) | r | 获取对象的大小。 |
| top | int | 读/写 |  |
| transparent_color | [Color](/psd/python-net/aspose.psd/color) | r/w |    |
| update_xmp_data | bool | 读/写 |  |
| use_palette | bool | r |  |
| use_raw_data | bool | 读/写 |  |
| vertical_resolution | double | 读/写 |  |
| width | int | r | 获取对象宽度。 |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w |    |
## **Methods**
| **Name** | **Description** |
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
| [get_modify_date(use_default)](#get_modify_date_use_default_15) |    |
| [get_original_options()](#get_original_options__16) |    |
| [get_pixel(x, y)](#get_pixel_x_y_17) |    |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_18) |    |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_19) |    |
| [get_related_layer_group()](#get_related_layer_group__20) | 获取与此 [SectionDividerLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/sectiondividerlayer/) 实例相关的 [LayerGroup](/psd/python-net/aspose.psd.fileformats.psd.layers/layergroup/)。 |
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
| [load_partial_argb_32_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_30) | 部分加载 32 位 ARGB 像素（按块）。 |
| load_partial_pixels(desired_rectangle, pixel_loader) |  |
| [load_pixels(rectangle)](#load_pixels_rectangle_31) |    |
| load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) |  |
| [load_raw_data(rectangle, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_raw_data_settings_raw_data_loader_32) | 加载原始数据。 |
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
| resize(new_width, new_height, resize_type) |  |
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
| [shallow_copy()](#shallow_copy__35) |    |
| [to_bitmap()](#to_bitmap__36) |    |
| write_argb_32_scan_line(scan_line_index, argb_32_pixels) |  |
| write_scan_line(scan_line_index, pixels) |  |


### Method: can_load(file_path)  [static] {#can_load_file_path_1}


```
 can_load(file_path) 
```

  

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| file_path | 字符串 |  |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool |  |


### Method: can_load(file_path, load_options)  [static] {#can_load_file_path_load_options_2}


```
 can_load(file_path, load_options) 
```

  

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| file_path | 字符串 |  |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) |  |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool |  |


### Method: can_load(stream)  [static] {#can_load_stream_3}


```
 can_load(stream) 
```

  

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 流 | _io.BufferedRandom |  |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool |  |


### Method: can_load(stream, load_options)  [static] {#can_load_stream_load_options_4}


```
 can_load(stream, load_options) 
```

  

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 流 | _io.BufferedRandom |  |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) |  |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool |  |


### Method: can_save(options) {#can_save_options_5}


```
 can_save(options) 
```

  

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) |  |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool |  |


### Method: create(image_options, width, height)  [static] {#create_image_options_width_height_6}


```
 create(image_options, width, height) 
```

  

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) |  |
| width | int |  |
| height | int |  |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) |  |


### Method: get_argb_32_pixel(x, y) {#get_argb_32_pixel_x_y_7}


```
 get_argb_32_pixel(x, y) 
```

  

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| x | int |  |
| y | int |  |

**Returns**

| 类型 | 描述 |
| :- | :- |
| int |  |


### Method: get_default_argb_32_pixels(rectangle) {#get_default_argb_32_pixels_rectangle_8}


```
 get_default_argb_32_pixels(rectangle) 
```

  

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |

**Returns**

| 类型 | 描述 |
| :- | :- |
| int |  |


### Method: get_default_options(args) {#get_default_options_args_9}


```
 get_default_options(args) 
```

  

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| args | object |  |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) |  |


### Method: get_default_raw_data(rectangle, raw_data_settings) {#get_default_raw_data_rectangle_raw_data_settings_10}


```
 get_default_raw_data(rectangle, raw_data_settings) 
```

  

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) |  |

**Returns**

| 类型 | 描述 |
| :- | :- |
| byte |  |


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_11}


```
 get_file_format(file_path) 
```

  

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| file_path | 字符串 |  |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [FileFormat](/psd/python-net/aspose.psd/fileformat) |  |


### Method: get_file_format(stream)  [static] {#get_file_format_stream_12}


```
 get_file_format(stream) 
```

  

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 流 | _io.BufferedRandom |  |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [FileFormat](/psd/python-net/aspose.psd/fileformat) |  |


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_13}


```
 get_fitting_rectangle(rectangle, pixels, width, height) 
```

  

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |
| pixels | int |  |
| width | int |  |
| height | int |  |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_14}


```
 get_fitting_rectangle(rectangle, width, height) 
```

  

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |
| width | int |  |
| height | int |  |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |


### Method: get_modify_date(use_default) {#get_modify_date_use_default_15}


```
 get_modify_date(use_default) 
```

  

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| use_default | bool |  |

**Returns**

| 类型 | 描述 |
| :- | :- |
| datetime |  |


### Method: get_original_options() {#get_original_options__16}


```
 get_original_options() 
```

  

**Returns**

| 类型 | 描述 |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) |  |


### Method: get_pixel(x, y) {#get_pixel_x_y_17}


```
 get_pixel(x, y) 
```

  

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| x | int |  |
| y | int |  |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) |  |


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_18}


```
 get_proportional_height(width, height, new_width) 
```

  

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| width | int |  |
| height | int |  |
| new_width | int |  |

**Returns**

| 类型 | 描述 |
| :- | :- |
| int |  |


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_19}


```
 get_proportional_width(width, height, new_height) 
```

  

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| width | int |  |
| height | int |  |
| new_height | int |  |

**Returns**

| 类型 | 描述 |
| :- | :- |
| int |  |


### Method: get_related_layer_group() {#get_related_layer_group__20}


```
 get_related_layer_group() 
```

获取与此 [SectionDividerLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/sectiondividerlayer/) 实例相关的 [LayerGroup](/psd/python-net/aspose.psd.fileformats.psd.layers/layergroup/)。

**Returns**

| 类型 | 描述 |
| :- | :- |
| [LayerGroup](/psd/python-net/aspose.psd.fileformats.psd.layers/layergroup) | 该 [LayerGroup](/psd/python-net/aspose.psd.fileformats.psd.layers/layergroup/) 实例。 |


### Method: get_skew_angle() {#get_skew_angle__21}


```
 get_skew_angle() 
```

  

**Returns**

| 类型 | 描述 |
| :- | :- |
| float |  |


### Method: load(file_path)  [static] {#load_file_path_22}


```
 load(file_path) 
```

  

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| file_path | 字符串 |  |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) |  |


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_23}


```
 load(file_path, load_options) 
```

  

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| file_path | 字符串 |  |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) |  |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) |  |


### Method: load(stream)  [static] {#load_stream_24}


```
 load(stream) 
```

  

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 流 | _io.BufferedRandom |  |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) |  |


### Method: load(stream, load_options)  [static] {#load_stream_load_options_25}


```
 load(stream, load_options) 
```

  

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 流 | _io.BufferedRandom |  |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) |  |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) |  |


### Method: load_argb_32_pixels(rectangle) {#load_argb_32_pixels_rectangle_26}


```
 load_argb_32_pixels(rectangle) 
```

  

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |

**Returns**

| 类型 | 描述 |
| :- | :- |
| int |  |


### Method: load_argb_64_pixels(rectangle) {#load_argb_64_pixels_rectangle_27}


```
 load_argb_64_pixels(rectangle) 
```

  

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |

**Returns**

| 类型 | 描述 |
| :- | :- |
| long |  |


### Method: load_cmyk_32_pixels(rectangle) {#load_cmyk_32_pixels_rectangle_28}


```
 load_cmyk_32_pixels(rectangle) 
```

  

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |

**Returns**

| 类型 | 描述 |
| :- | :- |
| int |  |


### Method: load_cmyk_pixels(rectangle) {#load_cmyk_pixels_rectangle_29}


```
 load_cmyk_pixels(rectangle) 
```

  

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) |  |


### Method: load_partial_argb_32_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_30}


```
 load_partial_argb_32_pixels(rectangle, partial_pixel_loader) 
```

部分加载 32 位 ARGB 像素（按块）。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 用于加载像素的矩形。 |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/psd/python-net/aspose.psd/ipartialargb32pixelloader) | 部分像素加载器。 |

### Method: load_pixels(rectangle) {#load_pixels_rectangle_31}


```
 load_pixels(rectangle) 
```

  

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) |  |


### Method: load_raw_data(rectangle, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_raw_data_settings_raw_data_loader_32}


```
 load_raw_data(rectangle, raw_data_settings, raw_data_loader) 
```

加载原始数据。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 用于加载原始数据的矩形。 |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | 用于已加载数据的原始数据设置。注意，如果数据不是指定的格式，则会执行数据转换。 |
| raw_data_loader | [IPartialRawDataLoader](/psd/python-net/aspose.psd/ipartialrawdataloader) | 原始数据加载器。 |

### Method: read_argb_32_scan_line(scan_line_index) {#read_argb_32_scan_line_scan_line_index_33}


```
 read_argb_32_scan_line(scan_line_index) 
```

  

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| scan_line_index | int |  |

**Returns**

| 类型 | 描述 |
| :- | :- |
| int |  |


### Method: read_scan_line(scan_line_index) {#read_scan_line_scan_line_index_34}


```
 read_scan_line(scan_line_index) 
```

  

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| scan_line_index | int |  |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) |  |


### Method: shallow_copy() {#shallow_copy__35}


```
 shallow_copy() 
```

  

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Layer](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) |  |


### Method: to_bitmap() {#to_bitmap__36}


```
 to_bitmap() 
```

  

**Returns**

| 类型 | 描述 |
| :- | :- |
| aspose.pydrawing.Bitmap |  |


