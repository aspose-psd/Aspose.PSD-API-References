---
title: OuterGlowEffect.Size
second_title: Aspose.PSD لمرجع .NET API
description: OuterGlowEffect ملكية. الحصول على قيمة التمويه بالبكسل .
type: docs
weight: 120
url: /ar/net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/size/
---
## OuterGlowEffect.Size property

الحصول على قيمة التمويه بالبكسل .

```csharp
public int Size { get; }
```

### Property_Value

الحجم .

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

* class [OuterGlowEffect](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../outergloweffect/)
* المجسم [Aspose.PSD](../../../)


