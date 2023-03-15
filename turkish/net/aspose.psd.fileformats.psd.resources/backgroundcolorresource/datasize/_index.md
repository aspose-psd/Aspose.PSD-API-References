---
title: BackgroundColorResource.DataSize
second_title: Aspose.PSD for .NET API Referansı
description: BackgroundColorResource mülk. Kaynak veri boyutunu bayt cinsinden alır.
type: docs
weight: 30
url: /tr/net/aspose.psd.fileformats.psd.resources/backgroundcolorresource/datasize/
---
## BackgroundColorResource.DataSize property

Kaynak veri boyutunu bayt cinsinden alır.

```csharp
public override int DataSize { get; }
```

### Mülk değeri

Kaynak veri boyutu.

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


