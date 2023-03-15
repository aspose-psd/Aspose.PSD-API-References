---
title: VibAResource.TypeToolKey
second_title: Aspose.PSD for .NET API Referansı
description: VibAResource alan. Tip aracı bilgi anahtarı.
type: docs
weight: 80
url: /tr/net/aspose.psd.fileformats.psd.layers.layerresources/vibaresource/typetoolkey/
---
## VibAResource.TypeToolKey field

Tip aracı bilgi anahtarı.

```csharp
public const int TypeToolKey;
```

### Örnekler

Aşağıdaki kod örneği, VibAResource kaynağının desteğini gösterir.

```csharp
[C#]

// Çalışma zamanında Titreşim Kaynağını okuma ve yazma desteği örneği.
string sourceFileName = "VibranceResource.psd";
string outputFileName = "out_VibranceResource.psd";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    foreach (var layer in image.Layers)
    {
        foreach (var resource in layer.Resources)
        {
            if (resource is VibAResource)
            {
                var vibranceResource = (VibAResource)resource;

                int vibranceValue =  vibranceResource.Vibrance;
                int saturationValue = vibranceResource.Saturation;

                vibranceResource.Vibrance = vibranceValue * 2;
                vibranceResource.Saturation = saturationValue * 2;

                break;
            }
        }
    }

    image.Save(outputFileName);
}
```

### Ayrıca bakınız

* class [VibAResource](../)
* ad alanı [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../vibaresource/)
* toplantı [Aspose.PSD](../../../)


