---
title: "VibAResource.VibAResource"
second_title: "Aspose.PSD for .NET API Referansı"
description: "VibAResource yapıcı. VibAResource sınıfının yeni bir örneğini başlatır"
type: docs
weight: 10
url: /tr/net/aspose.psd.fileformats.psd.layers.layerresources/vibaresource/vibaresource/
---
{{< psd/tize >}}
## VibAResource constructor

Yeni bir [`VibAResource`](../) sınıf örneği başlatır.

```csharp
public VibAResource()
```

## Örnekler

Aşağıdaki kod örneği, VibAResource kaynağının desteğini gösterir.

```csharp
[C#]

// Çalışma zamanında okuma ve yazma Vibrasyon Kaynağı desteği örneği.
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

### Ayrıca Bakınız

* class [VibAResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


