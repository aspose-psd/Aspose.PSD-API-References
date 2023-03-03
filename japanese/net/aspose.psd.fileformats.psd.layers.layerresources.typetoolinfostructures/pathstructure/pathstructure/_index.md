---
title: PathStructure.PathStructure
second_title: Aspose.PSD for .NET API リファレンス
description: PathStructure コンストラクタ. の新しいインスタンスを初期化しますPathStructureclass.
type: docs
weight: 10
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/pathstructure/
---
## PathStructure constructor

の新しいインスタンスを初期化します[`PathStructure`](../)class.

```csharp
public PathStructure(ClassID keyName)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| keyName | ClassID | キー名。 |

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

* class [ClassID](../../../aspose.psd.fileformats.psd.layers.layerresources/classid/)
* class [PathStructure](../)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../pathstructure/)
* 組み立て [Aspose.PSD](../../../)


