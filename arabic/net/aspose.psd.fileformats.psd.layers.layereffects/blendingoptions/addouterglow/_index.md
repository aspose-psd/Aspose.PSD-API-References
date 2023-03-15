---
title: BlendingOptions.AddOuterGlow
second_title: Aspose.PSD لمرجع .NET API
description: BlendingOptions طريقة. يضيف تأثير التوهج الخارجي.
type: docs
weight: 60
url: /ar/net/aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addouterglow/
---
## BlendingOptions.AddOuterGlow method

يضيف تأثير التوهج الخارجي.

```csharp
public OuterGlowEffect AddOuterGlow()
```

### قيمة الإرجاع

تم إنشاؤه[`OuterGlowEffect`](../../outergloweffect/) كائن

### أمثلة

يوضح الكود التالي دعم OuterGlowEffect.

```csharp
[C#]

string src = "GreenLayer.psd";
string outputPng = "output261.png";

using (var image = (PsdImage)Image.Load(src))
{
    OuterGlowEffect effect = image.Layers[1].BlendingOptions.AddOuterGlow();
    effect.Range = 10;
    effect.Spread = 10;
    ((IColorFillSettings)effect.FillColor).Color = Color.Red;
    effect.Opacity = 128;
    effect.BlendMode = BlendMode.Normal;

    image.Save(outputPng, new PngOptions());
}
```

### أنظر أيضا

* class [OuterGlowEffect](../../outergloweffect/)
* class [BlendingOptions](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../blendingoptions/)
* المجسم [Aspose.PSD](../../../)


