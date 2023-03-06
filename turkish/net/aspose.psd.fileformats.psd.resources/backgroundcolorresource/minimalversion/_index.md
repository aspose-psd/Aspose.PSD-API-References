---
title: BackgroundColorResource.MinimalVersion
second_title: Aspose.PSD for .NET API Referansı
description: BackgroundColorResource mülk. Gereken minimum PSD sürümünü alır.
type: docs
weight: 40
url: /tr/net/aspose.psd.fileformats.psd.resources/backgroundcolorresource/minimalversion/
---
## BackgroundColorResource.MinimalVersion property

Gereken minimum PSD sürümünü alır.

```csharp
public override int MinimalVersion { get; }
```

### Mülk değeri

Minimum PSD sürümü.

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

* class [BackgroundColorResource](../)
* ad alanı [Aspose.PSD.FileFormats.Psd.Resources](../../backgroundcolorresource/)
* toplantı [Aspose.PSD](../../../)


