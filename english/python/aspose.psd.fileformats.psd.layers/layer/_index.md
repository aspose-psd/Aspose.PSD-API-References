---
title: Layer Class
type: docs
weight: 930
url: /python-net/aspose.psd.fileformats.psd.layers/layer/
---

**Summary:** The psd layer.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.Layer

**Inheritance:** IObjectWithBounds, IRasterImageArgb32PixelLoader, IRasterImageRawDataLoader, RasterCachedImage

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Layer()](#Layer__1) | Initializes a new instance of the [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) class. Constructor for lazy initialization. |
| [Layer(bounds, red_bytes, green_bytes, blue_bytes, name)](#Layer_bounds_red_bytes_green_bytes_blue_bytes_name_2) | Initializes a new instance of the [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) class from byte arrays. |
| [Layer(image, dispose_image)](#Layer_image_dispose_image_3) | Initializes a new instance of the [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) class. |
| [Layer(stream)](#Layer_stream_4) | Initializes a new instance of the [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| BLEND_SIGNATURE [static] | int | r | Represents blend mode signature. |
| LAYER_HEADER_SIZE [static] | int | r | The layer header size. |
| auto_adjust_palette | bool | r/w | Gets or sets a value indicating whether automatic adjust palette. |
| background_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Gets or sets a value for the background color. |
| bits_per_pixel | int | r | Gets the image bits per pixel count. |
| blend_clipped_elements | bool | r/w | Gets or sets the blending of clipped element. |
| blend_mode_key | [BlendMode](/psd/python-net/aspose.psd.fileformats.core.blending/blendmode/) | r/w | Gets or sets the blend mode key. |
| blend_mode_signature | int | r | Gets the blend mode signature. |
| blending_options | [BlendingOptions](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/) | r | Gets the blending options. |
| bottom | int | r/w | Gets or sets the bottom layer position. |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | Gets the object bounds. |
| buffer_size_hint | int | r/w | Gets or sets the buffer size hint which is defined max allowed size for all internal buffers. |
| channel_information | [ChannelInformation[]](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | r/w | Gets or sets the channel information. |
| channels_count | ushort | r | Gets the layer's channels count. |
| clipping | byte | r/w | Gets or sets the layer clipping. 0 = base, 1 = non-base. |
| container | [Image](/psd/python-net/aspose.psd/image) | r | Gets the [Image](/psd/python-net/aspose.psd/image/) container. |
| data_stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | r | Gets the object's data stream. |
| display_name | string | r/w | Gets or sets the display name of the layer. |
| disposed | bool | r | Gets a value indicating whether this instance is disposed. |
| extra_length | int | r | Gets the layer extra information length in bytes. |
| file_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | Gets a value of file format |
| fill_opacity | int | r/w | Gets or sets the fill opacity. |
| filler | byte | r/w | Gets or sets the layer filler. |
| flags | [LayerFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layerflags) | r/w | Gets or sets the layer flags.<br/>            bit 0 = transparency protected;<br/>            bit 1 = visible;<br/>            bit 2 = obsolete;<br/>            bit 3 = 1 for Photoshop 5.0 and later, tells if bit 4 has useful information;<br/>            bit 4 = pixel data irrelevant to appearance of document. |
| has_alpha | bool | r | Gets a value indicating whether this instance has alpha. |
| has_background_color | bool | r/w | Gets or sets a value indicating whether image has background color. |
| has_transparent_color | bool | r/w | Gets a value indicating whether image has transparent color. |
| height | int | r | Gets the image height. |
| horizontal_resolution | double | r/w | Gets or sets the horizontal resolution, in pixels per inch, of this [RasterImage](/psd/python-net/aspose.psd/rasterimage/). |
| image_opacity | float | r | Gets opacity of this image. |
| interrupt_monitor | [InterruptMonitor](/psd/python-net/aspose.psd.multithreading/interruptmonitor/) | r/w | Gets or sets the interrupt monitor. |
| is_cached | bool | r | Gets a value indicating whether image data is cached currently. |
| is_raw_data_available | bool | r | Gets a value indicating whether raw data loading is supported. |
| is_visible | bool | r/w | Gets or sets a value indicating whether the layer is visible |
| is_visible_in_group | bool | r | Gets a value indicating whether this instance is visible in group(If layer is not in group it means root group). |
| layer_blending_ranges_data | [LayerBlendingRangesData](/psd/python-net/aspose.psd.fileformats.psd.layers/layerblendingrangesdata) | r/w | Gets or sets the layer blending ranges data. |
| layer_creation_date_time | datetime | r/w | Gets or sets the layer creation date time. |
| layer_lock | [LayerLockType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/layerlocktype/) | r/w | Gets or sets the layer lock.<br/>            Note that if flag LayerFlags.TransparencyProtected is set it will be overwritten by layer lock flag.<br/>            To return LayerFlags.TransparencyProtected flag need to apply for layer option layer.Flags |= LayerFlags.TransparencyProtected |
| layer_mask_data | [LayerMaskData](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata) | r/w | Gets or sets the layer mask data. |
| layer_options | [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/) | r | Gets the layer options. |
| left | int | r/w | Gets or sets the left layer position. |
| length | int | r | Gets the overall layer length in bytes. |
| name | string | r/w | Gets or sets the layer name. |
| opacity | byte | r/w | Gets or sets the layer opacity. 0 = transparent, 255 = opaque. |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Gets or sets the color palette. The color palette is not used when pixels are represented directly. |
| premultiply_components | bool | r/w | Gets or sets a value indicating whether the image components must be premultiplied. |
| raw_custom_color_converter | [IColorConverter](/psd/python-net/aspose.psd/icolorconverter) | r/w | Gets or sets the custom color converter |
| raw_data_format | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | Gets the raw data format. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | r | Gets the current raw data settings. Note when using these settings the data loads without conversion. |
| raw_fallback_index | int | r/w | Gets or sets the fallback index to use when palette index is out of bounds |
| raw_indexed_color_converter | [IIndexedColorConverter](/psd/python-net/aspose.psd/iindexedcolorconverter) | r/w | Gets or sets the indexed color converter |
| raw_line_size | int | r | Gets the raw line size in bytes. |
| resources | [LayerResource[]](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource) | r/w | Gets or sets the layer resources. |
| right | int | r/w | Gets or sets the right layer position. |
| sheet_color_highlight | [SheetColorHighlightEnum](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/sheetcolorhighlightenum/) | r/w | Gets or sets the decorative sheet color highlight in layers' list |
| size | [Size](/psd/python-net/aspose.psd/size) | r | Gets the object size. |
| top | int | r/w | Gets or sets the top layer position. |
| transparent_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Gets the image transparent color. |
| update_xmp_data | bool | r/w | Gets or sets a value indicating whether to update the XMP metadata. |
| use_palette | bool | r | Gets a value indicating whether the image palette is used. |
| use_raw_data | bool | r/w | Gets or sets a value indicating whether to use raw data loading when the raw data loading is available. |
| vertical_resolution | double | r/w | Gets or sets the vertical resolution, in pixels per inch, of this [RasterImage](/psd/python-net/aspose.psd/rasterimage/). |
| width | int | r | Gets the image width. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | Gets or sets the XMP metadata. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_layer_mask(layer_mask)](#add_layer_mask_layer_mask_1) | Adds the mask to current layer. |
| [adjust_brightness(brightness)](#adjust_brightness_brightness_2) | Adjust of a brightness for image. |
| [adjust_contrast(contrast)](#adjust_contrast_contrast_3) | Image contrasting |
| [adjust_gamma(gamma)](#adjust_gamma_gamma_4) | Gamma-correction of an image. |
| [adjust_gamma(gamma_red, gamma_green, gamma_blue)](#adjust_gamma_gamma_red_gamma_green_gamma_blue_5) | Gamma-correction of an image. |
| [binarize_bradley(brightness_difference)](#binarize_bradley_brightness_difference_6) | Binarization of an image using Bradley's adaptive thresholding algorithm using the integral image thresholding |
| [binarize_bradley(brightness_difference, window_size)](#binarize_bradley_brightness_difference_window_size_7) | Binarization of an image using Bradley's adaptive thresholding algorithm using the integral image thresholding |
| [binarize_fixed(threshold)](#binarize_fixed_threshold_8) | Binarization of an image with predefined threshold |
| binarize_otsu() | Binarization of an image with Otsu thresholding |
| cache_data() | Caches the data and ensures no additional data loading will be performed from the underlying [DataStreamSupporter.data_stream_container](/psd/python-net/aspose.psd/datastreamsupporter/). |
| [can_load(file_path)](#can_load_file_path_9) | Determines whether image can be loaded from the specified file path. |
| [can_load(file_path, load_options)](#can_load_file_path_load_options_10) | Determines whether image can be loaded from the specified file path and optionally using the specified open options. |
| [can_load(stream)](#can_load_stream_11) | Determines whether image can be loaded from the specified stream. |
| [can_load(stream, load_options)](#can_load_stream_load_options_12) | Determines whether image can be loaded from the specified stream and optionally using the specified <paramref name="loadOptions" />. |
| [can_save(options)](#can_save_options_13) | Determines whether image can be saved to the specified file format represented by the passed save options. |
| [create(image_options, width, height)](#create_image_options_width_height_14) | Creates a new image using the specified create options. |
| crop(left_shift, right_shift, top_shift, bottom_shift) |    |
| [crop(rectangle)](#crop_rectangle_15) | Cropping the image. |
| [dither(dithering_method, bits_count)](#dither_dithering_method_bits_count_16) | Performs dithering on the current image. |
| [dither(dithering_method, bits_count, custom_palette)](#dither_dithering_method_bits_count_custom_palette_17) | Performs dithering on the current image. |
| [draw_image(location, image)](#draw_image_location_image_18) | Draws the image on layer. |
| filter(rectangle, options) |    |
| [get_argb_32_pixel(x, y)](#get_argb_32_pixel_x_y_19) | Gets an image 32-bit ARGB pixel. |
| [get_default_argb_32_pixels(rectangle)](#get_default_argb_32_pixels_rectangle_20) | Gets the default 32-bit ARGB pixels array. |
| [get_default_options(args)](#get_default_options_args_21) | Gets the default options. |
| [get_default_pixels(rectangle, partial_pixel_loader)](#get_default_pixels_rectangle_partial_pixel_loader_22) | Gets the default pixels array using partial pixel loader. |
| [get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings)](#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_23) | Gets the default raw data array using partial pixel loader. |
| [get_default_raw_data(rectangle, raw_data_settings)](#get_default_raw_data_rectangle_raw_data_settings_24) | Gets the default raw data array. |
| [get_file_format(file_path)](#get_file_format_file_path_25) | Gets the file format. |
| [get_file_format(stream)](#get_file_format_stream_26) | Gets the file format. |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_27) | Gets rectangle which fits the current image. |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_28) | Gets rectangle which fits the current image. |
| [get_modify_date(use_default)](#get_modify_date_use_default_29) | Gets the date and time the resource image was last modified. |
| [get_original_options()](#get_original_options__30) | Gets the options based on the original file settings.<br/>            This can be helpful to keep bit-depth and other parameters of the original image unchanged.<br/>            For example, if we load a black-white PNG image with 1 bit per pixel and then save it using the<br/>            [DataStreamSupporter.save(file_path)](/psd/python-net/aspose.psd/datastreamsupporter/) method, the output PNG image with 8-bit per pixel will be produced.<br/>            To avoid it and save PNG image with 1-bit per pixel, use this method to get corresponding saving options and pass them<br/>            to the [Image.save(file_path, options)](/psd/python-net/aspose.psd/image/) method as the second parameter. |
| [get_pixel(x, y)](#get_pixel_x_y_31) | Gets an image pixel.<br/>            Performance Warning: Avoid using this method to iterate over all image pixels as it can lead to significant performance issues.<br/>            For more efficient pixel manipulation, use the `LoadArgb32Pixels` method to retrieve the entire pixel array simultaneously. |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_32) | Gets a proportional height. |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_33) | Gets a proportional width. |
| [get_skew_angle()](#get_skew_angle__34) |    |
| grayscale() | Transformation of an image to its grayscale representation |
| [load(file_path)](#load_file_path_35) | Loads a new image from the specified file. |
| [load(file_path, load_options)](#load_file_path_load_options_36) | Loads a new image from the specified file. |
| [load(stream)](#load_stream_37) | Loads a new image from the specified stream. |
| [load(stream, load_options)](#load_stream_load_options_38) | Loads a new image from the specified stream. |
| [load_argb_32_pixels(rectangle)](#load_argb_32_pixels_rectangle_39) | Loads 32-bit ARGB pixels. |
| [load_argb_64_pixels(rectangle)](#load_argb_64_pixels_rectangle_40) | Loads 64-bit ARGB pixels. |
| [load_cmyk_32_pixels(rectangle)](#load_cmyk_32_pixels_rectangle_41) | Loads pixels in CMYK format. |
| [load_cmyk_pixels(rectangle)](#load_cmyk_pixels_rectangle_42) | Loads pixels in CMYK format.<br/>            This method is deprecated. Please use more effective the [RasterImage.load_cmyk_32_pixels(rectangle)](/psd/python-net/aspose.psd/rasterimage/) method. |
| [load_partial_argb_32_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_43) | Loads 32-bit ARGB pixels partially (by blocks). |
| [load_partial_pixels(desired_rectangle, pixel_loader)](#load_partial_pixels_desired_rectangle_pixel_loader_44) | Loads pixels partially by packs. |
| [load_pixels(rectangle)](#load_pixels_rectangle_45) | Loads pixels. |
| [load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_46) | Loads raw data. |
| [load_raw_data(rectangle, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_raw_data_settings_raw_data_loader_47) | Loads raw data. |
| [merge_layer_to(layer_to_merge_into)](#merge_layer_to_layer_to_merge_into_48) | Merges the layer to specified layer |
| normalize_angle() |    |
| normalize_angle(resize_proportionally, background_color) |    |
| [read_argb_32_scan_line(scan_line_index)](#read_argb_32_scan_line_scan_line_index_49) | Reads the whole scan line by the specified scan line index. |
| [read_scan_line(scan_line_index)](#read_scan_line_scan_line_index_50) | Reads the whole scan line by the specified scan line index. |
| replace_color(old_color, old_color_diff, new_color) |    |
| replace_color(old_color_argb, old_color_diff, new_color_argb) |    |
| replace_non_transparent_colors(new_color) |    |
| replace_non_transparent_colors(new_color_argb) |    |
| [resize(new_width, new_height)](#resize_new_width_new_height_51) | Resizes the image. The default [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) is used. |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_52) | Resizes the image. |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_53) | Resizes the image. |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_54) | Resizes the height proportionally. |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_55) | Resizes the height proportionally. |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_56) | Resizes the height proportionally. |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_57) | Resizes the width proportionally. The default [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) is used. |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_58) | Resizes the width proportionally. |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_59) | Resizes the width proportionally. |
| rotate(angle) |    |
| [rotate(angle, resize_proportionally, background_color)](#rotate_angle_resize_proportionally_background_color_60) | Rotate image around the center. |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_61) | Rotates, flips, or rotates and flips the image. |
| save() | Saves the image data to the underlying stream. |
| [save(file_path)](#save_file_path_62) | Saves the object's data to the specified file location. |
| [save(file_path, options)](#save_file_path_options_63) | Saves the object's data to the specified file location in the specified file format according to save options. |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_64) | Saves the object's data to the specified file location in the specified file format according to save options. |
| [save(file_path, over_write)](#save_file_path_over_write_65) | Saves the object's data to the specified file location. |
| [save(stream)](#save_stream_66) | Saves the object's data to the specified stream. |
| [save(stream, options_base)](#save_stream_options_base_67) | Saves the image's data to the specified stream in the specified file format according to save options. |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_68) | Saves the image's data to the specified stream in the specified file format according to save options. |
| [save_argb_32_pixels(rectangle, pixels)](#save_argb_32_pixels_rectangle_pixels_69) | Saves the 32-bit ARGB pixels. |
| save_cmyk_32_pixels(rectangle, pixels) |    |
| save_cmyk_pixels(rectangle, pixels) |    |
| [save_pixels(rectangle, pixels)](#save_pixels_rectangle_pixels_70) | Saves pixels (format specific method). |
| [save_raw_data(data, data_offset, rectangle, raw_data_settings)](#save_raw_data_data_data_offset_rectangle_raw_data_settings_71) | Saves the raw data. |
| [set_argb_32_pixel(x, y, argb_32_color)](#set_argb_32_pixel_x_y_argb_32_color_72) | Sets an image 32-bit ARGB pixel for the specified position. |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_73) | Sets the image palette. |
| [set_pixel(x, y, color)](#set_pixel_x_y_color_74) | Sets an image pixel for the specified position. |
| set_resolution(dpi_x, dpi_y) |    |
| [shallow_copy()](#shallow_copy__75) | Creates a shallow copy of the current Layer.<br/>            Please <see href="https://msdn.microsoft.com/ru-ru/library/system.object.memberwiseclone(v=vs.110).aspx" /> for explanation. |
| [to_bitmap()](#to_bitmap__76) |    |
| [write_argb_32_scan_line(scan_line_index, argb_32_pixels)](#write_argb_32_scan_line_scan_line_index_argb_32_pixels_77) | Writes the whole scan line to the specified scan line index. |
| [write_scan_line(scan_line_index, pixels)](#write_scan_line_scan_line_index_pixels_78) | Writes the whole scan line to the specified scan line index. |


### Constructor: Layer() {#Layer__1}


```
 Layer() 
```

Initializes a new instance of the [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) class. Constructor for lazy initialization.

### Constructor: Layer(bounds, red_bytes, green_bytes, blue_bytes, name) {#Layer_bounds_red_bytes_green_bytes_blue_bytes_name_2}


```
 Layer(bounds, red_bytes, green_bytes, blue_bytes, name) 
```

Initializes a new instance of the [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) class from byte arrays.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | The layer bounds. |
| red_bytes | byte | The red bytes. |
| green_bytes | byte | The green bytes. |
| blue_bytes | byte | The blue bytes. |
| name | string | The layer name. |

### Constructor: Layer(image, dispose_image) {#Layer_image_dispose_image_3}


```
 Layer(image, dispose_image) 
```

Initializes a new instance of the [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | The image. |
| dispose_image | bool | if set to <c>true</c> [dispose image]. |

### Constructor: Layer(stream) {#Layer_stream_4}


```
 Layer(stream) 
```

Initializes a new instance of the [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The image stream |

### Method: add_layer_mask(layer_mask) {#add_layer_mask_layer_mask_1}


```
 add_layer_mask(layer_mask) 
```

Adds the mask to current layer.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| layer_mask | [LayerMaskData](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata) | The layer mask. |

### Method: adjust_brightness(brightness) {#adjust_brightness_brightness_2}


```
 adjust_brightness(brightness) 
```

Adjust of a brightness for image.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brightness | int | Brightness value. |

### Method: adjust_contrast(contrast) {#adjust_contrast_contrast_3}


```
 adjust_contrast(contrast) 
```

Image contrasting

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| contrast | float | Contrast value (in range [-100; 100]) |

### Method: adjust_gamma(gamma) {#adjust_gamma_gamma_4}


```
 adjust_gamma(gamma) 
```

Gamma-correction of an image.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| gamma | float | Gamma for red, green and blue channels coefficient |

### Method: adjust_gamma(gamma_red, gamma_green, gamma_blue) {#adjust_gamma_gamma_red_gamma_green_gamma_blue_5}


```
 adjust_gamma(gamma_red, gamma_green, gamma_blue) 
```

Gamma-correction of an image.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| gamma_red | float | Gamma for red channel coefficient |
| gamma_green | float | Gamma for green channel coefficient |
| gamma_blue | float | Gamma for blue channel coefficient |

### Method: binarize_bradley(brightness_difference) {#binarize_bradley_brightness_difference_6}


```
 binarize_bradley(brightness_difference) 
```

Binarization of an image using Bradley's adaptive thresholding algorithm using the integral image thresholding

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brightness_difference | double | The brightness difference between pixel and the average of an s x s window of pixels centered around this pixel. |

### Method: binarize_bradley(brightness_difference, window_size) {#binarize_bradley_brightness_difference_window_size_7}


```
 binarize_bradley(brightness_difference, window_size) 
```

Binarization of an image using Bradley's adaptive thresholding algorithm using the integral image thresholding

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brightness_difference | double | The brightness difference between pixel and the average of an s x s window of pixels centered around this pixel. |
| window_size | int | The size of s x s window of pixels centered around this pixel |

### Method: binarize_fixed(threshold) {#binarize_fixed_threshold_8}


```
 binarize_fixed(threshold) 
```

Binarization of an image with predefined threshold

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| threshold | byte | Threshold value. If corresponding gray value of a pixel is greater than threshold, a value of 255 will be assigned to it, 0 otherwise. |

### Method: can_load(file_path)  [static] {#can_load_file_path_9}


```
 can_load(file_path) 
```

Determines whether image can be loaded from the specified file path.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path. |

**Returns**

| Type | Description |
| :- | :- |
| bool | <c>true</c> if image can be loaded from the specified file; otherwise, <c>false</c>. |


### Method: can_load(file_path, load_options)  [static] {#can_load_file_path_load_options_10}


```
 can_load(file_path, load_options) 
```

Determines whether image can be loaded from the specified file path and optionally using the specified open options.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | The load options. |

**Returns**

| Type | Description |
| :- | :- |
| bool | <c>true</c> if image can be loaded from the specified file; otherwise, <c>false</c>. |


### Method: can_load(stream)  [static] {#can_load_stream_11}


```
 can_load(stream) 
```

Determines whether image can be loaded from the specified stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to load from. |

**Returns**

| Type | Description |
| :- | :- |
| bool | <c>true</c> if image can be loaded from the specified stream; otherwise, <c>false</c>. |


### Method: can_load(stream, load_options)  [static] {#can_load_stream_load_options_12}


```
 can_load(stream, load_options) 
```

Determines whether image can be loaded from the specified stream and optionally using the specified <paramref name="loadOptions" />.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to load from. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | The load options. |

**Returns**

| Type | Description |
| :- | :- |
| bool | <c>true</c> if image can be loaded from the specified stream; otherwise, <c>false</c>. |


### Method: can_save(options) {#can_save_options_13}


```
 can_save(options) 
```

Determines whether image can be saved to the specified file format represented by the passed save options.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | The save options to use. |

**Returns**

| Type | Description |
| :- | :- |
| bool | <c>true</c> if image can be saved to the specified file format represented by the passed save options; otherwise, <c>false</c>. |


### Method: create(image_options, width, height)  [static] {#create_image_options_width_height_14}


```
 create(image_options, width, height) 
```

Creates a new image using the specified create options.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | The image options. |
| width | int | The width. |
| height | int | The height. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | The newly created image. |


### Method: crop(rectangle) {#crop_rectangle_15}


```
 crop(rectangle) 
```

Cropping the image.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | The rectangle. |

### Method: dither(dithering_method, bits_count) {#dither_dithering_method_bits_count_16}


```
 dither(dithering_method, bits_count) 
```

Performs dithering on the current image.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/psd/python-net/aspose.psd/ditheringmethod) | The dithering method. |
| bits_count | int | The final bits count for dithering. |

### Method: dither(dithering_method, bits_count, custom_palette) {#dither_dithering_method_bits_count_custom_palette_17}


```
 dither(dithering_method, bits_count, custom_palette) 
```

Performs dithering on the current image.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/psd/python-net/aspose.psd/ditheringmethod) | The dithering method. |
| bits_count | int | The final bits count for dithering. |
| custom_palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | The custom palette for dithering. |

### Method: draw_image(location, image) {#draw_image_location_image_18}


```
 draw_image(location, image) 
```

Draws the image on layer.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| location | [Point](/psd/python-net/aspose.psd/point) | The location. |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | The image. |

### Method: get_argb_32_pixel(x, y) {#get_argb_32_pixel_x_y_19}


```
 get_argb_32_pixel(x, y) 
```

Gets an image 32-bit ARGB pixel.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | int | The pixel x location. |
| y | int | The pixel y location. |

**Returns**

| Type | Description |
| :- | :- |
| int | The 32-bit ARGB pixel for the specified location. |


### Method: get_default_argb_32_pixels(rectangle) {#get_default_argb_32_pixels_rectangle_20}


```
 get_default_argb_32_pixels(rectangle) 
```

Gets the default 32-bit ARGB pixels array.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | The rectangle to get pixels for. |

**Returns**

| Type | Description |
| :- | :- |
| int | The default pixels array. |


### Method: get_default_options(args) {#get_default_options_args_21}


```
 get_default_options(args) 
```

Gets the default options.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| args | object | The arguments. |

**Returns**

| Type | Description |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Default options |


### Method: get_default_pixels(rectangle, partial_pixel_loader) {#get_default_pixels_rectangle_partial_pixel_loader_22}


```
 get_default_pixels(rectangle, partial_pixel_loader) 
```

Gets the default pixels array using partial pixel loader.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | The rectangle to get pixels for. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/psd/python-net/aspose.psd/ipartialargb32pixelloader) | The partial pixel loader. |

### Method: get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) {#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_23}


```
 get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) 
```

Gets the default raw data array using partial pixel loader.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | The rectangle to get pixels for. |
| partial_raw_data_loader | [IPartialRawDataLoader](/psd/python-net/aspose.psd/ipartialrawdataloader) | The partial raw data loader. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | The raw data settings. |

### Method: get_default_raw_data(rectangle, raw_data_settings) {#get_default_raw_data_rectangle_raw_data_settings_24}


```
 get_default_raw_data(rectangle, raw_data_settings) 
```

Gets the default raw data array.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | The rectangle to get raw data for. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | The raw data settings. |

**Returns**

| Type | Description |
| :- | :- |
| byte | The default raw data array. |


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_25}


```
 get_file_format(file_path) 
```

Gets the file format.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path. |

**Returns**

| Type | Description |
| :- | :- |
| [FileFormat](/psd/python-net/aspose.psd/fileformat) | The determined file format. |


### Method: get_file_format(stream)  [static] {#get_file_format_stream_26}


```
 get_file_format(stream) 
```

Gets the file format.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream. |

**Returns**

| Type | Description |
| :- | :- |
| [FileFormat](/psd/python-net/aspose.psd/fileformat) | The determined file format. |


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_27}


```
 get_fitting_rectangle(rectangle, pixels, width, height) 
```

Gets rectangle which fits the current image.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | The rectangle to get fitting rectangle for. |
| pixels | int | The 32-bit ARGB pixels. |
| width | int | The object width. |
| height | int | The object height. |

**Returns**

| Type | Description |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | The fitting rectangle or exception if no fitting rectangle can be found. |


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_28}


```
 get_fitting_rectangle(rectangle, width, height) 
```

Gets rectangle which fits the current image.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | The rectangle to get fitting rectangle for. |
| width | int | The object width. |
| height | int | The object height. |

**Returns**

| Type | Description |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | The fitting rectangle or exception if no fitting rectangle can be found. |


### Method: get_modify_date(use_default) {#get_modify_date_use_default_29}


```
 get_modify_date(use_default) 
```

Gets the date and time the resource image was last modified.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| use_default | bool | if set to <c>true</c> uses the information from FileInfo as default value. |

**Returns**

| Type | Description |
| :- | :- |
| datetime | The date and time the resource image was last modified. |


### Method: get_original_options() {#get_original_options__30}


```
 get_original_options() 
```

Gets the options based on the original file settings.<br/>            This can be helpful to keep bit-depth and other parameters of the original image unchanged.<br/>            For example, if we load a black-white PNG image with 1 bit per pixel and then save it using the<br/>            [DataStreamSupporter.save(file_path)](/psd/python-net/aspose.psd/datastreamsupporter/) method, the output PNG image with 8-bit per pixel will be produced.<br/>            To avoid it and save PNG image with 1-bit per pixel, use this method to get corresponding saving options and pass them<br/>            to the [Image.save(file_path, options)](/psd/python-net/aspose.psd/image/) method as the second parameter.

**Returns**

| Type | Description |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | The options based on the original file settings. |


### Method: get_pixel(x, y) {#get_pixel_x_y_31}


```
 get_pixel(x, y) 
```

Gets an image pixel.<br/>            Performance Warning: Avoid using this method to iterate over all image pixels as it can lead to significant performance issues.<br/>            For more efficient pixel manipulation, use the `LoadArgb32Pixels` method to retrieve the entire pixel array simultaneously.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | int | The pixel x location. |
| y | int | The pixel y location. |

**Returns**

| Type | Description |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | The pixel color for the specified location. |


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_32}


```
 get_proportional_height(width, height, new_width) 
```

Gets a proportional height.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| width | int | The width. |
| height | int | The height. |
| new_width | int | The new width. |

**Returns**

| Type | Description |
| :- | :- |
| int | The proportional height. |


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_33}


```
 get_proportional_width(width, height, new_height) 
```

Gets a proportional width.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| width | int | The width. |
| height | int | The height. |
| new_height | int | The new height. |

**Returns**

| Type | Description |
| :- | :- |
| int | The proportional width. |


### Method: get_skew_angle() {#get_skew_angle__34}


```
 get_skew_angle() 
```

  

**Returns**

| Type | Description |
| :- | :- |
| float |  |


### Method: load(file_path)  [static] {#load_file_path_35}


```
 load(file_path) 
```

Loads a new image from the specified file.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path to load image from. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | The loaded image. |


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_36}


```
 load(file_path, load_options) 
```

Loads a new image from the specified file.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path to load image from. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | The load options. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | The loaded image. |


### Method: load(stream)  [static] {#load_stream_37}


```
 load(stream) 
```

Loads a new image from the specified stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to load image from. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | The loaded image. |


### Method: load(stream, load_options)  [static] {#load_stream_load_options_38}


```
 load(stream, load_options) 
```

Loads a new image from the specified stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to load image from. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | The load options. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | The loaded image. |


### Method: load_argb_32_pixels(rectangle) {#load_argb_32_pixels_rectangle_39}


```
 load_argb_32_pixels(rectangle) 
```

Loads 32-bit ARGB pixels.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | The rectangle to load pixels from. |

**Returns**

| Type | Description |
| :- | :- |
| int | The loaded 32-bit ARGB pixels array. |


### Method: load_argb_64_pixels(rectangle) {#load_argb_64_pixels_rectangle_40}


```
 load_argb_64_pixels(rectangle) 
```

Loads 64-bit ARGB pixels.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | The rectangle to load pixels from. |

**Returns**

| Type | Description |
| :- | :- |
| long | The loaded 64-bit ARGB pixels array. |


### Method: load_cmyk_32_pixels(rectangle) {#load_cmyk_32_pixels_rectangle_41}


```
 load_cmyk_32_pixels(rectangle) 
```

Loads pixels in CMYK format.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | The rectangle to load pixels from. |

**Returns**

| Type | Description |
| :- | :- |
| int | The loaded CMYK pixels presentes as 32-bit inateger values. |


### Method: load_cmyk_pixels(rectangle) {#load_cmyk_pixels_rectangle_42}


```
 load_cmyk_pixels(rectangle) 
```

Loads pixels in CMYK format.<br/>            This method is deprecated. Please use more effective the [RasterImage.load_cmyk_32_pixels(rectangle)](/psd/python-net/aspose.psd/rasterimage/) method.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | The rectangle to load pixels from. |

**Returns**

| Type | Description |
| :- | :- |
| [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | The loaded CMYK pixels array. |


### Method: load_partial_argb_32_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_43}


```
 load_partial_argb_32_pixels(rectangle, partial_pixel_loader) 
```

Loads 32-bit ARGB pixels partially (by blocks).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | The rectangle to load pixels from. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/psd/python-net/aspose.psd/ipartialargb32pixelloader) | The partial pixel loader. |

### Method: load_partial_pixels(desired_rectangle, pixel_loader) {#load_partial_pixels_desired_rectangle_pixel_loader_44}


```
 load_partial_pixels(desired_rectangle, pixel_loader) 
```

Loads pixels partially by packs.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| desired_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | The desired rectangle. |
| pixel_loader | [IPartialPixelLoader](/psd/python-net/aspose.psd/ipartialpixelloader) | The pixel loader. |

### Method: load_pixels(rectangle) {#load_pixels_rectangle_45}


```
 load_pixels(rectangle) 
```

Loads pixels.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | The rectangle to load pixels from. |

**Returns**

| Type | Description |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | The loaded pixels array. |


### Method: load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_46}


```
 load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) 
```

Loads raw data.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | The rectangle to load raw data from. |
| dest_image_bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | The dest image bounds. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | The raw data settings to use for loaded data. Note if data is not in the format specified then data conversion will be performed. |
| raw_data_loader | [IPartialRawDataLoader](/psd/python-net/aspose.psd/ipartialrawdataloader) | The raw data loader. |

### Method: load_raw_data(rectangle, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_raw_data_settings_raw_data_loader_47}


```
 load_raw_data(rectangle, raw_data_settings, raw_data_loader) 
```

Loads raw data.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | The rectangle to load raw data from. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | The raw data settings to use for loaded data. Note if data is not in the format specified then data conversion will be performed. |
| raw_data_loader | [IPartialRawDataLoader](/psd/python-net/aspose.psd/ipartialrawdataloader) | The raw data loader. |

### Method: merge_layer_to(layer_to_merge_into) {#merge_layer_to_layer_to_merge_into_48}


```
 merge_layer_to(layer_to_merge_into) 
```

Merges the layer to specified layer

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| layer_to_merge_into | [Layer](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | The layer to merge into. |

### Method: read_argb_32_scan_line(scan_line_index) {#read_argb_32_scan_line_scan_line_index_49}


```
 read_argb_32_scan_line(scan_line_index) 
```

Reads the whole scan line by the specified scan line index.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| scan_line_index | int | Zero based index of the scan line. |

**Returns**

| Type | Description |
| :- | :- |
| int | The scan line 32-bit ARGB color values array. |


### Method: read_scan_line(scan_line_index) {#read_scan_line_scan_line_index_50}


```
 read_scan_line(scan_line_index) 
```

Reads the whole scan line by the specified scan line index.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| scan_line_index | int | Zero based index of the scan line. |

**Returns**

| Type | Description |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | The scan line pixel color values array. |


### Method: resize(new_width, new_height) {#resize_new_width_new_height_51}


```
 resize(new_width, new_height) 
```

Resizes the image. The default [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) is used.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_width | int | The new width. |
| new_height | int | The new height. |

### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_52}


```
 resize(new_width, new_height, resize_type) 
```

Resizes the image.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_width | int | The new width. |
| new_height | int | The new height. |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | The resize type. |

### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_53}


```
 resize(new_width, new_height, settings) 
```

Resizes the image.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_width | int | The new width. |
| new_height | int | The new height. |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | The resize settings. |

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_54}


```
 resize_height_proportionally(new_height) 
```

Resizes the height proportionally.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_height | int | The new height. |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_55}


```
 resize_height_proportionally(new_height, resize_type) 
```

Resizes the height proportionally.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_height | int | The new height. |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | Type of the resize. |

### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_56}


```
 resize_height_proportionally(new_height, settings) 
```

Resizes the height proportionally.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_height | int | The new height. |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | The image resize settings. |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_57}


```
 resize_width_proportionally(new_width) 
```

Resizes the width proportionally. The default [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) is used.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_width | int | The new width. |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_58}


```
 resize_width_proportionally(new_width, resize_type) 
```

Resizes the width proportionally.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_width | int | The new width. |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | Type of the resize. |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_59}


```
 resize_width_proportionally(new_width, settings) 
```

Resizes the width proportionally.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_width | int | The new width. |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | The image resize settings. |

### Method: rotate(angle, resize_proportionally, background_color) {#rotate_angle_resize_proportionally_background_color_60}


```
 rotate(angle, resize_proportionally, background_color) 
```

Rotate image around the center.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| angle | float | The rotate angle in degrees. Positive values will rotate clockwise. |
| resize_proportionally | bool | if set to <c>true</c> you will have your image size changed according to rotated rectangle (corner points) projections in other case that leaves dimensions untouched and only internal image contents are rotated. |
| background_color | [Color](/psd/python-net/aspose.psd/color) | Color of the background. |

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_61}


```
 rotate_flip(rotate_flip_type) 
```

Rotates, flips, or rotates and flips the image.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/psd/python-net/aspose.psd/rotatefliptype) | The rotate flip type. |

### Method: save(file_path) {#save_file_path_62}


```
 save(file_path) 
```

Saves the object's data to the specified file location.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path to save the object's data to. |

### Method: save(file_path, options) {#save_file_path_options_63}


```
 save(file_path, options) 
```

Saves the object's data to the specified file location in the specified file format according to save options.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | The options. |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_64}


```
 save(file_path, options, bounds_rectangle) 
```

Saves the object's data to the specified file location in the specified file format according to save options.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | The options. |
| bounds_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | The destination image bounds rectangle. Set the empty rectangle for use source bounds. |

### Method: save(file_path, over_write) {#save_file_path_over_write_65}


```
 save(file_path, over_write) 
```

Saves the object's data to the specified file location.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path to save the object's data to. |
| over_write | bool | if set to <c>true</c> over write the file contents, otherwise append will occur. |

### Method: save(stream) {#save_stream_66}


```
 save(stream) 
```

Saves the object's data to the specified stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to save the object's data to. |

### Method: save(stream, options_base) {#save_stream_options_base_67}


```
 save(stream, options_base) 
```

Saves the image's data to the specified stream in the specified file format according to save options.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to save the image's data to. |
| options_base | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | The save options. |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_68}


```
 save(stream, options_base, bounds_rectangle) 
```

Saves the image's data to the specified stream in the specified file format according to save options.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to save the image's data to. |
| options_base | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | The save options. |
| bounds_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | The destination image bounds rectangle. Set the empty rectangle for use source bounds. |

### Method: save_argb_32_pixels(rectangle, pixels) {#save_argb_32_pixels_rectangle_pixels_69}


```
 save_argb_32_pixels(rectangle, pixels) 
```

Saves the 32-bit ARGB pixels.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | The rectangle to save pixels to. |
| pixels | int | The 32-bit ARGB pixels array. |

### Method: save_pixels(rectangle, pixels) {#save_pixels_rectangle_pixels_70}


```
 save_pixels(rectangle, pixels) 
```

Saves pixels (format specific method).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | The rectangle to save pixels to. |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) | The 32-bit ARGB pixels array. |

### Method: save_raw_data(data, data_offset, rectangle, raw_data_settings) {#save_raw_data_data_data_offset_rectangle_raw_data_settings_71}


```
 save_raw_data(data, data_offset, rectangle, raw_data_settings) 
```

Saves the raw data.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| data | byte | The raw data. |
| data_offset | int | The starting raw data offset. |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | The raw data rectangle. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | The raw data settings the data is in. |

### Method: set_argb_32_pixel(x, y, argb_32_color) {#set_argb_32_pixel_x_y_argb_32_color_72}


```
 set_argb_32_pixel(x, y, argb_32_color) 
```

Sets an image 32-bit ARGB pixel for the specified position.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | int | The pixel x location. |
| y | int | The pixel y location. |
| argb_32_color | int | The 32-bit ARGB pixel for the specified position. |

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_73}


```
 set_palette(palette, update_colors) 
```

Sets the image palette.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | The palette to set. |
| update_colors | bool | if set to <c>true</c> colors will be updated according to the new palette; otherwise color indexes remain unchanged. Note that unchanged indexes may crash the image on loading if some indexes have no corresponding palette entries. |

### Method: set_pixel(x, y, color) {#set_pixel_x_y_color_74}


```
 set_pixel(x, y, color) 
```

Sets an image pixel for the specified position.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | int | The pixel x location. |
| y | int | The pixel y location. |
| color | [Color](/psd/python-net/aspose.psd/color) | The pixel color for the specified position. |

### Method: shallow_copy() {#shallow_copy__75}


```
 shallow_copy() 
```

Creates a shallow copy of the current Layer.<br/>            Please <see href="https://msdn.microsoft.com/ru-ru/library/system.object.memberwiseclone(v=vs.110).aspx" /> for explanation.

**Returns**

| Type | Description |
| :- | :- |
| [Layer](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | A shallow copy of the current Layer. |


### Method: to_bitmap() {#to_bitmap__76}


```
 to_bitmap() 
```

  

**Returns**

| Type | Description |
| :- | :- |
| aspose.pydrawing.Bitmap |  |


### Method: write_argb_32_scan_line(scan_line_index, argb_32_pixels) {#write_argb_32_scan_line_scan_line_index_argb_32_pixels_77}


```
 write_argb_32_scan_line(scan_line_index, argb_32_pixels) 
```

Writes the whole scan line to the specified scan line index.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| scan_line_index | int | Zero based index of the scan line. |
| argb_32_pixels | int | The 32-bit ARGB colors array to write. |

### Method: write_scan_line(scan_line_index, pixels) {#write_scan_line_scan_line_index_pixels_78}


```
 write_scan_line(scan_line_index, pixels) 
```

Writes the whole scan line to the specified scan line index.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| scan_line_index | int | Zero based index of the scan line. |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) | The pixel colors array to write. |

