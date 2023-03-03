---
title: BlendingOptions.AddOuterGlow
second_title: Aspose.PSD für .NET-API-Referenz
description: BlendingOptions methode. Fügt den äußeren Glüheffekt hinzu.
type: docs
weight: 60
url: /de/net/aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addouterglow/
---
## BlendingOptions.AddOuterGlow method

Fügt den äußeren Glüheffekt hinzu.

```csharp
public OuterGlowEffect AddOuterGlow()
```

### Rückgabewert

Erstellt[`OuterGlowEffect`](../../outergloweffect/) Objekt

### Beispiele

Der folgende Code demonstriert die OuterGlowEffect-Unterstützung.

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

### Siehe auch

* class [OuterGlowEffect](../../outergloweffect/)
* class [BlendingOptions](../)
* namensraum [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../blendingoptions/)
* Montage [Aspose.PSD](../../../)


