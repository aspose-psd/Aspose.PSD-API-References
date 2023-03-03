---
title: Class GdFlResource
second_title: Aspose.PSD for .NET API 参考
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.GdFlResource 班级. GdFlResource 类 此资源包含有关剪切元素混合的信息
type: docs
weight: 2500
url: /zh/net/aspose.psd.fileformats.psd.layers.layerresources/gdflresource/
---
## GdFlResource class

GdFlResource 类。 此资源包含有关剪切元素混合的信息。

```csharp
public class GdFlResource : FillLayerResource
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [GdFlResource](gdflresource/)() | 默认构造函数。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [AlignWithLayer](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/alignwithlayer/) { get; set; } | 获取或设置一个值，指示是否[与图层对齐]. |
| [Angle](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/angle/) { get; set; } | 获取或设置角度。 |
| [Color](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/color/) { get; set; } | 获取RGB的颜色。 |
| [ColorPoints](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/colorpoints/) { get; set; } | 获取颜色点。 |
| [Dither](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/dither/) { get; set; } | 获取或设置一个值，指示是否这`GdFlResource`是抖动. |
| [GradientInterval](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/gradientinterval/) { get; set; } | 获取或设置梯度区间。 |
| [GradientName](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/gradientname/) { get; set; } | 获取或设置渐变的名称。 |
| [GradientType](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/gradienttype/) { get; set; } | 获取或设置渐变的类型。 |
| [HorizontalOffset](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/horizontaloffset/) { get; set; } | 获取或设置水平偏移量。 |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/key/) { get; } | 获取图层资源键。 |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/length/) { get; } | 获取以字节为单位的图层资源长度。 |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/psdversion/) { get; } | 获取层资源所需的最小 psd 版本。 0 表示没有限制。 |
| [Reverse](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/reverse/) { get; set; } | 获取或设置一个值，指示是否这`GdFlResource`是反向的. |
| [Scale](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/scale/) { get; set; } | 获取或设置比例。 |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/signature/) { get; } | 获取图层资源签名。 |
| [TransparencyPoints](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/transparencypoints/) { get; set; } | 获取透明度点。 |
| [VerticalOffset](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/verticaloffset/) { get; set; } | 获取或设置垂直偏移量。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/save/)(StreamContainer, int) | 将资源保存到指定的流容器中。 |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | 返回一个String代表这个实例. |

## 字段

| 姓名 | 描述 |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/typetoolkey/) | 类型工具信息键。 |

### 例子

以下示例演示了对 GdFlResource 资源加载的支持。

```csharp
[C#]

string sourceFileName = "ComplexGradientFillLayer.psd";
string exportPath = "ComplexGradientFillLayer_after.psd";
var im = (PsdImage)Image.Load(sourceFileName);
using (im)
{
    foreach (var layer in im.Layers)
    {
        if (layer is FillLayer)
        {
            var fillLayer = (FillLayer)layer;
            var resources = fillLayer.Resources;
            foreach (var res in resources)
            {
                if (res is GdFlResource)
                {
                    // 阅读
                    var resource = (GdFlResource)res;
                    if (resource.AlignWithLayer != false ||
                     (Math.Abs(resource.Angle - 45.0) > 0.001) ||
                     resource.Dither != true ||
                     resource.Reverse != false ||
                     resource.Color != Color.Empty ||
                     Math.Abs(resource.HorizontalOffset - (-39)) > 0.001 ||
                     Math.Abs(resource.VerticalOffset - (-5)) > 0.001 ||
                     resource.TransparencyPoints.Length != 3 ||
                     resource.ColorPoints.Length != 2)
                    {
                        throw new Exception("Resource Parameters were read wrong");
                    }
                    var transparencyPoints = resource.TransparencyPoints;
                    if (Math.Abs(100.0 - transparencyPoints[0].Opacity) > 0.25 ||
                     transparencyPoints[0].Location != 0 ||
                     transparencyPoints[0].MedianPointLocation != 50 ||
                     Math.Abs(50.0 - transparencyPoints[1].Opacity) > 0.25 ||
                     transparencyPoints[1].Location != 2048 ||
                     transparencyPoints[1].MedianPointLocation != 50 ||
                     Math.Abs(100.0 - transparencyPoints[2].Opacity) > 0.25 ||
                     transparencyPoints[2].Location != 4096 ||
                     transparencyPoints[2].MedianPointLocation != 50)
                    {
                        throw new Exception("Gradient Transparency Points were read Wrong");
                    }
                    var colorPoints = resource.ColorPoints;
                    if (colorPoints[0].Color != Color.FromArgb(203, 64, 140) ||
                     colorPoints[0].Location != 0 ||
                     colorPoints[0].MedianPointLocation != 50 ||
                     colorPoints[1].Color != Color.FromArgb(203, 0, 0) ||
                     colorPoints[1].Location != 4096 ||
                     colorPoints[1].MedianPointLocation != 50)
                    {
                        throw new Exception("Gradient Color Points were read Wrong");
                    }
                    // 编辑
                    resource.Angle = 30.0;
                    resource.Dither = false;
                    resource.AlignWithLayer = true;
                    resource.Reverse = true;
                    resource.HorizontalOffset = 25;
                    resource.VerticalOffset = -15;
                    var newColorPoints = new List<IGradientColorPoint>(resource.ColorPoints);
                    var
                     newTransparencyPoints = new
                    List<IGradientTransparencyPoint>(resource.TransparencyPoints);
                    newColorPoints.Add(new GradientColorPoint()
                    {
                        Color = Color.Violet,
                        Location = 4096,
                        MedianPointLocation = 75
                    });
                    colorPoints[1].Location = 3000;
                    newTransparencyPoints.Add(new GradientTransparencyPoint()
                    {
                        Opacity = 80.0,
                        Location = 4096,
                        MedianPointLocation = 25
                    });
                    transparencyPoints[2].Location = 3000;
                    resource.ColorPoints = newColorPoints.ToArray();
                    resource.TransparencyPoints = newTransparencyPoints.ToArray();
                    im.Save(exportPath);
                }
                break;
            }
            break;
        }
    }
}
```

### 也可以看看

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [FillLayerResource](../filllayerresource/)
* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* 部件 [Aspose.PSD](../../)


