---
title: PathStructure.Length
second_title: Aspose.PSD for .NET API リファレンス
description: PathStructure 財産. を取得しますOSTypeStructureバイト単位の長さ.
type: docs
weight: 30
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/length/
---
## PathStructure.Length property

を取得します[`OSTypeStructure`](../../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/)バイト単位の長さ.

```csharp
public override int Length { get; }
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


