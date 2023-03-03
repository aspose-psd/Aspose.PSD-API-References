---
title: OuterGlowEffect.Spread
second_title: Aspose.PSD لمرجع .NET API
description: OuterGlowEffect ملكية. الحصول على الكثافة أو تحديدها كنسبة مئوية .
type: docs
weight: 130
url: /ar/net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/spread/
---
## OuterGlowEffect.Spread property

الحصول على الكثافة أو تحديدها كنسبة مئوية .

```csharp
public int Spread { get; set; }
```

### Property_Value

السبريد .

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


