---
title: "PsdImage 클래스"
type: docs
weight: 1760
url: /ko/python-net/aspose.psd.fileformats.psd/psdimage/
---

**Summary:** Defines the PsdImage class that provides the ability to load, edit, save PSD files as well as<br/>            update properties, add watermarks, perform graphics operations or convert one file format to another.<br/>            Aspose.PSD supports import as a layer and export to the following formats:<br/>            Png, Jpeg, Jpeg2000, Gif, Bmp, Tiff, Psd, Psb along with export to Pdf with selectable text

**Module:** [aspose.psd.fileformats.psd](/psd/python-net/aspose.psd.fileformats.psd/)

**Full Name:** aspose.psd.fileformats.psd.PsdImage

**Inheritance:** IObjectWithBounds, IRasterImageArgb32PixelLoader, IRasterImageRawDataLoader, RasterCachedImage

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [PsdImage(path)](#PsdImage_path_1) | 지정된 경로에 있는 래스터 이미지(경로에 PSD 이미지가 아님)로부터 [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) 클래스의 새 인스턴스를 초기화합니다. 기본 매개변수로 PSD 이미지를 초기화하는 데 사용됩니다 - 색상 모드 - rgb, 4채널, 채널당 8비트, 압축 - Raw. |
| [PsdImage(path, color_mode, channel_bit_depth, channels, psd_version, compression)](#PsdImage_path_color_mode_channel_bit_depth_channels_psd_version_compression_2) | 지정된 경로에 있는 래스터 이미지(경로에 PSD 이미지가 아님)로부터 [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) 클래스를 생성자 매개변수를 사용하여 새 인스턴스를 초기화합니다. |
| [PsdImage(raster_image)](#PsdImage_raster_image_3) | 기존 래스터 이미지(PSD 이미지가 아님)에서 RGB 색상 모드, 4채널, 채널당 8비트, 압축 없음으로 [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) 클래스의 새 인스턴스를 초기화합니다. |
| [PsdImage(raster_image, color_mode, channel_bit_depth, channels, psd_version, compression)](#PsdImage_raster_image_color_mode_channel_bit_depth_channels_psd_version_compression_4) | 기존 래스터 이미지(PSD 이미지가 아님)에서 생성자 매개변수를 사용하여 [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) 클래스의 새 인스턴스를 초기화합니다. |
| [PsdImage(stream)](#PsdImage_stream_5) | 스트림에 있는 래스터 이미지(스트림에 PSD 이미지가 아님)에서 지정된 경로로부터 [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) 클래스의 새 인스턴스를 초기화합니다. 기본 매개변수로 PSD 이미지를 초기화하는 데 사용됩니다 - 색상 모드 - rgb, 4채널, 채널당 8비트, 압축 - Raw. |
| [PsdImage(stream, color_mode, channel_bit_depth, channels, psd_version, compression)](#PsdImage_stream_color_mode_channel_bit_depth_channels_psd_version_compression_6) | 스트림에 있는 래스터 이미지(스트림에 PSD 이미지가 아님)에서 지정된 경로로부터 [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) 클래스를 생성자 매개변수를 사용하여 새 인스턴스를 초기화합니다. |
| [PsdImage(width, height)](#PsdImage_width_height_7) | 지정된 너비와 높이로 [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) 클래스의 새 인스턴스를 초기화합니다. 빈 PSD 이미지를 초기화하는 데 사용됩니다. |
| [PsdImage(width, height, color_palette, color_mode, channel_bit_depth, channels, psd_version, compression)](#PsdImage_width_height_color_palette_color_mode_channel_bit_depth_channels_psd_version_compression_8) | 지정된 너비, 높이, paletter, 색상 모드, 채널 수 및 채널 비트 길이와 지정된 압축 모드 매개변수를 사용하여 [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) 클래스의 새 인스턴스를 초기화합니다. 빈 PSD 이미지를 초기화하는 데 사용됩니다. |
## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| DEFAULT_VERSION [static] | int | r | 기본 PSD 버전입니다. |
| active_layer | [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | r/w | 활성 레이어를 가져오거나 설정합니다. |
| auto_adjust_palette | bool | r/w | 자동 팔레트 조정 여부를 나타내는 값을 가져오거나 설정합니다. |
| background_color | [Color](/psd/python-net/aspose.psd/color) | r/w | 배경 색상의 값을 가져오거나 설정합니다. |
| bits_per_channel | int | r | 채널당 비트를 가져옵니다. |
| bits_per_pixel | int | r | 이미지의 픽셀당 비트 수를 가져옵니다. |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | 객체 경계를 가져옵니다. |
| buffer_size_hint | int | r/w | 버퍼 크기 힌트를 가져오거나 설정합니다. 이 힌트는 모든 내부 버퍼에 허용되는 최대 크기로 정의됩니다. |
| channels_count | int | r | PSD 채널 수를 가져옵니다. |
| cmyk_color_profile | [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/) | r/w | CMYK PSD 이미지에 대한 CMYK 색상 프로파일을 가져오거나 설정합니다. 올바른 색상 변환을 위해 RgbColorProfile와 쌍을 이루어야 합니다. |
| color_mode | [ColorModes](/psd/python-net/aspose.psd.fileformats.psd/colormodes) | r/w | 색상 모드를 가져오거나 설정합니다. |
| compression | [CompressionMethod](/psd/python-net/aspose.psd.fileformats.psd/compressionmethod) | r | 압축 방식을 가져옵니다. |
| container | [Image](/psd/python-net/aspose.psd/image) | r | 해당 [Image](/psd/python-net/aspose.psd/image/) 컨테이너를 가져옵니다. |
| data_stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | r | 객체의 데이터 스트림을 가져옵니다. |
| disposed | bool | r | 이 인스턴스가 해제되었는지 여부를 나타내는 값을 가져옵니다. |
| file_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | 파일 형식 값을 가져옵니다. |
| global_angle | int | r/w | 전역 각도를 가져오거나 설정합니다. |
| global_layer_mask_info | [GlobalLayerMaskInfo](/psd/python-net/aspose.psd.fileformats.psd.layers/globallayermaskinfo/) | r | 전역 레이어 마스크 정보를 가져옵니다. |
| global_layer_resources | [LayerResource[]](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/) | r/w | 전역 레이어 리소스를 가져오거나 설정합니다. |
| gray_color_profile | [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/) | r/w | 그레이스케일 PSD 이미지에 대한 GRAY(단색) 색상 프로파일을 가져오거나 설정합니다. |
| has_alpha | bool | r | 이 [RasterImage](/psd/python-net/aspose.psd/rasterimage/)의 수직 해상도(인치당 픽셀)를 가져오거나 설정합니다. |
| has_background_color | bool | r/w | 이미지에 배경색이 있는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| has_transparency_data | bool | r/w | 레이어 데이터를 지정할 때 병합 결과에 대한 첫 번째 알파 채널에 투명도 데이터가 포함되는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| has_transparent_color | bool | r/w | 이미지에 투명 색상이 있는지 여부를 나타내는 값을 가져옵니다. |
| 높이 | int | r | 이미지 높이를 가져옵니다. |
| horizontal_resolution | double | r/w | 이 [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/)의 가로 해상도(인치당 픽셀)를 가져오거나 설정합니다. |
| image_opacity | float | r | 이 이미지의 불투명도를 가져옵니다. |
| image_resources | [ResourceBlock[]](/psd/python-net/aspose.psd.fileformats.psd/resourceblock) | r/w | PSD 이미지 리소스를 가져오거나 설정합니다. |
| interrupt_monitor | [InterruptMonitor](/psd/python-net/aspose.psd.multithreading/interruptmonitor/) | r/w | 인터럽트 모니터를 가져오거나 설정합니다. |
| is_cached | bool | r | 이미지 데이터가 현재 캐시되어 있는지 여부를 나타내는 값을 가져옵니다. |
| is_flatten | bool | r | PSD 이미지가 평탄화되었는지 여부를 나타내는 값을 가져옵니다. |
| is_raw_data_available | bool | r | 원시 데이터 로드가 지원되는지 여부를 나타내는 값을 가져옵니다. |
| layers | [Layer[]](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | r/w | PSD 레이어를 가져오거나 설정합니다. |
| linked_layers_manager | [LinkedLayersManager](/psd/python-net/aspose.psd.fileformats.psd.layers/linkedlayersmanager/) | r | 연결된 레이어 관리자를 가져옵니다. |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | 색상 팔레트를 가져오거나 설정합니다. 픽셀이 직접 표현될 때는 색상 팔레트를 사용하지 않습니다. |
| premultiply_components | bool | r/w | 이미지 구성 요소를 사전 곱해야 하는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| raw_custom_color_converter | [IColorConverter](/psd/python-net/aspose.psd/icolorconverter) | r/w | 사용자 정의 색상 변환기를 가져오거나 설정합니다. |
| raw_data_format | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | 원시 데이터 형식을 가져옵니다. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | r | 현재 원시 데이터 설정을 가져옵니다. 이 설정을 사용할 때 데이터가 변환 없이 로드된다는 점에 유의하십시오. |
| raw_fallback_index | int | r/w | 팔레트 인덱스가 범위를 벗어났을 때 사용할 대체 인덱스를 가져오거나 설정합니다. |
| raw_indexed_color_converter | [IIndexedColorConverter](/psd/python-net/aspose.psd/iindexedcolorconverter) | r/w | 인덱스 색상 변환기를 가져오거나 설정합니다. |
| raw_line_size | int | r | 원시 라인 크기를 바이트 단위로 가져옵니다. |
| rgb_color_profile | [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/) | r/w | CMYK PSD 이미지에 대한 RGB 색상 프로파일을 가져오거나 설정합니다. 올바른 색상 변환을 위해 CmykColorProfile와 쌍을 이루어야 합니다. |
| size | [Size](/psd/python-net/aspose.psd/size) | r | 객체 크기를 가져옵니다. |
| smart_object_provider | [SmartObjectProvider](/psd/python-net/aspose.psd.fileformats.psd/smartobjectprovider) | r | 스마트 객체 제공자를 가져옵니다. |
| timeline | [Timeline](/psd/python-net/aspose.psd.fileformats.psd.layers.animation/timeline/) | r | 이 [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/)의 [PsdImage.timeline](/psd/python-net/aspose.psd.fileformats.psd/psdimage/)을 가져옵니다. |
| transparent_color | [Color](/psd/python-net/aspose.psd/color) | r/w | 이미지 투명 색상을 가져옵니다. |
| update_xmp_data | bool | r/w | XMP 메타데이터를 업데이트할지 여부를 나타내는 값을 가져오거나 설정합니다. |
| use_palette | bool | r | 이미지 팔레트를 사용하는지 여부를 나타내는 값을 가져옵니다. |
| use_raw_data | bool | r/w | 원시 데이터 로딩이 가능할 때 원시 데이터 로딩을 사용할지 여부를 나타내는 값을 가져오거나 설정합니다. |
| version | int | r/w | 버전을 가져오거나 설정합니다. |
| vertical_resolution | double | r/w | 이 [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/)의 세로 해상도(인치당 픽셀)를 가져오거나 설정합니다. |
| width | int | r | 이미지 너비를 가져옵니다. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | XMP 메타데이터를 가져오거나 설정합니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [add_black_white_adjustment_layer()](#add_black_white_adjustment_layer__1) | 흑백 조정 레이어를 추가합니다. |
| [add_brightness_contrast_adjustment_layer(brightness, contrast)](#add_brightness_contrast_adjustment_layer_brightness_contrast_2) | 밝기/대비 조정 레이어를 추가합니다. |
| [add_channel_mixer_adjustment_layer()](#add_channel_mixer_adjustment_layer__3) | 기본 매개변수로 채널 믹서 조정 레이어를 추가합니다. |
| [add_color_balance_adjustment_layer()](#add_color_balance_adjustment_layer__4) | 색상 균형 조정 레이어를 추가합니다. |
| [add_curves_adjustment_layer()](#add_curves_adjustment_layer__5) | 곡선 조정 레이어를 추가합니다. |
| [add_exposure_adjustment_layer(exposure, offset, gamma_correction)](#add_exposure_adjustment_layer_exposure_offset_gamma_correction_6) | 노출 조정 레이어를 추가합니다. |
| [add_gradient_map_adjustment_layer()](#add_gradient_map_adjustment_layer__7) | 그라디언트 맵 조정 레이어를 추가합니다. |
| [add_hue_saturation_adjustment_layer()](#add_hue_saturation_adjustment_layer__8) | 색조/채도 조정 레이어를 추가합니다. |
| [add_invert_adjustment_layer()](#add_invert_adjustment_layer__9) | 반전 조정 레이어를 추가합니다. |
| [add_layer(layer)](#add_layer_layer_10) | 레이어를 추가합니다. |
| [add_layer_group(group_name, index, start_behaviour)](#add_layer_group_group_name_index_start_behaviour_11) | 레이어 그룹을 추가합니다. |
| [add_levels_adjustment_layer()](#add_levels_adjustment_layer__12) | Levels 조정 레이어를 추가합니다. |
| [add_photo_filter_layer(color)](#add_photo_filter_layer_color_13) | PhotoFilter 레이어를 추가합니다. |
| [add_posterize_adjustment_layer()](#add_posterize_adjustment_layer__14) | Posterize 조정 레이어를 추가합니다. |
| [add_regular_layer()](#add_regular_layer__15) | 새로운 일반 레이어를 추가합니다. |
| [add_selective_color_adjustment_layer()](#add_selective_color_adjustment_layer__16) | 선택 색상 조정 레이어를 추가합니다. |
| [add_shape_layer()](#add_shape_layer__17) | 빈 Shape 레이어를 추가합니다.<br/>            경로가 없습니다. 저장하기 전에 shape 레이어에 추가해야 합니다. |
| [add_text_layer(text, rect)](#add_text_layer_text_rect_18) | 새로운 Text 레이어를 추가합니다. |
| [add_threshold_adjustment_layer()](#add_threshold_adjustment_layer__19) | Threshold 조정 레이어를 추가합니다. |
| [add_vibrance_adjustment_layer()](#add_vibrance_adjustment_layer__20) | Vibrance 조정 레이어를 추가합니다. |
| [adjust_brightness(brightness)](#adjust_brightness_brightness_21) | 이미지의 밝기를 조정합니다. |
| [adjust_contrast(contrast)](#adjust_contrast_contrast_22) | 이미지 대비 |
| [adjust_gamma(gamma)](#adjust_gamma_gamma_23) | 이미지의 감마 보정. |
| [adjust_gamma(gamma_red, gamma_green, gamma_blue)](#adjust_gamma_gamma_red_gamma_green_gamma_blue_24) | 이미지의 감마 보정. |
| [binarize_bradley(brightness_difference)](#binarize_bradley_brightness_difference_25) | Bradley의 적응형 임계값 알고리즘과 적분 이미지 임계값을 사용하여 이미지 이진화 |
| [binarize_bradley(brightness_difference, window_size)](#binarize_bradley_brightness_difference_window_size_26) | Bradley의 적응형 임계값 알고리즘과 적분 이미지 임계값을 사용하여 이미지 이진화 |
| [binarize_fixed(threshold)](#binarize_fixed_threshold_27) | 미리 정의된 임계값으로 이미지 이진화 |
| binarize_otsu() | Otsu 임계값을 사용한 이미지 이진화 |
| cache_data() | 데이터를 캐시하고 기본 [DataStreamSupporter.data_stream_container](/psd/python-net/aspose.psd/datastreamsupporter/)에서 추가 데이터 로드가 수행되지 않도록 보장합니다. |
| [can_load(file_path)](#can_load_file_path_28) | 지정된 파일 경로에서 이미지를 로드할 수 있는지 확인합니다. |
| [can_load(file_path, load_options)](#can_load_file_path_load_options_29) | 지정된 파일 경로와 선택적으로 지정된 열기 옵션을 사용하여 이미지를 로드할 수 있는지 확인합니다. |
| [can_load(stream)](#can_load_stream_30) | 지정된 스트림에서 이미지를 로드할 수 있는지 확인합니다. |
| [can_load(stream, load_options)](#can_load_stream_load_options_31) | 지정된 스트림에서 이미지를 로드할 수 있는지 확인하고, 선택적으로 지정된 <paramref name="loadOptions" />를 사용할 수 있습니다. |
| [can_save(options)](#can_save_options_32) | 전달된 저장 옵션으로 나타낸 지정된 파일 형식에 이미지를 저장할 수 있는지 확인합니다. |
| [convert(new_options)](#convert_new_options_33) | 이 이미지 형식을 옵션에 지정된 형식으로 변환합니다. |
| [create(image_options, width, height)](#create_image_options_width_height_34) | 지정된 생성 옵션을 사용하여 새 이미지를 생성합니다. |
| crop(left_shift, right_shift, top_shift, bottom_shift) |  |
| [crop(rectangle)](#crop_rectangle_35) | 이미지를 자릅니다. |
| [dither(dithering_method, bits_count)](#dither_dithering_method_bits_count_36) | 현재 이미지에 디더링을 수행합니다. |
| [dither(dithering_method, bits_count, custom_palette)](#dither_dithering_method_bits_count_custom_palette_37) | 현재 이미지에 디더링을 수행합니다. |
| [filter(rectangle, options)](#filter_rectangle_options_38) | 지정된 사각형을 필터링합니다. |
| flatten_image() | 모든 레이어를 평탄화합니다. |
| [get_argb_32_pixel(x, y)](#get_argb_32_pixel_x_y_39) | 이미지의 32비트 ARGB 픽셀을 가져옵니다. |
| [get_default_argb_32_pixels(rectangle)](#get_default_argb_32_pixels_rectangle_40) | 기본 32비트 ARGB 픽셀 배열을 가져옵니다. |
| [get_default_options(args)](#get_default_options_args_41) | 기본 옵션을 가져옵니다. |
| [get_default_pixels(rectangle, partial_pixel_loader)](#get_default_pixels_rectangle_partial_pixel_loader_42) | 부분 픽셀 로더를 사용하여 기본 픽셀 배열을 가져옵니다. |
| [get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings)](#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_43) | 부분 픽셀 로더를 사용하여 기본 원시 데이터 배열을 가져옵니다. |
| [get_default_raw_data(rectangle, raw_data_settings)](#get_default_raw_data_rectangle_raw_data_settings_44) | 기본 원시 데이터 배열을 가져옵니다. |
| [get_file_format(file_path)](#get_file_format_file_path_45) | 파일 형식을 가져옵니다. |
| [get_file_format(stream)](#get_file_format_stream_46) | 파일 형식을 가져옵니다. |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_47) | 현재 이미지에 맞는 사각형을 가져옵니다. |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_48) | 현재 이미지에 맞는 사각형을 가져옵니다. |
| [get_modify_date(use_default)](#get_modify_date_use_default_49) | 리소스 이미지가 마지막으로 수정된 날짜와 시간을 가져옵니다. |
| [get_original_options()](#get_original_options__50) | 원본 파일 설정을 기반으로 옵션을 가져옵니다.<br/>            이는 원본 이미지의 비트 깊이 및 기타 매개변수를 변경하지 않도록 유지하는 데 도움이 될 수 있습니다.<br/>            예를 들어, 1비트 픽셀의 흑백 PNG 이미지를 로드한 후<br/>            [DataStreamSupporter.save(file_path)](/psd/python-net/aspose.psd/datastreamsupporter/) 메서드를 사용하여 저장하면 8비트 픽셀의 PNG 이미지가 출력됩니다.<br/>            이를 방지하고 1비트 픽셀 PNG 이미지를 저장하려면 이 메서드를 사용하여 해당 저장 옵션을 가져오고 이를<br/>            [Image.save(file_path, options)](/psd/python-net/aspose.psd/image/) 메서드의 두 번째 매개변수로 전달하십시오. |
| [get_pixel(x, y)](#get_pixel_x_y_51) | 이미지 픽셀을 가져옵니다.<br/>            성능 경고: 모든 이미지 픽셀을 반복하는 데 이 메서드를 사용하면 성능 문제가 크게 발생할 수 있으므로 피하십시오.<br/>            보다 효율적인 픽셀 조작을 위해서는 `LoadArgb32Pixels` 메서드를 사용하여 전체 픽셀 배열을 한 번에 가져오세요. |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_52) | 비례 높이를 가져옵니다. |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_53) | 비례 너비를 가져옵니다. |
| [get_skew_angle()](#get_skew_angle__54) |    |
| grayscale() | 이미지를 회색조 표현으로 변환 |
| [load(file_path)](#load_file_path_55) | 지정된 파일에서 새 이미지를 로드합니다. |
| [load(file_path, load_options)](#load_file_path_load_options_56) | 지정된 파일에서 새 이미지를 로드합니다. |
| [load(stream)](#load_stream_57) | 지정된 스트림에서 새 이미지를 로드합니다. |
| [load(stream, load_options)](#load_stream_load_options_58) | 지정된 스트림에서 새 이미지를 로드합니다. |
| [load_argb_32_pixels(rectangle)](#load_argb_32_pixels_rectangle_59) | 32비트 ARGB 픽셀을 로드합니다. |
| [load_argb_64_pixels(rectangle)](#load_argb_64_pixels_rectangle_60) | 64비트 ARGB 픽셀을 로드합니다. |
| [load_cmyk_32_pixels(rectangle)](#load_cmyk_32_pixels_rectangle_61) | CMYK 형식의 픽셀을 로드합니다. |
| [load_cmyk_pixels(rectangle)](#load_cmyk_pixels_rectangle_62) | CMYK 형식의 픽셀을 로드합니다.<br/>            이 메서드는 더 이상 사용되지 않습니다. 보다 효율적인 [RasterImage.load_cmyk_32_pixels(rectangle)](/psd/python-net/aspose.psd/rasterimage/) 메서드를 사용하십시오. |
| [load_partial_argb_32_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_63) | 32비트 ARGB 픽셀을 부분적으로(블록 단위로) 로드합니다. |
| [load_partial_pixels(desired_rectangle, pixel_loader)](#load_partial_pixels_desired_rectangle_pixel_loader_64) | 픽셀을 패키지 단위로 부분적으로 로드합니다. |
| [load_pixels(rectangle)](#load_pixels_rectangle_65) | 픽셀을 로드합니다. |
| [load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_66) | 원시 데이터를 로드합니다. |
| [load_raw_data(rectangle, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_raw_data_settings_raw_data_loader_67) | 원시 데이터를 로드합니다. |
| [merge_layers(bottom_layer, top_layer)](#merge_layers_bottom_layer_top_layer_68) | 레이어를 병합합니다. |
| normalize_angle() |  |
| normalize_angle(resize_proportionally, background_color) |  |
| [read_argb_32_scan_line(scan_line_index)](#read_argb_32_scan_line_scan_line_index_69) | 지정된 스캔 라인 인덱스로 전체 스캔 라인을 읽습니다. |
| [read_scan_line(scan_line_index)](#read_scan_line_scan_line_index_70) | 지정된 스캔 라인 인덱스로 전체 스캔 라인을 읽습니다. |
| [replace_color(old_color, old_color_diff, new_color)](#replace_color_old_color_old_color_diff_new_color_71) | 허용된 차이로 한 색상을 다른 색상으로 교체하고 원래 알파 값을 보존하여 부드러운 가장자리를 유지합니다. |
| [replace_color(old_color_argb, old_color_diff, new_color_argb)](#replace_color_old_color_argb_old_color_diff_new_color_argb_72) | 허용된 차이로 한 색상을 다른 색상으로 교체하고 원래 알파 값을 보존하여 부드러운 가장자리를 유지합니다. |
| [replace_non_transparent_colors(new_color)](#replace_non_transparent_colors_new_color_73) | 투명하지 않은 모든 색상을 새 색상으로 교체하고 원래 알파 값을 유지하여 부드러운 가장자리를 보존합니다.<br/>            참고: 투명성이 없는 이미지에 사용하면 모든 색상이 하나의 색상으로 교체됩니다. |
| [replace_non_transparent_colors(new_color_argb)](#replace_non_transparent_colors_new_color_argb_74) | 투명하지 않은 모든 색상을 새 색상으로 교체하고 원래 알파 값을 유지하여 부드러운 가장자리를 보존합니다.<br/>            참고: 투명성이 없는 이미지에 사용하면 모든 색상이 하나의 색상으로 교체됩니다. |
| [resize(new_width, new_height)](#resize_new_width_new_height_75) | 이미지를 리사이즈합니다. 기본값으로 [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/)이 사용됩니다. |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_76) | 이미지를 리사이즈합니다. |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_77) | 이미지를 리사이즈합니다. |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_78) | 높이를 비례적으로 리사이즈합니다. |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_79) | 높이를 비례적으로 리사이즈합니다. |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_80) | 높이를 비례적으로 리사이즈합니다. |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_81) | 너비를 비례적으로 리사이즈합니다. 기본값으로 [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/)이 사용됩니다. |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_82) | 너비를 비례적으로 리사이즈합니다. |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_83) | 너비를 비례적으로 리사이즈합니다. |
| [rotate(angle)](#rotate_angle_84) | 이미지를 중심을 기준으로 회전합니다. |
| [rotate(angle, resize_proportionally, background_color)](#rotate_angle_resize_proportionally_background_color_85) | 이미지를 중심을 기준으로 회전합니다. |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_86) | 이미지를 회전하거나 뒤집거나 회전 및 뒤집습니다. |
| save() | 이미지 데이터를 기본 스트림에 저장합니다. |
| [save(file_path)](#save_file_path_87) | 지정된 파일 위치에 객체의 데이터를 저장합니다. |
| [save(file_path, options)](#save_file_path_options_88) | 저장 옵션에 따라 지정된 파일 형식으로 지정된 파일 위치에 객체의 데이터를 저장합니다. |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_89) | 저장 옵션에 따라 지정된 파일 형식으로 지정된 파일 위치에 객체의 데이터를 저장합니다. |
| [save(file_path, over_write)](#save_file_path_over_write_90) | 지정된 파일 위치에 객체의 데이터를 저장합니다. |
| [save(stream)](#save_stream_91) | 지정된 스트림에 객체의 데이터를 저장합니다. |
| [save(stream, options_base)](#save_stream_options_base_92) | 저장 옵션에 따라 지정된 파일 형식으로 지정된 스트림에 이미지 데이터를 저장합니다. |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_93) | 저장 옵션에 따라 지정된 파일 형식으로 지정된 스트림에 이미지 데이터를 저장합니다. |
| [save_argb_32_pixels(rectangle, pixels)](#save_argb_32_pixels_rectangle_pixels_94) | 32비트 ARGB 픽셀을 저장합니다. |
| save_cmyk_32_pixels(rectangle, pixels) |  |
| save_cmyk_pixels(rectangle, pixels) |  |
| [save_pixels(rectangle, pixels)](#save_pixels_rectangle_pixels_95) | 픽셀을 저장합니다 (형식 별 메서드). |
| [save_raw_data(data, data_offset, rectangle, raw_data_settings)](#save_raw_data_data_data_offset_rectangle_raw_data_settings_96) | 원시 데이터를 저장합니다. |
| [set_argb_32_pixel(x, y, argb_32_color)](#set_argb_32_pixel_x_y_argb_32_color_97) | 지정된 위치에 이미지 32비트 ARGB 픽셀을 설정합니다. |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_98) | 이미지 팔레트를 설정합니다. |
| [set_pixel(x, y, color)](#set_pixel_x_y_color_99) | 지정된 위치에 이미지 픽셀을 설정합니다. |
| [set_resolution(dpi_x, dpi_y)](#set_resolution_dpi_x_dpi_y_100) | 이 [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/)의 해상도를 설정합니다. |
| [to_bitmap()](#to_bitmap__101) |    |
| [write_argb_32_scan_line(scan_line_index, argb_32_pixels)](#write_argb_32_scan_line_scan_line_index_argb_32_pixels_102) | 전체 스캔 라인을 지정된 스캔 라인 인덱스로 씁니다. |
| [write_scan_line(scan_line_index, pixels)](#write_scan_line_scan_line_index_pixels_103) | 전체 스캔 라인을 지정된 스캔 라인 인덱스로 씁니다. |


### Constructor: PsdImage(path) {#PsdImage_path_1}


```
 PsdImage(path) 
```

지정된 경로에 있는 래스터 이미지(경로에 PSD 이미지가 아님)로부터 [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) 클래스의 새 인스턴스를 초기화합니다. 기본 매개변수로 PSD 이미지를 초기화하는 데 사용됩니다 - 색상 모드 - rgb, 4채널, 채널당 8비트, 압축 - Raw.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 경로 | 문자열 | 픽셀 및 팔레트 데이터를 로드하고 초기화할 경로입니다. |

### Constructor: PsdImage(path, color_mode, channel_bit_depth, channels, psd_version, compression) {#PsdImage_path_color_mode_channel_bit_depth_channels_psd_version_compression_2}


```
 PsdImage(path, color_mode, channel_bit_depth, channels, psd_version, compression) 
```

지정된 경로에 있는 래스터 이미지(경로에 PSD 이미지가 아님)로부터 [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) 클래스를 생성자 매개변수를 사용하여 새 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 경로 | 문자열 | 픽셀 및 팔레트 데이터를 로드하고 초기화할 경로입니다. |
| color_mode | [ColorModes](/psd/python-net/aspose.psd.fileformats.psd/colormodes) | 색상 모드. |
| channel_bit_depth | short | 채널당 PSD 비트 깊이입니다. |
| channels | short | PSD 채널 수입니다. |
| psd_version | int | PSD 버전. |
| compression | [CompressionMethod](/psd/python-net/aspose.psd.fileformats.psd/compressionmethod) | 사용할 압축 방식입니다. |

### Constructor: PsdImage(raster_image) {#PsdImage_raster_image_3}


```
 PsdImage(raster_image) 
```

기존 래스터 이미지(PSD 이미지가 아님)에서 RGB 색상 모드, 4채널, 채널당 8비트, 압축 없음으로 [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| raster_image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | 픽셀 및 팔레트 데이터를 로드하고 초기화할 이미지입니다. |

### Constructor: PsdImage(raster_image, color_mode, channel_bit_depth, channels, psd_version, compression) {#PsdImage_raster_image_color_mode_channel_bit_depth_channels_psd_version_compression_4}


```
 PsdImage(raster_image, color_mode, channel_bit_depth, channels, psd_version, compression) 
```

기존 래스터 이미지(PSD 이미지가 아님)에서 생성자 매개변수를 사용하여 [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| raster_image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | 픽셀 및 팔레트 데이터를 로드하고 초기화할 이미지입니다. |
| color_mode | [ColorModes](/psd/python-net/aspose.psd.fileformats.psd/colormodes) | 색상 모드. |
| channel_bit_depth | short | 채널당 PSD 비트 깊이입니다. |
| channels | short | PSD 채널 수입니다. |
| psd_version | int | PSD 버전. |
| compression | [CompressionMethod](/psd/python-net/aspose.psd.fileformats.psd/compressionmethod) | 사용할 압축 방식입니다. |

### Constructor: PsdImage(stream) {#PsdImage_stream_5}


```
 PsdImage(stream) 
```

스트림에 있는 래스터 이미지(스트림에 PSD 이미지가 아님)에서 지정된 경로로부터 [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) 클래스의 새 인스턴스를 초기화합니다. 기본 매개변수로 PSD 이미지를 초기화하는 데 사용됩니다 - 색상 모드 - rgb, 4채널, 채널당 8비트, 압축 - Raw.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 스트림 | _io.BufferedRandom | 픽셀 및 팔레트 데이터를 로드하고 초기화할 스트림입니다. |

### Constructor: PsdImage(stream, color_mode, channel_bit_depth, channels, psd_version, compression) {#PsdImage_stream_color_mode_channel_bit_depth_channels_psd_version_compression_6}


```
 PsdImage(stream, color_mode, channel_bit_depth, channels, psd_version, compression) 
```

스트림에 있는 래스터 이미지(스트림에 PSD 이미지가 아님)에서 지정된 경로로부터 [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) 클래스를 생성자 매개변수를 사용하여 새 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 스트림 | _io.BufferedRandom | 픽셀 및 팔레트 데이터를 로드하고 초기화할 스트림입니다. |
| color_mode | [ColorModes](/psd/python-net/aspose.psd.fileformats.psd/colormodes) | 색상 모드. |
| channel_bit_depth | short | 채널당 PSD 비트 깊이입니다. |
| channels | short | PSD 채널 수입니다. |
| psd_version | int | PSD 버전. |
| compression | [CompressionMethod](/psd/python-net/aspose.psd.fileformats.psd/compressionmethod) | 사용할 압축 방식입니다. |

### Constructor: PsdImage(width, height) {#PsdImage_width_height_7}


```
 PsdImage(width, height) 
```

지정된 너비와 높이로 [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) 클래스의 새 인스턴스를 초기화합니다. 빈 PSD 이미지를 초기화하는 데 사용됩니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| width | int | 이미지 너비입니다. |
| 높이 | int | 이미지 높이. |

### Constructor: PsdImage(width, height, color_palette, color_mode, channel_bit_depth, channels, psd_version, compression) {#PsdImage_width_height_color_palette_color_mode_channel_bit_depth_channels_psd_version_compression_8}


```
 PsdImage(width, height, color_palette, color_mode, channel_bit_depth, channels, psd_version, compression) 
```

지정된 너비, 높이, paletter, 색상 모드, 채널 수 및 채널 비트 길이와 지정된 압축 모드 매개변수를 사용하여 [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) 클래스의 새 인스턴스를 초기화합니다. 빈 PSD 이미지를 초기화하는 데 사용됩니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| width | int | 이미지 너비입니다. |
| 높이 | int | 이미지 높이. |
| color_palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | 색상 팔레트. |
| color_mode | [ColorModes](/psd/python-net/aspose.psd.fileformats.psd/colormodes) | 색상 모드. |
| channel_bit_depth | short | 채널당 PSD 비트 깊이입니다. |
| channels | short | PSD 채널 수입니다. |
| psd_version | int | PSD 버전. |
| compression | [CompressionMethod](/psd/python-net/aspose.psd.fileformats.psd/compressionmethod) | 사용할 압축 방식입니다. |

### Method: add_black_white_adjustment_layer() {#add_black_white_adjustment_layer__1}


```
 add_black_white_adjustment_layer() 
```

흑백 조정 레이어를 추가합니다.

**Returns**

| 유형 | 설명 |
| :- | :- |
| [BlackWhiteAdjustmentLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/blackwhiteadjustmentlayer/) | 생성된 흑백 조정 레이어. |


### Method: add_brightness_contrast_adjustment_layer(brightness, contrast) {#add_brightness_contrast_adjustment_layer_brightness_contrast_2}


```
 add_brightness_contrast_adjustment_layer(brightness, contrast) 
```

밝기/대비 조정 레이어를 추가합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 밝기 | int | 밝기입니다. |
| 대비 | int | 대비입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [BrightnessContrastLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/brightnesscontrastlayer/) | 생성된 밝기/대비 레이어 |


### Method: add_channel_mixer_adjustment_layer() {#add_channel_mixer_adjustment_layer__3}


```
 add_channel_mixer_adjustment_layer() 
```

기본 매개변수로 채널 믹서 조정 레이어를 추가합니다.

**Returns**

| 유형 | 설명 |
| :- | :- |
| [ChannelMixerLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/channelmixerlayer/) | 채널 믹서 레이어 추가 |


### Method: add_color_balance_adjustment_layer() {#add_color_balance_adjustment_layer__4}


```
 add_color_balance_adjustment_layer() 
```

색상 균형 조정 레이어를 추가합니다.

**Returns**

| 유형 | 설명 |
| :- | :- |
| [ColorBalanceAdjustmentLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer/) | 새로 생성된 색상 균형 레이어. |


### Method: add_curves_adjustment_layer() {#add_curves_adjustment_layer__5}


```
 add_curves_adjustment_layer() 
```

곡선 조정 레이어를 추가합니다.

**Returns**

| 유형 | 설명 |
| :- | :- |
| [CurvesLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/curveslayer/) | 생성된 [CurvesLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/curveslayer/) 레이어 |


### Method: add_exposure_adjustment_layer(exposure, offset, gamma_correction) {#add_exposure_adjustment_layer_exposure_offset_gamma_correction_6}


```
 add_exposure_adjustment_layer(exposure, offset, gamma_correction) 
```

노출 조정 레이어를 추가합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 노출 | float | 노출입니다. |
| offset | float | 오프셋. |
| 감마_보정 | float | 감마 보정. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [ExposureLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/exposurelayer/) | 노출 조정 레이어 생성 |


### Method: add_gradient_map_adjustment_layer() {#add_gradient_map_adjustment_layer__7}


```
 add_gradient_map_adjustment_layer() 
```

그라디언트 맵 조정 레이어를 추가합니다.

**Returns**

| 유형 | 설명 |
| :- | :- |
| [GradientMapLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/gradientmaplayer/) | GradientMap 인스턴스. |


### Method: add_hue_saturation_adjustment_layer() {#add_hue_saturation_adjustment_layer__8}


```
 add_hue_saturation_adjustment_layer() 
```

색조/채도 조정 레이어를 추가합니다.

**Returns**

| 유형 | 설명 |
| :- | :- |
| [HueSaturationLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/huesaturationlayer/) | 새로 생성된 색조/채도 레이어. |


### Method: add_invert_adjustment_layer() {#add_invert_adjustment_layer__9}


```
 add_invert_adjustment_layer() 
```

반전 조정 레이어를 추가합니다.

**Returns**

| 유형 | 설명 |
| :- | :- |
| [InvertAdjustmentLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/invertadjustmentlayer/) | 생성된 반전 레이어 |


### Method: add_layer(layer) {#add_layer_layer_10}


```
 add_layer(layer) 
```

레이어를 추가합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| layer | [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | 레이어. |

### Method: add_layer_group(group_name, index, start_behaviour) {#add_layer_group_group_name_index_start_behaviour_11}


```
 add_layer_group(group_name, index, start_behaviour) 
```

레이어 그룹을 추가합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| group_name | 문자열 | 그룹의 이름입니다. |
| index | int | 삽입할 레이어 뒤의 인덱스입니다. |
| start_behaviour | bool | 만약 <c>true</c> 로 설정하면 [start behaviour] 그룹이 시작 시 열려 있는 상태가 되며, 그렇지 않으면 최소화된 상태가 됩니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [LayerGroup](/psd/python-net/aspose.psd.fileformats.psd.layers/layergroup/) | 그룹 레이어 열기 |


### Method: add_levels_adjustment_layer() {#add_levels_adjustment_layer__12}


```
 add_levels_adjustment_layer() 
```

Levels 조정 레이어를 추가합니다.

**Returns**

| 유형 | 설명 |
| :- | :- |
| [LevelsLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/levelslayer/) | 새로 생성된 레벨 레이어 |


### Method: add_photo_filter_layer(color) {#add_photo_filter_layer_color_13}


```
 add_photo_filter_layer(color) 
```

PhotoFilter 레이어를 추가합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) | 색상. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [PhotoFilterLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/photofilterlayer/) | PhotoFilter 레이어 생성 |


### Method: add_posterize_adjustment_layer() {#add_posterize_adjustment_layer__14}


```
 add_posterize_adjustment_layer() 
```

Posterize 조정 레이어를 추가합니다.

**Returns**

| 유형 | 설명 |
| :- | :- |
| [PosterizeLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/posterizelayer/) | PosterizeLayer 인스턴스. |


### Method: add_regular_layer() {#add_regular_layer__15}


```
 add_regular_layer() 
```

새로운 일반 레이어를 추가합니다.

**Returns**

| 유형 | 설명 |
| :- | :- |
| [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | 일반 레이어 생성. |


### Method: add_selective_color_adjustment_layer() {#add_selective_color_adjustment_layer__16}


```
 add_selective_color_adjustment_layer() 
```

선택 색상 조정 레이어를 추가합니다.

**Returns**

| 유형 | 설명 |
| :- | :- |
| [SelectiveColorLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/selectivecolorlayer/) | 생성된 선택 색상 조정 레이어. |


### Method: add_shape_layer() {#add_shape_layer__17}


```
 add_shape_layer() 
```

빈 Shape 레이어를 추가합니다.<br/>            경로가 없습니다. 저장하기 전에 shape 레이어에 추가해야 합니다.

**Returns**

| 유형 | 설명 |
| :- | :- |
| [ShapeLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/shapelayer/) | ShapeLayer 인스턴스. |


### Method: add_text_layer(text, rect) {#add_text_layer_text_rect_18}


```
 add_text_layer(text, rect) 
```

새로운 Text 레이어를 추가합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| text | 문자열 | 레이어의 텍스트. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 레이어의 사각형. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [TextLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/textlayer/) | 텍스트 레이어 생성. |


### Method: add_threshold_adjustment_layer() {#add_threshold_adjustment_layer__19}


```
 add_threshold_adjustment_layer() 
```

Threshold 조정 레이어를 추가합니다.

**Returns**

| 유형 | 설명 |
| :- | :- |
| [ThresholdLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/thresholdlayer/) | 생성된 임계값 조정 레이어. |


### Method: add_vibrance_adjustment_layer() {#add_vibrance_adjustment_layer__20}


```
 add_vibrance_adjustment_layer() 
```

Vibrance 조정 레이어를 추가합니다.

**Returns**

| 유형 | 설명 |
| :- | :- |
| [VibranceLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/vibrancelayer/) | 새로 생성된 활기 레이어. |


### Method: adjust_brightness(brightness) {#adjust_brightness_brightness_21}


```
 adjust_brightness(brightness) 
```

이미지의 밝기를 조정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 밝기 | int | 밝기 값입니다. |

### Method: adjust_contrast(contrast) {#adjust_contrast_contrast_22}


```
 adjust_contrast(contrast) 
```

이미지 대비

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 대비 | float | 대비 값 (범위 [-100; 100]) |

### Method: adjust_gamma(gamma) {#adjust_gamma_gamma_23}


```
 adjust_gamma(gamma) 
```

이미지의 감마 보정.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 감마 | float | 빨강, 초록 및 파랑 채널에 대한 감마 계수 |

### Method: adjust_gamma(gamma_red, gamma_green, gamma_blue) {#adjust_gamma_gamma_red_gamma_green_gamma_blue_24}


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

### Method: binarize_bradley(brightness_difference) {#binarize_bradley_brightness_difference_25}


```
 binarize_bradley(brightness_difference) 
```

Bradley의 적응형 임계값 알고리즘과 적분 이미지 임계값을 사용하여 이미지 이진화

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| brightness_difference | double | 픽셀과 해당 픽셀을 중심으로 하는 s x s 창의 픽셀 평균 사이의 밝기 차이. |

### Method: binarize_bradley(brightness_difference, window_size) {#binarize_bradley_brightness_difference_window_size_26}


```
 binarize_bradley(brightness_difference, window_size) 
```

Bradley의 적응형 임계값 알고리즘과 적분 이미지 임계값을 사용하여 이미지 이진화

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| brightness_difference | double | 픽셀과 해당 픽셀을 중심으로 하는 s x s 창의 픽셀 평균 사이의 밝기 차이. |
| window_size | int | 해당 픽셀을 중심으로 하는 s x s 픽셀 창의 크기 |

### Method: binarize_fixed(threshold) {#binarize_fixed_threshold_27}


```
 binarize_fixed(threshold) 
```

미리 정의된 임계값으로 이미지 이진화

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 임계값 | byte | 임계값. 픽셀의 해당 회색 값이 임계값보다 크면 255가 할당되고, 그렇지 않으면 0이 할당됩니다. |

### Method: can_load(file_path)  [static] {#can_load_file_path_28}


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


### Method: can_load(file_path, load_options)  [static] {#can_load_file_path_load_options_29}


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


### Method: can_load(stream)  [static] {#can_load_stream_30}


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


### Method: can_load(stream, load_options)  [static] {#can_load_stream_load_options_31}


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


### Method: can_save(options) {#can_save_options_32}


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


### Method: convert(new_options) {#convert_new_options_33}


```
 convert(new_options) 
```

이 이미지 형식을 옵션에 지정된 형식으로 변환합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| new_options | [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/) | 새 옵션. |

### Method: create(image_options, width, height)  [static] {#create_image_options_width_height_34}


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


### Method: crop(rectangle) {#crop_rectangle_35}


```
 crop(rectangle) 
```

이미지를 자릅니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 사각형. |

### Method: dither(dithering_method, bits_count) {#dither_dithering_method_bits_count_36}


```
 dither(dithering_method, bits_count) 
```

현재 이미지에 디더링을 수행합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/psd/python-net/aspose.psd/ditheringmethod) | 디더링 방법. |
| bits_count | int | 디더링을 위한 최종 비트 수. |

### Method: dither(dithering_method, bits_count, custom_palette) {#dither_dithering_method_bits_count_custom_palette_37}


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

### Method: filter(rectangle, options) {#filter_rectangle_options_38}


```
 filter(rectangle, options) 
```

지정된 사각형을 필터링합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 사각형. |
| options | [FilterOptionsBase](/psd/python-net/aspose.psd.imagefilters.filteroptions/filteroptionsbase/) | 옵션. |

### Method: get_argb_32_pixel(x, y) {#get_argb_32_pixel_x_y_39}


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


### Method: get_default_argb_32_pixels(rectangle) {#get_default_argb_32_pixels_rectangle_40}


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


### Method: get_default_options(args) {#get_default_options_args_41}


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


### Method: get_default_pixels(rectangle, partial_pixel_loader) {#get_default_pixels_rectangle_partial_pixel_loader_42}


```
 get_default_pixels(rectangle, partial_pixel_loader) 
```

부분 픽셀 로더를 사용하여 기본 픽셀 배열을 가져옵니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 픽셀을 가져올 사각형. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/psd/python-net/aspose.psd/ipartialargb32pixelloader) | 부분 픽셀 로더. |

### Method: get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) {#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_43}


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

### Method: get_default_raw_data(rectangle, raw_data_settings) {#get_default_raw_data_rectangle_raw_data_settings_44}


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


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_45}


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


### Method: get_file_format(stream)  [static] {#get_file_format_stream_46}


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


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_47}


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


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_48}


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


### Method: get_modify_date(use_default) {#get_modify_date_use_default_49}


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


### Method: get_original_options() {#get_original_options__50}


```
 get_original_options() 
```

원본 파일 설정을 기반으로 옵션을 가져옵니다.<br/>            이는 원본 이미지의 비트 깊이 및 기타 매개변수를 변경하지 않도록 유지하는 데 도움이 될 수 있습니다.<br/>            예를 들어, 1비트 픽셀의 흑백 PNG 이미지를 로드한 후<br/>            [DataStreamSupporter.save(file_path)](/psd/python-net/aspose.psd/datastreamsupporter/) 메서드를 사용하여 저장하면 8비트 픽셀의 PNG 이미지가 출력됩니다.<br/>            이를 방지하고 1비트 픽셀 PNG 이미지를 저장하려면 이 메서드를 사용하여 해당 저장 옵션을 가져오고 이를<br/>            [Image.save(file_path, options)](/psd/python-net/aspose.psd/image/) 메서드의 두 번째 매개변수로 전달하십시오.

**Returns**

| 유형 | 설명 |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | 원본 파일 설정을 기반으로 하는 옵션입니다. |


### Method: get_pixel(x, y) {#get_pixel_x_y_51}


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


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_52}


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


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_53}


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


### Method: get_skew_angle() {#get_skew_angle__54}


```
 get_skew_angle() 
```

  

**Returns**

| 유형 | 설명 |
| :- | :- |
| float |  |


### Method: load(file_path)  [static] {#load_file_path_55}


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


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_56}


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


### Method: load(stream)  [static] {#load_stream_57}


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


### Method: load(stream, load_options)  [static] {#load_stream_load_options_58}


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


### Method: load_argb_32_pixels(rectangle) {#load_argb_32_pixels_rectangle_59}


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


### Method: load_argb_64_pixels(rectangle) {#load_argb_64_pixels_rectangle_60}


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


### Method: load_cmyk_32_pixels(rectangle) {#load_cmyk_32_pixels_rectangle_61}


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


### Method: load_cmyk_pixels(rectangle) {#load_cmyk_pixels_rectangle_62}


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


### Method: load_partial_argb_32_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_63}


```
 load_partial_argb_32_pixels(rectangle, partial_pixel_loader) 
```

32비트 ARGB 픽셀을 부분적으로(블록 단위로) 로드합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 픽셀을 로드할 사각형. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/psd/python-net/aspose.psd/ipartialargb32pixelloader) | 부분 픽셀 로더. |

### Method: load_partial_pixels(desired_rectangle, pixel_loader) {#load_partial_pixels_desired_rectangle_pixel_loader_64}


```
 load_partial_pixels(desired_rectangle, pixel_loader) 
```

픽셀을 패키지 단위로 부분적으로 로드합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| desired_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 원하는 사각형입니다. |
| pixel_loader | [IPartialPixelLoader](/psd/python-net/aspose.psd/ipartialpixelloader) | 픽셀 로더입니다. |

### Method: load_pixels(rectangle) {#load_pixels_rectangle_65}


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


### Method: load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_66}


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

### Method: load_raw_data(rectangle, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_raw_data_settings_raw_data_loader_67}


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

### Method: merge_layers(bottom_layer, top_layer) {#merge_layers_bottom_layer_top_layer_68}


```
 merge_layers(bottom_layer, top_layer) 
```

레이어를 병합합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| bottom_layer | [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | 하단 레이어. |
| top_layer | [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | 상단 레이어. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | 병합 후 하단 레이어 |


### Method: read_argb_32_scan_line(scan_line_index) {#read_argb_32_scan_line_scan_line_index_69}


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


### Method: read_scan_line(scan_line_index) {#read_scan_line_scan_line_index_70}


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


### Method: replace_color(old_color, old_color_diff, new_color) {#replace_color_old_color_old_color_diff_new_color_71}


```
 replace_color(old_color, old_color_diff, new_color) 
```

허용된 차이로 한 색상을 다른 색상으로 교체하고 원래 알파 값을 보존하여 부드러운 가장자리를 유지합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| old_color | [Color](/psd/python-net/aspose.psd/color) |  |
| old_color_diff | byte | 대체된 색조를 넓히기 위해 허용되는 이전 색상의 차이. |
| new_color | [Color](/psd/python-net/aspose.psd/color) |  |

### Method: replace_color(old_color_argb, old_color_diff, new_color_argb) {#replace_color_old_color_argb_old_color_diff_new_color_argb_72}


```
 replace_color(old_color_argb, old_color_diff, new_color_argb) 
```

허용된 차이로 한 색상을 다른 색상으로 교체하고 원래 알파 값을 보존하여 부드러운 가장자리를 유지합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| old_color_argb | int | 대체될 이전 색상의 ARGB 값. |
| old_color_diff | byte | 대체된 색조를 넓히기 위해 허용되는 이전 색상의 차이. |
| new_color_argb | int | 이전 색상을 대체할 새로운 색상의 ARGB 값. |

### Method: replace_non_transparent_colors(new_color) {#replace_non_transparent_colors_new_color_73}


```
 replace_non_transparent_colors(new_color) 
```

투명하지 않은 모든 색상을 새 색상으로 교체하고 원래 알파 값을 유지하여 부드러운 가장자리를 보존합니다.<br/>            참고: 투명성이 없는 이미지에 사용하면 모든 색상이 하나의 색상으로 교체됩니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| new_color | [Color](/psd/python-net/aspose.psd/color) |  |

### Method: replace_non_transparent_colors(new_color_argb) {#replace_non_transparent_colors_new_color_argb_74}


```
 replace_non_transparent_colors(new_color_argb) 
```

투명하지 않은 모든 색상을 새 색상으로 교체하고 원래 알파 값을 유지하여 부드러운 가장자리를 보존합니다.<br/>            참고: 투명성이 없는 이미지에 사용하면 모든 색상이 하나의 색상으로 교체됩니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| new_color_argb | int | 투명하지 않은 색상을 교체할 새 색상 ARGB 값. |

### Method: resize(new_width, new_height) {#resize_new_width_new_height_75}


```
 resize(new_width, new_height) 
```

이미지를 리사이즈합니다. 기본값으로 [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/)이 사용됩니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| new_width | int | 새로운 너비입니다. |
| new_height | int | 새로운 높이입니다. |

### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_76}


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

### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_77}


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

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_78}


```
 resize_height_proportionally(new_height) 
```

높이를 비례적으로 리사이즈합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| new_height | int | 새로운 높이입니다. |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_79}


```
 resize_height_proportionally(new_height, resize_type) 
```

높이를 비례적으로 리사이즈합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| new_height | int | 새로운 높이입니다. |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | 크기 조정 유형. |

### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_80}


```
 resize_height_proportionally(new_height, settings) 
```

높이를 비례적으로 리사이즈합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| new_height | int | 새로운 높이입니다. |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | 이미지 크기 조정 설정. |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_81}


```
 resize_width_proportionally(new_width) 
```

너비를 비례적으로 리사이즈합니다. 기본값으로 [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/)이 사용됩니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| new_width | int | 새로운 너비입니다. |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_82}


```
 resize_width_proportionally(new_width, resize_type) 
```

너비를 비례적으로 리사이즈합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| new_width | int | 새로운 너비입니다. |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | 크기 조정 유형. |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_83}


```
 resize_width_proportionally(new_width, settings) 
```

너비를 비례적으로 리사이즈합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| new_width | int | 새로운 너비입니다. |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | 이미지 크기 조정 설정. |

### Method: rotate(angle) {#rotate_angle_84}


```
 rotate(angle) 
```

이미지를 중심을 기준으로 회전합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 각도 | float | 회전 각도(도). 양수 값은 시계 방향으로 회전합니다. |

### Method: rotate(angle, resize_proportionally, background_color) {#rotate_angle_resize_proportionally_background_color_85}


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

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_86}


```
 rotate_flip(rotate_flip_type) 
```

이미지를 회전하거나 뒤집거나 회전 및 뒤집습니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/psd/python-net/aspose.psd/rotatefliptype) | 회전 뒤집기 유형. |

### Method: save(file_path) {#save_file_path_87}


```
 save(file_path) 
```

지정된 파일 위치에 객체의 데이터를 저장합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| file_path | 문자열 | 객체 데이터를 저장할 파일 경로. |

### Method: save(file_path, options) {#save_file_path_options_88}


```
 save(file_path, options) 
```

저장 옵션에 따라 지정된 파일 형식으로 지정된 파일 위치에 객체의 데이터를 저장합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| file_path | 문자열 | 파일 경로. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | 옵션. |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_89}


```
 save(file_path, options, bounds_rectangle) 
```

저장 옵션에 따라 지정된 파일 형식으로 지정된 파일 위치에 객체의 데이터를 저장합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| file_path | 문자열 | 파일 경로. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | 옵션. |
| bounds_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 대상 이미지 경계 사각형. 빈 사각형을 설정하면 소스 경계를 사용합니다. |

### Method: save(file_path, over_write) {#save_file_path_over_write_90}


```
 save(file_path, over_write) 
```

지정된 파일 위치에 객체의 데이터를 저장합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| file_path | 문자열 | 객체 데이터를 저장할 파일 경로. |
| over_write | bool | 만약 <c>true</c> 로 설정하면 파일 내용을 덮어쓰고, 그렇지 않으면 추가됩니다. |

### Method: save(stream) {#save_stream_91}


```
 save(stream) 
```

지정된 스트림에 객체의 데이터를 저장합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 스트림 | _io.BufferedRandom | 객체 데이터를 저장할 스트림. |

### Method: save(stream, options_base) {#save_stream_options_base_92}


```
 save(stream, options_base) 
```

저장 옵션에 따라 지정된 파일 형식으로 지정된 스트림에 이미지 데이터를 저장합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 스트림 | _io.BufferedRandom | 이미지 데이터를 저장할 스트림. |
| options_base | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | 저장 옵션. |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_93}


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

### Method: save_argb_32_pixels(rectangle, pixels) {#save_argb_32_pixels_rectangle_pixels_94}


```
 save_argb_32_pixels(rectangle, pixels) 
```

32비트 ARGB 픽셀을 저장합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 픽셀을 저장할 사각형. |
| pixels | int | 32비트 ARGB 픽셀 배열. |

### Method: save_pixels(rectangle, pixels) {#save_pixels_rectangle_pixels_95}


```
 save_pixels(rectangle, pixels) 
```

픽셀을 저장합니다 (형식 별 메서드).

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 픽셀을 저장할 사각형. |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) | 32비트 ARGB 픽셀 배열. |

### Method: save_raw_data(data, data_offset, rectangle, raw_data_settings) {#save_raw_data_data_data_offset_rectangle_raw_data_settings_96}


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

### Method: set_argb_32_pixel(x, y, argb_32_color) {#set_argb_32_pixel_x_y_argb_32_color_97}


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

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_98}


```
 set_palette(palette, update_colors) 
```

이미지 팔레트를 설정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | 설정할 팔레트. |
| update_colors | bool | 설정이 <c>true</c>이면 색상이 새 팔레트에 따라 업데이트됩니다; 그렇지 않으면 색인은 변경되지 않은 상태로 유지됩니다. 변경되지 않은 색인은 일부 색인에 해당하는 팔레트 항목이 없을 경우 이미지를 로드할 때 충돌할 수 있습니다. |

### Method: set_pixel(x, y, color) {#set_pixel_x_y_color_99}


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

### Method: set_resolution(dpi_x, dpi_y) {#set_resolution_dpi_x_dpi_y_100}


```
 set_resolution(dpi_x, dpi_y) 
```

이 [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/)의 해상도를 설정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| dpi_x | double | 인치당 도트 수로 표시된 [RasterImage](/psd/python-net/aspose.psd/rasterimage/)의 수평 해상도. |
| dpi_y | double | 인치당 도트 수로 표시된 [RasterImage](/psd/python-net/aspose.psd/rasterimage/)의 수직 해상도. |

### Method: to_bitmap() {#to_bitmap__101}


```
 to_bitmap() 
```

  

**Returns**

| 유형 | 설명 |
| :- | :- |
| aspose.pydrawing.Bitmap |  |


### Method: write_argb_32_scan_line(scan_line_index, argb_32_pixels) {#write_argb_32_scan_line_scan_line_index_argb_32_pixels_102}


```
 write_argb_32_scan_line(scan_line_index, argb_32_pixels) 
```

전체 스캔 라인을 지정된 스캔 라인 인덱스로 씁니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| scan_line_index | int | 스캔 라인의 0 기반 인덱스입니다. |
| argb_32_pixels | int | 작성할 32비트 ARGB 색상 배열입니다. |

### Method: write_scan_line(scan_line_index, pixels) {#write_scan_line_scan_line_index_pixels_103}


```
 write_scan_line(scan_line_index, pixels) 
```

전체 스캔 라인을 지정된 스캔 라인 인덱스로 씁니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| scan_line_index | int | 스캔 라인의 0 기반 인덱스입니다. |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) | 작성할 픽셀 색상 배열입니다. |

