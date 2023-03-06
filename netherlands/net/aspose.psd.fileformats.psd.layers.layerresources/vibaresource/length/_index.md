---
title: VibAResource.Length
second_title: Aspose.PSD voor .NET API-referentie
description: VibAResource eigendom. Haalt de resourcelengte van de laag op in bytes.
type: docs
weight: 30
url: /nl/net/aspose.psd.fileformats.psd.layers.layerresources/vibaresource/length/
---
## VibAResource.Length property

Haalt de resourcelengte van de laag op in bytes.

```csharp
public override int Length { get; }
```

### Voorbeelden

Het volgende codevoorbeeld demonstreert de ondersteuning van de VibAResource-resource.

```csharp
[C#]

// Voorbeeld van de ondersteuning van lezen en schrijven Vibration Resource tijdens runtime.
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

### Zie ook

* class [VibAResource](../)
* naamruimte [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../vibaresource/)
* montage [Aspose.PSD](../../../)


