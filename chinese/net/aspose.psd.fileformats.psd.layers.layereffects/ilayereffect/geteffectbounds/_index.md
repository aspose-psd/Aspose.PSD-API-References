---
title: "ILayerEffect.GetEffectBounds"
second_title: "Aspose.PSD for .NET API 参考"
description: "ILayerEffect 方法。根据输入图层像素边界计算并获取效果像素的边界"
type: docs
weight: 50
url: /zh/net/aspose.psd.fileformats.psd.layers.layereffects/ilayereffect/geteffectbounds/
---
{{< psd/tize >}}
## ILayerEffect.GetEffectBounds method

计算并获取基于输入图层像素边界的效果像素边界。

```csharp
public Rectangle GetEffectBounds(Rectangle layerBounds, int globalAngle)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| layerBounds | Rectangle | 图层像素的边界。 |
| globalAngle | Int32 | 用于计算全局光照角度的全局角度。 |

### 返回值

基于输入图层像素边界的效果像素边界。

## 示例

演示如何获取带有效果的图层边界并以正确的尺寸导出。

```csharp
[C#]

string srcFile = "1958.psd";
string outputFile = "out_1958.png";

using (var psdImage = (PsdImage)Image.Load(srcFile, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    var layer1 = psdImage.Layers[1];

    var layerBoudns = layer1.Bounds;
    foreach (var effect in layer1.BlendingOptions.Effects)
    {
        layerBoudns = Rectangle.Union(
            layerBoudns,
            effect.GetEffectBounds(layer1.Bounds, psdImage.GlobalAngle));
    }

    Rectangle boundsToExport = Rectangle.Empty; // The default value is to save only the layer with effects.
                                                // boundsToExport = psdImage.Bounds; // 在原始图层位置的 PsdImage 边界内保存

    layer1.Save(
        outputFile,
        new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha },
        boundsToExport);

    using (var imgStream = new FileStream(outputFile, FileMode.Open))
    {
        var loadedLayer = new Layer(imgStream);
        if (loadedLayer.Size == layerBoudns.Size)
        {
            System.Console.WriteLine("The size is calculated correctly.");
        }
    }
}
```

### 另请参阅

* struct [Rectangle](../../../aspose.psd/rectangle/)
* interface [ILayerEffect](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)


