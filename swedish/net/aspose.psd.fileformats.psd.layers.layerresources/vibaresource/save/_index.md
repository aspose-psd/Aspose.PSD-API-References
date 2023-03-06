---
title: VibAResource.Save
second_title: Aspose.PSD för .NET API-referens
description: VibAResource metod. Sparar resursen till den angivna strömbehållaren.
type: docs
weight: 70
url: /sv/net/aspose.psd.fileformats.psd.layers.layerresources/vibaresource/save/
---
## VibAResource.Save method

Sparar resursen till den angivna strömbehållaren.

```csharp
public override void Save(StreamContainer streamContainer, int psdVersion)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| streamContainer | StreamContainer | Strömbehållaren att spara till. |
| psdVersion | Int32 | PSD-versionen. |

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

* class [StreamContainer](../../../aspose.psd/streamcontainer/)
* class [VibAResource](../)
* namnutrymme [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../vibaresource/)
* hopsättning [Aspose.PSD](../../../)


