---
title: "クラス ImageAttributes"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.ImageAttributes クラス。ImageAttributes オブジェクトは、ビットマップおよびメタファイルの色がレンダリング中にどのように操作されるかに関する情報を保持します。ImageAttributes オブジェクトは、カラー調整マトリックス、グレースケール調整マトリックス、ガンマ補正値、カラーマップテーブル、カラーしきい値など、複数のカラー調整設定を保持します。レンダリング中に色は補正、暗く、明るく、除去することができます。このような操作を適用するには、ImageAttributes オブジェクトを初期化し、その ImageAttributes オブジェクトのパスと Image のパスを DrawImage メソッドに渡します。"
type: docs
weight: 5080
url: /ja/net/aspose.psd/imageattributes/
---
{{< psd/tize >}}
## ImageAttributes class

`ImageAttributes` オブジェクトは、ビットマップおよびメタファイルの色がレンダリング中にどのように操作されるかに関する情報を保持します。`ImageAttributes` オブジェクトは、カラー調整マトリックス、グレースケール調整マトリックス、ガンマ補正値、カラーマップテーブル、カラーしきい値など、複数のカラー調整設定を保持します。レンダリング中に、色は補正、暗く、明るく、除去することができます。このような操作を適用するには、`ImageAttributes` オブジェクトを初期化し、その `ImageAttributes` オブジェクトのパス（[`Image`](../image/) のパスとともに）を DrawImage メソッドに渡します。

