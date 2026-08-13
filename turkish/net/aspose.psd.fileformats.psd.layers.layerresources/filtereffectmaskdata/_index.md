---
title: "Sınıf FilterEffectMaskData"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.FilterEffectMaskData class. Filtre maske veri sınıfı"
type: docs
weight: 2740
url: /tr/net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/
---
{{< psd/tize >}}
## FilterEffectMaskData class

Filtre maskesi veri sınıfı.

```csharp
public sealed class FilterEffectMaskData
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [FilterEffectMaskData](filtereffectmaskdata/)(string, Rectangle, int, int, ChannelInformation[], ChannelInformation, Rectangle, ChannelInformation) | `FilterEffectMaskData` sınıfının yeni bir örneğini başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Channels](../../aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/channels/) { get; } | Kanalları alır. |
| [GUID](../../aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/guid/) { get; } | GUID'i alır. |
| [Length](../../aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/length/) { get; } | Filtre maske veri uzunluğunu bayt cinsinden alır. |
| [MaskRectangle](../../aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/maskrectangle/) { get; } | Sayfa maskesi dikdörtgenini alır. |
| [MaxChannels](../../aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/maxchannels/) { get; } | Kanal sayısının maksimumunu alır. |
| [PixelsDepth](../../aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/pixelsdepth/) { get; } | Piksel derinliğini alır. |
| [Rectangle](../../aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/rectangle/) { get; } | Kanalların dikdörtgenini alır. |
| [SheetMask](../../aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/sheetmask/) { get; } | Sayfa maskesini alır. |
| [UserMask](../../aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/usermask/) { get; } | Kullanıcı maskesini alır. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [SaveData](../../aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/savedata/)(StreamContainer) | Kaynağı belirtilen akış konteynerine kaydeder. |

## Örnekler

Bu örnek, FXidResource kaynağının özelliklerini nasıl alıp ayarlayacağını gösterir.

```csharp
[C#]

string inputFilePath = "psdnet414_3.psd";
string output = "out_psdnet414_3.psd";

int resLength = 1144;
long maskLength = 369;

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

// kaydetme sonrası kontrol et
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

### Ayrıca Bakınız

* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


