---
title: BorderInformationResource.MinimalVersion
second_title: Aspose.PSD per riferimento API .NET
description: BorderInformationResource proprietà. Ottiene la versione PSD minima richiesta.
type: docs
weight: 30
url: /it/net/aspose.psd.fileformats.psd.resources/borderinformationresource/minimalversion/
---
## BorderInformationResource.MinimalVersion property

Ottiene la versione PSD minima richiesta.

```csharp
public override int MinimalVersion { get; }
```

### Valore della proprietà

La versione minima del PSD.

### Esempi

L'esempio seguente dimostra il supporto della risorsa BorderInformationResource.

```csharp
[C#]

string sourceFilePath = "input.psd";
string outputFilePath = "output.psd";

using (var image = (PsdImage)Image.Load(sourceFilePath))
{
    ResourceBlock[] imageResources = image.ImageResources;
    BorderInformationResource borderInfoResource = null;
    foreach (var imageResource in imageResources)
    {
        if (imageResource is BorderInformationResource)
        {
            borderInfoResource = (BorderInformationResource)imageResource;
            break;
        }
    }

    // aggiorna BorderInformationResource
    borderInfoResource.Width = 0.1;
    borderInfoResource.Unit = PhysicalUnit.Inches;

    image.Save(outputFilePath);
}
```

### Guarda anche

* class [BorderInformationResource](../)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Resources](../../borderinformationresource/)
* assemblea [Aspose.PSD](../../../)


