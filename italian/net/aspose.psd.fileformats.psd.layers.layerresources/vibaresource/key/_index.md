---
title: VibAResource.Key
second_title: Aspose.PSD per riferimento API .NET
description: VibAResource proprietà. Ottiene la chiave della risorsa del livello.
type: docs
weight: 20
url: /it/net/aspose.psd.fileformats.psd.layers.layerresources/vibaresource/key/
---
## VibAResource.Key property

Ottiene la chiave della risorsa del livello.

```csharp
public override int Key { get; }
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


