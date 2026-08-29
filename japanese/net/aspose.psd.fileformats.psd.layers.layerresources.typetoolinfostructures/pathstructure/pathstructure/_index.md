---
title: "PathStructure.PathStructure"
second_title: "Aspose.PSD for .NET API Reference"
description: "PathStructure コンストラクタ。PathStructure クラスの新しいインスタンスを初期化します。"
type: docs
weight: 10
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/pathstructure/
---
{{< psd/tize >}}
## PathStructure constructor

[`PathStructure`](../) クラスの新しいインスタンスを初期化します。

```csharp
public PathStructure(ClassID keyName)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| keyName | ClassID | キー名。 |

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

* class [ClassID](../../../aspose.psd.fileformats.psd.layers.layerresources/classid/)
* class [PathStructure](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)
* assembly [Aspose.PSD](../../../)


