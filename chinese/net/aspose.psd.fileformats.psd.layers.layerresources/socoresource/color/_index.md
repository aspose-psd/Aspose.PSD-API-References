---
title: SoCoResource.Color
second_title: Aspose.PSD for .NET API 参考
description: SoCoResource 财产. 获取 RGB 颜色 .
type: docs
weight: 20
url: /zh/net/aspose.psd.fileformats.psd.layers.layerresources/socoresource/color/
---
## SoCoResource.Color property

获取 RGB 颜色 .

```csharp
public Color Color { get; set; }
```

### 返回值

RGB 颜色

### 例子

以下示例演示如何编辑 SoCoResource（颜色填充图层的图层资源）

```csharp
[C#]

string sourceFile = "ColorFillLayer.psd";
string outputFile = "SoCoResource_Edited.psd";

// 将现有图像加载到 PsdImage 类的实例中
var im = (PsdImage)Image.Load(sourceFile);

using (im)
{
    foreach (var layer in im.Layers)
    {
        // FillLayer 的查找
        if (layer is FillLayer)
        {
            var fillLayer = (FillLayer)layer;
            foreach (var resource in fillLayer.Resources)
            {
                // 在图层资源列表中查找SoCoResource
                if (resource is SoCoResource)
                {
                    var socoResource = (SoCoResource)resource;
                    var expectedColor = Color.FromArgb(63, 83, 141);
                    
                    if ((expectedColor.R != socoResource.Color.R) ||
                        (expectedColor.G != socoResource.Color.G) ||
                        (expectedColor.B != socoResource.Color.B) ||
                        (expectedColor.A != socoResource.Color.A))
                    {
                        throw new Exception("Unexpected color");
                    }

                    // 设置 SoCoResource 颜色属性
                    socoResource.Color = Color.Red;
                    break;
                }
            }
            break;
        }
        im.Save(outputFile);
    }
}
```

### 也可以看看

* struct [Color](../../../aspose.psd/color/)
* class [SoCoResource](../)
* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../socoresource/)
* 部件 [Aspose.PSD](../../../)


