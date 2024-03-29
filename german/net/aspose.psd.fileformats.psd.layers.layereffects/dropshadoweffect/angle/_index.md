---
title: DropShadowEffect.Angle
second_title: Aspose.PSD für .NET-API-Referenz
description: DropShadowEffect eigendom. Ruft den Winkel in Grad ab oder legt ihn fest.
type: docs
weight: 10
url: /de/net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/angle/
---
## DropShadowEffect.Angle property

Ruft den Winkel in Grad ab oder legt ihn fest.

```csharp
public int Angle { get; set; }
```

### Eigentumswert

Der Winkel.

### Beispiele

Der folgende Code veranschaulicht die Verwendung der Opacity-Eigenschaft von DropShadowEffect.

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

    // Beispiel mit Deckkraft = 20
    dropShadowEffect.Opacity = 20;
    psdImage.Save(outputImage20, new PngOptions());

    // Beispiel mit Deckkraft = 200
    dropShadowEffect.Opacity = 200;
    psdImage.Save(outputImage200, new PngOptions());
}
```

### Siehe auch

* class [DropShadowEffect](../)
* namensraum [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../dropshadoweffect/)
* Montage [Aspose.PSD](../../../)


