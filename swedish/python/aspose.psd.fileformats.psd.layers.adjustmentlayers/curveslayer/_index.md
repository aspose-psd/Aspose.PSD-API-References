---
title: "CurvesLayer klass"
type: docs
weight: 90
url: /sv/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/curveslayer/
---

**Summary:** Curves Adjustment Layer

**Module:** [aspose.psd.fileformats.psd.layers.adjustmentlayers](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/)

**Full Name:** aspose.psd.fileformats.psd.layers.adjustmentlayers.CurvesLayer

**Inheritance:** IObjectWithBounds, IRasterImageArgb32PixelLoader, IRasterImageRawDataLoader, AdjustmentLayer

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
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
| nedre | int | r/w |  |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | Hämtar objektets gränser. |
| buffer_size_hint | int | r/w |  |
| channel_information | [ChannelInformation[]](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | r/w |    |
| channels_count | ushort | r |  |
| clipping | byte | r/w |  |
| container | [Image](/psd/python-net/aspose.psd/image) | r |    |
| data_stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | r |    |
| display_name | string | r/w |  |
| borttagen | bool | r |  |
| extra_length | int | r |  |
| file_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r |    |
| fill_opacity | int | r/w |  |
| filler | byte | r/w |  |
| flags | [LayerFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layerflags) | r/w |    |
| has_alpha | bool | r |  |
| has_background_color | bool | r/w |  |
| has_transparent_color | bool | r/w |  |
| height | int | r | Hämtar objektets höjd. |
| horizontal_resolution | double | r/w |  |
| image_opacity | float | r |  |
| interrupt_monitor | [InterruptMonitor](/psd/python-net/aspose.psd.multithreading/interruptmonitor/) | r/w |    |
| is_cached | bool | r |  |
| is_continuous_manager_used | bool | r/w | Hämtar eller anger ett värde som indikerar om denna instans använder en kontinuerlig manager. |
| is_discrete_manager_used | bool | r/w | Hämtar eller anger ett värde som indikerar om denna instans använder en diskret manager. |
| is_raw_data_available | bool | r | Hämtar ett värde som indikerar om inläsning av rådata stöds. |
| is_visible | bool | r/w |  |
| is_visible_in_group | bool | r |  |
| layer_blending_ranges_data | [LayerBlendingRangesData](/psd/python-net/aspose.psd.fileformats.psd.layers/layerblendingrangesdata) | r/w |    |
| layer_creation_date_time | datetime | r/w |  |
| layer_lock | [LayerLockType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/layerlocktype/) | r/w |    |
| layer_mask_data | [LayerMaskData](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata) | r/w |    |
| layer_options | [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/) | r |    |
| vänster | int | r/w |  |
| längd | int | r |  |
| name | string | r/w | Hämtar eller anger namnet på textlagret. |
| opacity | byte | r/w |  |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w |    |
| premultiply_components | bool | r/w |  |
| raw_custom_color_converter | [IColorConverter](/psd/python-net/aspose.psd/icolorconverter) | r/w |    |
| raw_data_format | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r |    |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | r | Hämtar de aktuella rådatainställningarna. Observera att när dessa inställningar används laddas data utan konvertering. |
| raw_fallback_index | int | r/w |  |
| raw_indexed_color_converter | [IIndexedColorConverter](/psd/python-net/aspose.psd/iindexedcolorconverter) | r/w |    |
| raw_line_size | int | r |  |
| resources | [LayerResource[]](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource) | r/w |    |
| höger | int | r/w |  |
| sheet_color_highlight | [SheetColorHighlightEnum](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/sheetcolorhighlightenum/) | r/w |    |
| size | [Size](/psd/python-net/aspose.psd/size) | r | Hämtar objektets storlek. |
| övre | int | r/w |  |
| transparent_color | [Color](/psd/python-net/aspose.psd/color) | r/w |    |
| update_xmp_data | bool | r/w |  |
| use_palette | bool | r |  |
| use_raw_data | bool | r/w |  |
| vertical_resolution | double | r/w |  |
| width | int | r | Hämtar objektets bredd. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w |    |
## **Methods**
| **Name** | **Beskrivning** |
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
| [get_curves_manager()](#get_curves_manager__8) | Hämtar kurvhanteraren. |
| [get_default_argb_32_pixels(rectangle)](#get_default_argb_32_pixels_rectangle_9) |    |
| [get_default_options(args)](#get_default_options_args_10) |    |
| get_default_pixels(rectangle, partial_pixel_loader) |  |
| get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) |  |
| [get_default_raw_data(rectangle, raw_data_settings)](#get_default_raw_data_rectangle_raw_data_settings_11) |    |
| [get_file_format(file_path)](#get_file_format_file_path_12) |    |
| [get_file_format(stream)](#get_file_format_stream_13) |    |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_14) |    |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_15) |    |
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
| [load_partial_argb_32_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_30) | Laddar 32‑bitars ARGB‑pixlar delvis (i block). |
| load_partial_pixels(desired_rectangle, pixel_loader) |  |
| [load_pixels(rectangle)](#load_pixels_rectangle_31) |    |
| load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) |  |
| [load_raw_data(rectangle, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_raw_data_settings_raw_data_loader_32) | Laddar rådata. |
| [merge_layer_to(layer_to_merge_into)](#merge_layer_to_layer_to_merge_into_33) | Slår samman lagret med angivet lager. |
| normalize_angle() |  |
| normalize_angle(resize_proportionally, background_color) |  |
| [read_argb_32_scan_line(scan_line_index)](#read_argb_32_scan_line_scan_line_index_34) |    |
| [read_scan_line(scan_line_index)](#read_scan_line_scan_line_index_35) |    |
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
| [shallow_copy()](#shallow_copy__36) |    |
| [to_bitmap()](#to_bitmap__37) |    |
| write_argb_32_scan_line(scan_line_index, argb_32_pixels) |  |
| write_scan_line(scan_line_index, pixels) |  |


### Method: can_load(file_path)  [static] {#can_load_file_path_1}


```
 can_load(file_path) 
```

  

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | string |  |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool |  |


### Method: can_load(file_path, load_options)  [static] {#can_load_file_path_load_options_2}


```
 can_load(file_path, load_options) 
```

  

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | string |  |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) |  |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool |  |


### Method: can_load(stream)  [static] {#can_load_stream_3}


```
 can_load(stream) 
```

  

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream | _io.BufferedRandom |  |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool |  |


### Method: can_load(stream, load_options)  [static] {#can_load_stream_load_options_4}


```
 can_load(stream, load_options) 
```

  

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream | _io.BufferedRandom |  |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) |  |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool |  |


### Method: can_save(options) {#can_save_options_5}


```
 can_save(options) 
```

  

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) |  |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool |  |


### Method: create(image_options, width, height)  [static] {#create_image_options_width_height_6}


```
 create(image_options, width, height) 
```

  

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) |  |
| width | int |  |
| height | int |  |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) |  |


### Method: get_argb_32_pixel(x, y) {#get_argb_32_pixel_x_y_7}


```
 get_argb_32_pixel(x, y) 
```

  

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| x | int |  |
| y | int |  |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int |  |


### Method: get_curves_manager() {#get_curves_manager__8}


```
 get_curves_manager() 
```

Hämtar kurvhanteraren.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [CurvesManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvesmanager/) | [CurvesDiscreteManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvesdiscretemanager/) eller [CurvesContinuousManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager/) som beror på egenskapen IsDiscreteManagerUsed och IsContinuousManagerUsed |


### Method: get_default_argb_32_pixels(rectangle) {#get_default_argb_32_pixels_rectangle_9}


```
 get_default_argb_32_pixels(rectangle) 
```

  

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int |  |


### Method: get_default_options(args) {#get_default_options_args_10}


```
 get_default_options(args) 
```

  

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| args | object |  |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) |  |


### Method: get_default_raw_data(rectangle, raw_data_settings) {#get_default_raw_data_rectangle_raw_data_settings_11}


```
 get_default_raw_data(rectangle, raw_data_settings) 
```

  

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) |  |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| byte |  |


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_12}


```
 get_file_format(file_path) 
```

  

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | string |  |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [FileFormat](/psd/python-net/aspose.psd/fileformat) |  |


### Method: get_file_format(stream)  [static] {#get_file_format_stream_13}


```
 get_file_format(stream) 
```

  

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream | _io.BufferedRandom |  |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [FileFormat](/psd/python-net/aspose.psd/fileformat) |  |


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_14}


```
 get_fitting_rectangle(rectangle, pixels, width, height) 
```

  

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |
| pixlar | int |  |
| width | int |  |
| height | int |  |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_15}


```
 get_fitting_rectangle(rectangle, width, height) 
```

  

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |
| width | int |  |
| height | int |  |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |


### Method: get_modify_date(use_default) {#get_modify_date_use_default_16}


```
 get_modify_date(use_default) 
```

  

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| use_default | bool |  |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| datetime |  |


### Method: get_original_options() {#get_original_options__17}


```
 get_original_options() 
```

  

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) |  |


### Method: get_pixel(x, y) {#get_pixel_x_y_18}


```
 get_pixel(x, y) 
```

  

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| x | int |  |
| y | int |  |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) |  |


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_19}


