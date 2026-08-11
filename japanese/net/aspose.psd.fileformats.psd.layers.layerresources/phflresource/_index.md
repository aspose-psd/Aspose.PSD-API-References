---
title: "クラス PhflResource"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.PhflResource クラス。クラス PhflResource。露光調整レイヤー 2 のリソース。バージョン 3 または 2。XYZ カラー用に各 12 4 バイト（バージョン 3 のみ）。10 バイトのカラースペースに続く 4 バイトのカラ―コンポーネント（バージョン 2 のみ）。Density は 4、Preserve Luminosity は 1"
type: docs
weight: 3240
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources/phflresource/
---
{{< psd/tize >}}
## PhflResource class

PhflResource クラス。Exposure 調整レイヤー 2 のリソース バージョン ( = 3 ) または ( = 2 ) 12 4 バイトずつ XYZ カラー（バージョン 3 のみ） 10 2 バイトのカラースペースに続く 4 * 2 バイトのカラ―コンポーネント（バージョン 2 のみ） 4 密度 1 輝度保持

```csharp
public abstract class PhflResource : AdjustmentLayerResource
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Density](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/density/) { get; set; } | 密度を取得または設定します。 |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | レイヤーリソースキーを取得します。 |
| abstract [Length](../../aspose.psd.fileformats.psd.layers/layerresource/length/) { get; } | レイヤーリソースの長さ（バイト単位）を取得します。 |
| [PreserveLuminosity](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/preserveluminosity/) { get; set; } | [preserve luminosity] を示すかどうかの値を取得または設定します。 |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | レイヤーリソースに必要な最小 PSD バージョンを取得します。0 は制限なしを示します。 |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | 署名を取得します。 |
| abstract [Version](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/version/) { get; } | バージョンを取得します。デフォルトは 2 または 3 です。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| abstract [GetRgbColor](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/getrgbcolor/)() | RGB の色を取得します。 |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/save/)(StreamContainer, int) | リソースを指定されたストリームコンテナに保存します。 |
| abstract [SetRgbColor](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/setrgbcolor/)(Color) | RGB カラーを設定します。 |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | このインスタンスを表すStringを返します。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/typetoolkey/) | タイプツール情報キーです。 |

### 関連項目

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


