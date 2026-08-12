---
title: "Clase OuterGlowEffect"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Clase Aspose.PSD.FileFormats.Psd.Layers.LayerEffects.OuterGlowEffect. Efecto de capa de resplandor externo."
type: docs
weight: 2370
url: /es/net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/
---
{{< psd/tize >}}
## OuterGlowEffect class

Efecto de capa de resplandor externo.

```csharp
public class OuterGlowEffect : ILayerEffect
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/blendmode/) { get; set; } | Obtiene o establece el modo de fusión. |
| [EffectType](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/effecttype/) { get; } | Obtiene un tipo de efecto. |
| [FillColor](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/fillcolor/) { get; set; } | Obtiene o establece el color. |
| [Intensity](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/intensity/) { get; set; } | Obtiene o establece el ángulo en grados. |
| [IsAntiAliasing](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/isantialiasing/) { get; set; } | Obtiene o establece el efecto AntiAliasing habilitado. |
| [IsSoftBlend](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/issoftblend/) { get; set; } | Obtiene o establece un valor que indica si [knocks out]. |
| [IsVisible](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/isvisible/) { get; set; } | Obtiene o establece un valor que indica si esta instancia es visible. |
| [Jitter](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/jitter/) { get; set; } | Obtiene o establece el ruido. |
| [Noise](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/noise/) { get; set; } | Obtiene o establece el ruido. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/opacity/) { get; set; } | Obtiene o establece la opacidad. |
| [Range](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/range/) { get; set; } | Obtiene o establece el ruido. |
| [Size](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/size/) { get; set; } | Obtiene el valor de desenfoque en píxeles. |
| [Spread](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/spread/) { get; set; } | Obtiene o establece la intensidad como un porcentaje. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [GetEffectBounds](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/geteffectbounds/)(Rectangle, int) | Calcula y obtiene los límites de los píxeles del efecto basándose en los límites de los píxeles de la capa de entrada. |

## Ejemplos

El siguiente código demuestra el soporte de OuterGlowEffect.

```csharp
[C#]

string src = "GreenLayer.psd";
string outputPng = "output261.png";

using (var image = (PsdImage)Image.Load(src))
{
    OuterGlowEffect effect = image.Layers[1].BlendingOptions.AddOuterGlow();
    effect.Range = 10;
    effect.Spread = 10;
    ((IColorFillSettings)effect.FillColor).Color = Color.Red;
    effect.Opacity = 128;
    effect.BlendMode = BlendMode.Normal;

    image.Save(outputPng, new PngOptions());
}
```

### Ver también

* interface [ILayerEffect](../ilayereffect/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../)


