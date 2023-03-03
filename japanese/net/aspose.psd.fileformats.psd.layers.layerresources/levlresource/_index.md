---
title: Class LevlResource
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LevlResource クラス. クラスのレベル リソース露出調整レイヤーのリソース
type: docs
weight: 2640
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/
---
## LevlResource class

クラスのレベル リソース。露出調整レイヤーのリソース

```csharp
public class LevlResource : AdjustmentLayerResource
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [LevlResource](levlresource/#constructor)() | の新しいインスタンスを初期化します`LevlResource`class. |
| [LevlResource](levlresource/#constructor_1)(byte[]) | の新しいインスタンスを初期化します`LevlResource` class. グレースケール、デュオトーン、RGB、CMYK、Lab カラー モードでサポート 2 バイト - バージョン (=2) 29 * 10 バイト - 5 つの短い整数を含むレベル レコードのセット 4 バイト - Lvls ヘッダー (292 インデックスで開始) 2 バイト - バージョン (=3) 2 バイト - 合計レベル レコードのカウント 10 * (合計カウント - 29) |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/key/) { get; } | レイヤ リソース キーを取得します。 |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/length/) { get; } | 層リソースの長さをバイト単位で取得します。 |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/psdversion/) { get; } | psd バージョンを取得します。 |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/signature/) { get; } | 署名を取得します。 |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/version/) { get; } | バージョンを取得します。デフォルトは 2 です |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [GetChannel](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/getchannel/)(int) | チャネルを取得します。 |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/save/)(StreamContainer, int) | 指定したストリーム コンテナーにリソースを保存します。 |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | を返しますStringこのインスタンスを表す. |

## 田畑

| 名前 | 説明 |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/typetoolkey/) | タイプ ツール情報キー。 |

### 関連項目

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* 組み立て [Aspose.PSD](../../)


