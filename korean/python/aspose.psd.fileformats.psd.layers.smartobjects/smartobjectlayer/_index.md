---
title: "SmartObjectLayer 클래스"
type: docs
weight: 10
url: /ko/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/
---

**Summary:** Defines the SmartObjectLayer class that contains embedded in the PSD file or linked smart object in the external file.<br/>            With Smart Objects, you can:<br/>            Perform nondestructive transforms. You can scale, rotate, skew, distort, perspective transform, or warp a layer<br/>            without losing original image data or quality because the transforms don�t affect the original data.<br/>            Work with vector data, such as vector artwork from Illustrator, that otherwise would be rasterized.<br/>            Perform nondestructive filtering. You can edit filters applied to Smart Objects at any time.<br/>            Edit one Smart Object and automatically update all its linked instances.<br/>            Apply a layer mask that�s either linked or unlinked to the Smart Object layer.<br/>            Try various designs with low-resolution placeholder images that you later replace with final versions.<br/>            In Adobe� Photoshop�, you can embed the contents of an image into a PSD document.<br/>            More information is here: <see href="https://helpx.adobe.com/photoshop/using/create-smart-objects.html" /><br/>            A layer with an embedded smart object contains placed (PlLd) and SoLd resources with smart object properties.<br/>            The PlLd resource can be alone for PSD versions older then 10.<br/>            These resources contain UniqueId of the LiFdDataSource in the global Lnk2Resource with the embedded filename<br/>            and other parameters, including the embedded file contents in the original format as a byte array.

**Module:** [aspose.psd.fileformats.psd.layers.smartobjects](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/)

**Full Name:** aspose.psd.fileformats.psd.layers.smartobjects.SmartObjectLayer

