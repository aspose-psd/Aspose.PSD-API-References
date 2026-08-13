---
title: "IGradientFillSettings.Scale"
second_title: "Aspose.PSD for .NET API Referansı"
description: "IGradientFillSettings özelliği. Normalleştirilmiş degrade ölçeğini yüzde olarak alır veya ayarlar"
type: docs
weight: 90
url: /tr/net/aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/scale/
---
{{< psd/tize >}}
## IGradientFillSettings.Scale property

Yüzde olarak **normalized** gradyan ölçeğini alır veya ayarlar.

```csharp
public int Scale { get; set; }
```

### Property Value

Ölçek.

## Örnekler

Aşağıdaki örnek, Scale özelliğini kullanarak FillLayer'ı degrade ile ölçeklendirmeyi gösterir.

```csharp
[C#]

string sourceFileName = "FillLayerGradient.psd";
string output = "scaledImage.png";

using (var image = (PsdImage)Image.Load(sourceFileName))
{
    // fill layer alınıyor
    FillLayer fillLayer = null;
    foreach (var layer in image.Layers)
    {
        fillLayer = layer as FillLayer;
        if (fillLayer != null)
        {
            break;
        }
    }

    var settings = fillLayer.FillSettings as IGradientFillSettings;

    // scale değerini güncelle
    settings.Scale = 200;
    fillLayer.Update(); // Updates pixels data

    image.Save(output, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### Ayrıca Bakınız

* interface [IGradientFillSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../../)


