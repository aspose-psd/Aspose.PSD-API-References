---
title: BackgroundColorResource.DataSize
second_title: Aspose.PSD voor .NET API-referentie
description: BackgroundColorResource eigendom. Haalt de gegevensgrootte van de bron op in bytes.
type: docs
weight: 30
url: /nl/net/aspose.psd.fileformats.psd.resources/backgroundcolorresource/datasize/
---
## BackgroundColorResource.DataSize property

Haalt de gegevensgrootte van de bron op in bytes.

```csharp
public override int DataSize { get; }
```

### Eigendoms-waarde

De grootte van de brongegevens.

### Voorbeelden

In het volgende voorbeeld wordt de ondersteuning van de BackgroundColorResource-resource gedemonstreerd.

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

    // update BackgroundColorResource
    backgroundColorResource.Color = Color.DarkRed;

    image.Save(outputFilePath);
}
```

### Zie ook

* class [BackgroundColorResource](../)
* naamruimte [Aspose.PSD.FileFormats.Psd.Resources](../../backgroundcolorresource/)
* montage [Aspose.PSD](../../../)


