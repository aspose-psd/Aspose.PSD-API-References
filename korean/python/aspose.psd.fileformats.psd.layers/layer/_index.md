---
title: "Layer 클래스"
type: docs
weight: 930
url: /ko/python-net/aspose.psd.fileformats.psd.layers/layer/
---

**Summary:** The psd layer.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.Layer

**Inheritance:** IObjectWithBounds, IRasterImageArgb32PixelLoader, IRasterImageRawDataLoader, RasterCachedImage

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [Layer()](#Layer__1) | [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) 클래스의 새 인스턴스를 초기화합니다. 지연 초기화를 위한 생성자. |
| [Layer(bounds, red_bytes, green_bytes, blue_bytes, name)](#Layer_bounds_red_bytes_green_bytes_blue_bytes_name_2) | [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) 클래스의 새 인스턴스를 바이트 배열에서 초기화합니다. |
| [Layer(image, dispose_image)](#Layer_image_dispose_image_3) | [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) 클래스의 새 인스턴스를 초기화합니다. |
| [Layer(stream)](#Layer_stream_4) | [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) 클래스의 새 인스턴스를 초기화합니다. |
## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| BLEND_SIGNATURE [static] | int | r | 블렌드 모드 서명을 나타냅니다. |
| LAYER_HEADER_SIZE [static] | int | r | 레이어 헤더 크기. |
| auto_adjust_palette | bool | r/w | 자동 팔레트 조정 여부를 나타내는 값을 가져오거나 설정합니다. |
| background_color | [Color](/psd/python-net/aspose.psd/color) | r/w | 배경 색상의 값을 가져오거나 설정합니다. |
| bits_per_pixel | int | r | 이미지의 픽셀당 비트 수를 가져옵니다. |
| blend_clipped_elements | bool | r/w | 클립된 요소의 블렌딩을 가져오거나 설정합니다. |
| blend_mode_key | [BlendMode](/psd/python-net/aspose.psd.fileformats.core.blending/blendmode/) | r/w | 블렌드 모드 키를 가져오거나 설정합니다. |
| blend_mode_signature | int | r | 블렌드 모드 서명을 가져옵니다. |
| blending_options | [BlendingOptions](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/) | r | 블렌딩 옵션을 가져옵니다. |
| 하단 | int | r/w | 하위 레이어 위치를 가져오거나 설정합니다. |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | 객체 경계를 가져옵니다. |
| buffer_size_hint | int | r/w | 버퍼 크기 힌트를 가져오거나 설정합니다. 이 힌트는 모든 내부 버퍼에 허용되는 최대 크기로 정의됩니다. |
| channel_information | [ChannelInformation[]](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | r/w | 채널 정보를 가져오거나 설정합니다. |
| channels_count | ushort | r | 레이어의 채널 수를 가져옵니다. |
| clipping | byte | r/w | 레이어 클리핑을 가져오거나 설정합니다. 0 = 기본, 1 = 비기본. |
| container | [Image](/psd/python-net/aspose.psd/image) | r | 해당 [Image](/psd/python-net/aspose.psd/image/) 컨테이너를 가져옵니다. |
| data_stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | r | 객체의 데이터 스트림을 가져옵니다. |
| display_name | 문자열 | r/w | 레이어의 표시 이름을 가져오거나 설정합니다. |
| disposed | bool | r | 이 인스턴스가 해제되었는지 여부를 나타내는 값을 가져옵니다. |
| extra_length | int | r | 레이어 추가 정보 길이를 바이트 단위로 가져옵니다. |
| file_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | 파일 형식 값을 가져옵니다. |
| fill_opacity | int | r/w | 채우기 불투명도를 가져오거나 설정합니다. |
| filler | byte | r/w | 레이어 필러를 가져오거나 설정합니다. |
| flags | [LayerFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layerflags) | r/w | 레이어 플래그를 가져오거나 설정합니다.<br/>            bit 0 = 투명도 보호;<br/>            bit 1 = 표시;<br/>            bit 2 = 사용되지 않음;<br/>            bit 3 = Photoshop 5.0 이상에서는 1이며, bit 4에 유용한 정보가 있는지 나타냅니다;<br/>            bit 4 = 문서 외관과 무관한 픽셀 데이터. |
| has_alpha | bool | r | 이 인스턴스에 알파가 있는지 여부를 나타내는 값을 가져옵니다. |
| has_background_color | bool | r/w | 이미지에 배경색이 있는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| has_transparent_color | bool | r/w | 이미지에 투명 색상이 있는지 여부를 나타내는 값을 가져옵니다. |
| 높이 | int | r | 이미지 높이를 가져옵니다. |
| horizontal_resolution | double | r/w | 이 [RasterImage](/psd/python-net/aspose.psd/rasterimage/)의 수평 해상도(인치당 픽셀)를 가져오거나 설정합니다. |
| image_opacity | float | r | 이 이미지의 불투명도를 가져옵니다. |
| interrupt_monitor | [InterruptMonitor](/psd/python-net/aspose.psd.multithreading/interruptmonitor/) | r/w | 인터럽트 모니터를 가져오거나 설정합니다. |
| is_cached | bool | r | 이미지 데이터가 현재 캐시되어 있는지 여부를 나타내는 값을 가져옵니다. |
| is_raw_data_available | bool | r | 원시 데이터 로드가 지원되는지 여부를 나타내는 값을 가져옵니다. |
| is_visible | bool | r/w | 레이어가 표시되는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| is_visible_in_group | bool | r | 이 인스턴스가 그룹에서 표시되는지 여부를 나타내는 값을 가져옵니다(레이어가 그룹에 없으면 루트 그룹을 의미합니다). |
| layer_blending_ranges_data | [LayerBlendingRangesData](/psd/python-net/aspose.psd.fileformats.psd.layers/layerblendingrangesdata) | r/w | 레이어 블렌딩 범위 데이터를 가져오거나 설정합니다. |
| layer_creation_date_time | datetime | r/w | 레이어 생성 날짜 및 시간을 가져오거나 설정합니다. |
| layer_lock | [LayerLockType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/layerlocktype/) | r/w | Gets or sets the layer lock.<br/>            Note that if flag LayerFlags.TransparencyProtected is set it will be overwritten by layer lock flag.<br/>            To return LayerFlags.TransparencyProtected flag need to apply for layer option layer.Flags | = LayerFlags.TransparencyProtected |
| layer_mask_data | [LayerMaskData](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata) | r/w | 레이어 마스크 데이터를 가져오거나 설정합니다. |
| layer_options | [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/) | r | 레이어 옵션을 가져옵니다. |
| left | int | r/w | 왼쪽 레이어 위치를 가져오거나 설정합니다. |
| 길이 | int | r | 전체 레이어 길이를 바이트 단위로 가져옵니다. |
| name | 문자열 | r/w | 레이어 이름을 가져오거나 설정합니다. |
| opacity | byte | r/w | 레이어 불투명도를 가져오거나 설정합니다. 0 = 투명, 255 = 불투명. |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | 색상 팔레트를 가져오거나 설정합니다. 픽셀이 직접 표현될 때는 색상 팔레트를 사용하지 않습니다. |
| premultiply_components | bool | r/w | 이미지 구성 요소를 사전 곱해야 하는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| raw_custom_color_converter | [IColorConverter](/psd/python-net/aspose.psd/icolorconverter) | r/w | 사용자 정의 색상 변환기를 가져오거나 설정합니다. |
| raw_data_format | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | 원시 데이터 형식을 가져옵니다. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | r | 현재 원시 데이터 설정을 가져옵니다. 이 설정을 사용할 때 데이터가 변환 없이 로드된다는 점에 유의하십시오. |
| raw_fallback_index | int | r/w | 팔레트 인덱스가 범위를 벗어났을 때 사용할 대체 인덱스를 가져오거나 설정합니다. |
| raw_indexed_color_converter | [IIndexedColorConverter](/psd/python-net/aspose.psd/iindexedcolorconverter) | r/w | 인덱스 색상 변환기를 가져오거나 설정합니다. |
| raw_line_size | int | r | 원시 라인 크기를 바이트 단위로 가져옵니다. |
| resources | [LayerResource[]](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource) | r/w | 레이어 리소스를 가져오거나 설정합니다. |
| right | int | r/w | 오른쪽 레이어 위치를 가져오거나 설정합니다. |
| sheet_color_highlight | [SheetColorHighlightEnum](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/sheetcolorhighlightenum/) | r/w | 레이어 목록에서 장식 시트 색상 강조를 가져오거나 설정합니다. |
| size | [Size](/psd/python-net/aspose.psd/size) | r | 객체 크기를 가져옵니다. |
| top | int | r/w | 상단 레이어 위치를 가져오거나 설정합니다. |
| transparent_color | [Color](/psd/python-net/aspose.psd/color) | r/w | 이미지 투명 색상을 가져옵니다. |
| update_xmp_data | bool | r/w | XMP 메타데이터를 업데이트할지 여부를 나타내는 값을 가져오거나 설정합니다. |
| use_palette | bool | r | 이미지 팔레트를 사용하는지 여부를 나타내는 값을 가져옵니다. |
| use_raw_data | bool | r/w | 원시 데이터 로딩이 가능할 때 원시 데이터 로딩을 사용할지 여부를 나타내는 값을 가져오거나 설정합니다. |
| vertical_resolution | double | r/w | 이 [RasterImage](/psd/python-net/aspose.psd/rasterimage/)의 수직 해상도(인치당 픽셀)를 가져오거나 설정합니다. |
| width | int | r | 이미지 너비를 가져옵니다. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | XMP 메타데이터를 가져오거나 설정합니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [add_layer_mask(layer_mask)](#add_layer_mask_layer_mask_1) | 마스크를 현재 레이어에 추가합니다. |
| [adjust_brightness(brightness)](#adjust_brightness_brightness_2) | 이미지의 밝기를 조정합니다. |
| [adjust_contrast(contrast)](#adjust_contrast_contrast_3) | 이미지 대비 |
| [adjust_gamma(gamma)](#adjust_gamma_gamma_4) | 이미지의 감마 보정. |
| [adjust_gamma(gamma_red, gamma_green, gamma_blue)](#adjust_gamma_gamma_red_gamma_green_gamma_blue_5) | 이미지의 감마 보정. |
| [binarize_bradley(brightness_difference)](#binarize_bradley_brightness_difference_6) | Bradley의 적응형 임계값 알고리즘과 적분 이미지 임계값을 사용하여 이미지 이진화 |
| [binarize_bradley(brightness_difference, window_size)](#binarize_bradley_brightness_difference_window_size_7) | Bradley의 적응형 임계값 알고리즘과 적분 이미지 임계값을 사용하여 이미지 이진화 |
| [binarize_fixed(threshold)](#binarize_fixed_threshold_8) | 미리 정의된 임계값으로 이미지 이진화 |
| binarize_otsu() | Otsu 임계값을 사용한 이미지 이진화 |
| cache_data() | 데이터를 캐시하고 기본 [DataStreamSupporter.data_stream_container](/psd/python-net/aspose.psd/datastreamsupporter/)에서 추가 데이터 로드가 수행되지 않도록 보장합니다. |
| [can_load(file_path)](#can_load_file_path_9) | 지정된 파일 경로에서 이미지를 로드할 수 있는지 확인합니다. |
| [can_load(file_path, load_options)](#can_load_file_path_load_options_10) | 지정된 파일 경로와 선택적으로 지정된 열기 옵션을 사용하여 이미지를 로드할 수 있는지 확인합니다. |
| [can_load(stream)](#can_load_stream_11) | 지정된 스트림에서 이미지를 로드할 수 있는지 확인합니다. |
| [can_load(stream, load_options)](#can_load_stream_load_options_12) | 지정된 스트림에서 이미지를 로드할 수 있는지 확인하고, 선택적으로 지정된 <paramref name="loadOptions" />를 사용할 수 있습니다. |
| [can_save(options)](#can_save_options_13) | 전달된 저장 옵션으로 나타낸 지정된 파일 형식에 이미지를 저장할 수 있는지 확인합니다. |
| [create(image_options, width, height)](#create_image_options_width_height_14) | 지정된 생성 옵션을 사용하여 새 이미지를 생성합니다. |
| crop(left_shift, right_shift, top_shift, bottom_shift) |  |
| [crop(rectangle)](#crop_rectangle_15) | 이미지를 자릅니다. |
| [dither(dithering_method, bits_count)](#dither_dithering_method_bits_count_16) | 현재 이미지에 디더링을 수행합니다. |
| [dither(dithering_method, bits_count, custom_palette)](#dither_dithering_method_bits_count_custom_palette_17) | 현재 이미지에 디더링을 수행합니다. |
| [draw_image(location, image)](#draw_image_location_image_18) | 이미지를 레이어에 그립니다. |
| filter(rectangle, options) |  |
| [get_argb_32_pixel(x, y)](#get_argb_32_pixel_x_y_19) | 이미지의 32비트 ARGB 픽셀을 가져옵니다. |
| [get_default_argb_32_pixels(rectangle)](#get_default_argb_32_pixels_rectangle_20) | 기본 32비트 ARGB 픽셀 배열을 가져옵니다. |
| [get_default_options(args)](#get_default_options_args_21) | 기본 옵션을 가져옵니다. |
| [get_default_pixels(rectangle, partial_pixel_loader)](#get_default_pixels_rectangle_partial_pixel_loader_22) | 부분 픽셀 로더를 사용하여 기본 픽셀 배열을 가져옵니다. |
| [get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings)](#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_23) | 부분 픽셀 로더를 사용하여 기본 원시 데이터 배열을 가져옵니다. |
| [get_default_raw_data(rectangle, raw_data_settings)](#get_default_raw_data_rectangle_raw_data_settings_24) | 기본 원시 데이터 배열을 가져옵니다. |
| [get_file_format(file_path)](#get_file_format_file_path_25) | 파일 형식을 가져옵니다. |
| [get_file_format(stream)](#get_file_format_stream_26) | 파일 형식을 가져옵니다. |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_27) | 현재 이미지에 맞는 사각형을 가져옵니다. |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_28) | 현재 이미지에 맞는 사각형을 가져옵니다. |
| [get_modify_date(use_default)](#get_modify_date_use_default_29) | 리소스 이미지가 마지막으로 수정된 날짜와 시간을 가져옵니다. |
| [get_original_options()](#get_original_options__30) | 원본 파일 설정을 기반으로 옵션을 가져옵니다.<br/>            이는 원본 이미지의 비트 깊이 및 기타 매개변수를 변경하지 않도록 유지하는 데 도움이 될 수 있습니다.<br/>            예를 들어, 1비트 픽셀의 흑백 PNG 이미지를 로드한 후<br/>            [DataStreamSupporter.save(file_path)](/psd/python-net/aspose.psd/datastreamsupporter/) 메서드를 사용하여 저장하면 8비트 픽셀의 PNG 이미지가 출력됩니다.<br/>            이를 방지하고 1비트 픽셀 PNG 이미지를 저장하려면 이 메서드를 사용하여 해당 저장 옵션을 가져오고 이를<br/>            [Image.save(file_path, options)](/psd/python-net/aspose.psd/image/) 메서드의 두 번째 매개변수로 전달하십시오. |
| [get_pixel(x, y)](#get_pixel_x_y_31) | 이미지 픽셀을 가져옵니다.<br/>            성능 경고: 모든 이미지 픽셀을 반복하는 데 이 메서드를 사용하면 성능 문제가 크게 발생할 수 있으므로 피하십시오.<br/>            보다 효율적인 픽셀 조작을 위해서는 `LoadArgb32Pixels` 메서드를 사용하여 전체 픽셀 배열을 한 번에 가져오세요. |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_32) | 비례 높이를 가져옵니다. |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_33) | 비례 너비를 가져옵니다. |
| [get_skew_angle()](#get_skew_angle__34) |    |
| grayscale() | 이미지를 회색조 표현으로 변환 |
| [load(file_path)](#load_file_path_35) | 지정된 파일에서 새 이미지를 로드합니다. |
| [load(file_path, load_options)](#load_file_path_load_options_36) | 지정된 파일에서 새 이미지를 로드합니다. |
| [load(stream)](#load_stream_37) | 지정된 스트림에서 새 이미지를 로드합니다. |
| [load(stream, load_options)](#load_stream_load_options_38) | 지정된 스트림에서 새 이미지를 로드합니다. |
| [load_argb_32_pixels(rectangle)](#load_argb_32_pixels_rectangle_39) | 32비트 ARGB 픽셀을 로드합니다. |
| [load_argb_64_pixels(rectangle)](#load_argb_64_pixels_rectangle_40) | 64비트 ARGB 픽셀을 로드합니다. |
| [load_cmyk_32_pixels(rectangle)](#load_cmyk_32_pixels_rectangle_41) | CMYK 형식의 픽셀을 로드합니다. |
| [load_cmyk_pixels(rectangle)](#load_cmyk_pixels_rectangle_42) | CMYK 형식의 픽셀을 로드합니다.<br/>            이 메서드는 더 이상 사용되지 않습니다. 보다 효율적인 [RasterImage.load_cmyk_32_pixels(rectangle)](/psd/python-net/aspose.psd/rasterimage/) 메서드를 사용하십시오. |
| [load_partial_argb_32_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_43) | 32비트 ARGB 픽셀을 부분적으로(블록 단위로) 로드합니다. |
| [load_partial_pixels(desired_rectangle, pixel_loader)](#load_partial_pixels_desired_rectangle_pixel_loader_44) | 픽셀을 패키지 단위로 부분적으로 로드합니다. |
| [load_pixels(rectangle)](#load_pixels_rectangle_45) | 픽셀을 로드합니다. |
| [load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_46) | 원시 데이터를 로드합니다. |
| [load_raw_data(rectangle, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_raw_data_settings_raw_data_loader_47) | 원시 데이터를 로드합니다. |
| [merge_layer_to(layer_to_merge_into)](#merge_layer_to_layer_to_merge_into_48) | 지정된 레이어에 레이어를 병합합니다. |
| normalize_angle() |  |
| normalize_angle(resize_proportionally, background_color) |  |
| [read_argb_32_scan_line(scan_line_index)](#read_argb_32_scan_line_scan_line_index_49) | 지정된 스캔 라인 인덱스로 전체 스캔 라인을 읽습니다. |
| [read_scan_line(scan_line_index)](#read_scan_line_scan_line_index_50) | 지정된 스캔 라인 인덱스로 전체 스캔 라인을 읽습니다. |
| replace_color(old_color, old_color_diff, new_color) |  |
| replace_color(old_color_argb, old_color_diff, new_color_argb) |  |
| replace_non_transparent_colors(new_color) |  |
| replace_non_transparent_colors(new_color_argb) |  |
| [resize(new_width, new_height)](#resize_new_width_new_height_51) | 이미지를 리사이즈합니다. 기본값으로 [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/)이 사용됩니다. |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_52) | 이미지를 리사이즈합니다. |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_53) | 이미지를 리사이즈합니다. |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_54) | 높이를 비례적으로 리사이즈합니다. |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_55) | 높이를 비례적으로 리사이즈합니다. |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_56) | 높이를 비례적으로 리사이즈합니다. |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_57) | 너비를 비례적으로 리사이즈합니다. 기본값으로 [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/)이 사용됩니다. |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_58) | 너비를 비례적으로 리사이즈합니다. |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_59) | 너비를 비례적으로 리사이즈합니다. |
| rotate(angle) |  |
| [rotate(angle, resize_proportionally, background_color)](#rotate_angle_resize_proportionally_background_color_60) | 이미지를 중심을 기준으로 회전합니다. |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_61) | 이미지를 회전하거나 뒤집거나 회전 및 뒤집습니다. |
| save() | 이미지 데이터를 기본 스트림에 저장합니다. |
| [save(file_path)](#save_file_path_62) | 지정된 파일 위치에 객체의 데이터를 저장합니다. |
| [save(file_path, options)](#save_file_path_options_63) | 저장 옵션에 따라 지정된 파일 형식으로 지정된 파일 위치에 객체의 데이터를 저장합니다. |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_64) | 저장 옵션에 따라 지정된 파일 형식으로 지정된 파일 위치에 객체의 데이터를 저장합니다. |
| [save(file_path, over_write)](#save_file_path_over_write_65) | 지정된 파일 위치에 객체의 데이터를 저장합니다. |
| [save(stream)](#save_stream_66) | 지정된 스트림에 객체의 데이터를 저장합니다. |
| [save(stream, options_base)](#save_stream_options_base_67) | 저장 옵션에 따라 지정된 파일 형식으로 지정된 스트림에 이미지 데이터를 저장합니다. |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_68) | 저장 옵션에 따라 지정된 파일 형식으로 지정된 스트림에 이미지 데이터를 저장합니다. |
| [save_argb_32_pixels(rectangle, pixels)](#save_argb_32_pixels_rectangle_pixels_69) | 32비트 ARGB 픽셀을 저장합니다. |
| save_cmyk_32_pixels(rectangle, pixels) |  |
| save_cmyk_pixels(rectangle, pixels) |  |
| [save_pixels(rectangle, pixels)](#save_pixels_rectangle_pixels_70) | 픽셀을 저장합니다 (형식 별 메서드). |
| [save_raw_data(data, data_offset, rectangle, raw_data_settings)](#save_raw_data_data_data_offset_rectangle_raw_data_settings_71) | 원시 데이터를 저장합니다. |
| [set_argb_32_pixel(x, y, argb_32_color)](#set_argb_32_pixel_x_y_argb_32_color_72) | 지정된 위치에 이미지 32비트 ARGB 픽셀을 설정합니다. |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_73) | 이미지 팔레트를 설정합니다. |
| [set_pixel(x, y, color)](#set_pixel_x_y_color_74) | 지정된 위치에 이미지 픽셀을 설정합니다. |
| set_resolution(dpi_x, dpi_y) |  |
| [shallow_copy()](#shallow_copy__75) | 현재 Layer의 얕은 복사본을 생성합니다.<br/>            설명은 <see href="https://msdn.microsoft.com/ru-ru/library/system.object.memberwiseclone(v=vs.110).aspx" /> 를 참조하십시오. |
| [to_bitmap()](#to_bitmap__76) |    |
| [write_argb_32_scan_line(scan_line_index, argb_32_pixels)](#write_argb_32_scan_line_scan_line_index_argb_32_pixels_77) | 전체 스캔 라인을 지정된 스캔 라인 인덱스로 씁니다. |
| [write_scan_line(scan_line_index, pixels)](#write_scan_line_scan_line_index_pixels_78) | 전체 스캔 라인을 지정된 스캔 라인 인덱스로 씁니다. |


### Constructor: Layer() {#Layer__1}


```
 Layer() 
```

[Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) 클래스의 새 인스턴스를 초기화합니다. 지연 초기화를 위한 생성자.

### Constructor: Layer(bounds, red_bytes, green_bytes, blue_bytes, name) {#Layer_bounds_red_bytes_green_bytes_blue_bytes_name_2}


```
 Layer(bounds, red_bytes, green_bytes, blue_bytes, name) 
```

[Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) 클래스의 새 인스턴스를 바이트 배열에서 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 레이어 경계입니다. |
| red_bytes | byte | 빨간색 바이트입니다. |
| green_bytes | byte | 녹색 바이트입니다. |
| blue_bytes | byte | 파란색 바이트입니다. |
| name | 문자열 | 레이어 이름입니다. |

### Constructor: Layer(image, dispose_image) {#Layer_image_dispose_image_3}


```
 Layer(image, dispose_image) 
```

[Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | 이미지입니다. |
| dispose_image | bool | 설정이 <c>true</c>이면 [dispose image]. |

### Constructor: Layer(stream) {#Layer_stream_4}


```
 Layer(stream) 
```

[Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 스트림 | _io.BufferedRandom | 이미지 스트림입니다. |

### Method: add_layer_mask(layer_mask) {#add_layer_mask_layer_mask_1}


```
 add_layer_mask(layer_mask) 
```

마스크를 현재 레이어에 추가합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| layer_mask | [LayerMaskData](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata) | 레이어 마스크입니다. |

### Method: adjust_brightness(brightness) {#adjust_brightness_brightness_2}


```
 adjust_brightness(brightness) 
```

이미지의 밝기를 조정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 밝기 | int | 밝기 값입니다. |

### Method: adjust_contrast(contrast) {#adjust_contrast_contrast_3}


```
 adjust_contrast(contrast) 
```

이미지 대비

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 대비 | float | 대비 값 (범위 [-100; 100]) |

### Method: adjust_gamma(gamma) {#adjust_gamma_gamma_4}


```
 adjust_gamma(gamma) 
```

이미지의 감마 보정.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 감마 | float | 빨강, 초록 및 파랑 채널에 대한 감마 계수 |

### Method: adjust_gamma(gamma_red, gamma_green, gamma_blue) {#adjust_gamma_gamma_red_gamma_green_gamma_blue_5}


```
 adjust_gamma(gamma_red, gamma_green, gamma_blue) 
```

이미지의 감마 보정.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| gamma_red | float | 빨강 채널에 대한 감마 계수 |
| gamma_green | float | 초록 채널에 대한 감마 계수 |
| gamma_blue | float | 파랑 채널에 대한 감마 계수 |

### Method: binarize_bradley(brightness_difference) {#binarize_bradley_brightness_difference_6}


```
 binarize_bradley(brightness_difference) 
```

Bradley의 적응형 임계값 알고리즘과 적분 이미지 임계값을 사용하여 이미지 이진화

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| brightness_difference | double | 픽셀과 해당 픽셀을 중심으로 하는 s x s 창의 픽셀 평균 사이의 밝기 차이. |

### Method: binarize_bradley(brightness_difference, window_size) {#binarize_bradley_brightness_difference_window_size_7}


```
 binarize_bradley(brightness_difference, window_size) 
```

Bradley의 적응형 임계값 알고리즘과 적분 이미지 임계값을 사용하여 이미지 이진화

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| brightness_difference | double | 픽셀과 해당 픽셀을 중심으로 하는 s x s 창의 픽셀 평균 사이의 밝기 차이. |
| window_size | int | 해당 픽셀을 중심으로 하는 s x s 픽셀 창의 크기 |

### Method: binarize_fixed(threshold) {#binarize_fixed_threshold_8}


```
 binarize_fixed(threshold) 
```

미리 정의된 임계값으로 이미지 이진화

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 임계값 | byte | 임계값. 픽셀의 해당 회색 값이 임계값보다 크면 255가 할당되고, 그렇지 않으면 0이 할당됩니다. |

### Method: can_load(file_path)  [static] {#can_load_file_path_9}


```
 can_load(file_path) 
```

지정된 파일 경로에서 이미지를 로드할 수 있는지 확인합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| file_path | 문자열 | 파일 경로. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| bool | <c>true</c> if 이미지가 지정된 파일에서 로드될 수 있으면; 그렇지 않으면 <c>false</c>. |


### Method: can_load(file_path, load_options)  [static] {#can_load_file_path_load_options_10}


```
 can_load(file_path, load_options) 
```

지정된 파일 경로와 선택적으로 지정된 열기 옵션을 사용하여 이미지를 로드할 수 있는지 확인합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| file_path | 문자열 | 파일 경로. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | 로드 옵션. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| bool | <c>true</c> if 이미지가 지정된 파일에서 로드될 수 있으면; 그렇지 않으면 <c>false</c>. |


### Method: can_load(stream)  [static] {#can_load_stream_11}


```
 can_load(stream) 
```

지정된 스트림에서 이미지를 로드할 수 있는지 확인합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 스트림 | _io.BufferedRandom | 로드할 스트림. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| bool | <c>true</c> if 이미지가 지정된 스트림에서 로드될 수 있으면; 그렇지 않으면 <c>false</c>. |


### Method: can_load(stream, load_options)  [static] {#can_load_stream_load_options_12}


```
 can_load(stream, load_options) 
```

지정된 스트림에서 이미지를 로드할 수 있는지 확인하고, 선택적으로 지정된 <paramref name="loadOptions" />를 사용할 수 있습니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 스트림 | _io.BufferedRandom | 로드할 스트림. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | 로드 옵션. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| bool | <c>true</c> if 이미지가 지정된 스트림에서 로드될 수 있으면; 그렇지 않으면 <c>false</c>. |


### Method: can_save(options) {#can_save_options_13}


```
 can_save(options) 
```

전달된 저장 옵션으로 나타낸 지정된 파일 형식에 이미지를 저장할 수 있는지 확인합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | 사용할 저장 옵션. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| bool | <c>true</c> if 이미지가 전달된 저장 옵션으로 나타내는 지정된 파일 형식에 저장될 수 있으면; 그렇지 않으면 <c>false</c>. |


### Method: create(image_options, width, height)  [static] {#create_image_options_width_height_14}


```
 create(image_options, width, height) 
```

지정된 생성 옵션을 사용하여 새 이미지를 생성합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | 이미지 옵션. |
| width | int | 너비. |
| 높이 | int | 높이. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | 새로 생성된 이미지. |


### Method: crop(rectangle) {#crop_rectangle_15}


```
 crop(rectangle) 
```

이미지를 자릅니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 사각형. |

### Method: dither(dithering_method, bits_count) {#dither_dithering_method_bits_count_16}


```
 dither(dithering_method, bits_count) 
```

현재 이미지에 디더링을 수행합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/psd/python-net/aspose.psd/ditheringmethod) | 디더링 방법. |
| bits_count | int | 디더링을 위한 최종 비트 수. |

### Method: dither(dithering_method, bits_count, custom_palette) {#dither_dithering_method_bits_count_custom_palette_17}


```
 dither(dithering_method, bits_count, custom_palette) 
```

현재 이미지에 디더링을 수행합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/psd/python-net/aspose.psd/ditheringmethod) | 디더링 방법. |
| bits_count | int | 디더링을 위한 최종 비트 수. |
| custom_palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | 디더링을 위한 사용자 정의 팔레트. |

### Method: draw_image(location, image) {#draw_image_location_image_18}


```
 draw_image(location, image) 
```

이미지를 레이어에 그립니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| location | [Point](/psd/python-net/aspose.psd/point) | 위치. |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | 이미지입니다. |

### Method: get_argb_32_pixel(x, y) {#get_argb_32_pixel_x_y_19}


```
 get_argb_32_pixel(x, y) 
```

이미지의 32비트 ARGB 픽셀을 가져옵니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| x | int | 픽셀 x 위치. |
| y | int | 픽셀 y 위치. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| int | 지정된 위치의 32비트 ARGB 픽셀. |


### Method: get_default_argb_32_pixels(rectangle) {#get_default_argb_32_pixels_rectangle_20}


```
 get_default_argb_32_pixels(rectangle) 
```

기본 32비트 ARGB 픽셀 배열을 가져옵니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 픽셀을 가져올 사각형. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| int | 기본 픽셀 배열. |


### Method: get_default_options(args) {#get_default_options_args_21}


```
 get_default_options(args) 
```

기본 옵션을 가져옵니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| args | object | 인수. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | 기본 옵션 |


### Method: get_default_pixels(rectangle, partial_pixel_loader) {#get_default_pixels_rectangle_partial_pixel_loader_22}


```
 get_default_pixels(rectangle, partial_pixel_loader) 
```

부분 픽셀 로더를 사용하여 기본 픽셀 배열을 가져옵니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 픽셀을 가져올 사각형. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/psd/python-net/aspose.psd/ipartialargb32pixelloader) | 부분 픽셀 로더. |

### Method: get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) {#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_23}


```
 get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) 
```

부분 픽셀 로더를 사용하여 기본 원시 데이터 배열을 가져옵니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 픽셀을 가져올 사각형. |
| partial_raw_data_loader | [IPartialRawDataLoader](/psd/python-net/aspose.psd/ipartialrawdataloader) | 부분 원시 데이터 로더. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | 원시 데이터 설정. |

### Method: get_default_raw_data(rectangle, raw_data_settings) {#get_default_raw_data_rectangle_raw_data_settings_24}


```
 get_default_raw_data(rectangle, raw_data_settings) 
```

기본 원시 데이터 배열을 가져옵니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 원시 데이터를 가져올 사각형. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | 원시 데이터 설정. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| byte | 기본 원시 데이터 배열. |


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_25}


```
 get_file_format(file_path) 
```

파일 형식을 가져옵니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| file_path | 문자열 | 파일 경로. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [FileFormat](/psd/python-net/aspose.psd/fileformat) | 결정된 파일 형식. |


### Method: get_file_format(stream)  [static] {#get_file_format_stream_26}


```
 get_file_format(stream) 
```

파일 형식을 가져옵니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 스트림 | _io.BufferedRandom | 스트림. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [FileFormat](/psd/python-net/aspose.psd/fileformat) | 결정된 파일 형식. |


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_27}


```
 get_fitting_rectangle(rectangle, pixels, width, height) 
```

현재 이미지에 맞는 사각형을 가져옵니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 맞는 사각형을 얻기 위한 사각형. |
| pixels | int | 32비트 ARGB 픽셀. |
| width | int | 객체 너비. |
| 높이 | int | 객체 높이. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | 맞는 사각형이 없을 경우 예외를 포함한 맞는 사각형. |


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_28}


```
 get_fitting_rectangle(rectangle, width, height) 
```

현재 이미지에 맞는 사각형을 가져옵니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 맞는 사각형을 얻기 위한 사각형. |
| width | int | 객체 너비. |
| 높이 | int | 객체 높이. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | 맞는 사각형이 없을 경우 예외를 포함한 맞는 사각형. |


### Method: get_modify_date(use_default) {#get_modify_date_use_default_29}


```
 get_modify_date(use_default) 
```

리소스 이미지가 마지막으로 수정된 날짜와 시간을 가져옵니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| use_default | bool | <c>true</c> 로 설정하면 FileInfo의 정보를 기본값으로 사용합니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| datetime | 리소스 이미지가 마지막으로 수정된 날짜와 시간입니다. |


### Method: get_original_options() {#get_original_options__30}


```
 get_original_options() 
```

원본 파일 설정을 기반으로 옵션을 가져옵니다.<br/>            이는 원본 이미지의 비트 깊이 및 기타 매개변수를 변경하지 않도록 유지하는 데 도움이 될 수 있습니다.<br/>            예를 들어, 1비트 픽셀의 흑백 PNG 이미지를 로드한 후<br/>            [DataStreamSupporter.save(file_path)](/psd/python-net/aspose.psd/datastreamsupporter/) 메서드를 사용하여 저장하면 8비트 픽셀의 PNG 이미지가 출력됩니다.<br/>            이를 방지하고 1비트 픽셀 PNG 이미지를 저장하려면 이 메서드를 사용하여 해당 저장 옵션을 가져오고 이를<br/>            [Image.save(file_path, options)](/psd/python-net/aspose.psd/image/) 메서드의 두 번째 매개변수로 전달하십시오.

**Returns**

| 유형 | 설명 |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | 원본 파일 설정을 기반으로 하는 옵션입니다. |


### Method: get_pixel(x, y) {#get_pixel_x_y_31}


```
 get_pixel(x, y) 
```

이미지 픽셀을 가져옵니다.<br/>            성능 경고: 모든 이미지 픽셀을 반복하는 데 이 메서드를 사용하면 성능 문제가 크게 발생할 수 있으므로 피하십시오.<br/>            보다 효율적인 픽셀 조작을 위해서는 `LoadArgb32Pixels` 메서드를 사용하여 전체 픽셀 배열을 한 번에 가져오세요.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| x | int | 픽셀 x 위치. |
| y | int | 픽셀 y 위치. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | 지정된 위치의 픽셀 색상입니다. |


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_32}


```
 get_proportional_height(width, height, new_width) 
```

비례 높이를 가져옵니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| width | int | 너비. |
| 높이 | int | 높이. |
| new_width | int | 새로운 너비입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| int | 비례 높이입니다. |


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_33}


```
 get_proportional_width(width, height, new_height) 
```

비례 너비를 가져옵니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| width | int | 너비. |
| 높이 | int | 높이. |
| new_height | int | 새로운 높이입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| int | 비례 너비입니다. |


### Method: get_skew_angle() {#get_skew_angle__34}


```
 get_skew_angle() 
```

  

**Returns**

| 유형 | 설명 |
| :- | :- |
| float |  |


### Method: load(file_path)  [static] {#load_file_path_35}


```
 load(file_path) 
```

지정된 파일에서 새 이미지를 로드합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| file_path | 문자열 | 이미지를 로드할 파일 경로입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | 로드된 이미지입니다. |


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_36}


```
 load(file_path, load_options) 
```

지정된 파일에서 새 이미지를 로드합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| file_path | 문자열 | 이미지를 로드할 파일 경로입니다. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | 로드 옵션. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | 로드된 이미지입니다. |


### Method: load(stream)  [static] {#load_stream_37}


```
 load(stream) 
```

지정된 스트림에서 새 이미지를 로드합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 스트림 | _io.BufferedRandom | 이미지를 로드할 스트림입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | 로드된 이미지입니다. |


### Method: load(stream, load_options)  [static] {#load_stream_load_options_38}


```
 load(stream, load_options) 
```

지정된 스트림에서 새 이미지를 로드합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 스트림 | _io.BufferedRandom | 이미지를 로드할 스트림입니다. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | 로드 옵션. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | 로드된 이미지입니다. |


### Method: load_argb_32_pixels(rectangle) {#load_argb_32_pixels_rectangle_39}


```
 load_argb_32_pixels(rectangle) 
```

32비트 ARGB 픽셀을 로드합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 픽셀을 로드할 사각형. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| int | 로드된 32비트 ARGB 픽셀 배열입니다. |


### Method: load_argb_64_pixels(rectangle) {#load_argb_64_pixels_rectangle_40}


```
 load_argb_64_pixels(rectangle) 
```

64비트 ARGB 픽셀을 로드합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 픽셀을 로드할 사각형. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| long | 로드된 64비트 ARGB 픽셀 배열입니다. |


### Method: load_cmyk_32_pixels(rectangle) {#load_cmyk_32_pixels_rectangle_41}


```
 load_cmyk_32_pixels(rectangle) 
```

CMYK 형식의 픽셀을 로드합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 픽셀을 로드할 사각형. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| int | 로드된 CMYK 픽셀은 32비트 정수 값으로 제공됩니다. |


### Method: load_cmyk_pixels(rectangle) {#load_cmyk_pixels_rectangle_42}


```
 load_cmyk_pixels(rectangle) 
```

CMYK 형식의 픽셀을 로드합니다.<br/>            이 메서드는 더 이상 사용되지 않습니다. 보다 효율적인 [RasterImage.load_cmyk_32_pixels(rectangle)](/psd/python-net/aspose.psd/rasterimage/) 메서드를 사용하십시오.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 픽셀을 로드할 사각형. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | 로드된 CMYK 픽셀 배열입니다. |


### Method: load_partial_argb_32_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_43}


```
 load_partial_argb_32_pixels(rectangle, partial_pixel_loader) 
```

32비트 ARGB 픽셀을 부분적으로(블록 단위로) 로드합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 픽셀을 로드할 사각형. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/psd/python-net/aspose.psd/ipartialargb32pixelloader) | 부분 픽셀 로더. |

### Method: load_partial_pixels(desired_rectangle, pixel_loader) {#load_partial_pixels_desired_rectangle_pixel_loader_44}


```
 load_partial_pixels(desired_rectangle, pixel_loader) 
```

픽셀을 패키지 단위로 부분적으로 로드합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| desired_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 원하는 사각형입니다. |
| pixel_loader | [IPartialPixelLoader](/psd/python-net/aspose.psd/ipartialpixelloader) | 픽셀 로더입니다. |

### Method: load_pixels(rectangle) {#load_pixels_rectangle_45}


```
 load_pixels(rectangle) 
```

픽셀을 로드합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 픽셀을 로드할 사각형. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | 로드된 픽셀 배열입니다. |


### Method: load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_46}


```
 load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) 
```

원시 데이터를 로드합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 원시 데이터를 로드할 사각형. |
| dest_image_bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 대상 이미지 경계입니다. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | 로드된 데이터에 사용할 원시 데이터 설정입니다. 지정된 형식이 아니면 데이터 변환이 수행됩니다. |
| raw_data_loader | [IPartialRawDataLoader](/psd/python-net/aspose.psd/ipartialrawdataloader) | 원시 데이터 로더입니다. |

### Method: load_raw_data(rectangle, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_raw_data_settings_raw_data_loader_47}


```
 load_raw_data(rectangle, raw_data_settings, raw_data_loader) 
```

원시 데이터를 로드합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 원시 데이터를 로드할 사각형. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | 로드된 데이터에 사용할 원시 데이터 설정입니다. 지정된 형식이 아니면 데이터 변환이 수행됩니다. |
| raw_data_loader | [IPartialRawDataLoader](/psd/python-net/aspose.psd/ipartialrawdataloader) | 원시 데이터 로더입니다. |

### Method: merge_layer_to(layer_to_merge_into) {#merge_layer_to_layer_to_merge_into_48}


```
 merge_layer_to(layer_to_merge_into) 
```

지정된 레이어에 레이어를 병합합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| layer_to_merge_into | [Layer](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | 병합할 레이어입니다. |

### Method: read_argb_32_scan_line(scan_line_index) {#read_argb_32_scan_line_scan_line_index_49}


```
 read_argb_32_scan_line(scan_line_index) 
```

지정된 스캔 라인 인덱스로 전체 스캔 라인을 읽습니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| scan_line_index | int | 스캔 라인의 0 기반 인덱스입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| int | 스캔 라인의 32비트 ARGB 색상 값 배열입니다. |


### Method: read_scan_line(scan_line_index) {#read_scan_line_scan_line_index_50}


```
 read_scan_line(scan_line_index) 
```

지정된 스캔 라인 인덱스로 전체 스캔 라인을 읽습니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| scan_line_index | int | 스캔 라인의 0 기반 인덱스입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | 스캔 라인의 픽셀 색상 값 배열입니다. |


### Method: resize(new_width, new_height) {#resize_new_width_new_height_51}


```
 resize(new_width, new_height) 
```

이미지를 리사이즈합니다. 기본값으로 [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/)이 사용됩니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| new_width | int | 새로운 너비입니다. |
| new_height | int | 새로운 높이입니다. |

### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_52}


```
 resize(new_width, new_height, resize_type) 
```

이미지를 리사이즈합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| new_width | int | 새로운 너비입니다. |
| new_height | int | 새로운 높이입니다. |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | 리사이즈 유형입니다. |

### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_53}


```
 resize(new_width, new_height, settings) 
```

이미지를 리사이즈합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| new_width | int | 새로운 너비입니다. |
| new_height | int | 새로운 높이입니다. |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | 리사이즈 설정입니다. |

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_54}


```
 resize_height_proportionally(new_height) 
```

높이를 비례적으로 리사이즈합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| new_height | int | 새로운 높이입니다. |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_55}


```
 resize_height_proportionally(new_height, resize_type) 
```

높이를 비례적으로 리사이즈합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| new_height | int | 새로운 높이입니다. |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | 크기 조정 유형. |

### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_56}


```
 resize_height_proportionally(new_height, settings) 
```

높이를 비례적으로 리사이즈합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| new_height | int | 새로운 높이입니다. |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | 이미지 크기 조정 설정. |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_57}


```
 resize_width_proportionally(new_width) 
```

너비를 비례적으로 리사이즈합니다. 기본값으로 [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/)이 사용됩니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| new_width | int | 새로운 너비입니다. |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_58}


```
 resize_width_proportionally(new_width, resize_type) 
```

너비를 비례적으로 리사이즈합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| new_width | int | 새로운 너비입니다. |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | 크기 조정 유형. |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_59}


```
 resize_width_proportionally(new_width, settings) 
```

너비를 비례적으로 리사이즈합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| new_width | int | 새로운 너비입니다. |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | 이미지 크기 조정 설정. |

### Method: rotate(angle, resize_proportionally, background_color) {#rotate_angle_resize_proportionally_background_color_60}


```
 rotate(angle, resize_proportionally, background_color) 
```

이미지를 중심을 기준으로 회전합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 각도 | float | 회전 각도(도). 양수 값은 시계 방향으로 회전합니다. |
| resize_proportionally | bool | 만약 <c>true</c> 로 설정하면 회전된 사각형(코너 포인트) 투영에 따라 이미지 크기가 변경됩니다. 그렇지 않으면 차원은 그대로 유지되고 내부 이미지 내용만 회전됩니다. |
| background_color | [Color](/psd/python-net/aspose.psd/color) | 배경 색상. |

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_61}


```
 rotate_flip(rotate_flip_type) 
```

이미지를 회전하거나 뒤집거나 회전 및 뒤집습니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/psd/python-net/aspose.psd/rotatefliptype) | 회전 뒤집기 유형. |

### Method: save(file_path) {#save_file_path_62}


```
 save(file_path) 
```

지정된 파일 위치에 객체의 데이터를 저장합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| file_path | 문자열 | 객체 데이터를 저장할 파일 경로. |

### Method: save(file_path, options) {#save_file_path_options_63}


```
 save(file_path, options) 
```

저장 옵션에 따라 지정된 파일 형식으로 지정된 파일 위치에 객체의 데이터를 저장합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| file_path | 문자열 | 파일 경로. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | 옵션. |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_64}


```
 save(file_path, options, bounds_rectangle) 
```

저장 옵션에 따라 지정된 파일 형식으로 지정된 파일 위치에 객체의 데이터를 저장합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| file_path | 문자열 | 파일 경로. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | 옵션. |
| bounds_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 대상 이미지 경계 사각형. 소스 경계를 사용하려면 빈 사각형을 설정하십시오. |

### Method: save(file_path, over_write) {#save_file_path_over_write_65}


```
 save(file_path, over_write) 
```

지정된 파일 위치에 객체의 데이터를 저장합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| file_path | 문자열 | 객체 데이터를 저장할 파일 경로. |
| over_write | bool | 만약 <c>true</c> 로 설정하면 파일 내용을 덮어쓰고, 그렇지 않으면 추가됩니다. |

### Method: save(stream) {#save_stream_66}


```
 save(stream) 
```

지정된 스트림에 객체의 데이터를 저장합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 스트림 | _io.BufferedRandom | 객체 데이터를 저장할 스트림. |

### Method: save(stream, options_base) {#save_stream_options_base_67}


```
 save(stream, options_base) 
```

저장 옵션에 따라 지정된 파일 형식으로 지정된 스트림에 이미지 데이터를 저장합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 스트림 | _io.BufferedRandom | 이미지 데이터를 저장할 스트림. |
| options_base | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | 저장 옵션. |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_68}


```
 save(stream, options_base, bounds_rectangle) 
```

저장 옵션에 따라 지정된 파일 형식으로 지정된 스트림에 이미지 데이터를 저장합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 스트림 | _io.BufferedRandom | 이미지 데이터를 저장할 스트림. |
| options_base | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | 저장 옵션. |
| bounds_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 대상 이미지 경계 사각형. 소스 경계를 사용하려면 빈 사각형을 설정하십시오. |

### Method: save_argb_32_pixels(rectangle, pixels) {#save_argb_32_pixels_rectangle_pixels_69}


```
 save_argb_32_pixels(rectangle, pixels) 
```

32비트 ARGB 픽셀을 저장합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 픽셀을 저장할 사각형. |
| pixels | int | 32비트 ARGB 픽셀 배열. |

### Method: save_pixels(rectangle, pixels) {#save_pixels_rectangle_pixels_70}


```
 save_pixels(rectangle, pixels) 
```

픽셀을 저장합니다 (형식 별 메서드).

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 픽셀을 저장할 사각형. |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) | 32비트 ARGB 픽셀 배열. |

### Method: save_raw_data(data, data_offset, rectangle, raw_data_settings) {#save_raw_data_data_data_offset_rectangle_raw_data_settings_71}


```
 save_raw_data(data, data_offset, rectangle, raw_data_settings) 
```

원시 데이터를 저장합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 데이터 | byte | 원시 데이터. |
| data_offset | int | 시작 원시 데이터 오프셋. |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 원시 데이터 사각형. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | 데이터가 포함된 원시 데이터 설정. |

### Method: set_argb_32_pixel(x, y, argb_32_color) {#set_argb_32_pixel_x_y_argb_32_color_72}


```
 set_argb_32_pixel(x, y, argb_32_color) 
```

지정된 위치에 이미지 32비트 ARGB 픽셀을 설정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| x | int | 픽셀 x 위치. |
| y | int | 픽셀 y 위치. |
| argb_32_color | int | 지정된 위치의 32비트 ARGB 픽셀. |

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_73}


```
 set_palette(palette, update_colors) 
```

이미지 팔레트를 설정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | 설정할 팔레트. |
| update_colors | bool | 설정이 <c>true</c>이면 색상이 새 팔레트에 따라 업데이트됩니다; 그렇지 않으면 색인은 변경되지 않은 상태로 유지됩니다. 변경되지 않은 색인은 일부 색인에 해당하는 팔레트 항목이 없을 경우 이미지를 로드할 때 충돌할 수 있습니다. |

### Method: set_pixel(x, y, color) {#set_pixel_x_y_color_74}


```
 set_pixel(x, y, color) 
```

지정된 위치에 이미지 픽셀을 설정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| x | int | 픽셀 x 위치. |
| y | int | 픽셀 y 위치. |
| color | [Color](/psd/python-net/aspose.psd/color) | 지정된 위치의 픽셀 색상입니다. |

### Method: shallow_copy() {#shallow_copy__75}


```
 shallow_copy() 
```

현재 Layer의 얕은 복사본을 생성합니다.<br/>            설명은 <see href="https://msdn.microsoft.com/ru-ru/library/system.object.memberwiseclone(v=vs.110).aspx" /> 를 참조하십시오.

**Returns**

| 유형 | 설명 |
| :- | :- |
| [Layer](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | 현재 레이어의 얕은 복사본입니다. |


### Method: to_bitmap() {#to_bitmap__76}


```
 to_bitmap() 
```

  

**Returns**

| 유형 | 설명 |
| :- | :- |
| aspose.pydrawing.Bitmap |  |


### Method: write_argb_32_scan_line(scan_line_index, argb_32_pixels) {#write_argb_32_scan_line_scan_line_index_argb_32_pixels_77}


```
 write_argb_32_scan_line(scan_line_index, argb_32_pixels) 
```

전체 스캔 라인을 지정된 스캔 라인 인덱스로 씁니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| scan_line_index | int | 스캔 라인의 0 기반 인덱스입니다. |
| argb_32_pixels | int | 작성할 32비트 ARGB 색상 배열입니다. |

### Method: write_scan_line(scan_line_index, pixels) {#write_scan_line_scan_line_index_pixels_78}


```
 write_scan_line(scan_line_index, pixels) 
```

전체 스캔 라인을 지정된 스캔 라인 인덱스로 씁니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| scan_line_index | int | 스캔 라인의 0 기반 인덱스입니다. |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) | 작성할 픽셀 색상 배열입니다. |

