---
title: Class ColorPalette
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.ColorPalette クラス. カラー パレットを構成する色の配列を定義します色は 32 ビット ARGB 色です継承不可.
type: docs
weight: 370
url: /ja/net/aspose.psd/colorpalette/
---
## ColorPalette class

カラー パレットを構成する色の配列を定義します。色は 32 ビット ARGB 色です。継承不可.

```csharp
public sealed class ColorPalette : IColorPalette
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [ColorPalette](colorpalette/#constructor)(Color[]) | の新しいインスタンスを初期化します`ColorPalette`クラスと IsCompactPalette は false. |
| [ColorPalette](colorpalette/#constructor_2)(int[]) | の新しいインスタンスを初期化します`ColorPalette`クラスと IsCompactPalette は false. |
| [ColorPalette](colorpalette/#constructor_1)(Color[], bool) | の新しいインスタンスを初期化します`ColorPalette`class. |
| [ColorPalette](colorpalette/#constructor_3)(int[], bool) | の新しいインスタンスを初期化します`ColorPalette`class. |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Argb32Entries](../../aspose.psd/colorpalette/argb32entries/) { get; } | 32 ビット ARGB 構造体の配列を取得します。 |
| [Entries](../../aspose.psd/colorpalette/entries/) { get; } | の配列を取得します[`Color`](../color/)構造物. |
| [EntriesCount](../../aspose.psd/colorpalette/entriescount/) { get; } | エントリ数を取得します。 |
| [IsCompactPalette](../../aspose.psd/colorpalette/iscompactpalette/) { get; } | コンパクト パレットを使用するかどうかを示す値を取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [CopyPalette](../../aspose.psd/colorpalette/copypalette/#copypalette)(IColorPalette) | パレットをコピーします。 |
| static [CopyPalette](../../aspose.psd/colorpalette/copypalette/#copypalette_1)(IColorPalette, bool) | パレットをコピーします。 |
| [GetArgb32Color](../../aspose.psd/colorpalette/getargb32color/)(int) | インデックスで 32 ビット ARGB パレット カラーを取得します。 |
| [GetColor](../../aspose.psd/colorpalette/getcolor/)(int) | インデックスでパレットの色を取得します. |
| [GetNearestColorIndex](../../aspose.psd/colorpalette/getnearestcolorindex/#getnearestcolorindex)(Color) | 最も近い色のインデックスを取得します。 |
| [GetNearestColorIndex](../../aspose.psd/colorpalette/getnearestcolorindex/#getnearestcolorindex_1)(int) | 最も近い色のインデックスを取得します。 |

### 関連項目

* interface [IColorPalette](../icolorpalette/)
* 名前空間 [Aspose.PSD](../../aspose.psd/)
* 組み立て [Aspose.PSD](../../)


