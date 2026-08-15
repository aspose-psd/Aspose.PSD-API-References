---
title: "CmykColorHelper 클래스"
type: docs
weight: 640
url: /ko/python-net/aspose.psd/cmykcolorhelper/
---

**Summary:** Helper methods to work with CMYK color presented as a signed 32-bit integer value.<br/>            Provides the similar API as the [CmykColor](/psd/python-net/aspose.psd/cmykcolor/) struct.<br/>            It's more lightweight because CMYK color is presented just as Int32 rather than structure with internal fields.<br/>            Please prefer to use static methods of this class when possible instead of the deprecated<br/>            [CmykColor](/psd/python-net/aspose.psd/cmykcolor/) struct.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.CmykColorHelper

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **설명** |
| :- | :- |
| [from_components(cyan, magenta, yellow, black)](#from_components_cyan_magenta_yellow_black_1) | 32비트 시안, 마젠타, 옐로우 및 블랙 값을 사용하여 CMYK를 생성합니다. |
| [get_c(cmyk)](#get_c_cmyk_2) | 시안 구성 요소 값을 가져옵니다. |
| [get_k(cmyk)](#get_k_cmyk_3) | 블랙 구성 요소 값을 가져옵니다. |
| [get_m(cmyk)](#get_m_cmyk_4) | 마젠타 구성 요소 값을 가져옵니다. |
| [get_y(cmyk)](#get_y_cmyk_5) | 옐로우 구성 요소 값을 가져옵니다. |
| [to_argb(cmyk_pixel)](#to_argb_cmyk_pixel_6) | CMYK 색상에서 ARGB 색상으로의 변환. |
| [to_argb(cmyk_pixels)](#to_argb_cmyk_pixels_7) | CMYK 색상에서 ARGB 색상으로의 변환. |
| [to_argb32(cmyk_pixels)](#to_argb32_cmyk_pixels_8) | CMYK 색상에서 ARGB 색상으로의 변환. |
| [to_argb_icc(cmyk_pixel)](#to_argb_icc_cmyk_pixel_9) | 기본 프로파일을 사용한 Icc 변환을 통해 CMYK 색상에서 ARGB 색상으로 변환합니다. |
| [to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)](#to_argb_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_10) | 사용자 정의 프로파일을 사용한 Icc 변환을 통해 CMYK 색상에서 ARGB 색상으로의 변환입니다. |
| [to_argb_icc(cmyk_pixels)](#to_argb_icc_cmyk_pixels_11) | 기본 프로파일을 사용한 Icc 변환을 통해 CMYK 색상에서 ARGB 색상으로 변환합니다. |
| [to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](#to_argb_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_12) | 사용자 정의 프로파일을 사용한 Icc 변환을 통해 CMYK 색상에서 ARGB 색상으로의 변환입니다. |
| [to_cmyk(argb_pixel)](#to_cmyk_argb_pixel_13) | ARGB 색상에서 CMYK 색상으로의 변환입니다. |
| [to_cmyk(argb_pixels)](#to_cmyk_argb_pixels_14) | ARGB 색상에서 CMYK 색상으로의 변환입니다. |
| [to_cmyk(pixel)](#to_cmyk_pixel_15) | ARGB 색상에서 CMYK 색상으로의 변환입니다. |
| [to_cmyk(pixels)](#to_cmyk_pixels_16) | ARGB 색상에서 CMYK 색상으로의 변환입니다. |
| [to_cmyk_bytes(argb_pixels, start_index, length)](#to_cmyk_bytes_argb_pixels_start_index_length_17) | RGB를 CMYK로 변환합니다. |
| [to_cmyk_icc(pixel)](#to_cmyk_icc_pixel_18) | 기본 프로파일을 사용한 Icc 변환을 통해 ARGB 색상에서 CMYK 색상으로의 변환입니다. |
| [to_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_pixel_rgb_icc_stream_cmyk_icc_stream_19) | 사용자 정의 프로파일을 사용한 Icc 변환을 통해 ARGB 색상에서 CMYK 색상으로의 변환입니다. |
| [to_cmyk_icc(pixels)](#to_cmyk_icc_pixels_20) | 기본 프로파일을 사용한 Icc 변환을 통해 ARGB 색상에서 CMYK 색상으로의 변환입니다. |
| [to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_21) | 사용자 정의 프로파일을 사용한 Icc 변환을 통해 ARGB 색상에서 CMYK 색상으로의 변환입니다. |
| [to_cmyk_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_bytes_pixels_start_index_length_rgb_icc_stream_cmyk_icc_stream_22) | 사용자 정의 ICC 프로파일을 사용하여 RGB를 CMYK로 변환합니다. |


### Method: from_components(cyan, magenta, yellow, black)  [static] {#from_components_cyan_magenta_yellow_black_1}


```
 from_components(cyan, magenta, yellow, black) 
```

32비트 시안, 마젠타, 옐로우 및 블랙 값을 사용하여 CMYK를 생성합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 시안 | int | 시안 성분입니다. 유효값은 0부터 255까지입니다. |
| 마젠타 | int | 마젠타 성분입니다. 유효값은 0부터 255까지입니다. |
| 노랑 | int | 노랑 성분입니다. 유효값은 0부터 255까지입니다. |
| 검정 | int | 검정 성분입니다. 유효값은 0부터 255까지입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| int | 32비트 정수 값으로 표시된 CMYK 색상입니다. |


### Method: get_c(cmyk)  [static] {#get_c_cmyk_2}


```
 get_c(cmyk) 
```

시안 구성 요소 값을 가져옵니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| cmyk | int | 32비트 정수 값으로 표시된 CMYK 색상입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| int | 시안 성분 값입니다. |


### Method: get_k(cmyk)  [static] {#get_k_cmyk_3}


```
 get_k(cmyk) 
```

블랙 구성 요소 값을 가져옵니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| cmyk | int | 32비트 정수 값으로 표시된 CMYK 색상입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| int | 검정 구성 요소 값. |


### Method: get_m(cmyk)  [static] {#get_m_cmyk_4}


```
 get_m(cmyk) 
```

마젠타 구성 요소 값을 가져옵니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| cmyk | int | 32비트 정수 값으로 표시된 CMYK 색상입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| int | 마젠타 구성 요소 값. |


### Method: get_y(cmyk)  [static] {#get_y_cmyk_5}


```
 get_y(cmyk) 
```

옐로우 구성 요소 값을 가져옵니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| cmyk | int | 32비트 정수 값으로 표시된 CMYK 색상입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| int | 노랑 구성 요소 값. |


### Method: to_argb(cmyk_pixel)  [static] {#to_argb_cmyk_pixel_6}


```
 to_argb(cmyk_pixel) 
```

CMYK 색상에서 ARGB 색상으로의 변환.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| cmyk_pixel | int |  |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | ARGB 색상입니다. |


### Method: to_argb(cmyk_pixels)  [static] {#to_argb_cmyk_pixels_7}


```
 to_argb(cmyk_pixels) 
```

CMYK 색상에서 ARGB 색상으로의 변환.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| cmyk_pixels | int | 32비트 정수 값으로 표시된 CMYK 색상들입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | ARGB 색상입니다. |


### Method: to_argb32(cmyk_pixels)  [static] {#to_argb32_cmyk_pixels_8}


```
 to_argb32(cmyk_pixels) 
```

CMYK 색상에서 ARGB 색상으로의 변환.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| cmyk_pixels | int | 32비트 정수 값으로 표시된 CMYK 색상들입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| int | 32비트 정수 값으로 표시된 ARGB 색상들입니다. |


### Method: to_argb_icc(cmyk_pixel)  [static] {#to_argb_icc_cmyk_pixel_9}


```
 to_argb_icc(cmyk_pixel) 
```

기본 프로파일을 사용한 Icc 변환을 통해 CMYK 색상에서 ARGB 색상으로 변환합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| cmyk_pixel | int |  |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | ARGB 색상입니다. |


### Method: to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_argb_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_10}


```
 to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream) 
```

사용자 정의 프로파일을 사용한 Icc 변환을 통해 CMYK 색상에서 ARGB 색상으로의 변환입니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| cmyk_pixel | int |  |
| cmyk_icc_stream | _io.BufferedRandom | CMYK Icc 프로파일을 포함하는 스트림입니다. |
| rgb_icc_stream | _io.BufferedRandom | RGB Icc 프로파일을 포함하는 스트림입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | ARGB 색상입니다. |


### Method: to_argb_icc(cmyk_pixels)  [static] {#to_argb_icc_cmyk_pixels_11}


```
 to_argb_icc(cmyk_pixels) 
```

기본 프로파일을 사용한 Icc 변환을 통해 CMYK 색상에서 ARGB 색상으로 변환합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| cmyk_pixels | int | 32비트 정수 값으로 표시된 CMYK 픽셀들입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | ARGB 색상입니다. |


### Method: to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_argb_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_12}


```
 to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream) 
```

사용자 정의 프로파일을 사용한 Icc 변환을 통해 CMYK 색상에서 ARGB 색상으로의 변환입니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| cmyk_pixels | int | 32비트 정수 값으로 표시된 CMYK 색상들입니다. |
| cmyk_icc_stream | _io.BufferedRandom | CMYK Icc 프로파일을 포함하는 스트림입니다. |
| rgb_icc_stream | _io.BufferedRandom | RGB Icc 프로파일을 포함하는 스트림입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | ARGB 색상입니다. |


### Method: to_cmyk(argb_pixel)  [static] {#to_cmyk_argb_pixel_13}


```
 to_cmyk(argb_pixel) 
```

ARGB 색상에서 CMYK 색상으로의 변환입니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| argb_pixel | int |  |

**Returns**

| 유형 | 설명 |
| :- | :- |
| int | 32비트 정수 값으로 표시된 CMYK 색상들입니다. |


### Method: to_cmyk(argb_pixels)  [static] {#to_cmyk_argb_pixels_14}


```
 to_cmyk(argb_pixels) 
```

ARGB 색상에서 CMYK 색상으로의 변환입니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| argb_pixels | int | 32비트 정수 값으로 표시된 ARGB 색상들입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| int | 32비트 정수 값으로 표시된 CMYK 색상들입니다. |


### Method: to_cmyk(pixel)  [static] {#to_cmyk_pixel_15}


```
 to_cmyk(pixel) 
```

ARGB 색상에서 CMYK 색상으로의 변환입니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| pixel | [Color](/psd/python-net/aspose.psd/color) |  |

**Returns**

| 유형 | 설명 |
| :- | :- |
| int | 32비트 정수 값으로 표시된 CMYK 색상들입니다. |


### Method: to_cmyk(pixels)  [static] {#to_cmyk_pixels_16}


```
 to_cmyk(pixels) 
```

ARGB 색상에서 CMYK 색상으로의 변환입니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) |  |

**Returns**

| 유형 | 설명 |
| :- | :- |
| int | 32비트 정수 값으로 표시된 CMYK 색상들입니다. |


### Method: to_cmyk_bytes(argb_pixels, start_index, length)  [static] {#to_cmyk_bytes_argb_pixels_start_index_length_17}


```
 to_cmyk_bytes(argb_pixels, start_index, length) 
```

RGB를 CMYK로 변환합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| argb_pixels | int | 32비트 정수 값으로 표시된 RGB 색상입니다. |
| start_index | int | RGB 색상의 시작 인덱스입니다. |
| 길이 | int | 변환할 RGB 픽셀 수입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| byte | 바이트 배열로 표시된 CMYK 색상입니다. |


### Method: to_cmyk_icc(pixel)  [static] {#to_cmyk_icc_pixel_18}


```
 to_cmyk_icc(pixel) 
```

기본 프로파일을 사용한 Icc 변환을 통해 ARGB 색상에서 CMYK 색상으로의 변환입니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| pixel | [Color](/psd/python-net/aspose.psd/color) |  |

**Returns**

| 유형 | 설명 |
| :- | :- |
| int | 32비트 정수 값으로 표시된 CMYK 색상들입니다. |


### Method: to_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_pixel_rgb_icc_stream_cmyk_icc_stream_19}


```
 to_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream) 
```

사용자 정의 프로파일을 사용한 Icc 변환을 통해 ARGB 색상에서 CMYK 색상으로의 변환입니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| pixel | [Color](/psd/python-net/aspose.psd/color) |  |
| rgb_icc_stream | _io.BufferedRandom | RGB Icc 프로파일을 포함하는 스트림입니다. |
| cmyk_icc_stream | _io.BufferedRandom | CMYK Icc 프로파일을 포함하는 스트림입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| int | 32비트 정수 값으로 표시된 CMYK 색상들입니다. |


### Method: to_cmyk_icc(pixels)  [static] {#to_cmyk_icc_pixels_20}


```
 to_cmyk_icc(pixels) 
```

기본 프로파일을 사용한 Icc 변환을 통해 ARGB 색상에서 CMYK 색상으로의 변환입니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) | ARGB 색상입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| int | 32비트 정수 값으로 표시된 CMYK 색상들입니다. |


### Method: to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_21}


```
 to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream) 
```

사용자 정의 프로파일을 사용한 Icc 변환을 통해 ARGB 색상에서 CMYK 색상으로의 변환입니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) | ARGB 색상입니다. |
| rgb_icc_stream | _io.BufferedRandom | RGB Icc 프로파일을 포함하는 스트림입니다. |
| cmyk_icc_stream | _io.BufferedRandom | CMYK Icc 프로파일을 포함하는 스트림입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| int | 32비트 정수 값으로 표시된 CMYK 색상들입니다. |


### Method: to_cmyk_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_bytes_pixels_start_index_length_rgb_icc_stream_cmyk_icc_stream_22}


```
 to_cmyk_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream) 
```

사용자 정의 ICC 프로파일을 사용하여 RGB를 CMYK로 변환합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| pixels | int | 32비트 정수 값으로 표시된 RGB 색상입니다. |
| start_index | int | RGB 색상의 시작 인덱스입니다. |
| 길이 | int | 변환할 RGB 픽셀 수입니다. |
| rgb_icc_stream | _io.BufferedRandom | RGB 프로파일 스트림입니다. |
| cmyk_icc_stream | _io.BufferedRandom | CMYK 프로파일 스트림입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| byte | 바이트 배열로 표시된 CMYK 색상입니다. |


