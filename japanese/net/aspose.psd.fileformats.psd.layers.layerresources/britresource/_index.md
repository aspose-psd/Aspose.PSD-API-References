---
title: "クラス BritResource"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.BritResource クラス。クラス BritResource。明るさ/コントラスト調整レイヤーのリソース"
type: docs
weight: 2600
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources/britresource/
---
{{< psd/tize >}}
## BritResource class

BritResource クラス。Brightness/Contrast Adjustment Layer のリソースです。

```csharp
public class BritResource : AdjustmentLayerResource
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [BritResource](britresource/#constructor)() | `BritResource` クラスの新しいインスタンスを初期化します。 |
| [BritResource](britresource/#constructor_1)(byte[]) | `BritResource` クラスの新しいインスタンスを初期化します。PSD フォーマットの仕様には次の説明が含まれます: 2 明度 2 コントラスト 2 明度とコントラストの平均値 1 ラボカラーのみ。これは、CgEd が使用されている最新の PSD（CS5 以降）では使用されません。CgEd は情報プロパティを保存します。 |
| [BritResource](britresource/#constructor_2)(short, short, short, bool) | `BritResource` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Brightness](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/brightness/) { get; set; } | 明るさを取得または設定します。 |
| [Contrast](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/contrast/) { get; set; } | コントラストを取得または設定します。 |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | レイヤーリソースキーを取得します。 |
| [LabColor](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/labcolor/) { get; set; } | 取得または設定します。 [lab color] かどうかを示す値。 |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/length/) { get; } | レイヤーリソースの長さ（バイト単位）を取得します。 |
| [MeanValueForBrightnessAndContrast](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/meanvalueforbrightnessandcontrast/) { get; set; } | 明るさとコントラストの平均値を取得または設定します。 |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | レイヤーリソースに必要な最小 PSD バージョンを取得します。0 は制限なしを示します。 |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | 署名を取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/save/)(StreamContainer, int) | リソースを指定されたストリームコンテナに保存します。 |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | このインスタンスを表すStringを返します。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/typetoolkey/) | タイプツール情報キーです。 |

### 関連項目

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


