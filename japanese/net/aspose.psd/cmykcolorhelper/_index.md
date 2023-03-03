---
title: Class CmykColorHelper
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.CmykColorHelper クラス. 符号付き 32 ビット整数値として提示される CMYK カラーを操作するヘルパー メソッドCmykColorstruct. 内部フィールドを持つ構造体ではなくCMYK カラーが Int32 として表示されるためより軽量です deprecated の代わりに可能な場合はこのクラスの静的メソッドを使用することをお勧めしますCmykColor構造体.
type: docs
weight: 280
url: /ja/net/aspose.psd/cmykcolorhelper/
---
## CmykColorHelper class

符号付き 32 ビット整数値として提示される CMYK カラーを操作するヘルパー メソッド。[`CmykColor`](../cmykcolor/)struct. 内部フィールドを持つ構造体ではなく、CMYK カラーが Int32 として表示されるため、より軽量です。 deprecated の代わりに、可能な場合はこのクラスの静的メソッドを使用することをお勧めします。[`CmykColor`](../cmykcolor/)構造体.

```csharp
public static class CmykColorHelper
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [FromComponents](../../aspose.psd/cmykcolorhelper/fromcomponents/)(int, int, int, int) | 32 ビットのシアン、マゼンタ、イエロー、およびブラックの値から CMYK を作成します。 |
| static [GetC](../../aspose.psd/cmykcolorhelper/getc/)(int) | シアン成分の値を取得します。 |
| static [GetK](../../aspose.psd/cmykcolorhelper/getk/)(int) | 黒成分値を取得します。 |
| static [GetM](../../aspose.psd/cmykcolorhelper/getm/)(int) | マゼンタ成分の値を取得します。 |
| static [GetY](../../aspose.psd/cmykcolorhelper/gety/)(int) | 黄色のコンポーネント値を取得します。 |
| static [ToArgb](../../aspose.psd/cmykcolorhelper/toargb/#toargb)(int) | CMYK カラーから ARGB カラーへの変換。 |
| static [ToArgb](../../aspose.psd/cmykcolorhelper/toargb/#toargb_1)(int[]) | CMYK カラーから ARGB カラーへの変換。 |
| static [ToArgb32](../../aspose.psd/cmykcolorhelper/toargb32/)(int[]) | CMYK カラーから ARGB カラーへの変換。 |
| static [ToArgbIcc](../../aspose.psd/cmykcolorhelper/toargbicc/#toargbicc)(int) | デフォルト プロファイルの Icc 変換を使用した CMYK カラーから ARGB カラーへの変換. |
| static [ToArgbIcc](../../aspose.psd/cmykcolorhelper/toargbicc/#toargbicc_2)(int[]) | デフォルトのプロファイルで Icc 変換を使用した CMYK カラーから ARGB カラーへの変換. |
| static [ToArgbIcc](../../aspose.psd/cmykcolorhelper/toargbicc/#toargbicc_1)(int, Stream, Stream) | カスタムプロファイルによる Icc 変換を使用した CMYK カラーから ARGB カラーへの変換. |
| static [ToArgbIcc](../../aspose.psd/cmykcolorhelper/toargbicc/#toargbicc_3)(int[], Stream, Stream) | カスタム プロファイルによる Icc 変換を使用した CMYK カラーから ARGB カラーへの変換。 |
| static [ToCmyk](../../aspose.psd/cmykcolorhelper/tocmyk/#tocmyk)(Color) | ARGB カラーから CMYK カラーへの変換. |
| static [ToCmyk](../../aspose.psd/cmykcolorhelper/tocmyk/#tocmyk_2)(Color[]) | ARGB カラーから CMYK カラーへの変換。 |
| static [ToCmyk](../../aspose.psd/cmykcolorhelper/tocmyk/#tocmyk_1)(int) | ARGB カラーから CMYK カラーへの変換. |
| static [ToCmyk](../../aspose.psd/cmykcolorhelper/tocmyk/#tocmyk_3)(int[]) | ARGB カラーから CMYK カラーへの変換。 |
| static [ToCmykBytes](../../aspose.psd/cmykcolorhelper/tocmykbytes/)(int[], int, int) | RGB を CMYK に変換します。 |
| static [ToCmykIcc](../../aspose.psd/cmykcolorhelper/tocmykicc/#tocmykicc)(Color) | デフォルトのプロファイルで Icc 変換を使用した ARGB カラーから CMYK カラーへの変換. |
| static [ToCmykIcc](../../aspose.psd/cmykcolorhelper/tocmykicc/#tocmykicc_2)(Color[]) | デフォルトのプロファイルで Icc 変換を使用した ARGB カラーから CMYK カラーへの変換. |
| static [ToCmykIcc](../../aspose.psd/cmykcolorhelper/tocmykicc/#tocmykicc_1)(Color, Stream, Stream) | カスタム プロファイルによる Icc 変換を使用した ARGB カラーから CMYK カラーへの変換. |
| static [ToCmykIcc](../../aspose.psd/cmykcolorhelper/tocmykicc/#tocmykicc_3)(Color[], Stream, Stream) | カスタム プロファイルによる Icc 変換を使用した ARGB カラーから CMYK カラーへの変換. |
| static [ToCmykIccBytes](../../aspose.psd/cmykcolorhelper/tocmykiccbytes/)(int[], int, int, Stream, Stream) | カスタム ICC プロファイルを使用して RGB を CMYK に変換します。 |

### 関連項目

* 名前空間 [Aspose.PSD](../../aspose.psd/)
* 組み立て [Aspose.PSD](../../)


