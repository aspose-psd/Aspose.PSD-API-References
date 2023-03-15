---
title: Enum LineCapType
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources.LineCapType 列挙. ラインキャップタイプ.
type: docs
weight: 3040
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/linecaptype/
---
## LineCapType enumeration

ラインキャップタイプ.

```csharp
public enum LineCapType : short
```

### 値

| 名前 | 価値 | 説明 |
| --- | --- | --- |
| RoundCap | `0` | ラウンドキャップタイプ. |
| SquareCap | `1` | スクエアキャップタイプ. |
| ButtCap | `2` | バットキャップタイプ. |

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


