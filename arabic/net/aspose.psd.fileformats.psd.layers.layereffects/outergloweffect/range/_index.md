---
title: OuterGlowEffect.Range
second_title: Aspose.PSD لمرجع .NET API
description: OuterGlowEffect ملكية. الحصول على الضوضاء أو ضبطها .
type: docs
weight: 110
url: /ar/net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/range/
---
## OuterGlowEffect.Range property

الحصول على الضوضاء أو ضبطها .

```csharp
public int Range { get; set; }
```

### Property_Value

الضوضاء .

### استثناءات

| استثناء | حالة |
| --- | --- |
| [PsdImageArgumentException](../../../aspose.psd.coreexceptions.imageformats/psdimageargumentexception/) | يجب تحديد الضوضاء كنسبة مئوية في النطاق من 0 إلى 100 |

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


