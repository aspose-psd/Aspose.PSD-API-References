---
title: VibAResource.VibAResource
second_title: Aspose.PSD for .NET API Referansı
description: VibAResource inşaatçı. Yeni bir örneğini başlatır.VibAResource sınıf.
type: docs
weight: 10
url: /tr/net/aspose.psd.fileformats.psd.layers.layerresources/vibaresource/vibaresource/
---
## VibAResource constructor

Yeni bir örneğini başlatır.[`VibAResource`](../) sınıf.

```csharp
public VibAResource()
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


