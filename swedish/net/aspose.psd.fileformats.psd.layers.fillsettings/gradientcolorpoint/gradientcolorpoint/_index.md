---
title: "GradientColorPoint.GradientColorPoint"
second_title: "Aspose.PSD för .NET API‑referens"
description: "GradientColorPoint constructor. Initierar en ny instans av klassen GradientColorPoint"
type: docs
weight: 10
url: /sv/net/aspose.psd.fileformats.psd.layers.fillsettings/gradientcolorpoint/gradientcolorpoint/
---
{{< psd/tize >}}
## GradientColorPoint() {#constructor}

Initierar en ny instans av klassen [`GradientColorPoint`](../).

```csharp
public GradientColorPoint()
```

### Se även

* class [GradientColorPoint](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../../)

---

## GradientColorPoint(Color, int, int) {#constructor_1}

Initierar en ny instans av klassen [`GradientColorPoint`](../).

```csharp
public GradientColorPoint(Color color, int location, int medianPointLocation)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| färg | Färg | Färgpunkt på gradienten. |
| position | Int32 | Placeringen av färgpunkten på gradienten. |
| medianPointLocation | Int32 | Medianposition för gradientpunkten. |

## Exempel

Följande exempel visar hur man skapar/redigerar GradientOverlayEffect-effektobjektet i ett lager.

```csharp
[C#]

string sourceFilePath = "psdnet256.psd";
string outputFilePath = "psdnet256.psd_output.psd";

// Skapar/hämtar och redigerar gradient overlay effect i ett lager.
using (var psdImage = (PsdImage)Image.Load(sourceFilePath, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    BlendingOptions layerBlendOptions = psdImage.Layers[1].BlendingOptions;
    GradientOverlayEffect gradientOverlayEffect = null;

    // Sök efter GradientOverlayEffect i ett lager.
    foreach (ILayerEffect effect in layerBlendOptions.Effects)
    {
        gradientOverlayEffect = effect as GradientOverlayEffect;
        if (gradientOverlayEffect != null)
        {
            break;
        }
    }

    if (gradientOverlayEffect == null)
    {
        // Du kan skapa en ny GradientOverlayEffect om den inte finns.
        gradientOverlayEffect = layerBlendOptions.AddGradientOverlay();
    }

    // Lägg till lite transparens till effekten.
    gradientOverlayEffect.Opacity = 200;

    // Ändra blandningsläget för gradienteffekten.
    gradientOverlayEffect.BlendMode = BlendMode.Hue;

    // Hämtar GradientFillSettings-objekt för att konfigurera gradientöverläggningsinställningar.
    GradientFillSettings settings = (GradientFillSettings)gradientOverlayEffect.Settings;
    SolidGradient solidGradient = (SolidGradient)settings.Gradient;

    // Ställer in ett nytt gradient med två färger.
    solidGradient.ColorPoints = new IGradientColorPoint[]
    {
        new GradientColorPoint(Color.GreenYellow, 0, 50),
        new GradientColorPoint(Color.BlueViolet, 4096, 50),
    };

    // Ställer in en lutning på gradienten med en vinkel på 80 grader.
    settings.Angle = 80;

    // Skala gradienteffekten upp till 150 %.
    settings.Scale = 150;

    // Ställer in gradienttyp.
    settings.GradientType = GradientType.Linear;

    // Gör gradienten ogenomskinlig genom att sätta opaciteten till 100 % vid varje transparenspunkt.
    solidGradient.TransparencyPoints[0].Opacity = 100;
    solidGradient.TransparencyPoints[1].Opacity = 100;

    psdImage.Save(outputFilePath);
}
```

### Se även

* struct [Color](../../../aspose.psd/color/)
* class [GradientColorPoint](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../../)


