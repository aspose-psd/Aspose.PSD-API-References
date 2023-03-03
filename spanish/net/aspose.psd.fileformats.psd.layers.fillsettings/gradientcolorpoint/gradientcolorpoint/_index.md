---
title: GradientColorPoint.GradientColorPoint
second_title: Referencia de API de Aspose.PSD para .NET
description: GradientColorPoint constructor. Inicializa una nueva instancia delGradientColorPoint clase.
type: docs
weight: 10
url: /es/net/aspose.psd.fileformats.psd.layers.fillsettings/gradientcolorpoint/gradientcolorpoint/
---
## GradientColorPoint() {#constructor}

Inicializa una nueva instancia del[`GradientColorPoint`](../) clase.

```csharp
public GradientColorPoint()
```

### Ver también

* class [GradientColorPoint](../)
* espacio de nombres [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../gradientcolorpoint/)
* asamblea [Aspose.PSD](../../../)

---

## GradientColorPoint(Color, int, int) {#constructor_1}

Inicializa una nueva instancia del[`GradientColorPoint`](../) clase.

```csharp
public GradientColorPoint(Color color, int location, int medianPointLocation)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| color | Color | Punto de color en degradado. |
| location | Int32 | La ubicación del punto de color en el degradado. |
| medianPointLocation | Int32 | La ubicación del punto de gradiente medio. |

### Ejemplos

El siguiente ejemplo muestra cómo crear/editar el objeto de efecto GradientOverlayEffect en la capa.

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
        // Puede crear un nuevo GradientOverlayEffect si no existe.
        gradientOverlayEffect = layerBlendOptions.AddGradientOverlay();
    }

    // Agrega un poco de transparencia al efecto.
    gradientOverlayEffect.Opacity = 200;

    // Cambiar el modo de fusión del efecto degradado.
    gradientOverlayEffect.BlendMode = BlendMode.Hue;

    // Obtiene el objeto GradientFillSettings para configurar los ajustes de superposición de degradado.
    GradientFillSettings settings = gradientOverlayEffect.Settings;

    // Establecer un nuevo degradado con dos colores.
    settings.ColorPoints = new IGradientColorPoint[]
    {
        new GradientColorPoint(Color.GreenYellow, 0, 50),
        new GradientColorPoint(Color.BlueViolet, 4096, 50),
    };

    // Establece una inclinación del gradiente en un ángulo de 80 grados.
    settings.Angle = 80;

    // Escale el efecto de degradado hasta un 150 %.
    settings.Scale = 150;

    // Establece el tipo de degradado.
    settings.GradientType = GradientType.Linear;

    // Haga que el degradado sea opaco configurando la opacidad al 100% en cada punto de transparencia.
    settings.TransparencyPoints[0].Opacity = 100;
    settings.TransparencyPoints[1].Opacity = 100;

    psdImage.Save(outputFilePath);
}
```

### Ver también

* struct [Color](../../../aspose.psd/color/)
* class [GradientColorPoint](../)
* espacio de nombres [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../gradientcolorpoint/)
* asamblea [Aspose.PSD](../../../)