```
 get_proportional_height(width, height, new_width) 
```

  

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| width | int |  |
| height | int |  |
| new_width | int |  |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int |  |


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_20}


```
 get_proportional_width(width, height, new_height) 
```

  

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| width | int |  |
| height | int |  |
| new_height | int |  |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int |  |


### Method: get_skew_angle() {#get_skew_angle__21}


```
 get_skew_angle() 
```

  

**Returns**

| Typ | Beskrivning |
| :- | :- |
| float |  |


### Method: load(file_path)  [static] {#load_file_path_22}


```
 load(file_path) 
```

  

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | string |  |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) |  |


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_23}


```
 load(file_path, load_options) 
```

  

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | string |  |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) |  |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) |  |


### Method: load(stream)  [static] {#load_stream_24}


```
 load(stream) 
```

  

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream | _io.BufferedRandom |  |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) |  |


### Method: load(stream, load_options)  [static] {#load_stream_load_options_25}


```
 load(stream, load_options) 
```

  

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream | _io.BufferedRandom |  |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) |  |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) |  |


### Method: load_argb_32_pixels(rectangle) {#load_argb_32_pixels_rectangle_26}


```
 load_argb_32_pixels(rectangle) 
```

  

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int |  |


### Method: load_argb_64_pixels(rectangle) {#load_argb_64_pixels_rectangle_27}


