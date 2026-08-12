---
title: "Clase DropShadowEffect"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Clase Aspose.PSD.FileFormats.Psd.Layers.LayerEffects.DropShadowEffect. Efecto de capa de sombra paralela"
type: docs
weight: 2310
url: /es/net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/
---
{{< psd/tize >}}
## DropShadowEffect class

Efecto de capa de sombra paralela.

```csharp
public class DropShadowEffect : IShadowEffect
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Angle](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/angle/) { get; set; } | Obtiene o establece el ángulo en grados. |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/blendmode/) { get; set; } | Obtiene o establece el modo de fusión. |
| [Color](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/color/) { get; set; } | Obtiene o establece el color. |
| [Distance](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/distance/) { get; set; } | Obtiene o establece la distancia en píxeles. |
| [EffectType](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/effecttype/) { get; } | Obtiene un tipo de efecto |
| [IsVisible](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/isvisible/) { get; set; } | Obtiene o establece un valor que indica si esta instancia es visible. |
| [KnocksOut](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/knocksout/) { get; set; } | Obtiene o establece un valor que indica si [knocks out]. |
| [Noise](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/noise/) { get; set; } | Obtiene o establece el ruido. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/opacity/) { get; set; } | Obtiene o establece la opacidad. |
| [Size](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/size/) { get; set; } | Obtiene o establece el valor de desenfoque en píxeles. |
| [Spread](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/spread/) { get; set; } | Obtiene o establece la intensidad como un porcentaje. |
| [UseGlobalLight](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/usegloballight/) { get; set; } | Obtiene o establece un valor que indica si [use this angle in all of the layer effects]. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [GetEffectBounds](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/geteffectbounds/)(Rectangle, int) | Calcula y obtiene los límites de los píxeles del efecto basándose en los límites de los píxeles de la capa de entrada. |

## Ejemplos

El siguiente código demuestra el soporte de la propiedad PsdImage.GlobalAngle para cambiar el valor del ángulo global.

```csharp
[C#]

// Cuando la propiedad DropShadowEffect.UseGlobalLight es 'true', el objeto DropShadowEffect utiliza el valor del ángulo de la propiedad PsdImage.GlobalAngle.

using (PsdImage image = (PsdImage)Image.Load("4.psd"))
{
    image.GlobalAngle = 30;
    image.Save("output.psd");
}
```

El siguiente código demuestra el uso de la propiedad Opacity de DropShadowEffect.

```csharp
[C#]

string inputFile = "input.psd";
string outputImage20 = "outputImage20.png";
string outputImage200 = "outputImage200.png";

using (PsdImage psdImage = (PsdImage)Image.Load(inputFile, new LoadOptions()))
{
    Layer workLayer = psdImage.Layers[1];

    DropShadowEffect dropShadowEffect = workLayer.BlendingOptions.AddDropShadow();
    dropShadowEffect.Distance = 0;
    dropShadowEffect.Size = 8;

    // Ejemplo con Opacity = 20
    dropShadowEffect.Opacity = 20;
    psdImage.Save(outputImage20, new PngOptions());

    // Ejemplo con Opacity = 200
    dropShadowEffect.Opacity = 200;
    psdImage.Save(outputImage200, new PngOptions());
}
```

### Ver también

* interface [IShadowEffect](../ishadoweffect/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../)


