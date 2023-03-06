---
title: BackgroundColorResource.MinimalVersion
second_title: Aspose.PSD voor .NET API-referentie
description: BackgroundColorResource eigendom. Krijgt de minimaal vereiste PSDversie.
type: docs
weight: 40
url: /nl/net/aspose.psd.fileformats.psd.resources/backgroundcolorresource/minimalversion/
---
## BackgroundColorResource.MinimalVersion property

Krijgt de minimaal vereiste PSD-versie.

```csharp
public override int MinimalVersion { get; }
```

### Eigendoms-waarde

De minimale PSD-versie.

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


