---
title: PathStructure.Path
second_title: Aspose.PSD for .NET API リファレンス
description: PathStructure 財産. パスを取得または設定します
type: docs
weight: 40
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/path/
---
## PathStructure.Path property

パスを取得または設定します。

```csharp
public string Path { get; set; }
```

### プロパティ値

フルパス.

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


