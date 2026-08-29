---
title: "クラス ClblResource"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.ClblResource クラス。 クラス ClblResource。 このリソースはクリップされた要素のブレンドに関する情報を含みます。"
type: docs
weight: 2630
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/
---
{{< psd/tize >}}
## ClblResource class

ClblResource クラス。このリソースはクリップされた要素のブレンド情報を含みます。

```csharp
public class ClblResource : BooleanResource
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [ClblResource](clblresource/#constructor)() | `ClblResource` クラスの新しいインスタンスを初期化します。 |
| [ClblResource](clblresource/#constructor_1)(bool) | `ClblResource` クラスの新しいインスタンスを初期化します。 |
| [ClblResource](clblresource/#constructor_2)(byte[]) | `ClblResource` クラスの新しいインスタンスを初期化します。 カスタムまたは不明な値の場合 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [BlendClippedElements](../../aspose.psd.fileformats.psd.layers.layerresources/clblresource/blendclippedelements/) { get; set; } | 取得または設定する値は、[blend clipped elements] かどうかを示します。 |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | レイヤーリソースキーを取得します。 |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/booleanresource/length/) { get; } | レイヤーリソースの長さ（バイト単位）を取得します。 |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | レイヤーリソースに必要な最小 PSD バージョンを取得します。0 は制限なしを示します。 |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | 署名を取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/booleanresource/save/)(StreamContainer, int) | 指定されたストリームコンテナを保存します。 |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | このインスタンスを表すStringを返します。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/clblresource/typetoolkey/) | タイプツール情報キーです。 |

### 関連項目

* class [BooleanResource](../booleanresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


