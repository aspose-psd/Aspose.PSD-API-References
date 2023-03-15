---
title: IGradientFillSettings.Scale
second_title: Aspose.PSD for .NET API Referansı
description: IGradientFillSettings mülk. Ölçeği alır veya ayarlar.
type: docs
weight: 100
url: /tr/net/aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/scale/
---
## IGradientFillSettings.Scale property

Ölçeği alır veya ayarlar.

```csharp
public int Scale { get; set; }
```

### Mülk değeri

Ölçek.

### Örnekler

Aşağıdaki örnek, FillLayer'ı degradeyle ölçeklendirmek için Scale özelliğinin nasıl kullanılacağını gösterir.

```csharp
[C#]

string sourceFileName = "FillLayerGradient.psd";
string output = "scaledImage.png";

using (var image = (PsdImage)Image.Load(sourceFileName))
{
    // bir dolgu katmanı elde ediyoruz
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

    // ölçek değerini güncelle
    settings.Scale = 200;
    fillLayer.Update(); // Piksel verilerini günceller

    image.Save(output, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### Ayrıca bakınız

* interface [IGradientFillSettings](../)
* ad alanı [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../igradientfillsettings/)
* toplantı [Aspose.PSD](../../../)


