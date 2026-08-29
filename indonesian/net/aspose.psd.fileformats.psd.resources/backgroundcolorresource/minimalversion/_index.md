---
title: "BackgroundColorResource.MinimalVersion"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Properti BackgroundColorResource. Mendapatkan versi PSD minimal yang diperlukan"
type: docs
weight: 40
url: /id/net/aspose.psd.fileformats.psd.resources/backgroundcolorresource/minimalversion/
---
{{< psd/tize >}}
## BackgroundColorResource.MinimalVersion property

Mendapatkan versi PSD minimal yang diperlukan.

```csharp
public override int MinimalVersion { get; }
```

### Property Value

Versi PSD minimal.

## Contoh

Contoh berikut menunjukkan dukungan sumber daya BackgroundColorResource.

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

    // perbarui BackgroundColorResource
    backgroundColorResource.Color = Color.DarkRed;

    image.Save(outputFilePath);
}
```

### Lihat Juga

* class [BackgroundColorResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Resources](../../../aspose.psd.fileformats.psd.resources/)
* assembly [Aspose.PSD](../../../)


