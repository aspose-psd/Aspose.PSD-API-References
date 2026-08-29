---
title: "DropShadowEffect.EffectType"
second_title: "Aspose.PSD for .NET API Reference"
description: "DropShadowEffect プロパティ。エフェクトのタイプを取得します"
type: docs
weight: 50
url: /ja/net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/effecttype/
---
{{< psd/tize >}}
## DropShadowEffect.EffectType property

エフェクトのタイプを取得します。

```csharp
public LayerEffectsTypes EffectType { get; }
```

## 例

以下のコードは、DropShadowEffect の Opacity プロパティの使用例を示しています。

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

    // Opacity = 20 の例
    dropShadowEffect.Opacity = 20;
    psdImage.Save(outputImage20, new PngOptions());

    // Opacity = 200 の例
    dropShadowEffect.Opacity = 200;
    psdImage.Save(outputImage200, new PngOptions());
}
```

以下のコードは ILayerEffect.EffectType プロパティのサポートを示しています。

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
            // 捕捉されました
            psdImage.Save(outputWith, new PngOptions());
        }
    }
}
```

### 関連項目

* enum [LayerEffectsTypes](../../layereffectstypes/)
* class [DropShadowEffect](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)


