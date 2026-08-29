---
title: "类 VstkResource"
second_title: "Aspose.PSD for .NET API 参考"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources.VstkResource 类。资源类 VstkResource。包含有关矢量描边数据的信息。资源应通过 ResourceLoader 的 AssignItems 方法初始化，或通过为类的属性赋值进行初始化。"
type: docs
weight: 3440
url: /zh/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/
---
{{< psd/tize >}}
## VstkResource class

资源类 VstkResource。包含有关矢量描边数据的信息。资源应通过 ResourceLoader 的 AssignItems 方法初始化，或通过为类的属性赋值进行初始化。

```csharp
public class VstkResource : LayerResource
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [VstkResource](vstkresource/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [FillEnabled](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/fillenabled/) { get; set; } | 获取或设置一个值，指示是否启用描边填充。 |
| [FillSettings](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/fillsettings/) { get; set; } | 获取或设置笔划的填充设置。 |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | 获取图层资源键。 |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/length/) { get; } | 获取图层资源的字节长度。 |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | 获取图层资源所需的最低 PSD 版本。0 表示没有限制。 |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | 获取签名。 |
| [StrokeEnabled](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokeenabled/) { get; set; } | 获取或设置一个值，指示是否启用描边效果。 |
| [StrokeStyleBlendMode](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestyleblendmode/) { get; set; } | 获取或设置描边混合模式。 |
| [StrokeStyleContent](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestylecontent/) { get; set; } | 获取或设置描边实体。属性决定描边的填充设置。 |
| [StrokeStyleLineAlignment](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestylelinealignment/) { get; set; } | 获取或设置笔划样式线对齐方式。 |
| [StrokeStyleLineCapType](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestylelinecaptype/) { get; set; } | 获取或设置描边样式线帽的类型。 |
| [StrokeStyleLineCapWidth](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestylelinecapwidth/) { get; set; } | 获取或设置描边线帽宽度。 |
| [StrokeStyleLineDashOffset](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestylelinedashoffset/) { get; set; } | 获取或设置描边样式线段偏移。 |
| [StrokeStyleLineDashSet](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestylelinedashset/) { get; set; } | 获取或设置线段虚线数组。 |
| [StrokeStyleLineJoinType](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestylelinejointype/) { get; set; } | 获取或设置描边样式线段连接类型。 |
| [StrokeStyleLineWidth](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestylelinewidth/) { get; set; } | 获取或设置描边线宽。 |
| [StrokeStyleMiterLimit](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestylemiterlimit/) { get; set; } | 获取或设置描边样式斜接限制。 |
| [StrokeStyleOpacity](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestyleopacity/) { get; set; } | 获取或设置描边样式不透明度（0-100%）。 |
| [StrokeStyleResolution](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestyleresolution/) { get; set; } | 获取或设置描边样式分辨率。 |
| [StrokeStyleScaleLock](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestylescalelock/) { get; set; } | 获取或设置描边样式比例锁定。 |
| [StrokeStyleStrokeAdjust](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestylestrokeadjust/) { get; set; } | 获取或设置描边调整。 |
| [StrokeStyleVersion](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestyleversion/) { get; set; } | 获取或设置笔画样式版本。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/save/)(StreamContainer, int) | 将资源保存到指定的流容器中。 |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | 返回一个表示此实例的字符串。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/typetoolkey/) | 类型工具信息键。 |

## 示例

以下代码演示了对 VstkResource 资源的支持。

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

### 另请参阅

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/)
* assembly [Aspose.PSD](../../)


