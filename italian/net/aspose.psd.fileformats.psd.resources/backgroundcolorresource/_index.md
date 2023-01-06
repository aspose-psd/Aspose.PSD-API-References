---
title: BackgroundColorResource
second_title: Riferimento all'API di Aspose.PSD per .NET
description: La risorsa con le informazioni sui bordi delle impostazioni di stampa dellimmagine.
type: docs
weight: 3580
url: /it/net/aspose.psd.fileformats.psd.resources/backgroundcolorresource/
---
## BackgroundColorResource class

La risorsa con le informazioni sui bordi delle impostazioni di stampa dell'immagine.

```csharp
public sealed class BackgroundColorResource : ResourceBlock
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [BackgroundColorResource](backgroundcolorresource)() | Default_Costruttore |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Color](../../aspose.psd.fileformats.psd.resources/backgroundcolorresource/color) { get; set; } | Ottiene o imposta il colore di sfondo. |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/backgroundcolorresource/datasize) { get; } | Ottiene la dimensione dei dati della risorsa in byte. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id) { get; set; } | Ottiene o imposta l'identificatore univoco per la risorsa. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/backgroundcolorresource/minimalversion) { get; } | Ottiene la versione PSD minima richiesta. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name) { get; set; } | Ottiene o imposta il nome della risorsa. Stringa Pascal, imbottita per rendere uniforme la dimensione (un nome null è costituito da due byte di 0). |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature) { get; } | Ottiene la firma della risorsa. Dovrebbe essere sempre '8BIM'. |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size) { get; } | Ottiene la dimensione del blocco di risorse in byte inclusi i suoi dati. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save)(StreamContainer) | Salva il blocco di risorse nel flusso specificato. |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues)() | Convalida i valori delle risorse. |

### Esempi

Nell'esempio seguente viene illustrato il supporto della risorsa BackgroundColorResource.

```csharp
[C#]

string sourceFilePath = "input.psd";
string outputFilePath = "output.psd";

using (var image = (PsdImage)Image.Load(sourceFilePath))
{
    ResourceBlock[] imageResources = image.ImageResources;
    BackgroundColorResource backgroundColorResource = null;
    foreach (var imageResource in imageResources)
    {
        if (imageResource is BackgroundColorResource)
        {
            backgroundColorResource = (BackgroundColorResource)imageResource;
            break;
        }
    }

    // aggiorna BackgroundColorResource
    backgroundColorResource.Color = Color.DarkRed;

    image.Save(outputFilePath);
}
```

### Guarda anche

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources)
* assemblea [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->