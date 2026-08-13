---
title: "SoCoResource.Color"
second_title: "Aspose.PSD for .NET API Referansı"
description: "SoCoResource özelliği. RGB rengini alır"
type: docs
weight: 20
url: /tr/net/aspose.psd.fileformats.psd.layers.layerresources/socoresource/color/
---
{{< psd/tize >}}
## SoCoResource.Color property

RGB rengini alır.

```csharp
public Color Color { get; set; }
```

### Dönüş Değeri

RGB Rengi

## Örnekler

Aşağıdaki örnek, SoCoResource'ı (Renk Doldurma Katmanı için Katman Kaynağı) nasıl düzenleyeceğinizi gösterir

```csharp
[C#]

string sourceFile = "ColorFillLayer.psd";
string outputFile = "SoCoResource_Edited.psd";

// Mevcut bir görüntüyü PsdImage sınıfının bir örneğine yükle
var im = (PsdImage)Image.Load(sourceFile);

using (im)
{
    foreach (var layer in im.Layers)
    {
        // FillLayer bulunması
        if (layer is FillLayer)
        {
            var fillLayer = (FillLayer)layer;
            foreach (var resource in fillLayer.Resources)
            {
                // Katman Kaynak Listesinde SoCoResource bulunması
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

                    // SoCoResource Renk özelliğini ayarlama
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

### Ayrıca Bakınız

* struct [Color](../../../aspose.psd/color/)
* class [SoCoResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


