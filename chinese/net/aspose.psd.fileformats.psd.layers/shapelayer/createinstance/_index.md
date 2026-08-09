---
title: "ShapeLayer.CreateInstance"
second_title: "Aspose.PSD for .NET API 参考"
description: "ShapeLayer 方法。创建 ShapeLayer 类的新实例"
type: docs
weight: 20
url: /zh/net/aspose.psd.fileformats.psd.layers/shapelayer/createinstance/
---
{{< psd/tize >}}
## ShapeLayer.CreateInstance method

创建一个 [`ShapeLayer`](../) 类的新实例。

```csharp
public static ShapeLayer CreateInstance()
```

### 返回值

返回 [`ShapeLayer`](../) 类的新实例。

## 示例

以下代码展示了对 ShapeLayer 图层的支持。

```csharp
[C#]

string srcFile = "ShapeLayerTest.psd";
string outFile = "ShapeLayerTest-out.psd";

using (PsdImage image = (PsdImage)Image.Load(srcFile, new PsdLoadOptions { LoadEffectsResource = true }))
{
    ShapeLayer shapeLayer = (ShapeLayer)image.Layers[1];
    IPath layerPath = shapeLayer.Path;

    IPathShape[] pathShapeSource = layerPath.GetItems();
    List<IPathShape> pathShapesDest = new List<IPathShape>(pathShapeSource);

    // 源文件包含 2 个图形。删除第二个。
    pathShapesDest.RemoveAt(1);

    layerPath.SetItems(pathShapesDest.ToArray());

    shapeLayer.Update();

    image.Save(outFile);
}
```

### 另请参阅

* class [ShapeLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


