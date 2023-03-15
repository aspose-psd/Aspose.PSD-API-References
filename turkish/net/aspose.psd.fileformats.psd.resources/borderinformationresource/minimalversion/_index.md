---
title: BorderInformationResource.MinimalVersion
second_title: Aspose.PSD for .NET API Referansı
description: BorderInformationResource mülk. Gereken minimum PSD sürümünü alır.
type: docs
weight: 30
url: /tr/net/aspose.psd.fileformats.psd.resources/borderinformationresource/minimalversion/
---
## BorderInformationResource.MinimalVersion property

Gereken minimum PSD sürümünü alır.

```csharp
public override int MinimalVersion { get; }
```

### Mülk değeri

Minimum PSD sürümü.

### Örnekler

Aşağıdaki örnek, BorderInformationResource kaynağının desteğini göstermektedir.

```csharp
[C#]

string sourceFilePath = "input.psd";
string outputFilePath = "output.psd";

using (var image = (PsdImage)Image.Load(sourceFilePath))
{
    ResourceBlock[] imageResources = image.ImageResources;
    BorderInformationResource borderInfoResource = null;
    foreach (var imageResource in imageResources)
    {
        if (imageResource is BorderInformationResource)
        {
            borderInfoResource = (BorderInformationResource)imageResource;
            break;
        }
    }

    // BorderInformationResource'u güncelle
    borderInfoResource.Width = 0.1;
    borderInfoResource.Unit = PhysicalUnit.Inches;

    image.Save(outputFilePath);
}
```

### Ayrıca bakınız

* class [BorderInformationResource](../)
* ad alanı [Aspose.PSD.FileFormats.Psd.Resources](../../borderinformationresource/)
* toplantı [Aspose.PSD](../../../)


