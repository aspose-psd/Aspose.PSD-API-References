---
title: "クラス PhflResourceVersion2"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.PhflResourceVersion2 クラス。クラス PhflResource。Exposure Adjustment Layer 2 のリソース。Version 3 または Version 2。Version 3 では XYZ カラー用に各 12 バイト、カラースペースは 10 バイトで続いて 4 バイト。Version 2 のみではカラ―コンポーネントが 2 バイト。Density は 4、Preserve Luminosity は 1。"
type: docs
weight: 3250
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/
---
{{< psd/tize >}}
## PhflResourceVersion2 class

PhflResource クラス。Exposure 調整レイヤー 2 のリソース バージョン ( = 3 ) または ( = 2 ) 12 4 バイトずつ XYZ カラー（バージョン 3 のみ） 10 2 バイトのカラースペースに続く 4 * 2 バイトのカラ―コンポーネント（バージョン 2 のみ） 4 密度 1 輝度保持

```csharp
public class PhflResourceVersion2 : PhflResource
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [PhflResourceVersion2](phflresourceversion2/#constructor)() | `PhflResourceVersion2` クラスの新しいインスタンスを初期化します。 |
| [PhflResourceVersion2](phflresourceversion2/#constructor_1)(byte[]) | `PhflResourceVersion2` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [ColorSpace](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/colorspace/) { get; } | カラースペースを取得します。 |
| [ComponentA](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/componenta/) { get; set; } | 色の A コンポーネントを取得または設定します。 |
| [ComponentB](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/componentb/) { get; set; } | B コンポーネントを取得または設定します。 |
| [ComponentL](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/componentl/) { get; set; } | 色の L コンポーネントを取得または設定します。 |
| [Density](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/density/) { get; set; } | 密度を取得または設定します。 |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | レイヤーリソースキーを取得します。 |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/length/) { get; } | レイヤーリソースの長さ（バイト単位）を取得します。 |
| [PreserveLuminosity](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/preserveluminosity/) { get; set; } | [preserve luminosity] を示すかどうかの値を取得または設定します。 |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | レイヤーリソースに必要な最小 PSD バージョンを取得します。0 は制限なしを示します。 |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | 署名を取得します。 |
| override [Version](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/version/) { get; } | バージョンを取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [GetRgbColor](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/getrgbcolor/)() | 色を取得します。 |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/save/)(StreamContainer, int) | リソースを指定されたストリームコンテナに保存します。 |
| override [SetRgbColor](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/setrgbcolor/)(Color) | RGB カラーを設定します。 |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | このインスタンスを表すStringを返します。 |

### 関連項目

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [PhflResource](../phflresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


