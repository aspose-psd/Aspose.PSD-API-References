---
title: "クラス PsdColorPalette"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.FileFormats.Psd.PsdColorPalette クラス。PSD カラーパレットです。"
type: docs
weight: 4040
url: /ja/net/aspose.psd.fileformats.psd/psdcolorpalette/
---
{{< psd/tize >}}
## PsdColorPalette class

PSD カラーパレットです。

```csharp
public class PsdColorPalette : IPsdColorPalette
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [PsdColorPalette](psdcolorpalette/#constructor_6)(byte[]) | `PsdColorPalette` クラスの新しいインスタンスを初期化し、IsCompactPalette は false です。 |
| [PsdColorPalette](psdcolorpalette/#constructor)(Color[]) | `PsdColorPalette` クラスの新しいインスタンスを初期化し、IsCompactPalette は false です。 |
| [PsdColorPalette](psdcolorpalette/#constructor_4)(IColorPalette) | `PsdColorPalette` クラスの新しいインスタンスを初期化します。 |
| [PsdColorPalette](psdcolorpalette/#constructor_7)(byte[], bool) | `PsdColorPalette` クラスの新しいインスタンスを初期化します。 |
| [PsdColorPalette](psdcolorpalette/#constructor_8)(byte[], short) | `PsdColorPalette` クラスの新しいインスタンスを初期化し、IsCompactPalette は false です。 |
| [PsdColorPalette](psdcolorpalette/#constructor_1)(Color[], bool) | `PsdColorPalette` クラスの新しいインスタンスを初期化します。 |
| [PsdColorPalette](psdcolorpalette/#constructor_2)(Color[], short) | `PsdColorPalette` クラスの新しいインスタンスを初期化し、IsCompactPalette は false です。 |
| [PsdColorPalette](psdcolorpalette/#constructor_5)(IColorPalette, short) | `PsdColorPalette` クラスの新しいインスタンスを初期化します。 |
| [PsdColorPalette](psdcolorpalette/#constructor_10)(int[], bool) | `PsdColorPalette` クラスの新しいインスタンスを初期化します。 |
| [PsdColorPalette](psdcolorpalette/#constructor_9)(byte[], short, bool) | `PsdColorPalette` クラスの新しいインスタンスを初期化します。 |
| [PsdColorPalette](psdcolorpalette/#constructor_3)(Color[], short, bool) | `PsdColorPalette` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Argb32Entries](../../aspose.psd.fileformats.psd/psdcolorpalette/argb32entries/) { get; } | 32 ビット ARGB カラーの配列を取得します。 |
| [Entries](../../aspose.psd.fileformats.psd/psdcolorpalette/entries/) { get; } | [`Color`](../../aspose.psd/color/) 構造体の配列を取得します。 |
| [EntriesCount](../../aspose.psd.fileformats.psd/psdcolorpalette/entriescount/) { get; } | エントリ数を取得します。 |
| [HasTransparentColor](../../aspose.psd.fileformats.psd/psdcolorpalette/hastransparentcolor/) { get; } | 透過色が存在するかどうかを示す値を取得します。 |
| [IsCompactPalette](../../aspose.psd.fileformats.psd/psdcolorpalette/iscompactpalette/) { get; } | コンパクトなパレットかどうかを示す値を取得します。 |
| [RawEntries](../../aspose.psd.fileformats.psd/psdcolorpalette/rawentries/) { get; } | 生のカラーパレットエントリーデータを取得します。 |
| [RawEntriesCount](../../aspose.psd.fileformats.psd/psdcolorpalette/rawentriescount/) { get; } | 生のカラーパレットエントリー数を取得します。 |
| [TransparentColor](../../aspose.psd.fileformats.psd/psdcolorpalette/transparentcolor/) { get; } | 透過色を取得します。 |
| [TransparentIndex](../../aspose.psd.fileformats.psd/psdcolorpalette/transparentindex/) { get; } | 透過色のインデックスを取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [CopyPalette](../../aspose.psd.fileformats.psd/psdcolorpalette/copypalette/#copypalette)(IColorPalette) | パレットをコピーします。 |
| static [CopyPalette](../../aspose.psd.fileformats.psd/psdcolorpalette/copypalette/#copypalette_1)(IColorPalette, bool) | パレットをコピーします。 |
| [GetArgb32Color](../../aspose.psd.fileformats.psd/psdcolorpalette/getargb32color/)(int) | インデックスで 32 ビット ARGB パレットカラーを取得します。 |
| [GetColor](../../aspose.psd.fileformats.psd/psdcolorpalette/getcolor/)(int) | インデックスでパレットカラーを取得します。 |
| [GetNearestColorIndex](../../aspose.psd.fileformats.psd/psdcolorpalette/getnearestcolorindex/#getnearestcolorindex)(Color) | 最も近い色のインデックスを取得します。 |
| [GetNearestColorIndex](../../aspose.psd.fileformats.psd/psdcolorpalette/getnearestcolorindex/#getnearestcolorindex_1)(int) | 最も近い色のインデックスを取得します。 |

### 関連項目

* interface [IPsdColorPalette](../../aspose.psd/ipsdcolorpalette/)
* namespace [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../)


