---
title: Class BlendingOptions
second_title: Referencia de API de Aspose.PSD para .NET
description: Aspose.PSD.FileFormats.Psd.Layers.LayerEffects.BlendingOptions clase. Opciones de fusión. Es un contenedor para Lfx2Resource que proporciona API para efectos de capa
type: docs
weight: 2100
url: /es/net/aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/
---
## BlendingOptions class

Opciones de fusión. Es un contenedor para Lfx2Resource que proporciona API para efectos de capa

```csharp
public class BlendingOptions
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Effects](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/effects/) { get; } | Obtiene los efectos. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddColorOverlay](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addcoloroverlay/)() | Agrega la superposición de color. |
| [AddDropShadow](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/adddropshadow/)() | Añade el efecto de sombra paralela. |
| [AddGradientOverlay](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addgradientoverlay/)() | Agrega la superposición de degradado. |
| [AddInnerShadow](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addinnershadow/)() | Añade el efecto de sombra interior. |
| [AddOuterGlow](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addouterglow/)() | Agrega el efecto de brillo exterior. |
| [AddPatternOverlay](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addpatternoverlay/)() | Agrega la superposición de Patrón. |
| [AddStroke](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addstroke/)(FillType) | Añade el efecto de trazo. |

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

* espacio de nombres [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../aspose.psd.fileformats.psd.layers.layereffects/)
* asamblea [Aspose.PSD](../../)


