---
title: "クラス ColorPalette"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.ColorPalette クラス。カラーパレットを構成する色の配列を定義します。色は 32 ビット ARGB カラーです。継承できません。"
type: docs
weight: 370
url: /ja/net/aspose.psd/colorpalette/
---
{{< psd/tize >}}
## ColorPalette class

カラーパレットを構成する色の配列を定義します。これらの色は 32 ビット ARGB カラーです。継承できません。

```csharp
public sealed class ColorPalette : IColorPalette
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [ColorPalette](colorpalette/#constructor)(Color[]) | `ColorPalette` クラスの新しいインスタンスを初期化し、IsCompactPalette は false です。 |
| [ColorPalette](colorpalette/#constructor_2)(int[]) | `ColorPalette` クラスの新しいインスタンスを初期化し、IsCompactPalette は false です。 |
| [ColorPalette](colorpalette/#constructor_1)(Color[], bool) | `ColorPalette` クラスの新しいインスタンスを初期化します。 |
| [ColorPalette](colorpalette/#constructor_3)(int[], bool) | `ColorPalette` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Argb32Entries](../../aspose.psd/colorpalette/argb32entries/) { get; } | 32 ビット ARGB 構造体の配列を取得します。 |
| [Entries](../../aspose.psd/colorpalette/entries/) { get; } | [`Color`](../color/) 構造体の配列を取得します。 |
| [EntriesCount](../../aspose.psd/colorpalette/entriescount/) { get; } | エントリ数を取得します。 |
| [IsCompactPalette](../../aspose.psd/colorpalette/iscompactpalette/) { get; } | コンパクト パレットが使用されているかどうかを示す値を取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [CopyPalette](../../aspose.psd/colorpalette/copypalette/#copypalette)(IColorPalette) | パレットをコピーします。 |
| static [CopyPalette](../../aspose.psd/colorpalette/copypalette/#copypalette_1)(IColorPalette, bool) | パレットをコピーします。 |
| [GetArgb32Color](../../aspose.psd/colorpalette/getargb32color/)(int) | インデックスで 32 ビット ARGB パレットカラーを取得します。 |
| [GetColor](../../aspose.psd/colorpalette/getcolor/)(int) | インデックスでパレットカラーを取得します。 |
| [GetNearestColorIndex](../../aspose.psd/colorpalette/getnearestcolorindex/#getnearestcolorindex)(Color) | 最も近い色のインデックスを取得します。 |
| [GetNearestColorIndex](../../aspose.psd/colorpalette/getnearestcolorindex/#getnearestcolorindex_1)(int) | 最も近い色のインデックスを取得します。 |

### 関連項目

* interface [IColorPalette](../icolorpalette/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


