---
title: "BackgroundColorResource.MinimalVersion"
second_title: "Aspose.PSD för .NET API‑referens"
description: "BackgroundColorResource egenskap. Hämtar den minsta erforderliga PSD-versionen"
type: docs
weight: 40
url: /sv/net/aspose.psd.fileformats.psd.resources/backgroundcolorresource/minimalversion/
---
{{< psd/tize >}}
## BackgroundColorResource.MinimalVersion property

Hämtar den minsta erforderliga PSD-versionen.

```csharp
public override int MinimalVersion { get; }
```

### Property Value

Den minsta PSD-versionen.

## Exempel

Följande exempel demonstrerar stödet för BackgroundColorResource-resursen.

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
* namespace [Aspose.PSD.FileFormats.Psd.Resources](../../../aspose.psd.fileformats.psd.resources/)
* assembly [Aspose.PSD](../../../)


