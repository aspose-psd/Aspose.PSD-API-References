---
title: "クラス CmykColorHelper"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.CmykColorHelper クラス。符号付き 32 ビット整数値として表現された CMYK カラーを扱うヘルパーメソッドを提供します。CmykColor 構造体と同様の API を提供します。CMYK カラーが内部フィールドを持つ構造体ではなく Int32 として表現されるため、より軽量です。可能な限り、非推奨となった CmykColor 構造体の代わりにこのクラスの静的メソッドを使用してください。"
type: docs
weight: 280
url: /ja/net/aspose.psd/cmykcolorhelper/
---
{{< psd/tize >}}
## CmykColorHelper class

符号付き 32 ビット整数値として表現された CMYK カラーを扱うヘルパーメソッド。[`CmykColor`](../cmykcolor/) 構造体と同様の API を提供します。CMYK カラーが内部フィールドを持つ構造体ではなく Int32 として表現されるため、より軽量です。可能な限り、非推奨となった [`CmykColor`](../cmykcolor/) 構造体の代わりにこのクラスの静的メソッドを使用してください。

```csharp
public static class CmykColorHelper
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [FromComponents](../../aspose.psd/cmykcolorhelper/fromcomponents/)(int, int, int, int) | 32 ビットのシアン、マゼンタ、イエロー、ブラックの値から CMYK を作成します。 |
| static [GetC](../../aspose.psd/cmykcolorhelper/getc/)(int) | シアン成分の値を取得します。 |
| static [GetK](../../aspose.psd/cmykcolorhelper/getk/)(int) | ブラック成分の値を取得します。 |
| static [GetM](../../aspose.psd/cmykcolorhelper/getm/)(int) | マゼンタ成分の値を取得します。 |
| static [GetY](../../aspose.psd/cmykcolorhelper/gety/)(int) | イエロー成分の値を取得します。 |
| static [ToArgb](../../aspose.psd/cmykcolorhelper/toargb/#toargb)(int) | CMYK カラーから ARGB カラーへの変換。 |
| static [ToArgb](../../aspose.psd/cmykcolorhelper/toargb/#toargb_1)(int[]) | CMYK カラーから ARGB カラーへの変換。 |
| static [ToArgb32](../../aspose.psd/cmykcolorhelper/toargb32/)(int[]) | CMYK カラーから ARGB カラーへの変換。 |
| static [ToArgbIcc](../../aspose.psd/cmykcolorhelper/toargbicc/#toargbicc)(int) | デフォルトプロファイルを使用した ICC 変換により、CMYK カラーから ARGB カラーへの変換。 |
| static [ToArgbIcc](../../aspose.psd/cmykcolorhelper/toargbicc/#toargbicc_2)(int[]) | デフォルトプロファイルを使用した ICC 変換により、CMYK カラーから ARGB カラーへの変換。 |
| static [ToArgbIcc](../../aspose.psd/cmykcolorhelper/toargbicc/#toargbicc_1)(int, Stream, Stream) | カスタムプロファイルを使用した ICC 変換により、CMYK カラーから ARGB カラーへの変換。 |
| static [ToArgbIcc](../../aspose.psd/cmykcolorhelper/toargbicc/#toargbicc_3)(int[], Stream, Stream) | カスタムプロファイルを使用した ICC 変換により、CMYK カラーから ARGB カラーへの変換。 |
| static [ToCmyk](../../aspose.psd/cmykcolorhelper/tocmyk/#tocmyk)(Color) | ARGB カラーから CMYK カラーへの変換。 |
| static [ToCmyk](../../aspose.psd/cmykcolorhelper/tocmyk/#tocmyk_2)(Color[]) | ARGB カラーから CMYK カラーへの変換。 |
| static [ToCmyk](../../aspose.psd/cmykcolorhelper/tocmyk/#tocmyk_1)(int) | ARGB カラーから CMYK カラーへの変換。 |
| static [ToCmyk](../../aspose.psd/cmykcolorhelper/tocmyk/#tocmyk_3)(int[]) | ARGB カラーから CMYK カラーへの変換。 |
| static [ToCmykBytes](../../aspose.psd/cmykcolorhelper/tocmykbytes/)(int[], int, int) | RGB を CMYK に変換します。 |
| static [ToCmykIcc](../../aspose.psd/cmykcolorhelper/tocmykicc/#tocmykicc)(Color) | デフォルトプロファイルを使用した ICC 変換により、ARGB カラーから CMYK カラーへの変換。 |
| static [ToCmykIcc](../../aspose.psd/cmykcolorhelper/tocmykicc/#tocmykicc_2)(Color[]) | デフォルトプロファイルを使用した ICC 変換により、ARGB カラーから CMYK カラーへの変換。 |
| static [ToCmykIcc](../../aspose.psd/cmykcolorhelper/tocmykicc/#tocmykicc_1)(Color, Stream, Stream) | カスタムプロファイルを使用した ICC 変換により、ARGB カラーから CMYK カラーへの変換。 |
| static [ToCmykIcc](../../aspose.psd/cmykcolorhelper/tocmykicc/#tocmykicc_3)(Color[], Stream, Stream) | カスタムプロファイルを使用した Icc 変換による ARGB カラーから CMYK カラーへの変換。 |
| static [ToCmykIccBytes](../../aspose.psd/cmykcolorhelper/tocmykiccbytes/)(int[], int, int, Stream, Stream) | カスタム ICC プロファイルを使用して RGB を CMYK に変換します。 |

### 関連項目

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


