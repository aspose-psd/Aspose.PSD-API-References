---
title: Class CurvResource
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.CurvResource クラス. クラス CurvResourceカーブ調整のリソース Layer 1 バイト  カーブを使用する場合は 0マップ上のピクセルを使用する場合は 1 0 の場合 2 バイト  ショートデフォルトは 1 4 バイト  int です最後のバイトのみをビット単位で使用最初のビットは 1 チャンネル4 チャンネルの場合は 4 番目のビットです Curves 4 バイト  int の短いデフォルトは 4 ですデフォルトは 1 4 バイト  ポイント数 4 バイト  ポイント数  曲線 2 のポイント 短い 最初の位置2 番目の高さ 0 から 4 バイト  フォーフォーの折り畳みにつながる 1 の場合 2 バイト  短いデフォルトは 1 4 バイト  int です最後のバイトのみ使用 1 チャネルは 1 ビットです最初のビットは 1 チャンネル用4 番目のビットは 4 チャンネル用ですデフォルトは map 上のピクセルの 3 です 4 バイト  int Channel count 2  256 バイト  チャネル インデックスの短い 2256 は範囲 0 から 255 のチャネルの順序付けられた値です
type: docs
weight: 2400
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/
---
## CurvResource class

クラス CurvResource。カーブ調整のリソース Layer 1 バイト - カーブを使用する場合は 0、マップ上のピクセルを使用する場合は 1 0 の場合: 2 バイト - ショート。デフォルトは 1 4 バイト - int です。最後のバイトのみをビット単位で使用。最初のビットは 1 チャンネル、4 チャンネルの場合は 4 番目のビットです。 Curves 4 バイト - int の短いデフォルトは 4 です。デフォルトは 1 4 バイト - ポイント数 4 バイト * ポイント数 - 曲線 2 のポイント 短い: 最初の位置、2 番目の高さ 0 から 4 バイト - フォーフォーの折り畳みにつながる 1 の場合: 2 バイト - 短い。デフォルトは 1 4 バイト - int です。最後のバイトのみ使用。 1 チャネルは 1 ビットです。最初のビットは 1 チャンネル用、4 番目のビットは 4 チャンネル用です。デフォルトは map 上のピクセルの 3 です 4 バイト - int Channel count (2 + 256) バイト - チャネル インデックスの短い 2、256 は範囲 0 から 255 のチャネルの順序付けられた値です

```csharp
public class CurvResource : AdjustmentLayerResource
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [CurvResource](curvresource/#constructor)(byte[]) | の新しいインスタンスを初期化します`CurvResource`class. |
| [CurvResource](curvresource/#constructor_1)(int) | の新しいインスタンスを初期化します`CurvResource`class. |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [IsDataStoredDiscretely](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/isdatastoreddiscretely/) { get; set; } | このインスタンスが個別に格納されたデータであるかどうかを示す値を取得または設定します。 |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/key/) { get; } | レイヤ リソース キーを取得します。 |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/length/) { get; } | 層リソースの長さをバイト単位で取得します。 |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/psdversion/) { get; } | psd バージョンを取得します。 |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/signature/) { get; } | 署名を取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [GetActiveManager](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/getactivemanager/)() | アクティブなマネージャを取得します。 |
| [GetChannelData](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/getchanneldata/)(int) | チャネルデータを取得します。 |
| [GetCurveManager](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/getcurvemanager/)() | カーブ マネージャを取得します。 |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/save/)(StreamContainer, int) | 指定したストリーム コンテナーにリソースを保存します。 |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | を返しますStringこのインスタンスを表す. |

## 田畑

| 名前 | 説明 |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/typetoolkey/) | タイプ ツール情報キー。 |

### 関連項目

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* 組み立て [Aspose.PSD](../../)


