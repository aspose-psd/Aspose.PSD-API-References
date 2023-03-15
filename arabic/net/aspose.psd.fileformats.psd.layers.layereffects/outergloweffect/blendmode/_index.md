---
title: OuterGlowEffect.BlendMode
second_title: Aspose.PSD لمرجع .NET API
description: OuterGlowEffect ملكية. الحصول على أو تحديد وضع المزج .
type: docs
weight: 10
url: /ar/net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/blendmode/
---
## OuterGlowEffect.BlendMode property

الحصول على أو تحديد وضع المزج .

```csharp
public BlendMode BlendMode { get; set; }
```

### Property_Value

وضع المزج .

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

* enum [BlendMode](../../../aspose.psd.fileformats.core.blending/blendmode/)
* class [OuterGlowEffect](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../outergloweffect/)
* المجسم [Aspose.PSD](../../../)


