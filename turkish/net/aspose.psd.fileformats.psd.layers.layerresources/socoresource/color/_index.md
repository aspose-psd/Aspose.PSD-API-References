---
title: SoCoResource.Color
second_title: Aspose.PSD for .NET API Referansı
description: SoCoResource mülk. RGB rengini alır .
type: docs
weight: 20
url: /tr/net/aspose.psd.fileformats.psd.layers.layerresources/socoresource/color/
---
## SoCoResource.Color property

RGB rengini alır .

```csharp
public Color Color { get; set; }
```

### Geri dönüş değeri

RGB Rengi

### Örnekler

Aşağıdaki örnek, SoCoResource'u (Renk Dolgu Katmanı için Katman Kaynağı) nasıl düzenlediğinizi göstermektedir.

```csharp
[C#]

string sourceFile = "ColorFillLayer.psd";
string outputFile = "SoCoResource_Edited.psd";

// Varolan bir görüntüyü PsdImage sınıfının bir örneğine yükleyin
var im = (PsdImage)Image.Load(sourceFile);

using (im)
{
    foreach (var layer in im.Layers)
    {
        // FillLayer'ın Bulunması
        if (layer is FillLayer)
        {
            var fillLayer = (FillLayer)layer;
            foreach (var resource in fillLayer.Resources)
            {
                // Katman Kaynak Listesinde SoCoResource'un Bulunması
                if (resource is SoCoResource)
                {
                    var socoResource = (SoCoResource)resource;
                    var expectedColor = Color.FromArgb(63, 83, 141);
                    
                    if ((expectedColor.R != socoResource.Color.R) ||
                        (expectedColor.G != socoResource.Color.G) ||
                        (expectedColor.B != socoResource.Color.B) ||
                        (expectedColor.A != socoResource.Color.A))
                    {
                        throw new Exception("Unexpected color");
                    }

                    // SoCoResource Color özelliğinin ayarlanması
                    socoResource.Color = Color.Red;
                    break;
                }
            }
            break;
        }
        im.Save(outputFile);
    }
}
```

### Ayrıca bakınız

* struct [Color](../../../aspose.psd/color/)
* class [SoCoResource](../)
* ad alanı [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../socoresource/)
* toplantı [Aspose.PSD](../../../)


