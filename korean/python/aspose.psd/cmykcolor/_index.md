---
title: "CmykColor 클래스"
type: docs
weight: 630
url: /ko/python-net/aspose.psd/cmykcolor/
---

**Summary:** The CMYK color of pixel.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.CmykColor

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [CmykColor()](#CmykColor__1) | CmykColor 클래스의 새 인스턴스를 초기화합니다. |
## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| c | byte | r | 이 [Color](/psd/python-net/aspose.psd/color/) 구조의 시안 구성 요소 값을 가져옵니다. |
| empty [static] | [CmykColor](/psd/python-net/aspose.psd/cmykcolor) | r | 빈 값을 가져옵니다. |
| is_empty | bool | r | 이 [Color](/psd/python-net/aspose.psd/color/) 구조가 초기화되지 않았는지 여부를 나타내는 값을 가져옵니다. |
| k | byte | r | 이 [Color](/psd/python-net/aspose.psd/color/) 구조의 검정 구성 요소 값을 가져옵니다. |
| m | byte | r | 이 [Color](/psd/python-net/aspose.psd/color/) 구조의 마젠타 구성 요소 값을 가져옵니다. |
| y | byte | r | 이 [Color](/psd/python-net/aspose.psd/color/) 구조의 노란색 구성 요소 값을 가져옵니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [from_params(cyan, magenta, yellow, black)](#from_params_cyan_magenta_yellow_black_1) | 32비트 시안, 마젠타, 노랑 및 검정 값으로부터 [CmykColor](/psd/python-net/aspose.psd/cmykcolor/) 구조를 생성합니다.<br/>            이 메서드는 사용 중단되었습니다. 보다 효율적인 [CmykColorHelper.from_components(cyan, magenta, yellow, black)](/psd/python-net/aspose.psd/cmykcolorhelper/)을 사용하십시오. |
| [to_argb32(cmyk_pixels)](#to_argb32_cmyk_pixels_2) | 기본 프로파일을 사용한 icc 변환으로 CMYKColor를 32비트 ARGB Color로 변환합니다.<br/>            이 메서드는 사용 중단되었습니다. 보다 효율적인 [CmykColorHelper.to_argb32(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/)을 사용하십시오. |
| [to_cmyk(argb_pixel)](#to_cmyk_argb_pixel_3) | 32비트 ARGB 색상을 CMYKColor로 변환합니다.<br/>            이 메서드는 사용 중단되었습니다. 보다 효율적인 [CmykColorHelper.to_cmyk(argb_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/)을 사용하십시오. |
| [to_cmyk(argb_pixels)](#to_cmyk_argb_pixels_4) | 32비트 ARGB 색상을 CMYKColor로 변환합니다.<br/>            이 메서드는 사용 중단되었습니다. 보다 효율적인 [CmykColorHelper.to_cmyk(argb_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/)을 사용하십시오. |
| [to_color(cmyk_pixel)](#to_color_cmyk_pixel_5) | 기본 프로파일을 사용한 icc 변환으로 CMYKColor를 Color로 변환합니다.<br/>            이 메서드는 사용 중단되었습니다. 보다 효율적인 [CmykColorHelper.to_argb(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/)을 사용하십시오. |
| [to_color(cmyk_pixels)](#to_color_cmyk_pixels_6) | 기본 프로파일을 사용한 icc 변환으로 CMYKColor를 Color로 변환합니다.<br/>            이 메서드는 사용 중단되었습니다. 보다 효율적인 [CmykColorHelper.to_argb(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/)을 사용하십시오. |
| [to_color_icc(cmyk_pixel)](#to_color_icc_cmyk_pixel_7) | 기본 프로파일을 사용한 icc 변환으로 CMYKColor를 Color로 변환합니다.<br/>            이 메서드는 사용 중단되었습니다. 보다 효율적인 [CmykColorHelper.to_argb_icc(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/)을 사용하십시오. |
| [to_color_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)](#to_color_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_8) | icc 변환을 사용하여 CMYKColor를 Color로 변환합니다.<br/>            이 메서드는 사용 중단되었습니다. 보다 효율적인 Aspose.PSD.CmykColorHelper.ToArgbIcc(int[],_io.BufferedRandom,_io.BufferedRandom)를 사용하십시오. |
| [to_color_icc(cmyk_pixels)](#to_color_icc_cmyk_pixels_9) | 기본 프로파일을 사용한 icc 변환으로 CMYKColor를 Color로 변환합니다.<br/>            이 메서드는 사용 중단되었습니다. 보다 효율적인 [CmykColorHelper.to_argb_icc(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/)을 사용하십시오. |
| [to_color_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](#to_color_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_10) | icc 변환을 사용하여 CMYKColor를 Color로 변환합니다.<br/>            이 메서드는 사용 중단되었습니다. 보다 효율적인 Aspose.PSD.CmykColorHelper.ToArgbIcc(int[],_io.BufferedRandom,_io.BufferedRandom)를 사용하십시오. |
| [to_value()](#to_value__11) | to 값입니다. |


### Constructor: CmykColor() {#CmykColor__1}


```
 CmykColor() 
```

CmykColor 클래스의 새 인스턴스를 초기화합니다.

### Method: from_params(cyan, magenta, yellow, black)  [static] {#from_params_cyan_magenta_yellow_black_1}


```
 from_params(cyan, magenta, yellow, black) 
```

32비트 시안, 마젠타, 노랑 및 검정 값으로부터 [CmykColor](/psd/python-net/aspose.psd/cmykcolor/) 구조를 생성합니다.<br/>            이 메서드는 사용 중단되었습니다. 보다 효율적인 [CmykColorHelper.from_components(cyan, magenta, yellow, black)](/psd/python-net/aspose.psd/cmykcolorhelper/)을 사용하십시오.

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
| [CmykColor](/psd/python-net/aspose.psd/cmykcolor) | 다음 [CmykColor](/psd/python-net/aspose.psd/cmykcolor/)입니다. |


### Method: to_argb32(cmyk_pixels)  [static] {#to_argb32_cmyk_pixels_2}


```
 to_argb32(cmyk_pixels) 
```

기본 프로파일을 사용한 icc 변환으로 CMYKColor를 32비트 ARGB Color로 변환합니다.<br/>            이 메서드는 사용 중단되었습니다. 보다 효율적인 [CmykColorHelper.to_argb32(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/)을 사용하십시오.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | CMYK 형식의 CMYKColor 타입 픽셀입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| int | 32비트 ARGB 색상의 배열입니다. |


### Method: to_cmyk(argb_pixel)  [static] {#to_cmyk_argb_pixel_3}


```
 to_cmyk(argb_pixel) 
```

32비트 ARGB 색상을 CMYKColor로 변환합니다.<br/>            이 메서드는 사용 중단되었습니다. 보다 효율적인 [CmykColorHelper.to_cmyk(argb_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/)을 사용하십시오.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| argb_pixel | int |  |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [CmykColor](/psd/python-net/aspose.psd/cmykcolor) | 다음 <see cref=\"T:Aspose:PSD:CmykColor[]\" />. |


### Method: to_cmyk(argb_pixels)  [static] {#to_cmyk_argb_pixels_4}


```
 to_cmyk(argb_pixels) 
```

32비트 ARGB 색상을 CMYKColor로 변환합니다.<br/>            이 메서드는 사용 중단되었습니다. 보다 효율적인 [CmykColorHelper.to_cmyk(argb_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/)을 사용하십시오.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| argb_pixels | int | 32비트 ARGB 형식의 픽셀입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | 다음 <see cref=\"T:Aspose:PSD:CmykColor[]\" />. |


### Method: to_color(cmyk_pixel)  [static] {#to_color_cmyk_pixel_5}


```
 to_color(cmyk_pixel) 
```

기본 프로파일을 사용한 icc 변환으로 CMYKColor를 Color로 변환합니다.<br/>            이 메서드는 사용 중단되었습니다. 보다 효율적인 [CmykColorHelper.to_argb(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/)을 사용하십시오.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| cmyk_pixel | [CmykColor](/psd/python-net/aspose.psd/cmykcolor) |  |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | ARGB 색상의 배열입니다. |


### Method: to_color(cmyk_pixels)  [static] {#to_color_cmyk_pixels_6}


```
 to_color(cmyk_pixels) 
```

기본 프로파일을 사용한 icc 변환으로 CMYKColor를 Color로 변환합니다.<br/>            이 메서드는 사용 중단되었습니다. 보다 효율적인 [CmykColorHelper.to_argb(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/)을 사용하십시오.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | CMYK 형식의 CMYKColor 타입 픽셀입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | ARGB 색상의 배열입니다. |


### Method: to_color_icc(cmyk_pixel)  [static] {#to_color_icc_cmyk_pixel_7}


```
 to_color_icc(cmyk_pixel) 
```

기본 프로파일을 사용한 icc 변환으로 CMYKColor를 Color로 변환합니다.<br/>            이 메서드는 사용 중단되었습니다. 보다 효율적인 [CmykColorHelper.to_argb_icc(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/)을 사용하십시오.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| cmyk_pixel | [CmykColor](/psd/python-net/aspose.psd/cmykcolor) |  |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | 다음 [Color[]](/psd/python-net/aspose.psd/color/). |


### Method: to_color_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_color_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_8}


```
 to_color_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream) 
```

icc 변환을 사용하여 CMYKColor를 Color로 변환합니다.<br/>            이 메서드는 사용 중단되었습니다. 보다 효율적인 Aspose.PSD.CmykColorHelper.ToArgbIcc(int[],_io.BufferedRandom,_io.BufferedRandom)를 사용하십시오.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| cmyk_pixel | [CmykColor](/psd/python-net/aspose.psd/cmykcolor) |  |
| cmyk_icc_stream | _io.BufferedRandom | icc cmyk 프로파일을 포함하는 스트림입니다. |
| rgb_icc_stream | _io.BufferedRandom | icc rgb 프로파일을 포함하는 스트림입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | 다음 [Color[]](/psd/python-net/aspose.psd/color/). |


### Method: to_color_icc(cmyk_pixels)  [static] {#to_color_icc_cmyk_pixels_9}


```
 to_color_icc(cmyk_pixels) 
```

기본 프로파일을 사용한 icc 변환으로 CMYKColor를 Color로 변환합니다.<br/>            이 메서드는 사용 중단되었습니다. 보다 효율적인 [CmykColorHelper.to_argb_icc(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/)을 사용하십시오.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | CMYK 형식의 CMYKColor 타입 픽셀입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | 다음 [Color[]](/psd/python-net/aspose.psd/color/). |


### Method: to_color_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_color_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_10}


```
 to_color_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream) 
```

icc 변환을 사용하여 CMYKColor를 Color로 변환합니다.<br/>            이 메서드는 사용 중단되었습니다. 보다 효율적인 Aspose.PSD.CmykColorHelper.ToArgbIcc(int[],_io.BufferedRandom,_io.BufferedRandom)를 사용하십시오.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | CMYK 형식의 CMYKColor 타입 픽셀입니다. |
| cmyk_icc_stream | _io.BufferedRandom | icc cmyk 프로파일을 포함하는 스트림입니다. |
| rgb_icc_stream | _io.BufferedRandom | icc rgb 프로파일을 포함하는 스트림입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | 다음 [Color[]](/psd/python-net/aspose.psd/color/). |


### Method: to_value() {#to_value__11}


```
 to_value() 
```

to 값입니다.

**Returns**

| 유형 | 설명 |
| :- | :- |
| long | 정수입니다. |


