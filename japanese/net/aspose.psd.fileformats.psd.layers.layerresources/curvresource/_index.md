---
title: "クラス CurvResource"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.CurvResource クラス。クラス CurvResource。カーブ調整レイヤーのリソースです。1 バイト - カーブを使用する場合は 0、マップ上のピクセルを使用する場合は 1。0 の場合は 2 バイトの short。デフォルトは 1。4 バイトの int。ビット単位で最後のバイトのみ使用されます。最初のビットは 1 チャネル用、4 番目のビットは 4 チャネル用です。例として、2 バイトの short はポイント数、4 バイトはポイントの数、カーブのポイントは 2 つの short（最初の位置と高さ）で表されます。4 バイトの word Crv。2 バイトの short はカーブのデフォルトが 4。4 バイトの int はデフォルトが 1。4 バイトの point count、4 バイトの point count、カーブのポイントは 2 short（最初の位置と高さ）。04 バイトは 4 に折りたたむため、1 の場合は 2 バイトの short。デフォルトは 1。4 バイトの int は最後のバイトのみ使用されます。1 チャネルは 1 ビット、4 チャネルは 4 ビットです。例として、256 は変更されたチャネル数、0〜255 の範囲のチャネルの順序付けられた値です。4 バイトの word Crv。2 バイトの short はマップ上のピクセルのデフォルトが 3。4 バイトの int はチャネル数。2、256 バイトの short はチャネルインデックス 2 用、256 は 0〜255 の範囲のチャネルの順序付けられた値です。"
type: docs
weight: 2660
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/
---
{{< psd/tize >}}
## CurvResource class

CurvResource クラス。Curves Adjustment Layer のリソースです。1 バイト - 曲線を使用する場合は 0、ピクセルマップを使用する場合は 1。0 の場合は: 2 バイト - short。デフォルトは 1。4 バイト - int。ビットで最後のバイトのみ使用されます。最初のビットは 1 チャンネル用、4 番目のビットは 4 チャンネル用です。例: 2 バイト - short、ポイント数。4 バイト * ポイント数 - カーブのポイント。2 short: 最初の位置、2 番目の高さ。4 バイト - word \"Crv \"。2 バイト - short、デフォルトは Curves の場合 4。4 バイト - int。デフォルトは 1。4 バイト - ポイント数。4 バイト * ポイント数 - カーブのポイント。2 short: 最初の位置、2 番目の高さ。0-4 バイト - 4 つの場合は折りたたみになる。1 の場合は: 2 バイト - short。デフォルトは 1。4 バイト - int。最後のバイトのみ使用されます。1 チャンネルは 1 ビットに、4 チャンネルは 4 ビットに割り当てられます。例: 256 * 変更されたチャンネル数 - 0 から 255 の範囲のチャンネル順序値。4 バイト - word \"Crv \"。2 バイト - short、デフォルトはピクセルマップの場合 3。4 バイト - int、チャンネル数 (2 + 256) バイト - short、2 はチャンネルインデックス、256 は 0 から 255 の範囲のチャンネル順序値です。

```csharp
public class CurvResource : AdjustmentLayerResource
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [CurvResource](curvresource/#constructor)(byte[]) | `CurvResource` クラスの新しいインスタンスを初期化します。 |
| [CurvResource](curvresource/#constructor_1)(int) | `CurvResource` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [IsDataStoredDiscretely](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/isdatastoreddiscretely/) { get; set; } | 取得または設定します。このインスタンスが離散的にデータが保存されているかどうかを示す値。 |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | レイヤーリソースキーを取得します。 |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/length/) { get; } | レイヤーリソースの長さ（バイト単位）を取得します。 |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | レイヤーリソースに必要な最小 PSD バージョンを取得します。0 は制限なしを示します。 |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | 署名を取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [GetActiveManager](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/getactivemanager/)() | アクティブなマネージャーを取得します。 |
| [GetChannelData](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/getchanneldata/)(int) | チャネルデータを取得します。 |
| [GetCurveManager](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/getcurvemanager/)() | 曲線マネージャーを取得します。 |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/save/)(StreamContainer, int) | リソースを指定されたストリームコンテナに保存します。 |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | このインスタンスを表すStringを返します。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/typetoolkey/) | タイプツール情報キーです。 |

### 関連項目

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


