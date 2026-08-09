---
title: "تعداد LayerEffectsTypes"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.Lfx2Resources.LayerEffectsTypes تعداد. تأثيرات دمج الطبقة"
type: docs
weight: 2900
url: /ar/net/aspose.psd.fileformats.psd.layers.layerresources.lfx2resources/layereffectstypes/
---
{{< psd/tize >}}
## LayerEffectsTypes enumeration

تأثيرات دمج الطبقة.

```csharp
public enum LayerEffectsTypes
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| DropShadow | `0` | ظل الإسقاط. |
| OuterGlow | `1` | التوهج الخارجي. |
| PatternOverlay | `2` | تراكب النمط. |
| GradientOverlay | `3` | تراكب التدرج. |
| ColorOverlay | `4` | تراكب اللون. |
| Satin | `5` | نوع تأثير الساتان. |
| InnerGlow | `6` | التوهج الداخلي. |
| InnerShadow | `7` | الظل الداخلي. |
| Stroke | `8` | الخط. |
| BevelEmboss | `9` | النقش المائل. |

## أمثلة

الكود التالي يوضح دعم الخاصية ILayerEffect.EffectType.

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
            // تم التقاطه
            psdImage.Save(outputWith, new PngOptions());
        }
    }
}
```

### انظر أيضًا

* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.Lfx2Resources](../../aspose.psd.fileformats.psd.layers.layerresources.lfx2resources/)
* assembly [Aspose.PSD](../../)


