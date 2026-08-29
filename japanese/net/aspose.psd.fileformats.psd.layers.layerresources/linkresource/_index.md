---
title: "クラス LinkResource"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LinkResource クラス。PSD 形式画像内のリンクまたは埋め込みファイルに関する情報を含む LinkResource クラスを定義します。リンクリソースは複数の LinkDataSource インスタンスを含む可能性があり、派生クラスのインデクサーでアクセスできます。"
type: docs
weight: 3010
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources/linkresource/
---
{{< psd/tize >}}
## LinkResource class

リンクまたは埋め込みファイルに関する情報を含む LinkResource クラスを定義します。リンクリソースは複数の [`LinkDataSource`](../linkdatasource/) インスタンスを含む可能性があり、派生クラスのインデクサーでアクセスできます。

```csharp
public abstract class LinkResource : LayerResource
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [DataSourceCount](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/datasourcecount/) { get; } | インデクサでアクセスできるリンクデータソースの数を取得します。 |
| [IsEmpty](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/isempty/) { get; } | このリンクリソースインスタンスが空かどうかを示す値を取得します。 |
| [Item](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/item/) { get; } | 指定されたインデックスの [`LinkDataSource`](../linkdatasource/) を取得します。これはリンクデータソースの一意の識別子です。 |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | レイヤーリソースキーを取得します。 |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/length/) { get; } | PSD グローバルリンクリソースの長さ（バイト単位）を取得します。 |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | レイヤーリソースに必要な最小 PSD バージョンを取得します。0 は制限なしを示します。 |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | 署名を取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/save/)(StreamContainer, int) | リソースブロックデータを保存します。 |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | このインスタンスを表すStringを返します。 |

### 関連項目

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


