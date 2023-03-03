---
title: GradientColorPoint.GradientColorPoint
second_title: Aspose.PSD per riferimento API .NET
description: GradientColorPoint costruttore. Inizializza una nuova istanza diGradientColorPoint classe.
type: docs
weight: 10
url: /it/net/aspose.psd.fileformats.psd.layers.fillsettings/gradientcolorpoint/gradientcolorpoint/
---
## GradientColorPoint() {#constructor}

Inizializza una nuova istanza di[`GradientColorPoint`](../) classe.

```csharp
public GradientColorPoint()
```

### Guarda anche

* class [GradientColorPoint](../)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../gradientcolorpoint/)
* assemblea [Aspose.PSD](../../../)

---

## GradientColorPoint(Color, int, int) {#constructor_1}

Inizializza una nuova istanza di[`GradientColorPoint`](../) classe.

```csharp
public GradientColorPoint(Color color, int location, int medianPointLocation)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| color | Color | Punto di colore sul gradiente. |
| location | Int32 | La posizione del punto di colore sulla sfumatura. |
| medianPointLocation | Int32 | La posizione del punto del gradiente mediano. |

### Esempi

L'esempio seguente mostra come creare/modificare l'oggetto effetto GradientOverlayEffect nel livello.

```csharp
[C#]

string sourceFilePath = "psdnet256.psd";
string outputFilePath = "psdnet256.psd_output.psd";

// Crea/Ottiene e modifica l'effetto di sovrapposizione sfumatura in un livello.
using (var psdImage = (PsdImage)Image.Load(sourceFilePath, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    BlendingOptions layerBlendOptions = psdImage.Layers[1].BlendingOptions;
    GradientOverlayEffect gradientOverlayEffect = null;

    // Cerca GradientOverlayEffect in un livello.
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
        // Puoi creare un nuovo GradientOverlayEffect se non esiste.
        gradientOverlayEffect = layerBlendOptions.AddGradientOverlay();
    }

    // Aggiungi un po' di trasparenza all'effetto.
    gradientOverlayEffect.Opacity = 200;

    // Modifica la modalità di fusione dell'effetto sfumatura.
    gradientOverlayEffect.BlendMode = BlendMode.Hue;

    // Ottiene l'oggetto GradientFillSettings per configurare le impostazioni di sovrapposizione del gradiente.
    GradientFillSettings settings = gradientOverlayEffect.Settings;

    // Impostazione di un nuovo gradiente con due colori.
    settings.ColorPoints = new IGradientColorPoint[]
    {
        new GradientColorPoint(Color.GreenYellow, 0, 50),
        new GradientColorPoint(Color.BlueViolet, 4096, 50),
    };

    // Imposta un'inclinazione del gradiente ad un angolo di 80 gradi.
    settings.Angle = 80;

    // Ridimensiona l'effetto gradiente fino al 150%.
    settings.Scale = 150;

    // Imposta il tipo di gradiente.
    settings.GradientType = GradientType.Linear;

    // Rendi opaco il gradiente impostando l'opacità al 100% in ogni punto di trasparenza.
    settings.TransparencyPoints[0].Opacity = 100;
    settings.TransparencyPoints[1].Opacity = 100;

    psdImage.Save(outputFilePath);
}
```

### Guarda anche

* struct [Color](../../../aspose.psd/color/)
* class [GradientColorPoint](../)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../gradientcolorpoint/)
* assemblea [Aspose.PSD](../../../)


