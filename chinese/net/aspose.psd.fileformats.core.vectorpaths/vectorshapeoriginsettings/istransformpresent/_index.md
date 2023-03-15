---
title: VectorShapeOriginSettings.IsTransformPresent
second_title: Aspose.PSD for .NET API 参考
description: VectorShapeOriginSettings 财产. 获取一个值指示此实例是否具有转换属性
type: docs
weight: 100
url: /zh/net/aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/istransformpresent/
---
## VectorShapeOriginSettings.IsTransformPresent property

获取一个值，指示此实例是否具有转换属性。

```csharp
public bool IsTransformPresent { get; }
```

### 适当的价值

`真的`如果此实例具有转换属性；否则，`错误的` .

### 例子

以下代码演示了调整包含矢量路径的形状图层大小的能力。

```csharp
[C#]

string sourceFileName = "vectorShapes.psd";
string outputFileName = "out_vectorShapes.psd";
string sourcePath = sourceFileName;
string outputPath = outputFileName;
string outputPathPng = Path.ChangeExtension(outputPath, ".png");
using (var psdImage = (PsdImage)Image.Load(sourcePath))
{
    foreach (var layer in psdImage.Layers)
    {
        layer.Resize(layer.Width * 5 / 4, layer.Height / 2);
    }

    psdImage.Save(outputPath);
    psdImage.Save(outputPathPng, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### 也可以看看

* class [VectorShapeOriginSettings](../)
* 命名空间 [Aspose.PSD.FileFormats.Core.VectorPaths](../../vectorshapeoriginsettings/)
* 部件 [Aspose.PSD](../../../)


