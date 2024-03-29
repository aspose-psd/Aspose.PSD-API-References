---
title: GradientColorPoint.GradientColorPoint
second_title: Aspose.PSD für .NET-API-Referenz
description: GradientColorPoint constructeur. Initialisiert eine neue Instanz vonGradientColorPoint Klasse.
type: docs
weight: 10
url: /de/net/aspose.psd.fileformats.psd.layers.fillsettings/gradientcolorpoint/gradientcolorpoint/
---
## GradientColorPoint() {#constructor}

Initialisiert eine neue Instanz von[`GradientColorPoint`](../) Klasse.

```csharp
public GradientColorPoint()
```

### Siehe auch

* class [GradientColorPoint](../)
* namensraum [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../gradientcolorpoint/)
* Montage [Aspose.PSD](../../../)

---

## GradientColorPoint(Color, int, int) {#constructor_1}

Initialisiert eine neue Instanz von[`GradientColorPoint`](../) Klasse.

```csharp
public GradientColorPoint(Color color, int location, int medianPointLocation)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| color | Color | Farbpunkt auf Farbverlauf. |
| location | Int32 | Die Position des Farbpunkts auf dem Farbverlauf. |
| medianPointLocation | Int32 | Die Position des mittleren Gradientenpunkts. |

### Beispiele

Das folgende Beispiel zeigt, wie das GradientOverlayEffect-Effektobjekt in einer Ebene erstellt/bearbeitet wird.

```csharp
[C#]

string sourceFilePath = "psdnet256.psd";
string outputFilePath = "psdnet256.psd_output.psd";

// Erstellt/erhält und bearbeitet den Verlaufsüberlagerungseffekt in einer Ebene.
using (var psdImage = (PsdImage)Image.Load(sourceFilePath, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    BlendingOptions layerBlendOptions = psdImage.Layers[1].BlendingOptions;
    GradientOverlayEffect gradientOverlayEffect = null;

    // GradientOverlayEffect in einer Ebene suchen.
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
        // Sie können einen neuen GradientOverlayEffect erstellen, falls er nicht existiert.
        gradientOverlayEffect = layerBlendOptions.AddGradientOverlay();
    }

    // Fügen Sie dem Effekt etwas Transparenz hinzu.
    gradientOverlayEffect.Opacity = 200;

    // Ändern Sie den Mischmodus des Verlaufseffekts.
    gradientOverlayEffect.BlendMode = BlendMode.Hue;

    // Ruft das GradientFillSettings-Objekt ab, um die Verlaufsüberlagerungseinstellungen zu konfigurieren.
    GradientFillSettings settings = gradientOverlayEffect.Settings;

    // Setzen eines neuen Farbverlaufs mit zwei Farben.
    settings.ColorPoints = new IGradientColorPoint[]
    {
        new GradientColorPoint(Color.GreenYellow, 0, 50),
        new GradientColorPoint(Color.BlueViolet, 4096, 50),
    };

    // Legt eine Neigung des Farbverlaufs in einem Winkel von 80 Grad fest.
    settings.Angle = 80;

    // Gradienteneffekt bis zu 150 % skalieren.
    settings.Scale = 150;

    // Legt die Art des Farbverlaufs fest.
    settings.GradientType = GradientType.Linear;

    // Machen Sie den Farbverlauf undurchsichtig, indem Sie die Deckkraft an jedem Transparenzpunkt auf 100 % setzen.
    settings.TransparencyPoints[0].Opacity = 100;
    settings.TransparencyPoints[1].Opacity = 100;

    psdImage.Save(outputFilePath);
}
```

### Siehe auch

* struct [Color](../../../aspose.psd/color/)
* class [GradientColorPoint](../)
* namensraum [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../gradientcolorpoint/)
* Montage [Aspose.PSD](../../../)


