---
title: BackgroundColorResource.DataSize
second_title: Aspose.PSD untuk Referensi .NET API
description: BackgroundColorResource Properti. Mendapatkan ukuran data sumber daya dalam byte.
type: docs
weight: 30
url: /id/net/aspose.psd.fileformats.psd.resources/backgroundcolorresource/datasize/
---
## BackgroundColorResource.DataSize property

Mendapatkan ukuran data sumber daya dalam byte.

```csharp
public override int DataSize { get; }
```

### Nilai properti

Ukuran data sumber daya.

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


