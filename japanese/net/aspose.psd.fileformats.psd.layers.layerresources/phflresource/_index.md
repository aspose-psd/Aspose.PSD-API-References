---
title: Class PhflResource
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.PhflResource クラス. クラス PhflResource露出調整のリソース Layer 2 バージョン   3  または   2  12 XYZ 色ごとに 4 バイト バージョン 3 のみ 10 2 バイトの色空間の後に 4  2 バイトの色コンポーネント バージョン 2 のみ 4 Density 1 明るさを保持
type: docs
weight: 2890
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources/phflresource/
---
## PhflResource class

クラス PhflResource。露出調整のリソース Layer 2 バージョン ( = 3 ) または ( = 2 ) 12 XYZ 色ごとに 4 バイト (バージョン 3 のみ) 10 2 バイトの色空間の後に 4 * 2 バイトの色コンポーネント (バージョン 2 のみ) 4 Density 1 明るさを保持

```csharp
public abstract class PhflResource : AdjustmentLayerResource
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Density](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/density/) { get; set; } | 密度を取得または設定します。 |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/key/) { get; } | レイヤ リソース キーを取得します。 |
| abstract [Length](../../aspose.psd.fileformats.psd.layers/layerresource/length/) { get; } | 層リソースの長さをバイト単位で取得します。 |
| [PreserveLuminosity](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/preserveluminosity/) { get; set; } | [明るさを維持する]かどうかを示す値を取得または設定します。 |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/psdversion/) { get; } | psd バージョンを取得します。 |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/signature/) { get; } | 署名を取得します。 |
| abstract [Version](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/version/) { get; } | バージョンを取得します。デフォルトは 2 または 3 です |

## メソッド

| 名前 | 説明 |
| --- | --- |
| abstract [GetRgbColor](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/getrgbcolor/)() | RGB の色を取得します。 |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/save/)(StreamContainer, int) | 指定したストリーム コンテナーにリソースを保存します。 |
| abstract [SetRgbColor](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/setrgbcolor/)(Color) | RGB カラーを設定します。 |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | を返しますStringこのインスタンスを表す. |

## 田畑

| 名前 | 説明 |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/typetoolkey/) | タイプ ツール情報キー。 |

### 関連項目

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* 組み立て [Aspose.PSD](../../)


