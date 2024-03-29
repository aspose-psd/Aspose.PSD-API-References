---
title: BorderInformationResource.Unit
second_title: Aspose.PSD per riferimento API .NET
description: BorderInformationResource proprietà. Ottiene o imposta le unità del bordo.
type: docs
weight: 40
url: /it/net/aspose.psd.fileformats.psd.resources/borderinformationresource/unit/
---
## BorderInformationResource.Unit property

Ottiene o imposta le unità del bordo.

```csharp
public PhysicalUnit Unit { get; set; }
```

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

* enum [PhysicalUnit](../../../aspose.psd.fileformats.psd.resources.resolutionenums/physicalunit/)
* class [BorderInformationResource](../)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Resources](../../borderinformationresource/)
* assemblea [Aspose.PSD](../../../)


