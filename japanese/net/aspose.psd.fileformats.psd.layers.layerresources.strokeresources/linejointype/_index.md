---
title: "列挙型 LineJoinType"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources.LineJoinType 列挙型。ライン結合タイプ"
type: docs
weight: 3410
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/linejointype/
---
{{< psd/tize >}}
## LineJoinType enumeration

ラインジョインのタイプ。

```csharp
public enum LineJoinType : short
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| BevelJoin | `0` | ベベル結合タイプ。 |
| RoundJoin | `1` | ラウンド結合タイプ。 |
| MiterJoin | `2` | ミタージョインタイプ。 |

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


