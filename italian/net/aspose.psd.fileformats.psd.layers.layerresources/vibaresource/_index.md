---
title: Class VibAResource
second_title: Aspose.PSD per riferimento API .NET
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.VibAResource classe. Risorsa VibA.
type: docs
weight: 3350
url: /it/net/aspose.psd.fileformats.psd.layers.layerresources/vibaresource/
---
## VibAResource class

Risorsa VibA.

```csharp
public class VibAResource : AdjustmentLayerResource
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [VibAResource](vibaresource/)() | Inizializza una nuova istanza di`VibAResource` classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/vibaresource/key/) { get; } | Ottiene la chiave della risorsa del livello. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/vibaresource/length/) { get; } | Ottiene la lunghezza della risorsa del livello in byte. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/vibaresource/psdversion/) { get; } | Ottiene la versione psd. |
| [Saturation](../../aspose.psd.fileformats.psd.layers.layerresources/vibaresource/saturation/) { get; set; } | Ottiene o imposta il valore di saturazione |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/signature/) { get; } | Ottiene la firma. |
| [Vibrance](../../aspose.psd.fileformats.psd.layers.layerresources/vibaresource/vibrance/) { get; set; } | Ottiene o imposta il valore di vibrazione |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/vibaresource/save/)(StreamContainer, int) | Salva la risorsa nel contenitore del flusso specificato. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Restituisce aString che rappresenta questa istanza. |

## Campi

| Nome | Descrizione |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/vibaresource/typetoolkey/) | Il tasto informazioni dello strumento testo. |

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

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assemblea [Aspose.PSD](../../)


