---
title: "RawColor 클래스"
type: docs
weight: 20
url: /ko/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/
---

**Summary:** Raw Color Class helps to store colors with any channels count, any color mode and any bit depth<br/>            Please note, some internal classes can have issues with converting RawColor to its' native format,<br/>            so if API provides for you CMYK color, it's more reliable to use the provided format.<br/>            Also, there are can be some cases when Raw Color can be converted

**Module:** [aspose.psd.fileformats.psd.core.rawcolor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/)

**Full Name:** aspose.psd.fileformats.psd.core.rawcolor.RawColor

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [RawColor(components)](#RawColor_components_1) | [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) 클래스의 새 인스턴스를 초기화합니다. |
| [RawColor(pixel_data_format, color_mode)](#RawColor_pixel_data_format_color_mode_2) | 미리 정의된 색상 모드를 사용하여 픽셀 데이터 형식에서 [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) 클래스의 새 인스턴스를 초기화합니다. |
## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| color_mode | short | r/w | 따라야 할 색상의 모드입니다. |
| components | [ColorComponent[]](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/colorcomponent) | r | 색상의 구성 요소를 가져옵니다. 각 구성 요소는 별도의 채널이며, 일반적이지 않은<br/>            색상 체계를 사용하는 경우 각 채널을 별도로 작업하는 것이 좋습니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [get_as_int()](#get_as_int__1) | 가능한 경우 색상을 int 형식으로 가져옵니다. |
| [get_as_long()](#get_as_long__2) | 가능한 경우 색상을 long 형식으로 가져옵니다. |
| [get_bit_depth()](#get_bit_depth__3) | Raw Color의 비트 깊이를 가져옵니다. <br/>            예를 들어 채널/구성 요소당 8비트인 ARGB 색상의 경우 32비트입니다.<br/>            채널당 16비트인 전체 ARGB 색상의 비트 깊이는 64비트입니다.<br/>            비트 깊이는 채널들의 비트 깊이 합계에서 누적됩니다. <br/>            서로 다른 채널이 서로 다른 비트 깊이를 가질 경우 가능합니다. |
| [get_color_mode_name()](#get_color_mode_name__4) | 색상 모드의 이름을 가져옵니다. 색상 모드 이름은 채널/구성 요소 이름에서 누적됩니다. |
| [set_as_int(value)](#set_as_int_value_5) | 가능한 경우 int 인수에서 모든 채널에 데이터를 설정합니다. |
| [set_as_long(value)](#set_as_long_value_6) | 가능한 경우 int 인수에서 모든 채널에 데이터를 설정합니다. |


### Constructor: RawColor(components) {#RawColor_components_1}


```
 RawColor(components) 
```

[RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| components | [ColorComponent[]](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/colorcomponent) | 사용자 정의 색상 구성 요소입니다. |

### Constructor: RawColor(pixel_data_format, color_mode) {#RawColor_pixel_data_format_color_mode_2}


```
 RawColor(pixel_data_format, color_mode) 
```

미리 정의된 색상 모드를 사용하여 픽셀 데이터 형식에서 [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| pixel_data_format | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | 픽셀 데이터 형식입니다. |
| color_mode | short | 따라야 할 색상의 모드입니다. |

### Method: get_as_int() {#get_as_int__1}


```
 get_as_int() 
```

가능한 경우 색상을 int 형식으로 가져옵니다.

**Returns**

| 유형 | 설명 |
| :- | :- |
| int | 채널 데이터가 Int에 저장됩니다. |


### Method: get_as_long() {#get_as_long__2}


```
 get_as_long() 
```

가능한 경우 색상을 long 형식으로 가져옵니다.

**Returns**

| 유형 | 설명 |
| :- | :- |
| long | 채널 데이터가 Int에 저장됩니다. |


### Method: get_bit_depth() {#get_bit_depth__3}


```
 get_bit_depth() 
```

Raw Color의 비트 깊이를 가져옵니다. <br/>            예를 들어 채널/구성 요소당 8비트인 ARGB 색상의 경우 32비트입니다.<br/>            채널당 16비트인 전체 ARGB 색상의 비트 깊이는 64비트입니다.<br/>            비트 깊이는 채널들의 비트 깊이 합계에서 누적됩니다. <br/>            서로 다른 채널이 서로 다른 비트 깊이를 가질 경우 가능합니다.

**Returns**

| 유형 | 설명 |
| :- | :- |
| int | 모든 채널 비트 깊이의 합계 |


### Method: get_color_mode_name() {#get_color_mode_name__4}


```
 get_color_mode_name() 
```

색상 모드의 이름을 가져옵니다. 색상 모드 이름은 채널/구성 요소 이름에서 누적됩니다.

**Returns**

| 유형 | 설명 |
| :- | :- |
| 문자열 | 색상 모드 이름이 포함된 문자열 |


### Method: set_as_int(value) {#set_as_int_value_5}


```
 set_as_int(value) 
```

가능한 경우 int 인수에서 모든 채널에 데이터를 설정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 값 | int | 구성 요소 데이터를 포함하는 int 값 |

### Method: set_as_long(value) {#set_as_long_value_6}


```
 set_as_long(value) 
```

가능한 경우 int 인수에서 모든 채널에 데이터를 설정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 값 | long | 구성 요소 데이터를 포함하는 int 값 |

