---
title: FilterEffectMaskData.FilterEffectMaskData
second_title: Aspose.PSD for .NET API Referansı
description: FilterEffectMaskData inşaatçı. Yeni bir örneğini başlatır.FilterEffectMaskData sınıf.
type: docs
weight: 10
url: /tr/net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/filtereffectmaskdata/
---
## FilterEffectMaskData constructor

Yeni bir örneğini başlatır.[`FilterEffectMaskData`](../) sınıf.

```csharp
public FilterEffectMaskData(string guid, Rectangle rectangle, int pixelsDepth, int maxChannels, 
    ChannelInformation[] channels, ChannelInformation userMask, Rectangle maskRectangle, 
    ChannelInformation sheetMask)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| guid | String | Kaynak kılavuzu. |
| rectangle | Rectangle | Kanallar dikdörtgen. |
| pixelsDepth | Int32 | Piksel derinliği. |
| maxChannels | Int32 | Maksimum kanal değeri. |
| channels | ChannelInformation[] | kanallar |
| userMask | ChannelInformation | Kullanıcı maskesi. |
| maskRectangle | Rectangle | Sayfa maskesi dikdörtgeni. |
| sheetMask | ChannelInformation | Yaprak maskesi. |

### Örnekler

Bu örnek, FXidResource kaynağının özelliklerinin nasıl alınacağını ve ayarlanacağını gösterir.

```csharp
[C#]

string inputFilePath = "psdnet414_3.psd";
string output = "out_psdnet414_3.psd";

int resLength = 1144;
int maskLength = 369;

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new FormatException(message ?? "Objects are not equal.");
    }
}

using (var psdImage = (PsdImage)Image.Load(inputFilePath))
{
    FXidResource fXidResource = (FXidResource)psdImage.GlobalLayerResources[3];

    AssertAreEqual(resLength, fXidResource.Length);
    foreach (var maskData in fXidResource.FilterEffectMasks)
    {
        AssertAreEqual(maskLength, maskData.Length);
    }

    psdImage.Save(output);
}

// kaydettikten sonra kontrol edin
using (var psdImage = (PsdImage)Image.Load(output))
{
    FXidResource fXidResource = (FXidResource)psdImage.GlobalLayerResources[3];

    AssertAreEqual(resLength, fXidResource.Length);
    foreach (var maskData in fXidResource.FilterEffectMasks)
    {
        AssertAreEqual(maskLength, maskData.Length);
    }
}
```

### Ayrıca bakınız

* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [ChannelInformation](../../../aspose.psd.fileformats.psd.layers/channelinformation/)
* class [FilterEffectMaskData](../)
* ad alanı [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../filtereffectmaskdata/)
* toplantı [Aspose.PSD](../../../)


