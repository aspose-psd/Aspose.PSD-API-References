---
title: Class InnerShadowEffect
second_title: Referencia de API de Aspose.PSD para .NET
description: Aspose.PSD.FileFormats.Psd.Layers.LayerEffects.InnerShadowEffect clase. Efecto de capa de sombra interna
type: docs
weight: 2160
url: /es/net/aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/
---
## InnerShadowEffect class

Efecto de capa de sombra interna

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
| [IsVisible](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/isvisible/) { get; set; } | Obtiene o establece un valor que indica si esta instancia está visible. |
| [Noise](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/noise/) { get; set; } | Obtiene o establece el ruido. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/opacity/) { get; set; } | Obtiene o establece la opacidad. |
| [Size](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/size/) { get; set; } | Obtiene o establece el valor de desenfoque en píxeles. |
| [Spread](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/spread/) { get; set; } | Obtiene o establece el spread (choke) como porcentaje. |
| [UseGlobalLight](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/usegloballight/) { get; set; } | Obtiene o establece un valor que indica si [usar este ángulo en todos los efectos de capa]. |

### Ejemplos

El siguiente código demuestra cómo cambiar la configuración del efecto de capa de sombra interior.

```csharp
[C#]

string sourceFile = "example.psd";
string outputFile = "sample_out.psd";

// Carga una imagen existente en una instancia de la clase PsdImage
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
* espacio de nombres [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../aspose.psd.fileformats.psd.layers.layereffects/)
* asamblea [Aspose.PSD](../../)


