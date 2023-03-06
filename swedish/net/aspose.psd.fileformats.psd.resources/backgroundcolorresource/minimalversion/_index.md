---
title: BackgroundColorResource.MinimalVersion
second_title: Aspose.PSD för .NET API-referens
description: BackgroundColorResource fast egendom. Får den minsta nödvändiga PSDversionen.
type: docs
weight: 40
url: /sv/net/aspose.psd.fileformats.psd.resources/backgroundcolorresource/minimalversion/
---
## BackgroundColorResource.MinimalVersion property

Får den minsta nödvändiga PSD-versionen.

```csharp
public override int MinimalVersion { get; }
```

### Fastighetsvärde

Den minimala PSD-versionen.

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


