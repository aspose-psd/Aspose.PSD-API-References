---
title: Class Lnk2Resource
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.Lnk2Resource クラス. PSD 形式の画像に埋め込まれたファイルに関する情報を含むクラスを定義します リンク リソースには複数のLiFdDataSourceインデクサーがアクセスできるインスタンス.
type: docs
weight: 2720
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources/lnk2resource/
---
## Lnk2Resource class

PSD 形式の画像に埋め込まれたファイルに関する情報を含むクラスを定義します。 リンク リソースには複数の[`LiFdDataSource`](../lifddatasource/)インデクサーがアクセスできるインスタンス.

```csharp
public class Lnk2Resource : LinkResource
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [Lnk2Resource](lnk2resource/)() | の新しいインスタンスを初期化します`Lnk2Resource`class. |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [DataSourceCount](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/datasourcecount/) { get; } | インデクサーがアクセスできるリンク データ ソースの数を取得します。 |
| [IsEmpty](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/isempty/) { get; } | このリンク リソース インスタンスが空かどうかを示す値を取得します。 |
| [Item](../../aspose.psd.fileformats.psd.layers.layerresources/lnk2resource/item/) { get; } | を取得します[`LiFdDataSource`](../lifddatasource/)指定されたインデックスで. (2 indexers) |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/lnk2resource/key/) { get; } | レイヤ リソース キーを取得します。 |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/length/) { get; } | PSD グローバル リンク リソースの長さをバイト単位で取得します。 |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/psdversion/) { get; } | PSD 形式のバージョンを取得します。 |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/signature/) { get; } | PSD グローバル リンク リソース署名を取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/save/)(StreamContainer, int) | リソースブロックデータを保存します。 |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | を返しますStringこのインスタンスを表す. |

## 田畑

| 名前 | 説明 |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/lnk2resource/typetoolkey/) | タイプ ツール情報キー。 |

### 関連項目

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [LinkResource](../linkresource/)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* 組み立て [Aspose.PSD](../../)


