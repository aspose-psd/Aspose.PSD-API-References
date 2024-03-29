---
title: VibAResource.PsdVersion
second_title: Aspose.PSD per riferimento API .NET
description: VibAResource proprietà. Ottiene la versione psd.
type: docs
weight: 40
url: /it/net/aspose.psd.fileformats.psd.layers.layerresources/vibaresource/psdversion/
---
## VibAResource.PsdVersion property

Ottiene la versione psd.

```csharp
public override int PsdVersion { get; }
```

### Esempi

L'esempio di codice seguente illustra il supporto della risorsa VibAResource.

```csharp
[C#]

// Esempio del supporto di lettura e scrittura Vibration Resource in fase di esecuzione.
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

### Guarda anche

* class [VibAResource](../)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../vibaresource/)
* assemblea [Aspose.PSD](../../../)


