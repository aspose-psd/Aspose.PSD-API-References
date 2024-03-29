---
title: RasterCachedImage.Crop
second_title: Aspose.PSD for .NET API 参考
description: RasterCachedImage 方法. 裁剪图像
type: docs
weight: 90
url: /zh/net/aspose.psd/rastercachedimage/crop/
---
## RasterCachedImage.Crop method

裁剪图像。

```csharp
public override void Crop(Rectangle rectangle)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| rectangle | Rectangle | 矩形。 |

### 例子

以下代码演示了按特定矩形裁剪图像的能力。

```csharp
[C#]

string sourceFileName = "SourceFile.psd";
string exportPath = "SourceFileEdited.psd";
string exportPathPng = "SourceFileEdited.png";

using (var image = (PsdImage)Image.Load(sourceFileName))
{
    var oldLayer = image.Layers[0];
    var oldBounds = oldLayer.Bounds;

    var oldLayerData = image.Layers[0].LoadArgb32Pixels(oldBounds);

    var layers = new Layer[4];
    for (int i = 0; i < 4; i++)
    {
        layers[i] = new Layer(
            oldBounds,
            new byte[oldBounds.Width * oldBounds.Height],
            new byte[oldBounds.Width * oldBounds.Height],
            new byte[oldBounds.Width * oldBounds.Height],
            "Layer " + i.ToString());
        layers[i].SaveArgb32Pixels(oldBounds, oldLayerData);
    }

    image.Resize(186, 602);

    layers[0].Crop(new Rectangle(0, 0, 186, 159));
    layers[1].Crop(new Rectangle(186, 0, 186, 159));
    layers[2].Crop(new Rectangle(0, 159, 186, 142));
    layers[3].Crop(new Rectangle(186, 159, 186, 142));

    oldLayer.Dispose();
    image.Layers = layers;

    var top = 0;
    for (int i = 0; i < 4; i++)
    {
        var width = layers[i].Width;
        var height = layers[i].Height;
        layers[i].Left = 0;
        layers[i].Top = top;
        layers[i].Right = width;
        layers[i].Bottom = height + layers[i].Top;
        top += layers[i].Height;
    }

    // 保存psd
    image.Save(exportPath, new PsdOptions());

    // 保存png
    image.Save(exportPathPng, new PngOptions());
}
```

### 也可以看看

* struct [Rectangle](../../rectangle/)
* class [RasterCachedImage](../)
* 命名空间 [Aspose.PSD](../../rastercachedimage/)
* 部件 [Aspose.PSD](../../../)


