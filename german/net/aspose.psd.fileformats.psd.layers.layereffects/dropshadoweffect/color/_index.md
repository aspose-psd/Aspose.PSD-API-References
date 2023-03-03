---
title: DropShadowEffect.Color
second_title: Aspose.PSD für .NET-API-Referenz
description: DropShadowEffect eigendom. Ruft die Farbe ab oder legt sie fest.
type: docs
weight: 30
url: /de/net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/color/
---
## DropShadowEffect.Color property

Ruft die Farbe ab oder legt sie fest.

```csharp
public Color Color { get; set; }
```

### Eigentumswert

Die Farbe.

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

* struct [Color](../../../aspose.psd/color/)
* class [DropShadowEffect](../)
* namensraum [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../dropshadoweffect/)
* Montage [Aspose.PSD](../../../)


