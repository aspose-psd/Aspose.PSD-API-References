---
title: "ColorPaletteHelper 클래스"
type: docs
weight: 810
url: /ko/python-net/aspose.psd/colorpalettehelper/
---

**Summary:** Helper class for color palettes manipulation.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ColorPaletteHelper

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **설명** |
| :- | :- |
| [create_4_bit()](#create_4_bit__1) | 4비트 색상 팔레트를 생성합니다. |
| [create_4_bit_grayscale(min_is_white)](#create_4_bit_grayscale_min_is_white_2) | 4비트 그레이스케일 팔레트를 생성합니다. |
| [create_8_bit()](#create_8_bit__3) | 8비트 색상 팔레트를 생성합니다. |
| [create_8_bit_grayscale(min_is_white)](#create_8_bit_grayscale_min_is_white_4) | 8비트 그레이스케일 팔레트를 생성합니다. |
| [create_monochrome()](#create_monochrome__5) | 2가지 색상만 포함하는 단색 색상 팔레트를 생성합니다. |
| [get_close_image_palette(image, dest_bounds, entries_count)](#get_close_image_palette_image_dest_bounds_entries_count_6) | 이미지에 색상 팔레트가 없을 경우 래스터 이미지에서 색상 팔레트를 가져옵니다(이미지를 팔레트화). 팔레트가 존재하면 계산을 수행하는 대신 해당 팔레트를 사용합니다. |
| [get_close_image_palette(image, dest_bounds, entries_count, use_image_palette)](#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_7) | 이미지에 색상 팔레트가 없을 경우 래스터 이미지에서 색상 팔레트를 가져옵니다(이미지를 팔레트화). 팔레트가 존재하면 계산을 수행하는 대신 해당 팔레트를 사용합니다. |
| [get_close_image_palette(image, entries_count)](#get_close_image_palette_image_entries_count_8) | 이미지에 색상 팔레트가 없을 경우 래스터 이미지에서 색상 팔레트를 가져옵니다(이미지를 팔레트화). 팔레트가 존재하면 계산을 수행하는 대신 해당 팔레트를 사용합니다. |
| [get_downscale_palette(image)](#get_downscale_palette_image_9) | 초기 이미지 색상 값의 상위 비트로 구성된 256색 팔레트를 가져옵니다. |
| [get_uniform_color_palette(image)](#get_uniform_color_palette_image_10) | 균일한 256색 팔레트를 가져옵니다. |
| [has_transparent_colors(palette)](#has_transparent_colors_palette_11) | 지정된 팔레트에 투명 색상이 있는지 여부를 결정합니다. |


### Method: create_4_bit()  [static] {#create_4_bit__1}


```
 create_4_bit() 
```

4비트 색상 팔레트를 생성합니다.

**Returns**

| 유형 | 설명 |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | 4비트 색상 팔레트. |


### Method: create_4_bit_grayscale(min_is_white)  [static] {#create_4_bit_grayscale_min_is_white_2}


```
 create_4_bit_grayscale(min_is_white) 
```

4비트 그레이스케일 팔레트를 생성합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| min_is_white | bool | 설정이 <c>true</c>이면 팔레트가 흰색으로 시작하고, 그렇지 않으면 검은색으로 시작합니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | 4비트 그레이스케일 팔레트. |


### Method: create_8_bit()  [static] {#create_8_bit__3}


```
 create_8_bit() 
```

8비트 색상 팔레트를 생성합니다.

**Returns**

| 유형 | 설명 |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | 8비트 컬러 팔레트. |


### Method: create_8_bit_grayscale(min_is_white)  [static] {#create_8_bit_grayscale_min_is_white_4}


```
 create_8_bit_grayscale(min_is_white) 
```

8비트 그레이스케일 팔레트를 생성합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| min_is_white | bool | 설정이 <c>true</c>이면 팔레트가 흰색으로 시작하고, 그렇지 않으면 검은색으로 시작합니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | 8비트 그레이스케일 팔레트. |


### Method: create_monochrome()  [static] {#create_monochrome__5}


```
 create_monochrome() 
```

2가지 색상만 포함하는 단색 색상 팔레트를 생성합니다.

**Returns**

| 유형 | 설명 |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | 흑백 이미지용 컬러 팔레트. |


### Method: get_close_image_palette(image, dest_bounds, entries_count)  [static] {#get_close_image_palette_image_dest_bounds_entries_count_6}


```
 get_close_image_palette(image, dest_bounds, entries_count) 
```

이미지에 색상 팔레트가 없을 경우 래스터 이미지에서 색상 팔레트를 가져옵니다(이미지를 팔레트화). 팔레트가 존재하면 계산을 수행하는 대신 해당 팔레트를 사용합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | 래스터 이미지. |
| dest_bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 대상 이미지 경계. |
| entries_count | int | 원하는 항목 수. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | 이미지(<paramref name="image" />)에서 가장 빈번한 색상으로 시작하고 <paramref name="entriesCount" />개의 항목을 포함하는 컬러 팔레트. |


### Method: get_close_image_palette(image, dest_bounds, entries_count, use_image_palette)  [static] {#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_7}


```
 get_close_image_palette(image, dest_bounds, entries_count, use_image_palette) 
```

이미지에 색상 팔레트가 없을 경우 래스터 이미지에서 색상 팔레트를 가져옵니다(이미지를 팔레트화). 팔레트가 존재하면 계산을 수행하는 대신 해당 팔레트를 사용합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | 래스터 이미지. |
| dest_bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 대상 이미지 경계. |
| entries_count | int | 원하는 항목 수. |
| use_image_palette | bool | 설정하면 사용 가능한 경우 자체 이미지 팔레트를 사용합니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | 이미지(<paramref name="image" />)에서 가장 빈번한 색상으로 시작하고 <paramref name="entriesCount" />개의 항목을 포함하는 컬러 팔레트. |


### Method: get_close_image_palette(image, entries_count)  [static] {#get_close_image_palette_image_entries_count_8}


```
 get_close_image_palette(image, entries_count) 
```

이미지에 색상 팔레트가 없을 경우 래스터 이미지에서 색상 팔레트를 가져옵니다(이미지를 팔레트화). 팔레트가 존재하면 계산을 수행하는 대신 해당 팔레트를 사용합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | 래스터 이미지. |
| entries_count | int | 원하는 항목 수. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | 이미지(<paramref name="image" />)에서 가장 빈번한 색상으로 시작하고 <paramref name="entriesCount" />개의 항목을 포함하는 컬러 팔레트. |


### Method: get_downscale_palette(image)  [static] {#get_downscale_palette_image_9}


```
 get_downscale_palette(image) 
```

초기 이미지 색상 값의 상위 비트로 구성된 256색 팔레트를 가져옵니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | 이미지입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [ColorPalette](/psd/python-net/aspose.psd/colorpalette) | 다음 [ColorPalette](/psd/python-net/aspose.psd/colorpalette/). |


### Method: get_uniform_color_palette(image)  [static] {#get_uniform_color_palette_image_10}


```
 get_uniform_color_palette(image) 
```

균일한 256색 팔레트를 가져옵니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | 이미지입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [ColorPalette](/psd/python-net/aspose.psd/colorpalette) | 다음 [ColorPalette](/psd/python-net/aspose.psd/colorpalette/). |


### Method: has_transparent_colors(palette)  [static] {#has_transparent_colors_palette_11}


```
 has_transparent_colors(palette) 
```

지정된 팔레트에 투명 색상이 있는지 여부를 결정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | 팔레트. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| bool | <c>true</c> 지정된 팔레트에 투명 색상이 있는 경우; 그렇지 않으면 <c>false</c>. |


