---
title: GradientColorPoint.GradientColorPoint
second_title: Aspose.PSD voor .NET API-referentie
description: GradientColorPoint constructeur. Initialiseert een nieuw exemplaar van hetGradientColorPoint klasse.
type: docs
weight: 10
url: /nl/net/aspose.psd.fileformats.psd.layers.fillsettings/gradientcolorpoint/gradientcolorpoint/
---
## GradientColorPoint() {#constructor}

Initialiseert een nieuw exemplaar van het[`GradientColorPoint`](../) klasse.

```csharp
public GradientColorPoint()
```

### Zie ook

* class [GradientColorPoint](../)
* naamruimte [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../gradientcolorpoint/)
* montage [Aspose.PSD](../../../)

---

## GradientColorPoint(Color, int, int) {#constructor_1}

Initialiseert een nieuw exemplaar van het[`GradientColorPoint`](../) klasse.

```csharp
public GradientColorPoint(Color color, int location, int medianPointLocation)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| color | Color | Kleurpunt op verloop. |
| location | Int32 | De locatie van het kleurpunt op het verloop. |
| medianPointLocation | Int32 | De locatie van het gemiddelde verlooppunt. |

### Voorbeelden

Het volgende voorbeeld laat zien hoe u het effectobject GradientOverlayEffect in een laag maakt/bewerkt.

```csharp
[C#]

string sourceFilePath = "psdnet256.psd";
string outputFilePath = "psdnet256.psd_output.psd";

// Creëert/krijgt en bewerkt het verloopoverlay-effect in een laag.
using (var psdImage = (PsdImage)Image.Load(sourceFilePath, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    BlendingOptions layerBlendOptions = psdImage.Layers[1].BlendingOptions;
    GradientOverlayEffect gradientOverlayEffect = null;

    // Zoek GradientOverlayEffect in een laag.
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
        // U kunt een nieuw GradientOverlayEffect maken als het nog niet bestaat.
        gradientOverlayEffect = layerBlendOptions.AddGradientOverlay();
    }

    // Voeg een beetje transparantie toe aan het effect.
    gradientOverlayEffect.Opacity = 200;

    // Wijzig de overvloeimodus van het verloopeffect.
    gradientOverlayEffect.BlendMode = BlendMode.Hue;

    // Haalt GradientFillSettings-object op om instellingen voor overlay met kleurovergang te configureren.
    GradientFillSettings settings = gradientOverlayEffect.Settings;

    // Een nieuw verloop instellen met twee kleuren.
    settings.ColorPoints = new IGradientColorPoint[]
    {
        new GradientColorPoint(Color.GreenYellow, 0, 50),
        new GradientColorPoint(Color.BlueViolet, 4096, 50),
    };

    // Stelt een helling van het verloop in onder een hoek van 80 graden.
    settings.Angle = 80;

    // Schaalverloopeffect tot 150%.
    settings.Scale = 150;

    // Stelt het type verloop in.
    settings.GradientType = GradientType.Linear;

    // Maak het verloop dekkend door de dekking op elk transparantiepunt in te stellen op 100%.
    settings.TransparencyPoints[0].Opacity = 100;
    settings.TransparencyPoints[1].Opacity = 100;

    psdImage.Save(outputFilePath);
}
```

### Zie ook

* struct [Color](../../../aspose.psd/color/)
* class [GradientColorPoint](../)
* naamruimte [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../gradientcolorpoint/)
* montage [Aspose.PSD](../../../)


