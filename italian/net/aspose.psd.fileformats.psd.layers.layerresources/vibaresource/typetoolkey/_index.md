---
title: VibAResource.TypeToolKey
second_title: Aspose.PSD per riferimento API .NET
description: VibAResource campo. Il tasto informazioni dello strumento testo.
type: docs
weight: 80
url: /it/net/aspose.psd.fileformats.psd.layers.layerresources/vibaresource/typetoolkey/
---
## VibAResource.TypeToolKey field

Il tasto informazioni dello strumento testo.

```csharp
public const int TypeToolKey;
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