```
 load_argb_64_pixels(rectangle) 
```

  

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| long |  |


### Method: load_cmyk_32_pixels(rectangle) {#load_cmyk_32_pixels_rectangle_28}


```
 load_cmyk_32_pixels(rectangle) 
```

  

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int |  |


### Method: load_cmyk_pixels(rectangle) {#load_cmyk_pixels_rectangle_29}


```
 load_cmyk_pixels(rectangle) 
```

  

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) |  |


### Method: load_partial_argb_32_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_30}


```
 load_partial_argb_32_pixels(rectangle, partial_pixel_loader) 
```

Laddar 32‑bitars ARGB‑pixlar delvis (i block).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Rektangeln att ladda pixlar från. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/psd/python-net/aspose.psd/ipartialargb32pixelloader) | Den partiella pixel‑laddaren. |

### Method: load_pixels(rectangle) {#load_pixels_rectangle_31}


```
 load_pixels(rectangle) 
```

  

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) |  |


### Method: load_raw_data(rectangle, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_raw_data_settings_raw_data_loader_32}


```
 load_raw_data(rectangle, raw_data_settings, raw_data_loader) 
```

Laddar rådata.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Rektangeln att ladda rådata från. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | Rådatainställningarna att använda för laddade data. Observera att om data inte är i det angivna formatet kommer datakonvertering att utföras. |
| raw_data_loader | [IPartialRawDataLoader](/psd/python-net/aspose.psd/ipartialrawdataloader) | Rådata‑laddaren. |

### Method: merge_layer_to(layer_to_merge_into) {#merge_layer_to_layer_to_merge_into_33}


```
 merge_layer_to(layer_to_merge_into) 
```

Slår samman lagret med angivet lager.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| layer_to_merge_into | [Layer](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | Lagret att slå samman med. |

### Method: read_argb_32_scan_line(scan_line_index) {#read_argb_32_scan_line_scan_line_index_34}


```
 read_argb_32_scan_line(scan_line_index) 
```

  

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| scan_line_index | int |  |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int |  |


### Method: read_scan_line(scan_line_index) {#read_scan_line_scan_line_index_35}


```
 read_scan_line(scan_line_index) 
```

  

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| scan_line_index | int |  |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) |  |


### Method: shallow_copy() {#shallow_copy__36}


```
 shallow_copy() 
```

  

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Layer](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) |  |


### Method: to_bitmap() {#to_bitmap__37}


```
 to_bitmap() 
```

  

**Returns**

| Typ | Beskrivning |
| :- | :- |
| aspose.pydrawing.Bitmap |  |


