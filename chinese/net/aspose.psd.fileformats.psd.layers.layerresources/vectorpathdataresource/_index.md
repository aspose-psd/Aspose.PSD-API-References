---
title: Class VectorPathDataResource
second_title: Aspose.PSD for .NET API 参考
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.VectorPathDataResource 班级. Class VectorPathDataResource. 此资源包含有关矢量图层掩码 的信息
type: docs
weight: 3340
url: /zh/net/aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/
---
## VectorPathDataResource class

Class VectorPathDataResource. 此资源包含有关矢量图层掩码 的信息

```csharp
public abstract class VectorPathDataResource : LayerResource, IVectorPathData
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [IsDisabled](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/isdisabled/) { get; set; } | 获取或设置一个值，指示此实例是否被禁用。 |
| [IsInverted](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/isinverted/) { get; set; } | 获取或设置一个值，指示此实例是否反转。 |
| [IsNotLinked](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/isnotlinked/) { get; set; } | 获取或设置一个值，指示此实例是否未链接。 |
| abstract [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | 获取图层资源键。 |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/length/) { get; } | 获取以字节为单位的图层资源长度。 |
| [Paths](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/paths/) { get; set; } | 获取或设置路径记录。 |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/psdversion/) { get; } | 获取 psd 版本。 |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/signature/) { get; } | 获取签名. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/version/) { get; set; } | 获取或设置版本。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/save/)(StreamContainer, int) | 将资源保存到指定的流容器中。 |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | 返回一个String代表这个实例. |

### 例子

以下示例演示了对图层矢量蒙版处理的支持。如何编辑路径以及 Aspose.PSD 如何绘制最终图像。

```csharp
[C#]

string sourceFileName = "DifferentLayerMasks_Source.psd";
string exportPath = "DifferentLayerMasks_Export.psd";
string exportPathPng = "DifferentLayerMasks_Export.png";

// 阅读
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    // 更改矢量路径点
    foreach (var layer in image.Layers)
    {
        foreach (var layerResource in layer.Resources)
        {
            var resource = layerResource as VectorPathDataResource;
            if (resource != null)
            {
                foreach (var pathRecord in resource.Paths)
                {
                    var bezierKnotRecord = pathRecord as BezierKnotRecord;
                    if (bezierKnotRecord != null)
                    {
                        Point p0 = bezierKnotRecord.Points[0];
                        bezierKnotRecord.Points[0] = bezierKnotRecord.Points[2];
                        bezierKnotRecord.Points[2] = p0;
                        break;
                    }
                }
            }
        }
    }

    // 导出
    image.Save(exportPath);
    image.Save(exportPathPng, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### 也可以看看

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* interface [IVectorPathData](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/)
* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* 部件 [Aspose.PSD](../../)


