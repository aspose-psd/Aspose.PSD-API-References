---
title: DropShadowEffect.IsVisible
second_title: Aspose.PSD für .NET-API-Referenz
description: DropShadowEffect eigendom. Ruft einen Wert ab oder legt einen Wert fest der angibt ob diese Instanz sichtbar ist.
type: docs
weight: 60
url: /de/net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/isvisible/
---
## DropShadowEffect.IsVisible property

Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob diese Instanz sichtbar ist.

```csharp
public bool IsVisible { get; set; }
```

### Eigentumswert

`WAHR` wenn diese Instanz sichtbar ist; ansonsten,`FALSCH` .

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


