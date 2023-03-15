---
title: InnerShadowEffect.EffectType
second_title: Aspose.PSD for .NET API 参考
description: InnerShadowEffect 财产. 获取一种效果
type: docs
weight: 50
url: /zh/net/aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/effecttype/
---
## InnerShadowEffect.EffectType property

获取一种效果

```csharp
public LayerEffectsTypes EffectType { get; }
```

### 例子

以下代码演示了对 ILayerEffect.EffectType 属性的支持。

```csharp
[C#]

string inputFile = "input.psd";
string outputWithout = "outputWithout.png";
string outputWith = "outputWith.png";

using (PsdImage psdImage = (PsdImage)Image.Load(inputFile, new LoadOptions()))
{
    psdImage.Save(outputWithout, new PngOptions());

    Layer workLayer = psdImage.Layers[1];

    DropShadowEffect dropShadowEffect = workLayer.BlendingOptions.AddDropShadow();
    dropShadowEffect.Distance = 0;
    dropShadowEffect.Size = 8;
    dropShadowEffect.Opacity = 20;

    foreach (ILayerEffect iEffect in workLayer.BlendingOptions.Effects)
    {
        if (iEffect.EffectType == LayerEffectsTypes.DropShadow)
        {
            // 它抓住了
            psdImage.Save(outputWith, new PngOptions());
        }
    }
}
```

### 也可以看看

* enum [LayerEffectsTypes](../../../aspose.psd.fileformats.psd.layers.layerresources.lfx2resources/layereffectstypes/)
* class [InnerShadowEffect](../)
* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../innershadoweffect/)
* 部件 [Aspose.PSD](../../../)


