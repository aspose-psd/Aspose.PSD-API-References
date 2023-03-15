---
title: BorderInformationResource.DataSize
second_title: Aspose.PSD for .NET API Referansı
description: BorderInformationResource mülk. Kaynak veri boyutunu bayt cinsinden alır.
type: docs
weight: 20
url: /tr/net/aspose.psd.fileformats.psd.resources/borderinformationresource/datasize/
---
## BorderInformationResource.DataSize property

Kaynak veri boyutunu bayt cinsinden alır.

```csharp
public override int DataSize { get; }
```

### Mülk değeri

Kaynak veri boyutu.

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


