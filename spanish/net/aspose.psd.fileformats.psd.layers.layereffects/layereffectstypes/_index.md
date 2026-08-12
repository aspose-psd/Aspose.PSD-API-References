---
title: "Enumeración LayerEffectsTypes"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerEffects.LayerEffectsTypes enum. Efectos de fusión de capa"
type: docs
weight: 2360
url: /es/net/aspose.psd.fileformats.psd.layers.layereffects/layereffectstypes/
---
{{< psd/tize >}}
## LayerEffectsTypes enumeration

Efectos de fusión de capa.

```csharp
public enum LayerEffectsTypes
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| DropShadow | `0` | La sombra paralela. |
| OuterGlow | `1` | El resplandor exterior. |
| PatternOverlay | `2` | La superposición de patrón. |
| GradientOverlay | `3` | La superposición de degradado. |
| ColorOverlay | `4` | La superposición de color. |
| Satin | `5` | El tipo de efecto satinado. |
| InnerGlow | `6` | El resplandor interno. |
| InnerShadow | `7` | La sombra interna. |
| Stroke | `8` | El trazo. |
| BevelEmboss | `9` | El biselado en relieve. |

## Ejemplos

El siguiente código demuestra el soporte de la propiedad ILayerEffect.EffectType.

```csharp
[C#]

string inputFile = "input.psd";
string outputWithout = "outputWithout.png";
string outputWith = "outputWith.png";

using (PsdImage psdImage = (PsdImage)Image.Load(inputFile, new LoadOptions()))
{
    psdImage.Save(outputWithout, new PngOptions());

    Layer workLayer = psdImage.Layers[1];

    DropShadowEffect dropShadowEffect = workLayer.BlendingOptions.AddDropShadow();
    dropShadowEffect.Distance = 0;
    dropShadowEffect.Size = 8;
    dropShadowEffect.Opacity = 20;

    foreach (ILayerEffect iEffect in workLayer.BlendingOptions.Effects)
    {
        if (iEffect.EffectType == LayerEffectsTypes.DropShadow)
        {
            // lo atrapó
            psdImage.Save(outputWith, new PngOptions());
        }
    }
}
```

### Ver también

* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../)


