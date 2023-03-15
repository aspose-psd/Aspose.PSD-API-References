---
title: Class VibAResource
second_title: Aspose.PSD för .NET API-referens
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.VibAResource klass. VibA Resource.
type: docs
weight: 3350
url: /sv/net/aspose.psd.fileformats.psd.layers.layerresources/vibaresource/
---
## VibAResource class

VibA Resource.

```csharp
public class VibAResource : AdjustmentLayerResource
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [VibAResource](vibaresource/)() | Initierar en ny instans av`VibAResource` class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/vibaresource/key/) { get; } | Hämtar lagerresursnyckeln. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/vibaresource/length/) { get; } | Hämtar lagerresurslängden i byte. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/vibaresource/psdversion/) { get; } | Hämtar psd-versionen. |
| [Saturation](../../aspose.psd.fileformats.psd.layers.layerresources/vibaresource/saturation/) { get; set; } | Hämtar eller ställer in mättnadsvärde |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/signature/) { get; } | Får signaturen. |
| [Vibrance](../../aspose.psd.fileformats.psd.layers.layerresources/vibaresource/vibrance/) { get; set; } | Får eller ställer in vibransvärde |

## Metoder

| namn | Beskrivning |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/vibaresource/save/)(StreamContainer, int) | Sparar resursen till den angivna strömbehållaren. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Returnerar enString som representerar denna instans. |

## Fält

| namn | Beskrivning |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/vibaresource/typetoolkey/) | Typverktygets infonyckel. |

### Exempel

Följande kodexempel visar stödet för VibAResource-resursen.

```csharp
[C#]

// Exempel på stöd för läs- och skrivvibrationsresurs vid körning.
string sourceFileName = "VibranceResource.psd";
string outputFileName = "out_VibranceResource.psd";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    foreach (var layer in image.Layers)
    {
        foreach (var resource in layer.Resources)
        {
            if (resource is VibAResource)
            {
                var vibranceResource = (VibAResource)resource;

                int vibranceValue =  vibranceResource.Vibrance;
                int saturationValue = vibranceResource.Saturation;

                vibranceResource.Vibrance = vibranceValue * 2;
                vibranceResource.Saturation = saturationValue * 2;

                break;
            }
        }
    }

    image.Save(outputFileName);
}
```

### Se även

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* namnutrymme [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* hopsättning [Aspose.PSD](../../)


