---
title: ColorOverlayEffect.EffectType
second_title: Aspose.PSD لمرجع .NET API
description: ColorOverlayEffect ملكية. يحصل على نوع من التأثير
type: docs
weight: 30
url: /ar/net/aspose.psd.fileformats.psd.layers.layereffects/coloroverlayeffect/effecttype/
---
## ColorOverlayEffect.EffectType property

يحصل على نوع من التأثير

```csharp
public LayerEffectsTypes EffectType { get; }
```

### أمثلة

توضح التعليمات البرمجية التالية دعم الخاصية ILayerEffect.EffectType.

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
            // اشتعلت
            psdImage.Save(outputWith, new PngOptions());
        }
    }
}
```

### أنظر أيضا

* enum [LayerEffectsTypes](../../../aspose.psd.fileformats.psd.layers.layerresources.lfx2resources/layereffectstypes/)
* class [ColorOverlayEffect](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../coloroverlayeffect/)
* المجسم [Aspose.PSD](../../../)

