---
title: "OuterGlowEffect.Size"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "OuterGlowEffect Eigenschaft. Gibt den Unschärfewert in Pixeln zurück"
type: docs
weight: 120
url: /de/net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/size/
---
{{< psd/tize >}}
## OuterGlowEffect.Size property

Liest den Unschärfewert in Pixeln.

```csharp
public int Size { get; set; }
```

### Property Value

Die Größe.

## Beispiele

Der folgende Code demonstriert die Unterstützung von OuterGlowEffect.

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

* class [OuterGlowEffect](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)


