---
title: DropShadowEffect.Angle
second_title: Aspose.PSD per riferimento API .NET
description: DropShadowEffect proprietà. Ottiene o imposta langolo in gradi.
type: docs
weight: 10
url: /it/net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/angle/
---
## DropShadowEffect.Angle property

Ottiene o imposta l'angolo in gradi.

```csharp
public int Angle { get; set; }
```

### Valore della proprietà

L'angolo.

### Esempi

Il codice seguente illustra l'utilizzo della proprietà Opacity di DropShadowEffect.

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

    // Esempio con Opacità = 20
    dropShadowEffect.Opacity = 20;
    psdImage.Save(outputImage20, new PngOptions());

    // Esempio con Opacità = 200
    dropShadowEffect.Opacity = 200;
    psdImage.Save(outputImage200, new PngOptions());
}
```

### Guarda anche

* class [DropShadowEffect](../)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../dropshadoweffect/)
* assemblea [Aspose.PSD](../../../)


