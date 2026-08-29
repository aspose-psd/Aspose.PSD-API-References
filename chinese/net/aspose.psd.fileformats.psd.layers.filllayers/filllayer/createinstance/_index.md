---
title: "FillLayer.CreateInstance"
second_title: "Aspose.PSD for .NET API 参考"
description: "FillLayer 方法。根据填充类型构建 FillLayer 类的新实例。"
type: docs
weight: 10
url: /zh/net/aspose.psd.fileformats.psd.layers.filllayers/filllayer/createinstance/
---
{{< psd/tize >}}
## FillLayer.CreateInstance method

根据填充类型构建 [`FillLayer`](../) 类的新实例。

```csharp
public static FillLayer CreateInstance(FillType fillType)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fillType | FillType | 填充层的类型。 |

### 返回值

返回根据填充类型创建的 [`FillLayer`](../) 类的新实例。

## 示例

下面的示例演示了如何在运行时添加 FillLayer 类型的层。

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

### 另请参阅

* enum [FillType](../../../aspose.psd.fileformats.psd.layers.fillsettings/filltype/)
* class [FillLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillLayers](../../../aspose.psd.fileformats.psd.layers.filllayers/)
* assembly [Aspose.PSD](../../../)