**Inheritance:** IObjectWithBounds, IRasterImageArgb32PixelLoader, IRasterImageRawDataLoader, Layer

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [SmartObjectLayer(stream)](#SmartObjectLayer_stream_1) | 새로운 [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) 클래스 인스턴스를 초기화합니다. |
## **Properties**
| **Name** | **Type** | **Access** | **설명** |
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
| 하단 | int | r/w |  |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | 객체 경계를 가져옵니다. |
| buffer_size_hint | int | r/w |  |
| channel_information | [ChannelInformation[]](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | r/w |    |
| channels_count | ushort | r |  |
| clipping | byte | r/w |  |
| container | [Image](/psd/python-net/aspose.psd/image) | r |    |
| content_type | [SmartObjectType](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjecttype) | r | 스마트 오브젝트 레이어 콘텐츠의 유형을 가져옵니다.<br/>            포함된 스마트 오브젝트 콘텐츠는 포함된 원시 이미지 파일입니다: [LiFdDataSource.data](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/).<br/>            연결된 스마트 오브젝트 콘텐츠는 사용 가능한 경우 연결된 이미지 파일의 원시 콘텐츠입니다: [LiFeDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/).<br/>            [LinkDataSource.is_library_link](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/)가 true인 경우 Adobe� Photoshop� �� Graphics Library에서 로드하는 것을 지원하지 않습니다.<br/>            일반 링크 파일의 경우, 먼저 [LiFeDataSource.relative_path](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/)를 사용하여 원본 이미지 경로 [None](/psd/python-net/aspose.psd/datastreamsupporter/)에 상대적으로 파일을 찾습니다.<br/>            사용 가능한 경우가 아니면 [LiFeDataSource.full_path](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/)를 확인합니다.<br/>            그래도 없으면 이미지와 동일한 디렉터리에서 링크 파일을 찾습니다: [None](/psd/python-net/aspose.psd/datastreamsupporter/). |
| contents | byte | r/w | 스마트 오브젝트 레이어 콘텐츠를 가져오거나 설정합니다.<br/>            포함된 스마트 오브젝트 콘텐츠는 포함된 원시 이미지 파일과 해당 속성입니다: [LiFdDataSource.data](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifdddatasource/).<br/>            연결된 스마트 오브젝트 콘텐츠는 사용 가능한 경우 연결된 이미지 파일의 원시 콘텐츠와 해당 속성입니다: [LiFeDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/).<br/>            [LinkDataSource.is_library_link](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/)가 true인 경우 Adobe� Photoshop� �� Graphics Library에서 로드하는 것을 지원하지 않습니다.<br/>            일반 링크 파일의 경우, 먼저 [LiFeDataSource.relative_path](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/)를 사용하여 원본 이미지 경로 [None](/psd/python-net/aspose.psd/datastreamsupporter/)에 상대적으로 파일을 찾습니다.<br/>            사용 가능한 경우가 아니면 [LiFeDataSource.full_path](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/)를 확인합니다.<br/>            그래도 없으면 이미지와 동일한 디렉터리에서 링크 파일을 찾습니다: [None](/psd/python-net/aspose.psd/datastreamsupporter/). |
| contents_bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | 스마트 오브젝트 콘텐츠의 경계를 가져오거나 설정합니다. |
| contents_source | [LinkDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/) | r/w | 스마트 오브젝트 콘텐츠의 소스를 가져오거나 설정합니다. |
| data_stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | r |    |
| display_name | 문자열 | r/w |  |
| disposed | bool | r |  |
| extra_length | int | r |  |
| file_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r |    |
| fill_opacity | int | r/w |  |
| filler | byte | r/w |  |
| flags | [LayerFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layerflags) | r/w |    |
| has_alpha | bool | r |  |
| has_background_color | bool | r/w |  |
| has_transparent_color | bool | r/w |  |
| 높이 | int | r | 객체 높이를 가져옵니다. |
| horizontal_resolution | double | r/w |  |
| image_opacity | float | r |  |
| interrupt_monitor | [InterruptMonitor](/psd/python-net/aspose.psd.multithreading/interruptmonitor/) | r/w |    |
| is_cached | bool | r |  |
| is_raw_data_available | bool | r | 원시 데이터 로드가 지원되는지 여부를 나타내는 값을 가져옵니다. |
| is_visible | bool | r/w |  |
| is_visible_in_group | bool | r |  |
| layer_blending_ranges_data | [LayerBlendingRangesData](/psd/python-net/aspose.psd.fileformats.psd.layers/layerblendingrangesdata) | r/w |    |
| layer_creation_date_time | datetime | r/w |  |
| layer_lock | [LayerLockType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/layerlocktype/) | r/w |    |
| layer_mask_data | [LayerMaskData](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata) | r/w |    |
| layer_options | [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/) | r |    |
| left | int | r/w |  |
| 길이 | int | r |  |
| name | 문자열 | r/w | 텍스트 레이어의 이름을 가져오거나 설정합니다. |
| opacity | byte | r/w |  |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w |    |
| premultiply_components | bool | r/w |  |
| raw_custom_color_converter | [IColorConverter](/psd/python-net/aspose.psd/icolorconverter) | r/w |    |
| raw_data_format | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r |    |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | r | 현재 원시 데이터 설정을 가져옵니다. 이 설정을 사용할 때 데이터가 변환 없이 로드된다는 점에 유의하십시오. |
| raw_fallback_index | int | r/w |  |
| raw_indexed_color_converter | [IIndexedColorConverter](/psd/python-net/aspose.psd/iindexedcolorconverter) | r/w |    |
| raw_line_size | int | r |  |
| resources | [LayerResource[]](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource) | r/w |    |
| right | int | r/w |  |
| sheet_color_highlight | [SheetColorHighlightEnum](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/sheetcolorhighlightenum/) | r/w |    |
| size | [Size](/psd/python-net/aspose.psd/size) | r | 객체 크기를 가져옵니다. |
| smart_filters | [SmartFilters](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/smartfilters/) | r | 스마트 필터를 가져옵니다. |
| smart_object_provider | [SmartObjectProvider](/psd/python-net/aspose.psd.fileformats.psd/smartobjectprovider) | r | 스마트 객체 제공자를 가져옵니다. |
| top | int | r/w |  |
| transparent_color | [Color](/psd/python-net/aspose.psd/color) | r/w |    |
| update_xmp_data | bool | r/w |  |
| use_palette | bool | r |  |
| use_raw_data | bool | r/w |  |
| vertical_resolution | double | r/w |  |
| warp_settings | [WarpSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.warp/warpsettings/) | r/w | Warp 매개변수를 가져오거나 설정합니다(리소스에서 설정되었거나 가져온 경우, 기본값) |
| width | int | r | 객체 너비를 가져옵니다. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w |    |
## **Methods**
| **Name** | **설명** |
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
| [convert_to_linked(linked_path)](#convert_to_linked_linked_path_6) | 이 포함된 스마트 객체를 연결된 스마트 객체로 변환합니다. |
| [create(image_options, width, height)](#create_image_options_width_height_7) |    |
| crop(left_shift, right_shift, top_shift, bottom_shift) |  |
| crop(rectangle) |  |
| dither(dithering_method, bits_count) |  |
| dither(dithering_method, bits_count, custom_palette) |  |
| draw_image(location, image) |  |
| [duplicate_layer()](#duplicate_layer__8) | 이 레이어를 복사하여 새로운 스마트 객체 레이어를 생성합니다.<br/>            포함된 스마트 객체의 경우 포함된 이미지가 공유된다는 점에 유의하십시오.<br/>            포함된 이미지를 복사하려면 [SmartObjectLayer.new_smart_object_via_copy()](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) 메서드를 사용하십시오. |
| embed_linked() | 연결된 스마트 오브젝트를 이 레이어에 삽입합니다. |
| [export_contents(file_path)](#export_contents_file_path_9) | 임베드되거나 연결된 콘텐츠를 파일로 내보냅니다. |
| filter(rectangle, options) |  |
| [get_argb_32_pixel(x, y)](#get_argb_32_pixel_x_y_10) |    |
| [get_default_argb_32_pixels(rectangle)](#get_default_argb_32_pixels_rectangle_11) |    |
| [get_default_options(args)](#get_default_options_args_12) |    |
| get_default_pixels(rectangle, partial_pixel_loader) |  |
| get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) |  |
| [get_default_raw_data(rectangle, raw_data_settings)](#get_default_raw_data_rectangle_raw_data_settings_13) |    |
| [get_file_format(file_path)](#get_file_format_file_path_14) |    |
| [get_file_format(stream)](#get_file_format_stream_15) |    |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_16) |    |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_17) |    |
| [get_modify_date(use_default)](#get_modify_date_use_default_18) |    |
| [get_original_options()](#get_original_options__19) |    |
| [get_pixel(x, y)](#get_pixel_x_y_20) |    |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_21) |    |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_22) |    |
| [get_skew_angle()](#get_skew_angle__23) |    |
| grayscale() |  |
| [load(file_path)](#load_file_path_24) |    |
| [load(file_path, load_options)](#load_file_path_load_options_25) |    |
| [load(stream)](#load_stream_26) |    |
| [load(stream, load_options)](#load_stream_load_options_27) |    |
| [load_argb_32_pixels(rectangle)](#load_argb_32_pixels_rectangle_28) |    |
| [load_argb_64_pixels(rectangle)](#load_argb_64_pixels_rectangle_29) |    |
| [load_cmyk_32_pixels(rectangle)](#load_cmyk_32_pixels_rectangle_30) |    |
| [load_cmyk_pixels(rectangle)](#load_cmyk_pixels_rectangle_31) |    |
| [load_contents(options)](#load_contents_options_32) | 스마트 오브젝트 레이어의 임베드되거나 연결된 이미지 콘텐츠를 가져옵니다. |
| [load_partial_argb_32_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_33) | 32비트 ARGB 픽셀을 부분적으로(블록 단위로) 로드합니다. |
| load_partial_pixels(desired_rectangle, pixel_loader) |  |
| [load_pixels(rectangle)](#load_pixels_rectangle_34) |    |
| load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) |  |
| [load_raw_data(rectangle, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_raw_data_settings_raw_data_loader_35) | 원시 데이터를 로드합니다. |
| merge_layer_to(layer_to_merge_into) |  |
| [new_smart_object_via_copy()](#new_smart_object_via_copy__36) | 이 레이어를 복사하여 새로운 스마트 오브젝트 레이어를 생성합니다.<br/>            Adobe™ Photoshop™의 `Layer -&gt; Smart Objects -&gt; New Smart Object via Copy` 기능을 재현합니다.<br/>            임베드된 스마트 오브젝트에만 사용할 수 있으며, 임베드된 이미지도 복사된다는 점에 유의하십시오.<br/>            임베드된 이미지를 공유하려면 [SmartObjectLayer.duplicate_layer()](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) 메서드를 사용하십시오. |
| normalize_angle() |  |
| normalize_angle(resize_proportionally, background_color) |  |
| [read_argb_32_scan_line(scan_line_index)](#read_argb_32_scan_line_scan_line_index_37) |    |
| [read_scan_line(scan_line_index)](#read_scan_line_scan_line_index_38) |    |
| [relink_to_file(linked_path)](#relink_to_file_linked_path_39) | 연결된 스마트 오브젝트를 새 파일에 다시 연결합니다.<br/>            이후에 UpdateModifiedContent 메서드를 호출할 필요가 없습니다. |
| replace_color(old_color, old_color_diff, new_color) |  |
| replace_color(old_color_argb, old_color_diff, new_color_argb) |  |
| [replace_contents(image)](#replace_contents_image_40) | 스마트 오브젝트 레이어에 임베드된 스마트 오브젝트 콘텐츠를 교체합니다. |
| [replace_contents(image, resolution)](#replace_contents_image_resolution_41) | 스마트 오브젝트 레이어에 임베드된 스마트 오브젝트 콘텐츠를 교체합니다. |
| [replace_contents(linked_path)](#replace_contents_linked_path_42) | 파일로 콘텐츠를 교체합니다.<br/>            이후에 UpdateModifiedContent 메서드를 호출할 필요가 없습니다. |
| [replace_contents(linked_path, resolution)](#replace_contents_linked_path_resolution_43) | 파일로 콘텐츠를 교체합니다.<br/>            이후에 UpdateModifiedContent 메서드를 호출할 필요가 없습니다. |
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
| [shallow_copy()](#shallow_copy__44) |    |
| [to_bitmap()](#to_bitmap__45) |    |
| update_modified_content() | 수정된 콘텐츠로 스마트 오브젝트 레이어 이미지 캐시를 업데이트합니다. |
| write_argb_32_scan_line(scan_line_index, argb_32_pixels) |  |
| write_scan_line(scan_line_index, pixels) |  |


### Constructor: SmartObjectLayer(stream) {#SmartObjectLayer_stream_1}


```
 SmartObjectLayer(stream) 
```

새로운 [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) 클래스 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 스트림 | _io.BufferedRandom | 항목들의 스트림 |

### Method: can_load(file_path)  [static] {#can_load_file_path_1}


```
 can_load(file_path) 
```

  

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| file_path | 문자열 |  |

**Returns**

| 유형 | 설명 |
| :- | :- |
| bool |  |


### Method: can_load(file_path, load_options)  [static] {#can_load_file_path_load_options_2}


```
 can_load(file_path, load_options) 
```

  

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| file_path | 문자열 |  |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) |  |

**Returns**

| 유형 | 설명 |
| :- | :- |
| bool |  |


### Method: can_load(stream)  [static] {#can_load_stream_3}


```
 can_load(stream) 
```

  

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 스트림 | _io.BufferedRandom |  |

**Returns**

| 유형 | 설명 |
| :- | :- |
| bool |  |


### Method: can_load(stream, load_options)  [static] {#can_load_stream_load_options_4}


```
 can_load(stream, load_options) 
```

  

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 스트림 | _io.BufferedRandom |  |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) |  |

**Returns**

| 유형 | 설명 |
| :- | :- |
| bool |  |


### Method: can_save(options) {#can_save_options_5}


```
 can_save(options) 
```

  

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) |  |

**Returns**

| 유형 | 설명 |
| :- | :- |
| bool |  |


### Method: convert_to_linked(linked_path) {#convert_to_linked_linked_path_6}


```
 convert_to_linked(linked_path) 
```

이 포함된 스마트 객체를 연결된 스마트 객체로 변환합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| linked_path | 문자열 | 연결된 경로. |

### Method: create(image_options, width, height)  [static] {#create_image_options_width_height_7}


```
 create(image_options, width, height) 
```

  

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) |  |
| width | int |  |
| 높이 | int |  |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) |  |


### Method: duplicate_layer() {#duplicate_layer__8}


```
 duplicate_layer() 
```

이 레이어를 복사하여 새로운 스마트 객체 레이어를 생성합니다.<br/>            포함된 스마트 객체의 경우 포함된 이미지가 공유된다는 점에 유의하십시오.<br/>            포함된 이미지를 복사하려면 [SmartObjectLayer.new_smart_object_via_copy()](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) 메서드를 사용하십시오.

**Returns**

| 유형 | 설명 |
| :- | :- |
| [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) | 복제된 [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) 인스턴스. |


### Method: export_contents(file_path) {#export_contents_file_path_9}


```
 export_contents(file_path) 
```

임베드되거나 연결된 콘텐츠를 파일로 내보냅니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| file_path | 문자열 | 내보내기 파일 경로. |

### Method: get_argb_32_pixel(x, y) {#get_argb_32_pixel_x_y_10}


```
 get_argb_32_pixel(x, y) 
```

  

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| x | int |  |
| y | int |  |

**Returns**

| 유형 | 설명 |
| :- | :- |
| int |  |


### Method: get_default_argb_32_pixels(rectangle) {#get_default_argb_32_pixels_rectangle_11}


```
 get_default_argb_32_pixels(rectangle) 
```

  

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |

**Returns**

| 유형 | 설명 |
| :- | :- |
| int |  |


### Method: get_default_options(args) {#get_default_options_args_12}


```
 get_default_options(args) 
```

  

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| args | object |  |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) |  |


### Method: get_default_raw_data(rectangle, raw_data_settings) {#get_default_raw_data_rectangle_raw_data_settings_13}


```
 get_default_raw_data(rectangle, raw_data_settings) 
```

  

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) |  |

**Returns**

| 유형 | 설명 |
| :- | :- |
| byte |  |


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_14}


```
 get_file_format(file_path) 
```

  

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| file_path | 문자열 |  |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [FileFormat](/psd/python-net/aspose.psd/fileformat) |  |


### Method: get_file_format(stream)  [static] {#get_file_format_stream_15}


```
 get_file_format(stream) 
```

  

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 스트림 | _io.BufferedRandom |  |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [FileFormat](/psd/python-net/aspose.psd/fileformat) |  |


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_16}


```
 get_fitting_rectangle(rectangle, pixels, width, height) 
```

  

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |
| pixels | int |  |
| width | int |  |
| 높이 | int |  |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_17}


```
 get_fitting_rectangle(rectangle, width, height) 
```

  

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |
| width | int |  |
| 높이 | int |  |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |


### Method: get_modify_date(use_default) {#get_modify_date_use_default_18}


```
 get_modify_date(use_default) 
```

  

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| use_default | bool |  |

**Returns**

| 유형 | 설명 |
| :- | :- |
| datetime |  |


### Method: get_original_options() {#get_original_options__19}


```
 get_original_options() 
```

  

**Returns**

| 유형 | 설명 |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) |  |


### Method: get_pixel(x, y) {#get_pixel_x_y_20}


```
 get_pixel(x, y) 
```

  

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| x | int |  |
| y | int |  |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) |  |


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_21}


```
 get_proportional_height(width, height, new_width) 
```

  

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| width | int |  |
| 높이 | int |  |
| new_width | int |  |

**Returns**

| 유형 | 설명 |
| :- | :- |
| int |  |


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_22}


```
 get_proportional_width(width, height, new_height) 
```

  

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| width | int |  |
| 높이 | int |  |
| new_height | int |  |

**Returns**

| 유형 | 설명 |
| :- | :- |
| int |  |


### Method: get_skew_angle() {#get_skew_angle__23}


```
 get_skew_angle() 
```

  

**Returns**

| 유형 | 설명 |
| :- | :- |
| float |  |


### Method: load(file_path)  [static] {#load_file_path_24}


```
 load(file_path) 
```

  

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| file_path | 문자열 |  |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) |  |


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_25}


```
 load(file_path, load_options) 
```

  

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| file_path | 문자열 |  |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) |  |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) |  |


### Method: load(stream)  [static] {#load_stream_26}


```
 load(stream) 
```

  

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 스트림 | _io.BufferedRandom |  |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) |  |


### Method: load(stream, load_options)  [static] {#load_stream_load_options_27}


```
 load(stream, load_options) 
```

  

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 스트림 | _io.BufferedRandom |  |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) |  |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) |  |


### Method: load_argb_32_pixels(rectangle) {#load_argb_32_pixels_rectangle_28}


```
 load_argb_32_pixels(rectangle) 
```

  

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |

**Returns**

| 유형 | 설명 |
| :- | :- |
| int |  |


### Method: load_argb_64_pixels(rectangle) {#load_argb_64_pixels_rectangle_29}


```
 load_argb_64_pixels(rectangle) 
```

  

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |

**Returns**

| 유형 | 설명 |
| :- | :- |
| long |  |


### Method: load_cmyk_32_pixels(rectangle) {#load_cmyk_32_pixels_rectangle_30}


```
 load_cmyk_32_pixels(rectangle) 
```

  

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |

**Returns**

| 유형 | 설명 |
| :- | :- |
| int |  |


### Method: load_cmyk_pixels(rectangle) {#load_cmyk_pixels_rectangle_31}


```
 load_cmyk_pixels(rectangle) 
```

  

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) |  |


### Method: load_contents(options) {#load_contents_options_32}


```
 load_contents(options) 
```

스마트 오브젝트 레이어의 임베드되거나 연결된 이미지 콘텐츠를 가져옵니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | 옵션. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | 로드된 [Image](/psd/python-net/aspose.psd/image/) 스마트 오브젝트 인스턴스. |


### Method: load_partial_argb_32_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_33}


```
 load_partial_argb_32_pixels(rectangle, partial_pixel_loader) 
```

32비트 ARGB 픽셀을 부분적으로(블록 단위로) 로드합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 픽셀을 로드할 사각형. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/psd/python-net/aspose.psd/ipartialargb32pixelloader) | 부분 픽셀 로더. |

### Method: load_pixels(rectangle) {#load_pixels_rectangle_34}


```
 load_pixels(rectangle) 
```

  

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) |  |


### Method: load_raw_data(rectangle, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_raw_data_settings_raw_data_loader_35}


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

### Method: new_smart_object_via_copy() {#new_smart_object_via_copy__36}


```
 new_smart_object_via_copy() 
```

이 레이어를 복사하여 새로운 스마트 오브젝트 레이어를 생성합니다.<br/>            Adobe™ Photoshop™의 `Layer -&gt; Smart Objects -&gt; New Smart Object via Copy` 기능을 재현합니다.<br/>            임베드된 스마트 오브젝트에만 사용할 수 있으며, 임베드된 이미지도 복사된다는 점에 유의하십시오.<br/>            임베드된 이미지를 공유하려면 [SmartObjectLayer.duplicate_layer()](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) 메서드를 사용하십시오.

**Returns**

| 유형 | 설명 |
| :- | :- |
| [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) | 복제된 [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) 인스턴스. |


### Method: read_argb_32_scan_line(scan_line_index) {#read_argb_32_scan_line_scan_line_index_37}


```
 read_argb_32_scan_line(scan_line_index) 
```

  

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| scan_line_index | int |  |

**Returns**

| 유형 | 설명 |
| :- | :- |
| int |  |


### Method: read_scan_line(scan_line_index) {#read_scan_line_scan_line_index_38}


```
 read_scan_line(scan_line_index) 
```

  

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| scan_line_index | int |  |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) |  |


### Method: relink_to_file(linked_path) {#relink_to_file_linked_path_39}


```
 relink_to_file(linked_path) 
```

연결된 스마트 오브젝트를 새 파일에 다시 연결합니다.<br/>            이후에 UpdateModifiedContent 메서드를 호출할 필요가 없습니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| linked_path | 문자열 | 연결된 경로. |

### Method: replace_contents(image) {#replace_contents_image_40}


```
 replace_contents(image) 
```

스마트 오브젝트 레이어에 임베드된 스마트 오브젝트 콘텐츠를 교체합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | 이미지입니다. |

### Method: replace_contents(image, resolution) {#replace_contents_image_resolution_41}


```
 replace_contents(image, resolution) 
```

스마트 오브젝트 레이어에 임베드된 스마트 오브젝트 콘텐츠를 교체합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | 이미지입니다. |
| resolution | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | 해상도 설정입니다. null인 경우 이미지 해상도가 사용됩니다. |

### Method: replace_contents(linked_path) {#replace_contents_linked_path_42}


```
 replace_contents(linked_path) 
```

파일로 콘텐츠를 교체합니다.<br/>            이후에 UpdateModifiedContent 메서드를 호출할 필요가 없습니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| linked_path | 문자열 | 연결된 경로. |

### Method: replace_contents(linked_path, resolution) {#replace_contents_linked_path_resolution_43}


```
 replace_contents(linked_path, resolution) 
```

파일로 콘텐츠를 교체합니다.<br/>            이후에 UpdateModifiedContent 메서드를 호출할 필요가 없습니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| linked_path | 문자열 | 연결된 경로. |
| resolution | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | 해상도 설정입니다. null인 경우 이미지 해상도가 사용됩니다. |

### Method: shallow_copy() {#shallow_copy__44}


```
 shallow_copy() 
```

  

**Returns**

| 유형 | 설명 |
| :- | :- |
| [Layer](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) |  |


### Method: to_bitmap() {#to_bitmap__45}


```
 to_bitmap() 
```

  

**Returns**

| 유형 | 설명 |
| :- | :- |
| aspose.pydrawing.Bitmap |  |


