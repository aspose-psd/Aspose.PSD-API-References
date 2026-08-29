---
title: "PathStructure.Prefix"
second_title: "Aspose.PSD for .NET API Reference"
description: "PathStructure プロパティ。パスプレフィックスを取得または設定します。"
type: docs
weight: 50
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/prefix/
---
{{< psd/tize >}}
## PathStructure.Prefix property

パスプレフィックスを取得または設定します。

```csharp
public string Prefix { get; set; }
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


