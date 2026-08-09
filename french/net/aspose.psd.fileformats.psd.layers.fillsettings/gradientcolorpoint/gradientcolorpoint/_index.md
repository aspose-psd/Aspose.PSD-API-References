---
title: "GradientColorPoint.GradientColorPoint"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Constructeur GradientColorPoint. Initialise une nouvelle instance de la classe GradientColorPoint"
type: docs
weight: 10
url: /fr/net/aspose.psd.fileformats.psd.layers.fillsettings/gradientcolorpoint/gradientcolorpoint/
---
{{< psd/tize >}}
## GradientColorPoint() {#constructor}

Initialise une nouvelle instance de la classe [`GradientColorPoint`](../).

```csharp
public GradientColorPoint()
```

### Voir aussi

* class [GradientColorPoint](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../../)

---

## GradientColorPoint(Color, int, int) {#constructor_1}

Initialise une nouvelle instance de la classe [`GradientColorPoint`](../).

```csharp
public GradientColorPoint(Color color, int location, int medianPointLocation)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| couleur | Couleur | Point de couleur sur le dégradé. |
| emplacement | Int32 | L'emplacement du point de couleur sur le dégradé. |
| medianPointLocation | Int32 | L'emplacement du point médian du dégradé. |

## Exemples

L'exemple suivant montre comment créer/modifier l'objet d'effet GradientOverlayEffect dans le calque.

```csharp
[C#]

string sourceFilePath = "psdnet256.psd";
string outputFilePath = "psdnet256.psd_output.psd";

// Crée/Obtient et modifie l'effet de superposition de dégradé dans un calque.
using (var psdImage = (PsdImage)Image.Load(sourceFilePath, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    BlendingOptions layerBlendOptions = psdImage.Layers[1].BlendingOptions;
    GradientOverlayEffect gradientOverlayEffect = null;

    // Rechercher GradientOverlayEffect dans un calque.
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
        // Vous pouvez créer un nouveau GradientOverlayEffect s'il n'existe pas.
        gradientOverlayEffect = layerBlendOptions.AddGradientOverlay();
    }

    // Ajoutez un peu de transparence à l'effet.
    gradientOverlayEffect.Opacity = 200;

    // Changez le mode de fusion de l'effet de dégradé.
    gradientOverlayEffect.BlendMode = BlendMode.Hue;

    // Obtient l'objet GradientFillSettings pour configurer les paramètres de superposition de dégradé.
    GradientFillSettings settings = (GradientFillSettings)gradientOverlayEffect.Settings;
    SolidGradient solidGradient = (SolidGradient)settings.Gradient;

    // Définition d'un nouveau dégradé avec deux couleurs.
    solidGradient.ColorPoints = new IGradientColorPoint[]
    {
        new GradientColorPoint(Color.GreenYellow, 0, 50),
        new GradientColorPoint(Color.BlueViolet, 4096, 50),
    };

    // Définit une inclinaison du dégradé à un angle de 80 degrés.
    settings.Angle = 80;

    // Mettez à l'échelle l'effet de dégradé jusqu'à 150 %.
    settings.Scale = 150;

    // Définit le type de dégradé.
    settings.GradientType = GradientType.Linear;

    // Rendez le dégradé opaque en réglant l'opacité à 100 % à chaque point de transparence.
    solidGradient.TransparencyPoints[0].Opacity = 100;
    solidGradient.TransparencyPoints[1].Opacity = 100;

    psdImage.Save(outputFilePath);
}
```

### Voir aussi

* struct [Color](../../../aspose.psd/color/)
* class [GradientColorPoint](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../../)


