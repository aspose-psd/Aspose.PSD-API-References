---
title: "GradientColorPoint.GradientColorPoint"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Constructor GradientColorPoint. Inicializa una nueva instancia de la clase GradientColorPoint"
type: docs
weight: 10
url: /es/net/aspose.psd.fileformats.psd.layers.fillsettings/gradientcolorpoint/gradientcolorpoint/
---
{{< psd/tize >}}
## GradientColorPoint() {#constructor}

Inicializa una nueva instancia de la clase [`GradientColorPoint`](../).

```csharp
public GradientColorPoint()
```

### Ver también

* class [GradientColorPoint](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../../)

---

## GradientColorPoint(Color, int, int) {#constructor_1}

Inicializa una nueva instancia de la clase [`GradientColorPoint`](../).

```csharp
public GradientColorPoint(Color color, int location, int medianPointLocation)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| color | Color | Punto de color en el degradado. |
| ubicación | Int32 | La ubicación del punto de color en el degradado. |
| medianPointLocation | Int32 | La ubicación del punto medio del degradado. |

## Ejemplos

El siguiente ejemplo muestra cómo crear/editar el objeto de efecto GradientOverlayEffect en una capa.

```csharp
[C#]

string sourceFilePath = "psdnet256.psd";
string outputFilePath = "psdnet256.psd_output.psd";

// Crea/Obtiene y edita el efecto de superposición de degradado en una capa.
using (var psdImage = (PsdImage)Image.Load(sourceFilePath, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    BlendingOptions layerBlendOptions = psdImage.Layers[1].BlendingOptions;
    GradientOverlayEffect gradientOverlayEffect = null;

    // Buscar GradientOverlayEffect en una capa.
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
        // Puedes crear un nuevo GradientOverlayEffect si no existe.
        gradientOverlayEffect = layerBlendOptions.AddGradientOverlay();
    }

    // Añade un poco de transparencia al efecto.
    gradientOverlayEffect.Opacity = 200;

    // Cambia el modo de fusión del efecto de degradado.
    gradientOverlayEffect.BlendMode = BlendMode.Hue;

    // Obtiene el objeto GradientFillSettings para configurar los ajustes de superposición de degradado.
    GradientFillSettings settings = (GradientFillSettings)gradientOverlayEffect.Settings;
    SolidGradient solidGradient = (SolidGradient)settings.Gradient;

    // Estableciendo un nuevo degradado con dos colores.
    solidGradient.ColorPoints = new IGradientColorPoint[]
    {
        new GradientColorPoint(Color.GreenYellow, 0, 50),
        new GradientColorPoint(Color.BlueViolet, 4096, 50),
    };

    // Establece una inclinación del degradado en un ángulo de 80 grados.
    settings.Angle = 80;

    // Escala el efecto de degradado hasta un 150%.
    settings.Scale = 150;

    // Establece el tipo de degradado.
    settings.GradientType = GradientType.Linear;

    // Haz que el degradado sea opaco estableciendo la opacidad al 100% en cada punto de transparencia.
    solidGradient.TransparencyPoints[0].Opacity = 100;
    solidGradient.TransparencyPoints[1].Opacity = 100;

    psdImage.Save(outputFilePath);
}
```

### Ver también

* struct [Color](../../../aspose.psd/color/)
* class [GradientColorPoint](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../../)