```csharp
public sealed class ImageAttributes
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [ImageAttributes](imageattributes/)() | デフォルトコンストラクタです。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [ClearBrushRemapTable](../../aspose.psd/imageattributes/clearbrushremaptable/)() | この `ImageAttributes` オブジェクトのブラシ カラーリマップ テーブルをクリアします。 |
| [ClearColorKey](../../aspose.psd/imageattributes/clearcolorkey/#clearcolorkey)() | デフォルト カテゴリのカラーキー（透過範囲）をクリアします。 |
| [ClearColorKey](../../aspose.psd/imageattributes/clearcolorkey/#clearcolorkey_1)(ColorAdjustType) | 指定されたカテゴリのカラーキー（透過範囲）をクリアします。 |
| [ClearColorMatrix](../../aspose.psd/imageattributes/clearcolormatrix/#clearcolormatrix)() | デフォルト カテゴリのカラー調整マトリックスをクリアします。 |
| [ClearColorMatrix](../../aspose.psd/imageattributes/clearcolormatrix/#clearcolormatrix_1)(ColorAdjustType) | 指定されたカテゴリのカラー調整マトリックスをクリアします。 |
| [ClearGamma](../../aspose.psd/imageattributes/cleargamma/#cleargamma)() | デフォルト カテゴリのガンマ補正を無効にします。 |
| [ClearGamma](../../aspose.psd/imageattributes/cleargamma/#cleargamma_1)(ColorAdjustType) | 指定されたカテゴリのガンマ補正を無効にします。 |
| [ClearNoOp](../../aspose.psd/imageattributes/clearnoop/#clearnoop)() | デフォルト カテゴリの NoOp 設定をクリアします。 |
| [ClearNoOp](../../aspose.psd/imageattributes/clearnoop/#clearnoop_1)(ColorAdjustType) | 指定されたカテゴリの NoOp 設定をクリアします。 |
| [ClearOutputChannel](../../aspose.psd/imageattributes/clearoutputchannel/#clearoutputchannel)() | デフォルト カテゴリの CMYK（シアン・マゼンタ・イエロー・ブラック）出力チャネル設定をクリアします。 |
| [ClearOutputChannel](../../aspose.psd/imageattributes/clearoutputchannel/#clearoutputchannel_1)(ColorAdjustType) | 指定されたカテゴリの（シアン・マゼンタ・イエロー・ブラック）出力チャネル設定をクリアします。 |
| [ClearOutputChannelColorProfile](../../aspose.psd/imageattributes/clearoutputchannelcolorprofile/#clearoutputchannelcolorprofile)() | デフォルト カテゴリの出力チャネル カラープロファイル設定をクリアします。 |
| [ClearOutputChannelColorProfile](../../aspose.psd/imageattributes/clearoutputchannelcolorprofile/#clearoutputchannelcolorprofile_1)(ColorAdjustType) | 指定されたカテゴリの出力チャネル カラープロファイル設定をクリアします。 |
| [ClearRemapTable](../../aspose.psd/imageattributes/clearremaptable/#clearremaptable)() | デフォルト カテゴリのカラーリマップテーブルをクリアします。 |
| [ClearRemapTable](../../aspose.psd/imageattributes/clearremaptable/#clearremaptable_1)(ColorAdjustType) | 指定されたカテゴリのカラーリマップテーブルをクリアします。 |
| [ClearThreshold](../../aspose.psd/imageattributes/clearthreshold/#clearthreshold)() | デフォルト カテゴリのしきい値をクリアします。 |
| [ClearThreshold](../../aspose.psd/imageattributes/clearthreshold/#clearthreshold_1)(ColorAdjustType) | 指定されたカテゴリのしきい値をクリアします。 |
| [SetBrushRemapTable](../../aspose.psd/imageattributes/setbrushremaptable/)(ColorMap[]) | ブラシ カテゴリのカラーリマップテーブルを設定します。 |
| [SetColorKey](../../aspose.psd/imageattributes/setcolorkey/#setcolorkey)(Color, Color) | デフォルトカテゴリのカラーキーを設定します。 |
| [SetColorKey](../../aspose.psd/imageattributes/setcolorkey/#setcolorkey_1)(Color, Color, ColorAdjustType) | 指定されたカテゴリのカラーキー（透過範囲）を設定します。 |
| [SetColorMatrices](../../aspose.psd/imageattributes/setcolormatrices/#setcolormatrices)(ColorMatrix, ColorMatrix) | デフォルトカテゴリのカラー調整マトリックスとグレースケール調整マトリックスを設定します。 |
| [SetColorMatrices](../../aspose.psd/imageattributes/setcolormatrices/#setcolormatrices_1)(ColorMatrix, ColorMatrix, ColorMatrixFlag) | デフォルトカテゴリのカラー調整マトリックスとグレースケール調整マトリックスを設定します。 |
| [SetColorMatrices](../../aspose.psd/imageattributes/setcolormatrices/#setcolormatrices_2)(ColorMatrix, ColorMatrix, ColorMatrixFlag, ColorAdjustType) | 指定されたカテゴリのカラー調整マトリックスとグレースケール調整マトリックスを設定します。 |
| [SetColorMatrix](../../aspose.psd/imageattributes/setcolormatrix/#setcolormatrix)(ColorMatrix) | デフォルトカテゴリのカラー調整マトリックスを設定します。 |
| [SetColorMatrix](../../aspose.psd/imageattributes/setcolormatrix/#setcolormatrix_1)(ColorMatrix, ColorMatrixFlag) | デフォルトカテゴリのカラー調整マトリックスを設定します。 |
| [SetColorMatrix](../../aspose.psd/imageattributes/setcolormatrix/#setcolormatrix_2)(ColorMatrix, ColorMatrixFlag, ColorAdjustType) | 指定されたカテゴリのカラー調整マトリックスを設定します。 |
| [SetGamma](../../aspose.psd/imageattributes/setgamma/#setgamma)(float) | デフォルトカテゴリのガンマ値を設定します。 |
| [SetGamma](../../aspose.psd/imageattributes/setgamma/#setgamma_1)(float, ColorAdjustType) | 指定されたカテゴリのガンマ値を設定します。 |
| [SetNoOp](../../aspose.psd/imageattributes/setnoop/#setnoop)() | デフォルトカテゴリのカラー調整をオフにします。 |
| [SetNoOp](../../aspose.psd/imageattributes/setnoop/#setnoop_1)(ColorAdjustType) | 指定されたカテゴリのカラー調整をオフにします。 |
| [SetOutputChannel](../../aspose.psd/imageattributes/setoutputchannel/#setoutputchannel)(ColorChannelFlag) | デフォルトカテゴリの CMYK（シアン・マゼンタ・イエロー・ブラック）出力チャンネルを設定します。 |
| [SetOutputChannel](../../aspose.psd/imageattributes/setoutputchannel/#setoutputchannel_1)(ColorChannelFlag, ColorAdjustType) | 指定されたカテゴリの CMYK（シアン・マゼンタ・イエロー・ブラック）出力チャンネルを設定します。 |
| [SetOutputChannelColorProfile](../../aspose.psd/imageattributes/setoutputchannelcolorprofile/#setoutputchannelcolorprofile)(string) | デフォルトカテゴリの出力チャンネル カラープロファイル ファイルを設定します。 |
| [SetOutputChannelColorProfile](../../aspose.psd/imageattributes/setoutputchannelcolorprofile/#setoutputchannelcolorprofile_1)(string, ColorAdjustType) | 指定されたカテゴリの出力チャンネル カラープロファイル ファイルを設定します。 |
| [SetRemapTable](../../aspose.psd/imageattributes/setremaptable/#setremaptable)(ColorMap[]) | デフォルトカテゴリのカラーリマップテーブルを設定します。 |
| [SetRemapTable](../../aspose.psd/imageattributes/setremaptable/#setremaptable_1)(ColorMap[], ColorAdjustType) | 指定されたカテゴリのカラーリマップテーブルを設定します。 |
| [SetThreshold](../../aspose.psd/imageattributes/setthreshold/#setthreshold)(float) | デフォルトカテゴリのしきい値（透過範囲）を設定します。 |
| [SetThreshold](../../aspose.psd/imageattributes/setthreshold/#setthreshold_1)(float, ColorAdjustType) | 指定されたカテゴリのしきい値（透過範囲）を設定します。 |
| [SetWrapMode](../../aspose.psd/imageattributes/setwrapmode/#setwrapmode)(WrapMode) | テクスチャをシェイプ全体またはシェイプの境界でタイル状に配置する方法を決定するために使用されるラップモードを設定します。テクスチャがシェイプより小さい場合、テクスチャはシェイプ全体を埋めるようにタイル状に配置されます。 |
| [SetWrapMode](../../aspose.psd/imageattributes/setwrapmode/#setwrapmode_1)(WrapMode, Color) | テクスチャをシェイプ全体またはシェイプの境界でタイル状に配置する方法を決定するために使用されるラップモードとカラーを設定します。テクスチャがシェイプより小さい場合、テクスチャはシェイプ全体を埋めるようにタイル状に配置されます。 |
| [SetWrapMode](../../aspose.psd/imageattributes/setwrapmode/#setwrapmode_2)(WrapMode, Color, bool) | テクスチャをシェイプ全体またはシェイプの境界でタイル状に配置する方法を決定するために使用されるラップモードとカラーを設定します。テクスチャがシェイプより小さい場合、テクスチャはシェイプ全体を埋めるようにタイル状に配置されます。 |

### 関連項目

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


