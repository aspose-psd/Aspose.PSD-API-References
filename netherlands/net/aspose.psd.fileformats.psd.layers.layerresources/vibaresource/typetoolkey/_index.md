---
title: VibAResource.TypeToolKey
second_title: Aspose.PSD voor .NET API-referentie
description: VibAResource veld. De infotoets voor het typen van gereedschap.
type: docs
weight: 80
url: /nl/net/aspose.psd.fileformats.psd.layers.layerresources/vibaresource/typetoolkey/
---
## VibAResource.TypeToolKey field

De infotoets voor het typen van gereedschap.

```csharp
public const int TypeToolKey;
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


