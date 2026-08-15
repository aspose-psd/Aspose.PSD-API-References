---
title: "PixelDataFormat 클래스"
type: docs
weight: 3450
url: /ko/python-net/aspose.psd/pixeldataformat/
---

**Summary:** The pixel data format. This is an immutable object.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.PixelDataFormat

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| bits_per_pixel | int | r | 픽셀당 비트를 가져옵니다. |
| 캡션 | 문자열 | r | 픽셀 데이터 형식 캡션을 가져옵니다. |
| channel_bits | int | r | 각 채널에 대한 비트 수를 가져옵니다. |
| channels_count | int | r | 채널 수를 가져옵니다. |
| cmyk [static] | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | 0-255 구간의 그레이스케일 강도를 나타내는 8비트가 할당된 32비트당 픽셀에 대해 정의된 [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat/)을 가져옵니다. |
| cmyka [static] | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | acmyk를 가져옵니다. |
| grayscale [static] | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | 0-255 구간의 그레이스케일 강도를 나타내는 8비트가 할당된 8비트당 픽셀에 대해 정의된 [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat/)을 가져옵니다. |
| grayscale_alpha [static] | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | 0-255 구간의 그레이스케일 강도를 나타내는 8비트와 추가 8비트 알파 구성 요소가 포함된 16비트당 픽셀에 대해 정의된 [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat/)을 가져옵니다. |
| pixel_format | [PixelFormat](/psd/python-net/aspose.psd/pixelformat) | r | 픽셀 형식을 가져옵니다. |
| rgb_16_bpp_555 [static] | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | 빨강, 초록, 파랑 각각에 5비트가 할당되고 알파가 정의되지 않은 16비트당 픽셀에 대해 정의된 [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat/)을 가져옵니다. |
| rgb_16_bpp_565 [static] | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | 빨강에 5비트, 초록에 6비트, 파랑에 5비트를 할당하고 알파가 정의되지 않은 16비트당 픽셀에 대해 정의된 [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat/)을 가져옵니다. |
| rgb_24_bpp [static] | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | 알파, 빨강, 초록, 파랑 각각에 8비트가 할당되고 알파가 정의되지 않은 24비트당 픽셀에 대해 정의된 [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat/)을 가져옵니다. |
| rgb_24_bpp_png [static] | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | 알파, 빨강, 초록, 파랑 각각에 8비트가 할당되고 알파가 정의되지 않은 24비트당 픽셀에 대해 정의된 [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat/)을 가져옵니다. |
| rgb_32_bpp [static] | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | 알파, 빨강, 초록, 파랑 각각에 8비트가 할당된 32비트당 픽셀에 대해 정의된 [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat/)을 가져옵니다. |
| rgb_indexed_1_bpp [static] | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | 색상당 1비트 인덱싱된 [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat/)을 가져옵니다.<br/>            인덱싱된 픽셀 데이터 저장소는 색상 팔레트가 사용되는 모든 곳에서 데이터 저장 및 검색을 가능하게 하기 위해 설계되었습니다.<br/>            변환이 필요할 수 있으므로 주의해서 사용하십시오(한 팔레트에서 다른 팔레트로 또는 RGBA에서 인덱싱된 색상 모델로 변환). |
| rgb_indexed_2_bpp [static] | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | 인덱스된 색상당 2비트에 대해 정의된 [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat/)을 가져옵니다.<br/>            인덱스된 픽셀 데이터 저장소는 색상 팔레트가 사용되는 모든 곳에서 데이터 저장 및 검색을 가능하게 하기 위해 설계되었습니다.<br/>            변환이 필요할 수 있으므로 주의해서 사용하십시오. 변환은 한 팔레트에서 다른 팔레트로 또는 RGBA에서 인덱스 색상 모델로 이루어질 수 있습니다. |
| rgb_indexed_4_bpp [static] | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | 인덱스된 색상당 4비트에 대해 정의된 [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat/)을 가져옵니다.<br/>            인덱스된 픽셀 데이터 저장소는 색상 팔레트가 사용되는 모든 곳에서 데이터 저장 및 검색을 가능하게 하기 위해 설계되었습니다.<br/>            변환이 필요할 수 있으므로 주의해서 사용하십시오. 변환은 한 팔레트에서 다른 팔레트로 또는 RGBA에서 인덱스 색상 모델로 이루어질 수 있습니다. |
| rgb_indexed_8_bpp [static] | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | 인덱스된 색상당 8비트에 대해 정의된 [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat/)을 가져옵니다.<br/>            인덱스된 픽셀 데이터 저장소는 색상 팔레트가 사용되는 모든 곳에서 데이터 저장 및 검색을 가능하게 하기 위해 설계되었습니다.<br/>            변환이 필요할 수 있으므로 주의해서 사용하십시오. 변환은 한 팔레트에서 다른 팔레트로 또는 RGBA에서 인덱스 색상 모델로 이루어질 수 있습니다. |
| rgba_32_bpp [static] | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | 알파, 빨강, 초록, 파랑 각각에 8비트가 할당된 32비트당 픽셀에 대해 정의된 [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat/)을 가져옵니다. |
| rgba_64_bpp [static] | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | 알파, 레드, 그린, 블루 각각에 16비트를 사용하여 픽셀당 64비트에 대해 정의된 [PixelDataFormat]을 가져옵니다. |
| y_cb_cr [static] | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | 루마, 청차, 적차 각각에 8비트를 사용하여 픽셀당 24비트에 대해 정의된 [PixelDataFormat]을 가져옵니다. |
| ycck [static] | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | 루마, 청차, 적차 및 블랙 색차 성분 각각에 8비트를 사용하여 픽셀당 32비트에 대해 정의된 [PixelDataFormat]을 가져옵니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [get_bgr(bits_per_sample)](#get_bgr_bits_per_sample_1) | 샘플당 지정된 비트 수를 가진 BGRA 색상을 가져옵니다. |
| [get_bgra(bits_per_sample)](#get_bgra_bits_per_sample_2) | 샘플당 지정된 비트 수를 가진 BGRA 색상을 가져옵니다. |
| [get_cie_lab(bits_per_l, bits_per_a, bits_per_b)](#get_cie_lab_bits_per_l_bits_per_a_bits_per_b_3) | 샘플당 지정된 비트 수를 가진 CIE Lab 색상을 가져옵니다. |
| [get_cmyk(bits_per_cyan_channel, bits_per_magenta_channel, bits_per_yellow_channel, bits_per_key_channel)](#get_cmyk_bits_per_cyan_channel_bits_per_magenta_channel_bits_per_yellow_channel_bits_per_key_channel_4) | 샘플당 지정된 비트 수를 가진 CMYK 색상을 가져옵니다. |
| [get_cmyk(bits_per_sample)](#get_cmyk_bits_per_sample_5) | 샘플당 지정된 비트 수를 가진 CMYK 색상을 가져옵니다. |
| [get_cmyka(bits_per_cyan_channel, bits_per_magenta_channel, bits_per_yellow_channel, bits_per_key_channel, bits_per_alpha_channel)](#get_cmyka_bits_per_cyan_channel_bits_per_magenta_channel_bits_per_yellow_channel_bits_per_key_channel_bits_per_alpha_channel_6) | 샘플당 지정된 비트 수를 가진 CMYKA 색상을 가져옵니다. |
| [get_grayscale(bits_per_sample)](#get_grayscale_bits_per_sample_7) | 샘플당 지정된 비트 수를 가진 그레이스케일 색상을 가져옵니다. |
| [get_grayscale_alpha(bits_per_sample)](#get_grayscale_alpha_bits_per_sample_8) | 샘플당 지정된 비트 수를 가진 GrayscaleAlpha 색상을 가져옵니다. |
| [get_grayscale_alpha(bits_per_sample, alpha_channel_bits)](#get_grayscale_alpha_bits_per_sample_alpha_channel_bits_9) | 샘플당 지정된 비트 수를 가진 GrayscaleAlpha 색상을 가져옵니다. |
| [get_rgb(bits_per_red_channel, bits_per_green_channel, bits_per_blue_channel)](#get_rgb_bits_per_red_channel_bits_per_green_channel_bits_per_blue_channel_10) | 샘플당 지정된 비트 수를 가진 RGB 색상을 가져옵니다. |
| [get_rgb(bits_per_sample)](#get_rgb_bits_per_sample_11) | 샘플당 지정된 비트 수를 가진 RGB 색상을 가져옵니다. |
| [get_rgb_indexed(bits_per_sample)](#get_rgb_indexed_bits_per_sample_12) | 샘플당 지정된 비트 수를 가진 BGRA 인덱스 색상을 가져옵니다. |
| [get_rgba(bits_per_red_channel, bits_per_green_channel, bits_per_blue_channel, bits_per_alpha_channel)](#get_rgba_bits_per_red_channel_bits_per_green_channel_bits_per_blue_channel_bits_per_alpha_channel_13) | 샘플당 지정된 비트 수를 가진 RGBA 색상을 가져옵니다. |
| [get_rgba(bits_per_sample)](#get_rgba_bits_per_sample_14) | 샘플당 지정된 비트 수를 가진 RGBA 색상을 가져옵니다. |
| [get_y_cb_cr(bits_per_sample)](#get_y_cb_cr_bits_per_sample_15) | 샘플당 지정된 비트 수를 가진 YCbCr 색상을 가져옵니다. |
| [get_y_cb_cr(bits_per_y, bits_per_cb, bits_per_cr)](#get_y_cb_cr_bits_per_y_bits_per_cb_bits_per_cr_16) | 샘플당 지정된 비트 수를 가진 YCbCr 색상을 가져옵니다. |
| [get_ycck(bits_per_sample)](#get_ycck_bits_per_sample_17) | 샘플당 지정된 비트 수를 가진 YCCK 색상을 가져옵니다. |


### Method: get_bgr(bits_per_sample)  [static] {#get_bgr_bits_per_sample_1}


```
 get_bgr(bits_per_sample) 
```

샘플당 지정된 비트 수를 가진 BGRA 색상을 가져옵니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| bits_per_sample | int | 샘플당 비트 수. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | BGRA 색상. |


### Method: get_bgra(bits_per_sample)  [static] {#get_bgra_bits_per_sample_2}


```
 get_bgra(bits_per_sample) 
```

샘플당 지정된 비트 수를 가진 BGRA 색상을 가져옵니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| bits_per_sample | int | 샘플당 비트 수. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | BGRA 색상. |


### Method: get_cie_lab(bits_per_l, bits_per_a, bits_per_b)  [static] {#get_cie_lab_bits_per_l_bits_per_a_bits_per_b_3}


```
 get_cie_lab(bits_per_l, bits_per_a, bits_per_b) 
```

샘플당 지정된 비트 수를 가진 CIE Lab 색상을 가져옵니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| bits_per_l | int | L 채널당 비트 수. |
| bits_per_a | int | A 채널당 비트 수. |
| bits_per_b | int | B 채널당 비트 수. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | CIE Lab 색상. |


### Method: get_cmyk(bits_per_cyan_channel, bits_per_magenta_channel, bits_per_yellow_channel, bits_per_key_channel)  [static] {#get_cmyk_bits_per_cyan_channel_bits_per_magenta_channel_bits_per_yellow_channel_bits_per_key_channel_4}


```
 get_cmyk(bits_per_cyan_channel, bits_per_magenta_channel, bits_per_yellow_channel, bits_per_key_channel) 
```

샘플당 지정된 비트 수를 가진 CMYK 색상을 가져옵니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| bits_per_cyan_channel | int | Cyan 채널당 비트 수. |
| bits_per_magenta_channel | int | Magenta 채널당 비트 수. |
| bits_per_yellow_channel | int | Yellow 채널당 비트 수. |
| bits_per_key_channel | int | Key 채널당 비트 수. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | CMYK 색상. |


### Method: get_cmyk(bits_per_sample)  [static] {#get_cmyk_bits_per_sample_5}


```
 get_cmyk(bits_per_sample) 
```

샘플당 지정된 비트 수를 가진 CMYK 색상을 가져옵니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| bits_per_sample | int | 샘플당 비트 수. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | CMYK 색상. |


### Method: get_cmyka(bits_per_cyan_channel, bits_per_magenta_channel, bits_per_yellow_channel, bits_per_key_channel, bits_per_alpha_channel)  [static] {#get_cmyka_bits_per_cyan_channel_bits_per_magenta_channel_bits_per_yellow_channel_bits_per_key_channel_bits_per_alpha_channel_6}


```
 get_cmyka(bits_per_cyan_channel, bits_per_magenta_channel, bits_per_yellow_channel, bits_per_key_channel, bits_per_alpha_channel) 
```

샘플당 지정된 비트 수를 가진 CMYKA 색상을 가져옵니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| bits_per_cyan_channel | int | Cyan 채널당 비트 수. |
| bits_per_magenta_channel | int | Magenta 채널당 비트 수. |
| bits_per_yellow_channel | int | Yellow 채널당 비트 수. |
| bits_per_key_channel | int | Key 채널당 비트 수. |
| bits_per_alpha_channel | int | Alpha 채널당 비트 수. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | CMYK 색상. |


### Method: get_grayscale(bits_per_sample)  [static] {#get_grayscale_bits_per_sample_7}


```
 get_grayscale(bits_per_sample) 
```

샘플당 지정된 비트 수를 가진 그레이스케일 색상을 가져옵니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| bits_per_sample | int | 샘플당 비트 수. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | Grayscale 색상. |


### Method: get_grayscale_alpha(bits_per_sample)  [static] {#get_grayscale_alpha_bits_per_sample_8}


```
 get_grayscale_alpha(bits_per_sample) 
```

샘플당 지정된 비트 수를 가진 GrayscaleAlpha 색상을 가져옵니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| bits_per_sample | int | 샘플당 비트 수. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | GrayscaleAlpha 색상. |


### Method: get_grayscale_alpha(bits_per_sample, alpha_channel_bits)  [static] {#get_grayscale_alpha_bits_per_sample_alpha_channel_bits_9}


```
 get_grayscale_alpha(bits_per_sample, alpha_channel_bits) 
```

샘플당 지정된 비트 수를 가진 GrayscaleAlpha 색상을 가져옵니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| bits_per_sample | int | 샘플당 비트 수. |
| alpha_channel_bits | int | alpha 채널의 샘플당 비트 수. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | GrayscaleAlpha 색상. |


### Method: get_rgb(bits_per_red_channel, bits_per_green_channel, bits_per_blue_channel)  [static] {#get_rgb_bits_per_red_channel_bits_per_green_channel_bits_per_blue_channel_10}


```
 get_rgb(bits_per_red_channel, bits_per_green_channel, bits_per_blue_channel) 
```

샘플당 지정된 비트 수를 가진 RGB 색상을 가져옵니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| bits_per_red_channel | int | Red 채널당 비트 수. |
| bits_per_green_channel | int | Green 채널당 비트 수. |
| bits_per_blue_channel | int | Blue 채널당 비트 수. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | RGB 색상입니다. |


### Method: get_rgb(bits_per_sample)  [static] {#get_rgb_bits_per_sample_11}


```
 get_rgb(bits_per_sample) 
```

샘플당 지정된 비트 수를 가진 RGB 색상을 가져옵니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| bits_per_sample | int | 샘플당 비트 수. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | RGB 색상입니다. |


### Method: get_rgb_indexed(bits_per_sample)  [static] {#get_rgb_indexed_bits_per_sample_12}


```
 get_rgb_indexed(bits_per_sample) 
```

샘플당 지정된 비트 수를 가진 BGRA 인덱스 색상을 가져옵니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| bits_per_sample | int | 샘플당 비트 수. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | BGRA 색상. |


### Method: get_rgba(bits_per_red_channel, bits_per_green_channel, bits_per_blue_channel, bits_per_alpha_channel)  [static] {#get_rgba_bits_per_red_channel_bits_per_green_channel_bits_per_blue_channel_bits_per_alpha_channel_13}


```
 get_rgba(bits_per_red_channel, bits_per_green_channel, bits_per_blue_channel, bits_per_alpha_channel) 
```

샘플당 지정된 비트 수를 가진 RGBA 색상을 가져옵니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| bits_per_red_channel | int | Red 채널당 비트 수. |
| bits_per_green_channel | int | Green 채널당 비트 수. |
| bits_per_blue_channel | int | Blue 채널당 비트 수. |
| bits_per_alpha_channel | int | Alpha 채널당 비트 수. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | RGBA 색상. |


### Method: get_rgba(bits_per_sample)  [static] {#get_rgba_bits_per_sample_14}


```
 get_rgba(bits_per_sample) 
```

샘플당 지정된 비트 수를 가진 RGBA 색상을 가져옵니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| bits_per_sample | int | 샘플당 비트 수. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | RGBA 색상. |


### Method: get_y_cb_cr(bits_per_sample)  [static] {#get_y_cb_cr_bits_per_sample_15}


```
 get_y_cb_cr(bits_per_sample) 
```

샘플당 지정된 비트 수를 가진 YCbCr 색상을 가져옵니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| bits_per_sample | int | 샘플당 비트 수. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | YCbCr 색상. |


### Method: get_y_cb_cr(bits_per_y, bits_per_cb, bits_per_cr)  [static] {#get_y_cb_cr_bits_per_y_bits_per_cb_bits_per_cr_16}


```
 get_y_cb_cr(bits_per_y, bits_per_cb, bits_per_cr) 
```

샘플당 지정된 비트 수를 가진 YCbCr 색상을 가져옵니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| bits_per_y | int | Y 채널당 비트 수. |
| bits_per_cb | int | Cb 채널당 비트 수. |
| bits_per_cr | int | Cr 채널당 비트 수. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | YCbCr 색상. |


### Method: get_ycck(bits_per_sample)  [static] {#get_ycck_bits_per_sample_17}


```
 get_ycck(bits_per_sample) 
```

샘플당 지정된 비트 수를 가진 YCCK 색상을 가져옵니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| bits_per_sample | int | 샘플당 비트 수. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | YCCK 색상. |


