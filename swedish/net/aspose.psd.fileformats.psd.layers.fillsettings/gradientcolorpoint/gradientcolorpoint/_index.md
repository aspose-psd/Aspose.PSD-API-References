---
title: GradientColorPoint.GradientColorPoint
second_title: Aspose.PSD för .NET API-referens
description: GradientColorPoint byggare. Initierar en ny instans avGradientColorPoint class.
type: docs
weight: 10
url: /sv/net/aspose.psd.fileformats.psd.layers.fillsettings/gradientcolorpoint/gradientcolorpoint/
---
## GradientColorPoint() {#constructor}

Initierar en ny instans av[`GradientColorPoint`](../) class.

```csharp
public GradientColorPoint()
```

### Se även

* class [GradientColorPoint](../)
* namnutrymme [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../gradientcolorpoint/)
* hopsättning [Aspose.PSD](../../../)

---

## GradientColorPoint(Color, int, int) {#constructor_1}

Initierar en ny instans av[`GradientColorPoint`](../) class.

```csharp
public GradientColorPoint(Color color, int location, int medianPointLocation)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| color | Color | Färgpunkt på gradient. |
| location | Int32 | Placeringen av färgpunkten på övertoningen. |
| medianPointLocation | Int32 | Mediangradientpunktens läge. |

### Exempel

Följande exempel visar hur man skapar/redigerar GradientOverlayEffect-effektobjektet i lager.

```csharp
[C#]

string sourceFilePath = "psdnet256.psd";
string outputFilePath = "psdnet256.psd_output.psd";

// Skapar/Hämtar och redigerar övertoningseffekten i ett lager.
using (var psdImage = (PsdImage)Image.Load(sourceFilePath, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    BlendingOptions layerBlendOptions = psdImage.Layers[1].BlendingOptions;
    GradientOverlayEffect gradientOverlayEffect = null;

    // Sök GradientOverlayEffect i ett lager.
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

    // Ändra blandningsläge för gradienteffekt.
    gradientOverlayEffect.BlendMode = BlendMode.Hue;

    // Hämtar GradientFillSettings-objektet för att konfigurera övertoningsöverlagringsinställningar.
    GradientFillSettings settings = gradientOverlayEffect.Settings;

    // Att ställa in en ny gradient med två färger.
    settings.ColorPoints = new IGradientColorPoint[]
    {
        new GradientColorPoint(Color.GreenYellow, 0, 50),
        new GradientColorPoint(Color.BlueViolet, 4096, 50),
    };

    // Ställer in en lutning av gradienten i en vinkel på 80 grader.
    settings.Angle = 80;

    // Skalgradienteffekt upp till 150 %.
    settings.Scale = 150;

    // Ställer in typ av gradient.
    settings.GradientType = GradientType.Linear;

    // Gör gradienten ogenomskinlig genom att ställa in opaciteten till 100 % vid varje transparenspunkt.
    settings.TransparencyPoints[0].Opacity = 100;
    settings.TransparencyPoints[1].Opacity = 100;

    psdImage.Save(outputFilePath);
}
```

### Se även

* struct [Color](../../../aspose.psd/color/)
* class [GradientColorPoint](../)
* namnutrymme [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../gradientcolorpoint/)
* hopsättning [Aspose.PSD](../../../)


