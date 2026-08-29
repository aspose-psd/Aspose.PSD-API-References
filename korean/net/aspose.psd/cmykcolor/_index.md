---
title: "구조체 CmykColor"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.CmykColor 구조체. 픽셀의 CMYK 색상"
type: docs
weight: 270
url: /ko/net/aspose.psd/cmykcolor/
---
{{< psd/tize >}}
## CmykColor structure

픽셀의 CMYK 색상입니다.

```csharp
public struct CmykColor
```

## 속성

| 이름 | 설명 |
| --- | --- |
| static [Empty](../../aspose.psd/cmykcolor/empty/) { get; } | 비어 있는 값을 가져옵니다. |
| [C](../../aspose.psd/cmykcolor/c/) { get; } | 이 [`Color`](../color/) 구조체의 시안 구성 요소 값을 가져옵니다. |
| [IsEmpty](../../aspose.psd/cmykcolor/isempty/) { get; } | 이 [`Color`](../color/) 구조체가 초기화되지 않았는지 여부를 나타내는 값을 가져옵니다. |
| [K](../../aspose.psd/cmykcolor/k/) { get; } | 이 [`Color`](../color/) 구조체의 검정 구성 요소 값을 가져옵니다. |
| [M](../../aspose.psd/cmykcolor/m/) { get; } | 이 [`Color`](../color/) 구조체의 마젠타 구성 요소 값을 가져옵니다. |
| [Y](../../aspose.psd/cmykcolor/y/) { get; } | 이 [`Color`](../color/) 구조체의 노란색 구성 요소 값을 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| static [FromParams](../../aspose.psd/cmykcolor/fromparams/)(int, int, int, int) | `CmykColor` 구조체를 32비트 시안, 마젠타, 옐로우 및 블랙 값으로 생성합니다. 이 메서드는 더 이상 사용되지 않습니다. 보다 효율적인 [`FromComponents`](../cmykcolorhelper/fromcomponents/)을 사용하십시오. |
| static [ToCmyk](../../aspose.psd/cmykcolor/tocmyk/#tocmyk)(int) | 32비트 ARGB에서 CMYKColor로의 변환입니다. 이 메서드는 더 이상 사용되지 않습니다. 보다 효율적인 [`ToCmyk`](../cmykcolorhelper/tocmyk/)을 사용하십시오. |
| override [Equals](../../aspose.psd/cmykcolor/equals/)(object) | 지정된 객체가 이 인스턴스와 같은지 여부를 결정합니다. |
| override [GetHashCode](../../aspose.psd/cmykcolor/gethashcode/)() | 해시 코드를 가져옵니다. |
| [ToValue](../../aspose.psd/cmykcolor/tovalue/)() | 값을 반환합니다. |
| static [ToArgb32](../../aspose.psd/cmykcolor/toargb32/)(CmykColor[]) | 기본 프로파일을 사용한 ICC 변환으로 CMYKColor에서 32비트 ARGB Color로의 변환입니다. 이 메서드는 더 이상 사용되지 않습니다. 보다 효율적인 [`ToArgb32`](../cmykcolorhelper/toargb32/)을 사용하십시오. |
| static [ToCmyk](../../aspose.psd/cmykcolor/tocmyk/#tocmyk_1)(int[]) | 32비트 ARGB 색상에서 CMYKColor로의 변환입니다. 이 메서드는 더 이상 사용되지 않습니다. 보다 효율적인 [`ToCmyk`](../cmykcolorhelper/tocmyk/)을 사용하십시오. |
| static [ToColor](../../aspose.psd/cmykcolor/tocolor/#tocolor)(CmykColor) | CMYKColor에서 Color로의 변환입니다. 이 메서드는 더 이상 사용되지 않습니다. 보다 효율적인 [`ToArgb`](../cmykcolorhelper/toargb/)을 사용하십시오. |
| static [ToColor](../../aspose.psd/cmykcolor/tocolor/#tocolor_1)(CmykColor[]) | 기본 프로파일을 사용한 ICC 변환으로 CMYKColor에서 Color로의 변환입니다. 이 메서드는 더 이상 사용되지 않습니다. 보다 효율적인 [`ToArgb`](../cmykcolorhelper/toargb/)을 사용하십시오. |
| static [ToColorIcc](../../aspose.psd/cmykcolor/tocoloricc/#tocoloricc)(CmykColor) | 기본 프로파일을 사용한 ICC 변환으로 CMYKColor에서 Color로의 변환입니다. 이 메서드는 더 이상 사용되지 않습니다. 보다 효율적인 [`ToArgbIcc`](../cmykcolorhelper/toargbicc/)을 사용하십시오. |
| static [ToColorIcc](../../aspose.psd/cmykcolor/tocoloricc/#tocoloricc_2)(CmykColor[]) | 기본 프로파일을 사용한 ICC 변환으로 CMYKColor에서 Color로의 변환입니다. 이 메서드는 더 이상 사용되지 않습니다. 보다 효율적인 [`ToArgbIcc`](../cmykcolorhelper/toargbicc/)을 사용하십시오. |
| static [ToColorIcc](../../aspose.psd/cmykcolor/tocoloricc/#tocoloricc_1)(CmykColor, Stream, Stream) | ICC 변환을 사용한 CMYKColor에서 Color로의 변환입니다. 이 메서드는 더 이상 사용되지 않습니다. 보다 효율적인 [`ToArgbIcc`](../cmykcolorhelper/toargbicc/)을 사용하십시오. |
| static [ToColorIcc](../../aspose.psd/cmykcolor/tocoloricc/#tocoloricc_3)(CmykColor[], Stream, Stream) | ICC 변환을 사용한 CMYKColor에서 Color로의 변환입니다. 이 메서드는 더 이상 사용되지 않습니다. 보다 효율적인 [`ToArgbIcc`](../cmykcolorhelper/toargbicc/)을 사용하십시오. |

### 또 보기

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


