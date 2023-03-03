---
title: FillLayer.CreateInstance
second_title: Aspose.PSD for .NET API 参考
description: FillLayer 方法. 建立一个新的实例FillLayer按填充类型分类.
type: docs
weight: 10
url: /zh/net/aspose.psd.fileformats.psd.layers.filllayers/filllayer/createinstance/
---
## FillLayer.CreateInstance method

建立一个新的实例[`FillLayer`](../)按填充类型分类.

```csharp
public static FillLayer CreateInstance(FillType fillType)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fillType | FillType | 填充层的类型。 |

### 返回值

返回一个新的实例[`FillLayer`](../)按填充类型分类。

### 例子

以下示例演示如何在运行时添加 FillLayer 类型层。

```csharp
[C#]

string outputFilePath = "output.psd";

using (var image = new PsdImage(100, 100))
{
    FillLayer colorFillLayer = FillLayer.CreateInstance(FillType.Color);
    colorFillLayer.DisplayName = "Color Fill Layer";
    image.AddLayer(colorFillLayer);

    FillLayer gradientFillLayer = FillLayer.CreateInstance(FillType.Gradient);
    gradientFillLayer.DisplayName = "Gradient Fill Layer";
    image.AddLayer(gradientFillLayer);

    FillLayer patternFillLayer = FillLayer.CreateInstance(FillType.Pattern);
    patternFillLayer.DisplayName = "Pattern Fill Layer";
    patternFillLayer.Opacity = 50;
    image.AddLayer(patternFillLayer);

    image.Save(outputFilePath);
}
```

### 也可以看看

* enum [FillType](../../../aspose.psd.fileformats.psd.layers.fillsettings/filltype/)
* class [FillLayer](../)
* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers.FillLayers](../../filllayer/)
* 部件 [Aspose.PSD](../../../)


