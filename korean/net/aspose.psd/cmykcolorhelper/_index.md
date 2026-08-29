---
title: "클래스 CmykColorHelper"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.CmykColorHelper 클래스. 서명된 32비트 정수 값으로 표현된 CMYK 색상을 다루는 도우미 메서드입니다. CmykColor 구조체와 유사한 API를 제공합니다. CMYK 색상이 구조체의 내부 필드가 아니라 Int32로만 표현되기 때문에 더 가볍습니다. 가능한 경우 사용이 중단된 CmykColor 구조체 대신 이 클래스의 정적 메서드를 사용하는 것이 좋습니다."
type: docs
weight: 280
url: /ko/net/aspose.psd/cmykcolorhelper/
---
{{< psd/tize >}}
## CmykColorHelper class

서명된 32비트 정수 값으로 표현된 CMYK 색상을 다루는 도우미 메서드입니다. [`CmykColor`](../cmykcolor/) 구조체와 유사한 API를 제공합니다. CMYK 색상이 구조체의 내부 필드가 아니라 Int32로만 표현되기 때문에 더 가볍습니다. 가능한 경우 사용이 중단된 [`CmykColor`](../cmykcolor/) 구조체 대신 이 클래스의 정적 메서드를 사용하는 것이 좋습니다.

```csharp
public static class CmykColorHelper
```

## 메서드

| 이름 | 설명 |
| --- | --- |
| static [FromComponents](../../aspose.psd/cmykcolorhelper/fromcomponents/)(int, int, int, int) | 32비트 시안, 마젠타, 옐로우 및 블랙 값을 사용하여 CMYK를 생성합니다. |
| static [GetC](../../aspose.psd/cmykcolorhelper/getc/)(int) | 시안 구성 요소 값을 가져옵니다. |
| static [GetK](../../aspose.psd/cmykcolorhelper/getk/)(int) | 블랙 구성 요소 값을 가져옵니다. |
| static [GetM](../../aspose.psd/cmykcolorhelper/getm/)(int) | 마젠타 구성 요소 값을 가져옵니다. |
| static [GetY](../../aspose.psd/cmykcolorhelper/gety/)(int) | 옐로우 구성 요소 값을 가져옵니다. |
| static [ToArgb](../../aspose.psd/cmykcolorhelper/toargb/#toargb)(int) | CMYK 색상에서 ARGB 색상으로의 변환. |
| static [ToArgb](../../aspose.psd/cmykcolorhelper/toargb/#toargb_1)(int[]) | CMYK 색상에서 ARGB 색상으로의 변환. |
| static [ToArgb32](../../aspose.psd/cmykcolorhelper/toargb32/)(int[]) | CMYK 색상에서 ARGB 색상으로의 변환. |
| static [ToArgbIcc](../../aspose.psd/cmykcolorhelper/toargbicc/#toargbicc)(int) | 기본 프로파일을 사용한 Icc 변환으로 CMYK 색상에서 ARGB 색상으로 변환합니다. |
| static [ToArgbIcc](../../aspose.psd/cmykcolorhelper/toargbicc/#toargbicc_2)(int[]) | 기본 프로파일을 사용한 Icc 변환으로 CMYK 색상에서 ARGB 색상으로 변환합니다. |
| static [ToArgbIcc](../../aspose.psd/cmykcolorhelper/toargbicc/#toargbicc_1)(int, Stream, Stream) | 사용자 지정 프로파일을 사용한 Icc 변환으로 CMYK 색상에서 ARGB 색상으로 변환합니다. |
| static [ToArgbIcc](../../aspose.psd/cmykcolorhelper/toargbicc/#toargbicc_3)(int[], Stream, Stream) | 사용자 지정 프로파일을 사용한 Icc 변환으로 CMYK 색상에서 ARGB 색상으로 변환합니다. |
| static [ToCmyk](../../aspose.psd/cmykcolorhelper/tocmyk/#tocmyk)(Color) | ARGB 색상에서 CMYK 색상으로의 변환. |
| static [ToCmyk](../../aspose.psd/cmykcolorhelper/tocmyk/#tocmyk_2)(Color[]) | ARGB 색상에서 CMYK 색상으로 변환. |
| static [ToCmyk](../../aspose.psd/cmykcolorhelper/tocmyk/#tocmyk_1)(int) | ARGB 색상에서 CMYK 색상으로의 변환. |
| static [ToCmyk](../../aspose.psd/cmykcolorhelper/tocmyk/#tocmyk_3)(int[]) | ARGB 색상에서 CMYK 색상으로 변환. |
| static [ToCmykBytes](../../aspose.psd/cmykcolorhelper/tocmykbytes/)(int[], int, int) | RGB를 CMYK로 변환합니다. |
| static [ToCmykIcc](../../aspose.psd/cmykcolorhelper/tocmykicc/#tocmykicc)(Color) | 기본 프로파일을 사용한 Icc 변환으로 ARGB 색상에서 CMYK 색상으로 변환합니다. |
| static [ToCmykIcc](../../aspose.psd/cmykcolorhelper/tocmykicc/#tocmykicc_2)(Color[]) | 기본 프로파일을 사용한 Icc 변환으로 ARGB 색상에서 CMYK 색상으로 변환합니다. |
| static [ToCmykIcc](../../aspose.psd/cmykcolorhelper/tocmykicc/#tocmykicc_1)(Color, Stream, Stream) | 사용자 지정 프로파일을 사용한 Icc 변환으로 ARGB 색상에서 CMYK 색상으로 변환합니다. |
| static [ToCmykIcc](../../aspose.psd/cmykcolorhelper/tocmykicc/#tocmykicc_3)(Color[], Stream, Stream) | 사용자 정의 프로파일을 사용한 Icc 변환으로 ARGB 색상을 CMYK 색상으로 변환합니다. |
| static [ToCmykIccBytes](../../aspose.psd/cmykcolorhelper/tocmykiccbytes/)(int[], int, int, Stream, Stream) | 사용자 정의 ICC 프로파일을 사용하여 RGB를 CMYK로 변환합니다. |

### 또 보기

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


