---
title: "ColorantCmyk 클래스"
type: docs
weight: 20
url: /ko/python-net/aspose.psd.xmp.types.complex.colorant/colorantcmyk/
---

**Summary:** Represents CMYK Colorant.

**Module:** [aspose.psd.xmp.types.complex.colorant](/psd/python-net/aspose.psd.xmp.types.complex.colorant/)

**Full Name:** aspose.psd.xmp.types.complex.colorant.ColorantCmyk

**Inheritance:** IXmpType, ColorantBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [ColorantCmyk()](#ColorantCmyk__1) | [ColorantCmyk](/psd/python-net/aspose.psd.xmp.types.complex.colorant/colorantcmyk/) 클래스의 새 인스턴스를 초기화합니다. |
| [ColorantCmyk(black, cyan, magenta, yellow)](#ColorantCmyk_black_cyan_magenta_yellow_2) | [ColorantCmyk](/psd/python-net/aspose.psd.xmp.types.complex.colorant/colorantcmyk/) 클래스의 새 인스턴스를 초기화합니다. |
## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| COLOR_VALUE_MAX [static] | float | r | CMYK 색소에서 색상의 최대값. |
| COLOR_VALUE_MIN [static] | float | r | CMYK 색소에서 색상의 최소값. |
| 검정 | float | r/w | 검정 구성 요소 값을 가져오거나 설정합니다. |
| color_type | [ColorType](/psd/python-net/aspose.psd.xmp.types.complex.colorant/colortype) | r/w | 색상의 유형을 가져오거나 설정합니다. |
| 시안 | float | r/w | 시안 구성 요소 값을 가져오거나 설정합니다. |
| 마젠타 | float | r/w | 마젠타 구성 요소 값을 가져오거나 설정합니다. |
| mode | [ColorMode](/psd/python-net/aspose.psd.xmp.types.complex.colorant/colormode) | r | 가져옵니다 [ColorMode](/psd/python-net/aspose.psd.xmp.types.complex.colorant/colormode/). |
| namespace_uri | 문자열 | r | 기본 네임스페이스 URI를 가져옵니다. |
| 접두사 | 문자열 | r | 접두사를 가져옵니다. |
| swatch_name | 문자열 | r/w | 스와치 이름을 가져오거나 설정합니다. |
| 노랑 | float | r/w | 노랑 구성 요소 값을 가져오거나 설정합니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [get_xmp_representation()](#get_xmp_representation__1) | XMP 형식의 문자열 포함 값을 가져옵니다. |


### Constructor: ColorantCmyk() {#ColorantCmyk__1}


```
 ColorantCmyk() 
```

[ColorantCmyk](/psd/python-net/aspose.psd.xmp.types.complex.colorant/colorantcmyk/) 클래스의 새 인스턴스를 초기화합니다.

### Constructor: ColorantCmyk(black, cyan, magenta, yellow) {#ColorantCmyk_black_cyan_magenta_yellow_2}


```
 ColorantCmyk(black, cyan, magenta, yellow) 
```

[ColorantCmyk](/psd/python-net/aspose.psd.xmp.types.complex.colorant/colorantcmyk/) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 검정 | float | 검정 구성 요소 값. |
| 시안 | float | 시안 색상 구성 요소 값. |
| 마젠타 | float | 마젠타 구성 요소 값. |
| 노랑 | float | 노랑 구성 요소 값. |

### Method: get_xmp_representation() {#get_xmp_representation__1}


```
 get_xmp_representation() 
```

XMP 형식의 문자열 포함 값을 가져옵니다.

**Returns**

| 유형 | 설명 |
| :- | :- |
| 문자열 | XMP 형식의 문자열 포함 값을 반환합니다. |


