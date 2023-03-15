---
title: BackgroundColorResource.Color
second_title: Aspose.PSD för .NET API-referens
description: BackgroundColorResource fast egendom. Hämtar eller ställer in bakgrundsfärgen.
type: docs
weight: 20
url: /sv/net/aspose.psd.fileformats.psd.resources/backgroundcolorresource/color/
---
## BackgroundColorResource.Color property

Hämtar eller ställer in bakgrundsfärgen.

```csharp
public Color Color { get; set; }
```

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

* struct [Color](../../../aspose.psd/color/)
* class [BackgroundColorResource](../)
* namnutrymme [Aspose.PSD.FileFormats.Psd.Resources](../../backgroundcolorresource/)
* hopsättning [Aspose.PSD](../../../)


