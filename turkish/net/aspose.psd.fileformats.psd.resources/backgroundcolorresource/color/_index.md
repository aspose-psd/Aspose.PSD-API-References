---
title: "BackgroundColorResource.Color"
second_title: "Aspose.PSD for .NET API Referansı"
description: "BackgroundColorResource özelliği. Arka plan rengini alır veya ayarlar"
type: docs
weight: 20
url: /tr/net/aspose.psd.fileformats.psd.resources/backgroundcolorresource/color/
---
{{< psd/tize >}}
## BackgroundColorResource.Color property

Arka plan rengini alır veya ayarlar.

```csharp
public Color Color { get; set; }
```

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

* struct [Color](../../../aspose.psd/color/)
* class [BackgroundColorResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Resources](../../../aspose.psd.fileformats.psd.resources/)
* assembly [Aspose.PSD](../../../)


