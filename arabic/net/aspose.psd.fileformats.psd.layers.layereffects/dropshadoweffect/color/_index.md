---
title: "DropShadowEffect.Color"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "خاصية DropShadowEffect. يحصل أو يضبط اللون"
type: docs
weight: 30
url: /ar/net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/color/
---
{{< psd/tize >}}
## DropShadowEffect.Color property

يحصل أو يعيّن اللون.

```csharp
public Color Color { get; set; }
```

### Property Value

اللون.

## أمثلة

يوضح الشيفرة التالية استخدام الخاصية Opacity في DropShadowEffect.

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

    // مثال مع Opacity = 20
    dropShadowEffect.Opacity = 20;
    psdImage.Save(outputImage20, new PngOptions());

    // مثال مع Opacity = 200
    dropShadowEffect.Opacity = 200;
    psdImage.Save(outputImage200, new PngOptions());
}
```

### انظر أيضًا

* struct [Color](../../../aspose.psd/color/)
* class [DropShadowEffect](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)


