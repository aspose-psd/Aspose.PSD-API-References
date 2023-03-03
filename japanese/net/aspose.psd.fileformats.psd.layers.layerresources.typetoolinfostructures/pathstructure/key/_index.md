---
title: PathStructure.Key
second_title: Aspose.PSD for .NET API リファレンス
description: PathStructure 財産. 構造キーを取得します
type: docs
weight: 20
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/key/
---
## PathStructure.Key property

構造キーを取得します。

```csharp
public override int Key { get; }
```

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

* class [PathStructure](../)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../pathstructure/)
* 組み立て [Aspose.PSD](../../../)


