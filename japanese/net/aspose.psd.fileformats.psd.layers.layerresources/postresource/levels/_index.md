---
title: "PostResource.Levels"
second_title: "Aspose.PSD for .NET API Reference"
description: "PostResource プロパティ。ポスタライズレイヤーのレベル"
type: docs
weight: 30
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources/postresource/levels/
---
{{< psd/tize >}}
## PostResource.Levels property

Posterize レイヤーのレベル。

```csharp
public short Levels { get; set; }
```

### 戻り値

Levels 整数値

## 例

以下のコードは PostResource の操作機能を示しています。

```csharp
[C#]

string sourceFile = "zendeya_posterize.psd";
string outputFile = "zendeya_posterize_10.psd";

using (var image = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions()))
{
    Layer layer = image.Layers[1];

    foreach (LayerResource resource in layer.Resources)
    {
        if (resource is PostResource)
        {
            ((PostResource)resource).Levels = 10;
            image.Save(outputFile);

            break;
        }
    }
}
```

### 関連項目

* class [PostResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


