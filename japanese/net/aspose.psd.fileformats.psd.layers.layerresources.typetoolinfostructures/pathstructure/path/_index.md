---
title: "PathStructure.Path"
second_title: "Aspose.PSD for .NET API Reference"
description: "PathStructure プロパティ。パスを取得または設定します"
type: docs
weight: 40
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/path/
---
{{< psd/tize >}}
## PathStructure.Path property

パスを取得または設定します。

```csharp
public string Path { get; set; }
```

### Property Value

完全なパスです。

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

* class [PathStructure](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)
* assembly [Aspose.PSD](../../../)


