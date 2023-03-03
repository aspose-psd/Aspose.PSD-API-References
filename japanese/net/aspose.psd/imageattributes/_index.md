---
title: Class ImageAttributes
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.ImageAttributes クラス. アンImageAttributesオブジェクトにはレンダリング中にビットマップとメタファイルの色がどのように操作されるかに関する情報が含まれていますアンImageAttributesオブジェクトは色調整マトリックスグレースケール調整マトリックスガンマ補正値カラーマップ テーブル色しきい値などいくつかの色調整設定を保持しますレンダリング中に色を修正したり暗くしたり明るくしたり削除したりできますこのような操作を適用するにはImageAttributesオブジェクトとそのパスを渡しますImageAttributesオブジェクト のパスとともにImage DrawImage メソッドに.
type: docs
weight: 4610
url: /ja/net/aspose.psd/imageattributes/
---
## ImageAttributes class

アン`ImageAttributes`オブジェクトには、レンダリング中にビットマップとメタファイルの色がどのように操作されるかに関する情報が含まれています。アン`ImageAttributes`オブジェクトは、色調整マトリックス、グレースケール調整マトリックス、ガンマ補正値、カラーマップ テーブル、色しきい値など、いくつかの色調整設定を保持します。レンダリング中に、色を修正したり、暗くしたり、明るくしたり、削除したりできます。このような操作を適用するには、`ImageAttributes`オブジェクトとそのパスを渡します`ImageAttributes`オブジェクト (のパスとともに[`Image`](../image/) DrawImage メソッドに.

```csharp
public sealed class ImageAttributes
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [ImageAttributes](imageattributes/)() | デフォルトのコンストラクター。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [ClearBrushRemapTable](../../aspose.psd/imageattributes/clearbrushremaptable/)() | このブラシ カラー リマップ テーブルをクリアします`ImageAttributes`object. |
| [ClearColorKey](../../aspose.psd/imageattributes/clearcolorkey/#clearcolorkey)() | デフォルト カテゴリのカラー キー (透明度範囲) をクリアします。 |
| [ClearColorKey](../../aspose.psd/imageattributes/clearcolorkey/#clearcolorkey_1)(ColorAdjustType) | 指定したカテゴリのカラー キー (透明度範囲) をクリアします。 |
| [ClearColorMatrix](../../aspose.psd/imageattributes/clearcolormatrix/#clearcolormatrix)() | デフォルト カテゴリの色調整マトリックスをクリアします。 |
| [ClearColorMatrix](../../aspose.psd/imageattributes/clearcolormatrix/#clearcolormatrix_1)(ColorAdjustType) | 指定したカテゴリの色調整マトリックスをクリアします。 |
| [ClearGamma](../../aspose.psd/imageattributes/cleargamma/#cleargamma)() | デフォルト カテゴリのガンマ補正を無効にします。 |
| [ClearGamma](../../aspose.psd/imageattributes/cleargamma/#cleargamma_1)(ColorAdjustType) | 指定したカテゴリのガンマ補正を無効にします。 |
| [ClearNoOp](../../aspose.psd/imageattributes/clearnoop/#clearnoop)() | デフォルト カテゴリの NoOp 設定をクリアします。 |
| [ClearNoOp](../../aspose.psd/imageattributes/clearnoop/#clearnoop_1)(ColorAdjustType) | 指定したカテゴリの NoOp 設定をクリアします。 |
| [ClearOutputChannel](../../aspose.psd/imageattributes/clearoutputchannel/#clearoutputchannel)() | デフォルト カテゴリの CMYK (シアン-マゼンタ-イエロー-ブラック) 出力チャネル設定をクリアします。 |
| [ClearOutputChannel](../../aspose.psd/imageattributes/clearoutputchannel/#clearoutputchannel_1)(ColorAdjustType) | 指定されたカテゴリーの (シアン-マゼンタ-黄-黒) 出力チャネル設定をクリアします。 |
| [ClearOutputChannelColorProfile](../../aspose.psd/imageattributes/clearoutputchannelcolorprofile/#clearoutputchannelcolorprofile)() | デフォルト カテゴリの出力チャネル カラー プロファイル設定をクリアします。 |
| [ClearOutputChannelColorProfile](../../aspose.psd/imageattributes/clearoutputchannelcolorprofile/#clearoutputchannelcolorprofile_1)(ColorAdjustType) | 指定したカテゴリの出力チャネル カラー プロファイル設定をクリアします。 |
| [ClearRemapTable](../../aspose.psd/imageattributes/clearremaptable/#clearremaptable)() | デフォルト カテゴリのカラー リマップ テーブルをクリアします。 |
| [ClearRemapTable](../../aspose.psd/imageattributes/clearremaptable/#clearremaptable_1)(ColorAdjustType) | 指定したカテゴリのカラー リマップ テーブルをクリアします。 |
| [ClearThreshold](../../aspose.psd/imageattributes/clearthreshold/#clearthreshold)() | デフォルト カテゴリのしきい値をクリアします。 |
| [ClearThreshold](../../aspose.psd/imageattributes/clearthreshold/#clearthreshold_1)(ColorAdjustType) | 指定したカテゴリのしきい値をクリアします。 |
| [SetBrushRemapTable](../../aspose.psd/imageattributes/setbrushremaptable/)(ColorMap[]) | ブラシ カテゴリのカラー リマップ テーブルを設定します。 |
| [SetColorKey](../../aspose.psd/imageattributes/setcolorkey/#setcolorkey)(Color, Color) | デフォルト カテゴリのカラー キーを設定します。 |
| [SetColorKey](../../aspose.psd/imageattributes/setcolorkey/#setcolorkey_1)(Color, Color, ColorAdjustType) | 指定したカテゴリのカラー キー (透明度の範囲) を設定します。 |
| [SetColorMatrices](../../aspose.psd/imageattributes/setcolormatrices/#setcolormatrices)(ColorMatrix, ColorMatrix) | デフォルト カテゴリの色調整マトリックスとグレースケール調整マトリックスを設定します。 |
| [SetColorMatrices](../../aspose.psd/imageattributes/setcolormatrices/#setcolormatrices_1)(ColorMatrix, ColorMatrix, ColorMatrixFlag) | デフォルト カテゴリの色調整マトリックスとグレースケール調整マトリックスを設定します。 |
| [SetColorMatrices](../../aspose.psd/imageattributes/setcolormatrices/#setcolormatrices_2)(ColorMatrix, ColorMatrix, ColorMatrixFlag, ColorAdjustType) | 指定したカテゴリのカラー調整マトリックスとグレースケール調整マトリックスを設定します。 |
| [SetColorMatrix](../../aspose.psd/imageattributes/setcolormatrix/#setcolormatrix)(ColorMatrix) | デフォルト カテゴリの色調整マトリックスを設定します。 |
| [SetColorMatrix](../../aspose.psd/imageattributes/setcolormatrix/#setcolormatrix_1)(ColorMatrix, ColorMatrixFlag) | デフォルト カテゴリの色調整マトリックスを設定します。 |
| [SetColorMatrix](../../aspose.psd/imageattributes/setcolormatrix/#setcolormatrix_2)(ColorMatrix, ColorMatrixFlag, ColorAdjustType) | 指定したカテゴリの色調整マトリックスを設定します。 |
| [SetGamma](../../aspose.psd/imageattributes/setgamma/#setgamma)(float) | デフォルト カテゴリのガンマ値を設定します。 |
| [SetGamma](../../aspose.psd/imageattributes/setgamma/#setgamma_1)(float, ColorAdjustType) | 指定したカテゴリのガンマ値を設定します。 |
| [SetNoOp](../../aspose.psd/imageattributes/setnoop/#setnoop)() | デフォルト カテゴリの色調整をオフにします。 |
| [SetNoOp](../../aspose.psd/imageattributes/setnoop/#setnoop_1)(ColorAdjustType) | 指定したカテゴリの色調整をオフにします。 |
| [SetOutputChannel](../../aspose.psd/imageattributes/setoutputchannel/#setoutputchannel)(ColorChannelFlag) | デフォルト カテゴリの CMYK (シアン-マゼンタ-イエロー-ブラック) 出力チャネルを設定します。 |
| [SetOutputChannel](../../aspose.psd/imageattributes/setoutputchannel/#setoutputchannel_1)(ColorChannelFlag, ColorAdjustType) | 指定したカテゴリの CMYK (シアン-マゼンタ-イエロー-ブラック) 出力チャネルを設定します。 |
| [SetOutputChannelColorProfile](../../aspose.psd/imageattributes/setoutputchannelcolorprofile/#setoutputchannelcolorprofile)(string) | デフォルト カテゴリの出力チャネル カラー プロファイル ファイルを設定します。 |
| [SetOutputChannelColorProfile](../../aspose.psd/imageattributes/setoutputchannelcolorprofile/#setoutputchannelcolorprofile_1)(string, ColorAdjustType) | 指定したカテゴリの出力チャネル カラー プロファイル ファイルを設定します。 |
| [SetRemapTable](../../aspose.psd/imageattributes/setremaptable/#setremaptable)(ColorMap[]) | デフォルト カテゴリのカラー リマップ テーブルを設定します。 |
| [SetRemapTable](../../aspose.psd/imageattributes/setremaptable/#setremaptable_1)(ColorMap[], ColorAdjustType) | 指定したカテゴリのカラー リマップ テーブルを設定します。 |
| [SetThreshold](../../aspose.psd/imageattributes/setthreshold/#setthreshold)(float) | 既定のカテゴリのしきい値 (透明度の範囲) を設定します。 |
| [SetThreshold](../../aspose.psd/imageattributes/setthreshold/#setthreshold_1)(float, ColorAdjustType) | 指定したカテゴリのしきい値 (透明度の範囲) を設定します。 |
| [SetWrapMode](../../aspose.psd/imageattributes/setwrapmode/#setwrapmode)(WrapMode) | シェイプ全体またはシェイプ境界でテクスチャをタイリングする方法を決定するために使用されるラップ モードを設定します。テクスチャが塗りつぶしている形状よりも小さい場合、テクスチャは形状全体にタイル張りされて塗りつぶされます. |
| [SetWrapMode](../../aspose.psd/imageattributes/setwrapmode/#setwrapmode_1)(WrapMode, Color) | シェイプ全体またはシェイプ境界でテクスチャをタイル化する方法を決定するために使用されるラップ モードと色を設定します。テクスチャが塗りつぶしている形状よりも小さい場合、テクスチャは形状全体にタイル張りされて塗りつぶされます. |
| [SetWrapMode](../../aspose.psd/imageattributes/setwrapmode/#setwrapmode_2)(WrapMode, Color, bool) | シェイプ全体またはシェイプ境界でテクスチャをタイル化する方法を決定するために使用されるラップ モードと色を設定します。テクスチャが塗りつぶしている形状よりも小さい場合、テクスチャは形状全体にタイル張りされて塗りつぶされます. |

### 関連項目

* 名前空間 [Aspose.PSD](../../aspose.psd/)
* 組み立て [Aspose.PSD](../../)


