---
title: BackgroundColorResource.Color
second_title: Aspose.PSD voor .NET API-referentie
description: BackgroundColorResource eigendom. Krijgt of stelt de achtergrondkleur in.
type: docs
weight: 20
url: /nl/net/aspose.psd.fileformats.psd.resources/backgroundcolorresource/color/
---
## BackgroundColorResource.Color property

Krijgt of stelt de achtergrondkleur in.

```csharp
public Color Color { get; set; }
```

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

* struct [Color](../../../aspose.psd/color/)
* class [BackgroundColorResource](../)
* naamruimte [Aspose.PSD.FileFormats.Psd.Resources](../../backgroundcolorresource/)
* montage [Aspose.PSD](../../../)


