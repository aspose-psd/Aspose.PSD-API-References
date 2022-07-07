---
title: VsmsResource
second_title: Aspose.PSD for .NET API 参考
description: 类 VsmsResource 此资源包含有关矢量图层蒙版的信息
type: docs
weight: 3270
url: /zh/net/aspose.psd.fileformats.psd.layers.layerresources/vsmsresource/
---
## VsmsResource class

类 VsmsResource。 此资源包含有关矢量图层蒙版的信息

```csharp
public class VsmsResource : VectorPathDataResource
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [VsmsResource](vsmsresource#constructor)() | 初始化[`VsmsResource`](../vsmsresource)类的新实例。 |
| [VsmsResource](vsmsresource#constructor_1)(byte[]) | 初始化[`VsmsResource`](../vsmsresource)类的新实例。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [IsDisabled](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/isdisabled) { get; set; } | 获取或设置一个值，指示该实例是否被禁用。 |
| [IsInverted](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/isinverted) { get; set; } | 获取或设置一个值，指示此实例是否反转。 |
| [IsNotLinked](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/isnotlinked) { get; set; } | 获取或设置一个值，该值指示此实例是否未链接。 |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/vsmsresource/key) { get; } | 获取层资源密钥。 |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/length) { get; } | 获取层资源长度（以字节为单位）。 |
| [Paths](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/paths) { get; set; } | 获取或设置路径记录。 |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/psdversion) { get; } | 获取psd版本。 |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/signature) { get; } | 获取签名。 |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/version) { get; set; } | 获取或设置版本。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/save)(StreamContainer, int) | 将资源保存到指定的流容器。 |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring)() | 返回代表此实例的String。 |

## 字段

| 姓名 | 描述 |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/vsmsresource/typetoolkey) | 类型工具信息键。 |

### 例子

下面的例子演示了对VsmsResource资源加载的支持。路径的编辑是如何工作的。

```csharp
[C#]

[Test]
public void TestPsdNet140()
{
    // Vsms资源支持
    string sourceFileName = "EmptyRectangle.psd";
    string exportPath = "EmptyRectangle_changed.psd";
    var im = (PsdImage)Image.Load(sourceFileName);
    using (im)
    {
        var resource = GetVsmsResource(im);
        // 阅读
        if (resource.IsDisabled != false ||
            resource.IsInverted != false ||
            resource.IsNotLinked != false ||
            resource.Paths.Length != 7 ||
            resource.Paths[0].Type != VectorPathType.PathFillRuleRecord ||
            resource.Paths[1].Type != VectorPathType.InitialFillRuleRecord ||
            resource.Paths[2].Type != VectorPathType.ClosedSubpathLengthRecord ||
            resource.Paths[3].Type != VectorPathType.ClosedSubpathBezierKnotUnlinked ||
            resource.Paths[4].Type != VectorPathType.ClosedSubpathBezierKnotUnlinked ||
            resource.Paths[5].Type != VectorPathType.ClosedSubpathBezierKnotUnlinked ||
            resource.Paths[6].Type != VectorPathType.ClosedSubpathBezierKnotUnlinked)
        {
            throw new Exception("VsmsResource was read wrong");
        }

        var pathFillRule = (PathFillRuleRecord)resource.Paths[0];
        var initialFillRule = (InitialFillRuleRecord)resource.Paths[1];
        var subpathLength = (LengthRecord)resource.Paths[2];

        // 路径填充规则不包含任何附加信息
        if (pathFillRule.Type != VectorPathType.PathFillRuleRecord ||
        initialFillRule.Type != VectorPathType.InitialFillRuleRecord ||
        initialFillRule.IsFillStartsWithAllPixels != false ||
        subpathLength.Type != VectorPathType.ClosedSubpathLengthRecord ||
        subpathLength.IsClosed != true ||
        subpathLength.IsOpen != false)
        {
            throw new Exception("VsmsResource paths were read wrong");
        }

        // 编辑
        resource.IsDisabled = true;
        resource.IsInverted = true;
        resource.IsNotLinked = true;
        var bezierKnot = (BezierKnotRecord)resource.Paths[3];
        bezierKnot.Points[0] = new Point(0, 0);
        bezierKnot = (BezierKnotRecord)resource.Paths[4];
        bezierKnot.Points[0] = new Point(8039798, 10905191);
        initialFillRule.IsFillStartsWithAllPixels = true;
        subpathLength.IsClosed = false;
        im.Save(exportPath);
    }
}

private VsmsResource GetVsmsResource(PsdImage image)
{
    var layer = image.Layers[1];
    VsmsResource resource = null;
    var resources = layer.Resources;
    for (int i = 0; i < resources.Length; i++)
    {
        if (resources[i] is VsmsResource)
        {
            resource = (VsmsResource)resources[i];
            break;
        }
    }
    if (resource == null)
    {
        throw new Exception("VsmsResource not found");
    }
    return resource;
}
```

### 也可以看看

* class [VectorPathDataResource](../vectorpathdataresource)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource)
* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources)
* 部件 [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
