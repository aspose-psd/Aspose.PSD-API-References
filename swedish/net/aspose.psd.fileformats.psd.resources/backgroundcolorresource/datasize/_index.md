---
title: BackgroundColorResource.DataSize
second_title: Aspose.PSD för .NET API-referens
description: BackgroundColorResource fast egendom. Hämtar resursdatastorleken i byte.
type: docs
weight: 30
url: /sv/net/aspose.psd.fileformats.psd.resources/backgroundcolorresource/datasize/
---
## BackgroundColorResource.DataSize property

Hämtar resursdatastorleken i byte.

```csharp
public override int DataSize { get; }
```

### Fastighetsvärde

Resursdatastorleken.

### Exempel

Följande exempel visar stödet för BackgroundColorResource-resursen.

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

    // uppdatera BackgroundColorResource
    backgroundColorResource.Color = Color.DarkRed;

    image.Save(outputFilePath);
}
```

### Se även

* class [BackgroundColorResource](../)
* namnutrymme [Aspose.PSD.FileFormats.Psd.Resources](../../backgroundcolorresource/)
* hopsättning [Aspose.PSD](../../../)


