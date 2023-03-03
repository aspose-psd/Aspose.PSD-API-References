---
title: BackgroundColorResource.Color
second_title: Aspose.PSD untuk Referensi .NET API
description: BackgroundColorResource Properti. Mendapat atau mengatur warna latar belakang.
type: docs
weight: 20
url: /id/net/aspose.psd.fileformats.psd.resources/backgroundcolorresource/color/
---
## BackgroundColorResource.Color property

Mendapat atau mengatur warna latar belakang.

```csharp
public Color Color { get; set; }
```

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

* struct [Color](../../../aspose.psd/color/)
* class [BackgroundColorResource](../)
* ruang nama [Aspose.PSD.FileFormats.Psd.Resources](../../backgroundcolorresource/)
* perakitan [Aspose.PSD](../../../)


