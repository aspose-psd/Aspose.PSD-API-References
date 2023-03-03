---
title: BackgroundColorResource.DataSize
second_title: Aspose.PSD per riferimento API .NET
description: BackgroundColorResource proprietà. Ottiene la dimensione dei dati della risorsa in byte.
type: docs
weight: 30
url: /it/net/aspose.psd.fileformats.psd.resources/backgroundcolorresource/datasize/
---
## BackgroundColorResource.DataSize property

Ottiene la dimensione dei dati della risorsa in byte.

```csharp
public override int DataSize { get; }
```

### Valore della proprietà

La dimensione dei dati della risorsa.

### Esempi

L'esempio seguente dimostra il supporto della risorsa BackgroundColorResource.

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

* class [BackgroundColorResource](../)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Resources](../../backgroundcolorresource/)
* assemblea [Aspose.PSD](../../../)


