---
title: "클래스 ColorPalette"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.ColorPalette 클래스. 색상 팔레트를 구성하는 색상의 배열을 정의합니다. 색상은 32비트 ARGB 색상입니다. 상속할 수 없습니다."
type: docs
weight: 370
url: /ko/net/aspose.psd/colorpalette/
---
{{< psd/tize >}}
## ColorPalette class

색상 팔레트를 구성하는 색상 배열을 정의합니다. 색상은 32비트 ARGB 색상입니다. 상속할 수 없습니다.

```csharp
public sealed class ColorPalette : IColorPalette
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [ColorPalette](colorpalette/#constructor)(Color[]) | 새로운 `ColorPalette` 클래스 인스턴스를 초기화하고 IsCompactPalette는 false입니다. |
| [ColorPalette](colorpalette/#constructor_2)(int[]) | 새로운 `ColorPalette` 클래스 인스턴스를 초기화하고 IsCompactPalette는 false입니다. |
| [ColorPalette](colorpalette/#constructor_1)(Color[], bool) | 새로운 `ColorPalette` 클래스 인스턴스를 초기화합니다. |
| [ColorPalette](colorpalette/#constructor_3)(int[], bool) | 새로운 `ColorPalette` 클래스 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Argb32Entries](../../aspose.psd/colorpalette/argb32entries/) { get; } | 32비트 ARGB 구조체 배열을 가져옵니다. |
| [Entries](../../aspose.psd/colorpalette/entries/) { get; } | [`Color`](../color/) 구조체 배열을 가져옵니다. |
| [EntriesCount](../../aspose.psd/colorpalette/entriescount/) { get; } | 엔트리 수를 가져옵니다. |
| [IsCompactPalette](../../aspose.psd/colorpalette/iscompactpalette/) { get; } | 컴팩트 팔레트 사용 여부를 나타내는 값을 가져오거나 설정합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| static [CopyPalette](../../aspose.psd/colorpalette/copypalette/#copypalette)(IColorPalette) | 팔레트를 복사합니다. |
| static [CopyPalette](../../aspose.psd/colorpalette/copypalette/#copypalette_1)(IColorPalette, bool) | 팔레트를 복사합니다. |
| [GetArgb32Color](../../aspose.psd/colorpalette/getargb32color/)(int) | 인덱스로 32비트 ARGB 팔레트 색상을 가져옵니다. |
| [GetColor](../../aspose.psd/colorpalette/getcolor/)(int) | 인덱스로 팔레트 색상을 가져옵니다. |
| [GetNearestColorIndex](../../aspose.psd/colorpalette/getnearestcolorindex/#getnearestcolorindex)(Color) | 가장 가까운 색상의 인덱스를 가져옵니다. |
| [GetNearestColorIndex](../../aspose.psd/colorpalette/getnearestcolorindex/#getnearestcolorindex_1)(int) | 가장 가까운 색상의 인덱스를 가져옵니다. |

### 또 보기

* interface [IColorPalette](../icolorpalette/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


