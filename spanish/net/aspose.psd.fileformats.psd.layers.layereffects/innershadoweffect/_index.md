---
title: "Clase InnerShadowEffect"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Clase Aspose.PSD.FileFormats.Psd.Layers.LayerEffects.InnerShadowEffect. Efecto de capa de sombra interna"
type: docs
weight: 2350
url: /es/net/aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/
---
{{< psd/tize >}}
## InnerShadowEffect class

Efecto de capa de sombra interna.

```csharp
public class InnerShadowEffect : IShadowEffect
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Angle](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/angle/) { get; set; } | Obtiene o establece el ángulo en grados. |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/blendmode/) { get; set; } | Obtiene o establece el modo de fusión. |
| [Color](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/color/) { get; set; } | Obtiene o establece el color. |
| [Distance](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/distance/) { get; set; } | Obtiene o establece la distancia en píxeles. |
| [EffectType](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/effecttype/) { get; } | Obtiene un tipo de efecto |
| [IsVisible](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/isvisible/) { get; set; } | Obtiene o establece un valor que indica si esta instancia es visible. |
| [Noise](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/noise/) { get; set; } | Obtiene o establece el ruido. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/opacity/) { get; set; } | Obtiene o establece la opacidad. |
| [Size](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/size/) { get; set; } | Obtiene o establece el valor de desenfoque en píxeles. |
| [Spread](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/spread/) { get; set; } | Obtiene o establece la expansión (estrangulamiento) como porcentaje. |
| [UseGlobalLight](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/usegloballight/) { get; set; } | Obtiene o establece un valor que indica si [use this angle in all of the layer effects]. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [GetEffectBounds](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/geteffectbounds/)(Rectangle, int) | Calcula y obtiene los límites de los píxeles del efecto basándose en los límites de los píxeles de la capa de entrada. |

## Ejemplos

El siguiente código muestra cómo cambiar la configuración del efecto de capa de sombra interna.

```csharp
[C#]

string sourceFile = "example.psd";
string outputFile = "sample_out.psd";

// Cargar una imagen existente en una instancia de la clase PsdImage
var loadOptions = new PsdLoadOptions();
loadOptions.LoadEffectsResource = true;
using (var image = (PsdImage)Image.Load(sourceFile, loadOptions))
{
    var layer = image.Layers[image.Layers.Length - 1];
    var shadowEffect = (IShadowEffect)layer.BlendingOptions.Effects[0];

    shadowEffect.Color = Color.Green;
    shadowEffect.Opacity = 128;
    shadowEffect.Distance = 1;
    shadowEffect.UseGlobalLight = false;
    shadowEffect.Size = 2;
    shadowEffect.Angle = 45;
    shadowEffect.Spread = 50;
    shadowEffect.Noise = 5;

    image.Save(outputFile, new PsdOptions(image));
}
```

### Ver también

* interface [IShadowEffect](../ishadoweffect/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../)


