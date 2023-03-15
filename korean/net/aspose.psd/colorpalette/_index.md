---
title: Class ColorPalette
second_title: .NET API 참조용 Aspose.PSD
description: Aspose.PSD.ColorPalette 수업. 색상 팔레트를 구성하는 색상 배열을 정의합니다. 색상은 32비트 ARGB 색상입니다. 상속불가.
type: docs
weight: 370
url: /ko/net/aspose.psd/colorpalette/
---
## ColorPalette class

색상 팔레트를 구성하는 색상 배열을 정의합니다. 색상은 32비트 ARGB 색상입니다. 상속불가.

```csharp
public sealed class ColorPalette : IColorPalette
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [ColorPalette](colorpalette/#constructor)(Color[]) | 의 새 인스턴스를 초기화합니다.`ColorPalette` 클래스 및 IsCompactPalette가 false입니다. |
| [ColorPalette](colorpalette/#constructor_2)(int[]) | 의 새 인스턴스를 초기화합니다.`ColorPalette` 클래스 및 IsCompactPalette가 false입니다. |
| [ColorPalette](colorpalette/#constructor_1)(Color[], bool) | 의 새 인스턴스를 초기화합니다.`ColorPalette` 클래스. |
| [ColorPalette](colorpalette/#constructor_3)(int[], bool) | 의 새 인스턴스를 초기화합니다.`ColorPalette` 클래스. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Argb32Entries](../../aspose.psd/colorpalette/argb32entries/) { get; } | 32비트 ARGB 구조의 배열을 가져옵니다. |
| [Entries](../../aspose.psd/colorpalette/entries/) { get; } | 배열을 가져옵니다.[`Color`](../color/) 구조. |
| [EntriesCount](../../aspose.psd/colorpalette/entriescount/) { get; } | 항목 수를 가져옵니다. |
| [IsCompactPalette](../../aspose.psd/colorpalette/iscompactpalette/) { get; } | 컴팩트 팔레트 사용 여부를 나타내는 값을 가져오거나 설정합니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| static [CopyPalette](../../aspose.psd/colorpalette/copypalette/#copypalette)(IColorPalette) | 팔레트를 복사합니다. |
| static [CopyPalette](../../aspose.psd/colorpalette/copypalette/#copypalette_1)(IColorPalette, bool) | 팔레트를 복사합니다. |
| [GetArgb32Color](../../aspose.psd/colorpalette/getargb32color/)(int) | 인덱스로 32비트 ARGB 팔레트 색상을 가져옵니다. |
| [GetColor](../../aspose.psd/colorpalette/getcolor/)(int) | 인덱스로 팔레트 색상을 가져옵니다. |
| [GetNearestColorIndex](../../aspose.psd/colorpalette/getnearestcolorindex/#getnearestcolorindex)(Color) | 가장 가까운 색상의 인덱스를 가져옵니다. |
| [GetNearestColorIndex](../../aspose.psd/colorpalette/getnearestcolorindex/#getnearestcolorindex_1)(int) | 가장 가까운 색상의 인덱스를 가져옵니다. |

### 또한보십시오

* interface [IColorPalette](../icolorpalette/)
* 네임스페이스 [Aspose.PSD](../../aspose.psd/)
* 집회 [Aspose.PSD](../../)


