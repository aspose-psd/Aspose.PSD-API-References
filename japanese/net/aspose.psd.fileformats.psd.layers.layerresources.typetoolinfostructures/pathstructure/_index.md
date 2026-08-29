---
title: "PathStructure クラス"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures.PathStructure クラス。パス構造です。"
type: docs
weight: 3610
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/
---
{{< psd/tize >}}
## PathStructure class

パス構造です。

```csharp
public sealed class PathStructure : OSTypeStructure
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [PathStructure](pathstructure/)(ClassID) | `PathStructure` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/key/) { get; } | 構造キーを取得します。 |
| [KeyName](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/keyname/) { get; set; } | キー名を取得または設定します。 |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/length/) { get; } | バイト単位で[`OSTypeStructure`](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) の長さを取得します。 |
| [Path](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/path/) { get; set; } | パスを取得または設定します。 |
| [Prefix](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/prefix/) { get; set; } | パスプレフィックスを取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| virtual [GetHeaderLength](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/getheaderlength/)() | ヘッダーの長さを取得します。 |
| [Save](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/save/)(StreamContainer) | 構造体を指定されたストリーム コンテナに保存します。 |
| [SaveWithoutKeyName](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/savewithoutkeyname/)(StreamContainer) | 構造体を指定されたストリーム コンテナに保存します。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| const [StructureKey](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/structurekey/) | 構造キーを識別します。 |

## 例

次のコードは PathStructure 構造を使用してファイルをロードする機能を示しています。

```csharp
[C#]

string srcFile = "shirt-color.psd";
string output = "output.psd";

using (PsdImage image = (PsdImage)Image.Load(srcFile))
{
    image.Save(output);
}
```

### 関連項目

* class [OSTypeStructure](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)
* assembly [Aspose.PSD](../../)


