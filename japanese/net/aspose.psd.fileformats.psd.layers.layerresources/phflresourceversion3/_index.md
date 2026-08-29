---
title: "クラス PhflResourceVersion3"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.PhflResourceVersion3 クラス。クラス PhflResource。露光調整レイヤー 2 のリソース。バージョン 3 または 2。XYZ カラーごとに 12 4 バイト（バージョン 3 のみ）10 2 バイトのカラースペースに続く 4 2 バイトのカラ―コンポーネント（バージョン 2 のみ）4 密度 1 ルミナンスを保持"
type: docs
weight: 3260
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/
---
{{< psd/tize >}}
## PhflResourceVersion3 class

PhflResource クラス。Exposure 調整レイヤー 2 のリソース バージョン ( = 3 ) または ( = 2 ) 12 4 バイトずつ XYZ カラー（バージョン 3 のみ） 10 2 バイトのカラースペースに続く 4 * 2 バイトのカラ―コンポーネント（バージョン 2 のみ） 4 密度 1 輝度保持

```csharp
public class PhflResourceVersion3 : PhflResource
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [PhflResourceVersion3](phflresourceversion3/#constructor)() | `PhflResourceVersion3` クラスの新しいインスタンスを初期化します。 |
| [PhflResourceVersion3](phflresourceversion3/#constructor_1)(byte[]) | `PhflResourceVersion3` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [ColorSpace](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/colorspace/) { get; } | カラースペースを取得します。 |
| [ColorX](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/colorx/) { get; set; } | X カラーを取得または設定します。 |
| [ColorY](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/colory/) { get; set; } | Y カラーを取得または設定します。 |
| [ColorZ](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/colorz/) { get; set; } | Z カラーを取得または設定します。 |
| [Density](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/density/) { get; set; } | 密度を取得または設定します。 |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | レイヤーリソースキーを取得します。 |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/length/) { get; } | レイヤーリソースの長さ（バイト単位）を取得します。 |
| [PreserveLuminosity](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/preserveluminosity/) { get; set; } | [preserve luminosity] を示すかどうかの値を取得または設定します。 |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | レイヤーリソースに必要な最小 PSD バージョンを取得します。0 は制限なしを示します。 |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | 署名を取得します。 |
| override [Version](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/version/) { get; } | バージョンを取得します。デフォルトは 2 または 3 です。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [GetRgbColor](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/getrgbcolor/)() | 色を取得します。 |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/save/)(StreamContainer, int) | リソースを指定されたストリームコンテナに保存します。 |
| override [SetRgbColor](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/setrgbcolor/)(Color) | RGB カラーを設定します。 |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | このインスタンスを表すStringを返します。 |

### 関連項目

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [PhflResource](../phflresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


