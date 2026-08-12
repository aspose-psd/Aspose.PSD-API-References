---
title: "DropShadowEffect.IsVisible"
second_title: "Aspose.PSD för .NET API‑referens"
description: "DropShadowEffect‑egenskap. Hämtar eller anger ett värde som indikerar om detta objekt är synligt"
type: docs
weight: 60
url: /sv/net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/isvisible/
---
{{< psd/tize >}}
## DropShadowEffect.IsVisible property

Hämtar eller anger ett värde som indikerar om den här instansen är synlig.

```csharp
public bool IsVisible { get; set; }
```

### Property Value

`true` om detta objekt är synligt; annars `false`.

## Exempel

Följande kod demonstrerar användning av Opacity‑egenskapen för DropShadowEffect.

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

    // Exempel med Opacity = 20
    dropShadowEffect.Opacity = 20;
    psdImage.Save(outputImage20, new PngOptions());

    // Exempel med Opacity = 200
    dropShadowEffect.Opacity = 200;
    psdImage.Save(outputImage200, new PngOptions());
}
```

### Se även

* class [DropShadowEffect](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)


