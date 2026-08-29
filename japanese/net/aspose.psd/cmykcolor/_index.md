---
title: "構造体 CmykColor"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.CmykColor 構造体。ピクセルの CMYK カラー"
type: docs
weight: 270
url: /ja/net/aspose.psd/cmykcolor/
---
{{< psd/tize >}}
## CmykColor structure

ピクセルの CMYK カラーです。

```csharp
public struct CmykColor
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| static [Empty](../../aspose.psd/cmykcolor/empty/) { get; } | 空であるかを取得します。 |
| [C](../../aspose.psd/cmykcolor/c/) { get; } | この [`Color`](../color/) 構造体のシアン成分の値を取得します。 |
| [IsEmpty](../../aspose.psd/cmykcolor/isempty/) { get; } | この [`Color`](../color/) 構造体が未初期化かどうかを示す値を取得します。 |
| [K](../../aspose.psd/cmykcolor/k/) { get; } | この [`Color`](../color/) 構造体のブラック成分の値を取得します。 |
| [M](../../aspose.psd/cmykcolor/m/) { get; } | この [`Color`](../color/) 構造体のマゼンタ成分の値を取得します。 |
| [Y](../../aspose.psd/cmykcolor/y/) { get; } | この [`Color`](../color/) 構造体の黄色成分の値を取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [FromParams](../../aspose.psd/cmykcolor/fromparams/)(int, int, int, int) | 32ビットのシアン、マゼンタ、イエロー、ブラック値から `CmykColor` 構造体を作成します。このメソッドは非推奨です。より効果的な [`FromComponents`](../cmykcolorhelper/fromcomponents/) を使用してください。 |
| static [ToCmyk](../../aspose.psd/cmykcolor/tocmyk/#tocmyk)(int) | 32ビット ARGB から CMYKColor への変換。このメソッドは非推奨です。より効果的な [`ToCmyk`](../cmykcolorhelper/tocmyk/) を使用してください。 |
| override [Equals](../../aspose.psd/cmykcolor/equals/)(object) | 指定されたオブジェクトがこのインスタンスと等しいかどうかを判断します。 |
| override [GetHashCode](../../aspose.psd/cmykcolor/gethashcode/)() | ハッシュコードを取得します。 |
| [ToValue](../../aspose.psd/cmykcolor/tovalue/)() | 変換後の値です。 |
| static [ToArgb32](../../aspose.psd/cmykcolor/toargb32/)(CmykColor[]) | デフォルトプロファイルを使用した ICC 変換により、CMYKColor から 32 ビット ARGB Color への変換。このメソッドは非推奨です。より効果的な [`ToArgb32`](../cmykcolorhelper/toargb32/) を使用してください。 |
| static [ToCmyk](../../aspose.psd/cmykcolor/tocmyk/#tocmyk_1)(int[]) | 32 ビット ARGB カラーから CMYKColor への変換。このメソッドは非推奨です。より効果的な [`ToCmyk`](../cmykcolorhelper/tocmyk/) を使用してください。 |
| static [ToColor](../../aspose.psd/cmykcolor/tocolor/#tocolor)(CmykColor) | CMYKColor から Color への変換。このメソッドは非推奨です。より効果的な [`ToArgb`](../cmykcolorhelper/toargb/) を使用してください。 |
| static [ToColor](../../aspose.psd/cmykcolor/tocolor/#tocolor_1)(CmykColor[]) | デフォルトプロファイルを使用した ICC 変換により、CMYKColor から Color への変換。このメソッドは非推奨です。より効果的な [`ToArgb`](../cmykcolorhelper/toargb/) を使用してください。 |
| static [ToColorIcc](../../aspose.psd/cmykcolor/tocoloricc/#tocoloricc)(CmykColor) | デフォルトプロファイルを使用した ICC 変換により、CMYKColor から Color への変換。このメソッドは非推奨です。より効果的な [`ToArgbIcc`](../cmykcolorhelper/toargbicc/) を使用してください。 |
| static [ToColorIcc](../../aspose.psd/cmykcolor/tocoloricc/#tocoloricc_2)(CmykColor[]) | デフォルトプロファイルを使用した ICC 変換により、CMYKColor から Color への変換。このメソッドは非推奨です。より効果的な [`ToArgbIcc`](../cmykcolorhelper/toargbicc/) を使用してください。 |
| static [ToColorIcc](../../aspose.psd/cmykcolor/tocoloricc/#tocoloricc_1)(CmykColor, Stream, Stream) | ICC 変換を使用した CMYKColor から Color への変換。このメソッドは非推奨です。より効果的な [`ToArgbIcc`](../cmykcolorhelper/toargbicc/) を使用してください。 |
| static [ToColorIcc](../../aspose.psd/cmykcolor/tocoloricc/#tocoloricc_3)(CmykColor[], Stream, Stream) | ICC 変換を使用した CMYKColor から Color への変換。このメソッドは非推奨です。より効果的な [`ToArgbIcc`](../cmykcolorhelper/toargbicc/) を使用してください。 |

### 関連項目

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


