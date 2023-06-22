---
title: GradientColorPoint.GradientColorPoint
second_title: Aspose.PSD for .NET API Reference
description: GradientColorPoint constructor. Initializes a new instance of the GradientColorPoint class
type: docs
weight: 10
url: /net/aspose.psd.fileformats.psd.layers.fillsettings/gradientcolorpoint/gradientcolorpoint/
---
{{< psd/tize >}}
## GradientColorPoint() {#constructor}

Initializes a new instance of the [`GradientColorPoint`](../) class.

```csharp
public GradientColorPoint()
```

### See Also

* class [GradientColorPoint](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../../)

---

## GradientColorPoint(Color, int, int) {#constructor_1}

Initializes a new instance of the [`GradientColorPoint`](../) class.

```csharp
public GradientColorPoint(Color color, int location, int medianPointLocation)
```

| Parameter | Type | Description |
| --- | --- | --- |
| color | Color | Color point on gradient. |
| location | Int32 | The location of the color point on the gradient. |
| medianPointLocation | Int32 | The median gradient point location. |

## Examples

The following example demonstrates how to create/edit the GradientOverlayEffect effect object in layer.

```csharp
[C#]

string sourceFilePath = "psdnet256.psd";
string outputFilePath = "psdnet256.psd_output.psd";

// Creates/Gets and edits the gradient overlay effect in a layer.
using (var psdImage = (PsdImage)Image.Load(sourceFilePath, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    BlendingOptions layerBlendOptions = psdImage.Layers[1].BlendingOptions;
    GradientOverlayEffect gradientOverlayEffect = null;

    // Search GradientOverlayEffect in a layer.
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
        // You can create a new GradientOverlayEffect if it not exists.
        gradientOverlayEffect = layerBlendOptions.AddGradientOverlay();
    }

    // Add a bit of transparency to the effect.
    gradientOverlayEffect.Opacity = 200;

    // Change the blend mode of gradient effect.
    gradientOverlayEffect.BlendMode = BlendMode.Hue;

    // Gets GradientFillSettings object to configure gradient overlay settings.
    GradientFillSettings settings = gradientOverlayEffect.Settings;

    // Setting a new gradient with two colors.
    settings.ColorPoints = new IGradientColorPoint[]
    {
        new GradientColorPoint(Color.GreenYellow, 0, 50),
        new GradientColorPoint(Color.BlueViolet, 4096, 50),
    };

    // Sets an inclination of the gradient at an angle of 80 degrees.
    settings.Angle = 80;

    // Scale gradient effect up to 150%.
    settings.Scale = 150;

    // Sets type of gradient.
    settings.GradientType = GradientType.Linear;

    // Make the gradient opaque by setting the opacity to 100% at each transparency point.
    settings.TransparencyPoints[0].Opacity = 100;
    settings.TransparencyPoints[1].Opacity = 100;

    psdImage.Save(outputFilePath);
}
```

### See Also

* struct [Color](../../../aspose.psd/color/)
* class [GradientColorPoint](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../../)


