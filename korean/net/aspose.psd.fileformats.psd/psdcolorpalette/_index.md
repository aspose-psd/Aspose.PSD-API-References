---
title: "클래스 PsdColorPalette"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.FileFormats.Psd.PsdColorPalette 클래스. PSD 색상 팔레트"
type: docs
weight: 4040
url: /ko/net/aspose.psd.fileformats.psd/psdcolorpalette/
---
{{< psd/tize >}}
## PsdColorPalette class

PSD 색상 팔레트.

```csharp
public class PsdColorPalette : IPsdColorPalette
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [PsdColorPalette](psdcolorpalette/#constructor_6)(byte[]) | `PsdColorPalette` 클래스의 새 인스턴스를 초기화하고 IsCompactPalette는 false입니다. |
| [PsdColorPalette](psdcolorpalette/#constructor)(Color[]) | `PsdColorPalette` 클래스의 새 인스턴스를 초기화하고 IsCompactPalette는 false입니다. |
| [PsdColorPalette](psdcolorpalette/#constructor_4)(IColorPalette) | `PsdColorPalette` 클래스의 새 인스턴스를 초기화합니다. |
| [PsdColorPalette](psdcolorpalette/#constructor_7)(byte[], bool) | `PsdColorPalette` 클래스의 새 인스턴스를 초기화합니다. |
| [PsdColorPalette](psdcolorpalette/#constructor_8)(byte[], short) | `PsdColorPalette` 클래스의 새 인스턴스를 초기화하고 IsCompactPalette는 false입니다. |
| [PsdColorPalette](psdcolorpalette/#constructor_1)(Color[], bool) | `PsdColorPalette` 클래스의 새 인스턴스를 초기화합니다. |
| [PsdColorPalette](psdcolorpalette/#constructor_2)(Color[], short) | `PsdColorPalette` 클래스의 새 인스턴스를 초기화하고 IsCompactPalette는 false입니다. |
| [PsdColorPalette](psdcolorpalette/#constructor_5)(IColorPalette, short) | `PsdColorPalette` 클래스의 새 인스턴스를 초기화합니다. |
| [PsdColorPalette](psdcolorpalette/#constructor_10)(int[], bool) | `PsdColorPalette` 클래스의 새 인스턴스를 초기화합니다. |
| [PsdColorPalette](psdcolorpalette/#constructor_9)(byte[], short, bool) | `PsdColorPalette` 클래스의 새 인스턴스를 초기화합니다. |
| [PsdColorPalette](psdcolorpalette/#constructor_3)(Color[], short, bool) | `PsdColorPalette` 클래스의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Argb32Entries](../../aspose.psd.fileformats.psd/psdcolorpalette/argb32entries/) { get; } | 32비트 ARGB 색상의 배열을 가져옵니다. |
| [Entries](../../aspose.psd.fileformats.psd/psdcolorpalette/entries/) { get; } | [`Color`](../../aspose.psd/color/) 구조체 배열을 가져옵니다. |
| [EntriesCount](../../aspose.psd.fileformats.psd/psdcolorpalette/entriescount/) { get; } | 엔트리 수를 가져옵니다. |
| [HasTransparentColor](../../aspose.psd.fileformats.psd/psdcolorpalette/hastransparentcolor/) { get; } | 투명 색상이 존재하는지 여부를 나타내는 값을 가져옵니다. |
| [IsCompactPalette](../../aspose.psd.fileformats.psd/psdcolorpalette/iscompactpalette/) { get; } | 컴팩트된 팔레트인지 여부를 나타내는 값을 가져옵니다. |
| [RawEntries](../../aspose.psd.fileformats.psd/psdcolorpalette/rawentries/) { get; } | 원시 색상 팔레트 항목 데이터를 가져옵니다. |
| [RawEntriesCount](../../aspose.psd.fileformats.psd/psdcolorpalette/rawentriescount/) { get; } | 원시 색상 팔레트 항목 수를 가져옵니다. |
| [TransparentColor](../../aspose.psd.fileformats.psd/psdcolorpalette/transparentcolor/) { get; } | 투명 색상을 가져옵니다. |
| [TransparentIndex](../../aspose.psd.fileformats.psd/psdcolorpalette/transparentindex/) { get; } | 투명 색상의 인덱스를 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| static [CopyPalette](../../aspose.psd.fileformats.psd/psdcolorpalette/copypalette/#copypalette)(IColorPalette) | 팔레트를 복사합니다. |
| static [CopyPalette](../../aspose.psd.fileformats.psd/psdcolorpalette/copypalette/#copypalette_1)(IColorPalette, bool) | 팔레트를 복사합니다. |
| [GetArgb32Color](../../aspose.psd.fileformats.psd/psdcolorpalette/getargb32color/)(int) | 인덱스로 32비트 ARGB 팔레트 색상을 가져옵니다. |
| [GetColor](../../aspose.psd.fileformats.psd/psdcolorpalette/getcolor/)(int) | 인덱스로 팔레트 색상을 가져옵니다. |
| [GetNearestColorIndex](../../aspose.psd.fileformats.psd/psdcolorpalette/getnearestcolorindex/#getnearestcolorindex)(Color) | 가장 가까운 색상의 인덱스를 가져옵니다. |
| [GetNearestColorIndex](../../aspose.psd.fileformats.psd/psdcolorpalette/getnearestcolorindex/#getnearestcolorindex_1)(int) | 가장 가까운 색상의 인덱스를 가져옵니다. |

### 또 보기

* interface [IPsdColorPalette](../../aspose.psd/ipsdcolorpalette/)
* namespace [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../)


