---
title: BackgroundColorResource.MinimalVersion
second_title: Aspose.PSD untuk Referensi .NET API
description: BackgroundColorResource Properti. Mendapatkan versi PSD minimal yang diperlukan.
type: docs
weight: 40
url: /id/net/aspose.psd.fileformats.psd.resources/backgroundcolorresource/minimalversion/
---
## BackgroundColorResource.MinimalVersion property

Mendapatkan versi PSD minimal yang diperlukan.

```csharp
public override int MinimalVersion { get; }
```

### Nilai properti

Versi PSD minimal.

### Contoh

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

### Lihat juga

* class [BackgroundColorResource](../)
* ruang nama [Aspose.PSD.FileFormats.Psd.Resources](../../backgroundcolorresource/)
* perakitan [Aspose.PSD](../../../)


