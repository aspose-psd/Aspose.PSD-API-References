---
title: DropShadowEffect.Angle
second_title: Aspose.PSD for .NET API 参考
description: DropShadowEffect 财产. 获取或设置角度以度为单位
type: docs
weight: 10
url: /zh/net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/angle/
---
## DropShadowEffect.Angle property

获取或设置角度（以度为单位）。

```csharp
public int Angle { get; set; }
```

### 适当的价值

角度.

### 例子

以下代码演示了如何使用 DropShadowEffect 的 Opacity 属性。

```csharp
[C#]

string inputFile = "input.psd";
string outputImage20 = "outputImage20.png";
string outputImage200 = "outputImage200.png";

using (PsdImage psdImage = (PsdImage)Image.Load(inputFile, new LoadOptions()))
{
    Layer workLayer = psdImage.Layers[1];

    DropShadowEffect dropShadowEffect = workLayer.BlendingOptions.AddDropShadow();
    dropShadowEffect.Distance = 0;
    dropShadowEffect.Size = 8;

    // 不透明度 = 20 的示例
    dropShadowEffect.Opacity = 20;
    psdImage.Save(outputImage20, new PngOptions());

    // 不透明度 = 20 的示例0
    dropShadowEffect.Opacity = 200;
    psdImage.Save(outputImage200, new PngOptions());
}
```

### 也可以看看

* class [DropShadowEffect](../)
* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../dropshadoweffect/)
* 部件 [Aspose.PSD](../../../)


