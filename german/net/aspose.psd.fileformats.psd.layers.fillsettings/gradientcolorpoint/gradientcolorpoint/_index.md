---
title: "GradientColorPoint.GradientColorPoint"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "GradientColorPoint-Konstruktor. Initialisiert eine neue Instanz der Klasse GradientColorPoint"
type: docs
weight: 10
url: /de/net/aspose.psd.fileformats.psd.layers.fillsettings/gradientcolorpoint/gradientcolorpoint/
---
{{< psd/tize >}}
## GradientColorPoint() {#constructor}

Initialisiert eine neue Instanz der [`GradientColorPoint`](../)-Klasse.

```csharp
public GradientColorPoint()
```

### Siehe auch

* class [GradientColorPoint](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../../)

---

## GradientColorPoint(Color, int, int) {#constructor_1}

Initialisiert eine neue Instanz der [`GradientColorPoint`](../)-Klasse.

```csharp
public GradientColorPoint(Color color, int location, int medianPointLocation)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Farbe | Farbe | Farbpunkt im Farbverlauf. |
| Position | Int32 | Die Position des Farbpunktes im Farbverlauf. |
| medianPointLocation | Int32 | Der Median-Gradient-Punkt-Standort. |

## Beispiele

Das folgende Beispiel zeigt, wie man das GradientOverlayEffect-Effektobjekt in einer Ebene erstellt/bearbeitet.

```csharp
[C#]

string sourceFilePath = "psdnet256.psd";
string outputFilePath = "psdnet256.psd_output.psd";

// Erstellt/Abruft und bearbeitet den Gradient-Overlay-Effekt in einer Ebene.
using (var psdImage = (PsdImage)Image.Load(sourceFilePath, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    BlendingOptions layerBlendOptions = psdImage.Layers[1].BlendingOptions;
    GradientOverlayEffect gradientOverlayEffect = null;

    // Suche GradientOverlayEffect in einer Ebene.
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
        // Sie können ein neues GradientOverlayEffect erstellen, falls es nicht existiert.
        gradientOverlayEffect = layerBlendOptions.AddGradientOverlay();
    }

    // Fügen Sie dem Effekt ein wenig Transparenz hinzu.
    gradientOverlayEffect.Opacity = 200;

    // Ändern Sie den Mischmodus des Gradient-Effekts.
    gradientOverlayEffect.BlendMode = BlendMode.Hue;

    // Ruft das GradientFillSettings-Objekt ab, um die Gradient-Overlay-Einstellungen zu konfigurieren.
    GradientFillSettings settings = (GradientFillSettings)gradientOverlayEffect.Settings;
    SolidGradient solidGradient = (SolidGradient)settings.Gradient;

    // Festlegen eines neuen Gradienten mit zwei Farben.
    solidGradient.ColorPoints = new IGradientColorPoint[]
    {
        new GradientColorPoint(Color.GreenYellow, 0, 50),
        new GradientColorPoint(Color.BlueViolet, 4096, 50),
    };

    // Setzt die Neigung des Gradienten auf einen Winkel von 80 Grad.
    settings.Angle = 80;

    // Skaliert den Gradient-Effekt bis zu 150 %.
    settings.Scale = 150;

    // Setzt den Typ des Gradienten.
    settings.GradientType = GradientType.Linear;

    // Machen Sie den Gradient undurchsichtig, indem Sie die Opazität an jedem Transparenzpunkt auf 100 % setzen.
    solidGradient.TransparencyPoints[0].Opacity = 100;
    solidGradient.TransparencyPoints[1].Opacity = 100;

    psdImage.Save(outputFilePath);
}
```

### Siehe auch

* struct [Color](../../../aspose.psd/color/)
* class [GradientColorPoint](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../../)


