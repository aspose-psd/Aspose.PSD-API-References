---
title: "VibAResource.PsdVersion"
second_title: "Aspose.PSD for .NET API Referansı"
description: "VibAResource özelliği. psd sürümünü alır"
type: docs
weight: 40
url: /tr/net/aspose.psd.fileformats.psd.layers.layerresources/vibaresource/psdversion/
---
{{< psd/tize >}}
## VibAResource.PsdVersion property

PSD sürümünü alır.

```csharp
public override int PsdVersion { get; }
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


