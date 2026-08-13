---
title: "BackgroundColorResource.MinimalVersion"
second_title: "Aspose.PSD for .NET API Referansı"
description: "BackgroundColorResource özelliği. Minimum gerekli PSD sürümünü alır"
type: docs
weight: 40
url: /tr/net/aspose.psd.fileformats.psd.resources/backgroundcolorresource/minimalversion/
---
{{< psd/tize >}}
## BackgroundColorResource.MinimalVersion property

Gerekli minimum PSD sürümünü alır.

```csharp
public override int MinimalVersion { get; }
```

### Property Value

Minimum PSD sürümü.

## Örnekler

Aşağıdaki örnek, BackgroundColorResource kaynağının desteğini gösterir.

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

    // BackgroundColorResource güncelle
    backgroundColorResource.Color = Color.DarkRed;

    image.Save(outputFilePath);
}
```

### Ayrıca Bakınız

* class [BackgroundColorResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Resources](../../../aspose.psd.fileformats.psd.resources/)
* assembly [Aspose.PSD](../../../)


