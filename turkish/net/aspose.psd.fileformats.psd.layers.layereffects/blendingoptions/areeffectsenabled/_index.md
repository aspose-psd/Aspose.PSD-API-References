---
title: "BlendingOptions.AreEffectsEnabled"
second_title: "Aspose.PSD for .NET API Referansı"
description: "BlendingOptions özelliği. Tüm katman etkilerinin görünürlüğünü alır veya ayarlar"
type: docs
weight: 10
url: /tr/net/aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/areeffectsenabled/
---
{{< psd/tize >}}
## BlendingOptions.AreEffectsEnabled property

Tüm katman efektlerinin görünürlüğünü alır veya ayarlar.

```csharp
public bool AreEffectsEnabled { get; set; }
```

## Örnekler

AreEffectsEnabled özelliğini kullanarak katman etkilerini nasıl etkinleştireceğinizi veya devre dışı bırakacağınızı gösterir

```csharp
[C#]

string srcFile = "2485.psd";
string outputOnFile = "on_2485.png";
string outputOffFile = "off_2485.png";

using (var psdImage = (PsdImage)Image.Load(srcFile, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    psdImage.Save(outputOnFile);

    psdImage.Layers[1].BlendingOptions.AreEffectsEnabled = false;

    psdImage.Save(outputOffFile);
}
```

### Ayrıca Bakınız

* class [BlendingOptions](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)


