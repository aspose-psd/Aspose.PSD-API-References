---
title: VstkResource.StrokeStyleLineWidth
second_title: Aspose.PSD for .NET API リファレンス
description: VstkResource 財産. ストロークの線幅を取得または設定します
type: docs
weight: 160
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestylelinewidth/
---
## VstkResource.StrokeStyleLineWidth property

ストロークの線幅を取得または設定します。

```csharp
public double StrokeStyleLineWidth { get; set; }
```

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

* class [VstkResource](../)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources](../../vstkresource/)
* 組み立て [Aspose.PSD](../../../)


