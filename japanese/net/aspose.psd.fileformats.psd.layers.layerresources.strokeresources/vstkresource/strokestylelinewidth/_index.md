---
title: "VstkResource.StrokeStyleLineWidth"
second_title: "Aspose.PSD for .NET API Reference"
description: "VstkResource プロパティ。ストロークライン幅を取得または設定します"
type: docs
weight: 140
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestylelinewidth/
---
{{< psd/tize >}}
## VstkResource.StrokeStyleLineWidth property

ストロークライン幅を取得または設定します。

```csharp
public double StrokeStyleLineWidth { get; set; }
```

## 例

次のコードは VstkResource リソースのサポートを示しています。

```csharp
[C#]

string srcFile = "StrokeShapeTest1.psd";
string dstFile = "StrokeShapeTest2.psd";

using (PsdImage image = (PsdImage)Image.Load(srcFile))
{
    Layer layer = image.Layers[1];
    foreach (LayerResource resource in layer.Resources)
    {
        if (resource is VstkResource)
        {
            VstkResource vstkResource = (VstkResource)resource;
            vstkResource.StrokeStyleLineAlignment = StrokePosition.Outside;
            vstkResource.StrokeStyleLineWidth = 20;
        }
    }

    image.Save(dstFile);
}
```

### 関連項目

* class [VstkResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources](../../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/)
* assembly [Aspose.PSD](../../../)


