---
title: Class LinkResource
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LinkResource クラス. PSD 形式の画像にリンクまたは埋め込まれたファイルに関する情報を含む LinkResource クラスを定義しますLinkDataSource任意の派生クラスのインデクサーからアクセスできるインスタンス.
type: docs
weight: 2710
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources/linkresource/
---
## LinkResource class

PSD 形式の画像にリンクまたは埋め込まれたファイルに関する情報を含む LinkResource クラスを定義します。[`LinkDataSource`](../linkdatasource/)任意の派生クラスのインデクサーからアクセスできるインスタンス.

```csharp
public abstract class LinkResource : LayerResource
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [DataSourceCount](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/datasourcecount/) { get; } | インデクサーがアクセスできるリンク データ ソースの数を取得します。 |
| [IsEmpty](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/isempty/) { get; } | このリンク リソース インスタンスが空かどうかを示す値を取得します。 |
| [Item](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/item/) { get; } | を取得します[`LinkDataSource`](../linkdatasource/)リンクデータソースの一意の識別子である指定されたインデックス.. |
| abstract [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | レイヤ リソース キーを取得します。 |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/length/) { get; } | PSD グローバル リンク リソースの長さをバイト単位で取得します。 |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/psdversion/) { get; } | PSD 形式のバージョンを取得します。 |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/signature/) { get; } | PSD グローバル リンク リソース署名を取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/save/)(StreamContainer, int) | リソースブロックデータを保存します。 |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | を返しますStringこのインスタンスを表す. |

### 関連項目

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* 組み立て [Aspose.PSD](../../)


