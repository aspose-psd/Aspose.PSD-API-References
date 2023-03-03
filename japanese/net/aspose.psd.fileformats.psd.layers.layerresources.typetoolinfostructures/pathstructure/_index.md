---
title: Class PathStructure
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures.PathStructure クラス. パス構造
type: docs
weight: 3220
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/
---
## PathStructure class

パス構造。

```csharp
public sealed class PathStructure : OSTypeStructure
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [PathStructure](pathstructure/)(ClassID) | の新しいインスタンスを初期化します`PathStructure`class. |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/key/) { get; } | 構造キーを取得します。 |
| [KeyName](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/keyname/) { get; set; } | キー名を取得または設定します。 |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/length/) { get; } | を取得します[`OSTypeStructure`](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/)バイト単位の長さ. |
| [Path](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/path/) { get; set; } | パスを取得または設定します。 |
| [Prefix](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/prefix/) { get; set; } | パスのプレフィックスを取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| virtual [GetHeaderLength](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/getheaderlength/)() | ヘッダー長を取得します。 |
| [Save](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/save/)(StreamContainer) | 指定したストリーム コンテナーに構造体を保存します。 |
| [SaveWithoutKeyName](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/savewithoutkeyname/)(StreamContainer) | 指定したストリーム コンテナーに構造体を保存します。 |

## 田畑

| 名前 | 説明 |
| --- | --- |
| const [StructureKey](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/structurekey/) | 構造キーを識別します。 |

### 例

次のコードは、PathStructure 構造を持つファイルをロードする機能を示しています。

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
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)
* 組み立て [Aspose.PSD](../../)


