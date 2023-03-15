---
title: VibAResource.Save
second_title: Aspose.PSD for .NET API Referansı
description: VibAResource yöntem. Kaynağı belirtilen akış kapsayıcısına kaydeder.
type: docs
weight: 70
url: /tr/net/aspose.psd.fileformats.psd.layers.layerresources/vibaresource/save/
---
## VibAResource.Save method

Kaynağı belirtilen akış kapsayıcısına kaydeder.

```csharp
public override void Save(StreamContainer streamContainer, int psdVersion)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| streamContainer | StreamContainer | Kaydedilecek akış kapsayıcısı. |
| psdVersion | Int32 | PSD versiyonu. |

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

* class [StreamContainer](../../../aspose.psd/streamcontainer/)
* class [VibAResource](../)
* ad alanı [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../vibaresource/)
* toplantı [Aspose.PSD](../../../)


