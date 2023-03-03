---
title: BackgroundColorResource.MinimalVersion
second_title: Aspose.PSD per riferimento API .NET
description: BackgroundColorResource proprietà. Ottiene la versione PSD minima richiesta.
type: docs
weight: 40
url: /it/net/aspose.psd.fileformats.psd.resources/backgroundcolorresource/minimalversion/
---
## BackgroundColorResource.MinimalVersion property

Ottiene la versione PSD minima richiesta.

```csharp
public override int MinimalVersion { get; }
```

### Valore della proprietà

La versione minima del PSD.

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


