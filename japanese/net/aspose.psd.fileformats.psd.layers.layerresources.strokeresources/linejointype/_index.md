---
title: Enum LineJoinType
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources.LineJoinType 列挙. 線結合タイプ.
type: docs
weight: 3050
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/linejointype/
---
## LineJoinType enumeration

線結合タイプ.

```csharp
public enum LineJoinType : short
```

### 値

| 名前 | 価値 | 説明 |
| --- | --- | --- |
| BevelJoin | `0` | ベベル結合タイプ. |
| RoundJoin | `1` | 丸め結合タイプ. |
| MiterJoin | `2` | マイター結合タイプ. |

### 例

次のコードは、VstkResource リソースのサポートを示しています。

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

* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/)
* 組み立て [Aspose.PSD](../../)


