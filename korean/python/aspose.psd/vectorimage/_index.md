---
title: "VectorImage 클래스"
type: docs
weight: 4700
url: /ko/python-net/aspose.psd/vectorimage/
---

**Summary:** The vector image is the base class for all type of vector images.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.VectorImage

**Inheritance:** IObjectWithBounds, IObjectWithSizeF, Image

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| auto_adjust_palette | bool | r/w | 자동 팔레트 조정 여부를 나타내는 값을 가져오거나 설정합니다. |
| background_color | [Color](/psd/python-net/aspose.psd/color) | r/w | 배경 색상의 값을 가져오거나 설정합니다. |
| bits_per_pixel | int | r | 이미지의 픽셀당 비트 수를 가져옵니다. |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | 이미지 경계를 가져옵니다. |
| buffer_size_hint | int | r/w | 버퍼 크기 힌트를 가져오거나 설정합니다. 이 힌트는 모든 내부 버퍼에 허용되는 최대 크기로 정의됩니다. |
| container | [Image](/psd/python-net/aspose.psd/image) | r | 해당 [Image](/psd/python-net/aspose.psd/image/) 컨테이너를 가져옵니다. |
| data_stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | r | 객체의 데이터 스트림을 가져옵니다. |
| disposed | bool | r | 이 인스턴스가 해제되었는지 여부를 나타내는 값을 가져옵니다. |
| file_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | 파일 형식 값을 가져옵니다. |
| has_background_color | bool | r/w | 이미지에 배경색이 있는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| 높이 | int | r | 이미지 높이를 가져옵니다. |
| height_f | float | r | 객체 높이를 인치 단위로 가져옵니다. |
| interrupt_monitor | [InterruptMonitor](/psd/python-net/aspose.psd.multithreading/interruptmonitor/) | r/w | 인터럽트 모니터를 가져오거나 설정합니다. |
| is_cached | bool | r | 객체의 데이터가 현재 캐시되어 있어 데이터 읽기가 필요 없는지를 나타내는 값을 가져옵니다. |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | 색상 팔레트를 가져오거나 설정합니다. 픽셀이 직접 표현될 때는 색상 팔레트를 사용하지 않습니다. |
| size | [Size](/psd/python-net/aspose.psd/size) | r | 이미지 크기를 가져옵니다. |
| size_f | [SizeF](/psd/python-net/aspose.psd/sizef) | r | 객체 크기를 인치 단위로 가져옵니다. |
| use_palette | bool | r | 이미지 팔레트를 사용하는지 여부를 나타내는 값을 가져옵니다. |
| width | int | r | 이미지 너비를 가져옵니다. |
| width_f | float | r | 객체 너비를 인치 단위로 가져옵니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| cache_data() | 데이터를 캐시하고 기본 [DataStreamSupporter.data_stream_container](/psd/python-net/aspose.psd/datastreamsupporter/)에서 추가 데이터 로드가 수행되지 않도록 보장합니다. |
| [can_load(file_path)](#can_load_file_path_1) | 지정된 파일 경로에서 이미지를 로드할 수 있는지 확인합니다. |
| [can_load(file_path, load_options)](#can_load_file_path_load_options_2) | 지정된 파일 경로와 선택적으로 지정된 열기 옵션을 사용하여 이미지를 로드할 수 있는지 확인합니다. |
| [can_load(stream)](#can_load_stream_3) | 지정된 스트림에서 이미지를 로드할 수 있는지 확인합니다. |
| [can_load(stream, load_options)](#can_load_stream_load_options_4) | 지정된 스트림에서 이미지를 로드할 수 있는지 확인하고, 선택적으로 지정된 <paramref name="loadOptions" />를 사용할 수 있습니다. |
| [can_save(options)](#can_save_options_5) | 전달된 저장 옵션으로 나타낸 지정된 파일 형식에 이미지를 저장할 수 있는지 확인합니다. |
| [create(image_options, width, height)](#create_image_options_width_height_6) | 지정된 생성 옵션을 사용하여 새 이미지를 생성합니다. |
| [get_default_options(args)](#get_default_options_args_7) | 기본 옵션을 가져옵니다. |
| [get_file_format(file_path)](#get_file_format_file_path_8) | 파일 형식을 가져옵니다. |
| [get_file_format(stream)](#get_file_format_stream_9) | 파일 형식을 가져옵니다. |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_10) | 현재 이미지에 맞는 사각형을 가져옵니다. |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_11) | 현재 이미지에 맞는 사각형을 가져옵니다. |
| [get_original_options()](#get_original_options__12) | 원본 파일 설정을 기반으로 옵션을 가져옵니다.<br/>            이는 원본 이미지의 비트 깊이 및 기타 매개변수를 변경하지 않도록 유지하는 데 도움이 될 수 있습니다.<br/>            예를 들어, 1비트 픽셀의 흑백 PNG 이미지를 로드한 후<br/>            [DataStreamSupporter.save(file_path)](/psd/python-net/aspose.psd/datastreamsupporter/) 메서드를 사용하여 저장하면 8비트 픽셀의 PNG 이미지가 출력됩니다.<br/>            이를 방지하고 1비트 픽셀 PNG 이미지를 저장하려면 이 메서드를 사용하여 해당 저장 옵션을 가져오고 이를<br/>            [Image.save(file_path, options)](/psd/python-net/aspose.psd/image/) 메서드의 두 번째 매개변수로 전달하십시오. |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_13) | 비례 높이를 가져옵니다. |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_14) | 비례 너비를 가져옵니다. |
| [load(file_path)](#load_file_path_15) | 지정된 파일에서 새 이미지를 로드합니다. |
| [load(file_path, load_options)](#load_file_path_load_options_16) | 지정된 파일에서 새 이미지를 로드합니다. |
| [load(stream)](#load_stream_17) | 지정된 스트림에서 새 이미지를 로드합니다. |
| [load(stream, load_options)](#load_stream_load_options_18) | 지정된 스트림에서 새 이미지를 로드합니다. |
| [resize(new_width, new_height)](#resize_new_width_new_height_19) | 이미지를 리사이즈합니다. 기본값으로 [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/)이 사용됩니다. |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_20) | 이미지를 리사이즈합니다. |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_21) | 이미지를 리사이즈합니다. |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_22) | 높이를 비례적으로 리사이즈합니다. |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_23) | 높이를 비례적으로 리사이즈합니다. |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_24) | 높이를 비례적으로 리사이즈합니다. |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_25) | 너비를 비례적으로 리사이즈합니다. 기본값으로 [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/)이 사용됩니다. |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_26) | 너비를 비례적으로 리사이즈합니다. |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_27) | 너비를 비례적으로 리사이즈합니다. |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_28) | 이미지를 회전하거나 뒤집거나 회전 및 뒤집습니다. |
| save() | 이미지 데이터를 기본 스트림에 저장합니다. |
| [save(file_path)](#save_file_path_29) | 지정된 파일 위치에 객체의 데이터를 저장합니다. |
| [save(file_path, options)](#save_file_path_options_30) | 저장 옵션에 따라 지정된 파일 형식으로 지정된 파일 위치에 객체의 데이터를 저장합니다. |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_31) | 저장 옵션에 따라 지정된 파일 형식으로 지정된 파일 위치에 객체의 데이터를 저장합니다. |
| [save(file_path, over_write)](#save_file_path_over_write_32) | 지정된 파일 위치에 객체의 데이터를 저장합니다. |
| [save(stream)](#save_stream_33) | 지정된 스트림에 객체의 데이터를 저장합니다. |
| [save(stream, options_base)](#save_stream_options_base_34) | 저장 옵션에 따라 지정된 파일 형식으로 지정된 스트림에 이미지 데이터를 저장합니다. |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_35) | 저장 옵션에 따라 지정된 파일 형식으로 지정된 스트림에 이미지 데이터를 저장합니다. |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_36) | 이미지 팔레트를 설정합니다. |


### Method: can_load(file_path)  [static] {#can_load_file_path_1}


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


### Method: can_load(file_path, load_options)  [static] {#can_load_file_path_load_options_2}


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


### Method: can_load(stream)  [static] {#can_load_stream_3}


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


### Method: can_load(stream, load_options)  [static] {#can_load_stream_load_options_4}


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


### Method: can_save(options) {#can_save_options_5}


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


### Method: create(image_options, width, height)  [static] {#create_image_options_width_height_6}


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


### Method: get_default_options(args) {#get_default_options_args_7}


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


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_8}


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


### Method: get_file_format(stream)  [static] {#get_file_format_stream_9}


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


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_10}


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


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_11}


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


### Method: get_original_options() {#get_original_options__12}


```
 get_original_options() 
```

원본 파일 설정을 기반으로 옵션을 가져옵니다.<br/>            이는 원본 이미지의 비트 깊이 및 기타 매개변수를 변경하지 않도록 유지하는 데 도움이 될 수 있습니다.<br/>            예를 들어, 1비트 픽셀의 흑백 PNG 이미지를 로드한 후<br/>            [DataStreamSupporter.save(file_path)](/psd/python-net/aspose.psd/datastreamsupporter/) 메서드를 사용하여 저장하면 8비트 픽셀의 PNG 이미지가 출력됩니다.<br/>            이를 방지하고 1비트 픽셀 PNG 이미지를 저장하려면 이 메서드를 사용하여 해당 저장 옵션을 가져오고 이를<br/>            [Image.save(file_path, options)](/psd/python-net/aspose.psd/image/) 메서드의 두 번째 매개변수로 전달하십시오.

**Returns**

| 유형 | 설명 |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | 원본 파일 설정을 기반으로 하는 옵션입니다. |


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_13}


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


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_14}


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


### Method: load(file_path)  [static] {#load_file_path_15}


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


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_16}


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


### Method: load(stream)  [static] {#load_stream_17}


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


### Method: load(stream, load_options)  [static] {#load_stream_load_options_18}


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


### Method: resize(new_width, new_height) {#resize_new_width_new_height_19}


```
 resize(new_width, new_height) 
```

이미지를 리사이즈합니다. 기본값으로 [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/)이 사용됩니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| new_width | int | 새로운 너비입니다. |
| new_height | int | 새로운 높이입니다. |

### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_20}


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

### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_21}


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

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_22}


```
 resize_height_proportionally(new_height) 
```

높이를 비례적으로 리사이즈합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| new_height | int | 새로운 높이입니다. |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_23}


```
 resize_height_proportionally(new_height, resize_type) 
```

높이를 비례적으로 리사이즈합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| new_height | int | 새로운 높이입니다. |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | 크기 조정 유형. |

### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_24}


```
 resize_height_proportionally(new_height, settings) 
```

높이를 비례적으로 리사이즈합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| new_height | int | 새로운 높이입니다. |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | 이미지 크기 조정 설정. |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_25}


```
 resize_width_proportionally(new_width) 
```

너비를 비례적으로 리사이즈합니다. 기본값으로 [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/)이 사용됩니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| new_width | int | 새로운 너비입니다. |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_26}


```
 resize_width_proportionally(new_width, resize_type) 
```

너비를 비례적으로 리사이즈합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| new_width | int | 새로운 너비입니다. |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | 크기 조정 유형. |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_27}


```
 resize_width_proportionally(new_width, settings) 
```

너비를 비례적으로 리사이즈합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| new_width | int | 새로운 너비입니다. |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | 이미지 크기 조정 설정. |

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_28}


```
 rotate_flip(rotate_flip_type) 
```

이미지를 회전하거나 뒤집거나 회전 및 뒤집습니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/psd/python-net/aspose.psd/rotatefliptype) | 회전 뒤집기의 유형. |

### Method: save(file_path) {#save_file_path_29}


```
 save(file_path) 
```

지정된 파일 위치에 객체의 데이터를 저장합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| file_path | 문자열 | 객체 데이터를 저장할 파일 경로. |

### Method: save(file_path, options) {#save_file_path_options_30}


```
 save(file_path, options) 
```

저장 옵션에 따라 지정된 파일 형식으로 지정된 파일 위치에 객체의 데이터를 저장합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| file_path | 문자열 | 파일 경로. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | 옵션. |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_31}


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

### Method: save(file_path, over_write) {#save_file_path_over_write_32}


```
 save(file_path, over_write) 
```

지정된 파일 위치에 객체의 데이터를 저장합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| file_path | 문자열 | 객체 데이터를 저장할 파일 경로. |
| over_write | bool | 만약 <c>true</c> 로 설정하면 파일 내용을 덮어쓰고, 그렇지 않으면 추가됩니다. |

### Method: save(stream) {#save_stream_33}


```
 save(stream) 
```

지정된 스트림에 객체의 데이터를 저장합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 스트림 | _io.BufferedRandom | 객체 데이터를 저장할 스트림. |

### Method: save(stream, options_base) {#save_stream_options_base_34}


```
 save(stream, options_base) 
```

저장 옵션에 따라 지정된 파일 형식으로 지정된 스트림에 이미지 데이터를 저장합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 스트림 | _io.BufferedRandom | 이미지 데이터를 저장할 스트림. |
| options_base | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | 저장 옵션. |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_35}


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

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_36}


```
 set_palette(palette, update_colors) 
```

이미지 팔레트를 설정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | 설정할 팔레트. |
| update_colors | bool | 설정이 <c>true</c>이면 색상이 새 팔레트에 따라 업데이트됩니다; 그렇지 않으면 색인은 변경되지 않은 상태로 유지됩니다. 변경되지 않은 색인은 일부 색인에 해당하는 팔레트 항목이 없을 경우 이미지를 로드할 때 충돌할 수 있습니다. |

