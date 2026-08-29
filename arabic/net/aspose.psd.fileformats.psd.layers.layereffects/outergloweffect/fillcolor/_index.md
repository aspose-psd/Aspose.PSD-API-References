---
title: "OuterGlowEffect.FillColor"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "OuterGlowEffect property. يحصل أو يضبط اللون"
type: docs
weight: 30
url: /ar/net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/fillcolor/
---
{{< psd/tize >}}
## OuterGlowEffect.FillColor property

يحصل أو يعيّن اللون.

```csharp
public IFillSettings FillColor { get; set; }
```

### Property Value

اللون.

## أمثلة

يوضح الشيفرة التالية دعم OuterGlowEffect.

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

### انظر أيضًا

* interface [IFillSettings](../../../aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings/)
* class [OuterGlowEffect](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)


