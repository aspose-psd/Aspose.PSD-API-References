---
title: VibAResource.Saturation
second_title: Aspose.PSD för .NET API-referens
description: VibAResource fast egendom. Hämtar eller ställer in mättnadsvärde
type: docs
weight: 50
url: /sv/net/aspose.psd.fileformats.psd.layers.layerresources/vibaresource/saturation/
---
## VibAResource.Saturation property

Hämtar eller ställer in mättnadsvärde

```csharp
public int Saturation { get; set; }
```

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

* class [VibAResource](../)
* namnutrymme [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../vibaresource/)
* hopsättning [Aspose.PSD](../../../)


