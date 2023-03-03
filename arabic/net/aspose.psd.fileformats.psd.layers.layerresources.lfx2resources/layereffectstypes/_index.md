---
title: Enum LayerEffectsTypes
second_title: Aspose.PSD لمرجع .NET API
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.Lfx2Resources.LayerEffectsTypes تعداد. تأثيرات مزج الطبقة .
type: docs
weight: 2660
url: /ar/net/aspose.psd.fileformats.psd.layers.layerresources.lfx2resources/layereffectstypes/
---
## LayerEffectsTypes enumeration

تأثيرات مزج الطبقة .

```csharp
public enum LayerEffectsTypes
```

### قيم

| اسم | قيمة | وصف |
| --- | --- | --- |
| DropShadow | `0` | الظل المسقط . |
| OuterGlow | `1` | التوهج الخارجي. |
| PatternOverlay | `2` | تراكب النمط . |
| GradientOverlay | `3` | تراكب التدرج . |
| ColorOverlay | `4` | تراكب اللون . |
| Satin | `5` | نوع تأثير الساتان . |
| InnerGlow | `6` | التوهج الداخلي. |
| InnerShadow | `7` | الظل الداخلي . |
| Stroke | `8` | السكتة الدماغية . |
| BevelEmboss | `9` | النقش المائل . |

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

* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.Lfx2Resources](../../aspose.psd.fileformats.psd.layers.layerresources.lfx2resources/)
* المجسم [Aspose.PSD](../../)


