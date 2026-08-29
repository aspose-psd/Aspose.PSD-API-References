---
title: "VibAResource.TypeToolKey"
second_title: "Aspose.PSD för .NET API‑referens"
description: "VibAResource fält. Den typverktygsinformationsnyckeln"
type: docs
weight: 60
url: /sv/net/aspose.psd.fileformats.psd.layers.layerresources/vibaresource/typetoolkey/
---
{{< psd/tize >}}
## VibAResource.TypeToolKey field

Typverktygsinformationsnyckeln.

```csharp
public const int TypeToolKey;
```

## Exempel

Följande kodexempel visar stödet för VibAResource-resursen.

```csharp
[C#]

// Exempel på stöd för läsning och skrivning av Vibrationsresurs vid körning.
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
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


