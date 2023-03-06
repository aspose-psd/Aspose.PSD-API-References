---
title: BackgroundColorResource.Color
second_title: Aspose.PSD for .NET API Referansı
description: BackgroundColorResource mülk. Arka plan rengini alır veya ayarlar.
type: docs
weight: 20
url: /tr/net/aspose.psd.fileformats.psd.resources/backgroundcolorresource/color/
---
## BackgroundColorResource.Color property

Arka plan rengini alır veya ayarlar.

```csharp
public Color Color { get; set; }
```

### Örnekler

Aşağıdaki örnek, BackgroundColorResource kaynağının desteğini göstermektedir.

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

    // BackgroundColorResource'u güncelle
    backgroundColorResource.Color = Color.DarkRed;

    image.Save(outputFilePath);
}
```

### Ayrıca bakınız

* struct [Color](../../../aspose.psd/color/)
* class [BackgroundColorResource](../)
* ad alanı [Aspose.PSD.FileFormats.Psd.Resources](../../backgroundcolorresource/)
* toplantı [Aspose.PSD](../../../)


