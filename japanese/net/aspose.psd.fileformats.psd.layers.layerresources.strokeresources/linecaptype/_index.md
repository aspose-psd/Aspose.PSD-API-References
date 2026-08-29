---
title: "列挙型 LineCapType"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources.LineCapType 列挙型。ラインキャップの種類"
type: docs
weight: 3400
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/linecaptype/
---
{{< psd/tize >}}
## LineCapType enumeration

ラインキャップのタイプ。

```csharp
public enum LineCapType : short
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| RoundCap | `0` | 丸形キャップの種類。 |
| SquareCap | `1` | 四角形キャップの種類。 |
| ButtCap | `2` | バットキャップの種類。 |

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

* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/)
* assembly [Aspose.PSD](../../)


