---
title: "PsdImage 类"
type: docs
weight: 1760
url: /zh/python-net/aspose.psd.fileformats.psd/psdimage/
---

**Summary:** Defines the PsdImage class that provides the ability to load, edit, save PSD files as well as<br/>            update properties, add watermarks, perform graphics operations or convert one file format to another.<br/>            Aspose.PSD supports import as a layer and export to the following formats:<br/>            Png, Jpeg, Jpeg2000, Gif, Bmp, Tiff, Psd, Psb along with export to Pdf with selectable text

**Module:** [aspose.psd.fileformats.psd](/psd/python-net/aspose.psd.fileformats.psd/)

**Full Name:** aspose.psd.fileformats.psd.PsdImage

**Inheritance:** IObjectWithBounds, IRasterImageArgb32PixelLoader, IRasterImageRawDataLoader, RasterCachedImage

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [PsdImage(path)](#PsdImage_path_1) | 从指定路径的光栅图像（路径中不是 psd 图像）初始化 [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) 类的新实例。用于使用默认参数初始化 psd 图像 - 颜色模式 - rgb，4 通道，每通道 8 位，压缩方式 - Raw。 |
| [PsdImage(path, color_mode, channel_bit_depth, channels, psd_version, compression)](#PsdImage_path_color_mode_channel_bit_depth_channels_psd_version_compression_2) | 从指定路径的光栅图像（路径中不是 psd 图像）并使用构造函数参数初始化 [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) 类的新实例。 |
| [PsdImage(raster_image)](#PsdImage_raster_image_3) | 从现有光栅图像（不是 psd 图像）并使用 RGB 颜色模式、4 通道、每通道 8 位且无压缩，初始化 [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) 类的新实例。 |
| [PsdImage(raster_image, color_mode, channel_bit_depth, channels, psd_version, compression)](#PsdImage_raster_image_color_mode_channel_bit_depth_channels_psd_version_compression_4) | 从现有光栅图像（不是 psd 图像）并使用构造函数参数初始化 [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) 类的新实例。 |
| [PsdImage(stream)](#PsdImage_stream_5) | 从指定路径的光栅图像（流中不是 psd 图像）初始化 [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) 类的新实例。用于使用默认参数初始化 psd 图像 - 颜色模式 - rgb，4 通道，每通道 8 位，压缩方式 - Raw。 |
| [PsdImage(stream, color_mode, channel_bit_depth, channels, psd_version, compression)](#PsdImage_stream_color_mode_channel_bit_depth_channels_psd_version_compression_6) | 从指定路径的光栅图像（流中不是 psd 图像）并使用构造函数参数初始化 [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) 类的新实例。 |
| [PsdImage(width, height)](#PsdImage_width_height_7) | 使用指定的宽度和高度初始化 [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) 类的新实例。用于初始化空的 psd 图像。 |
| [PsdImage(width, height, color_palette, color_mode, channel_bit_depth, channels, psd_version, compression)](#PsdImage_width_height_color_palette_color_mode_channel_bit_depth_channels_psd_version_compression_8) | 使用指定的宽度、长度、调色板、颜色模式、通道数、通道位深以及指定的压缩模式参数初始化 [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) 类的新实例。用于初始化空的 psd 图像。 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| DEFAULT_VERSION [static] | int | r | 默认的 PSD 版本。 |
| active_layer | [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | r/w | 获取或设置活动图层。 |
| auto_adjust_palette | bool | 读/写 | 获取或设置指示是否自动调整调色板的值。 |
| background_color | [Color](/psd/python-net/aspose.psd/color) | r/w | 获取或设置背景颜色的值。 |
| bits_per_channel | int | r | 获取每通道的位数。 |
| bits_per_pixel | int | r | 获取图像每像素位数。 |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | 获取对象边界。 |
| buffer_size_hint | int | 读/写 | 获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| channels_count | int | r | 获取 PSD 通道数。 |
| cmyk_color_profile | [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/) | r/w | 获取或设置 CMYK PSD 图像的 CMYK 颜色配置文件。必须与 RgbColorProfile 配对以实现正确的颜色转换。 |
| color_mode | [ColorModes](/psd/python-net/aspose.psd.fileformats.psd/colormodes) | r/w | 获取或设置颜色模式。 |
| compression | [CompressionMethod](/psd/python-net/aspose.psd.fileformats.psd/compressionmethod) | r | 获取压缩方法。 |
| container | [Image](/psd/python-net/aspose.psd/image) | r | 获取 [Image](/psd/python-net/aspose.psd/image/) 容器。 |
| data_stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | r | 获取对象的数据流。 |
| 已释放 | bool | r | 获取一个值，指示此实例是否已释放。 |
| file_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | 获取文件格式的值 |
| global_angle | int | 读/写 | 获取或设置全局角度。 |
| global_layer_mask_info | [GlobalLayerMaskInfo](/psd/python-net/aspose.psd.fileformats.psd.layers/globallayermaskinfo/) | r | 获取全局图层蒙版信息。 |
| global_layer_resources | [LayerResource[]](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/) | r/w | 获取或设置全局图层资源。 |
| gray_color_profile | [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/) | r/w | 获取或设置灰度（单色）PSD 图像的 GRAY 颜色配置文件。 |
| has_alpha | bool | r | 获取或设置此 [RasterImage](/psd/python-net/aspose.psd/rasterimage/) 的垂直分辨率（每英寸像素数）。 |
| has_background_color | bool | 读/写 | 获取或设置一个值，指示图像是否具有背景颜色。 |
| has_transparency_data | bool | 读/写 | 获取或设置一个值，指示在指定图层数据时，第一个 alpha 通道是否包含合并结果的透明度数据。 |
| has_transparent_color | bool | 读/写 | 获取一个值，指示图像是否具有透明颜色。 |
| height | int | r | 获取图像高度。 |
| horizontal_resolution | double | r/w | 获取或设置此 [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) 的水平分辨率（每英寸像素数）。 |
| image_opacity | float | r | 获取此图像的不透明度。 |
| image_resources | [ResourceBlock[]](/psd/python-net/aspose.psd.fileformats.psd/resourceblock) | r/w | 获取或设置 PSD 图像资源。 |
| interrupt_monitor | [InterruptMonitor](/psd/python-net/aspose.psd.multithreading/interruptmonitor/) | r/w | 获取或设置中断监视器。 |
| is_cached | bool | r | 获取一个值，指示图像数据当前是否已缓存。 |
| is_flatten | bool | r | 获取一个值，指示 PSD 图像是否已展平。 |
| is_raw_data_available | bool | r | 获取指示是否支持原始数据加载的值。 |
| layers | [Layer[]](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | r/w | 获取或设置 PSD 图层。 |
| linked_layers_manager | [LinkedLayersManager](/psd/python-net/aspose.psd.fileformats.psd.layers/linkedlayersmanager/) | r | 获取链接图层管理器。 |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | 获取或设置颜色调色板。当像素直接表示时，不使用颜色调色板。 |
| premultiply_components | bool | 读/写 | 获取或设置一个值，指示图像组件是否必须预乘。 |
| raw_custom_color_converter | [IColorConverter](/psd/python-net/aspose.psd/icolorconverter) | r/w | 获取或设置自定义颜色转换器 |
| raw_data_format | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | 获取原始数据格式。 |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | r | 获取当前的原始数据设置。注意，使用这些设置时，数据将在不进行转换的情况下加载。 |
| raw_fallback_index | int | 读/写 | 获取或设置在调色板索引超出范围时使用的回退索引 |
| raw_indexed_color_converter | [IIndexedColorConverter](/psd/python-net/aspose.psd/iindexedcolorconverter) | r/w | 获取或设置索引颜色转换器 |
| raw_line_size | int | r | 获取原始行大小（字节）。 |
| rgb_color_profile | [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/) | r/w | 获取或设置 CMYK PSD 图像的 RGB 颜色配置文件。必须与 CmykColorProfile 配对以实现正确的颜色转换。 |
| size | [Size](/psd/python-net/aspose.psd/size) | r | 获取对象的大小。 |
| smart_object_provider | [SmartObjectProvider](/psd/python-net/aspose.psd.fileformats.psd/smartobjectprovider) | r | 获取智能对象提供程序。 |
| timeline | [Timeline](/psd/python-net/aspose.psd.fileformats.psd.layers.animation/timeline/) | r | 获取此 [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) 的 [PsdImage.timeline](/psd/python-net/aspose.psd.fileformats.psd/psdimage/)。 |
| transparent_color | [Color](/psd/python-net/aspose.psd/color) | r/w | 获取图像透明颜色。 |
| update_xmp_data | bool | 读/写 | 获取或设置一个值，指示是否更新 XMP 元数据。 |
| use_palette | bool | r | 获取一个值，指示是否使用图像调色板。 |
| use_raw_data | bool | 读/写 | 获取或设置一个值，指示在可用原始数据加载时是否使用原始数据加载。 |
| version | int | 读/写 | 获取或设置版本。 |
| vertical_resolution | double | r/w | 获取或设置此 [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) 的垂直分辨率（每英寸像素数）。 |
| width | int | r | 获取图像宽度。 |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | 获取或设置 XMP 元数据。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_black_white_adjustment_layer()](#add_black_white_adjustment_layer__1) | 添加黑白调整图层。 |
| [add_brightness_contrast_adjustment_layer(brightness, contrast)](#add_brightness_contrast_adjustment_layer_brightness_contrast_2) | 添加亮度/对比度调整图层。 |
| [add_channel_mixer_adjustment_layer()](#add_channel_mixer_adjustment_layer__3) | 添加带默认参数的通道混合器调整图层。 |
| [add_color_balance_adjustment_layer()](#add_color_balance_adjustment_layer__4) | 添加色彩平衡调整图层。 |
| [add_curves_adjustment_layer()](#add_curves_adjustment_layer__5) | 添加 Curves 调整图层。 |
| [add_exposure_adjustment_layer(exposure, offset, gamma_correction)](#add_exposure_adjustment_layer_exposure_offset_gamma_correction_6) | 添加曝光调整图层。 |
| [add_gradient_map_adjustment_layer()](#add_gradient_map_adjustment_layer__7) | 添加 GradientMap 调整图层。 |
| [add_hue_saturation_adjustment_layer()](#add_hue_saturation_adjustment_layer__8) | 添加色相/饱和度调整图层。 |
| [add_invert_adjustment_layer()](#add_invert_adjustment_layer__9) | 添加反相调整图层。 |
| [add_layer(layer)](#add_layer_layer_10) | 添加图层。 |
| [add_layer_group(group_name, index, start_behaviour)](#add_layer_group_group_name_index_start_behaviour_11) | 添加图层组。 |
| [add_levels_adjustment_layer()](#add_levels_adjustment_layer__12) | 添加 Levels 调整图层。 |
| [add_photo_filter_layer(color)](#add_photo_filter_layer_color_13) | 添加 PhotoFilter 图层。 |
| [add_posterize_adjustment_layer()](#add_posterize_adjustment_layer__14) | 添加 Posterize 调整图层。 |
| [add_regular_layer()](#add_regular_layer__15) | 添加一个新的常规图层。 |
| [add_selective_color_adjustment_layer()](#add_selective_color_adjustment_layer__16) | 添加选择性颜色调整图层。 |
| [add_shape_layer()](#add_shape_layer__17) | 添加空的 Shape 图层。<br/>            没有路径。它们应在保存前添加到 shape 图层。 |
| [add_text_layer(text, rect)](#add_text_layer_text_rect_18) | 添加一个新的 Text 图层。 |
| [add_threshold_adjustment_layer()](#add_threshold_adjustment_layer__19) | 添加 Threshold 调整图层。 |
| [add_vibrance_adjustment_layer()](#add_vibrance_adjustment_layer__20) | 添加 Vibrance 调整图层。 |
| [adjust_brightness(brightness)](#adjust_brightness_brightness_21) | 调整图像的亮度。 |
| [adjust_contrast(contrast)](#adjust_contrast_contrast_22) | 图像对比 |
| [adjust_gamma(gamma)](#adjust_gamma_gamma_23) | 图像的伽马校正。 |
| [adjust_gamma(gamma_red, gamma_green, gamma_blue)](#adjust_gamma_gamma_red_gamma_green_gamma_blue_24) | 图像的伽马校正。 |
| [binarize_bradley(brightness_difference)](#binarize_bradley_brightness_difference_25) | 使用 Bradley 的自适应阈值算法和积分图像阈值对图像进行二值化 |
| [binarize_bradley(brightness_difference, window_size)](#binarize_bradley_brightness_difference_window_size_26) | 使用 Bradley 的自适应阈值算法和积分图像阈值对图像进行二值化 |
| [binarize_fixed(threshold)](#binarize_fixed_threshold_27) | 使用预定义阈值对图像进行二值化 |
| binarize_otsu() | 使用 Otsu 阈值对图像进行二值化 |
| cache_data() | 缓存数据，并确保不会从底层 [DataStreamSupporter.data_stream_container](/psd/python-net/aspose.psd/datastreamsupporter/) 进行额外的数据加载。 |
| [can_load(file_path)](#can_load_file_path_28) | 确定是否可以从指定的文件路径加载图像。 |
| [can_load(file_path, load_options)](#can_load_file_path_load_options_29) | 确定是否可以从指定的文件路径加载图像，且可选地使用指定的打开选项。 |
| [can_load(stream)](#can_load_stream_30) | 确定是否可以从指定的流加载图像。 |
| [can_load(stream, load_options)](#can_load_stream_load_options_31) | 确定是否可以从指定的流加载图像，且可选地使用指定的 <paramref name="loadOptions" />。 |
| [can_save(options)](#can_save_options_32) | 确定是否可以将图像保存为由传入的保存选项表示的指定文件格式。 |
| [convert(new_options)](#convert_new_options_33) | 将此图像格式转换为选项中指定的格式。 |
| [create(image_options, width, height)](#create_image_options_width_height_34) | 使用指定的创建选项创建新图像。 |
| crop(left_shift, right_shift, top_shift, bottom_shift) |  |
| [crop(rectangle)](#crop_rectangle_35) | 裁剪图像。 |
| [dither(dithering_method, bits_count)](#dither_dithering_method_bits_count_36) | 对当前图像执行抖动处理。 |
| [dither(dithering_method, bits_count, custom_palette)](#dither_dithering_method_bits_count_custom_palette_37) | 对当前图像执行抖动处理。 |
| [filter(rectangle, options)](#filter_rectangle_options_38) | 过滤指定的矩形。 |
| flatten_image() | 将所有图层展平。 |
| [get_argb_32_pixel(x, y)](#get_argb_32_pixel_x_y_39) | 获取图像的 32 位 ARGB 像素。 |
| [get_default_argb_32_pixels(rectangle)](#get_default_argb_32_pixels_rectangle_40) | 获取默认的 32 位 ARGB 像素数组。 |
| [get_default_options(args)](#get_default_options_args_41) | 获取默认选项。 |
| [get_default_pixels(rectangle, partial_pixel_loader)](#get_default_pixels_rectangle_partial_pixel_loader_42) | 使用部分像素加载器获取默认像素数组。 |
| [get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings)](#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_43) | 使用部分像素加载器获取默认原始数据数组。 |
| [get_default_raw_data(rectangle, raw_data_settings)](#get_default_raw_data_rectangle_raw_data_settings_44) | 获取默认原始数据数组。 |
| [get_file_format(file_path)](#get_file_format_file_path_45) | 获取文件格式。 |
| [get_file_format(stream)](#get_file_format_stream_46) | 获取文件格式。 |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_47) | 获取适合当前图像的矩形。 |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_48) | 获取适合当前图像的矩形。 |
| [get_modify_date(use_default)](#get_modify_date_use_default_49) | 获取资源图像上次修改的日期和时间。 |
| [get_original_options()](#get_original_options__50) | 获取基于原始文件设置的选项。<br/>            这有助于保持原始图像的位深度和其他参数不变。<br/>            例如，如果我们加载一张每像素 1 位的黑白 PNG 图像，然后使用<br/>            [DataStreamSupporter.save(file_path)](/psd/python-net/aspose.psd/datastreamsupporter/) 方法保存，它将生成每像素 8 位的输出 PNG 图像。<br/>            为避免这种情况并以每像素 1 位保存 PNG 图像，请使用此方法获取相应的保存选项并将它们<br/>            作为第二个参数传递给 [Image.save(file_path, options)](/psd/python-net/aspose.psd/image/) 方法。 |
| [get_pixel(x, y)](#get_pixel_x_y_51) | 获取图像像素。<br/>            性能警告：避免使用此方法遍历所有图像像素，因为这可能导致显著的性能问题。<br/>            为了更高效的像素操作，请使用 `LoadArgb32Pixels` 方法一次性检索整个像素数组。 |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_52) | 获取等比例高度。 |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_53) | 获取等比例宽度。 |
| [get_skew_angle()](#get_skew_angle__54) |    |
| grayscale() | 将图像转换为灰度表示 |
| [load(file_path)](#load_file_path_55) | 从指定文件加载新图像。 |
| [load(file_path, load_options)](#load_file_path_load_options_56) | 从指定文件加载新图像。 |
| [load(stream)](#load_stream_57) | 从指定流加载新图像。 |
| [load(stream, load_options)](#load_stream_load_options_58) | 从指定流加载新图像。 |
| [load_argb_32_pixels(rectangle)](#load_argb_32_pixels_rectangle_59) | 加载 32 位 ARGB 像素。 |
| [load_argb_64_pixels(rectangle)](#load_argb_64_pixels_rectangle_60) | 加载 64 位 ARGB 像素。 |
| [load_cmyk_32_pixels(rectangle)](#load_cmyk_32_pixels_rectangle_61) | 加载 CMYK 格式的像素。 |
| [load_cmyk_pixels(rectangle)](#load_cmyk_pixels_rectangle_62) | 加载 CMYK 格式的像素。<br/>            此方法已弃用。请使用更有效的 [RasterImage.load_cmyk_32_pixels(rectangle)](/psd/python-net/aspose.psd/rasterimage/) 方法。 |
| [load_partial_argb_32_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_63) | 部分加载 32 位 ARGB 像素（按块）。 |
| [load_partial_pixels(desired_rectangle, pixel_loader)](#load_partial_pixels_desired_rectangle_pixel_loader_64) | 按批次部分加载像素。 |
| [load_pixels(rectangle)](#load_pixels_rectangle_65) | 加载像素。 |
| [load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_66) | 加载原始数据。 |
| [load_raw_data(rectangle, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_raw_data_settings_raw_data_loader_67) | 加载原始数据。 |
| [merge_layers(bottom_layer, top_layer)](#merge_layers_bottom_layer_top_layer_68) | 合并图层。 |
| normalize_angle() |  |
| normalize_angle(resize_proportionally, background_color) |  |
| [read_argb_32_scan_line(scan_line_index)](#read_argb_32_scan_line_scan_line_index_69) | 按指定的扫描线索引读取整条扫描线。 |
| [read_scan_line(scan_line_index)](#read_scan_line_scan_line_index_70) | 按指定的扫描线索引读取整条扫描线。 |
| [replace_color(old_color, old_color_diff, new_color)](#replace_color_old_color_old_color_diff_new_color_71) | 在允许的差异范围内将一种颜色替换为另一种颜色，并保留原始 alpha 值以保持平滑边缘。 |
| [replace_color(old_color_argb, old_color_diff, new_color_argb)](#replace_color_old_color_argb_old_color_diff_new_color_argb_72) | 在允许的差异范围内将一种颜色替换为另一种颜色，并保留原始 alpha 值以保持平滑边缘。 |
| [replace_non_transparent_colors(new_color)](#replace_non_transparent_colors_new_color_73) | 将所有非透明颜色替换为新颜色，并保留原始的 alpha 值以实现平滑边缘。<br/>            注意：如果在没有透明度的图像上使用，它将把所有颜色替换为单一颜色。 |
| [replace_non_transparent_colors(new_color_argb)](#replace_non_transparent_colors_new_color_argb_74) | 将所有非透明颜色替换为新颜色，并保留原始的 alpha 值以实现平滑边缘。<br/>            注意：如果在没有透明度的图像上使用，它将把所有颜色替换为单一颜色。 |
| [resize(new_width, new_height)](#resize_new_width_new_height_75) | 调整图像大小。使用默认的 [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/)。 |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_76) | 调整图像大小。 |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_77) | 调整图像大小。 |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_78) | 等比例调整高度。 |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_79) | 等比例调整高度。 |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_80) | 等比例调整高度。 |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_81) | 等比例调整宽度。使用默认的 [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/)。 |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_82) | 等比例调整宽度。 |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_83) | 等比例调整宽度。 |
| [rotate(angle)](#rotate_angle_84) | 围绕中心旋转图像。 |
| [rotate(angle, resize_proportionally, background_color)](#rotate_angle_resize_proportionally_background_color_85) | 围绕中心旋转图像。 |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_86) | 旋转、翻转或同时旋转并翻转图像。 |
| save() | 将图像数据保存到底层流。 |
| [save(file_path)](#save_file_path_87) | 将对象的数据保存到指定的文件位置。 |
| [save(file_path, options)](#save_file_path_options_88) | 根据保存选项，将对象的数据以指定的文件格式保存到指定的文件位置。 |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_89) | 根据保存选项，将对象的数据以指定的文件格式保存到指定的文件位置。 |
| [save(file_path, over_write)](#save_file_path_over_write_90) | 将对象的数据保存到指定的文件位置。 |
| [save(stream)](#save_stream_91) | 将对象的数据保存到指定的流中。 |
| [save(stream, options_base)](#save_stream_options_base_92) | 根据保存选项，将图像的数据以指定的文件格式保存到指定的流中。 |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_93) | 根据保存选项，将图像的数据以指定的文件格式保存到指定的流中。 |
| [save_argb_32_pixels(rectangle, pixels)](#save_argb_32_pixels_rectangle_pixels_94) | 保存 32 位 ARGB 像素。 |
| save_cmyk_32_pixels(rectangle, pixels) |  |
| save_cmyk_pixels(rectangle, pixels) |  |
| [save_pixels(rectangle, pixels)](#save_pixels_rectangle_pixels_95) | 保存像素（特定格式的方法）。 |
| [save_raw_data(data, data_offset, rectangle, raw_data_settings)](#save_raw_data_data_data_offset_rectangle_raw_data_settings_96) | 保存原始数据。 |
| [set_argb_32_pixel(x, y, argb_32_color)](#set_argb_32_pixel_x_y_argb_32_color_97) | 为指定位置设置图像的 32 位 ARGB 像素。 |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_98) | 设置图像调色板。 |
| [set_pixel(x, y, color)](#set_pixel_x_y_color_99) | 为指定位置设置图像像素。 |
| [set_resolution(dpi_x, dpi_y)](#set_resolution_dpi_x_dpi_y_100) | 设置此 [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) 的分辨率。 |
| [to_bitmap()](#to_bitmap__101) |    |
| [write_argb_32_scan_line(scan_line_index, argb_32_pixels)](#write_argb_32_scan_line_scan_line_index_argb_32_pixels_102) | 将整条扫描线写入指定的扫描线索引。 |
| [write_scan_line(scan_line_index, pixels)](#write_scan_line_scan_line_index_pixels_103) | 将整条扫描线写入指定的扫描线索引。 |


### Constructor: PsdImage(path) {#PsdImage_path_1}


```
 PsdImage(path) 
```

从指定路径的光栅图像（路径中不是 psd 图像）初始化 [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) 类的新实例。用于使用默认参数初始化 psd 图像 - 颜色模式 - rgb，4 通道，每通道 8 位，压缩方式 - Raw。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 路径 | 字符串 | 用于加载像素和调色板数据并进行初始化的路径。 |

### Constructor: PsdImage(path, color_mode, channel_bit_depth, channels, psd_version, compression) {#PsdImage_path_color_mode_channel_bit_depth_channels_psd_version_compression_2}


```
 PsdImage(path, color_mode, channel_bit_depth, channels, psd_version, compression) 
```

从指定路径的光栅图像（路径中不是 psd 图像）并使用构造函数参数初始化 [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) 类的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 路径 | 字符串 | 用于加载像素和调色板数据并进行初始化的路径。 |
| color_mode | [ColorModes](/psd/python-net/aspose.psd.fileformats.psd/colormodes) | 颜色模式。 |
| channel_bit_depth | short | 每个通道的 PSD 位深度。 |
| channels | short | PSD 通道数量。 |
| psd_version | int | PSD 版本。 |
| compression | [CompressionMethod](/psd/python-net/aspose.psd.fileformats.psd/compressionmethod) | 要使用的压缩方式。 |

### Constructor: PsdImage(raster_image) {#PsdImage_raster_image_3}


```
 PsdImage(raster_image) 
```

从现有光栅图像（不是 psd 图像）并使用 RGB 颜色模式、4 通道、每通道 8 位且无压缩，初始化 [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) 类的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| raster_image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | 用于加载像素和调色板数据并进行初始化的图像。 |

### Constructor: PsdImage(raster_image, color_mode, channel_bit_depth, channels, psd_version, compression) {#PsdImage_raster_image_color_mode_channel_bit_depth_channels_psd_version_compression_4}


```
 PsdImage(raster_image, color_mode, channel_bit_depth, channels, psd_version, compression) 
```

从现有光栅图像（不是 psd 图像）并使用构造函数参数初始化 [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) 类的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| raster_image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | 用于加载像素和调色板数据并进行初始化的图像。 |
| color_mode | [ColorModes](/psd/python-net/aspose.psd.fileformats.psd/colormodes) | 颜色模式。 |
| channel_bit_depth | short | 每个通道的 PSD 位深度。 |
| channels | short | PSD 通道数量。 |
| psd_version | int | PSD 版本。 |
| compression | [CompressionMethod](/psd/python-net/aspose.psd.fileformats.psd/compressionmethod) | 要使用的压缩方式。 |

### Constructor: PsdImage(stream) {#PsdImage_stream_5}


```
 PsdImage(stream) 
```

从指定路径的光栅图像（流中不是 psd 图像）初始化 [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) 类的新实例。用于使用默认参数初始化 psd 图像 - 颜色模式 - rgb，4 通道，每通道 8 位，压缩方式 - Raw。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 流 | _io.BufferedRandom | 用于加载像素和调色板数据并进行初始化的流。 |

### Constructor: PsdImage(stream, color_mode, channel_bit_depth, channels, psd_version, compression) {#PsdImage_stream_color_mode_channel_bit_depth_channels_psd_version_compression_6}


```
 PsdImage(stream, color_mode, channel_bit_depth, channels, psd_version, compression) 
```

从指定路径的光栅图像（流中不是 psd 图像）并使用构造函数参数初始化 [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) 类的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 流 | _io.BufferedRandom | 用于加载像素和调色板数据并进行初始化的流。 |
| color_mode | [ColorModes](/psd/python-net/aspose.psd.fileformats.psd/colormodes) | 颜色模式。 |
| channel_bit_depth | short | 每个通道的 PSD 位深度。 |
| channels | short | PSD 通道数量。 |
| psd_version | int | PSD 版本。 |
| compression | [CompressionMethod](/psd/python-net/aspose.psd.fileformats.psd/compressionmethod) | 要使用的压缩方式。 |

### Constructor: PsdImage(width, height) {#PsdImage_width_height_7}


```
 PsdImage(width, height) 
```

使用指定的宽度和高度初始化 [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) 类的新实例。用于初始化空的 psd 图像。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| width | int | 图像宽度。 |
| height | int | 图像高度。 |

### Constructor: PsdImage(width, height, color_palette, color_mode, channel_bit_depth, channels, psd_version, compression) {#PsdImage_width_height_color_palette_color_mode_channel_bit_depth_channels_psd_version_compression_8}


```
 PsdImage(width, height, color_palette, color_mode, channel_bit_depth, channels, psd_version, compression) 
```

使用指定的宽度、长度、调色板、颜色模式、通道数、通道位深以及指定的压缩模式参数初始化 [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) 类的新实例。用于初始化空的 psd 图像。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| width | int | 图像宽度。 |
| height | int | 图像高度。 |
| color_palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | 颜色调色板。 |
| color_mode | [ColorModes](/psd/python-net/aspose.psd.fileformats.psd/colormodes) | 颜色模式。 |
| channel_bit_depth | short | 每个通道的 PSD 位深度。 |
| channels | short | PSD 通道数量。 |
| psd_version | int | PSD 版本。 |
| compression | [CompressionMethod](/psd/python-net/aspose.psd.fileformats.psd/compressionmethod) | 要使用的压缩方式。 |

### Method: add_black_white_adjustment_layer() {#add_black_white_adjustment_layer__1}


```
 add_black_white_adjustment_layer() 
```

添加黑白调整图层。

**Returns**

| 类型 | 描述 |
| :- | :- |
| [BlackWhiteAdjustmentLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/blackwhiteadjustmentlayer/) | 已创建的黑白调整图层。 |


### Method: add_brightness_contrast_adjustment_layer(brightness, contrast) {#add_brightness_contrast_adjustment_layer_brightness_contrast_2}


```
 add_brightness_contrast_adjustment_layer(brightness, contrast) 
```

添加亮度/对比度调整图层。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 亮度 | int | 亮度。 |
| 对比度 | int | 对比度。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [BrightnessContrastLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/brightnesscontrastlayer/) | 已创建亮度/对比度图层 |


### Method: add_channel_mixer_adjustment_layer() {#add_channel_mixer_adjustment_layer__3}


```
 add_channel_mixer_adjustment_layer() 
```

添加带默认参数的通道混合器调整图层。

**Returns**

| 类型 | 描述 |
| :- | :- |
| [ChannelMixerLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/channelmixerlayer/) | 已添加通道混合器图层 |


### Method: add_color_balance_adjustment_layer() {#add_color_balance_adjustment_layer__4}


```
 add_color_balance_adjustment_layer() 
```

添加色彩平衡调整图层。

**Returns**

| 类型 | 描述 |
| :- | :- |
| [ColorBalanceAdjustmentLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer/) | 新创建的颜色平衡图层。 |


### Method: add_curves_adjustment_layer() {#add_curves_adjustment_layer__5}


```
 add_curves_adjustment_layer() 
```

添加 Curves 调整图层。

**Returns**

| 类型 | 描述 |
| :- | :- |
| [CurvesLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/curveslayer/) | 已创建 [CurvesLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/curveslayer/) 图层 |


### Method: add_exposure_adjustment_layer(exposure, offset, gamma_correction) {#add_exposure_adjustment_layer_exposure_offset_gamma_correction_6}


```
 add_exposure_adjustment_layer(exposure, offset, gamma_correction) 
```

添加曝光调整图层。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 曝光 | float | 曝光。 |
| offset | float | 偏移量。 |
| 伽马校正 | float | 伽马校正。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [ExposureLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/exposurelayer/) | 已创建曝光调整图层 |


### Method: add_gradient_map_adjustment_layer() {#add_gradient_map_adjustment_layer__7}


```
 add_gradient_map_adjustment_layer() 
```

添加 GradientMap 调整图层。

**Returns**

| 类型 | 描述 |
| :- | :- |
| [GradientMapLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/gradientmaplayer/) | GradientMap 实例。 |


### Method: add_hue_saturation_adjustment_layer() {#add_hue_saturation_adjustment_layer__8}


```
 add_hue_saturation_adjustment_layer() 
```

添加色相/饱和度调整图层。

**Returns**

| 类型 | 描述 |
| :- | :- |
| [HueSaturationLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/huesaturationlayer/) | 新创建的色相/饱和度图层。 |


### Method: add_invert_adjustment_layer() {#add_invert_adjustment_layer__9}


```
 add_invert_adjustment_layer() 
```

添加反相调整图层。

**Returns**

| 类型 | 描述 |
| :- | :- |
| [InvertAdjustmentLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/invertadjustmentlayer/) | 已创建的反相图层 |


### Method: add_layer(layer) {#add_layer_layer_10}


```
 add_layer(layer) 
```

添加图层。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| layer | [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | 该图层。 |

### Method: add_layer_group(group_name, index, start_behaviour) {#add_layer_group_group_name_index_start_behaviour_11}


```
 add_layer_group(group_name, index, start_behaviour) 
```

添加图层组。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| group_name | 字符串 | 组的名称。 |
| index | int | 要在其后插入的图层的索引。 |
| start_behaviour | bool | 如果设置为 <c>true</c> [start behaviour]，则组将在启动时处于打开状态，否则为最小化状态。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [LayerGroup](/psd/python-net/aspose.psd.fileformats.psd.layers/layergroup/) | 打开组图层 |


### Method: add_levels_adjustment_layer() {#add_levels_adjustment_layer__12}


```
 add_levels_adjustment_layer() 
```

添加 Levels 调整图层。

**Returns**

| 类型 | 描述 |
| :- | :- |
| [LevelsLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/levelslayer/) | 新创建的色阶图层 |


### Method: add_photo_filter_layer(color) {#add_photo_filter_layer_color_13}


```
 add_photo_filter_layer(color) 
```

添加 PhotoFilter 图层。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) | 颜色。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [PhotoFilterLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/photofilterlayer/) | 已创建照片滤镜图层 |


### Method: add_posterize_adjustment_layer() {#add_posterize_adjustment_layer__14}


```
 add_posterize_adjustment_layer() 
```

添加 Posterize 调整图层。

**Returns**

| 类型 | 描述 |
| :- | :- |
| [PosterizeLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/posterizelayer/) | PosterizeLayer 实例。 |


### Method: add_regular_layer() {#add_regular_layer__15}


```
 add_regular_layer() 
```

添加一个新的常规图层。

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | 已创建常规图层。 |


### Method: add_selective_color_adjustment_layer() {#add_selective_color_adjustment_layer__16}


```
 add_selective_color_adjustment_layer() 
```

添加选择性颜色调整图层。

**Returns**

| 类型 | 描述 |
| :- | :- |
| [SelectiveColorLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/selectivecolorlayer/) | 已创建的选择性颜色调整图层。 |


### Method: add_shape_layer() {#add_shape_layer__17}


```
 add_shape_layer() 
```

添加空的 Shape 图层。<br/>            没有路径。它们应在保存前添加到 shape 图层。

**Returns**

| 类型 | 描述 |
| :- | :- |
| [ShapeLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/shapelayer/) | ShapeLayer 实例。 |


### Method: add_text_layer(text, rect) {#add_text_layer_text_rect_18}


```
 add_text_layer(text, rect) 
```

添加一个新的 Text 图层。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| text | 字符串 | 图层的文本。 |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 图层的矩形。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [TextLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/textlayer/) | 已创建文本图层。 |


### Method: add_threshold_adjustment_layer() {#add_threshold_adjustment_layer__19}


```
 add_threshold_adjustment_layer() 
```

添加 Threshold 调整图层。

**Returns**

| 类型 | 描述 |
| :- | :- |
| [ThresholdLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/thresholdlayer/) | 已创建的阈值调整图层。 |


### Method: add_vibrance_adjustment_layer() {#add_vibrance_adjustment_layer__20}


```
 add_vibrance_adjustment_layer() 
```

添加 Vibrance 调整图层。

**Returns**

| 类型 | 描述 |
| :- | :- |
| [VibranceLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/vibrancelayer/) | 新创建的鲜艳度图层。 |


### Method: adjust_brightness(brightness) {#adjust_brightness_brightness_21}


```
 adjust_brightness(brightness) 
```

调整图像的亮度。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 亮度 | int | 亮度值。 |

### Method: adjust_contrast(contrast) {#adjust_contrast_contrast_22}


```
 adjust_contrast(contrast) 
```

图像对比

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 对比度 | float | 对比度值（范围为 [-100; 100]） |

### Method: adjust_gamma(gamma) {#adjust_gamma_gamma_23}


```
 adjust_gamma(gamma) 
```

图像的伽马校正。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 伽马 | float | 红、绿、蓝通道的伽马系数 |

### Method: adjust_gamma(gamma_red, gamma_green, gamma_blue) {#adjust_gamma_gamma_red_gamma_green_gamma_blue_24}


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

### Method: binarize_bradley(brightness_difference) {#binarize_bradley_brightness_difference_25}


```
 binarize_bradley(brightness_difference) 
```

使用 Bradley 的自适应阈值算法和积分图像阈值对图像进行二值化

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| brightness_difference | double | 像素的亮度差值，即该像素与其周围以该像素为中心的 s x s 窗口像素平均值之间的差异。 |

### Method: binarize_bradley(brightness_difference, window_size) {#binarize_bradley_brightness_difference_window_size_26}


```
 binarize_bradley(brightness_difference, window_size) 
```

使用 Bradley 的自适应阈值算法和积分图像阈值对图像进行二值化

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| brightness_difference | double | 像素的亮度差值，即该像素与其周围以该像素为中心的 s x s 窗口像素平均值之间的差异。 |
| window_size | int | 以该像素为中心的 s x s 像素窗口的大小 |

### Method: binarize_fixed(threshold) {#binarize_fixed_threshold_27}


```
 binarize_fixed(threshold) 
```

使用预定义阈值对图像进行二值化

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| threshold | byte | 阈值。如果像素的对应灰度值大于阈值，则赋值为 255；否则为 0。 |

### Method: can_load(file_path)  [static] {#can_load_file_path_28}


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


### Method: can_load(file_path, load_options)  [static] {#can_load_file_path_load_options_29}


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


### Method: can_load(stream)  [static] {#can_load_stream_30}


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


### Method: can_load(stream, load_options)  [static] {#can_load_stream_load_options_31}


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


### Method: can_save(options) {#can_save_options_32}


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


### Method: convert(new_options) {#convert_new_options_33}


```
 convert(new_options) 
```

将此图像格式转换为选项中指定的格式。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| new_options | [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/) | 新选项。 |

### Method: create(image_options, width, height)  [static] {#create_image_options_width_height_34}


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


### Method: crop(rectangle) {#crop_rectangle_35}


```
 crop(rectangle) 
```

裁剪图像。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 矩形。 |

### Method: dither(dithering_method, bits_count) {#dither_dithering_method_bits_count_36}


```
 dither(dithering_method, bits_count) 
```

对当前图像执行抖动处理。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/psd/python-net/aspose.psd/ditheringmethod) | 抖动方法。 |
| bits_count | int | 抖动的最终位计数。 |

### Method: dither(dithering_method, bits_count, custom_palette) {#dither_dithering_method_bits_count_custom_palette_37}


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

### Method: filter(rectangle, options) {#filter_rectangle_options_38}


```
 filter(rectangle, options) 
```

过滤指定的矩形。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 矩形。 |
| options | [FilterOptionsBase](/psd/python-net/aspose.psd.imagefilters.filteroptions/filteroptionsbase/) | 选项。 |

### Method: get_argb_32_pixel(x, y) {#get_argb_32_pixel_x_y_39}


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


### Method: get_default_argb_32_pixels(rectangle) {#get_default_argb_32_pixels_rectangle_40}


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


### Method: get_default_options(args) {#get_default_options_args_41}


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


### Method: get_default_pixels(rectangle, partial_pixel_loader) {#get_default_pixels_rectangle_partial_pixel_loader_42}


```
 get_default_pixels(rectangle, partial_pixel_loader) 
```

使用部分像素加载器获取默认像素数组。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 获取像素的矩形。 |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/psd/python-net/aspose.psd/ipartialargb32pixelloader) | 部分像素加载器。 |

### Method: get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) {#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_43}


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

### Method: get_default_raw_data(rectangle, raw_data_settings) {#get_default_raw_data_rectangle_raw_data_settings_44}


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


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_45}


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


### Method: get_file_format(stream)  [static] {#get_file_format_stream_46}


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


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_47}


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


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_48}


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


### Method: get_modify_date(use_default) {#get_modify_date_use_default_49}


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


### Method: get_original_options() {#get_original_options__50}


```
 get_original_options() 
```

获取基于原始文件设置的选项。<br/>            这有助于保持原始图像的位深度和其他参数不变。<br/>            例如，如果我们加载一张每像素 1 位的黑白 PNG 图像，然后使用<br/>            [DataStreamSupporter.save(file_path)](/psd/python-net/aspose.psd/datastreamsupporter/) 方法保存，它将生成每像素 8 位的输出 PNG 图像。<br/>            为避免这种情况并以每像素 1 位保存 PNG 图像，请使用此方法获取相应的保存选项并将它们<br/>            作为第二个参数传递给 [Image.save(file_path, options)](/psd/python-net/aspose.psd/image/) 方法。

**Returns**

| 类型 | 描述 |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | 基于原始文件设置的选项。 |


### Method: get_pixel(x, y) {#get_pixel_x_y_51}


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


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_52}


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


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_53}


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


### Method: get_skew_angle() {#get_skew_angle__54}


```
 get_skew_angle() 
```

  

**Returns**

| 类型 | 描述 |
| :- | :- |
| float |  |


### Method: load(file_path)  [static] {#load_file_path_55}


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


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_56}


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


### Method: load(stream)  [static] {#load_stream_57}


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


### Method: load(stream, load_options)  [static] {#load_stream_load_options_58}


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


### Method: load_argb_32_pixels(rectangle) {#load_argb_32_pixels_rectangle_59}


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


### Method: load_argb_64_pixels(rectangle) {#load_argb_64_pixels_rectangle_60}


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


### Method: load_cmyk_32_pixels(rectangle) {#load_cmyk_32_pixels_rectangle_61}


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


### Method: load_cmyk_pixels(rectangle) {#load_cmyk_pixels_rectangle_62}


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


### Method: load_partial_argb_32_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_63}


```
 load_partial_argb_32_pixels(rectangle, partial_pixel_loader) 
```

部分加载 32 位 ARGB 像素（按块）。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 用于加载像素的矩形。 |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/psd/python-net/aspose.psd/ipartialargb32pixelloader) | 部分像素加载器。 |

### Method: load_partial_pixels(desired_rectangle, pixel_loader) {#load_partial_pixels_desired_rectangle_pixel_loader_64}


```
 load_partial_pixels(desired_rectangle, pixel_loader) 
```

按批次部分加载像素。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| desired_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 所需的矩形。 |
| pixel_loader | [IPartialPixelLoader](/psd/python-net/aspose.psd/ipartialpixelloader) | 像素加载器。 |

### Method: load_pixels(rectangle) {#load_pixels_rectangle_65}


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


### Method: load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_66}


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

### Method: load_raw_data(rectangle, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_raw_data_settings_raw_data_loader_67}


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

### Method: merge_layers(bottom_layer, top_layer) {#merge_layers_bottom_layer_top_layer_68}


```
 merge_layers(bottom_layer, top_layer) 
```

合并图层。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| bottom_layer | [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | 底层。 |
| top_layer | [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | 顶层。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | 合并后的底层 |


### Method: read_argb_32_scan_line(scan_line_index) {#read_argb_32_scan_line_scan_line_index_69}


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


### Method: read_scan_line(scan_line_index) {#read_scan_line_scan_line_index_70}


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


### Method: replace_color(old_color, old_color_diff, new_color) {#replace_color_old_color_old_color_diff_new_color_71}


```
 replace_color(old_color, old_color_diff, new_color) 
```

在允许的差异范围内将一种颜色替换为另一种颜色，并保留原始 alpha 值以保持平滑边缘。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| old_color | [Color](/psd/python-net/aspose.psd/color) |  |
| old_color_diff | byte | 允许的旧颜色差异，以便能够扩大替换后的颜色色调。 |
| new_color | [Color](/psd/python-net/aspose.psd/color) |  |

### Method: replace_color(old_color_argb, old_color_diff, new_color_argb) {#replace_color_old_color_argb_old_color_diff_new_color_argb_72}


```
 replace_color(old_color_argb, old_color_diff, new_color_argb) 
```

在允许的差异范围内将一种颜色替换为另一种颜色，并保留原始 alpha 值以保持平滑边缘。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| old_color_argb | int | 待替换的旧颜色 ARGB 值。 |
| old_color_diff | byte | 允许的旧颜色差异，以便能够扩大替换后的颜色色调。 |
| new_color_argb | int | 用于替换旧颜色的新颜色 ARGB 值。 |

### Method: replace_non_transparent_colors(new_color) {#replace_non_transparent_colors_new_color_73}


```
 replace_non_transparent_colors(new_color) 
```

将所有非透明颜色替换为新颜色，并保留原始的 alpha 值以实现平滑边缘。<br/>            注意：如果在没有透明度的图像上使用，它将把所有颜色替换为单一颜色。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| new_color | [Color](/psd/python-net/aspose.psd/color) |  |

### Method: replace_non_transparent_colors(new_color_argb) {#replace_non_transparent_colors_new_color_argb_74}


```
 replace_non_transparent_colors(new_color_argb) 
```

将所有非透明颜色替换为新颜色，并保留原始的 alpha 值以实现平滑边缘。<br/>            注意：如果在没有透明度的图像上使用，它将把所有颜色替换为单一颜色。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| new_color_argb | int | 用于替换非透明颜色的新颜色 ARGB 值。 |

### Method: resize(new_width, new_height) {#resize_new_width_new_height_75}


```
 resize(new_width, new_height) 
```

调整图像大小。使用默认的 [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/)。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| new_width | int | 新的宽度。 |
| new_height | int | 新的高度。 |

### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_76}


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

### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_77}


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

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_78}


```
 resize_height_proportionally(new_height) 
```

等比例调整高度。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| new_height | int | 新的高度。 |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_79}


```
 resize_height_proportionally(new_height, resize_type) 
```

等比例调整高度。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| new_height | int | 新的高度。 |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | 调整大小的类型。 |

### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_80}


```
 resize_height_proportionally(new_height, settings) 
```

等比例调整高度。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| new_height | int | 新的高度。 |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | 图像调整大小设置。 |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_81}


```
 resize_width_proportionally(new_width) 
```

等比例调整宽度。使用默认的 [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/)。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| new_width | int | 新的宽度。 |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_82}


```
 resize_width_proportionally(new_width, resize_type) 
```

等比例调整宽度。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| new_width | int | 新的宽度。 |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | 调整大小的类型。 |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_83}


```
 resize_width_proportionally(new_width, settings) 
```

等比例调整宽度。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| new_width | int | 新的宽度。 |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | 图像调整大小设置。 |

### Method: rotate(angle) {#rotate_angle_84}


```
 rotate(angle) 
```

围绕中心旋转图像。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 角度 | float | 旋转角度（单位：度）。正值将顺时针旋转。 |

### Method: rotate(angle, resize_proportionally, background_color) {#rotate_angle_resize_proportionally_background_color_85}


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

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_86}


```
 rotate_flip(rotate_flip_type) 
```

旋转、翻转或同时旋转并翻转图像。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/psd/python-net/aspose.psd/rotatefliptype) | 旋转翻转类型。 |

### Method: save(file_path) {#save_file_path_87}


```
 save(file_path) 
```

将对象的数据保存到指定的文件位置。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| file_path | 字符串 | 用于保存对象数据的文件路径。 |

### Method: save(file_path, options) {#save_file_path_options_88}


```
 save(file_path, options) 
```

根据保存选项，将对象的数据以指定的文件格式保存到指定的文件位置。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| file_path | 字符串 | 文件路径。 |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | 选项。 |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_89}


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

### Method: save(file_path, over_write) {#save_file_path_over_write_90}


```
 save(file_path, over_write) 
```

将对象的数据保存到指定的文件位置。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| file_path | 字符串 | 用于保存对象数据的文件路径。 |
| over_write | bool | 如果设置为 <c>true</c>，则覆盖文件内容；否则将追加。 |

### Method: save(stream) {#save_stream_91}


```
 save(stream) 
```

将对象的数据保存到指定的流中。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 流 | _io.BufferedRandom | 用于保存对象数据的流。 |

### Method: save(stream, options_base) {#save_stream_options_base_92}


```
 save(stream, options_base) 
```

根据保存选项，将图像的数据以指定的文件格式保存到指定的流中。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 流 | _io.BufferedRandom | 用于保存图像数据的流。 |
| options_base | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | 保存选项。 |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_93}


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

### Method: save_argb_32_pixels(rectangle, pixels) {#save_argb_32_pixels_rectangle_pixels_94}


```
 save_argb_32_pixels(rectangle, pixels) 
```

保存 32 位 ARGB 像素。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 用于保存像素的矩形。 |
| pixels | int | 32 位 ARGB 像素数组。 |

### Method: save_pixels(rectangle, pixels) {#save_pixels_rectangle_pixels_95}


```
 save_pixels(rectangle, pixels) 
```

保存像素（特定格式的方法）。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 用于保存像素的矩形。 |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) | 32 位 ARGB 像素数组。 |

### Method: save_raw_data(data, data_offset, rectangle, raw_data_settings) {#save_raw_data_data_data_offset_rectangle_raw_data_settings_96}


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

### Method: set_argb_32_pixel(x, y, argb_32_color) {#set_argb_32_pixel_x_y_argb_32_color_97}


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

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_98}


```
 set_palette(palette, update_colors) 
```

设置图像调色板。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | 要设置的调色板。 |
| update_colors | bool | 如果设置为 <c>true</c>，颜色将根据新调色板进行更新；否则颜色索引保持不变。请注意，如果某些索引没有对应的调色板条目，未更改的索引可能在加载时导致图像崩溃。 |

### Method: set_pixel(x, y, color) {#set_pixel_x_y_color_99}


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

### Method: set_resolution(dpi_x, dpi_y) {#set_resolution_dpi_x_dpi_y_100}


```
 set_resolution(dpi_x, dpi_y) 
```

设置此 [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) 的分辨率。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| dpi_x | double | 水平分辨率（每英寸点数），针对 [RasterImage](/psd/python-net/aspose.psd/rasterimage/)。 |
| dpi_y | double | 垂直分辨率（每英寸点数），针对 [RasterImage](/psd/python-net/aspose.psd/rasterimage/)。 |

### Method: to_bitmap() {#to_bitmap__101}


```
 to_bitmap() 
```

  

**Returns**

| 类型 | 描述 |
| :- | :- |
| aspose.pydrawing.Bitmap |  |


### Method: write_argb_32_scan_line(scan_line_index, argb_32_pixels) {#write_argb_32_scan_line_scan_line_index_argb_32_pixels_102}


```
 write_argb_32_scan_line(scan_line_index, argb_32_pixels) 
```

将整条扫描线写入指定的扫描线索引。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| scan_line_index | int | 扫描线的零基索引。 |
| argb_32_pixels | int | 要写入的 32 位 ARGB 颜色数组。 |

### Method: write_scan_line(scan_line_index, pixels) {#write_scan_line_scan_line_index_pixels_103}


```
 write_scan_line(scan_line_index, pixels) 
```

将整条扫描线写入指定的扫描线索引。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| scan_line_index | int | 扫描线的零基索引。 |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) | 要写入的像素颜色数组。 |

