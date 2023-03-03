---
title: Class MixrResource
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.MixrResource クラス. クラス MixrResource Channel Mixer調整のリソース Layer
type: docs
weight: 2820
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/
---
## MixrResource class

クラス MixrResource。 Channel Mixer調整のリソース Layer

```csharp
public sealed class MixrResource : AdjustmentLayerResource
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [MixrResource](mixrresource/#constructor)() | の新しいインスタンスを初期化します`MixrResource` class. PSD 形式の仕様には、次の説明が含まれます。 2 バージョン ( = 1) 2 Monochrome 20 RGB または CMYK カラーとミキサー設定の定数。 4 * 2 バイトの定数を含む 2 バイトの色。 |
| [MixrResource](mixrresource/#constructor_1)(byte[]) | の新しいインスタンスを初期化します`MixrResource` class. PSD 形式の仕様には、次の説明が含まれます。 2 バージョン ( = 1) 2 Monochrome 20 RGB または CMYK カラーとミキサー設定の定数。 4 * 2 バイトの定数を含む 2 バイトの色。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/key/) { get; } | レイヤ リソース キーを取得します。 |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/length/) { get; } | 層リソースの長さをバイト単位で取得します。 |
| [Monochrome](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/monochrome/) { get; set; } | これが`MixrResource`モノクロです. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/psdversion/) { get; } | psd バージョンを取得します。 |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/signature/) { get; } | 署名を取得します。 |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/version/) { get; set; } | バージョンを取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [GetChannelInfo](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/getchannelinfo/)(int) | チャネル情報の生データを取得 |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/save/)(StreamContainer, int) | 指定したストリーム コンテナーにリソースを保存します。 |
| [SetChannelInfo](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/setchannelinfo/)(int, byte[]) | チャネル情報を設定します。 |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | を返しますStringこのインスタンスを表す. |

## 田畑

| 名前 | 説明 |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/typetoolkey/) | タイプ ツール情報キー。 |

### 関連項目

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* 組み立て [Aspose.PSD](../../)


