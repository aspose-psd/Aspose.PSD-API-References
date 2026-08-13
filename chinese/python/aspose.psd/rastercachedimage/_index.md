---
title: "RasterCachedImage 类"
type: docs
weight: 3730
url: /zh/python-net/aspose.psd/rastercachedimage/
---

**Summary:** Represents a raster image supporting raster graphics operations. This image caches pixel data when required.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.RasterCachedImage

**Inheritance:** IObjectWithBounds, IRasterImageArgb32PixelLoader, IRasterImageRawDataLoader, RasterImage

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| auto_adjust_palette | bool | 读/写 | 获取或设置指示是否自动调整调色板的值。 |
| background_color | [Color](/psd/python-net/aspose.psd/color) | r/w | 获取或设置背景颜色的值。 |
| bits_per_pixel | int | r | 获取图像每像素位数。 |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | 获取对象边界。 |
| buffer_size_hint | int | 读/写 | 获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| container | [Image](/psd/python-net/aspose.psd/image) | r | 获取 [Image](/psd/python-net/aspose.psd/image/) 容器。 |
| data_stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | r | 获取对象的数据流。 |
| 已释放 | bool | r | 获取一个值，指示此实例是否已释放。 |
| file_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | 获取文件格式的值 |
| has_alpha | bool | r | 获取一个值，指示此实例是否具有 alpha 通道。 |
| has_background_color | bool | 读/写 | 获取或设置一个值，指示图像是否具有背景颜色。 |
| has_transparent_color | bool | 读/写 | 获取一个值，指示图像是否具有透明颜色。 |
| height | int | r | 获取对象的高度。 |
| horizontal_resolution | double | r/w | 获取或设置此 [RasterImage](/psd/python-net/aspose.psd/rasterimage/) 的水平分辨率（每英寸像素数）。 |
| image_opacity | float | r | 获取此图像的不透明度。 |
| interrupt_monitor | [InterruptMonitor](/psd/python-net/aspose.psd.multithreading/interruptmonitor/) | r/w | 获取或设置中断监视器。 |
| is_cached | bool | r | 获取一个值，指示图像数据当前是否已缓存。 |
| is_raw_data_available | bool | r | 获取一个值，指示是否可用原始数据加载。 |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | 获取或设置颜色调色板。当像素直接表示时，不使用颜色调色板。 |
| premultiply_components | bool | 读/写 | 获取或设置一个值，指示图像组件是否必须预乘。 |
| raw_custom_color_converter | [IColorConverter](/psd/python-net/aspose.psd/icolorconverter) | r/w | 获取或设置自定义颜色转换器 |
| raw_data_format | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | 获取原始数据格式。 |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | r | 获取当前的原始数据设置。注意，使用这些设置时，数据将在不进行转换的情况下加载。 |
| raw_fallback_index | int | 读/写 | 获取或设置在调色板索引超出范围时使用的回退索引 |
| raw_indexed_color_converter | [IIndexedColorConverter](/psd/python-net/aspose.psd/iindexedcolorconverter) | r/w | 获取或设置索引颜色转换器 |
| raw_line_size | int | r | 获取原始行大小（字节）。 |
| size | [Size](/psd/python-net/aspose.psd/size) | r | 获取对象的大小。 |
| transparent_color | [Color](/psd/python-net/aspose.psd/color) | r/w | 获取图像透明颜色。 |
| update_xmp_data | bool | 读/写 | 获取或设置一个值，指示是否更新 XMP 元数据。 |
| use_palette | bool | r | 获取一个值，指示是否使用图像调色板。 |
| use_raw_data | bool | 读/写 | 获取或设置一个值，指示在可用原始数据加载时是否使用原始数据加载。 |
| vertical_resolution | double | r/w | 获取或设置此 [RasterImage](/psd/python-net/aspose.psd/rasterimage/) 的垂直分辨率（每英寸像素数）。 |
| width | int | r | 获取对象宽度。 |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | 获取或设置 XMP 元数据。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [adjust_brightness(brightness)](#adjust_brightness_brightness_1) | 调整图像的亮度。 |
| [adjust_contrast(contrast)](#adjust_contrast_contrast_2) | 图像对比 |
| [adjust_gamma(gamma)](#adjust_gamma_gamma_3) | 图像的伽马校正。 |
| [adjust_gamma(gamma_red, gamma_green, gamma_blue)](#adjust_gamma_gamma_red_gamma_green_gamma_blue_4) | 图像的伽马校正。 |
| [binarize_bradley(brightness_difference)](#binarize_bradley_brightness_difference_5) | 使用 Bradley 的自适应阈值算法和积分图像阈值对图像进行二值化 |
| [binarize_bradley(brightness_difference, window_size)](#binarize_bradley_brightness_difference_window_size_6) | 使用 Bradley 的自适应阈值算法和积分图像阈值对图像进行二值化 |
| [binarize_fixed(threshold)](#binarize_fixed_threshold_7) | 使用预定义阈值对图像进行二值化 |
| binarize_otsu() | 使用 Otsu 阈值对图像进行二值化 |
| cache_data() | 缓存数据，并确保不会从底层 [DataStreamSupporter.data_stream_container](/psd/python-net/aspose.psd/datastreamsupporter/) 进行额外的数据加载。 |
| [can_load(file_path)](#can_load_file_path_8) | 确定是否可以从指定的文件路径加载图像。 |
| [can_load(file_path, load_options)](#can_load_file_path_load_options_9) | 确定是否可以从指定的文件路径加载图像，且可选地使用指定的打开选项。 |
| [can_load(stream)](#can_load_stream_10) | 确定是否可以从指定的流加载图像。 |
| [can_load(stream, load_options)](#can_load_stream_load_options_11) | 确定是否可以从指定的流加载图像，且可选地使用指定的 <paramref name="loadOptions" />。 |
| [can_save(options)](#can_save_options_12) | 确定是否可以将图像保存为由传入的保存选项表示的指定文件格式。 |
| [create(image_options, width, height)](#create_image_options_width_height_13) | 使用指定的创建选项创建新图像。 |
| crop(left_shift, right_shift, top_shift, bottom_shift) |  |
| [crop(rectangle)](#crop_rectangle_14) | 裁剪图像。 |
| [dither(dithering_method, bits_count)](#dither_dithering_method_bits_count_15) | 对当前图像执行抖动处理。 |
| [dither(dithering_method, bits_count, custom_palette)](#dither_dithering_method_bits_count_custom_palette_16) | 对当前图像执行抖动处理。 |
| filter(rectangle, options) |  |
| [get_argb_32_pixel(x, y)](#get_argb_32_pixel_x_y_17) | 获取图像的 32 位 ARGB 像素。 |
| [get_default_argb_32_pixels(rectangle)](#get_default_argb_32_pixels_rectangle_18) | 获取默认的 32 位 ARGB 像素数组。 |
| [get_default_options(args)](#get_default_options_args_19) | 获取默认选项。 |
| [get_default_pixels(rectangle, partial_pixel_loader)](#get_default_pixels_rectangle_partial_pixel_loader_20) | 使用部分像素加载器获取默认像素数组。 |
| [get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings)](#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_21) | 使用部分像素加载器获取默认原始数据数组。 |
| [get_default_raw_data(rectangle, raw_data_settings)](#get_default_raw_data_rectangle_raw_data_settings_22) | 获取默认原始数据数组。 |
| [get_file_format(file_path)](#get_file_format_file_path_23) | 获取文件格式。 |
| [get_file_format(stream)](#get_file_format_stream_24) | 获取文件格式。 |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_25) | 获取适合当前图像的矩形。 |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_26) | 获取适合当前图像的矩形。 |
| [get_modify_date(use_default)](#get_modify_date_use_default_27) | 获取资源图像上次修改的日期和时间。 |
| [get_original_options()](#get_original_options__28) | 获取基于原始文件设置的选项。<br/>            这有助于保持原始图像的位深度和其他参数不变。<br/>            例如，如果我们加载一张每像素 1 位的黑白 PNG 图像，然后使用<br/>            [DataStreamSupporter.save(file_path)](/psd/python-net/aspose.psd/datastreamsupporter/) 方法保存，它将生成每像素 8 位的输出 PNG 图像。<br/>            为避免这种情况并以每像素 1 位保存 PNG 图像，请使用此方法获取相应的保存选项并将它们<br/>            作为第二个参数传递给 [Image.save(file_path, options)](/psd/python-net/aspose.psd/image/) 方法。 |
| [get_pixel(x, y)](#get_pixel_x_y_29) | 获取图像像素。<br/>            性能警告：避免使用此方法遍历所有图像像素，因为这可能导致显著的性能问题。<br/>            为了更高效的像素操作，请使用 `LoadArgb32Pixels` 方法一次性检索整个像素数组。 |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_30) | 获取等比例高度。 |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_31) | 获取等比例宽度。 |
| [get_skew_angle()](#get_skew_angle__32) |    |
| grayscale() | 将图像转换为灰度表示 |
| [load(file_path)](#load_file_path_33) | 从指定文件加载新图像。 |
| [load(file_path, load_options)](#load_file_path_load_options_34) | 从指定文件加载新图像。 |
| [load(stream)](#load_stream_35) | 从指定流加载新图像。 |
| [load(stream, load_options)](#load_stream_load_options_36) | 从指定流加载新图像。 |
| [load_argb_32_pixels(rectangle)](#load_argb_32_pixels_rectangle_37) | 加载 32 位 ARGB 像素。 |
| [load_argb_64_pixels(rectangle)](#load_argb_64_pixels_rectangle_38) | 加载 64 位 ARGB 像素。 |
| [load_cmyk_32_pixels(rectangle)](#load_cmyk_32_pixels_rectangle_39) | 加载 CMYK 格式的像素。 |
| [load_cmyk_pixels(rectangle)](#load_cmyk_pixels_rectangle_40) | 加载 CMYK 格式的像素。<br/>            此方法已弃用。请使用更有效的 [RasterImage.load_cmyk_32_pixels(rectangle)](/psd/python-net/aspose.psd/rasterimage/) 方法。 |
| [load_partial_argb_32_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_41) | 按包部分加载 32 位 ARGB 像素。 |
| [load_partial_pixels(desired_rectangle, pixel_loader)](#load_partial_pixels_desired_rectangle_pixel_loader_42) | 按批次部分加载像素。 |
| [load_pixels(rectangle)](#load_pixels_rectangle_43) | 加载像素。 |
| [load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_44) | 加载原始数据。 |
| [load_raw_data(rectangle, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_raw_data_settings_raw_data_loader_45) | 加载原始数据。 |
| normalize_angle() |  |
| normalize_angle(resize_proportionally, background_color) |  |
| [read_argb_32_scan_line(scan_line_index)](#read_argb_32_scan_line_scan_line_index_46) | 按指定的扫描线索引读取整条扫描线。 |
| [read_scan_line(scan_line_index)](#read_scan_line_scan_line_index_47) | 按指定的扫描线索引读取整条扫描线。 |
| replace_color(old_color, old_color_diff, new_color) |  |
| replace_color(old_color_argb, old_color_diff, new_color_argb) |  |
| replace_non_transparent_colors(new_color) |  |
| replace_non_transparent_colors(new_color_argb) |  |
| [resize(new_width, new_height)](#resize_new_width_new_height_48) | 调整图像大小。使用默认的 [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/)。 |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_49) | 调整图像大小。 |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_50) | 调整图像大小。 |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_51) | 等比例调整高度。 |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_52) | 等比例调整高度。 |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_53) | 等比例调整高度。 |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_54) | 等比例调整宽度。使用默认的 [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/)。 |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_55) | 等比例调整宽度。 |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_56) | 等比例调整宽度。 |
| rotate(angle) |  |
| [rotate(angle, resize_proportionally, background_color)](#rotate_angle_resize_proportionally_background_color_57) | 围绕中心旋转图像。 |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_58) | 旋转、翻转或同时旋转并翻转图像。 |
| save() | 将图像数据保存到底层流。 |
| [save(file_path)](#save_file_path_59) | 将对象的数据保存到指定的文件位置。 |
| [save(file_path, options)](#save_file_path_options_60) | 根据保存选项，将对象的数据以指定的文件格式保存到指定的文件位置。 |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_61) | 根据保存选项，将对象的数据以指定的文件格式保存到指定的文件位置。 |
| [save(file_path, over_write)](#save_file_path_over_write_62) | 将对象的数据保存到指定的文件位置。 |
| [save(stream)](#save_stream_63) | 将对象的数据保存到指定的流中。 |
| [save(stream, options_base)](#save_stream_options_base_64) | 根据保存选项，将图像的数据以指定的文件格式保存到指定的流中。 |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_65) | 根据保存选项，将图像的数据以指定的文件格式保存到指定的流中。 |
| [save_argb_32_pixels(rectangle, pixels)](#save_argb_32_pixels_rectangle_pixels_66) | 保存 32 位 ARGB 像素。 |
| save_cmyk_32_pixels(rectangle, pixels) |  |
| save_cmyk_pixels(rectangle, pixels) |  |
| [save_pixels(rectangle, pixels)](#save_pixels_rectangle_pixels_67) | 保存像素（特定格式的方法）。 |
| [save_raw_data(data, data_offset, rectangle, raw_data_settings)](#save_raw_data_data_data_offset_rectangle_raw_data_settings_68) | 保存原始数据。 |
| [set_argb_32_pixel(x, y, argb_32_color)](#set_argb_32_pixel_x_y_argb_32_color_69) | 为指定位置设置图像的 32 位 ARGB 像素。 |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_70) | 设置图像调色板。 |
| [set_pixel(x, y, color)](#set_pixel_x_y_color_71) | 为指定位置设置图像像素。 |
| set_resolution(dpi_x, dpi_y) |  |
| [to_bitmap()](#to_bitmap__72) |    |
| [write_argb_32_scan_line(scan_line_index, argb_32_pixels)](#write_argb_32_scan_line_scan_line_index_argb_32_pixels_73) | 将整条扫描线写入指定的扫描线索引。 |
| [write_scan_line(scan_line_index, pixels)](#write_scan_line_scan_line_index_pixels_74) | 将整条扫描线写入指定的扫描线索引。 |


### Method: adjust_brightness(brightness) {#adjust_brightness_brightness_1}


```
 adjust_brightness(brightness) 
```

调整图像的亮度。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 亮度 | int | 亮度值。 |

### Method: adjust_contrast(contrast) {#adjust_contrast_contrast_2}


```
 adjust_contrast(contrast) 
```

图像对比

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 对比度 | float | 对比度值（范围为 [-100; 100]） |

### Method: adjust_gamma(gamma) {#adjust_gamma_gamma_3}


```
 adjust_gamma(gamma) 
```

图像的伽马校正。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 伽马 | float | 红、绿、蓝通道的伽马系数 |

### Method: adjust_gamma(gamma_red, gamma_green, gamma_blue) {#adjust_gamma_gamma_red_gamma_green_gamma_blue_4}


```
 adjust_gamma(gamma_red, gamma_green, gamma_blue) 
```

图像的伽马校正。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| gamma_red | float | 红色通道的伽马系数 |
| gamma_green | float | 绿色通道的伽马系数 |
| gamma_blue | float | 蓝色通道的伽马系数 |

### Method: binarize_bradley(brightness_difference) {#binarize_bradley_brightness_difference_5}


```
 binarize_bradley(brightness_difference) 
```

使用 Bradley 的自适应阈值算法和积分图像阈值对图像进行二值化

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| brightness_difference | double | 像素的亮度差值，即该像素与其周围以该像素为中心的 s x s 窗口像素平均值之间的差异。 |

### Method: binarize_bradley(brightness_difference, window_size) {#binarize_bradley_brightness_difference_window_size_6}


```
 binarize_bradley(brightness_difference, window_size) 
```

使用 Bradley 的自适应阈值算法和积分图像阈值对图像进行二值化

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| brightness_difference | double | 像素的亮度差值，即该像素与其周围以该像素为中心的 s x s 窗口像素平均值之间的差异。 |
| window_size | int | 以该像素为中心的 s x s 像素窗口的大小 |

### Method: binarize_fixed(threshold) {#binarize_fixed_threshold_7}


```
 binarize_fixed(threshold) 
```

使用预定义阈值对图像进行二值化

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| threshold | byte | 阈值。如果像素的对应灰度值大于阈值，则赋值为 255；否则为 0。 |

### Method: can_load(file_path)  [static] {#can_load_file_path_8}


```
 can_load(file_path) 
```

确定是否可以从指定的文件路径加载图像。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| file_path | 字符串 | 文件路径。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | <c>true</c> 如果可以从指定文件加载图像；否则为 <c>false</c>。 |


### Method: can_load(file_path, load_options)  [static] {#can_load_file_path_load_options_9}


```
 can_load(file_path, load_options) 
```

确定是否可以从指定的文件路径加载图像，且可选地使用指定的打开选项。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| file_path | 字符串 | 文件路径。 |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | 加载选项。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | <c>true</c> 如果可以从指定文件加载图像；否则为 <c>false</c>。 |


### Method: can_load(stream)  [static] {#can_load_stream_10}


```
 can_load(stream) 
```

确定是否可以从指定的流加载图像。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 流 | _io.BufferedRandom | 要加载的流。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | <c>true</c> 如果可以从指定流加载图像；否则为 <c>false</c>。 |


### Method: can_load(stream, load_options)  [static] {#can_load_stream_load_options_11}


```
 can_load(stream, load_options) 
```

确定是否可以从指定的流加载图像，且可选地使用指定的 <paramref name="loadOptions" />。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 流 | _io.BufferedRandom | 要加载的流。 |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | 加载选项。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | <c>true</c> 如果可以从指定流加载图像；否则为 <c>false</c>。 |


### Method: can_save(options) {#can_save_options_12}


```
 can_save(options) 
```

确定是否可以将图像保存为由传入的保存选项表示的指定文件格式。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | 要使用的保存选项。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | <c>true</c> 如果可以使用传入的保存选项将图像保存为指定的文件格式；否则为 <c>false</c>。 |


### Method: create(image_options, width, height)  [static] {#create_image_options_width_height_13}


```
 create(image_options, width, height) 
```

使用指定的创建选项创建新图像。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | 图像选项。 |
| width | int | 宽度。 |
| height | int | 高度。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | 新创建的图像。 |


### Method: crop(rectangle) {#crop_rectangle_14}


```
 crop(rectangle) 
```

裁剪图像。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 矩形。 |

### Method: dither(dithering_method, bits_count) {#dither_dithering_method_bits_count_15}


```
 dither(dithering_method, bits_count) 
```

对当前图像执行抖动处理。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/psd/python-net/aspose.psd/ditheringmethod) | 抖动方法。 |
| bits_count | int | 抖动的最终位计数。 |

### Method: dither(dithering_method, bits_count, custom_palette) {#dither_dithering_method_bits_count_custom_palette_16}


```
 dither(dithering_method, bits_count, custom_palette) 
```

对当前图像执行抖动处理。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/psd/python-net/aspose.psd/ditheringmethod) | 抖动方法。 |
| bits_count | int | 抖动的最终位计数。 |
| custom_palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | 抖动的自定义调色板。 |

### Method: get_argb_32_pixel(x, y) {#get_argb_32_pixel_x_y_17}


```
 get_argb_32_pixel(x, y) 
```

获取图像的 32 位 ARGB 像素。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| x | int | 像素的 x 位置。 |
| y | int | 像素的 y 位置。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| int | 指定位置的 32 位 ARGB 像素。 |


### Method: get_default_argb_32_pixels(rectangle) {#get_default_argb_32_pixels_rectangle_18}


```
 get_default_argb_32_pixels(rectangle) 
```

获取默认的 32 位 ARGB 像素数组。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 获取像素的矩形。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| int | 默认像素数组。 |


### Method: get_default_options(args) {#get_default_options_args_19}


```
 get_default_options(args) 
```

获取默认选项。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| args | object | 参数。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | 默认选项 |


### Method: get_default_pixels(rectangle, partial_pixel_loader) {#get_default_pixels_rectangle_partial_pixel_loader_20}


```
 get_default_pixels(rectangle, partial_pixel_loader) 
```

使用部分像素加载器获取默认像素数组。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 获取像素的矩形。 |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/psd/python-net/aspose.psd/ipartialargb32pixelloader) | 部分像素加载器。 |

### Method: get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) {#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_21}


```
 get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) 
```

使用部分像素加载器获取默认原始数据数组。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 获取像素的矩形。 |
| partial_raw_data_loader | [IPartialRawDataLoader](/psd/python-net/aspose.psd/ipartialrawdataloader) | 部分原始数据加载器。 |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | 原始数据设置。 |

### Method: get_default_raw_data(rectangle, raw_data_settings) {#get_default_raw_data_rectangle_raw_data_settings_22}


```
 get_default_raw_data(rectangle, raw_data_settings) 
```

获取默认原始数据数组。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 获取原始数据的矩形。 |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | 原始数据设置。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| byte | 默认原始数据数组。 |


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_23}


```
 get_file_format(file_path) 
```

获取文件格式。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| file_path | 字符串 | 文件路径。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [FileFormat](/psd/python-net/aspose.psd/fileformat) | 确定的文件格式。 |


### Method: get_file_format(stream)  [static] {#get_file_format_stream_24}


```
 get_file_format(stream) 
```

获取文件格式。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 流 | _io.BufferedRandom | 流。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [FileFormat](/psd/python-net/aspose.psd/fileformat) | 确定的文件格式。 |


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_25}


```
 get_fitting_rectangle(rectangle, pixels, width, height) 
```

获取适合当前图像的矩形。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 获取适配矩形的矩形。 |
| pixels | int | 32 位 ARGB 像素。 |
| width | int | 对象宽度。 |
| height | int | 对象高度。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | 适配矩形，若未找到适配矩形则抛出异常。 |


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_26}


```
 get_fitting_rectangle(rectangle, width, height) 
```

获取适合当前图像的矩形。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 获取适配矩形的矩形。 |
| width | int | 对象宽度。 |
| height | int | 对象高度。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | 适配矩形，若未找到适配矩形则抛出异常。 |


### Method: get_modify_date(use_default) {#get_modify_date_use_default_27}


```
 get_modify_date(use_default) 
```

获取资源图像上次修改的日期和时间。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| use_default | bool | 如果设置为 <c>true</c>，则使用 FileInfo 中的信息作为默认值。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| datetime | 资源图像上次修改的日期和时间。 |


### Method: get_original_options() {#get_original_options__28}


```
 get_original_options() 
```

获取基于原始文件设置的选项。<br/>            这有助于保持原始图像的位深度和其他参数不变。<br/>            例如，如果我们加载一张每像素 1 位的黑白 PNG 图像，然后使用<br/>            [DataStreamSupporter.save(file_path)](/psd/python-net/aspose.psd/datastreamsupporter/) 方法保存，它将生成每像素 8 位的输出 PNG 图像。<br/>            为避免这种情况并以每像素 1 位保存 PNG 图像，请使用此方法获取相应的保存选项并将它们<br/>            作为第二个参数传递给 [Image.save(file_path, options)](/psd/python-net/aspose.psd/image/) 方法。

**Returns**

| 类型 | 描述 |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | 基于原始文件设置的选项。 |


### Method: get_pixel(x, y) {#get_pixel_x_y_29}


```
 get_pixel(x, y) 
```

获取图像像素。<br/>            性能警告：避免使用此方法遍历所有图像像素，因为这可能导致显著的性能问题。<br/>            为了更高效的像素操作，请使用 `LoadArgb32Pixels` 方法一次性检索整个像素数组。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| x | int | 像素的 x 位置。 |
| y | int | 像素的 y 位置。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | 指定位置的像素颜色。 |


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_30}


```
 get_proportional_height(width, height, new_width) 
```

获取等比例高度。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| width | int | 宽度。 |
| height | int | 高度。 |
| new_width | int | 新的宽度。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| int | 等比例高度。 |


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_31}


```
 get_proportional_width(width, height, new_height) 
```

获取等比例宽度。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| width | int | 宽度。 |
| height | int | 高度。 |
| new_height | int | 新的高度。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| int | 等比例宽度。 |


### Method: get_skew_angle() {#get_skew_angle__32}


```
 get_skew_angle() 
```

  

**Returns**

| 类型 | 描述 |
| :- | :- |
| float |  |


### Method: load(file_path)  [static] {#load_file_path_33}


```
 load(file_path) 
```

从指定文件加载新图像。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| file_path | 字符串 | 加载图像的文件路径。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | 已加载的图像。 |


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_34}


```
 load(file_path, load_options) 
```

从指定文件加载新图像。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| file_path | 字符串 | 加载图像的文件路径。 |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | 加载选项。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | 已加载的图像。 |


### Method: load(stream)  [static] {#load_stream_35}


```
 load(stream) 
```

从指定流加载新图像。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 流 | _io.BufferedRandom | 加载图像的流。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | 已加载的图像。 |


### Method: load(stream, load_options)  [static] {#load_stream_load_options_36}


```
 load(stream, load_options) 
```

从指定流加载新图像。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 流 | _io.BufferedRandom | 加载图像的流。 |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | 加载选项。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | 已加载的图像。 |


### Method: load_argb_32_pixels(rectangle) {#load_argb_32_pixels_rectangle_37}


```
 load_argb_32_pixels(rectangle) 
```

加载 32 位 ARGB 像素。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 用于加载像素的矩形。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| int | 已加载的 32 位 ARGB 像素数组。 |


### Method: load_argb_64_pixels(rectangle) {#load_argb_64_pixels_rectangle_38}


```
 load_argb_64_pixels(rectangle) 
```

加载 64 位 ARGB 像素。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 用于加载像素的矩形。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| long | 已加载的 64 位 ARGB 像素数组。 |


### Method: load_cmyk_32_pixels(rectangle) {#load_cmyk_32_pixels_rectangle_39}


```
 load_cmyk_32_pixels(rectangle) 
```

加载 CMYK 格式的像素。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 用于加载像素的矩形。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| int | 已加载的 CMYK 像素以 32 位整数值呈现。 |


### Method: load_cmyk_pixels(rectangle) {#load_cmyk_pixels_rectangle_40}


```
 load_cmyk_pixels(rectangle) 
```

加载 CMYK 格式的像素。<br/>            此方法已弃用。请使用更有效的 [RasterImage.load_cmyk_32_pixels(rectangle)](/psd/python-net/aspose.psd/rasterimage/) 方法。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 用于加载像素的矩形。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | 已加载的 CMYK 像素数组。 |


### Method: load_partial_argb_32_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_41}


```
 load_partial_argb_32_pixels(rectangle, partial_pixel_loader) 
```

按包部分加载 32 位 ARGB 像素。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 所需的矩形。 |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/psd/python-net/aspose.psd/ipartialargb32pixelloader) | 32 位 ARGB 像素加载器。 |

### Method: load_partial_pixels(desired_rectangle, pixel_loader) {#load_partial_pixels_desired_rectangle_pixel_loader_42}


```
 load_partial_pixels(desired_rectangle, pixel_loader) 
```

按批次部分加载像素。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| desired_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 所需的矩形。 |
| pixel_loader | [IPartialPixelLoader](/psd/python-net/aspose.psd/ipartialpixelloader) | 像素加载器。 |

### Method: load_pixels(rectangle) {#load_pixels_rectangle_43}


```
 load_pixels(rectangle) 
```

加载像素。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 用于加载像素的矩形。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | 已加载的像素数组。 |


### Method: load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_44}


```
 load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) 
```

加载原始数据。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 用于加载原始数据的矩形。 |
| dest_image_bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 目标图像边界。 |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | 用于已加载数据的原始数据设置。注意，如果数据不是指定的格式，则会执行数据转换。 |
| raw_data_loader | [IPartialRawDataLoader](/psd/python-net/aspose.psd/ipartialrawdataloader) | 原始数据加载器。 |

### Method: load_raw_data(rectangle, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_raw_data_settings_raw_data_loader_45}


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

### Method: read_argb_32_scan_line(scan_line_index) {#read_argb_32_scan_line_scan_line_index_46}


```
 read_argb_32_scan_line(scan_line_index) 
```

按指定的扫描线索引读取整条扫描线。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| scan_line_index | int | 扫描线的零基索引。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| int | 扫描线的 32 位 ARGB 颜色值数组。 |


### Method: read_scan_line(scan_line_index) {#read_scan_line_scan_line_index_47}


```
 read_scan_line(scan_line_index) 
```

按指定的扫描线索引读取整条扫描线。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| scan_line_index | int | 扫描线的零基索引。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | 扫描线像素颜色值数组。 |


### Method: resize(new_width, new_height) {#resize_new_width_new_height_48}


```
 resize(new_width, new_height) 
```

调整图像大小。使用默认的 [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/)。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| new_width | int | 新的宽度。 |
| new_height | int | 新的高度。 |

### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_49}


```
 resize(new_width, new_height, resize_type) 
```

调整图像大小。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| new_width | int | 新的宽度。 |
| new_height | int | 新的高度。 |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | 调整大小的类型。 |

### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_50}


```
 resize(new_width, new_height, settings) 
```

调整图像大小。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| new_width | int | 新的宽度。 |
| new_height | int | 新的高度。 |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | 调整大小的设置。 |

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_51}


```
 resize_height_proportionally(new_height) 
```

等比例调整高度。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| new_height | int | 新的高度。 |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_52}


```
 resize_height_proportionally(new_height, resize_type) 
```

等比例调整高度。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| new_height | int | 新的高度。 |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | 调整大小的类型。 |

### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_53}


```
 resize_height_proportionally(new_height, settings) 
```

等比例调整高度。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| new_height | int | 新的高度。 |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | 图像调整大小设置。 |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_54}


```
 resize_width_proportionally(new_width) 
```

等比例调整宽度。使用默认的 [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/)。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| new_width | int | 新的宽度。 |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_55}


```
 resize_width_proportionally(new_width, resize_type) 
```

等比例调整宽度。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| new_width | int | 新的宽度。 |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | 调整大小的类型。 |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_56}


```
 resize_width_proportionally(new_width, settings) 
```

等比例调整宽度。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| new_width | int | 新的宽度。 |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | 图像调整大小设置。 |

### Method: rotate(angle, resize_proportionally, background_color) {#rotate_angle_resize_proportionally_background_color_57}


```
 rotate(angle, resize_proportionally, background_color) 
```

围绕中心旋转图像。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 角度 | float | 旋转角度（单位：度）。正值将顺时针旋转。 |
| resize_proportionally | bool | 如果设置为 <c>true</c>，图像尺寸将根据旋转矩形（角点）投影进行更改；否则保持尺寸不变，仅旋转内部图像内容。 |
| background_color | [Color](/psd/python-net/aspose.psd/color) | 背景颜色。 |

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_58}


```
 rotate_flip(rotate_flip_type) 
```

旋转、翻转或同时旋转并翻转图像。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/psd/python-net/aspose.psd/rotatefliptype) | 旋转翻转类型。 |

### Method: save(file_path) {#save_file_path_59}


```
 save(file_path) 
```

将对象的数据保存到指定的文件位置。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| file_path | 字符串 | 用于保存对象数据的文件路径。 |

### Method: save(file_path, options) {#save_file_path_options_60}


```
 save(file_path, options) 
```

根据保存选项，将对象的数据以指定的文件格式保存到指定的文件位置。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| file_path | 字符串 | 文件路径。 |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | 选项。 |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_61}


```
 save(file_path, options, bounds_rectangle) 
```

根据保存选项，将对象的数据以指定的文件格式保存到指定的文件位置。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| file_path | 字符串 | 文件路径。 |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | 选项。 |
| bounds_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 目标图像边界矩形。将空矩形设置为使用源边界。 |

### Method: save(file_path, over_write) {#save_file_path_over_write_62}


```
 save(file_path, over_write) 
```

将对象的数据保存到指定的文件位置。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| file_path | 字符串 | 用于保存对象数据的文件路径。 |
| over_write | bool | 如果设置为 <c>true</c>，则覆盖文件内容；否则将追加。 |

### Method: save(stream) {#save_stream_63}


```
 save(stream) 
```

将对象的数据保存到指定的流中。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 流 | _io.BufferedRandom | 用于保存对象数据的流。 |

### Method: save(stream, options_base) {#save_stream_options_base_64}


```
 save(stream, options_base) 
```

根据保存选项，将图像的数据以指定的文件格式保存到指定的流中。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 流 | _io.BufferedRandom | 用于保存图像数据的流。 |
| options_base | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | 保存选项。 |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_65}


```
 save(stream, options_base, bounds_rectangle) 
```

根据保存选项，将图像的数据以指定的文件格式保存到指定的流中。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 流 | _io.BufferedRandom | 用于保存图像数据的流。 |
| options_base | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | 保存选项。 |
| bounds_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 目标图像边界矩形。设置为空矩形以使用源边界。 |

### Method: save_argb_32_pixels(rectangle, pixels) {#save_argb_32_pixels_rectangle_pixels_66}


```
 save_argb_32_pixels(rectangle, pixels) 
```

保存 32 位 ARGB 像素。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 用于保存像素的矩形。 |
| pixels | int | 32 位 ARGB 像素数组。 |

### Method: save_pixels(rectangle, pixels) {#save_pixels_rectangle_pixels_67}


```
 save_pixels(rectangle, pixels) 
```

保存像素（特定格式的方法）。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 用于保存像素的矩形。 |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) | 32 位 ARGB 像素数组。 |

### Method: save_raw_data(data, data_offset, rectangle, raw_data_settings) {#save_raw_data_data_data_offset_rectangle_raw_data_settings_68}


```
 save_raw_data(data, data_offset, rectangle, raw_data_settings) 
```

保存原始数据。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 数据 | byte | 原始数据。 |
| data_offset | int | 起始原始数据偏移。 |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 原始数据矩形。 |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | 原始数据所在的设置。 |

### Method: set_argb_32_pixel(x, y, argb_32_color) {#set_argb_32_pixel_x_y_argb_32_color_69}


```
 set_argb_32_pixel(x, y, argb_32_color) 
```

为指定位置设置图像的 32 位 ARGB 像素。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| x | int | 像素的 x 位置。 |
| y | int | 像素的 y 位置。 |
| argb_32_color | int | 指定位置的 32 位 ARGB 像素。 |

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_70}


```
 set_palette(palette, update_colors) 
```

设置图像调色板。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | 要设置的调色板。 |
| update_colors | bool | 如果设置为 <c>true</c>，颜色将根据新调色板进行更新；否则颜色索引保持不变。请注意，如果某些索引没有对应的调色板条目，未更改的索引可能在加载时导致图像崩溃。 |

### Method: set_pixel(x, y, color) {#set_pixel_x_y_color_71}


```
 set_pixel(x, y, color) 
```

为指定位置设置图像像素。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| x | int | 像素的 x 位置。 |
| y | int | 像素的 y 位置。 |
| color | [Color](/psd/python-net/aspose.psd/color) | 指定位置的像素颜色。 |

### Method: to_bitmap() {#to_bitmap__72}


```
 to_bitmap() 
```

  

**Returns**

| 类型 | 描述 |
| :- | :- |
| aspose.pydrawing.Bitmap |  |


### Method: write_argb_32_scan_line(scan_line_index, argb_32_pixels) {#write_argb_32_scan_line_scan_line_index_argb_32_pixels_73}


```
 write_argb_32_scan_line(scan_line_index, argb_32_pixels) 
```

将整条扫描线写入指定的扫描线索引。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| scan_line_index | int | 扫描线的零基索引。 |
| argb_32_pixels | int | 要写入的 32 位 ARGB 颜色数组。 |

### Method: write_scan_line(scan_line_index, pixels) {#write_scan_line_scan_line_index_pixels_74}


```
 write_scan_line(scan_line_index, pixels) 
```

将整条扫描线写入指定的扫描线索引。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| scan_line_index | int | 扫描线的零基索引。 |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) | 要写入的像素颜色数组。 |

