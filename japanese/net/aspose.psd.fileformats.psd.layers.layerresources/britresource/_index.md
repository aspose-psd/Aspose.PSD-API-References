---
title: Class BritResource
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.BritResource クラス. クラス BritResource明るさコントラスト調整レイヤーのリソース
type: docs
weight: 2340
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources/britresource/
---
## BritResource class

クラス BritResource。明るさ・コントラスト調整レイヤーのリソース

```csharp
public class BritResource : AdjustmentLayerResource
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [BritResource](britresource/#constructor)() | の新しいインスタンスを初期化します`BritResource`class. |
| [BritResource](britresource/#constructor_1)(byte[]) | の新しいインスタンスを初期化します`BritResource`class. PSD 形式の仕様には次の説明が含まれます: 2 Brightness 2 Contrast 2 輝度とコントラストの平均値 1 Lab color only CgEd が存在する最新の PSD (CS5 以降) では使用されません。 CgEd ストア情報 properties |
| [BritResource](britresource/#constructor_2)(short, short, short, bool) | の新しいインスタンスを初期化します`BritResource`class. |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Brightness](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/brightness/) { get; set; } | 明るさを取得または設定します。 |
| [Contrast](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/contrast/) { get; set; } | コントラストを取得または設定します。 |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/key/) { get; } | レイヤ リソース キーを取得します。 |
| [LabColor](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/labcolor/) { get; set; } | [ラボカラー] かどうかを示す値を取得または設定します。 |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/length/) { get; } | 層リソースの長さをバイト単位で取得します。 |
| [MeanValueForBrightnessAndContrast](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/meanvalueforbrightnessandcontrast/) { get; set; } | 明るさとコントラストの平均値を取得または設定します。 |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/psdversion/) { get; } | psd バージョンを取得します。 |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/signature/) { get; } | 署名を取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/save/)(StreamContainer, int) | 指定したストリーム コンテナーにリソースを保存します。 |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | を返しますStringこのインスタンスを表す. |

## 田畑

| 名前 | 説明 |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/typetoolkey/) | タイプ ツール情報キー。 |

### 関連項目

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* 組み立て [Aspose.PSD](../../)


